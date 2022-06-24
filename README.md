# R and R Studio


## Statistical Analysis and Hypothesis Testing in R
### The basic process to analyze datasets using R:
- Extract, Transform, and Load (ETL) data
- Visualize the data
- Perform statisical tests, create regression models
- Interpret the results

### A Detailed Look Ahead
- Load, clean up, and reshape datasets using **tidyverse** in R.
- Visualize datasets with basic plots such as line, bar, and scatter plots using **ggplot2**.
- Generate and interpret more complex plots such as boxplots and heatmaps using **ggplot2**.
- Plot and identify distribution characteristics of a given dataset.
- Formulate null and alternative hypothesis tests for a given data problem.
- Implement and evaluate simple linear regression and multiple linear regression models for a given dataset.
- Implement and evaluate the one-sample t-Tests, two-sample t-Tests, and analysis of variance (ANOVA) models for a given dataset.
- Implement and evaluate a chi-squared test for a given dataset.
- Identify key characteristics of **A/B testing**.
- Determine the most appropriate statistical test for a given hypothesis and dataset.

# Getting Started with R
## 1.1 Introduction to R
### Benefits of R
- Versatile and extensible programming language with many benefits
- Scripts are written in plaintext
- Versions of plaintext files are easy to control using tools such as Git
- R analysis scripts (or RScripts) are highly reproducible and easy to share with peers and collaborators
- Process of loading in a dataset, visualizing the data, and performing statistical tests is straightforward and easy to interpret
- Many useful data transformation and modelling libraries, such as the tidyverse package, that simplify the process of ETL and visualizations

### RStudio Integrated Development Environment
- RStudio is an integrated development environment (IDE) used to help design and test RScripts
- RStudio provides users a graphical user interface (GUI) with multiple dynamic windows and perpetual access to their RScript and R console
- RStudio enables users to test their analysis scripts line by line while allowing users to view different environment variables and outputs
- This means that for each line of code written and executed, users can verify the results and troubleshoot any problems quickly and easily

## 1.2 Install R
- We must first install R before installing RStudio
- This way, RStudio can easily find our R installation while being configured
- Otherwise, we would have to manually tell RStudio where to find our installed applications

### Install R on macOS or Windows
- Navigate to R's Comprehensive R Archive Network (CRAN) server ([Links to an external site.](https://cran.r-project.org/mirrors.html))
- Select a mirror link near our region
- After you navigate to a CRAN mirror site, you'll reach a self-explanatory download page
- For those running a **macOS** environment, select the latest release .pkg file
- For those running a **Windows** environment, click on the base installer link
- On the next page, click the "Download R for Windows" link to start downloading the installer

### Following Successful Download
- Once your installer files are successfully downloaded (.pkg for macOS or .exe for Windows), run them just as you would for any other installation program
- Use all default install options and, if prompted, check all boxes to allow all R components to install.

## 1.3 Install R Studio
-  Navigate to the RStudio Download Page ([Links to an external site.](https://www.rstudio.com/products/rstudio/download/?utm_source=downloadrstudio&utm_medium=Site&utm_campaign=home-hero-cta#download))
-  select the most appropriate installer link
-  If you're using **macOS**, drag the RStudio application into your application folder
-  If you're a **Windows** user, run it through the installer as you would with any other Windows program
-  Once you have R and RStudio installed, run RStudio for the first time, get acquainted with the software, and install our required packages

### Navigate and Configure RStudio
-  notice four panes laid out within the application window
-  The bottom-left pane contains the R console
-  The top-left pane contains your source, or (any RScripts, tables, and files you open within RStudio)
-  By default, RStudio will open an untitled RScript file in the pane
-  The top-right pane contains our environment objects, such as variables, functions, and data frames
-  On the bottom right is the multi-tool pane, which contains tabs for a file explorer, R documentation help, installed package list, and a plot viewing tool

### Install Required Libraries
- **tidyverse** ([Links to an external site.](https://www.tidyverse.org/)) simplifies the installation process for the most common data analysis packages in R
-  To install packages in our R environment, use the install.packages() function
-  to install the tidyverse in our R environment, simply run the following command in the R console:

> install.packages("tidyverse")

# Programming and ETL in R
## 2.1 Fundamentals of R Programming


## 2.2 Functions in R


## 2.3 Read and Write Using R


## 2.4 Select Data in R


## 2.5 Transform, Group, and Reshape Data Using the Tidyverse Package


# Visualize Your Data Using ggplot2
## 3.1 Introduction to ggplot2


## 3.2 Build a Bar Plot in ggplot2


## 3.3 Add Formatting Functions


## 3.4 Build a Line Plot in ggplot2


## 3.5 Create Advanced Boxplots in ggplot2


## 3.6 Create Heatmap Plots


## 3.7 Add Layers to Plots


# Introduction to Statistical Tests
## 4. 1 Identifying Statistical Test Types


## 4. 2 Identify Different Data Types


## 4. 3 Dive Into Distributions


## 4. 4 Test for Normality


## 4. 5 Understand Skew


# Introduction to Hypothesis Testing
## 5.1 Practice Hypothesis Testing


## 5.2 Assess Error in Hypothesis Testing


# Perform an Analysis of Means in R
## 6.1 Sample Versus Population Dataset


## 6.2 Use the One-Sample t-Test


## 6.3 Use the Two-Sample t-Test


## 6.4 Use the Two-Sample t-Test to Compare Samples


## 6.5 Use the ANOVA Test


# Correlation and Regression in R
## 7.1 The Correlation Conundrum


## 7.2 Return to Linear Regression


## 7.3 Perform Multiple Linear Regression


# Characterize Categorical Data
## 8.1 Category Complexities


# Getting Real With A/B Testing
## 9.1 Practice A/B Testing


# Choose the Right Test for Your Data
## 10.1 Whose Analysis Is It Anyway?
