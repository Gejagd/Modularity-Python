<div align="center">
    <h2>
        <b>
            Modularity
        </b>
    </h2>
        My Computer Science Class, Programing in Python<br>Meeting 12: Assignment
</div>

---

### Base Theory
<div align="justify">
    In software development, housing extensive code within a single file diminishes readability and maintainability. To address this, modularization is applied by breaking a program into smaller, distinct modules based on specific functionalities. In Python, a module is a .py file containing reusable functions, variables, or classes.<br>
    Python facilitates this architecture through the import statement. This command enables developers to access components from external files without rewriting the source code. Python supports several import methods, including standard imports (import module), specific component imports (from module import function), and aliasing (import module as alias). Consequently, modularization enhances code organization, scales development efficiency, and enforces the principle of code reusability.
</div>

#### Assignment
<div align="justify">
    Make two program (main.py & func.py) and apply the concept of module (import) in python, and optional to make file structure.
</div>

### Implementation
My first implementation here will be using:
| Class | Explanation |
| :-- | :-- |
| ``Class`` | OOP |
| ``def`` | function |
| ``import`` | modular concept |
---

### File Structure
```
Modularity/
├── src
|   ├── Mod.py              # Main program code file.
|   └── lib
|       ├── __init__.py 
|       └── Lib.py          # Library code.
└── README.md               # Please read for better general understanding.
```

### How to run
- First, making virtual environtment for yourself and activate it.
    - On Windows (for me using git bash):
    ```bash
    py -m venv .venv && source .venv/Scripts/activate
    ```
    - On linux based OS (bash / zsh):
    ```bash
    python3 -m venv .venv && source .venv/bin/activate
    ```
- Second, run the code file.
    - On windows (for me using git bash):
    ```bash
    py Mod.py
    ```
    - On linux based OS (bash / zsh):
    ```zsh
    python3 Mod.py
    ```

---

<div align="center">
    <b>
        Made By Me. 😊
    </b>
</div>