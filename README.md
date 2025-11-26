# 🚀 My Java Programming Journey

Welcome to my repository! This documents my progress, experiments, and projects as I learn and practice Java programming.

Currently, this repository features two main beginner projects: a **Student Marksheet System** and an **Invoice Generation Program**.

---

## 📚 Projects Overview

### 1. 🎓 Student Marksheet System
A console-based Java application designed to manage student grades. It records marks for multiple students across various courses and performs statistical calculations.

* **Key Features:**
    * Accepts user input for student details.
    * Calculates total marks and averages.
    * Demonstrates variable declaration and arithmetic logic.

### 2. 🧾 Invoice Generation Program
A program focused on formatted console output to simulate real-world billing documents.

* **Key Features:**
    * Generates a structured, tabular invoice/bill.
    * Utilizes `System.out.println()` effectively for alignment.
    * Simulates a professional document format in the terminal.

---

## 🛠️ Technology Stack

* **Language:** Java
* **Core Concepts:**
    * **Data Types:** `String`, `int`, `double`
    * **I/O:** `java.util.Scanner` class
    * **Logic:** Arithmetic Operators & Casting
    * **Output:** Console Formatting

---

## 💡 What I've Learned

Through building these projects, I have solidified my understanding of several fundamental concepts:

* **Data Types & Casting:** I learned the importance of type precision. For example, using `7.0` (double) during division to ensure the average calculation returns a decimal result rather than a truncated integer.
    
* **Input Handling (The "Scanner Trap"):**
    I learned how to handle the "newline character" issue. When using `scanner.nextInt()`, it reads the number but leaves the `\n` (Enter key) in the buffer. If `scanner.nextLine()` is called immediately after, it consumes that leftover newline instead of waiting for user input.
    [Image of Java Scanner buffer newline issue]
    
* **Code Structure:** Organizing logic within `public class Main` and the `public static void main(String[] args)` entry point.

* **Output Formatting:** Using string concatenation and spacing to create professional, tabular console outputs.

---

