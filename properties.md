# Java
#### The programmer has to write their own getter and setter methods as followings: 
```java
public class Doctor {
    private String name;
    
    public String getName()
    {
        return this.name;
    }
    
    public void setName(String name)
    {
        this.name = name;
    }
}
```

# C#
#### In C# you can assign getter and setter abilities to the variable itself. By using the 'get' and 'set' keywords you can make your variables read only, write only, or read-write. 
```C#
public class Doctor 
{
    // Property
    public String Name { 
        get {return name;}
        set {name = value;}
    }
}

public class Doctor 
{
    // Property
    public String Name {
        get => name;
        set => name = value;
    }
}

- Property accessors can also be implemented as single line statement.
public class Doctor 
{
    String firstname, lastname;
    Doctor(String first, String last) {
        this.firstname = first;
        this.lastname = last;
    }
    public String Name => $"{firstName} {lastName}";
}
```
