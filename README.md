# EDA of Mobile Banking Data in Kenya

## Author

**Grace Karanja**

## Overview

This project focuses on the **Exploratory Data Analysis (EDA)** of mobile banking data in Kenya. The analysis was conducted using the **R programming language**, and the results were documented in an RMarkdown-generated report. This submission was prepared as part of an interview for the **Data Analyst position** at a Research Center.

## Key Highlights

- **Objective**: To uncover insights about mobile banking usage, preferences, and safety concerns among users in Kenya.
- **Dataset**: Data collected from a survey on mobile banking services in Kenya, with 43 rows and 11 variables.
- **Tools Used**:
  - **Programming Language**: R
  - **Visualization Libraries**: `ggplot2`, `gridExtra`
  - **Data Manipulation Libraries**: `dplyr`, `tidyverse`, `data.table`
  - **Report Generation**: RMarkdown

## Analysis Process

1. **Data Importation**  
   The dataset was imported into R, and unnecessary columns were removed for a cleaner analysis.

2. **Data Inspection**

   - Checked data structure, identifying categorical variables.
   - Verified the absence of missing values, ensuring data integrity.

3. **Variable Distributions**

   - Visualized and analyzed categorical variables such as **gender**, **age range**, and **mobile banking preferences**.
   - Identified patterns in mobile banking usage and safety perceptions.

4. **Insights**
   - **Gender**: Males were slightly more represented, and they appeared more satisfied with mobile banking services.
   - **Age Range**: Most respondents were younger (21–30 years), with older respondents being the least represented.
   - **Usage Patterns**: Mobile banking was primarily used for payments and withdrawals.
   - **Safety**: Concerns about safety were common, particularly among male respondents.

## Tools for Visualization and Analysis

Custom functions were created for plotting histograms and bar charts to explore categorical variables. These visualizations helped derive insights into mobile banking preferences, satisfaction, and concerns.

## Conclusion

- **Mobile Banking Preferences**: Mobile banking is mainly favored by younger users for its convenience.
- **Safety Concerns**: While satisfaction with services is high, safety remains a significant issue.
- **Bank Visits**: Mobile banking has reduced the frequency of physical bank visits.

This project highlights the importance of understanding user demographics and perceptions to improve mobile banking services and address concerns, especially regarding security.

## How to Use the Project

This project is structured as an RMarkdown file, allowing for easy replication and customization of the analysis. Follow the steps below to explore the data:

1. **Clone the Repository**:  
   Download or clone the project files from the repository.

2. **Set Up R Environment**:  
   Ensure R and RStudio are installed. Install the required libraries using the following command:
   ```R
   required_packages <- c('data.table', 'tidyverse', 'gridExtra', 'corrplot', 'GGally', 'ggplot2', 'e1071', 'dplyr')
   install.packages(required_packages, dependencies = TRUE)
   ```
