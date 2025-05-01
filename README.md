We worked on a heart disease dataset using machine learning. First, we used a Decision Tree to train a model that can predict whether a person has heart disease. We also visualized the tree to see how it makes decisions based on different features like chest pain and blood pressure.

Next, we noticed that a full decision tree can overfit, meaning it works very well on training data but not as well on new data. To fix this, we limited the tree depth to 4 levels. This gave better results on test data, with about 89.7% accuracy on training and 83.4% on testing.

Then, we trained a Random Forest, which is a group of many decision trees working together. It performed better than a single tree, with 100% accuracy on training and 98.1% on testing.

After that, we looked at which features were most important. The top features were chest pain (cp), maximum heart rate (thalach), number of vessels (ca), and oldpeak (ST depression).

Finally, we used cross-validation to test how stable the model is. The Random Forest had an average accuracy of 99.7%, showing that it works well across different parts of the data.
