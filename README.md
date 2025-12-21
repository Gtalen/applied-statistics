# Applied-statistics 8651 2025/2026 Module Assignment

## ATU Galway

## Author: Ebelechukwu Igwagu G00439334@atu.ie


This repository contains solutions to four applied statistical problem using Python. The problems cover key statistical techniques including experimental design, randomization, simulation based sample generation, hypothesis testing, the normal and standard normal distributions, paired sample t tests, and one way ANOVA. The notebook [problems.ipynb](https://github.com/Gtalen/applied-statistics/blob/main/problems.ipynb) provides an overview of each problem, explains the approach used to solve it, and discusses the main findings.

## Repository Content

- problems.ipynb: Jupyter Notebook containing solutions, simulations, and explanations  
- requirements.txt: Python dependencies required to run the notebook
- README.md: Overview of the assessment and approach  
- License.md: Contains the license copyright information

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

**Lady Tasting Tea**

This assignment simulates an extended version of Fisher's Lady Tasting Tea experiment using 12 cups of tea (4 milk-first, 8 tea-first). The probaility of correctly identifying all cups by chance is estimated and compared to the original 8-cup experiment using statistical testing techniques such as probability and hypothesis testing.

**Problem 2 – Normal and Standard Normal Distribution**  
100,000 samples of size 10 were generated from normal and standard normal distributions using `numpy.random.normal`. This was used to demonstrate the effect of the mean and standard deviation on the population and sample statistics.

**Problem 3 – Type II Error**  
The probability of making a Type II error was simulated in independent-samples t-tests. 

**Problem 4 – ANOVA vs Multiple t-Tests**  
Three independent samples are generated and compared using one-way ANOVA and multiple pairwise t-tests. The Bonferroni correction and Tukey post-hoc tests were applied to demonstrate differences in rejection rates and to highlight why ANOVA is preferred when testing multiple groups.

## Reflective  Learning

These assignments provided valuable insight into applying statistical techniques to real-world problems. They highlight the importance of experimental design, sample size, confidence intervals, and the choice of appropriate statistical tests—including probability and hypothesis testing, t-tests, ANOVA, and post-hoc comparisons. It deepened my understanding of how these factors are core considerations in study design and how they help reduce the rates of Type I and Type II errors.


## Software Used

- Python 3.12
- NumPy
- SciPy
- Matplotlib

## Contributors

Author: Ebelechukwu Igwagu

## Additional Acknowledgement

- Github copilot - Aided with code autocompletion
- ChatGPT AI (2025). Productivity aid and debugging.
Hovever, the scope, logic, and decisions remain fully original to the author.

## Want to contribute?

Do you have a different and a better approach to these questions? This is open to contributions! Feel free to fork the repository, submit issues, or create pull requests. All contributions are welcome.

## License

This project is available under the MIT license.
