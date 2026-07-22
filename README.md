# Codium Snippets

Custom code snippets for [VS Codium](https://vscodium.com/) covering **C** | **Csharp** | **Java** | **Python**.

Type a snippet's **prefix** in an editor of the matching language, then press `Tab` or `Enter` to expand it. Placeholders (`$1`, `$2`, …) let you tab between the fields you need to fill in.

## Installation

Copy the files into your Codium user snippets folder:

- **Linux/macOS:** `~/.config/VSCodium/User/snippets/`
- **Windows:** `%APPDATA%\VSCodium\User\snippets\`

Place `c.json` as `c.json` and `python.json` as `python.json` and so on...

---

## C Snippets

Source: [C/c.json](C/c.json)

| Prefix | Name | Description |
| --- | --- | --- |
| `main` | Main | `main` function with `#include <stdio.h>` and `return 0;` |
| `func` | Function | Function definition with return type, name and args |
| `struct` | Struct | `typedef struct { … } Name;` |
| `enum` | Enum | `typedef enum { … } Name;` |
| `if` | If | `if` statement |
| `ife` | If Else | `if` / `else` statement |
| `for` | For Loop | Counted `for` loop |
| `while` | While Loop | `while` loop |
| `dowhile` | Do While | `do { … } while (…);` |
| `switch` | Switch | `switch` statement with `case` and `default` |
| `printf` | Printf | `printf` call |
| `scanf` | Scanf | `scanf` call |
| `malloc` | Malloc | `malloc` with `NULL` check and `exit` on failure |
| `calloc` | Calloc | `calloc` with `NULL` check and `exit` on failure |
| `free` | Free | `free` followed by setting the pointer to `NULL` |
| `fopen` | Open File | `fopen` with error check |
| `fclose` | Close File | `fclose` call |
| `fgets` | Read Line | Buffered line read with `fgets` |
| `check` | Error Check | Error guard printing to `stderr` and returning |
| `assert` | Assert | `assert` call |
| `guard` | Header Guard | `#ifndef` / `#define` / `#endif` include guard |
| `incstd` | Include Stdlib | Common standard-library includes |
| `cleanup` | Goto Cleanup | `cleanup:` label freeing/closing and returning |
| `define` | Macro | `#define` macro |
| `inline` | Inline Function | `static inline` function |
| `static` | Static Function | `static` function |
| `todo` | TODO | `/* TODO(name): description */` comment |

---

## Python Snippets

Source: [Python/python.json](Python/python.json)

| Prefix | Name | Description |
| --- | --- | --- |
| `readfile` | Open file for reading | `with open(...)` reading into `text` |
| `writefile` | Open file for writing | `with open(..., w)` writing block |
| `cod` | Encoding statement | `# -*- coding: utf-8 -*-` line |
| `fileheader` | File header comment | File header comment with filename, date and copyright |
| `abstractmethod` | Abstract method | Method that raises `NotImplementedError` |
| `pvar` | Print function variable | Print a function-local variable with its value |
| `main` | Main entry point | `main()` definition plus `__main__` guard |
| `class1` | New class with init | Class with `__init__` and `__str__` |
| `class2` | New class with init and docstring | Class with docstring, `__init__` and `__str__` |
| `decor` | Function decorator | Decorator that logs args/kwargs |
| `eprop` | Decorated property with encapsulation | Getter/setter/deleter backed by name-mangled attribute |
| `prop1` | Decorated property | Property getter, setter and deleter |
| `prop2` | Decorated property (without deleter) | Property getter and setter |
| `try` | Try / Except | Basic `try` / `except` block |
| `tryf` | Try / Except / Finally | `try` / `except` / `finally` block |
| `if` | If Statement | `if` statement |
| `ife` | If Else | `if` / `else` statement |
| `ifel` | If Elif Else | `if` / `elif` / `else` statement |
| `for` | For Loop | `for` loop over an iterable |
| `fore` | For with Enumerate | `for` loop using `enumerate` |
| `while` | While Loop | `while` loop |
| `def` | Function | Function definition with docstring |
| `lam` | Lambda | Lambda assignment |
| `listcomp` | List Comprehension | List comprehension |
| `dictcomp` | Dictionary Comprehension | Dictionary comprehension |
| `with` | With Open | `with … as …` statement |
| `imp` | Import | `import module` |
| `impa` | Import As | `import module as alias` |
| `from` | From Import | `from module import name` |
| `print` | Print | `print(value)` |
| `fprint` | Formatted Print | Formatted `print` with an f-string |
| `ret` | Return | `return` statement |
| `assert` | Assert | `assert` with message |
| `log` | Logging | Basic `logging` setup and info call |
| `dataclass` | Dataclass | `@dataclass` skeleton |
| `ifmain` | Main Guard | `if __name__ == "__main__":` guard |
| `deft` | Type Hint Function | Function with type-hinted params and return |
| `class` | Class | Simple class with `__init__` |

## C# Snippets

Source: [CSharp/csharp.json](CSharp/csharp.json)

| Prefix | Name | Description |
| --- | --- | --- |
| `main` | Main | Main method |
| `class` | Class | Class definition |
| `struct` | Struct | Struct definition |
| `interface` | Interface | Interface definition |
| `enum` | Enum | Enum |
| `record` | Record | Record |
| `func` | Method | Method |
| `static` | Static Method | Static method |
| `prop` | Property | Auto property |
| `propr` | Readonly Property | Readonly property |
| `ctor` | Constructor | Constructor |
| `if` | If | If statement |
| `ife` | If Else | If else |
| `switch` | Switch | Switch statement |
| `switche` | Switch Expression | Switch expression |
| `for` | For | For loop |
| `foreach` | Foreach | Foreach loop |
| `while` | While | While loop |
| `dowhile` | Do While | Do while |
| `try` | Try Catch | Try catch |
| `tryf` | Try Catch Finally | Try catch finally |
| `using` | Using | Using declaration |
| `cw` | Console WriteLine | Console.WriteLine |
| `cr` | Console ReadLine | Console.ReadLine |
| `parse` | Parse Int | Parse int |
| `tryparse` | TryParse Int | TryParse int |
| `list` | List | Generic List |
| `dict` | Dictionary | Dictionary |
| `lambda` | Lambda | Lambda expression |
| `where` | LINQ Where | LINQ Where |
| `select` | LINQ Select | LINQ Select |
| `task` | Task | Async Task |
| `taskt` | Task<T> | Async Task<T> |
| `await` | Await | Await |
| `namespace` | Namespace | File-scoped namespace |
| `region` | Region | Region |
| `const` | Constant | Constant |
| `readonly` | Readonly Field | Readonly field |
| `field` | Field | Field |
| `todo` | TODO | TODO comment |

## Java Snippets

Source: [java/java.json](Java/java.json)

| Prefix | Name | Description |
| --- | --- | --- |
| `main` | Main | Main class with `public static void main(String[] args)` |
| `class` | Class | Public class declaration |
| `interface` | Interface | Public interface declaration |
| `enum` | Enum | Enum declaration with sample values |
| `ctor` | Constructor | Public constructor |
| `func` | Method | Public method |
| `static` | Static Method | Public static method |
| `private` | Private Method | Private method |
| `if` | If | `if` statement |
| `ife` | If Else | `if` / `else` statement |
| `for` | For Loop | Counted `for` loop |
| `foreach` | Enhanced For | Enhanced `for-each` loop |
| `while` | While | `while` loop |
| `dowhile` | Do While | `do` / `while` loop |
| `switch` | Switch | `switch` statement with `case` and `default` |
| `try` | Try Catch | `try` / `catch` block |
| `tryr` | Try With Resources | `try`-with-resources block |
| `print` | Print | `System.out.print()` |
| `println` | Println | `System.out.println()` |
| `printf` | Printf | `System.out.printf()` |
| `scanner` | Scanner | Create a `Scanner` for standard input |
| `arraylist` | ArrayList | Create an `ArrayList` |
| `hashmap` | HashMap | Create a `HashMap` |
| `hashset` | HashSet | Create a `HashSet` |
| `readfile` | Read File | Read a file using `BufferedReader` |
| `writefile` | Write File | Write a file using `BufferedWriter` |
| `throw` | Throw | Throw an exception |
| `assert` | Assert | `assert` statement |
| `package` | Package | Package declaration |
| `import` | Import | Import a package or class |
| `incstd` | Common Imports | Import common Java utility, I/O, NIO, and Stream packages |
| `todo` | TODO | `// TODO(name): description` comment |
| `getter` | Getter | Generate a getter method |
| `setter` | Setter | Generate a setter method |

## JavaScript Snippets

Source: [JS/javascript.json]JS/javascript.json