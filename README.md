#  Battery Electrode Voltage Prediction using Machine Learning
This project marks my first major machine learning endeavor after three months of learning, marking the beginning of my exploration into data-driven materials discovery. In this project, A Deep Neural Network (DNN) model was developed and trained to predict the average voltage of battery electrode materials using computationally derived material descriptors. The objective is to facilitate the accelerated screening and identification of promising electrode candidates for advanced battery technologies.

## Dataset Source
The dataset was sourced from the **[Materials Project](https://materialsproject.org/)** — a leading open database of computed materials properties powered by high-throughput Density Functional Theory (DFT) calculations. To access the database programmatically, users must create an account on the Materials Project platform and obtain an API key from their profile settings.

##  Tools & Technologies
- **Python** 
- **Pandas** – Data manipulation and preprocessing
- **NumPy** – Numerical computations
- **Pymatgen** – Materials analysis and data extraction
- **CBFV (Composition-Based Feature Vectorization)** – Feature generation from material compositions
- **Scikit-learn** – Data preprocessing and evaluation metrics
- **TensorFlow / Keras** – Deep Neural Network modeling
- **Matplotlib & Seaborn** – Data visualization
- **Jupyter Notebook** – Exploratory Data Analysis and model development

## ⚠️ Disclaimer

### Data Extraction Runtime
The `additional_data` cell in the data extraction notebook performs extensive API calls to the Materials Project database, which may take several hours to complete due to API rate limits and the large dataset size. For efficiency and reproducibility, unless there is a significant update to the Materials Project data, it is recommended to use the pre-extracted battery dataset provided in the repository (`data/battery_data.csv`).

### Materials Project API Usage
Access to the Materials Project requires an API key and is subject to usage limits and their terms of use. Please ensure you adhere to these guidelines when retrieving data programmatically.



