# Hair Fall Analysis: A Statistical Approach using R

## Project Overview

This project aims to analyze hair fall levels using various statistical and machine learning techniques in R. The dataset used contains various physiological and nutritional factors that are analyzed to identify patterns and predict hair fall levels. The project explores data cleaning, feature engineering, visualization, and modeling using techniques like multinomial logistic regression, decision trees, random forests, SVM, and AutoML.

## Dataset

The dataset used in this project is `hair_loss.csv`, which is expected to be located in the `Downloads` folder. The dataset includes the following columns:

- `hair_fall`: Levels of hair fall (categorical variable)
- `iron`: Iron levels
- `stress_level`: Stress levels
- `total_protein`: Total protein levels
- `total_keratine`: Total keratine levels
- `hair_texture`: Hair texture
- `vitamin`: Vitamin levels
- `manganese`: Manganese levels
- `calcium`: Calcium levels
- `body_water_content`: Body water content
- `liver_data`: Liver data

## Installation

To get started, you'll need to install the required R packages. Use the following commands to install them:

```r
install.packages("tidyverse")
install.packages("psych")
install.packages("outliers")
install.packages("gridExtra")
install.packages("corrplot")
install.packages("ggcorrplot")
install.packages("ggstatsplot")
install.packages("caret")
install.packages("MASS")
install.packages("nnet")
install.packages("tree")
install.packages("randomForest")
install.packages("e1071")
install.packages("h2o")
```

## Usage

1. **Data Preprocessing:**

   - Read the dataset and inspect its structure.
   - Convert blank spaces to `NA` and handle missing values.
   - Normalize and standardize the data.
   - Handle outliers using the IQR method.

2. **Data Visualization:**

   - Plot the distribution of iron levels.
   - Generate histograms and density plots for various features.
   - Create box plots to visualize the distribution of numerical columns.

3. **Modeling:**

   - **Multinomial Logistic Regression:**
     Fit a multinomial logistic regression model and evaluate its performance using metrics like accuracy, precision, recall, and F1 score. Plot the ROC curves and calculate the AUC for each class.

   - **Decision Tree:**
     Fit a decision tree model, make predictions, and evaluate performance using confusion matrix metrics.

   - **Random Forest:**
     Fit a random forest model, make predictions, and evaluate performance using confusion matrix metrics.

   - **Support Vector Machine (SVM):**
     Fit an SVM model, make predictions, and evaluate performance using confusion matrix metrics.

   - **AutoML:**
     Use H2O's AutoML to automatically train and select the best model. Evaluate the leaderboard to find the best model.

## Results

The project demonstrates the application of various machine learning algorithms to classify hair fall levels based on multiple physiological factors. The results include performance metrics for each model and visualizations that provide insights into the data.

## Conclusion

This project showcases a comprehensive approach to analyzing and predicting hair fall levels using R. It combines data preprocessing, visualization, and a variety of machine learning techniques to understand and predict hair fall.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or comments, please reach out to 'sriramreddypendyala@gmail.com' or open an issue on this repository.
