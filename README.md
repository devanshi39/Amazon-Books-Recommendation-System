# Amazon-Books-Recommendation-System
![GitHub](https://img.shields.io/github/license/devanshi39/Amazon-Books-Recommendation-System)
![GitHub pull requests](https://img.shields.io/github/issues-pr/devanshi39/Amazon-Books-Recommendation-System)
![GitHub repo size](https://img.shields.io/github/repo-size/devanshi39/Amazon-Books-Recommendation-System)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/devanshi39/Amazon-Books-Recommendation-System)
![GitHub top language](https://img.shields.io/github/languages/top/devanshi39/Amazon-Books-Recommendation-System)
![GitHub contributors](https://img.shields.io/github/contributors/devanshi39/Amazon-Books-Recommendation-System)

## What is Recommendation System?
For e-commerce platforms like Amazon, recommendation systems have become a crucial tool for giving users tailored suggestions based on their preferences and prior interactions with the platform. Collaborative filtering (CF) and content-based filtering (CBF) are two common techniques employed in recommendation systems. While CF uses user-item interactions to suggest items to users with comparable preferences, CBF makes use of item characteristics to do so. Each method, however, has drawbacks, such as the cold start issue in CF and the incapability to record intricate user preferences in CBF. 

This repo proposes a hybrid approach that combines collaborative filtering (CF) and content-based filtering in order to enhance the effectiveness of Amazon’s
book recommendation system. (CBF). By adding item characteristics, the suggested approach improves the user-item interaction statistics used in CF. The research compares
the performance of the proposed approach to other CF and CBF-based approaches while evaluating it on a real-world dataset of book ratings from Amazon. The objective is to
determine whether the suggested strategy performs better in terms of accuracy and coverage than the baseline approaches. In order to enhance the effectiveness of recommender systems across a range of applications, the research also investigates the potential application of the suggested approach in other domains.

## About the dataset
The Amazon Rating mini-dataset contains multiple datasets for different categories, and we will focus on the Books and Kindle Store data. Upon initial analysis, we discovered that the Books data has 15,362,619 unique users, while the Kindle data has 2,409,261 unique users. Additionally, there are 1,780,433 users who have provided ratings for both categories, which can aid in creating more effective recommendations that span across categories.

## Getting Started

## Tools and Technology Used
1. Python 3
2. Surprise Library
3. Vader sentiment Analyzer
4. Single value decomposition
5. CUDA Python
6. Google Collab

## Contributors
