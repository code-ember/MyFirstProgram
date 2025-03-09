# My First Java Program

## Introduction
This project walks you through writing your very first **Java program**. Java is a versatile programming language used to create a wide range of applications, from mobile apps to games. If you're new to programming, don't worry! This guide provides a step-by-step approach to help you write, run, and modify your first program.

By the end of this project, you will have:
- Learned how to create and structure a Java project.
- Written a simple program that prints messages to the console.
- Experimented with modifying and running the program.

## Setting Up the Project

### Step 1: Create a New Project
1. Launch **IntelliJ IDEA** on your computer.
2. On the welcome screen, click **New Project**.
3. Enter the following details:
   - **Name**: `Java_Project`
   - **Location**: (Use the default or specify your folder.)
   - **Build System**: `IntelliJ`
   - **JDK**: `21`
4. Uncheck **Add a sample code**, then click **Create**.

### Step 2: Create a Java Class File
1. In the Project Structure panel on the left, locate your `Java_Project` folder.
2. Right-click the `src` folder, then select **New > Java Class**.
3. Name your class `MyFirstProgram` and press **Enter**.

### Step 3: Write Your First Program
1. Open the newly created `MyFirstProgram.java` file. You will see:
   ```java
   public class MyFirstProgram {
   
   }

2. Add the ```main``` method inside the class:
   ```java
   public static void main(String[] args) {
   
   }

3. Add a print statement within the ```main``` method to display a message:
   ```java
   public static void main(String[] args) {
       System.out.println("I'm a Programmer");
   }

4. Your final program should look like this:
   ```java
   public class MyFirstProgram {
       public static void main(String[] args) {
           System.out.println("I'm a Programmer");
       }
   }

## Running Your Program
1. Click the **Run** button (green triangle icon) at the top-right corner of IntelliJ to compile and execute your program.
2. The **Console** at the bottom of the IDE will display the message:
   ```java
   I'm a Programmer

## Experimenting with the Code
Try modifying the program by:
1. Printing a different message:
   ```java
   System.out.println("Let’s change the code now...");
   
2. Adding another line to print a second message:
   ```java
   System.out.println("It’s what I do!");

   
The output will look like this:
   ```plaintext
   Let’s change the code now...
   It’s what I do!
   ```
      
   

## Understanding the Code
- ```public class MyFirstProgram```: Declares a new class named MyFirstProgram.

- ```public static void main(String[] args)```: Defines the main method, which is the entry point of every Java program.

- ```System.out.println("...")```: Prints the specified message to the console.

## Conclusion
Congratulations on writing and running your first Java program! Programming is all about experimenting and learning from your mistakes. Keep practicing and exploring new concepts to improve your skills.

## Software Used
- IntelliJ IDEA
   

