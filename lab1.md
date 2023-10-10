[user@sahara ~]$ cd
[user@sahara ~]$ 
// returns nothing because there is no directory assigned
[user@sahara ~]$ cd lecture1
[user@sahara ~/lecture1]$ 
// goes to lecture1
[user@sahara ~]$ cd lecture1/Hello.java
bash: cd: lecture1/Hello.java: Not a directory
// the file is not a directory
[user@sahara ~]$ ls
lecture1
//list out that under main there is lecture1
[user@sahara ~]$ ls lecture1
Hello.class  Hello.java  messages  README
//shows the file under lecture1
[user@sahara ~]$ ls lecture1/Hello.java
lecture1/Hello.java
//under the file its the file itself
[user@sahara ~]$ cat lecture1
cat: lecture1: Is a directory
// shows that lecture1 is a directory but not file
[user@sahara ~]$ cat lecture1/Hello.java
import java.io.IOException;
import java.nio.charset.StandardCharsets;
import java.nio.file.Files;
import java.nio.file.Path;

public class Hello {
  public static void main(String[] args) throws IOException {
    String content = Files.readString(Path.of(args[0]), StandardCha
rsets.UTF_8);    
    System.out.println(content);
  }
}
// Reads the file content
[user@sahara ~]$ cat
// Run into weird stuff because nothing is assigned
