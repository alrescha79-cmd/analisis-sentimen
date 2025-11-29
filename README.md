# Sentiment Analysis Project Submission

This project is part of the [Machine Learning Path Dicoding](https://www.dicoding.com/learningpaths/30). The goal of this project is to build a sentiment analysis model using various machine learning algorithms.

## Project Description

Sentiment analysis is the process of determining an individual's opinion or feelings about a topic based on provided text. In this project, various machine learning techniques are used to classify text into positive, negative, or neutral sentiments.

### Algorithms Used

1. **Decision Trees**: A tree-based supervised learning algorithm for classification tasks.
2. **Random Forest**: An ensemble learning method based on decision trees for higher accuracy.
3. **Support Vector Machines (SVM)**: A hyperplane-based algorithm for text classification.
4. **Bidirectional Long Short-Term Memory (Bi-LSTM)**: A deep learning approach to understand text context from both directions.

## Dataset

The dataset consists of labeled text data with positive, negative, or neutral sentiments. This dataset can be obtained from trusted sources such as Kaggle or other public datasets.

## How to Use

1. **Install Dependencies**
   Ensure you have installed the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

2. **Prepare the Dataset**
   Place the dataset in the project directory and ensure its format matches the notebook's expected format.

3. **Train the Model**
   Run the following notebook to train the model:
   ```bash
   jupyter notebook
   ```

4. **Evaluate the Model**
   The model will be evaluated using metrics such as accuracy, precision, recall, and F1-score.

5. **Make Predictions**
   Use the trained model to make predictions on new data.

## Directory Structure

- `notebooks/`: Contains Jupyter Notebook files for preprocessing, training, and evaluating the model.
- `data/`: Directory where the dataset is stored.
- `models/`: Contains trained models for making predictions.

## Technologies Used

- Python
- Scikit-learn
- TensorFlow
- Keras
- Pandas
- Numpy
- Jupyter Notebook

## Contributing

Contributions are welcome! If you'd like to contribute, feel free to fork this repository, create a new branch, and submit a pull request.

```bash
git clone https://github.com/alrescha79-cmd/analisis-sentimen.git
git checkout -b new-feature
```

## Author 

This project was created by:
- **[Anggun Caksono](https://www.github.com/alrescha79-cmd)**

If you encounter any issues or have questions, feel free to open a [new issue](https://github.com/alrescha79-cmd/analisis-sentimen/issues).

---
