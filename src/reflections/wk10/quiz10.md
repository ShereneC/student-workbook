# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
It is like a file system - allows us to group all things related to that class in the namespace for that class.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
class is a reference type and struct is a value type
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
internal void?
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
public
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
I think this is the return type of that method.
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
Prevents a car from being created
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
I googled this and read about it, but still do not understand it. Does it have something to do with inheritance?
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public private protected internal
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
Only the class it is on
```