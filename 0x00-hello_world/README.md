# Repository Description

This repository contains code files and scripts for the low-level programming tasks in the ALX School curriculum.

## Project Description

This project focuses on various C programming tasks and shell scripting exercises. It covers different aspects such as preprocessor directives, compilation, and adherence to coding standards.

## General Requirements

- Editors allowed: vi, vim, emacs
- Compilation: gcc with the options -Wall -Werror -Wextra -pedantic -std=gnu89
- All files should end with a new line

## C Files

- The C files will be compiled on Ubuntu 20.04 LTS using gcc with the specified options.
- The code should adhere to the Betty style, which can be checked using the provided betty-style.pl and betty-doc.pl scripts.
- A README.md file should be present at the root of the repository, providing a description of the repository.
- Each project should have its own README.md file at the root of the folder, describing the project.
- There should be no compilation errors or warnings.

## Shell Scripts

- Editors allowed: vi, vim, emacs
- All shell scripts should be exactly two lines long (wc -l file should print 2).
- All files should end with a new line.
- The first line of each script should be #!/bin/bash.
- All scripts will be tested on Ubuntu 20.04 LTS.

## Preprocessor Task (C)

Write a script that runs a C file through the preprocessor and saves the result into another file.

- The C file name will be saved in the variable $CFILE.
- The output should be saved in the file `c`.

## Compiler Task (C)

Write a script that compiles a C file but does not link.

- The C file name will be saved in the variable $CFILE.
- The output file should have the same name as the C file, but with the extension .o instead of .c.

## Additional Information

For running the Betty linter, follow these steps:

1. Go to the Betty repository and clone it to your local machine.
2. Change directory to the Betty repository.
3. Install the linter using `sudo ./install.sh`.
4. Create a new file called `betty` using vi or emacs and copy the provided script into it.
5. Save the file and exit the editor.
6. Change the file permissions to apply to all users using `chmod a+x betty`.
7. Move the `betty` file to a directory in your $PATH (e.g., `/bin/`), using `sudo mv betty /bin/`.
8. You can now run the Betty linter by typing `betty <filename>`.

### Author
klayoff
