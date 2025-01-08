# jlox

`jlox` is an implementation of the tree-walk interpreter from Robert Nystrom's book [*Crafting Interpreters*](https://craftinginterpreters.com/). It supports a subset of the Lox programming language, offering features like expressions, statements, and basic control flow.

---

## Table of Contents
1. [Getting Started](#getting-started)
2. [Running the Java Interpreter](#running-the-java-interpreter)
3. [Examples](#examples)
4. [License](#license)

---

## Getting Started

### Prerequisites

- **Java Development Kit 21 (JDK 21)** for the tree-walk interpreter.

### Clone the Repository

```bash
git clone https://github.com/danielyonkeucheunko/lox.git
cd lox
```

---

## Running the Java Interpreter

Run this command to run the REPL:
   ```bash
   java -jar jlox.jar
   ```

Run this command to run from a file (using test.lox as a example): 
   ```bash
   java -jar jlox.jar test.lox
   ```

---

## Examples

Sample `test.lox` file:
```lox
// Example of Lox code
print "Hello, world!";
var a = 10;
if (a > 5) {
    print "a is greater than 5";
}
```

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
