# SymPy Project Overview

## Purpose
SymPy is a Python library for symbolic mathematics. It aims to become a full-featured computer algebra system (CAS) while keeping the code as simple as possible to be comprehensible and easily extensible. SymPy is written entirely in Python and depends on mpmath as an external library.

## Technology Stack
- **Language**: Python (supports Python 2.7 and 3.4+)
- **Main Dependencies**: 
  - mpmath (version >= 0.19) - required for mathematical computations
  - Optional dependencies for specific features (plotting, etc.)
- **Build System**: setuptools/distutils based setup.py
- **Testing**: Custom test framework (bin/test) with pytest-like interface

## Key Features
- Pure Python implementation
- Symbolic computation capabilities
- Mathematical functions, algebra, calculus, geometry
- Code generation capabilities
- Extensive test suite
- Cross-platform compatibility
