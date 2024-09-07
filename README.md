# Predicting-Movie-Rental-Duratlons
This project aims to predict the number of days a customer will rent a DVD using historical rental data. The machine learning model developed in this project helps to forecast rental durations, which can be useful for inventory management and customer behavior analysis.

## Project Structure
- notebook.ipynb: Jupyter notebook containing data exploration, model building, and evaluation processes.
- Data Files: Any relevant data files used for model training and evaluation (ensure these are mentioned if needed).

## Dependencies
- Python 3.x
- Jupyter Notebook
- Required libraries:
    - pandas
    - numpy
    - matplotlib
    - seaborn
    - sklearn

You can install all dependencies via:
`pip install -r requirements.txt`
## Steps
1. Data Preprocessing:
- Loaded and explored the DVD rental dataset.
- Created new features like rental_length_days using return_date and rental_date.
2. Model Building:
- Implemented various regression models to predict rental lengths.
- Models tested include:
    - RandomForestRegressor
    - Additional regressors (if any)
3. Model Evaluation:
- Hyperparameter tuning using GridSearchCV/RandomizedSearchCV to optimize model performance.
- Final model selected based on the lowest Mean Squared Error (MSE).

## Results
The best-performing model is the RandomForestRegressor, which achieved an MSE of approximately X (insert actual value here).

## Usage
To run the project:
- Clone the repository.
- Install the required libraries.
- Open the notebook.ipynb in Jupyter Notebook.
- Execute the cells to preprocess the data, train the model, and make predictions.

## Conclusion
The model provides reasonably accurate predictions of DVD rental durations, with room for further improvement through additional feature engineering and tuning.

## License
This project is licensed under the MIT License.
