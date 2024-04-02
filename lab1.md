# Lab Report 1
The absolute path for the following commands is **/c/Users/gaoch/lecture1**\
*The image below demonstrates what will happen when cd/ls/cat are used without arguments*

![Image](https://rxwy.github.io/cse15l-lab-reports/woarg.png)

> Comment: When cat was run w/o arguments, the terminal stops executing any other code.

> **Description**
* Example 1: When cd(change directory) without an argument, it returns to the broadest directory on local machine.
* Example 2: When ls(list) without an argument, it means to list items under the main/highest level of the directory.
* Example 3: When cat(concatenate) without an argument, it means concatenating 0 files, which the terminal awaits file input.

![Image](https://rxwy.github.io/cse15l-lab-reports/cd.png)
> **Description**
* As mentioned earlier, *"When cd(change directory) without an argument, it returns to the broadest directory on local machine."*
* When cd is used with a directory **(cd lecture1)**, the terminal updates the directory specified.
* When cd is used with a file name **(cd Hello.class)**, the terminal returns an error since the object that is being changed to is not a directory.


![Image](https://rxwy.github.io/cse15l-lab-reports/ls.png)
> **Description**
* As mentioned earlier, *"When ls(list) without an argument, it means to list items under the main/highest level of the directory."*
* When ls is used with a directory **(ls messages/)**, it outputs every file under that directory.
* When ls is used with a file name **(ls Hello.java)**, it returns the filename, indicating that there is only one file(itself) under that name. 

