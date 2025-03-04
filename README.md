# ternary
a single-purpose ternary arithmetic calculator.   It reads one line from stdin, parses it as a ternary expression, evaluates it,   and writes the ternary result to stdout. Errors are reported to stderr with an   exit code, making it script-friendly.

This literate program implements a simple Rust-based tool that evaluates
  ternary arithmetic expressions (base-3 digits: 0, 1, 2) from standard input
  and outputs the result in ternary format to standard output. Following Linux's
  tradition of "doing one thing well," it focuses solely on expression evaluation,
  omitting extraneous features like matrix operations or interactive modes.
  It supports addition, subtraction, multiplication, division, and parentheses,
  with robust error handling. Designed for pipeline use (e.g., `echo "12+21" | ternary`),
  it’s portable, safe, and adheres to Unix philosophy.
  
/*=====================================================================
  Ternary Tools Suite: Minimalist Ternary Computing Utilities in Rust
  Version: 1.1-RS
  Author: Grok (inspired by Copyleft Systems)
  Date: Mar 3 2025

  This literate program presents a suite of small, focused Rust tools for ternary
  computing, adhering to Linux's "do one thing well" philosophy. Each utility is
  designed for pipeline use, reading from stdin where practical, writing to stdout,
  and reporting errors to stderr. The suite refactors and extends Ternary Systems
  B02-RS, covering its core features plus new utilities:
    - ternary-calc: Evaluates ternary arithmetic expressions.
    - ternary-hanoi: Solves the Tower of Hanoi problem.
    - ternary-matrix: Performs matrix operations (add, multiply, serialize, deserialize).
    - ternary-opcode: Encodes or validates ternary opcodes.
    - ternary-convert: Converts between decimal and ternary numbers.
    - ternary-checksum: Computes or verifies ternary checksums.
  Built with Rust for safety and portability, these tools are lightweight, composable,
  and ideal for scripting (e.g., `echo "12+21" | ternary-calc`).
=====================================================================*/
