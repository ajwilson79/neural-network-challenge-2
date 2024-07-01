# Neural Network Attrition and Department Prediction - Module 19 Challenge

This project aims to predict whether employees are likely to leave the company and which department they are best suited for using a branched neural network model. The neural network utilizes various features from the dataset to make these predictions, which can help HR in managing employee retention and department assignments.

## Files in the Repository

- `attrition.ipynb`: Jupyter notebook containing the code to preprocess the data, build, evaluate, and use the branched neural network model for predictions.
- `employee_data.csv`: CSV file with information about employees.

## Requirements

Before running the notebook, ensure you have the following dependencies installed:

- Python 3.7+
- pandas
- scikit-learn
- tensorflow
- keras

You can install these dependencies using pip:

```sh
pip install pandas scikit-learn tensorflow keras
```

## How to Use

1. **Clone the Repository:**

   Clone the repository to your local machine using the following command:

   ```sh
   git clone <repository_url>
   cd <repository_directory>
   ```

2. **Upload Notebook to Google Colab:**

   - Open Google Colab and upload the `attrition.ipynb` notebook.
   - Alternatively, you can run the notebook locally using Jupyter Notebook.

3. **Prepare the Data:**

   - Load the data from the provided CSV file.
   - Preprocess the data using Pandas and scikit-learn’s `StandardScaler()`.

4. **Build and Evaluate the Branched Neural Network Model:**

   - Create a branched neural network model using TensorFlow’s Keras.
   - Compile and fit the model using the `binary_crossentropy` loss function for attrition and `categorical_crossentropy` for department prediction, the `adam` optimizer, and the `accuracy` metric.
   - Evaluate the model using test data to calculate its loss and accuracy for both attrition and department predictions.

5. **Predict Attrition and Department Suitability:**

   - Reload the saved model.
   - Make predictions on the testing data.
   - Generate classification reports with the predictions and testing data for both tasks.

## Results

After running the notebook, you will have a trained branched neural network model that can predict the likelihood of an employee leaving the company and the department they are best suited for. The notebook includes classification reports to evaluate the model’s performance on both tasks.

## Notes

- Ensure to periodically save your progress and push the changes to your GitHub repository.
- Follow best practices for preprocessing to ensure consistent results between training and testing data.

## References

Based on starter files and data provided as part of OSU-VIRT-AI-PT-02-2024-U-LOLC-MTTH (OSU AI Bootcamp) for Challenge 19. Remaining code based on code examples provided as part of the course.
