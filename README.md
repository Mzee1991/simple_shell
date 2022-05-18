<p align="center">
  <img src="https://www.alxafrica.com/wp-content/uploads/2022/01/header-logo.png" alt="ALX Africa logo">
</p>

# Simple Shell Project 0x16.c - Sodash-

### Overview
`shell` is a UNIX command interpreter that replicates core functionalities of the `sh` shell.

### Installation
Clone this repository to your local system and compile using `gcc -Wall -Werror -Wextra -pedantic *.c`.

### Usage
* Once in the shell, use exactly like `sh`. A list of covered features is provided below. The shell can run in either interactive or non-interactive mode.
* Function returns with the specified exit status.

### Features
The shell handles command line input, including arguements, without the use of most standard library functions such as `printf`, `strtok`, or `getline`. In addition to running executables in the PATH, the following features are currently implemented.

|  Builtin Commands  |    Functionality                            |
| ------------------ | ------------------------------------------- |
| `exit [status]`    | Exit shell with specified exit status       |
| `env`              | Print list of current environment variables |
| `setenv`           | Set an environment variable                 |
| `unsetenv`         | Unset an environment variable               |
| `cd`               | Change directories                          |
| `history`			 | Prints command history					   |
| `help` 			 | Displays help for builtin commands		   |
| `alias`			 | Alias a command as another or print aliases |

|  Other Features    |    Functionality                            |
| ------------------ | ------------------------------------------- |
| `Ctrl-D`           | End of file - exit shell                    |
| `Ctrl-C`           | Does not exit shell - (Differs from `sh`)   |
| `;`                | Command separator, allows command chaining  |
| `#`                | Comment indicator                           |
| `<`				 | Redirect input							   |
| `>`				 | Redirect output							   |
| `<<`				 | Append input (heredoc)					   |
| `>>`				 | Append output							   |

### Example Usage
* This shell takes input the same as a standard unix shell.  After running the executable `hsh`, enter desired input and press return.
* `ls -l`
* `exit 98`
* `cd -`

### Release History
* 0.0.1 - First release - 07 May 2022
* 0.0.2 - Second release - 18 May 2022

### About
All files were created and compiled on `Ubuntu 20.04 LTS` using `GCC 4.8.4` with the following flags: `-Wall -Werror -Wextra -pedantic`

### Authors & Copyrights
* John Mzee [Github](https://github.com/Mzee1991)
* Derrick Mayiku Locha [Github](https://github.com/DeroMal)

## More information

**Sodash** is a simple shell unix command interpreter that is part of the alx low level programming module at ALX Software Engineering School and is intended to emulate the basics **sh** shell. All the information given in this README is based on the **sodash** and **bash** man (1) pages.
