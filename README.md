# JAVA
# What is java?

> Java is a popular programming language, created in 1995, Java is a highly popular, object-oriented programming language. Java independent programming language is utilized for Android development,web development, artificial intelligence, cloud applications, and much more.
> Java is a class-based, object-oriented programming language that is designed to have as few implementation dependencies as possible. It is intended to let application developers write once, and run anywhere(WORA), meaning that compiled Java code can run on all platforms that support Java without the need for recompilation. Java is widely used for developing applications for desktop, web, and mobile devices. Java is known for its simplicity, robustness, and security features, making it a popular choice for enterprise-level applications.

* Java was developed by James Gosling at Sun Microsystems_Inc in the year 1995 and later acquired by Oracle Corporation. It is a simple programming language. Java makes writing, compiling, and debugging programming easy. It helps to create reusable code and modular programs. Java is a class-based, object-oriented programming language and is designed to have as few implementation dependencies as possible. A general-purpose programming language made for developers to write once run anywhere that is compiled java code can run on all platforms that supports Java. Java applications are compiled to byte code that can run on any Java Virtual Machine. The syntax of Java is similar to c/c++.

  ## Implementation of java application program involves a following step:
  > Creating the program
  > Compiling the program
  > Running the program

   ## CREATING THE PROGRAM
  > We can create a program using Text Editor(VSCODE) OR IDE(NetBeans)
  class Test
  {
     public static void main(String[]args)
     {
        System.out.println("My first Java Program.");
       }
  };

  ## Compiling the program

  > To compile the program, we must run the Java compiler(javac), with the name of the source file on "command prompt" like as follows.
  * If everything is OK, the "javac" compiler creates a file called "Test.class" containing byte code of the program.

    ## Running the program

    > We need to use the Java Interpreter to run a program.

    ## Java Terminology

    > One must be familiar with these common terms of java:

    * Java Virtual Machine(JVM): This is generally referred to as "JVM". There are three execution phases of a program. They are written, compile and run the program.
      > Writing a program is done by a java programmer like you and me.
      > The complilation is done by the JAVAC compiler which is a primary Java compiler included in the Java development kit(JDK).It takes the program as input and generates bytecode as output.
      > In the Running phase of a program, JVM  executes the bytecode generated by the compiler.
      > As we understood that the function of Java Virtual Machine is to execute the bytecode produced by the compiler. Every Operating System has a different JVM but they produce after the execution of bytecode is the same across all the operating systems. This is why Java is known as a platform independent language.
      :: Bytecode in the Development Process: As discussed, the JAVAC  compiler of JDK compiles the java source code into bytecode so that it can be executed by JVM. It is saved as .class file by the compiler. To view the bytecode, a disassembler like javap can be used.
      :: JAVA Development kit(JDK): While we were using the term JDK when we learn about bytecode and JVM. So, as the name suggests, it is a complete Java development kit that includes everything including compiler, Java Runtime Environment(JRE). java debuggers, java docs, etc. For the program to execute in java, we need to install JDK on our computer in order to create, compile and run the java program.
      :: Java Runtime Environment(JRE) JDK includes JRE.JRE installation on our computers allows the java program to run, however, we cannot compile it. JRE includes a browser, JVM, applet support, and plugins. For running the java program, a computer needs JRE.

        ## Power of complication and interpretation:
      > Most language are designed with the purpose of either they are compiled language or they are interpreted language. But java integrates arising enormous power as java compiler compiles the source code to bytecode and JVM executes this bytecode to manchine OS dependent executable code.
      :: class: class keyword is used to declare classes in Java
      :: public: It is an access specifier. Public means this function is visible to all.
      :: static: static is again a keyword used to make a function static. To execute a static function you do not have to create an Object of the class. The main() method here is called by JVM, without creating any object for class.
      ::void: It is the return type, meaning this function will not return anything.
      :: main: main() method is the most important method in java program. This is the method which is executed.hence all the logic must be inside the main() method. If a java class is not having a main() method, it causes compilation error.
      :: String[] args : This used to signify that the user may opt to enter parameters to the  Java Program at command line. We can use both Strings[] args or Strings args[]. Java compiler would accept both forms.
      :: System.out.println: This used to print anything on the console like "printf" in C language

      ## Example:

      // Importing classes from packages
      import java.io.*;

      // Main class
      public class GFG {

        // MAIN driver method
         public static void main(string[] args)
         {

           // Print statement
          System.out.println("Welcome to GeeksforGeeks");
      }

      }

      ## Example 2:

      // Q: Write a Java program to calculate the sum and product of two given number.

class Sample {
    public static void main(String args[])
    {
        int a,b,sum=0,product=0;
        a=10;
        b=20;
        sum=a+b;
        product=a*b;
        System.out.println("Sum="+sum);
        System.out.println("Product="+product);
    }

    ## Example 3:

    // Q: Write a Java program to accept two numbers from the
// user and calculate sum and product.

import java.util.*;
class Sample {
    public static void main(String args[])
    {
        int a, b, sum = 0, product = 0;
        Scanner scan = new Scanner(System.in);
        System.out.println("Enter the First No:");
        a = scan.nextInt();
        System.out.println("Enter the Second No:");
        b = scan.nextInt();
        sum = a + b;
        product = a * b;
        System.out.println("Sum=" + sum);
        System.out.println("Product=" + product);
    }
}

};


## Java Datatypes:

> Java is statically typed and also a strongly typed language because, in Java, each type of data (such as integer, character, hexadecimal, packed decimal, and so forth) is predefined as part of the programming language and all constants or variables defined for a given program must be described with one of the Java data types.

Data types in JAVA:

> Data types in Java are of different sizes and values that can be stored in the variable that is made as per convenience and circumstances to cover up all test cases. Java has two categories in which data types are segregated.

* 1. Primitive Data Type: such as boolean, char, int, short, byte, long, float, and double
  2.Non-Primitive Data Type or Object Data type: such as String, Array, etc

