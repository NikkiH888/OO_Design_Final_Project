# Java
#### To define a class you can do the following:
- By convention, capitalize the initial letter of the class name
- A class can only extend one class or one abstract class.
- A class can implement more than one interface, and common-sperated list is used in this case.
- The class body is surrounded by braces, {}.
#### Code example
```java
public class Class_name extends Super_class_name implements InterfaceA, InterfaceB, InterfaceC {

}
```
#### Constructings/Initializings are used when we want initialize an object. 
```java
Class_name(){
    this.x = 0;
}
```
#### When you want to create an instance of a class you must use the new keyword and then proceed to call the constructor with the correct parameters.
```java
Class_name myInstance = new Class_name();
```
# C#
####  To define a class you can do the following: 
```C#
class Class_name : Super_class_name, Interface_class_name {
    
}
```
#### Destructos receive called whenever an object is no longer used and garbage collected. Unlike Java, this does have the ability to write destructors on classes.
```C#
~Class_name()
{
    Console.WriteLine("The Class_name object has been destroyed!!");
}
```
