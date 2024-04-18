> [!note]
This project is still work in progress

# Luciphr-as-a-Service: Excel to R, Simplified

Transform your cluttered Excel datasets into clean, R-compatible data frames with ease using Luciphr-as-a-Service (LaaS).
This platform leverages the power of the [Lucifer R package](https://github.com/Rindrics/lucifer) to streamline the process of data consolidation, even across multiple sheets and directories, into a single, manageable format.

## Background

In fields where data aggregation and analysis are continuous and dynamic, Microsoft Excel is frequently the tool of choice.
Despite its versatility, Excel's usability diminishes when dealing with complex files that have undergone numerous modifications.
These files often become poorly maintainable and hardly readable by machines.

Luciphr-as-a-Service addresses these issues by providing a graphical interface that simplifies the use of the Lucifer package, which is not yet registered on CRAN as of April 2024.
This service is particularly beneficial for teams needing to upgrade their data analysis tools but are intimidated by the steep learning curve of new software.

## Key Features

### User-Friendly File Uploads:

Easily upload your Excel files directly into the platform.

### Interactive Excel Viewer:

Utilize a built-in Excel viewer to interactively select cells and construct parameters required for data transformation.

### Real-Time Data Preview:

Instantly preview the output of the Lucifer package to verify the correctness of the selected parameters and the expected data structure.

### Efficient R Code Generation:

Automatically generate the R code necessary for your data transformation, which you can run within the platform or export for external use.

### Seamless Downloads:

Download the cleaned data as `.rda` files or export the generated R script for further analysis in your preferred environment.

## Streamlined Interface

LaaS’s interface is designed for simplicity.
Our intuitive dashboard facilitates the entire process from data upload to transformation, making it accessible even to those with minimal technical expertise.
Check out our [design prototype on Figma](https://www.figma.com/file/P5TJFy65N3wg5j882LSjPx/LaaS-UI?type=design&node-id=0%3A1&mode=design&t=Y0FrNXDDz057ZpvF-1) for a more detailed look.
