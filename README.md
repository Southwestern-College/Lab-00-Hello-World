# Lab 00: Hello World
```
 __  __          ___    ___               __      __                 ___       __     
/\ \/\ \        /\_ \  /\_ \             /\ \  __/\ \               /\_ \     /\ \    
\ \ \_\ \     __\//\ \ \//\ \     ___    \ \ \/\ \ \ \    ___   _ __\//\ \    \_\ \   
 \ \  _  \  /'__`\\ \ \  \ \ \   / __`\   \ \ \ \ \ \ \  / __`\/\`'__\\ \ \   /'_` \  
  \ \ \ \ \/\  __/ \_\ \_ \_\ \_/\ \L\ \   \ \ \_/ \_\ \/\ \L\ \ \ \/  \_\ \_/\ \L\ \ 
   \ \_\ \_\ \____\/\____\/\____\ \____/    \ `\___x___/\ \____/\ \_\  /\____\ \___,_\
    \/_/\/_/\/____/\/____/\/____/\/___/      '\/__//__/  \/___/  \/_/  \/____/\/__,_ /                                                                                   
```

## Objectives

* Compile and run a Java application.
* Display output to console.

## Program Description

👋🏽 Hello world! In this lab you will create a program that displays a greeting message.

## Instructions

1. Open a new Codespace.
   1. Click the green "<> Code" button.
   2. Select "Codespaces".
   3. Click on the green "Create codespace on main" button. **‼️Be patient while the Codespace is being built‼️**
2. Create a new file named `HelloWorld.java`.
   1. In the *Explorer View* on the left, click on the *New File* icon or right-click and select *New File*
   2. Type `HelloWorld.java` and press enter.
3. Copy and paste the following example code into `HelloWorld.java`.

```java
public class ClassName {
    public static void main(String[] args) {
        System.out.println("Message");
    }
}
```

4. Change the class name to `HelloWorld`.
5. Modify the code inside `System.out.println` to displays the following message

```
Hello Math 130!
```

6. Run the program.

   * Click the play button on the top-right of the editor window or right-click the file and select **Run Java**.
7. Test the code

   1. Click on the  Erlenmeyer flask (cone flask) on the Activity Bar (left-hand navigation menu), which opens the Test view in the Primary Side Bar.
   2. Select ***Run Test*** from the Test view by hovering over the test (***Lab-00-Hello\_World***), which reveals a play button.
   3. If your code passes the test, a green checkmark will appear. If you see a red X, click on the expected message and investigate the differences.
8. Repeat steps 5 through 7 until all tests are passed.
9. Include a JavaDoc header comment at the top of your file using the `@author` tag with your full name.

Example:

```
/**
 * JavaDoc comment with your program description
 *
 * @author Firstname Lastname
 */
```

10. Commit and push your changes.

    1. Click on the Source Control icon (three interconnected circles) in the Activity Bar.
    2. Click on the plus sign next to the files you wish to commit.
    3. Enter a meaningful commit message.
    4. Click the Commit \& Push button. This sends your code to the GitHub repo, where I will be able to see your work.

## Specifications

Satisfy all of the following specifications to complete this lab.

* Program compiles and runs without errors.
* Program must display `Hello Math 130!` exactly.
* Source code includes comment with your name.
* Program is committed and pushed to your repository.

# Submit

Submit a link to you GitHub Repository on the Canvas assignment page for this lab (`https://github.com/Math-130/lab-00-your-username`). **Do not submit a link to your Codespace!**
