# Movie Genre Classification 🎬🎭

This project was part of my internship at CodSoft, where I worked on building a machine learning model to predict movie genres based on their plot summaries. The goal was to take raw text (like movie plots) and classify it into genres using techniques like **TF-IDF Vectorization** and a **Naive Bayes Classifier**.

## What This Project Does
The idea is simple: give the model a movie’s plot, and it predicts the genre! To do this:
- We clean up the text (like lowercasing and removing missing data).
- Use **TF-IDF** to turn the text into something the model can understand (numbers!).
- Train a Naive Bayes classifier to learn from the training data.
- Predict genres for new movies and save the results to a file.

## What You’ll Need
- **Training Data**: A file called `train_data.txt` with movie titles, genres, and plot summaries.
- **Test Data**: A file called `test_data.txt` with movie IDs, titles, and plot summaries.
- **Output**: The predictions will be saved in `test-predictions.csv`.

## How to Use
1. Open the Jupyter Notebook file in your setup.
2. Make sure `train_data.txt` and `test_data.txt` are in the right folder.
3. Run the notebook step by step.
4. Check the predicted genres in the `test-predictions.csv` file.

## Results
- **Validation Accuracy**: 50%  
- The model makes predictions for the test data, and the output is saved for you to review.

---

This was a fun and practical way to dive into text classification. Feel free to try it out, improve it, or make it your own!
