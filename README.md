# Climate-Patterns-Regional-Classification-and-Well-being-Analysis-in-the-UK

## Overview
This project investigates UK climate data using unsupervised and supervised learning techniques. It identifies weather-based regional patterns through clustering, classifies weather stations into geographical regions using machine learning, and explores potential correlations between climate factors and happiness using statistical analysis. A final clustering analysis on happiness data further highlights regional well-being trends. The project leverages Python for data collection, preprocessing, modeling, and visualization, emphasizing reproducibility and insightful reporting.

---

## Project Structure

- **Part 1: Clustering UK Weather Stations**
  - Data collected from Met Office historic station data.
  - Preprocessing includes handling missing values and standardization.
  - K-Means clustering applied (k=3) based on Elbow Method.
  - PCA used for visualization.

- **Part 2: Classifying Weather Stations into Regions**
  - Stations labeled into Northern, Central, and Southern regions using latitude.
  - Aggregated station-level features.
  - Trained and evaluated Random Forest and Gradient Boosting classifiers.
  - Achieved 80% accuracy on test set.

- **Part 3: Climate vs Happiness Correlation Analysis**
  - Happiness data from ONS (Office for National Statistics).
  - Combined using latitude bands.
  - Pearson and Spearman correlation analysis.
  - No significant correlations found, but negative trend between frost days and happiness noted.

- **Part 4a: Clustering Happiness Data**
  - Applied K-means to regional happiness statistics.
  - Optimal clusters determined via Elbow Method and Silhouette Score.
  - Clear separation found between regions with high vs low happiness.

---

## Technologies Used

- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook
- PCA, K-Means, Random Forest, Gradient Boosting
- Data Sources:
  - [Met Office Climate Data](https://www.metoffice.gov.uk/research/climate/maps-and-data/historic-station-data)
  - [ONS Happiness Statistics](https://www.ons.gov.uk/peoplepopulationandcommunity/wellbeing/datasets)

---

## How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/uk-climate-happiness-analysis.git
    cd uk-climate-happiness-analysis
    ```

2. Set up environment:
    ```bash
    pip install -r requirements.txt
    ```

3. Run analysis notebooks in order:
    - `part1_clustering_weather_stations.ipynb`
    - `part2_classification_weather_regions.ipynb`
    - `part3_climate_happiness_correlation.ipynb`
    - `part4a_happiness_clustering.ipynb`

---

## Results Summary

- **Clustering:** 3 main weather pattern clusters across UK stations.
- **Classification:** Models predicted regional climate zones with 80% accuracy.
- **Happiness Analysis:** No strong link found, but frost days slightly inversely correlated with happiness.
- **Clustering Happiness:** Two distinct happiness profiles emerged regionally.

---

## Author
Muhammad Zubair Khan  
[LinkedIn]([https://linkedin.com/in/your-profile](https://www.linkedin.com/in/zubair-khan-37412328a))

