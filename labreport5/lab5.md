
# Part 1 - A Debugging Scenario
![Image](https://rxwy.github.io/cse15l-lab-reports/labreport5/img/piazzapost.PNG)
![Image](https://rxwy.github.io/cse15l-lab-reports/labreport5/img/piazzascreen.PNG)
![Image](https://rxwy.github.io/cse15l-lab-reports/labreport5/img/piazzadesc.PNG)
![Image](https://rxwy.github.io/cse15l-lab-reports/labreport5/img/piazzasolu2.PNG)
Student's reply:
> Thank you! I noticed that the file is located in a different directory under the parent directory. I also recalled that in order to run a java class file with a designated path, I should use ```java -cp```! After going to the parent directory(It is where the textfile directory is located under!) by using the command ```cd ../``` I attempted to run Code class with its path as shown in the screenshot, and it worked! The bug was a display of ```The file does not exist :(```despite the file exists under the directory ```textfile/novels/Kobo.txt```. The code triggered such bug is ```java Code textfile/novels/Koko.txt``` the machine failed to find the path under the current directory, and I solved it by first change directory to it's parent directory by ```cd ../``` and then run the Code class using -cp (As shown in the screenshot below), the Code.java file(the whole code segment displayed in the screenshot above) was unchanged as it works properly before and after debugging! 

![Image](https://rxwy.github.io/cse15l-lab-reports/labreport5/img/student.PNG)


# Part 2

My experience:
> Thank you for providing an amazing quarter of CSE15L! I have learned so much about the techniques in debugging(JUnit!) and file management, from the basics like creating files and locating paths using bash to understanding a directory/file structure. In fact, I learned even more in the 2nd half of this class, such as VIM; I find it so cool because of how it could run smoothly on a terminal text box and experience compiling codes in an old-fashioned and without modern, super graphical clients. I also found out that my classmates have quite diverse computer science background and journey, some learning for software engineering, some for bioinformatics, and some for AI... 
