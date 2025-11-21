# Mean-Variance-Standard Deviation Calculator

## Overview
This is a Python data analysis project that calculates mean, variance, and standard deviation statistics from a 3x3 matrix. This is a freeCodeCamp Data Analysis with Python project.

## Project Structure
- `mean_var_std.py` - Main calculation module (implementation required)
- `main.py` - Entry point that runs the calculator and tests
- `test_module.py` - Unit tests for the calculator
- `requirements.txt` - Python dependencies (numpy)

## Technology Stack
- **Language**: Python 3.11
- **Dependencies**: NumPy (>=1.21.0)
- **Testing**: Python unittest framework

## Setup
The project is configured to run in the Replit environment:
1. Python 3.11 is installed
2. Dependencies are managed via requirements.txt
3. Run workflow executes `python main.py`

## How It Works
The `calculate()` function in `mean_var_std.py` should:
- Accept a list of 9 numbers
- Convert it to a 3x3 NumPy array
- Calculate statistics (mean, variance, std deviation, max, min, sum)
- Return results for axis 0, axis 1, and flattened array
- Raise ValueError if list doesn't contain exactly 9 numbers

## Recent Changes
- 2025-11-21: Initial Replit environment setup
  - Installed Python 3.11
  - Updated numpy from 1.18.5 to >=1.21.0 for Python 3.11 compatibility
  - Added comprehensive .gitignore for Python projects
  - Configured workflow to run main.py
  - Created project documentation
