# Forest Cover Type Classification

Machine learning project that predicts forest cover type using cartographic features such as elevation, slope, soil type, and wilderness area.

## Project Overview

This project applies machine learning techniques to classify forest cover types using cartographic variables derived from geographic data.

The dataset contains environmental attributes such as elevation, slope, hillshade values, soil types, and wilderness area indicators. These features help the model learn patterns that distinguish different forest ecosystems.

Such classification can support ecological monitoring, forest management, and land use planning.

## Dataset

The project uses the Forest CoverType dataset collected from the Roosevelt National Forest in Colorado.

Target variable:

Cover_Type (1–7) representing different forest species.

Key features include:

- elevation  
- aspect  
- slope  
- horizontal distance to hydrology  
- vertical distance to hydrology  
- horizontal distance to roadways  
- hillshade measurements  
- wilderness area indicators  
- soil type indicators  

## Tools and Libraries

- python  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  
- xgboost  

## Machine Learning Workflow

### Data Exploration
- inspect dataset structure  
- analyze distribution of forest cover types  
- explore relationships between features  

### Data Preprocessing
- separate features and target variable  
- train-test split  
- scaling when required for specific models  

### Model Training
- random forest classifier  
- xgboost classifier  

### Model Evaluation
- accuracy score  
- classification report  
- confusion matrix
