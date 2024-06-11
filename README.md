This project demonstrates a survival analysis using the Kaplan-Meier method on the colon cancer dataset from the `survival` package in R. The analysis includes generating descriptive statistics, visualizing missing values and correlations, and plotting the Kaplan-Meier survival curve.

## Project Structure

- `analysis.R`: The R script containing the data loading, processing, and analysis steps.
- `main.tex`: The LaTeX document that compiles the analysis into a well-formatted report.
- `images/`: Directory containing the generated plots used in the LaTeX document.

## Analysis Steps

1. **Data Loading**: Load the `colon` dataset from the `survival` package.
2. **Descriptive Statistics**: Calculate and visualize basic statistics and field information.
3. **Missing Values**: Identify and visualize missing values in the dataset.
4. **Correlations**: Compute and plot the correlations between selected variables.
5. **Kaplan-Meier Survival Analysis**:
    - Create a survival object.
    - Fit the Kaplan-Meier survival curve.
    - Plot the Kaplan-Meier survival curve.

## Usage

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/colon-cancer-survival-analysis.git
    cd colon-cancer-survival-analysis
    ```

2. **Run the Analysis**:
    - Open `analysis.R` in RStudio or your preferred R environment.
    - Run the script to generate the plots and save them in the `images/` directory.

3. **Compile the LaTeX Document**:
    - Ensure you have a LaTeX distribution installed (e.g., TeX Live, MiKTeX).
    - Open `main.tex` in your LaTeX editor or Overleaf.
    - Compile the document to produce the report.

## Required Packages

The following R packages are required to run the analysis:
- `survival`
- `survminer`
- `dplyr`
- `corrplot`
- `DataExplorer`
- `kableExtra`
- `summarytools`

Install them using:
```r
install.packages(c("survival", "survminer", "dplyr", "corrplot", "DataExplorer", "kableExtra", "summarytools"))
