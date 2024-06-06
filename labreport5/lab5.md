
# Part 1 - A Debugging Scenario
![Image](https://rxwy.github.io/cse15l-lab-reports/labreport5/img/piazzapost.PNG)
![Image](https://rxwy.github.io/cse15l-lab-reports/labreport5/img/piazzascreen.PNG)
![Image](https://rxwy.github.io/cse15l-lab-reports/labreport5/img/piazzadesc.PNG)
![Image](https://rxwy.github.io/cse15l-lab-reports/labreport5/img/piazzasolu2.PNG)
Student's reply:
> Thank you! I noticed that the file is located in a different directory under the parent directory. I also recalled that in order to run a java class file with a designated path, I should use ```java -cp```! After going to the parent directory(It is where the textfile directory is located under!) by using the command ```cd ../``` I attempted to run Code class with its path as shown in the screenshot, and it worked! The bug was a display of ```The file does not exist :(```despite the file exists under the directory ```textfile/novels/Kobo.txt```. The code triggered such bug is ```java Code textfile/novels/Koko.txt``` the machine failed to find the path under the current directory, and I solved it by first change directory to it's parent directory and then run the Code class using -cp (As shown in the screenshot below), the Code.java file was unchanged as it works properly before and after debugging! 

![Image](https://rxwy.github.io/cse15l-lab-reports/labreport5/img/student.PNG)


# Part 2

In a couple of sentences, describe something you learned from your lab experience in the second half of this quarter that you didn't know before. It could be a technical topic we addressed specifically, something cool you found out on your own building on labs, something you learned from a tutor or classmate, and so on. It doesn't have to be specifically related to a lab writeup, we just want to hear about cool things you learned!
