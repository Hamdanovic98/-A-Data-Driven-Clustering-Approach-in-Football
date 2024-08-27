# A Data-Driven Clustering Approach in Football

This project explores a data-driven approach to clustering football players based on their performance metrics. The analysis focuses on players from the top 5 European leagues over the last three seasons, with the primary goal of identifying and understanding player roles on the field beyond traditional positional labels. Additionally, the project tracks the evolution of certain high-profile players' roles over time, providing valuable insights for team management and recruitment strategies.

## Project Structure

* **FBRef Data/**: Directory containing the raw and processed data sourced from FBRef, including performance metrics of players across the top 5 European leagues.
* **A Data-Driven Clustering Approach in Football.pdf**: The main report that documents the entire analysis process, including data collection, preparation, clustering, and player role evolution. This PDF details the methodology, results, and conclusions drawn from the project.
* **Data Collection.ipynb**: Jupyter notebook detailing the steps taken to collect and preprocess the data from FBRef, including handling missing values and feature engineering.
* **Data Preparation.ipynb**: Jupyter notebook outlining the data preparation process, such as data cleaning, feature engineering, and transformation, preparing the dataset for clustering.
* **Players Clustering by Role.ipynb**: Jupyter notebook that walks through the clustering analysis, including applying K-Means clustering, evaluating clusters, and analyzing the evolution of player roles over multiple seasons.
* **ReadMe.md**: This file provides an overview of the project, its structure, and how to navigate the files within the repository.

## Objectives

The specific objectives of this project include:

* Collecting and preprocessing performance data from multiple seasons.
* Defining and calculating weighted scores for key performance metrics across different roles.
* Applying clustering algorithms to group players based on their performance data.
* Evaluating the clusters to ensure they provide meaningful insights into player roles.
* Analyzing the evolution of certain high-profile players' roles by season.

## Requirements

To replicate the analysis, you'll need the following Python libraries installed:

* **Pandas**: For data manipulation and analysis.
* **NumPy**: For numerical computing.
* **scikit-learn**: For machine learning, particularly for the clustering algorithms.
* **Matplotlib** and **Seaborn**: For data visualization.
* **Beautiful Soup**: For web scraping, used in the data collection phase.
* **Jupyter Notebook**: To run and interact with the `.ipynb` files.

## Usage

1. **Clone the Repository**: Start by cloning the repository to your local machine.
    
    git clone (https://github.com/Hamdanovic98/-A-Data-Driven-Clustering-Approach-in-Football.git)
    

2. **Install Dependencies**: Ensure you have all the required Python libraries installed. You can install them using:

    pip install -r requirements.txt
    

3. **Navigate the Notebooks**: Open the Jupyter notebooks in the following order to understand the full workflow:
    * `Data Collection.ipynb`
    * `Data Preparation.ipynb`
    * `Players Clustering by Role.ipynb`

4. **Explore the Report**: The PDF report (`A Data-Driven Clustering Approach in Football.pdf`) provides a comprehensive overview of the project, including the results and conclusions.

## Results and Discussion

The clustering analysis identified distinct player roles based on their performance metrics, offering a deeper understanding of their contributions on the field. The evolution tracking further highlighted how players' roles may shift over time, providing actionable insights for team management and recruitment.

## Future Work

This method not only classifies players but also tracks their evolution, helping managers and recruiters make better decisions. Future improvements could include incorporating data from leagues outside the top 5 and integrating event and positional data to refine player role classifications further.

## References

* [FBRef](https://fbref.com): Source for football statistics and player data.
* [American Soccer Analysis - Defining Roles: How Every Player Contributes to Goals](https://www.americansocceranalysis.com/home/2020/8/3/defining-roles-how-every-player-contributes-to-goals)
* [The Athletic - Player Roles](https://www.nytimes.com/athletic/3473297/2022/08/10/player-roles-the-athletic)
* [Tony El Habr - Dimensionality Reduction and Clustering](https://tonyelhabr.netlify.app/posts/dimensionality-reduction-and-clustering/)


