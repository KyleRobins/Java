# Java Variables

Variables are containers for storing data values. There are different types of variables in Java

- `String` - stores text, such as `"how do you do"`. String values are written inside qoutes 
- `int` - stores integers (whole numbers) without decimal, i.e `234` `-234`
- `float` - stores floating numbers with decimal values, i.e `2.3` `-2.3`
- `char` - stores single characters, such as `'a'`or `'B'`. Char values are sorrounded by single qoutes `('')`
- `boolean` - stores values with two states `true` or `false`

## Declaring Variables 

While declaring a variable you must specify the type and asign it a value

**Syntax**

`type variableName = value;`

Where `type` is one of Java's types such as `int` or `String` and `variableName` is the name of the variable (i.e `x` or `name`).
The equal sign `=` is used to asign values to the variable.

**Examples**
### A variable that should store text.
Create a variable called **name** of type `String` and assign it the value of "your Name":

```java

String name = "Kyle Robins"; // Strings are always enclosed in qoutes 
System.out.println(name); // NOTE We Used the println() method to print Variable name to the screen
```
### A variable that should store numbers.

Create a variable called `myNum` of type int and assign it the value `Current Year`:

```java
 int myNum = 2024;
 System.out.println(myNum);
 ```

 **_Points To Note:_** 

You can also declare a variable without assigning the value, and assign the value later:

```java
int myVal;
myVal = 2025;
System.out.println(myVal);
```
Also Note that if you assign a new value to an existing variable, it will overwrite the previous value:

```java
int newVal;
newVal = 2026; // initial declaration
newVal = 2037; // replaces initial declaration
System.out.println(newVal); // Output: 2037
```

### Final Variables 

If you do not the variables declarations to be overwritten you can use the `final` keyword(this declares the variable as final or constant)
Which means it cannot be changed.

**Example**
```java

final int constVar = 2024;
final String constString = " Constant Variables";
System.out.println(constVar + constString); // Output: 2024 Constant Variables
```

