
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
> ```vim <down><down><down><enter> <up><up><up><up><up><up><up><up><up><up><up><x><x> <down><down><down><down><down><down><down><down><down><down><down><down><x><i> <:wq>``` By doing this I fixed all the errors in the code.


![Image](https://rxwy.github.io/cse15l-lab-reports/labreport4/img/Screenshot5.png)
* Step 8 Run the tests, demonstrating that they now succeed

![Image](https://rxwy.github.io/cse15l-lab-reports/labreport4/img/Screenshot8.png)
* Step 9 Commit and push the resulting change to your Github account

![Image](https://rxwy.github.io/cse15l-lab-reports/labreport4/img/Screenshot9.png)

