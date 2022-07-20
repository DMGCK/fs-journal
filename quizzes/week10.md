# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
It's basically the same as import.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
A struct is a value type where as a class is a reference type, and a struct can't have a constructor.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
VOID
```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```
Public is the access modifier.
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
String is the return type
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
Instantiation of the the class without inheritance. Can't instantiate Car, but with a child it can be instantiated. 

try public class Maserati : Car
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
Virtual allows the method to be overwritten if there is another method somewhere in the inheritance that needs to be different. It will have the override modifier. 
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
Public, Private, Internal, Protected
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
Only that file can access the class. A private method can only be called from inside the classes definition, etc.
```