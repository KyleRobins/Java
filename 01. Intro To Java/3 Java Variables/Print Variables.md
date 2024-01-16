# Java Print Variables 

## Display Variables

The `println()` method is often used to display `variables` to the screen. To combine both `text` and a `variable` use the `+` sign.

**Example**

```java
String myString = "Hello there";
System.out.println(myString + " Kyle"); //Output: Hello there Kyle
```

You can also use the `+` sign to add a `variable` to another `variable`

**Example**
```java
String myText = "add this to another var";
int myNum = 2025;
System.out.println(myText + "" + myNum); //Output: add this to another var 2025
```

While using the `+` sign with integers it works as a mathematical `operator` and will add the two integers together to give a result

**Example**
```java

int x = 23;
int y = 24;
System.out.println(x + y); //Output: 47