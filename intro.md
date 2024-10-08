### How do Computers read code?
The compiler is a complex machine that bridges the gap between human-readable code and computer-readable code. At a low level, computer processors can only do a small number of things. They can read and write to memory, and they can do math with numbers they are holding. An executable program generated by the compiler is just an instruction list for the processor to follow, written in binary.
> `javac` is the Java Compiler.
### Object Oriented Programming (OOP) Concepts
Object Oriented Programming System is a paradigm that provides concepts such as objects, classes, inheritance among others.
#### Object
A real world entity having a particular state and behavior. It can be defined as an instance of a class.  A class defines a type of object.
*Example*
```java
public class FirstClass{
    public static void main(String[] args) { 
        FirstClass f = new FirstClass(); 
        System.out.println(“My First class”);
        f.add();
    }
    public static void add() {
        int a = 10, b = 5;
        int c = a + b;
    }
}
```
#### Class
A logical entity that defines the blueprint from which an object can be created or instantiated.
#### Inheritance
A concept that refers to an acquiring all the properties and behaviors of a parent object. It provides code reusability. 
#### Polymorphism
A concept that allows a task to be performed in different ways. In Java, we use method overloading and method overriding to achieve polymorphism.
#### Abstraction
A concept that hides the internal details of an application and only shows the functionality. In Java, we use abstract class and interface to achieve abstraction.
#### Encapsulation
A concept that refers to the wrapping of code and data together into a single unit.
### Java is not 100% Object Oriented
Java is not 100% Object Oriented because of the primitive data-types such as boolean, byte, char, int, double, long and short. When we say object oriented, everything should be in the form of an object but since we use the primitive data types are not an object Java is not 100% object oriented. But, to make them object oriented there is a workaround, these primitive data types can be converted into Wrapper classes which actually “_wrap_” the primitive data types into an object of that class.
### Why pointers are not used in Java?
Because firstly, pointers are unsafe, they increase the complexity of the program and since Java is known for the simplicity of the code, adding the concept of pointers will be contradicting, and since JVM is responsible for implicit memory allocation, thus in order to avoid direct access to memory by the user, pointers are discouraged in Java.
