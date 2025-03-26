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
The `Extract additional features` cell in the data extraction notebook performs extensive API calls to the Materials Project database, which may take several hours to complete due to API rate limits and the large dataset size. For efficiency and reproducibility, unless there is a significant update to the Materials Project data, it is recommended to use the pre-extracted battery dataset provided in the repository (`Battery data`).

### Materials Project API Usage
Access to the Materials Project requires an API key and is subject to usage limits and their terms of use. Please ensure you adhere to these guidelines when retrieving data programmatically.

### Model Generalization
The trained model is based solely on the dataset extracted from the Materials Project and may not generalize well to materials with features outside the training data's distribution. Additional validation is advised when applying the model to new or experimental materials.

## 📈 Future Work
- Explore alternative ML models (e.g., Random Forest, Gradient Boosting)
- Extend the dataset with new materials or updated data from the Materials Project
- Deploy the model as a web application for wider accessibility by researchers

## Author
Bernard Nii Adote Allotey – https://github.com/Evolved360

## Acknowledgments
Special thanks to my collaborators for their valuable contributions:
- Nana Yaw Boateng
- Wilhemina Tackie
- Nathaniel Sambi

 If you have any questions or contributions, feel free to reach out to me on: allotey361@gmail.com
  



