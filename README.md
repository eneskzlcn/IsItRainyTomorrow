## Predicting Is It Rain Tomorrow In Aus 

This project uses data mining techniques from data pre-proccessing
up to creating and training classfiers with cleaned data. The dataset
used on project consist of 8 years of weather data for AUS. The purpose of the classifier model that created and trained in project is predicting is it rain tomorrow on AUS according to its trainings.

### Contents

#### Preproccessing data
   * Cleaning dataset from unnecessary data
   * Get rid of empty,null values
   * Converting categorical and string variables to numeric values with Label Encoder
   * Normalizing dataset values
   * Applying PCA on dataset to dimension reduction.

#####  Visualizing dataset with boxplots ,histograms, pairplots or etc. for better understanding of data distrubition and correlation

#### Classification
   * Preparing test and training datasets
   * Perform training with training dataset and perform classification predictions using Decision Tree Classifier
   * Using both gini and entropy criterion with Decision Tree Classifer and their effects
   * Creating confusion matrix and visualising it with ConfusionMatrixDisplay
   * Creating classification report as result of classification operation and visualize it.
   * Interpreting classification with created confusion matrix and classification method
   * Analysis classification operation as result

### Requirements To Run Project Notebook
  * python3
  
  * **Libraries (you can install with python package manager)**
    * jupyter notebook
    * numpy
    * pandas
    * matplotlib
    * seaborn