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
