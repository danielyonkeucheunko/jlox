# Lox

This repository contains **my implementation** of the Java and C interpreters described in Robert Nystrom's book [*Crafting Interpreters*](https://craftinginterpreters.com/). It focuses on building interpreters for the Lox programming language.

---

## Project Overview

This repository includes two interpreters:

1. **Tree-Walk Interpreter**
   - Implemented in Java.
   - Covers the high-level interpreter described in the first part of the book.

2. **Bytecode Virtual Machine (VM)**
   - Implemented in C.
   - Covers the low-level VM described in the second part of the book.

---

## Getting Started

### Prerequisites

- **Java Development Kit (JDK)** for the tree-walk interpreter.
- **C Compiler** (e.g., GCC or Clang) for the bytecode VM.

### Clone the Repository

```bash
git clone https://github.com/danielyonkeucheunko/lox.git
cd lox
```

---

## Running the Java Interpreter (Tree-Walk)

Run this command to run the REPL:
   ```bash
   java -jar jlox.jar
   ```

Run this command to run from a file (using test.lox as a example): 
   ```bash
   java -jar jlox.jar test.lox
   ```

---

## Running the C Interpreter (Bytecode VM)

1. Navigate to the `clox/` directory:
   ```bash
   cd clox
   ```

2. Build the VM:
   ```bash
   make
   ```

3. Run the VM:
   ```bash
   ./clox
   ```

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
