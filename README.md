# deep-learning-challenge
In this project, I followed a structured approach to build a deep learning model for predicting the success of organizations funded by Alphabet Soup. First, I preprocessed the data by reading the dataset into a Pandas DataFrame, identifying the `IS_SUCCESSFUL` column as the target variable, and removing irrelevant columns like `EIN` and `NAME`. I handled categorical data by grouping rare categories and using `pd.get_dummies()` for encoding, followed by splitting the data into training and testing sets and scaling the features using `StandardScaler()`. Next, I designed and compiled a neural network model using TensorFlow and Keras, selecting two hidden layers with ReLU activation and an output layer with a sigmoid function to handle binary classification. I trained the model and evaluated its performance, saving the model’s weights at regular intervals. Then, I optimized the model by experimenting with additional layers, different numbers of neurons, and activation functions, aiming to improve the accuracy beyond 75%. Finally, I documented the entire process, including the data preprocessing steps, model structure, performance evaluation, and optimization attempts, and saved the final model for future use.
