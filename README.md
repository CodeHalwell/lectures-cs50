# CS50 Lecture Code Examples

This repository contains code examples and demonstrations from Harvard University's CS50 (Introduction to Computer Science) course lectures. The materials are organized by week and cover fundamental computer science concepts from basic programming to web development.

## 📚 Repository Structure

The repository is organized into directories representing different weeks/topics of the CS50 course:

### Week 0 - Scratch
- **Directory**: `0/`
- **Topics**: Visual programming, computational thinking basics
- **Language**: Scratch (visual programming)

### Week 1 - C
- **Directory**: `1/`
- **Topics**: 
  - Functions, arguments, return values
  - Variables and data types (int, char)
  - Conditionals and Boolean expressions
  - Loops (for, while, do-while)
  - Basic I/O operations
- **Language**: C
- **Key Examples**: `hello.c`, `compare.c`, `agree.c`, `cat.c`, `mario.c`

### Week 2 - Arrays
- **Directory**: `2/`
- **Topics**:
  - Arrays and strings
  - Command-line arguments
  - Debugging techniques
  - String manipulation
  - Character operations
- **Language**: C
- **Key Examples**: `buggy.c`, `scores.c`, `string.c`, `uppercase.c`, `greet.c`

### Week 3 - Algorithms
- **Directory**: `3/`
- **Topics**:
  - Searching algorithms (linear search, binary search)
  - Sorting algorithms (bubble sort, selection sort, merge sort)
  - Algorithm efficiency and Big O notation
  - Recursion
- **Language**: C

### Week 4 - Memory
- **Directory**: `4/`
- **Topics**:
  - Pointers and memory addresses
  - Dynamic memory allocation
  - Memory management (malloc, free)
  - File I/O
  - Image manipulation
- **Language**: C

### Week 5 - Data Structures
- **Directory**: `5/`
- **Topics**:
  - Linked lists
  - Trees and tries
  - Hash tables
  - Queues and stacks
- **Language**: C

### Week 6 - Python
- **Directory**: `6/`
- **Topics**:
  - Python syntax and basics
  - Transition from C to Python
  - Python data structures (lists, dictionaries, sets)
  - File handling in Python
  - Object-oriented programming
  - Libraries and packages
- **Language**: Python
- **Key Examples**: Various Python implementations of earlier C programs

### Week 7 - SQL
- **Directory**: `7/`
- **Topics**:
  - Relational databases
  - SQL queries (SELECT, INSERT, UPDATE, DELETE)
  - Database design
  - JOINs and relationships
  - Python database integration
- **Language**: SQL, Python

### Week 8 - Web Development
- **Directory**: `8/`
- **Topics**:
  - HTML structure and semantics
  - CSS styling
  - JavaScript basics
  - Flask web framework
  - HTTP requests and responses
  - Forms and user input
  - Sessions and cookies
- **Languages**: HTML, CSS, JavaScript, Python (Flask)
- **Key Examples**: Web pages, Flask applications

### AI - Artificial Intelligence
- **Directory**: `ai/`
- **Topics**: Introduction to AI concepts and applications
- **Language**: Python

## 🚀 Getting Started

### Prerequisites

To run the code examples in this repository, you'll need:

- **C Compiler**: `gcc` or `clang`
- **CS50 Library**: [CS50 Library for C](https://github.com/cs50/libcs50)
- **Python 3.x**: For Python examples
- **Web Browser**: For HTML/CSS/JavaScript examples
- **Flask**: For web application examples (`pip install flask`)

### Compilation and Execution

#### C Programs
```bash
# Compile a C program
gcc -o program program.c -lcs50 -lm

# Or using clang
clang -o program program.c -lcs50 -lm

# Run the compiled program
./program
```

#### Python Programs
```bash
# Run a Python script
python3 program.py
```

#### Flask Applications
```bash
# Run a Flask application
flask run
# Or
python3 app.py
```

## 📖 How to Use This Repository

### For Students
1. **Follow Along with Lectures**: Each directory corresponds to a week in the CS50 course
2. **Study Progressive Examples**: Files are often numbered (e.g., `hello0.c`, `hello1.c`) showing progression
3. **Experiment**: Modify the code to understand how it works
4. **Compare Implementations**: See how concepts translate across different languages (C → Python)

### For Educators
- Use these examples as teaching references
- Demonstrate progressive complexity in programming concepts
- Show students different approaches to solving problems

## 📋 File Naming Convention

Files follow a consistent naming pattern:
- **Numbered Examples**: `filename0.c`, `filename1.c`, etc. - Show progressive development
- **Descriptive Names**: Names reflect the concept being demonstrated
- **README.txt**: Each week's directory contains a README.txt listing the files and topics

## 🔧 Configuration

The repository includes:
- `.gitignore`: Excludes compiled binaries, cache files, and IDE-specific files
- `settings.json`: VS Code configuration for consistent development environment

## 📚 Additional Resources

- [CS50 Official Website](https://cs50.harvard.edu/)
- [CS50 on edX](https://www.edx.org/course/cs50s-introduction-to-computer-science)
- [CS50 GitHub](https://github.com/cs50)
- [CS50 Documentation](https://cs50.readthedocs.io/)

## 🤝 Contributing

This repository contains educational materials. When contributing:
1. Maintain the progressive, educational nature of examples
2. Follow existing code style and naming conventions
3. Include clear comments explaining concepts
4. Test all code before committing
5. Update README.txt files when adding new examples

## 📄 License

This repository contains educational materials related to Harvard's CS50 course. Please refer to CS50's usage policies for proper attribution and use.

## 🙏 Acknowledgments

- Harvard University's CS50 course staff and instructors
- David J. Malan and the CS50 team
- The CS50 community

## 📞 Support

For questions about CS50 course content:
- Visit the [CS50 Discord](https://discord.gg/cs50)
- Check the [CS50 FAQ](https://cs50.harvard.edu/x/faqs/)
- Explore [CS50 on Stack Exchange](https://cs50.stackexchange.com/)

---

**Note**: This repository is organized for educational purposes, presenting code examples that illustrate fundamental computer science concepts taught in Harvard's CS50 course.
