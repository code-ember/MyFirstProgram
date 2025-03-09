# MyFirstProgram
A simple Java program

## INTRODUCTION
In this lab, you will write your very first Java program. Java is a really versatile programming language that's used to create all sorts of applications, from mobile apps to games. Don't worry if you've never written code before - you will be guided through every step, and by the end of this lab, you'll have written your own Java program. Let's get started!
You're going to write a program that prints a message to the screen. This is the first traditional program in many programming languages. But first, you need to create a space to put the code you want to run. Java code lives in files called classes, so you need to create one of those.

## CREATE A NEW PROJECT
STEP 1:  Start by launching IntelliJ on your machine. Locate the IntelliJ icon on your desktop and double click on it. 

STEP 2: To create a new program in IntelliJ, select the *New Project* option on the top right-hand corner of the welcome screen.

STEP 3: You'll be prompted to choose the type of project you want to create. Insert the  following information:
- *Name*: Enter “*Java_Project*”.
- *Location*: Browse through the location where you want to save the project. It’s best to just leave this to the default location.
- *Build system*: Select *IntelliJ*.
- *JDK*: Select *21* from the dropdown menu.
- Uncheck the box for *Add a sample code*.
- Leave the rest of the settings and select *Create*

STEP 4: The next step is to create a new Java class file in your *Java_Project* project. A class is like a blueprint for objects in Java, but you will learn more about this later. On the left side of the screen in the project structure panel, open your *Java_Project* folder and right-click on the *src* folder icon. Next, select *New > Java Class*.

STEP 5: You will get a pop-up window with options. Name your class “*MyFirstProgram*” and press "Enter" on your keyboard.

STEP 6: Your file will have the following line of code when you open it: public class MyFirstProgram { }

STEP 7: Creating some space between those curly braces by pressing *Enter* a few times.

STEP 8: First, you are going to create the starting point for your program. You will write the *main* method, which is the starting point for every Java program. 
Type the following code: public static void main (String[] args) { }

STEP 9: Let’s add some code within the *main* method. Write a simple print statement that will print the text on the output screen. 
Type the following code: public static void main (String[] args) { System.out.println("I'm a Programmer"); }

STEP 10: Every program needs an end. You might notice that the class and the method starts and ends with curly braces.

public class MyFirstProgram { public static void main (String[] args) { System.out.println("I'm a Programmer"); } }

## TIPS
For Windows, use the Control (ctrl) key.
- Copy: Ctrl + C
- Paste: Ctrl + V

For Mac, use the Command (CMD) key.
- Copy: CMD + C
- Paste: CMD + V

## UNDERSTANDING THE CODE AND EXPLANATION
public class MyFirstProgram { }
- This defines a new class named *MyFirstProgram*

MyFirstProgram
- Name of new class

public static void main(String[] args) { }
- This is the main method. The program starts running from this method. All Java programs require this method, it acts as the starting point for your program, no matter how complex it gets, your program will always start in this method.

System.out.println("I’m a Programmer");
- This line prints "*I’m a Programmer*" to the *screen.System.out* is the instruction you gave to Java. Java reads this and knows that it has to use something called *System*, and something called out to print your message, *println* means "print line". These are built-in commands in Java. Anything you have placed inside the “ “ will get printed. 

## RUNNING YOUR PROGRAM
STEP 11: Before running the program, you need to compile it. Compiling means translating the code you wrote into a language the computer can understand. In your  Integrated Development Environment (IDE), there is a *Run* button (green triangle icon) in the menu at the top right-hand side of the screen. Select it to compile and run your program.

STEP 12: After selecting the *Run* button, an extra window will open on the screen and you will observe some code running at the bottom of your screen. This window is known as the *Console*. After running the program, you should receive *I’m a Programmer* printed on the console screen at the bottom.

## MORE EXPERIMENTING WITH THE CODE
Instead of printing "*I’m a Programmer*", let's print something else. Change the existing *System.out.println* statement to print some other output:
- System.out.println("Let’s change the code now…");

Run your program again. You should now receive the following printed on the screen.
- Let's change the code now...

Let's add another line to print a second message. Right below the first println statement, add:
- System.out.println("it’s what I do!");

Run your program again. You should now receive both messages printed on the screen.
- Let's change the code now... it's what I do!

## CONCLUSION
You've written your first Java program and changed it. Remember, programming is all about experimenting and learning from your mistakes. Don't be afraid to try new things and observe what happens. The more you practice, the better you'll get.

## Software Used: IntelliJ
