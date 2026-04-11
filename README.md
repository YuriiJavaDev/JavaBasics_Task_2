# Phrase Assembly with Console Output (Task #2)

## 📌 Description
This project demonstrates the difference between `System.out.print()` and `System.out.println()` methods in Java. The goal is to assemble phrases from individual words by controlling the cursor position on the console, ensuring that words appear on the same line or move to a new one as required.

## 🚀 Task Requirements
The application must satisfy the following criteria:
1.  Print the first phrase: **"I'm learning Java."**
2.  Print the second phrase: **"This is interesting!"**
3.  Each word (**I'm**, **learning**, **Java**, **This is**, **interesting!**) must be output using a separate command (`print` or `println`).
4.  The final result must display exactly **two lines** of text.
5.  Strictly follow the order of words and punctuation as specified in the task.

## 🛠 Technical Stack
- **Language:** Java 23
- **IDE:** IntelliJ IDEA
- **Concepts covered:** Standard Output, Stream Manipulation, Line breaks (`\n`).

## 💻 Implementation Detail
The project uses `System.out.print()` to keep the cursor on the same line for assembling a phrase, and `System.out.println()` to terminate the line and move to the next one. This illustrates how Java handles the standard output buffer.

## 📋 Expected result
```text
I'm learning Java.
This is interesting!
```

```java
public class Task_2_App {
    public static void main(String[] args) {
        System.out.print("I'm");
        System.out.print(" learning");
        System.out.println(" Java.");

        System.out.print("This is");
        System.out.println(" interesting!");
    }
}
```

## ⚖️ License
This project is licensed under the **MIT License**.

Copyright (c) 2026 Yurii Pavlenko

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files...

License: [MIT](LICENSE)
