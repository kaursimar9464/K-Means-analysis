# K-Means Clustering: Palmer Penguins Dataset 🐧

This project applies K-Means clustering to the [Palmer Penguins dataset](https://allisonhorst.github.io/palmerpenguins/) to explore unsupervised learning and visualize species groupings based on physical measurements.

## Objective

To cluster penguin species using unsupervised learning and evaluate cluster quality using various metrics and visual tools.

## Steps Performed
- Loaded and explored the Palmer Penguins dataset
- Handled missing values and standardized features
- Applied **K-Means clustering** to identify natural groupings
- Determined the optimal number of clusters using:
  - **Inertia (Elbow Method)**
  - **Silhouette Score**
- Compared clustering labels with actual species

## Visualizations
- Pairplot to understand feature relationships
- Elbow plot to find optimal number of clusters (k)
- Silhouette score line plot
- 2D scatter plot of clustered penguins
- Cluster centroid visualization

## Key Features Used
- Bill Length (mm)
- Bill Depth (mm)
- Flipper Length (mm)
- Body Mass (g)

## Libraries Used
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## How to Run

1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/kmeans-penguin-clustering.git
    cd kmeans-penguin-clustering
    ```

2. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Launch the notebook:
    ```bash
    jupyter notebook "Activity_Build a K-means model.ipynb"
    ```

## Dataset Source
- [`palmerpenguins` R package](https://allisonhorst.github.io/palmerpenguins/)

