# Java
#### Two ways to create threads:
```java
public class MyTask implements Runnable 
{
    // This block of code is executed while the thread is active.
    public void run() {
        System.out.println("Hello from a thread!");
    }
    public static void main(String args[]) {
        (new Thread(new MyTask())).start();
    }
}
public class MyTask extends Thread 
{
    public void run() {
        System.out.println("Hello from a thread!");
    }
    public static void main(String args[]) {
        (new MyTask()).start();
    }
}
```
# C#
#### A way to create thread in C#
```c#
using System.Threading;

Thread myThread = new Thread(new ThreadStart(DoThisMethod));
myThread.Start();

public void DoThisMethod(){
    
    //This code is executed by the myThread objcect

}
```

