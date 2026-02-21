# Country Clustering Analysis (Europe & Americas – 2007)

This project applies **Hierarchical Clustering (Ward Method)** and **K-Means Clustering** to group countries from Europe and the Americas based on socioeconomic indicators.

The analysis uses data from the Gapminder dataset and focuses on:

* GDP per capita
* Life expectancy
* Population

The objective is to identify meaningful country groupings based on development patterns.

---

## Dataset

**Source:**
Gapminder Dataset (Plotly repository)
[https://raw.githubusercontent.com/plotly/datasets/master/gapminderDataFiveYear.csv](https://raw.githubusercontent.com/plotly/datasets/master/gapminderDataFiveYear.csv)

### Data Selection

* Continents: **Europe and Americas**
* Year: **2007 (most recent year in dataset)**

### Features Used

* `gdpPercap` → GDP per capita
* `lifeExp` → Life expectancy
* `pop` → Population

---

## Methods Used

* **Hierarchical Clustering (Ward Method):** Used to visualize similarity structure between countries through a dendrogram, suggesting approximately 10 clusters.
* **Elbow Method:** Applied to determine the optimal number of clusters for K-Means.
* **K-Means Clustering:** Implemented with **K = 9**, selected based on inertia minimization and elbow detection.

---
## Results
The clustering revealed socioeconomic patterns:
* Countries with high GDP per capita and high life expectancy formed clusters representing developed nations.
* Countries with lower GDP and life expectancy grouped separately.
---


## Technologies Used

* Python
* Pandas
* Scikit-learn
* SciPy
* Matplotlib
