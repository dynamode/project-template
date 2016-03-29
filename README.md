# Project-Template README

## Project Structure
```
project-template\
- README.md
- .gitignore
- docs\
- src\
- experiments\
- scratch\
```
There are two files:

+ README.md - a text or markdown file detailing the project layout
+ .gitignore - a configuration file of which files git should ignore

There are 4 directories:

+ docs - for LaTeX documents and final figures
+ src - for source code and unit tests
+ experiments - for scripts
+ scratch - for temporary figures/data

### docs
The ```docs\``` directory is for LaTeX write-ups.
For example:
```
docs\
- conference-paper-20XX\
  - main.tex
  - main.pdf
  - figures\
    - fig1.png
- conference-poster\
  - poster.tex
```

### src
The ```src\``` directory is for source code.

For example in Python:
```
src\
- module_name\
  - __init__.py
  - module_name.py
  - helper.py
- test\
  - module_test.py
- setup.py
```
Where ```module_name\``` is a subdirectory containing your Python module's code, ```test\``` is a subdirectory for unit tests.

### experiments
The ```experiments\``` directory is for other code (such as for experiments, analysis, figures).




