# CS50P-2024

[![Language: Python](https://img.shields.io/badge/language-Python-blue.svg)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![CI Pipeline](https://github.com/krsna016/CS50P-2024/actions/workflows/ci.yml/badge.svg)](https://github.com/krsna016/CS50P-2024/actions/workflows/ci.yml)
[![Security: CodeQL](https://github.com/krsna016/CS50P-2024/actions/workflows/codeql.yml/badge.svg)](https://github.com/krsna016/CS50P-2024/actions/workflows/codeql.yml)

Professional engineering repository configurations deployed inside your GitHub profile.

---

## Overview & Core Description

Welcome to my repository for Harvard's CS50P: Introduction to Programming with Python. This repository contains my solutions and projects completed as part of the course.

## Course Overview

CS50P is a comprehensive introduction to programming using Python, covering topics such as:

- Variables, Data Types, and Operators
- Conditionals and Loops
- Functions and Scope
- Data Structures (Lists, Dictionaries, Sets, and Tuples)
- File I/O
- Exception Handling
- Object-Oriented Programming
- Web Programming with Flask

## Repository Contents

This repository is organized by weeks, each corresponding to a specific module of the course:

- **Week 0:** Scratch
- **Week 1:** Functions, Variables, and Conditionals
- **Week 2:** Loops
- **Week 3:** Exceptions
- **Week 4:** Libraries
- **Week 5:** Unit Testing
- **Week 6:** File I/O
- **Week 7:** Regular Expressions
- **Week 8:** Object-Oriented Programming
- **Week 9:** SQL
- **Week 10:** Flask

Each week's directory contains:

- Lecture Notes
- Problem Sets and Solutions
- Assignments and Projects
- Additional Resources

## Getting Started

To explore my solutions and projects:

1. Clone the repository:
    ```sh
    git clone https://github.com/krsna016/CS50P.git
    ```
3. Run the Python scripts or explore the notes and assignments.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements

Special thanks to the CS50 team for providing such a comprehensive and engaging course.

---

Happy coding!


---

## System Design & Folder Structure
```text
.github/                  # CI/CD pipelines, Dependabot, and Issue/PR schemas
.editorconfig             # Unified file formatting configuration
.gitattributes            # Normalization variables for LF line endings
.gitignore                # Local environment overrides and cache limits
.pre-commit-config.yaml   # Quality check execution triggers
LICENSE                   # Permissive open-source MIT License
Makefile                  # Development workspace orchestrator
CHANGELOG.md              # Historical version tracking
CONTRIBUTING.md           # Developer onboarding guidelines
CODE_OF_CONDUCT.md        # Communication guidelines
SECURITY.md               # Responsible vulnerability disclosures
```

---

## Tooling & Tech Stack
- **Primary Environment:** Python runtime.
- **Workflow Automation:** GitHub Actions CI, Dependabot, and CodeQL.
- **Standards Checkers:** Git `pre-commit` hook validations.

---

## Quickstart & Local Setup
1. Clone this repository locally:
   ```bash
   git clone https://github.com/krsna016/CS50P-2024.git
   cd CS50P-2024
   ```
2. Trigger the local setup runner:
   ```bash
   make help
   ```

---

## Security & Responsible Disclosure
For details on disclosing vulnerabilities or hardcoded secrets, refer directly to our [SECURITY.md](SECURITY.md) guidelines.

---

## License
This repository is licensed under the permissive **MIT License**. For details, see the [LICENSE](LICENSE) file.
