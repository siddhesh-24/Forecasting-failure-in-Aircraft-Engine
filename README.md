**<h1>Predictive Maintenance using NASA Engine Degradation Dataset</h1>**

This project focuses on predictive maintenance using the NASA engine degradation dataset. The goal is to predict the remaining useful life (RUL) of an engine based on historical sensor data. This project is crucial for industries relying on heavy machinery where timely maintenance can prevent costly failures.

<h2>Dataset</h2>

The dataset used is from NASA, specifically the [CMAPSS dataset](https://data.nasa.gov/dataset/Prognostics-Data-Challenge-Dataset/4nxq-icbz). I have used the train_FD001.txt file for this analysis. The dataset consists of multiple time-series sensor readings from different engines under varying operational conditions.

<h2>Project Structure</h2>

- **Data Loading and Preprocessing**: The raw data is loaded from a .txt file and pre-processed to clean and structure it for analysis.
- **Feature Engineering**: Additional features are created from the existing sensor readings to enhance the model's predictive power.
- **Modelling**: Random Forest model is used to predict the failure of the engine.
- **Evaluation**: The models are evaluated using K-fold cross validation technique that show the model’s robustness.
- **Best Parameters**: Using Grid Search we have found out the optimal parameters to used in Random Forest model to get the best performances.

<h2>Key Libraries Used</h2>

- pandas
- numpy
- matplotlib
- scikit-learn
- tensorflow

<h2>Results</h2>

The best model achieves an Accuracy of 97.59 % on the test set, demonstrating the effectiveness of predictive maintenance using this approach.

<h2>Future Work</h2>

- Incorporate more advanced deep learning models like LSTM or GRU.
- Experiment with different feature engineering techniques.
