# DS4002-CS3

## Contents


## Section 1: Software and Platform 
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


## Section 2: Documentation Map
Project Structure
```
Project
├── DATA
│   ├── appendix.md
│   └── theoffice.rda
├── LICENSE
├── OUTPUT
│   └── placeholder
├── README.md
└── SCRIPTS
    └── DS4002_Analysis.Rmd
```

## Section 3: Reproducing

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
