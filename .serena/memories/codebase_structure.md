# SymPy Codebase Structure

## Main Directory Layout
```
sympy/
├── sympy/           # Main library code
│   ├── core/        # Core symbolic computation classes (Basic, Expr, Add, Mul, etc.)
│   ├── functions/   # Mathematical functions (trig, special, elementary)
│   ├── algebras/    # Algebraic structures (quaternions, etc.)
│   ├── calculus/    # Calculus operations
│   ├── geometry/    # Geometric objects and operations
│   ├── matrices/    # Matrix operations and expressions
│   ├── polys/       # Polynomial manipulation
│   ├── solvers/     # Equation solvers
│   ├── simplify/    # Expression simplification
│   ├── series/      # Series expansion
│   ├── integrals/   # Integration
│   ├── plotting/    # Plotting capabilities
│   ├── physics/     # Physics modules (quantum, mechanics, etc.)
│   ├── logic/       # Boolean algebra
│   ├── sets/        # Set theory
│   ├── stats/       # Statistics and probability
│   ├── ntheory/     # Number theory
│   ├── combinatorics/ # Combinatorial functions
│   ├── tensor/      # Tensor operations
│   ├── utilities/   # Utility functions
│   └── printing/    # Pretty printing, code generation
├── bin/             # Executable scripts
├── examples/        # Example usage
├── doc/             # Documentation source
└── release/         # Release management
```

## Key Core Modules
- `core/basic.py` - Basic class (root of all SymPy objects)
- `core/expr.py` - Expression class
- `core/symbol.py` - Symbol definitions
- `core/numbers.py` - Number classes
- `core/add.py`, `core/mul.py`, `core/power.py` - Basic operations

## Test Organization
- Tests located in `tests/` subdirectories within each module
- Test files named `test_*.py`
- Doctests embedded in source code
