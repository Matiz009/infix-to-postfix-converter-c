# Infix to Postfix Converter (C)

Converts infix expressions to postfix (Reverse Polish) notation in C, using a stack.

## Features

- Supports the operators `+ - * / ^` with correct precedence
- Checks that `()`, `[]` and `{}` brackets are balanced
- Prints the infix and postfix forms, or "Expression is not balanced"

> Note: input is read with `gets()`, which was removed in C11. Newer compilers may warn about it or refuse to compile it.

## Tech stack

C

## Getting started

```bash
git clone https://github.com/Matiz009/infix-to-postfix-converter-c.git
cd infix-to-postfix-converter-c
gcc "infix_to_postfixConversion.c" -o infix_to_postfixConversion && ./infix_to_postfixConversion
```

## Project structure

```
infix_to_postfixConversion.c   Source code
infix_to_postfixConversion.exe   Old Windows build
```

## Author

**Mati ul Rehman** - [github.com/Matiz009](https://github.com/Matiz009)
