# SymPy Code Style and Conventions

## General Style
- **Indentation**: 4 spaces (no tabs)
- **Line endings**: LF (Unix style)
- **Encoding**: UTF-8
- **Trailing whitespace**: Trimmed
- **Final newline**: Required

## Python Code Conventions
- Follows PEP 8 Python style guidelines
- **Import organization**: 
  - from __future__ imports at the top
  - Third-party imports
  - Local sympy imports
  - Use absolute imports where possible

## Documentation
- **RST files**: 3-space indentation
- Extensive docstrings for all public functions/classes
- Examples in docstrings are tested via doctest

## File Structure
- Main library code in `sympy/` directory
- Tests alongside code in `tests/` subdirectories
- Examples in `examples/` directory
- Documentation source in `doc/`

## Type Hints
- Project predates widespread type hint adoption
- Type hints not consistently used throughout codebase

## Naming Conventions
- Snake_case for functions and variables
- CamelCase for classes
- ALL_CAPS for constants
- Private methods/attributes prefixed with underscore
