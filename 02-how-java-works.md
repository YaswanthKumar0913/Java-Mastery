# How Java Works Internally

---

To truly understand Java, it's important to know **what happens behind the scenes** when you run a Java program.

Let’s break it down into simple steps.

---

## What Happens When You Write Java Code?

Imagine you write this simple program:

```java
public class Hello {
    public static void main(String[] args) {
        System.out.println("Hello, world!");
    }
}
```
---

## Step-by-Step Java Program Execution

Now you might wonder:  
**How does this get executed by your computer?**

Here’s the full journey from code to output:

---

### Step 1: Write Java Code (`.java`)
You write the source code in a file like `Hello.java`.

This code is **human-readable** and written in the Java programming language.

---

### Step 2: Compile to Bytecode (`.class`)

You run the Java compiler using the following command:

```bash
javac Hello.java
```
---
### Step 3: Run with JVM

Now, run the bytecode file:

```bash
java Hello
```

This command starts the **Java Virtual Machine (JVM)**.

Here’s what happens:

- JVM reads the bytecode from Hello.class.

- JVM translates it into machine code — that is, 0s and 1s.

- Machine code is sent to the CPU for execution.

---

### Output

```bash
Hello, world!
```

---

Here's the simple flow of what happened,
```
Your Code (.java)
|
|--- Compiled by javac
v
Bytecode (.class)
|
|--- Executed by JVM
v
Machine Code → Output on Screen
```
---
## Keep Learning!

👉 Go to the next section: [Java Syntax, Variables & Data Types](./03-java-basics.md)
