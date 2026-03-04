# Java Notes
## 1.	Class and objects
## Introduction
•	Java is a popular programming language, created in
1995.
•	Java is a programming language that James Gosling developed at Sun Microsystems_Inc in the year 1995, which later on was taken into possession by the Oracle Corporation in 2009.
•	We can call it a high-level (makes the development of programs   easy   and   much   more   user-friendly) programming language which makes it very convenient for us to write, compile and debug Java programs.
•	Java is a class-based	object-oriented programming language that implements the principle of write once code anywhere.
•	Since Java applications are compiled to byte-code, they can run on and JVM-supported machine.
•	Java codes are very similar 	to C/C++, which	makes them easier to understand.


### Class and Object
•	Class  represent  real-world  concepts  and entities.
•	A class in Java is a set of objects which shares common    characteristics    and    common properties.
•	It  is  a  user-defined  blueprint  or  prototype from which objects are created.
•	Acts as a template to create objects with shared structure.
•	Does not occupy memory for fields until instantiation.
•	Can contain fields, methods, constructors, nested classes and interfaces.
•	Properties of Java Classes.
•	Class is not a real-world entity. It is just a template or blueprint or prototype from which objects are created.
•	Class does not occupy memory.
•	Class is a group of variables of different data types and a group of methods.
•	A Class in Java can contain:
•	Data member
•	Method
•	Constructor
•	Nested Class
•	Interface
Syntax of a Class access_modifier class<class_name>
{
data member; method; constructor; nested class; interface;
}
# java
### Simple program
```
public class Main {
static void myMethod() {
System.out.println("Hello World!");
}
}
```
### Example:
```public class Main {
static void myMethod() { 
    System.out.println("Hello World!");
}
public static void main(String[] args) {
myMethod();
}
}
```
# Create a object:
```
public class Main { int x = 5;
public static void main(String[] args) { Main myObj = new Main(); 
System.out.println(myObj.x);
}
}
```
## Access Methods With an Object.
```
public class Main {
public void student() {
System.out.println("These are MCA- I A students!");
}
public void subject(String sname) {
System.out.println("Subject name is: " + sname);
}
public static void main(String[] args) { Main mystud = new Main();
mystud.student(); mystud.subject("Java Programming");
}
}

```




