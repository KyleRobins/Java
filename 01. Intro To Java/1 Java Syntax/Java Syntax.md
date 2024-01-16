# Java Syntax

**Example Code**

```java
public class Main {
    public static void main(String[] args){
        System.out.println("Hello Welcome To Java")
    }
}
```
**Example Explained**

> **_NOTE:_** Every line of code that runs in `Java` must be inside a `class`.
In the example above we named our `class` **Main** a `class` should always start with an **UPPERCASE** letter.

Java is case senstive `MyClass` is not `myclass` both have different meanings.
The name to your `Java` file must much the name to the `class`, While saving it add a `.java` file extension i.e `Main.java` in this case our `class` had the name Main so the corrresponding java file will be `Main.java`.

## The Main Method 

The `main()` method is required, any code inside the `main()` method gets executed. so remember that every java program has a `class` which must match with the file name and that every program must contain a `main()` method.

## System.out.println()

Inside the `main()` method, we can use the `println()` method to print a line of text to the screen:
```java
public static void main(String[] args) {
    System.out.println("Output to the screen");
} 
```

>**_NOTE:_** The `{}` Braces mark the beggining and the end of a block of code.

`System` is a built-in Java class that contains useful members such as `out`, which stands for `output` in full. The `println()` method short form of `print line` prints values to the screen.

Each code Statement must end with a semi-colon `;`


