# Task Completion Guidelines for SymPy

## When a Development Task is Completed

### 1. Testing
**Always run tests after making changes:**
- `python bin/test [affected_module]` - Test the specific module you modified
- `python bin/test` - Run full test suite for comprehensive changes
- `python bin/doctest [module]` - Test documentation examples if you modified docstrings

### 2. Code Quality Checks
- `python setup.py audit` - Run pyflakes to check for code issues
- Manually review code for style compliance with project conventions

### 3. Documentation Updates
- Update docstrings if you added/modified public APIs
- Add examples to docstrings when appropriate
- Update relevant documentation files if needed

### 4. Validation Steps
- Verify your changes work in the interactive console: `python bin/isympy`
- Test with different Python versions if making significant changes
- Check that imports still work correctly

### 5. Performance Considerations
- For performance-critical changes, consider running benchmarks: `python setup.py bench`
- Profile code if making changes to core modules

### 6. Integration Testing
- Test how your changes interact with other SymPy modules
- Verify backward compatibility is maintained
- Check that mathematical properties still hold

## Before Submitting Changes
- Ensure all tests pass
- Code follows project style guidelines
- Documentation is updated appropriately
- Changes are well-tested with edge cases
