# Repository Description

This repository contains the code and scripts for the ALX low-level programming project.

## Project Description

The project focuses on C programming and shell scripting. It includes various tasks that involve compiling and executing C files, working with the preprocessor, and adhering to coding style guidelines.

## Repository Structure

The repository is organized as follows:

- **0x00-hello_world**: This directory contains the source code and scripts related to the "Hello, World" project.
  - **0-preprocessor**: Script that runs a C file through the preprocessor and saves the result into another file.
  - **1-compiler**: Script that compiles a C file but does not link.

## Coding Requirements

### C

- Editors: vi, vim, emacs
- Compilation: Ubuntu 20.04 LTS using gcc with options -Wall -Werror -Wextra -pedantic -std=gnu89
- File format: All files should end with a new line
- Style: Code should follow the Betty style guidelines
- Error and warning-free: No errors or warnings should be present during compilation
- Libraries: No use of the system library

### Shell Scripts

- Editors: vi, vim, emacs
- Testing environment: Ubuntu 20.04 LTS
- File format: All files should end with a new line
- First line: The first line of all files should be `#!/bin/bash`
- Line count: All scripts should be exactly two lines long
- Betty linter: The scripts should pass the Betty linter

## Running the Betty Linter

To run the Betty linter, follow these steps:

1. Clone the Betty repository to your local machine.
2. Navigate to the Betty directory.
3. Install the linter with the command `sudo ./install.sh`.
4. Create a new file called `betty` using `emacs` or `vi` and copy the provided wrapper script into it.
5. Save and exit the file.
6. Change the permissions of the `betty` file using `chmod a+x betty`.
7. Move the `betty` file into the `/bin/` directory or any other location in your `$PATH` using `sudo mv betty /bin/`.
8. You can now run the Betty linter on any file by typing `betty <filename>`.

## Quiz Questions

If you have completed the quiz successfully, you can proceed to the next tasks.

## Task List

- **Task 0: Preprocessor**: Write a script that runs a C file through the preprocessor and saves the result into another file.
- **Task 1: Compiler**: Write a script that compiles a C file but does not link.

### AUTHOR
anas klayoff
