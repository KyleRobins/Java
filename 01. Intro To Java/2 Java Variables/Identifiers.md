# Java Identifiers

## Identifiers 

All java `Variables` must be **identified** with **unique** names. This unique names are what we call **identifiers**

They can be short like **x** and **y** or long descriptive names like (myInt, firstName, lastName, currentDate) etc.

**_NOTE:_** It's recommended to use descriptive names  to create understandable and maintainable code.

**Example**

```Java

//Good

int minPerHour = 60;

// Ok but not easy to understand what m is

int m = 60;

```

### The general rules for naming variables are:

- Names can contain letters, digits, underscores, and dollar signs
- Names must begin with a letter
- Names should start with a lowercase letter and it cannot contain whitespace
- Names can also begin with $ and _ (but we will not use it in this tutorial)
- Names are case sensitive ("myVar" and "myvar" are different variables)
- Reserved words (like Java keywords, such as int or boolean) cannot be used as names