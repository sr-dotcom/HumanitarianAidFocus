# HumanitarianAidFocus
Data-driven analysis and clustering of countries to prioritize and strategize humanitarian aid distribution by HELP International. The repository includes data cleaning, exploratory analysis, and clustering techniques to identify countries in dire need of assistance

# Assignment: Part I

## Problem Statement

HELP International is an international humanitarian NGO committed to fighting poverty and providing the people of backward countries with basic amenities and relief during the time of disasters and natural calamities. It regularly runs operational projects, along with advocacy drives, to raise awareness and for funding purposes.

After the recent funding programmes, they were able to raise around $10 million. Now, the CEO of the NGO needs to decide how to use this money strategically and effectively. The significant issues that arise while taking these decisions are mostly related to choosing the countries that are in dire need of aid.

This is where you come in as a data analyst. Your job is to categorise the countries using some socio-economic and health factors that determine the overall development of the country. Then, you need to suggest the countries that the CEO needs to focus on the most. The data sets containing those socio-economic factors and the corresponding data dictionary are provided below.

> **Note:** The inflation definition in the data dictionary has a typo. The correct definition would be the measurement of the annual growth rate of the GDP deflator.

## Objectives

Your main task is to cluster the countries by the factors mentioned above and then present your solution and recommendations to the CEO using a PPT. The following approach is suggested:

- Start off with the necessary data inspection and EDA tasks suitable for this data set - data cleaning, univariate analysis, bivariate analysis, etc.
- You must perform the outlier analysis on the data set. However, you do have the flexibility of not removing the outliers if it suits the business needs or a lot of countries are getting removed. All you need to do is find the outliers in the data set, and then choose whether to keep them or remove them, depending on the results you get.
- Try both K-means and Hierarchical clustering (both single and complete linkage) on this data set to create the clusters. (Note that both the methods may not produce identical results, and you might have to choose one of them for the final list of countries.)
- Analyse the clusters and identify the ones that are in dire need of aid. You can analyze the clusters by comparing how these three variables (gdpp, child_mort and income) vary for each cluster of countries, and recognise and differentiate the clusters of developed countries from the clusters of underdeveloped countries.
- Also, you need to perform visualisations on the clusters that have been formed. You can do this by choosing any two of the three variables mentioned above on the X–Y axes and plotting a scatter plot of all the countries and differentiating the clusters. Make sure you create visualisations for all the three pairs. You can also choose other types of plots like boxplots.

## Expected Results

Go through the expected results below:

1. A well-commented Jupyter notebook containing the Clustering Models(both K-means and Hierarchical Clustering) and the final list of countries.
2. Present the overall approach of the analysis in a presentation including the following:
    - Mention the problem statement and the analysis approach.
    - Explain the results of the Clustering Model briefly.
    - Include visualisations and summarise the most important results in the presentation.
    - Make sure that you mention the final list of countries here (Do not just mention the cluster id or cluster name. Mention the names of all the countries.)

You need to submit the following two components:

- **Python notebook**: They should include detailed comments and should not contain unnecessary pieces of code.
- **PPT**: Make a PPT to present your analysis to the CEO (you should include both the technical and the business aspects). The PPT should be concise, clear and to the point. Submit the PPT after converting into the PDF format. The visualisations mentioned above must be present in this file.

# Assignment: Part II

This part of the assignment is subjective, and hence, you are required to write the answers and submit them in a PDF file. For writing normal text, you can use MS Word or any other similar software that can convert word files to the .pdf format. You can write equations, draw figures, etc., on a blank sheet of paper, photograph the images and upload them in the same word document.

Please limit your answers to 200–300 words per question. While calculating values, ensure you write all the necessary steps and formulae. Also, use the correct terminology to present the solution.

## Question 1: Assignment Summary

Briefly describe the 'Clustering of Countries' assignment that you just completed in 200–300 words. Mention the problem statement and the solution methodology that you followed to arrive at the final list of countries. Explain your main choices briefly (what EDA you performed, which type of clustering produced a better result and so on).

> **Note:** You do not have to include any images, equations or graphs for this question. Just text should be enough.

## Question 2: Clustering

This question is further divided into multiple questions as stated below:

1. Compare and contrast K-means clustering and hierarchical clustering.
2. Briefly explain the steps of the K-means clustering algorithm.
3. How is the value of 'k' chosen in K-means clustering? Explain both the statistical as well as the business aspect of it.
4. Explain the necessity of scaling/standardisation before performing clustering.
5. Explain the different linkages used in hierarchical clustering.


