# GitHub Copilot Instructions for CS50 Lectures Repository

This repository contains lecture code examples and demonstrations for Harvard's CS50 (Introduction to Computer Science) course. When working with this repository, please follow these guidelines:

## Code Style and Standards

### C Programming (Weeks 0-5)
- Follow CS50's style guide for C code
- Use meaningful variable names that are descriptive
- Include comments explaining complex logic, but keep code self-documenting where possible
- Use proper indentation (4 spaces)
- Include the CS50 library (`#include <cs50.h>`) where appropriate
- Prefer `stdio.h` standard library functions for basic I/O operations

### Python Programming (Week 6 onwards)
- Follow PEP 8 style guidelines
- Use descriptive variable and function names
- Include docstrings for functions and classes
- Keep code educational and easy to understand

### Web Development (Weeks 7-8)
- Write semantic HTML5
- Use proper CSS structure
- Write clean, readable JavaScript
- Follow web accessibility best practices

## Educational Context

### Code Examples Should:
- Be clear and educational, prioritizing readability over cleverness
- Progress incrementally (e.g., hello0.c → hello1.c → hello2.c)
- Include inline comments explaining new concepts
- Demonstrate one concept at a time when possible
- Be suitable for beginner programmers

### Avoid:
- Over-optimization that obscures the learning objective
- Advanced features not yet covered in the course
- Unnecessary complexity
- Assuming prior programming knowledge

## Repository Organization

The repository is organized by week/topic:
- `0/` - Scratch (visual programming)
- `1/` - C basics (functions, loops, conditionals)
- `2/` - Arrays and strings
- `3/` - Algorithms
- `4/` - Memory
- `5/` - Data structures
- `6/` - Python
- `7/` - SQL
- `8/` - Web development (HTML, CSS, JavaScript, Flask)
- `ai/` - Artificial Intelligence topics

Each directory contains:
- `README.txt` - List of files and topics covered
- `src{n}/` - Source code directory with numbered examples

## When Creating or Modifying Code

1. **Maintain Progressive Complexity**: If creating a series of examples (e.g., `example0.c`, `example1.c`), ensure each builds upon the previous one
2. **Keep Examples Focused**: Each file should demonstrate a specific concept or technique
3. **Add Helpful Comments**: Explain WHY, not just WHAT the code does
4. **Test Code**: Ensure all code compiles and runs correctly
5. **Follow Naming Conventions**: Use the existing naming pattern (lowercase, descriptive names)

## Common Patterns

### C Files
```c
// Brief description of what this program does

#include <stdio.h>
#include <cs50.h>  // If using CS50 library

int main(void)
{
    // Implementation
}
```

### Python Files
```python
# Brief description of what this program does

def main():
    # Implementation

if __name__ == "__main__":
    main()
```

## Documentation

- Update README.txt files when adding new examples
- Maintain consistency with existing documentation format
- Keep descriptions brief but informative

## Compiler and Runtime

- C code should compile with `clang` or `gcc`
- Use CS50's compilation flags: `-lcs50 -lm`
- Python code should be compatible with Python 3.x
- Web code should work in modern browsers

## Remember

This is an **educational repository**. Code clarity and pedagogical value take precedence over performance optimization or advanced techniques. The goal is to help students learn fundamental computer science concepts.
