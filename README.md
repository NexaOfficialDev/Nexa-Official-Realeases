# Nexa 1.0.0

**A programming language built with C and C++.**

Nexa is a programming-language project focused on its own syntax, language features, and development tools.

## Features

- **Variables** — store values for use throughout a program.
- **Data types** — represent different kinds of values supported by the language.
- **Operators** — perform calculations and comparisons.
- **Lists** — organize and work with collections of values.
- **Expressions** — combine values and operators.
- **Functions** — organize reusable code, where supported by the implementation.
- **Compiler** — build and run Nexa programs using the Nexa toolchain.
- **Native implementation** — developed using C and C++.

The exact syntax and availability of each feature must match the Nexa 1.0.0 implementation.

## Variables

Variables allow a program to store and reuse values.

The language reference will document:

- Variable declaration
- Assigning values
- Updating variables
- Variable naming rules
- Supported value types
- Variable scope and lifetime, where applicable

See the examples directory for working variable examples.

## Data Types

The Nexa 1.0.0 documentation should list the types actually supported by the compiler, including any supported numeric, string, Boolean, or collection types.

Type conversion, type checking, and default values should be documented only where implemented.

## Operators

Operators are used to manipulate values and build expressions.

The language reference will document supported:

- Arithmetic operators
- Comparison operators
- Logical operators
- Assignment operators
- Operator precedence and associativity

Not every operator category is guaranteed to be supported in 1.0.0.

## Lists

Lists allow multiple values to be grouped into a collection.

The list reference should cover supported operations such as:

- Creating a list
- Accessing elements
- Updating elements
- Adding or removing elements, if supported
- Getting the list length, if supported
- Iterating through list elements, if supported

## Functions

If supported in Nexa 1.0.0, functions provide reusable blocks of code.

Document function declarations, parameters, return values, calling syntax, and scope according to the actual implementation.

## Getting Started

1. Obtain the Nexa 1.0.0 distribution when it is published.
2. Follow the installation or build instructions included with the distribution.
3. Open an example program.
4. Run it using the documented Nexa compiler command.

Exact commands and requirements will be documented after the 1.0.0 build process is finalized.

## Examples

The `examples/` directory will contain small Nexa programs demonstrating the language.

Planned documentation examples:

- `hello_world.nx` — basic output
- `variables.nx` — variables and assignment
- `operators.nx` — supported operators
- `lists.nx` — list operations
- `functions.nx` — functions, if supported

Each example should be tested with Nexa 1.0.0 before being presented as working code.

## Building from Source

Nexa is implemented in C and C++.

Build instructions should specify the supported compiler, required dependencies, build command, and target architecture.

## Reporting Bugs

When reporting an issue, include:

- Nexa version
- Operating system and architecture
- The command used
- A small program that reproduces the issue
- The complete error message

## License

Nexa will be distributed under the MIT License. See `LICENSE` for the full license text.

---

**Nexa — Build. Learn. Create.**
