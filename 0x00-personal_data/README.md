# 0x00. Personal Data

This project focuses on understanding and implementing secure handling of personal data in Python applications. The key areas include obfuscating Personally Identifiable Information (PII) in logs, encrypting passwords, and authenticating database connections securely using environment variables.

## Background Context

Handling personal data securely is crucial in modern applications. Personally Identifiable Information (PII) needs to be managed with care to protect user privacy and comply with regulations such as GDPR. This project explores techniques for safely logging PII, encrypting sensitive data like passwords, and using environment variables for secure database authentication.

## Resources

- [What Is PII, non-PII, and Personal Data?](https://www.privacyshield.gov/article?id=What-is-Personally-Identifiable-Information)
- [Python Logging Documentation](https://docs.python.org/3/library/logging.html)
- [bcrypt Package](https://pypi.org/project/bcrypt/)
- [Logging to Files, Setting Levels, and Formatting](https://docs.python.org/3/howto/logging.html#logging-to-a-file)

## Learning Objectives

By the end of this project, you should be able to explain the following concepts:

### General

- Examples of Personally Identifiable Information (PII).
- How to implement a log filter to obfuscate PII fields.
- How to encrypt passwords and verify input password validity.
- How to authenticate to a database using environment variables.

## Requirements

### Python Scripts

- All files will be interpreted/compiled on Ubuntu 18.04 LTS using Python 3.7.
- All files should end with a new line.
- The first line of all files should be exactly `#!/usr/bin/env python3`.
- A `README.md` file, at the root of the folder of the project, is mandatory.
- Code should use the `pycodestyle` style (version 2.5).
- All files must be executable.
- The length of your files will be tested using `wc`.
- All modules should have documentation: `python3 -c 'print(__import__("my_module").__doc__)'`.
- All classes should have documentation: `python3 -c 'print(__import__("my_module").MyClass.__doc__)'`.
- All functions (inside and outside a class) should have documentation: `python3 -c 'print(__import__("my_module").my_function.__doc__)'` and `python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)'`.
- Documentation should be a real sentence explaining the purpose of the module, class, or method.
- All functions should be type annotated.

## Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Emakiflom/alx-interview.git
   cd alx-interview/0x00-personal_data

   ```

### Key Sections in the README

1. **Background Context**: Provides an overview of the importance of secure personal data handling.

2. **Resources**: Lists useful links to articles and documentation that aid in understanding project concepts.

3. **Learning Objectives**: Summarizes what you should be able to explain by the end of the project.

4. **Requirements**: Lists all requirements for Python scripts, including style guides and documentation.

5. **Setup**: Describes steps for setting up the project, installing dependencies, and running scripts.

6. **Usage**: Gives an overview of how to use the project's functionality.

7. **Examples of PII**: Lists common examples of Personally Identifiable Information.

8. **Author**: Aman Hablu
