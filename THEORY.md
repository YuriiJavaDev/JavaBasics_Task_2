## Output to the Screen

### 1. Introduction to the `System.out.println` Command

We've just written our first Java program and displayed our first message on the screen. This is an important step—we can now interact with the user through output. In this section, we'll learn one of the most basic and frequently used commands.

Any Java program consists of **commands (instructions)**. Each command describes a specific action the program should perform.

**Every command in Java must end with a semicolon (`;`).**

---

#### Examples of Output Commands

| Command | Result |
| --- | --- |
| `System.out.println(2025);` | Prints the number `2025` |
| `System.out.println("Ciao 🍕");` | Prints the text `Ciao 🍕` |
| `System.out.println("こんにちは 🗾");` | Prints the text `こんにちは 🗾` |

All examples use the same command – `System.out.println`.

The difference lies in the data we pass in the parentheses. This data is called parameters.

Depending on the parameters, the command can perform different actions. This makes the Java language flexible and convenient.

---

#### Letter size matters

In Java, letter case is important.

The command:

```java
System.out.println();
```

will work, but:

```java
system.out.println();
```

will not.

Java strictly distinguishes between uppercase and lowercase letters, so you need to be careful when writing commands.

---

#### Double Quotes

If we want to print text, we need to enclose it in double quotes:

```java
System.out.println("Hello, world!");
```

Important:

- Double quotes look like this: `"`
- Single quotes `'` are **not suitable** for strings
- A double quote is **not two single quotes**

---

### 2. The `System.out.print` Command

Besides `System.out.println()`, there is a similar command:

```java
System.out.print();
```

#### What's the difference?

- `println()` — prints text **and moves the cursor to a new line**
- `print()` — prints text **without a new line**

---

#### Example 1. Mixed output

```java
System.out.print("Java");
System.out.println("The");
System.out.print("Best");
```

Result:

```
JavaThe
Best
```

---

#### Example 2. Only `print`

```java
System.out.print("Java");
System.out.print("The");
System.out.print("Best");
```

Result:

```
JavaTheBest
```

👉 If we want to print text **on one line**, use `print()`.

👉 If each part should be **on a new line**, use `println()`.

---

### 3. Parsing the `System.out.println` command

The command name helps us understand what it does Does:

- `print` — print
- `line` — string

So, `println` means **"print a line"**.

#### What is `System.out`?

`System.out` is a special **system object** that is responsible for displaying information on the screen.

The screen where text is displayed is called the **console**.

When a program:

- receives input from the keyboard
- displays text on the screen

— we say that it is **working with the console**.

So, the command:

```java
System.out.println("Text");
```

means:

> "Console, display this line of text."
>

---

### 4. Examples of Outputting Various Data

#### Output Numbers

```java
System.out.println(1001);
System.out.println(-15);
```

---

#### Printing Text

```java
System.out.println("Programming is cool!");
System.out.println("Now we're writing Java code.");
```

---

#### Printing Multiple Values

In Java, you can **concatenate (glue) strings** using the `+` operator.

```java
System.out.println("My age: " + 28);
```

Result:

```
My age: 28
```

You can also concatenate multiple values:

```java
System.out.println("The current time is " + 2025 +" year.");
```

Result:

```
The current time is 2025 year.
```

---

### 5. Common Errors When Using `System.out.println`

#### Error 1. Unclosed String

```java
System.out.println("Forgot to close the quotation mark);
```

The compiler will report an error:

`unclosed string literal`

✔ Always check that each string is closed with a double quotation mark.

---

#### Error 2. Missing semicolon

```java
System.out.println("Missing semicolon")
```

✔ Always end every command in Java with `;`

---

#### Error 3. Incorrect quotation marks

```java
System.out.println('Error');// incorrect
System.out.println('Error');// also incorrect
```

✔ Always use standard double quotes for strings: `" "`.
