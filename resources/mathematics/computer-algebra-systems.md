# Computer Algebra Systems for Ternary Computing Research

## Available Computer Algebra Systems

### 1. **diofant/diofant** (Python)
- **Description**: Python computer algebra system library
- **Features**: Symbolic computation, algebraic structures
- **Use Case**: Algorithm verification, mathematical proofs
- **Stars**: 72
- **URL**: https://github.com/diofant/diofant

### 2. **Nonanti/mathcore** (Rust)
- **Description**: Symbolic math library and computer algebra system for Rust
- **Features**: Differential equations, equation solver, symbolic math
- **Use Case**: High-performance mathematical computations
- **Stars**: 83
- **URL**: https://github.com/Nonanti/mathcore

### 3. **aesara-devs/aesara** (Python)
- **Description**: Mathematical expression optimization library
- **Features**: Multi-dimensional arrays, automatic differentiation
- **Use Case**: Numerical optimization, performance analysis
- **Stars**: 1,215
- **URL**: https://github.com/aesara-devs/aesara

### 4. **Theano/Theano** (Python)
- **Description**: Multi-dimensional array mathematics (evolved to PyTensor)
- **Features**: Expression optimization, tensor operations
- **Use Case**: Large-scale numerical computations
- **Stars**: 9,959
- **URL**: https://github.com/Theano/Theano

### 5. **Vio-Eli/rme** (Rust)
- **Description**: High-performance computer algebra system library
- **Features**: Symbolic manipulation, complex mathematical computations
- **Use Case**: Efficient symbolic computation
- **Stars**: 0
- **URL**: https://github.com/Vio-Eli/rme

### 6. **Odeneho-Calculus/Mathrok** (TypeScript)
- **Description**: Symbolic mathematics with NLP and visualization
- **Features**: Natural language processing, voice interaction
- **Use Case**: Interactive mathematical problem-solving
- **Stars**: 0
- **URL**: https://github.com/Odeneho-Calculus/Mathrok

## Recommended for Ternary Computing

### Primary Choices:
1. **diofant/diofant** - For algorithm verification and proofs
2. **Nonanti/mathcore** - For high-performance computations
3. **aesara-devs/aesara** - For numerical optimization

### Integration Strategy:
- Use diofant for symbolic verification of conversion algorithms
- Use mathcore for performance-critical ternary operations
- Use aesara for optimizing ternary arithmetic expressions

## Implementation Notes

### Binary to Ternary Conversion Algorithms
```python
# Example conversion approach
def binary_to_ternary(binary_str):
    # Convert binary to decimal
    decimal = int(binary_str, 2)
    # Convert decimal to ternary
    ternary = ""
    while decimal > 0:
        remainder = decimal % 3
        ternary = str(remainder) + ternary
        decimal = decimal // 3
    return ternary
```

### Mathematical Properties to Verify
- Commutativity of ternary operations
- Associativity of ternary arithmetic
- Distributive properties
- Conversion algorithm correctness

## Next Steps
1. Clone selected CAS libraries
2. Develop ternary arithmetic modules
3. Create verification frameworks
4. Implement performance benchmarks
