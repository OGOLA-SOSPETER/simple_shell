# Simple Shell
-------------------------


### General requirements
 
   * Allowed editors: vi, vim, emacs
   * All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89
   * All your files should end with a new line
   * A README.md file, at the root of the folder of the project is mandatory
   * Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl
   * Your shell should not have any memory leaks
   * No more than 5 functions per file
   * All your header files should be include guarded
   * Use system calls only when you need to (why?)
   * Write a README with the description of your project
   * You should have an AUTHORS file at the root of your repository, listing all individuals having contributed content to the repository. Format, see Docker



### What is Shell
A **shell** is a command-line interpreter, it is the computer program that provides a user interface to access the services of the operating system. Depending on the type of interface they use, shells can be of various types, in this case, a shell program of the type **`sh`** ([Bourne Shell](https://en.wikipedia.org/wiki/Bourne_shell)) will be developed. Users typically interact with a shell using a [terminal emulator](https://en.wikipedia.org/wiki/Terminal_emulator) that is used for entering data into and displaying or printing data from, a computer or a computing system.

### What is it for
This consists of interpreting orders. It incorporates features such as process control, input/output redirection, law listing and reading, protection, communications, and a command language for writing batch programs or scripts. All Unix-type systems have at least one interpreter compatible with the Bourne shell. The Bourne shell program is found within the Unix file hierarchy at **`/bin/sh`**.

### Enviroment

<!-- ubuntu -->
<a href="https://ubuntu.com/" target="_blank"> <img height="" src="https://img.shields.io/static/v1?label=&message=Ubuntu&color=E95420&logo=Ubuntu&logoColor=E95420&labelColor=2F333A" alt="Suite CRM"></a> OS: Ubuntu 20.04 LTS
<!-- bash -->
<a href="https://www.gnu.org/software/bash/" target="_blank"> <img height="" src="https://img.shields.io/static/v1?label=&message=GNU%20Bash&color=4EAA25&logo=GNU%20Bash&logoColor=4EAA25&labelColor=2F333A" alt="terminal"></a>
<!-- c -->	
<a href="https://www.cprogramming.com/" target="_blank"><img src="https://img.shields.io/static/v1?label=&message=C%20Language&color=5C6BC0&logo=c&logoColor=A8B9CC&labelColor=2F333A" alt="C Low level programming language"></a> Language: C
Compiler: gcc 9.4.0 
<!-- vim -->
<a href="https://www.vim.org/" target="_blank"> <img height="" src="https://img.shields.io/static/v1?label=&message=Vim&color=019733&logo=Vim&logoColor=019733&labelColor=2F333A" alt="Suite CRM"></a> Editor: VIM 8.1.3741
<!-- git -->
<a href="https://git-scm.com/" target="_blank"> <img height="" src="https://img.shields.io/static/v1?label=&message=Git&color=F05032&logo=Git&logoColor=F05032&labelColor=2F333A" alt="git distributed version control system"></a> Control version: Git
<!-- github -->
<a href="https://github.com" target="_blank"> <img height="" src="https://img.shields.io/static/v1?label=&message=GitHub&color=181717&logo=GitHub&logoColor=f2f2f2&labelColor=2F333A" alt="Github"></a>

Style guidelines: [Betty style](https://github.com/holbertonschool/Betty/wiki)

### Installation

- Clone this repository: `git clone "https://github.com/OGOLA-SOSPETER/simple_shell"`
- Change directories into the repository: `cd simple_shell`
- Compile: `gcc -Wall -Werror -Wextra -pedantic *.c -o hsh`
- Run the shell in interactive mode: `./hsh`
- Or run the shell in non-interactive mode: example `echo "Hello world!" | ./hsh`

### Testing


 $ ls -l
 total 152
 -rw-r--r-- 1 root root   167 Aug 11 03:10 AUTHORS
 -rw-r--r-- 1 root root  3106 Aug  6 01:03 builtin_aliases.c
 -rw-r--r-- 1 root root  3458 Aug  6 01:03 builtins_more_helps.c
 -rw-r--r-- 1 root root  1167 Aug  6 01:03 buitins_helps.c
 -rw-r--r-- 1 root root  1809 Aug  6 02:31 custom_strings1.c
 -rw-r--r-- 1 root root  1955 Aug  6 02:30 custom_strings.c
 -rw-r--r-- 1 root root  3155 Aug  6 01:03 environ_builtins.c
 -rw-r--r-- 1 root root  1450 Aug  6 01:03 environ.c
 -rw-r--r-- 1 root root  1390 Aug  7 23:36 error_message1.c
 -rw-r--r-- 1 root root  3392 Aug  7 23:36 error_messages.c
 -rw-r--r-- 1 root root  2509 Aug 11 03:10 file_commands.c
 -rw-r--r-- 1 root root  2685 Aug  6 01:10 getline.c
 -rw-r--r-- 1 root root  3751 Aug  7 23:51 helpers2.c
 -rw-r--r-- 1 root root  4426 Aug  7 23:55 helpers3.c
 -rw-r--r-- 1 root root  3649 Aug  7 23:48 helpers.c
 -rwxr-xr-x 1 root root 45536 Aug 11 03:28 hsh
 -rw-r--r-- 1 root root  1643 Aug  7 23:36 len_itoa_err.c
 -rw-r--r-- 1 root root  2170 Aug 11 03:10 linkedlist.c
 -rw-r--r-- 1 root root  2624 Aug  6 01:24 locater.c
 -rw-r--r-- 1 root root  2531 Aug  6 01:03 main.c
 -rw-r--r-- 1 root root  4369 Aug 11 03:10 origbuiltin.c
 -rw-r--r-- 1 root root  3586 Aug 11 03:45 README.md
 -rw-r--r-- 1 root root  4372 Aug 11 03:18 shell.h
 drwxr-xr-x 2 root root   101 Aug 11 03:47 temp
 -rw-r--r-- 1 root root  2009 Aug  6 01:47 tokenizer.c
 $



## Authors

<li> Ogola Sospeter - <a href="https://github.com/OGOLA-SOSPETER">OGOLA-SOSPETER</a></li>
<li> Gabriel Musanga - <a href="https://github.com/gims-inc">gims-inc</a></li>
