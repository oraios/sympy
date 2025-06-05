# SymPy Development Commands

## Testing Commands
- `python bin/test` - Run the main test suite with pytest-like interface
- `python bin/test [module/path]` - Test specific module or path
- `python bin/test --verbose` - Verbose test output
- `python bin/test --pdb` - Run post-mortem debugger on failures
- `python bin/doctest` - Run doctests
- `python setup.py test` - Alternative way to run tests (though bin/test is preferred)

## Setup and Installation
- `python setup.py install` - Install SymPy
- `python setup.py develop` - Install in development mode
- `python setup.py clean` - Clean build artifacts

## Code Quality Commands
- `python setup.py audit` - Run pyflakes checker on source code
- Code formatting: Project doesn't appear to use automated formatters like black/autopep8

## Interactive Usage
- `python bin/isympy` - Start SymPy interactive console (local development)
- `isympy` - Start SymPy console (if installed)
- `python isympy.py` - Alternative way to start interactive console

## Benchmarking
- `python setup.py bench` - Run benchmark suite

## Git Commands (Development)
- `git clean -Xdf` - Clean all ignored files
- `git clean -df` - Clean all untracked files
- `git reset --hard` - Revert recent changes (WARNING: destructive)

## Documentation
- `cd doc && make html` - Build HTML documentation locally
