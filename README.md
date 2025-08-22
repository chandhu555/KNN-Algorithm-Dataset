# KNN-Algorithm-Dataset
First, we import some libraries. Pandas is a tool to handle data in table form. Sklearn is a library that gives us machine learning tools like splitting data, scaling values, and building the KNN model. Seaborn and Matplotlib are used for drawing graphs.

Then, we load our dataset. A dataset is just a table of information. We separate it into two parts: features (inputs we use to predict) and target (the thing we want to predict).

After that, we split the data into training data and testing data. Training data is used to teach the model, and testing data is used to check if the model learned correctly.

Before training, we scale the data. Scaling means changing the numbers so they are in a similar range. This is important because KNN works by finding distance between points, and big numbers can confuse the model if not scaled.

Next, we create the KNN model. KNN means “K-Nearest Neighbors.” Here, k=5, so the model looks at 5 nearby points to decide the class of a new point. We train the model with training data, and then we test it using testing data.

Finally, we check the results. Accuracy tells us how many predictions were correct. A confusion matrix shows correct and wrong predictions in a table
