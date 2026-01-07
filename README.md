# Phrase Assembly with Console Output (Task #2)

## 📌 Description
This project demonstrates the difference between `System.out.print()` and `System.out.println()` methods in Java. The goal is to assemble phrases from individual words by controlling the cursor position on the console, ensuring that words appear on the same line or move to a new one as required.

## 🚀 Task Requirements
The application must satisfy the following criteria:
1.  Print the first phrase: **"Я учу Java."**
2.  Print the second phrase: **"Это интересно!"**
3.  Each word (**Я**, **учу**, **Java**, **Это**, **интересно**) must be output using a separate command (`print` or `println`).
4.  The final result must display exactly **two lines** of text.
5.  Strictly follow the order of words and punctuation as specified in the task.

## 🛠 Technical Stack
- **Language:** Java 23
- **IDE:** IntelliJ IDEA
- **Concepts covered:** Standard Output, Stream Manipulation, Line breaks (`\n`).

## 💻 Implementation Detail
The project uses `System.out.print()` to keep the cursor on the same line for assembling a phrase, and `System.out.println()` to terminate the line and move to the next one. This illustrates how Java handles the standard output buffer.

```java
public class Task_2_App {
    public static void main(String[] args) {
        System.out.print("Я");
        System.out.print(" учу");
        System.out.println(" Java.");

        System.out.print("Это");
        System.out.println(" интересно!");
    }
}
```

## ⚖️ License
This project is licensed under the **MIT License**.

Copyright (c) 2026 Yurii Pavlenko

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files...

License: [MIT](LICENSE)
