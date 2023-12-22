# Course Recommendation System

## Overview

This project aims to develop a Course Recommendation System that leverages Exploratory Data Analysis (EDA), utilizes APIs to obtain the country where a university is located, and generates top recommendations based on a given course name. The recommendation system employs content-based filtering using cosine similarity to provide personalized suggestions to users.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Data Sources](#data-sources)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Content-Based Filtering](#content-based-filtering)
- [Results](#results)
- [Future Enhancements](#future-enhancements)

## Introduction

The Course Recommendation System is designed to assist users in finding relevant courses based on their interests and preferences. It incorporates EDA to understand the dataset, utilizes APIs to fetch additional information about the universities, and employs content-based filtering using cosine similarity to generate recommendations.

## Features

- **Exploratory Data Analysis (EDA):** Gain insights into the dataset, understand patterns, and identify key features.
  
- **API Integration:** Utilize APIs to fetch the country where a university is located, enhancing the recommendation system with geographical information.

- **Content-Based Filtering:** Implement a content-based filtering approach using cosine similarity to recommend courses based on their similarity to user preferences.

- **Top Recommendations:** Generate and display the top course recommendations given a specific course name as input.

## Prerequisites

- Python 3.x
- Jupyter Notebook
- Required Python libraries (specified in the `requirements.txt` file)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/SnehShah17/Course_Recommendation_System.git
    ```

2. Install the required libraries:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Open the Jupyter Notebook (`course_recommendation_system.ipynb`) in your preferred environment.
2. Follow the instructions in the notebook to run the code and generate course recommendations.

## Data Sources

The dataset used for this recommendation system is the [EdX Courses Dataset 2021](https://www.kaggle.com/datasets/khusheekapoor/edx-courses-dataset-2021) obtained from Kaggle.

## Exploratory Data Analysis

Perform a thorough EDA to understand the dataset, identify missing values, explore distributions, and visualize key trends.

![image](https://github.com/SnehShah17/Course_Reccomendation_System/assets/75317219/c11394ff-4a32-448e-a0f0-a0744bae8f99)

![image](https://github.com/SnehShah17/Course_Reccomendation_System/assets/75317219/95d816e6-0f5a-470a-868a-be0cc8e59d93)

![image](https://github.com/SnehShah17/Course_Reccomendation_System/assets/75317219/69db2c0c-d922-462b-a673-f3fb0aa70071)


## Results

### Content-Based Filtering using Cosine Similarity and TF-IDF Vectorizer:
The system employs content-based filtering, utilizing the TF-IDF (Term Frequency-Inverse Document Frequency) vectorizer to represent courses as numerical vectors based on their textual content. Cosine similarity is then applied to measure the similarity between these vectors, allowing the system to recommend courses closely related to a user's preferences. This technique takes into account the importance of words in describing the content of each course, enhancing the precision of recommendations by considering the relevance of terms in the course descriptions. The TF-IDF vectorizer and cosine similarity together contribute to a robust content-based filtering mechanism, offering personalized suggestions that align with the textual features of courses and user preferences.

![image](https://github.com/SnehShah17/Course_Reccomendation_System/assets/75317219/28ebbd94-0c94-451c-b97b-69ac7352797b)


## Future Enhancements

Future improvements include different techniques for broader recommendations, user feedback integration for continuous learning, and real-time updates for dynamic course preferences, enhancing the system's overall functionality and user satisfaction.
