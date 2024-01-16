# Java Numbers

## Numbers

Primitive number types are divided into two groups:

- **Integer types** store whole numbers, positive or negative (i.e 123 or -123) without decimals. Valid types are `byte`, `long`, `short` and `int`. The type you should use depends on the numeric value.

- **Floating point types** they represent numbers with a fractional part, containing one or more decimals. There are two types `float` and `double`.

> Even though there are many numeric types in java the commonly used ones are `int` for wholes numbers and `double` for floating point numbers.

### Integer Types

#### Byte
 The `byte` data type can store values from -128 to 127. This can be used in place of `int` or other integer types to save memory when certain the values will be within -128 and 127

 **Example**
```Java
byte myNum = 100;
System.out.println(myNum);
```

#### Short

The `short` data type stores values between `-32768` to `32767`:

**Example**
```java
short myNum = 5000;
System.out.println(myNum);
```
#### Int 

The `int` data type can store values between -2147483648 to 2147483647. In `java` the `int` data type is the most preffered while working with numbers

**Example**
```Java

int myNum = 10000;
Sytem.out.println(myNum);
```
#### Long

The `long` data type can store whole numbers from -9223372036854775808 to 9223372036854775807. This is used when `int` is not large enough to store the value. Note that you should end the value with an `"L"`:

**Example**
```Java
long myNum = 15000000000L;
System.out.println(myNum);
```

## Floating Point Types

They are used whenever you need a number with a decimal. The `float` and `double` data types can store fractional numbers. Note that you should end the value with an `"f"` for `floats` and `"d"` for `doubles`:

**Example**

**Float Example**

```Java
float myNum = 5.75f;
System.out.println(myNum);
```
**Double Example**

```java
double myNum = 19.99d;
System.out.println(myNum);
```

> **Use float or double?** The precision of float is only six or seven decimal digits, while double variables have a precision of about 15 digits. Therefore it is safer to use double for most calculations.

#### Scientific Numbers

A floating point number can also be a scientific number with an "e" to indicate the power of 10:

**Example**
```Java
float f1 = 35e3f;
double d1 = 12E4d;
System.out.println(f1);
System.out.println(d1);
```







