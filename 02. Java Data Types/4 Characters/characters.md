# Java Characters

## Characters

The `char` data type is used to store a single character. The character must be sorounded with single qoutes, like 'A' or 'c':

**Example** 
```java

char myGrade = 'A'
System.out.println(myGrade);
```

Alternatively, if you are familiar with ASCII values, you can use those to display certain characters:

**Example**

```java
char myVar1 = 65, myVar2 = 66, myVar3 = 67;
System.out.println(myVar1);
System.out.println(myVar2);
System.out.println(myVar3);
```

## Strings

The `String` data type is used to store a sequence of characters (text). String values must be surrounded by double quotes:

**Example**
```java
String greeting = "Hello World";
System.out.println(greeting);
```

> A String in Java is actually a non-primitive data type, because it refers to an object. The String object has methods that are used to perform certain operations on strings.