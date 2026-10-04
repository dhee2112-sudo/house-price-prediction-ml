# House Price Prediction using Machine Learning

## Objective

The goal of this project is to predict median house values using machine learning regression models and compare their performance.

## Dataset

California Housing Dataset from Scikit-learn.

The dataset contains housing, demographic, and geographic features such as:

- Median Income
- House Age
- Average Rooms
- Average Bedrooms
- Population
- Average Occupancy
- Latitude
- Longitude

## Models Used

- Linear Regression
- Ridge Regression
- Lasso Regression
- Decision Tree Regressor
- Random Forest Regressor

## Evaluation Metrics

The models were evaluated using:

- MAE (Mean Absolute Error) — lower is better
- MSE (Mean Squared Error) — lower is better
- R² Score — higher is better

## Results

| Model | MAE | MSE | R² |

| Linear Regression | 0.5332 | 0.5559 | 0.5758 |
| Ridge | 0.5337 | 0.5523 | 0.5785 |
| Lasso | 0.5353 | 0.5483 | 0.5816 |
| Decision Tree | 0.4332 | 0.4155 | 0.6829 |
| Random Forest | 0.3270 | 0.2542 | 0.8060 |

## Conclusion

Among the tested models, Random Forest achieved the best performance, with the highest R² score and the lowest MAE and MSE. This indicates that it captured the relationships in the housing data better than the other models tested.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
