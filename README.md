# Project Skeleton Development Script



The script below helps in creating a basic template for a data analysis project. It generates the folders and files 

## Project Overview



 A good workflow for a particular team depends on the tasks, goals,
and values of that team, whether they want to make their work
faster, more efficient, correct, compliant, agile, transparent, or
reproducible

> Step 1: Data and Code Organization

The [`Cookie-Cutter`](cookie_cutter.sh) shell script creates a basic directory structure that might be useful for set-up a Data Science project

* The License File for this project is included can be generated out of the 4 options:
 - MIT, GNU, BSD - 3 Clause, Apache
 
 
* The Sub-directories created using the shell script under the `data_science_project` are :
  1. `citations` : For including any References or Citation docs for this project
  2. `src` : source code files. 
  2. `data` :
    * external
    * processed
    * raw
    > Based on the various stages of the data processing, the raw, external and processed data can be stored
  3. `docs`: For storing import docs, discussions or scripts for this project
  4. `models` : Model outputs and iterations
  5. `notebooks` : storing `R`, `python` `Jupyter` notebooks
  6. `reports` :
    * images:
    * figures
    > Includes important figures and images from visualizations



> Steps to mirror this repo

* git clone

clone this repo using the below code snippet in command-line

*git clone https://github.com/simrnsethi/cookie-cutter.git*

* cookie_cutter shell script

Now that you have the README, LICENSE and cookie_cutter.sh file run the shell script

make sure to clone this repo in your current directory

```
bash cookie_cutter.sh
```

This will generate all the required folders.

## Author

**Simran Sethi**

_Master of Data Science 2017-18 @ University of British Columbia_
