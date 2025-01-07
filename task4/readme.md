# Spam Message Classifier 📧

This project is a basic machine learning program to classify messages as **Spam** or **Ham** (not spam). It's perfect for beginners who are just getting started with text classification and want to explore concepts like **TF-IDF Vectorization** and **Naive Bayes Classification**.

## What Does It Do?
The program:
1. Reads a dataset of messages labeled as spam or ham.
2. Preprocesses the data (cleaning and vectorizing the text).
3. Trains a **Naive Bayes** model to classify messages.
4. Evaluates the model's accuracy.
5. Lets you test it with your own messages!

## Files You’ll Need
- **Dataset**: A CSV file named `spam.csv` with two columns:
  - `v1`: The label (`ham` or `spam`).
  - `v2`: The message content.

## How to Run
1. Open the project in a Jupyter Notebook or any Python IDE.
2. Make sure you have the required dataset (`spam.csv`) in the correct location.
3. Run the code step by step.
4. Test the model with your own messages to see if they’re spam or ham.

## Libraries Used
- **pandas**: For reading and processing the data.
- **scikit-learn**: For text vectorization, model training, and evaluation.

## Key Steps in the Code
1. **Load the Data**: Import the dataset and clean it.
2. **Vectorization**: Use **TF-IDF** to convert text into numerical features.
3. **Model Training**: Train a **Naive Bayes** classifier on the data.
4. **Model Testing**: Check accuracy and test with new messages.

## Example Predictions
Here’s how the model works with new messages:
- **Input**: "Congratulations! You have won $1000. Click the link to claim your prize."
  - **Output**: Spam
- **Input**: "Hello, can we meet up tomorrow for the project discussion?"
  - **Output**: Ham

## Results
- **Accuracy**: The model achieves a good level of accuracy (~80–90%, depending on the dataset).

## Future Improvements
- Add more preprocessing steps (like removing special characters or lemmatization).
- Experiment with other machine learning models like Logistic Regression or SVM.
- Use a larger dataset for better training.

---

This project is a simple yet practical way to explore text classification with Python. Feel free to tweak the code, experiment with different datasets, and have fun learning!
