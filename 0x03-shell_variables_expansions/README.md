# 0x03. Shell, init files, variables and expansions

This project is part of the ALX System Engineering & DevOps track.  
It focuses on understanding shell initialization files, variables, expansions, arithmetic operations, and aliases in Bash.

All scripts are written for Ubuntu 20.04 LTS and follow strict project requirements:
- Each script contains exactly two lines
- The first line is `#!/bin/bash`
- No use of `;`, `&&`, `||`
- No use of `awk`, `sed`, or `bc`

---

## Files and Descriptions

| File | Description |
|------|-------------|
| 0-alias | Creates an alias named `ls` that runs `rm *` |
| 1-hello_you | Prints `hello` followed by the current Linux user |
| 2-path | Adds `/action` to the end of the `PATH` variable |
| 3-paths | Counts the number of directories in the `PATH` |
| 4-global_variables | Lists all environment variables |
| 5-local_variables | Lists all local variables, environment variables, and functions |
| 6-create_local_variable | Creates a local variable named `BEST` with value `School` |
| 7-create_global_variable | Creates a global variable named `BEST` with value `School` |
| 8-true_knowledge | Prints the result of `TRUEKNOWLEDGE + 128` |
| 9-divide_and_rule | Prints the result of `POWER / DIVIDE` |
| 10-love_exponent_breath | Prints the result of `BREATH` to the power of `LOVE` |
| 11-binary_to_decimal | Converts a binary number stored in `BINARY` to decimal |
| 12-combinations | Prints all two-letter combinations from `a` to `z` except `oo` |
| 13-print_float | Prints a number stored in `NUM` with two decimal places |

---

## Learning Objectives Covered

- Shell initialization files (`/etc/profile`, `~/.bashrc`)
- Local vs Global variables
- Reserved variables (`HOME`, `PATH`, `PS1`)
- Special parameters (`$?`, `$USER`, etc.)
- Shell expansions and command substitution
- Shell arithmetic
- Creating and managing aliases
- Executing scripts in the current shell using `source` or `.`

---

## How to Run Scripts

Some scripts must be executed using:

```bash
source ./script_name
