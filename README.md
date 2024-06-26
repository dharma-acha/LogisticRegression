## Logistic Regression

This repo implements logistic regression to predict a binary outcome using the Penguins dataset.

### Steps
1. Import Libraries
2. Choose Target 𝑌
3. Predict penguin gender (female/male) using the 'gender' column.
4. Predict if a penguin’s location is Torgersen Island using the 'island' column.
5. Create Data Matrices: Form X (input) and Y (target) matrices.
6. Dataset Splitting: Split into 80% training and 20% testing sets.
#### Logistic Regression Class

* Sigmoid Function


![](images/image.png)

* Cost Function


![](images/image1.png)

**Gradient Descent:** Updates weights using gradient descent.

**Fit Method:** Trains the model by iterating over the data and updating weights.

**Predict Method:** Returns binary predictions.

**Model Training:**
* Define model with different hyperparameters.
* Train the model and evaluate using accuracy.
* Save weights of the best model using pickle.

**Evaluation:** Calculate accuracy and plot the loss over iterations.

### Technologies Used

1. Python
2. NumPy
3. Pandas
4. Matplotlib

### Contact

If you have any questions or comments, feel free to contact me on [Email](mailto:achadharma333@gmail.com)


