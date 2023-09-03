# Grouping-Of-Movies

# Movie Clustering Project

## Overview

Welcome to the Movie Clustering Project! This personal project is dedicated to grouping similar movies based on their plot summaries using advanced unsupervised machine learning techniques. In this project, we utilize K-Means clustering, Dendrograms for visual representation, TF-IDF Vectorizer, and Similarity distance to accomplish this exciting task.

## Project Details

### Clustering Methodology

- **K-Means Clustering:** Our primary approach involves employing the K-Means algorithm to categorize IMDb movies into clusters based on the similarity of their plot summaries. This allows us to uncover hidden patterns and relationships between movies that might not be immediately obvious.

- **Dendrograms for Visual Insights:** To provide a clear visual representation of the closeness between clustered movies, we employ Dendrograms. These dendrogram visualizations help users understand the hierarchical structure of movie clusters.

### Movie Similarity Quantification

- **TF-IDF Vectorizer:** To quantify the similarity between movies, we utilize a Term Frequency-Inverse Document Frequency (TF-IDF) Vectorizer. This technique helps us measure how closely related the content of one movie's plot summary is to another, allowing for precise clustering.

- **Similarity Distance:** We calculate the similarity distance between movies using both IMDb and Wikipedia plot summaries. This dual-source approach enhances the accuracy and reliability of our similarity assessments.

## How to Use

1. **Clone the Repository:** Begin by cloning this repository to your local machine using Git.

2. **Install Dependencies:** Make sure to install the necessary libraries and dependencies outlined in the project's requirements file.

3. **Run the Provided Scripts:** Execute the provided Jupyter Notebook or Python script to initiate the clustering and similarity quantification process.

4. **Explore the Results:** Dive into the generated clusters and explore the insightful patterns and relationships uncovered by our model.

## Data Sources

- **IMDb Plot Summaries:** We leverage IMDb's extensive database of movie plot summaries to feed our clustering and similarity analysis.

- **Wikipedia Plot Summaries:** In addition to IMDb, we also consider Wikipedia's plot summaries to enrich our dataset and enhance the quality of our clustering.

## Project Structure

- `data/`: This directory houses the data files used in the project, including IMDb and Wikipedia plot summaries.

- `notebooks/`: Here, you'll find the Jupyter notebooks that detail our data analysis, clustering methods, and visualization techniques.

- `scripts/`: The Python scripts necessary to run the project are stored in this directory.

- `results/`: This directory contains all the output files and visualizations generated during the project.

## Acknowledgments

We extend our gratitude to IMDb and Wikipedia for providing the valuable data that made this project possible. Without their extensive databases of movie information, this analysis would not have been achievable.

## License

This project is licensed under the MIT License. For full details, please refer to the [LICENSE.md](LICENSE.md) file in the repository.
