![header](header.png)

# Improving the Number of Review: Exploring Review Patterns in Bangkok's Airbnb Landscape
## Abstract
Despite the increasing number of reviews, approximately 36% (or 5.7 thousand) of Airbnb listings in Bangkok have not received any reviews according to their records between 2012 and 2022. This project investigates potential factors contributing to the lack of reviews in certain listings in the capital city of Thailand. A comparative analysis was carried out to address this challenge and offer several actionable recommendations to the Host Engagement Manager at Airbnb Thailand. 

The analysis suggest that unreviewed Airbnb listings in Bangkok tend to have higher prices and longer minimum stay requirements compared to reviewed ones, potentially discouraging guests from booking and leaving reviews. Reviewed listings, often entire homes or apartments, experience higher booking rates and are concentrated in central areas with ample public facilities. Additionally, listings closer to popular neighborhoods receive more reviews over time.

Based on the findings, we can offer several actionable recommendations to address the lack of reviews for unreviewed listings such as consider adjusting prices to be more competitive and revising minimum stay requirements, particularly for shared rooms; implementing promotional campaigns to incentivize guests to book and review unreviewed listings, and focusing marketing efforts on highlighting unique features and nearby attractions in less central neighborhoods.

## Data
The dataset used for this analysis is available in the [data](https://github.com/LingAdeu/bangkok-airbnb-review-exploration/tree/main/data) folder. The dataset includes information on Airbnb listings in Bangkok such as locations, owners, pricing, and propeerty types. This analysis also leveraged geospatial data from Poom Wettayakorn's GitHub [repository](https://github.com/pcrete/gsvloader-demo/blob/master/geojson/Bangkok-districts.geojson).

## Contents
My analysis consists of five sections in which each of them is presented as follows:
1. <b>Introduction</b>: In this section, I give an overview about Airbnb, the business problem this company wants to solve, objective of the analysis, and short description about the dataset. 
2. <b>Initial Data Inspection</b>: This section inspects the dataset, starting from checking data types to descriptive statistics of the numeric columns. The aim of this section is to gain an understanding of the dataset prior to performing data preprocessing. 
3. <b>Data Preparation</b>: Before conducting a data analysis, data needs to be pre-processed. In this section, I explain a series of data checking, data type conversion, irrelevant column removal, and some treatments to outliers and missing data.
4. <b>Data Analysis</b>: I split this section into two: (1) an exploration of the problem stated in the introduction section, and (2) a question-guided analysis. For each question in the second part, I provide a takeaway message to summarize the key finding of each question.
5. <b>Conclusions</b>: To conclude my analysis, I give a summary of the findings from the previous section, and offer actionable recommendations for the stakeholder.

## Folder Organization

    .
    ├── README.md                           <- The top-level README for using this project.
    ├── data 
    │   ├── airbnb-listings-bangkok.csv     <- Dataset
    │   ├── bangkok-districts.geojson       <- Geospatial data for Bangkok, Thailand borders
    │   └── data-dictionary.pdf             <- Metadata (information about the data)
    ├── docs
    │   └── presentation.pptx               <- Presentation deck
    ├── requirements.txt                    <- The requirements file for reproducing the environment.
    │                                          Generated using `pip freeze > requirements.txt`
    └── src
        └── notebook.ipynb                  <- Data analysis in a Jupyter notebook file


## Usage
To replicate my analysis or explore the data further, kindly follow the following steps:
1. Clone this repository to your local machine.
```bash
git clone https://github.com/LingAdeu/bangkok-airbnb-review-exploration.git
```
2. Ensure that all necessary dependencies are installed, especially Python and Jupyter Notebook. Other than these, all libraries are specified on file requirements.txt which can be executed by running the following script on the terminal.

```bash
pip install altair==5.2.0 folium==0.16.0 geopandas==0.14.3 matplotlib==3.8.3 nltk==3.8.1 numpy==1.24.4 pandas==2.2.1 regex==2023.12.25 scipy==1.11.4 seaborn==0.11.0

```
3. Run my Jupyter Notebook file (`*.ipynb`) in src folder to reproduce the analysis.

## Tableau Public URL

> [!important] 
> This project also includes data visualization in Tableau for audience with a wider range of backgrounds. The Tableau dashboard can be accessed [here](https://public.tableau.com/shared/TWSRBZMHC?:display_count=n&:origin=viz_share_link).

## Feedback
If you have suggestions for improvements, feel free to contact me here:

<a href="https://www.linkedin.com/in/adelia-januarto/" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/linkedin/default.svg" width="52" height="40" alt="linkedin logo"/>
  </a>
<a href="mailto:januartoadelia@gmail.com" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/gmail/default.svg"  width="52" height="40" alt="gmail logo"/>
  </a>