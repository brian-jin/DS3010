# Sommelier Reviews: A Regression and Semantic Analysis on Wine Enthusiast Reviews

## Overview
This is a term project completed for the course DS 3010 at Worcester Polytechnic Institute in B-Term of 2024. Our group looked at the [Wine Enthusiast reviews dataset](https://www.kaggle.com/datasets/zynicide/wine-reviews/data) posted on Kaggle by Zackthoutt who scraped the Wine Enthusiast website for reviews. The dataset contained ~129k reviews after cleaning and initial EDA for us to perform data analysis. We applied regression analysis to understand the numerical features of the dataset and weighed how reviewer bias played a role in our data. With that, we performed stratified standardization to normalize around individual reviewer bias and avoid leaning into misleading review scores with globally pooled reviewer scores. After that, we looked toward preprocessing the review text and performed semantic analysis through a pretrained sentence embedding model.

## Goal
Our goal was to create business value out of a Wine Enthusiast analysis with a search tool that would allow customers to describe their perfect wine based on Wine Enthusiast reviews, using a keyword extraction for generating "tags" for different wines. This plays into distributors who can also utilize the data and search features for market research. 

## Future Work
Future work includes a Naive-bayes method for analyzing reviews that contain certain words and the review score of those wines.
We also look toward a word embedding model that looks at word connotations and its effect on ratings/review scores. An example is “history”, “vintage”, “aged”.
