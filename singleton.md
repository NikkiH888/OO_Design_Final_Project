# Java
#### There are multiple ways to create a singleton in Java. For example, the one with 'thread safe'.
```java
public class Singleton {
    private Singleton() {}
    private static class SingletonHolder {
        private static final Singleton INSTANCE = new Singleton();
    }
    public static Singleton getInstance() {
        return SingletonHolder.INSTANCE;
    }
}
```

# C#
#### There are multiple ways to create singletons in C#. For example, a design pattern which is thread safe and lazy.
```c#
public sealed class Singleton
{
    private Singleton() {
    }
    public static Singleton Instance { get { return Nested.instance; } }  
    private class Nested
    {
        // Explicit static constructor to tell compiler
        static Nested() {
        }
        internal static readonly Singleton instance = new Singleton();
    }
}
```

