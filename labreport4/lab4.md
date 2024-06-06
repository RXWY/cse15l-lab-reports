Instructions:

Write down exactly which keys you pressed to get to that step, including <enter> and <space> (e.g., cd<space>L<tab><enter> or <down><down><down><down><down><down><down><enter>). For special characters like <enter> or <tab>, write them in angle brackets with code formatting.
Then, summarize the commands you ran and what the effect of those keypresses were.
For example, when you run the tests, you might want to use the up arrow or Ctrl-R to access your bash history rather than typing in the full command with classpath, etc. You might say something like this accompanying the screenshot for running the tests:

Keys pressed: <up><up><up><up><enter>, <up><up><up><up><enter> The javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java command was 4 up in the search history, so I used up arrow to access it. Then the java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ... command was 4 up in the history, so I accessed and ran it in the same way.





Commit and push the resulting change to your Github account (you can pick any commit message!)
Add this lab report to your Github Pages site, and submit a PDF of it as usual.
* Step 4 Log into ieng6
Keys pressed:
> ```ssh c9gaoWieng6.ucsd.edu <enter>``` to log in to my account.


![Image](https://rxwy.github.io/cse15l-lab-reports/labreport4/img/Screenshot1.png)

> ```ssh-keygen <enter?``` to generate a key for SSH cloning of lab7

![Image](https://rxwy.github.io/cse15l-lab-reports/labreport4/img/Screenshot2.png)

> ```cat /home/linux/ieng6/oce/69/769/c9gao/.ssh/id_rsa.pub <enter> <Ctrl+C>``` extracted the ssh authentication and then copy and paste it to the github site to set up personal SSH, then use that to clone lab7. 

![Image](https://rxwy.github.io/cse15l-lab-reports/labreport4/img/Screenshot3.png)
* Step 5 Clone your fork of the repository from your Github account (using the SSH URL)
> ```<Ctrl+V> <enter>``` cloned by github SSH using c+v.

![Image](https://rxwy.github.io/cse15l-lab-reports/labreport4/img/Screenshot4.png)

* Step 6 Run the tests, demonstrating that they fail
> ```cd lab7 <enter> javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java <enter> java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExampleTests <enter>``` Compile the entire thing by cd into the folder, then run the entire class in junit. Which returns error. 

![Image](https://rxwy.github.io/cse15l-lab-reports/labreport4/img/Screenshot7.png)

![Image](https://rxwy.github.io/cse15l-lab-reports/labreport4/img/Screenshot6.png)

* Step 7 Edit the code file to fix the failing test



![Image](https://rxwy.github.io/cse15l-lab-reports/labreport4/img/Screenshot5.png)
* Step 8 Run the tests, demonstrating that they now succeed

![Image](https://rxwy.github.io/cse15l-lab-reports/labreport4/img/Screenshot8.png)
* Step 9 Commit and push the resulting change to your Github account

![Image](https://rxwy.github.io/cse15l-lab-reports/labreport4/img/Screenshot9.png)

