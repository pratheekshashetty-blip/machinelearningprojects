Forest Cover Type Classification

Machine learning project that predicts forest cover type using cartographic features such as elevation, slope, soil type, and wilderness area.

Project Overview

This project applies machine learning techniques to classify forest cover types using cartographic variables derived from geographic data.
The dataset contains environmental attributes such as elevation, slope, hillshade values, soil types, and wilderness area indicators. These features help the model learn patterns that distinguish different forest ecosystems.
Such classification can support ecological monitoring, forest management, and land use planning.

Dataset
The project uses the Forest CoverType dataset, which includes cartographic variables collected from the Roosevelt National Forest in Colorado.
Target variable: Cover_Type (1–7) representing different forest species.

Key features include:
- Elevation
- Aspect
- Slope
- Distance to Hydrology
- Distance to Roadways
- Hillshade measurements
- Wilderness area indicators
- Soil type indicators

Models Used
- Random Forest Classifier
- XGBoost Classifier

These models are well suited for structured tabular datasets with many features.

Evaluation

Model performance is evaluated using:
Accuracy score
Classification report

Confusion matrix
