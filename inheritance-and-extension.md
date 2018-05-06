# Java
#### Java allows subclasses to inherit from a single base class by using the "extends" keyword. 
```java
class Cat extends Animal {

}
```

#### Interfaces can also be used inheritance. Moreover, Java lets you implements multiple interfaces.
```java
interface A extends InterfaceB, InterfaceC, InterfaceD {

}
```

# C#
#### Similary, C# does not allow multiple inheritance on classes, but it does allow it on interfaces. The class must come first followed by the interface when you want a class to extend a superclass and implement multilpe interfaces.
```c#
class Cat : Pet, IAnimal, IMammal
```
