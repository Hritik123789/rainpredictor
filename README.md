1]User Input & Feature Handling: The model collects user input for various weather features, distinguishing between numeric and categorical features. Numeric inputs are validated to ensure correctness, and all inputs are stored in a DataFrame for further processing.

2]Preprocessing: Before making predictions, the input data is preprocessed using an imputer and a scaler for numeric columns. Categorical columns are encoded with an encoder to transform them into a suitable format for prediction.

3]Prediction & Probability Output: The processed data is passed to a pre-trained model, which predicts whether it will rain. The prediction and its probability are displayed to the user

Last block of code contains my main model.
datasetLink:https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package
