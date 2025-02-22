# Wooldridge's Introductory Econometrics - Stata Code 

This repository contains Stata code to reproduce the examples from Jeffrey Wooldridge's "Introductory Econometrics: A Modern Approach". The code covers all chapters from the book, providing a comprehensive set of examples and econometric analyses.

## Table of Contents

- [Introduction](#introduction)
- [Requirements](#requirements)
- [Installation](#installation)
- [Data and Output Setup](#data-and-output-setup)
- [Usage](#usage)
- [Credits](#credits)
- [Contact](#contact)

## Introduction

This repository contains Stata do-files to replicate the econometric analysis presented in all chapters of Wooldridge's textbook. This code covers a wide range of econometric topics, including linear regression, instrumental variables, panel data, time series, and more.

## Requirements

To run the code, you will need:

- Stata 18 (or compatible version)
- The `outreg2` package for exporting regression outputs

## Installation

Before running the code, ensure you have the necessary dependencies installed. In Stata, you can install the `outreg2` package by running:

```stata
ssc install outreg2
```

## Data and Output Setup

1. **Data Folder**: Create a folder named `data` in the root directory of this repository. Place all the Wooldridge dataset files (e.g., `hseinv.dta`, `intqrt.dta`, `phillips.dta`, etc.) in this folder.

2. **Output Folder**: Create a folder named `output` in the root directory of this repository. This folder will store the log files, graphs, and other output files generated by the Stata scripts.

## Usage

To run the code for a specific chapter:

1. Open Stata.
2. Set the working directory to the root of the repository.
3. Run the do-file for the chapter you are interested in. For example, to run the code for Chapter 18, use the following command in Stata:

    ```stata
    do Chapter18.do
    ```

Each do-file is designed to load the necessary data, perform the econometric analysis, and save the results to the `output` folder.

## Credits

The original code was prepared by Oleksandr Talavera (revised 8 Nov 2002) and has been amended for clarity and updated practices. The code examples are based on Jeffrey Wooldridge's "Introductory Econometrics: A Modern Approach".

The original page prepared by Oleksandr Talavera (revised 8 Nov 2002). The original pages are maintained by the Faculty Micro Resource Center's GSA Program, a unit of Boston College Academic Technology Services

http://fmwww.bc.edu/gstat/examples/wooldridge/

## Contact

For questions, comments, or suggestions, please contact Martin Conyon (mconyon@bentley.edu).
