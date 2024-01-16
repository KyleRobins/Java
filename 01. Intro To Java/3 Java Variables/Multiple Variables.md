# Java Declare Multiple Variables

## Declare Many Variables

To declare more than one `variable` of the same `datatype` you can use a comma `,` in a separated list 

**Example**

Instead of having:
```java
int x = 23;
int y = 21;
int z = 60;
System.out.println(x + y + z);
```
You can have:
```java
int x = 23, y = 21, z = 60;
System.out.println(x + y + z);// Output: 104
```

## One Value For Different Variables
You can also asign one value for different variables in the same line.

**Example**
```java
int x,y,z;
x = y = z = 50;
System.out.println(x + y + z); //Output: 150