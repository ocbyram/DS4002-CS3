# DS4002-CS3

## Contents


# Section 1: Software and Platform 
- Software: The following tools/programs were used to perform analysis
    - [R (3.3.0+)](https://cran.rstudio.com/)
    - [R Studio (2023.12.1)](https://posit.co/download/rstudio-desktop/)
    - [Python (3.10.12)](https://www.python.org/downloads/)
    - [Git](https://git-scm.com/)
- Hardware: Analyses were run on the following Hardware and Operating systems
    - Dell Latitude 7480 (Ubutnu 22.04.2)
    - Windows Surface
- Dependencies: 
    - [Schrute](https://github.com/bradlindblad/schrute 
) 


# Section 2: Repository Content Description

This repository is to help perform the case study "Analyzing Character Line Impact in The Office".

## Hook.pdf: 
    The "Hook.pdf" pdf is a general description of the case study and the motivation behind it. It also includes wat the deliverables for completing this case study are. 

## Articles: 
    The "articles" folder contains two articles. The first file serves as a motivator for this particular case study topic. The second file includes a description of doing Sentiment Analysis in R, which helps with the technical aspects of this case study. 

## Data:
    The "data" folder includes all of the data included in this case study. This data must be downloaded for the analysis code to run correctly. This folder also includes the data appendix that describes the data source and the variables within the data. 

## Rubric:
    The "rubric.pdf" file details the exact specifications of this case study. It outlines the deliverables that will be produced and how to correctly do so. 

## Code:
    The "code" folder includes the code that was previously written to perform the analysis. This code must be downloaded to complete the analysis and produce the correct output. 

# Section 3: Reproducing Analysis

Before starting ensure that you have all the required software installed as outlined in [Section 1](#section-1:-software-and-platform). We also
encourage use of either Mac, Windows or Ubuntu, as that is what the analysis was tested on, although other operating systems may work. 

Step 1:
Open your R software and import the 'Schrute' package. There is a dataframe within the package titled 'theoffice'. This is the dataframe that we manipulated to obtain our results. 

Step 2:
Ensure that your seed is set to 0 (set.seed(0)). This will guarantee you identical results to ours. 

Step 3:
Download the code that we have uploaded to the 'SCRIPTS' folder, and run the file. It should be seamless provided that you have already installed Schrute, TidyVerse, and ggplot2. It will output the same results as us. 

Step 4:
You can analyze these results in your own way, or look through our presentation to see the conclusions that we drew. 
