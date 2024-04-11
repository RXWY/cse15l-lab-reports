# Lab Report 1
* *Absolute paths are obtained by executing `pwd` in the terminal*
  
*The images below demonstrates what will happen when cd/ls/cat are used*

![Image](https://rxwy.github.io/cse15l-lab-reports/labreport1/img/cd.png)
> **Description**

> The absolute path before the following command is **/c/Users/gaoch**
* When cd(change directory) without an argument, it returns to the broadest directory on local machine.\
> The absolute path before the following command is **/c/Users/gaoch**
* When cd is used with a directory **(cd lecture1)**, the terminal updates the directory specified.\
> The absolute path before the following command is **/c/Users/gaoch/lecture1**
* When cd is used with a file name **(cd Hello.class)**, the terminal returns an error since the object that is being changed to is not a directory.\
  * Error message: `bash: cd: Hello.java: Not a directory`


![Image](https://rxwy.github.io/cse15l-lab-reports/labreport1/img/ls.png)
> **Description**
* When ls(list) without an argument, it means to list items under the main/highest level of the directory.
* When ls is used with a directory **(ls messages/)**, it outputs every file under that directory.
* When ls is used with a file name **(ls Hello.java)**, it returns the filename, indicating that there is only one file(itself) under that name. 

![Image](https://rxwy.github.io/cse15l-lab-reports/labreport1/img/cat.png)
> **Description**
> Comment: When cat was run w/o arguments, the terminal stops executing any other code.

* When cat(concatenate) without an argument, it generates an error, which the terminal awaits file input, concatenating 0 files.
* When cat is used with a directory **(cat lecture1)**, the terminal updates the directory specified.
* When cat is used with a file name **(cat Hello.class)**, the terminal returns an error since the object that is being changed to is not a directory.
  
