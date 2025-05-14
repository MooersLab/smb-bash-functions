![Version](https://img.shields.io/static/v1?label=smb-bash-functions&message=0.1&color=brightcolor)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

# smb-bash-functions

Bash functions that make it much easier to do many repetitive tasks on the structural molecular biology (SMB) server at the Stanford Synchrotron Radiation Light Source of the SLAC National Accelerator Center in Menlo Park, California.

## Problem Addressed
These functions execute various data reduction and file wrangling tasks on hundreds or thousands of X-ray diffraction image files.

## Usage

1. Move smbBashFunctions to `~/.bashFunctions`.
2. Change to the bash shell by entering `bash` in the terminal.
3. `source bashFunctions`
4. Enter the function name with arguments to print the documentation in the terminal.
5. Enter `which rename_cbfs` to display the code of a function in the terminal. 
6. Enter the function name and any command-line arguments.

## Features

1. xtriage
2. dmincbf: iteratively run autoxds over a range of resolution ranges.
3. rename_cbf_files: rename 100s of X-ray diffraction files.
4. summary: run summary scirpt on autoxds processing folder ending with dmin.
5. wilsond: make wilson plot for autoxds processing folder ending with dmin.
6. 

## Update history

|Version      | Changes                                                                                                                                                                         | Date                 |
|:-----------|:------------------------------------------------------------------------------------------------------------------------------------------|:--------------------|
| Version 0.1 |   Added badges, funding, and update table.  Initial commit.                                                                                                                | 5/14/2025  |

## Sources of funding

- NIH: R01 CA242845
- NIH: R01 AI088011
- NIH: P30 CA225520 (PI: R. Mannel)
- NIH: P20 GM103640 and P30 GM145423 (PI: A. West)

