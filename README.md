# CSD361 Project: Clinical Trials Clustering using Machine Learning

## Project Description

This project aims to utilize unsupervised machine learning techniques to cluster clinical trials, specifically focusing on Chimeric Antigen Receptor (CAR) T cell therapy trials. The goal is to group similar trials based on attributes available in their respective records on ClinicalTrials.gov. The clusters will then be visualized and described to provide insights into the landscape of CAR T cell clinical trials.

## Background

Searching for similar clinical trials can be highly beneficial for various stakeholders, including trial participants, investigators, and researchers. It assists participants in finding alternative trials, enables investigators to connect with similar studies, and helps researchers synthesize evidence from related trials.

CAR T cell therapy has emerged as a promising treatment for hematologic cancers, resulting in a significant number of registered interventional trials. This project focuses on clustering these trials based on their attributes to provide a better understanding of the CAR T cell therapy landscape.

## Goals

- Cluster CAR T cell clinical trials based on their attributes.
- Visualize and describe the identified clusters.
- Evaluate clustering performance using Silhouette score and Callinski-Harabasz Index.
- Assess cluster stability through resampling and similarity comparison.

## Data Availability

The project utilizes data from ClinicalTrials.gov, a publicly accessible registry of clinical trials. A local instance of the database containing trial records is available for access. Additionally, a CSV file containing National Clinical Trial (NCT) IDs for CAR T cell trials is provided.

## Additional Resources

- Eligibility criteria for the trials are available, providing insights into patient enrollment requirements.
- Medical concepts identified in the eligibility criteria have been mapped to Unified Medical Language System (UMLS) concept identifiers.
- Each trial is associated with a "bag of medical concepts" from its inclusion and exclusion criteria.

## Evaluation

- Clustering performance will be evaluated using Silhouette score and Callinski-Harabasz Index.
- Cluster stability will be assessed through resampling and comparison of clusters across multiple datasets.

## Submission Guidelines

- Include code chunks for cluster performance and stability evaluation in your submission.
- Ensure clarity and reproducibility of results.
