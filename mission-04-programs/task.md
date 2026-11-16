# Mission 4 – How Programs Run

## Task 4.1 – Create and Run a Python Program

Created a Python file named `hello.py` inside the `mission-04-programs` folder.

**Code:**

```python
print("Hello from Python")
```

**Command used:**

```bash
python3 mission-04-programs/hello.py
```

**Output:**

```text
Hello from Python
```

**Observation:** The Python program executed successfully and displayed the expected message.

## Task 4.2 – Compare Compiler and Interpreter

| Point | Compiler | Interpreter |
|---|---|---|
| When translation / execution happens | Translates the source code before the program runs. | Translates and executes instructions during runtime. |
| Typical output | Usually produces an executable or another translated form. | Usually executes instructions without producing a separate executable. |
| One example | C compiler (GCC) | Python interpreter |
| One advantage | Compiled programs can run faster. | Makes testing and debugging easier during development. |

### Explanation

A compiler translates the entire source code into another form before the program runs. An interpreter translates and executes instructions during runtime, usually one at a time. A compiler typically produces a separate output, while an interpreter executes the instructions as it processes them. Both help convert programming instructions into actions the computer can perform.
