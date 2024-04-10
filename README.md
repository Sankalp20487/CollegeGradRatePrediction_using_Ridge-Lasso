# CollegeGradRatePrediction

## Overview
`CollegeGradRatePrediction` is a repository containing the analysis and comparison of Ridge, LASSO, and stepwise feature selection methods applied to the `College` dataset from the `ISLR` library. The objective is to predict the graduation rate (`Grad.Rate`) of colleges using these regularization and feature selection techniques.

## Author
- Sankalp Biswal

## Key Features
- Implementation of Ridge and LASSO regression models.
- Comparison with stepwise feature selection method.
- Evaluation of models based on root mean square error (RMSE).
- Detailed interpretation and insights from the models' coefficients and performance metrics.

## File Descriptions
- `RegularizationAnalysis.Rmd`: R Markdown file containing the full analysis, code, and interpretations.
- `RegularizationAnalysis.html`: Compiled HTML version of the analysis for easy viewing.
- `RegularizationAnalysis.pdf`: PDF version of the analysis.
- `README.md`: This file, providing an overview and instructions for the repository.

## How to Use
1. Clone this repository to your local machine.
2. Open the R Markdown file (`ALY6015_SankalpBiswal_Week4_Winter_2024.Rmd`) in RStudio or any R Markdown editor.
3. Run the code chunks sequentially to reproduce the analysis and results.
4. Refer to the compiled `html` or `pdf` files for a detailed write-up and interpretations of the results.

## Dependencies
- R and RStudio
- R packages: `ISLR`, `MASS`, `caret`, `glmnet`, `caTools`, `knitr`, `kableExtra`, `ggplot2`

## References
1. Frasca. (n.d.). Lab: Regularization Video [Video]. Panopto.
2. OpenAI. (2021). ChatGPT (Version 3.5). OpenAI. <https://chat.openai.com/>
3. Shapiro, V. 4b__Regularization - revised in Jan 2024 [.Rmd file].
4. Northeastern University. (n.d.). ALY6015 Feature Selection R [PDF file].

## License
This project is open-source and available under the MIT License. See the LICENSE file for more details.
