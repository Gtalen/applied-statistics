# Applied-statistics 8651 2025/2026 Module Assignment

## ATU Galway

## Author: Ebelechukwu Igwagu G00439334@atu.ie


This repository contains solutions to four applied statistical problem using Python. The problems cover key statistical techniques including experimental design, randomization, simulation based sample generation, hypothesis testing, the normal and standard normal distributions, paired sample t tests, and one way ANOVA. The notebook [problems.ipynb](https://github.com/Gtalen/applied-statistics/blob/main/problems.ipynb) provides an overview of each problem, explains the approach used to solve it, and discusses the main findings.

## Repository Content

- README.md: Overview of the assessment and approach  
- problems.ipynb: Jupyter Notebook containin solutions, simulations, and explanations  
- requirements.txt: Python dependencies required to run the notebook

## How to Run

1. Create a virtual environment (optional but recommended)

      ```bash
      python -m venv venv
      venv\Scripts\activate
      ```

2. Install Required Packages

   ```
   pip install -r requirements.txt
   ```

3. Open and run the notebook:
   ```
     problems.ipynb

   ```

## Problem Summary

### 1. Lady Testing Tea

This experiments simulates the of probaility of choosing rightly if milk or tea was first added to a cup of tea.

**Test of Hypothesis**

NULL HYPOTHESIS
- The Lady cannot tell the difference between the cups of tea with tea in first versus those with milk in first
- The Lady is randomly choosing the 4 cups of tea frm the 12 at random


ALTERNATE HYPOTHESIS
- The Lady is able to differentiate between the cups of tea with milk in first from those with tea in first

.EVIDENCE

### 2. Standard Normal Distribution and degree of freedom

ddof means degree of freedom ddof=1 is used for calculating the sample standard devaition while ddof=0 is used to calculate the population standard deviation as described by [tidystat](https://tidystat.com/when-to-use-ddof1-in-np-std/) and in the official [numpy.std](https://numpy.org/devdocs/reference/generated/numpy.std.html) documentation.

## Software Used

- Python 3.2
- NumPy
- SciPy
- Matplotlib

## Contributors

Author: Ebelechukwu Igwagu

## Additional Acknowledgement

- Github copilot - Aided with codes autocompletion
- ChatGPT AI (2025). Productivity aid and debugging.
Hovever, the scope, logic, and decisions remain fully original to the author.

## Want to contribute?

This project is open to contributions! Feel free to fork the repository, submit issues, or create pull requests. All contributions are welcome.

## License

This project is available under the MIT license.
