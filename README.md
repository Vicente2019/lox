# Lox Interpreter in Java

This is the Lox Interpreter project! This repository contains an implementation of a Java-based interpreter for the Lox programming language, inspired by Robert Nystrom's book *"Crafting Interpreters"*.

## Project Overview

Lox is a simple, dynamically-typed language designed to teach the fundamentals of language design and implementation. This project is still under development, where the goal is to include all the functionalities of the book and more, such as types and array methods.

## Features

- **Lexical Analysis:** Tokenizes Lox source code into symbols for parsing.
- **Parsing:** Utilizes the Visitor design pattern to build an Abstract Syntax Tree (AST).
- **Interpretation:** Executes Lox code, supporting various expressions and statements.

## Getting Started

To get started with the Lox Interpreter, follow these steps:

### Prerequisites

- Java Development Kit (JDK) installed on your machine (preferably JDK 17).

### Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Vicente2019/lox.git

2. **Navigate to the Project Directory:**

    ```bash
   cd lox

3. **Compile the Project:**

    ```bash
   javac -d bin src/*.java

4. **Run the Interpreter:**

    ```bash
   java -cp bin lox.Lox
