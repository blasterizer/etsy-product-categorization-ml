<h1 align="center">Optimizing E-Commerce Product Categorization Using Textual Data</h1>
<p align="center">
<img src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue"/>
<img src="https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white"/>
<img src="https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
<img src="https://img.shields.io/badge/NLP-blue?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&color=525252"/>
</p>
## Overview
This repository contains the resources and code for my Machine Learning Project at Dublin City University, focusing on enhancing product categorization and authentication for the Etsy e-commerce platform using advanced machine learning techniques.

## Project Description
The primary goal of this project was to develop a machine learning approach to improve product classification and authentication on Etsy, addressing the following key areas:

Categorizing products into 'top category' and 'bottom category'
Identifying 'primary color' and 'secondary color'
Enhancing user experience and operational efficiency
Ensuring product authenticity and fraud detection

The project utilized various machine learning models to analyze product titles, descriptions, and tags, aiming to predict customer preferences and authenticate products accurately.

## Technologies Used

Python: Main programming language
Natural Language Processing (NLP): For text data processing
CountVectorizer: For converting text data into numerical format
Scikit-learn: For implementing machine learning models including:
Pandas and NumPy: For data manipulation and analysis

K-Means Clustering
KNN Classifier
Multinomial Naive Bayes
Multi-label Logistic Regression


## Results

The Multi-label Logistic Regression model demonstrated superior performance, achieving the highest accuracy (90.30%) in identifying product categories.
K-Means Clustering was used to understand data patterns, with the top category ID showing the lowest Mean Squared Error.
The models showed varying performance across different category types, with color prediction presenting more challenges than top and bottom category predictions.

## Conclusion
This project provided valuable insights into applying machine learning techniques to e-commerce data, particularly in the context of Etsy's unique marketplace for handmade and vintage items. The research demonstrated the potential of these techniques to enhance product categorization, improve user experience, and contribute to fraud detection efforts.

## Future Work
Future iterations of this project aim to:
Refine data sampling techniques to increase model accuracy
Enhance image processing methods to improve color prediction
Explore additional methodologies to boost performance across all category types
