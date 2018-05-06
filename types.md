# Java: There are two main types.
## 1. Primitive Data Types
#### There are 8 value types and it is impossible to create new ones.
  - byte
  - short
  - int
  - long
  - float
  - double
  - boolean
  - char

## 2. Objects 
#### This is reference types. It is the variables hold references to the object. Objects from the java.lang.number which sort of parallel the primitive data types are listed below.
  - Byte 
  - Short
  - Integer
  - Long
  - Float
  - Double

# C#: There are three main types.
## 1. Value Types
#### C# value types are derived from the System.ValueType class
  - bool
  - byte
  - char
  - decimal
  - double
  - float
  - int
  - long
  - sbyte
  - short
  - uint
  - ulong
  - ushort
#### In C#, structs are also value types:
struct example{
  private int data;
  
  string[] array;
}

 ## 2. Reference Type
 #### Listed below are referencce types keywords:
   - class
   - interface
   - delegate
#### Built in reference types keywords:
   - dynamic
   - object
   - string

## 3. Pointer Types
#### A pointer cannot point to a reference or struct becuase object reference can be a garbage collector which does not notice if an object is being pointed to, but the keywords like 'unsafe' and 'fixed' are needed to be used when working with pointers to get around this.
