
# Forest Fire Area Prediction Project

## Overview
This project aims to predict the area affected by forest fires using data mining techniques. By applying models such as Linear Regression and
Decision Tree Regression, we seek to better manage and mitigate the devastating impacts of wildfires.

## Background
Forest fires are a significant environmental hazard causing ecological damage and economic losses. Effective prediction and management of these fires
 are crucial for conservation efforts and minimizing harm to human and animal habitats.

## Motivation
The project is driven by the need for effective resource allocation in firefighting efforts and environmental conservation. By predicting fire spread,
we can optimize the deployment of firefighting resources and reduce the overall damage caused by wildfires.

## Data Description
The dataset includes various factors from the Fire Weather Index (FWI) system, along with meteorological data:
- `X`, `Y`: Spatial coordinates within Montesinho park map
- `month`, `day`: Date information
- `FFMC`, `DMC`, `DC`, `ISI`: Fire weather indices
- `temp`, `RH`, `wind`, `rain`: Weather conditions
- `area`: Burned area (response variable)

## Methodology
We employed two main algorithms:
1. **Linear Regression**
2. **Decision Tree Regression**

### Preprocessing
- Conversion of categorical variables
- Log transformation of skewed data

### Model Evaluation
Models were evaluated based on their RMSE and R-squared values, comparing their effectiveness in predicting the extent of forest fires.

## Results
- **Linear Regression**: Achieved an RMSE of 1.62 and an Adjusted R-squared of 0.07.
- **Decision Tree Regression**: Showed improved performance with an RMSE of 0.85 and an Adjusted R-squared of 0.42.

## Conclusion and Recommendations
While the Decision Tree Regression model provided a more accurate prediction, further data collection and model refinement are recommended to improve prediction
accuracy across different regions and conditions.

