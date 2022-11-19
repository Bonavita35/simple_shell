# Simple Shell by Edward Ezeabasili and Augustine Ikenwa
## The Gates of Shell shall not prevail.

![alt text](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-low_level_programming/235/shell.jpeg)

### Description

Shell is a simple UNIX command interpreter that replicates functionalities of the simple shell (sh). Additional functions are also included. This program was written entirely in C as a milestone project for ALX Africa Software Engineering.

### Installation

Clone this repository into your working directory. For best results, files should be compiled with GCC and the following flags: -Wall -Wextra -Werror -pedantic -std=gnu89

### Usage

After compilation, the resulting program can run stand-alone, either in interactive or non-interactive mode.

#### Interactive Mode

In interactive mode, simply run the program and wait for the prompt to appear. From there, you can type commands freely, exiting with either the "exit" command or ctrl-D.

#### Non-Interactive Mode

In non-interactive mode, echo your desired command and pipe it into the program like this:

```sh
echo "ls" | ./shell
```

In non-interactive mode, the program will exit after finishing your desired command(s).

#### Included Built-Ins

Our shell has support for the following built-in commands:

| Command             | Definition                                                                                |
| ------------------- | ----------------------------------------------------------------------------------------- |
| exit [n]            | Exit the shell, with an optional exit status, n.                                          |
| env                 | Print the environment.                                                                    |
| setenv [var][value] | Set an environment variable and value. If the variable exists, the value will be updated. |
| unsetenv [var]      | Remove an environment variable.                                                           |
| cd [dir]            | Change the directory.                                                                     |
| help [built-in]     | Read documentation for a built-in.                                                        |


### Authors
 Edward Ezeabasili: [GitHub](https://github.com/Bonavita35), [Twitter](https://twitter.com/experditus);
 Augustine Ikenwa: [GitHub](https://github.com/ikenwaa), [Twitter](https://twitter.com/im_ikenwa).