# deep-learning-challenge
Module 21 Challenge

Overview of the Analysis:

The purpose of this analysis is to develop a deep learning model to predict whether applicants to Alphabet Soup will be successful if funded based on various features provided in the dataset. By accurately predicting success, Alphabet Soup can optimize its funding allocation process and increase the impact of its contributions.

Results:

Data Preprocessing:

* Target Variable: The target variable for the model is whether the applicant was successful (1) or not (0).
* Feature Variables: The features for the model include various factors such as application type, organization type, use case, income amount, etc.
* Variables to be Removed: Variables such as 'EIN' (Employer Identification Number) and 'NAME' (Applicant Organization Name) should be removed from the input data as they are neither targets nor features.

Compiling, Training, and Evaluating the Model:

* The model consists of three hidden layers with 100, 50, and 20 neurons respectively, with the tanh activation function. The output layer has 1 neuron with the sigmoid activation function.
* The choice of the number of neurons and layers is based on the complexity of the dataset and experimentation to find a balance between model performance and computational efficiency.
* The model achieved an accuracy of approximately 71.85% on the test dataset.
* To improve model performance, various techniques could be employed such as:
* Experimenting with different architectures by adding or removing layers and adjusting the number of neurons.
* Tuning hyperparameters like learning rate, batch size, and optimizer.
* Feature engineering to create new features or remove irrelevant ones.
* Regularization techniques to prevent overfitting, such as dropout or L2 regularization.

Summary:

In summary, the deep learning model achieved a moderate accuracy of approximately 71.85% in predicting the success of funding applicants for Alphabet Soup. While this performance is acceptable, there is still potential for enhancement. Overall, further experimentation with different models and techniques is recommended to find the optimal solution for predicting funding success effectively.
