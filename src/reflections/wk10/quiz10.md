# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
it feels like it acts as the 'export' meaning when another piece of code says 'using' it connects with that defined namespace

```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
one is a reference type and the other is a value type. memory usage is also different
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
that sounds like any kind of  Get methods. so I'm gonna go with that.

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
virtual... NO WAIT that's the public and private thing... so public, PUBLIC!
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
the data type

```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
it indicates that the thing is missing a piece i guess
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
to be a stand in for the real data, so it's part of the other data but it's not the original
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public
private
protected
internal

```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
local stuff, or things that match an id requirement i think

```