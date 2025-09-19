# HunarIntern_task02
Weather Prediction using Linear Regression 

This project demonstrates a machine learning approach to weather prediction using regression techniques. The main goal of the model is to predict temperature values based on multiple weather-related features such as cloud cover, season, and location. The dataset used for this task is a CSV file containing weather records with both numerical and categorical attributes.

The workflow begins by loading the dataset into a Pandas DataFrame and separating the target variable, which is the temperature, from the input features. Since the dataset includes categorical columns such as cloud cover, season, and location, these are one-hot encoded to transform them into numerical form suitable for training the model. After preprocessing, the dataset is split into training and testing subsets using an 80-20 ratio.

For the predictive model, Linear Regression from scikit-learn is applied. The model is trained on the training dataset and then tested on unseen data. To evaluate its performance, metrics such as Mean Squared Error (MSE) and the R² score are calculated. The MSE indicates the average squared difference between the predicted and actual temperatures, while the R² score shows how well the model explains the variance in the data.

A visualization is also included to provide better insights into the model’s accuracy. A scatter plot is drawn comparing the actual vs predicted temperature values. Ideally, if the predictions are perfect, the points would lie close to the diagonal line. This makes it easy to observe how well the model performs across the test set.

In addition to general predictions, the project also includes a demonstration of how to use the model for single-row predictions. By selecting one row from the test dataset, the model generates a temperature prediction, showing how it can be applied in real-world scenarios where individual weather records need to be analyzed.

This project highlights the use of Python libraries such as Pandas, NumPy, Matplotlib, and scikit-learn for data preprocessing, machine learning, evaluation, and visualization. Through this task, I gained practical experience in handling categorical variables with one-hot encoding, implementing linear regression models, and analyzing their effectiveness through statistical metrics and visual plots.

In the future, this project can be extended by experimenting with more advanced regression models such as Decision Trees, Random Forests, or Gradient Boosting, which might capture complex weather patterns more effectively. Integrating additional weather features or real-time weather APIs could further enhance the accuracy and practical use of this system.
