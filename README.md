# Predicting Modeling Hydropower Consumption using *k*-Nearest Neighbors Regression

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![GitHub Stars](https://img.shields.io/github/stars/jorgesandoval/hydropower-regression-knn.svg)
![GitHub Downloads](https://img.shields.io/github/downloads/jorgesandoval/hydropower-regression-knn/total.svg)
![GitHub Forks](https://img.shields.io/github/forks/jorgesandoval/hydropower-regression-knn.svg)

![Alt text](images/hydropower.png)
This repository contains a Jupyter notebook that demonstrates the use of *k*-Nearest Neighbors (KNN) regression to predict hydropower consumption based on historical data.

## 📖 Table of Contents
- [Predicting Modeling Hydropower Consumption using *k*-Nearest Neighbors Regression](#predicting-modeling-hydropower-consumption-using-k-nearest-neighbors-regression)
  - [📖 Table of Contents](#-table-of-contents)
  - [📌 Overview](#-overview)
  - [📊 Dataset](#-dataset)
  - [🔧 Dependencies](#-dependencies)
  - [🚀 Usage](#-usage)
  - [📈 Key Findings](#-key-findings)
  - [💡 Contributions](#-contributions)
  - [📜 License](#-license)
  - [👤 Authors](#-authors)
  - [🙌 Acknowledgements](#-acknowledgements)

## 📌 Overview
The notebook ingests historical hydropower consumption data, preprocesses it, and then employs the KNN regression model to predict the consumption for the year 2019. Various metrics, such as Root Mean Squared Log Error (RMSLE), R-squared, Mean Absolute Error (MAE), and more, are used to evaluate the model's performance.

## 📊 Dataset

- **File Name:** `Hydropower_Consumption.csv`
- **Description:** The dataset contains yearly hydropower consumption data. The data for each country spans from the year 2000 to 2019. The notebook specifically drops the `Country` column and scales the data between 0 and 1 using `MinMaxScaler` for modeling purposes.

## 🔧 Dependencies

To run the notebook, you'll need the following libraries:

- pandas
- numpy
- matplotlib
- scikit-learn

You can install these using `pip`:

```bash
pip install pandas numpy matplotlib scikit-learn
```

## 🚀 Usage

1. **Clone the repository:**

   ```bash
   git clone https://github.com/jorgesandoval/hydropower-regression-knn.git
    ```
2. **Navigate to the cloned directory and open the Jupyter notebook"**

    ```bash
    cd hydropower-regression-knn
    jupyter notebook
    ```
3. **Run the notebook**: Execute the notebook cells sequentially to preprocess the data, train the KNN model, and evaluate its performance.

## 📈 Key Findings
* The notebook performs a search to determine the optimal number of neighbors (k) for the KNN regressor.

* A grid search is conducted to further refine the model parameters.

* The final model's performance metrics are displayed at the end of the notebook.

## 💡 Contributions

Contributions to this repository are very welcome! Whether it's fixing bugs, improving the documentation, adding new features, or providing feedback, your insights can help improve this project. Here's how you can contribute:

1. **Fork the Project**
* Navigate to the main page of the repository.
* Click on the Fork button on the top right.

2. **Create Your Feature Branch**
    ```bash
    git checkout -b feature/AmazingFeature
    ```

3. **Commit Your Changes**
    ```bash
    git commit -m 'Add some AmazingFeature'
    ```
4. **Push to the Branch**
    ```bash
    git push origin feature/AmazingFeature
    ```
5. **Open a Pull Request**
* Navigate back to the main page of your forked repository.
* Click on the "Pull requests" tab.
* Click on the green "New pull request" button.


## 📜 License

Distributed under the MIT License. See [LICENSE](https://opensource.org/licenses/MIT) for more information.

## 👤 Authors
* [Jorge Sandoval](https://www.linkedin.com/in/jorge-g-sandoval/)

## 🙌 Acknowledgements

The compilation and analytical undertakings presented in this repository owe their comprehensiveness to the invaluable datasets and insights provided by several esteemed organizations. We would like to formally recognize the following entities:

- **[Our World in Data](https://ourworldindata.org/)**: Their meticulous data aggregation efforts have been foundational to the scope and depth of our work.

- **[BP Statistical Review of World Energy](https://www.bp.com/en/global/corporate/energy-economics/statistical-review-of-world-energy.html)**: We are indebted to their thorough energy statistical reviews, offering both comprehensive energy and electricity data over an extensive historical timeline.

- **[Ember](https://ember-climate.org/data/)**: Their rigorous approach to collating electricity mix data, which amalgamates information from a myriad of international and national sources, has been indispensable. We recognize their primary reliance on the [Energy Information Administration (EIA)](https://www.eia.gov/).

Our profound gratitude extends to all the scholars, data scientists, and domain experts who have dedicated their expertise to the creation and maintenance of these pivotal data sources. Their contributions have been paramount in enhancing the academic community's understanding of global energy paradigms.
