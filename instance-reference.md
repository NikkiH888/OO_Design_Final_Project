# Java
#### We use the 'this' keyword to refer to an instance of a class.
```java
public class ClassA {
    private int data;
    ClassA(int data){
        this.data = data
    }
}
```

# C#
#### Both languages use 'this' keyword to refer to an instance of a class.
```C#
public class ClassA {
    int data;
    
    Example(int data){
        this.data = data;
        functionA(this); // pass to a function called functionA
    }
}
```

