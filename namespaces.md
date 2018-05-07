# Java
#### In Java namespaces can be refereed to as packages:
```java
package pieces;
class Pawn {}
```
#### Here are two examples of commonly used Java packages.
- java.lang
- java.io
```java
import java.io.BufferedInputStream;
```

# C#
#### Name space in C# is used as following:
```C#
namespace store {
    class a {}
}
```
#### The .NET framework provides C# users with pre-defined namespaces: 
```C#
using System
using WinformTimer = System.Windows.Forms.Timer;
using ThreadingTimer = System.Threading.Timer;
```
#### Nested namespaces to help control scopes:
```C#
using top_namespace;
using top_namespace.inner_namespace;
namespace top_namespace 
{
    class ClassA {}
    namespace inner_namespace {
        class ClassB {}
    }
}
```
