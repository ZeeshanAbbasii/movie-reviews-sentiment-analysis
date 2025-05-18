# 🎬 Movie Review Sentiment Analysis

This project analyzes the sentiment of movie reviews using a Support Vector Machine (SVM) model trained on the IMDB Dataset.

---

## 📁 Project Structure
movie_review_sentiment/
├── IMDB Dataset.csv           # Dataset used for training
├── cleaned_notebook.ipynb     # Final cleaned notebook
├── svm_model.pkl              # Trained SVM model
├── tfidf_vectorizer.pkl       # TF-IDF vectorizer used during training
├── requirements.txt           # Python dependencies
└── README.md                  # Project documentation

---

## 🧠 What It Does

- Cleans and preprocesses movie reviews
- Trains a Support Vector Machine (SVM) for sentiment classification
- Saves the trained model and vectorizer using `pickle`
- Allows interactive sentiment prediction for new reviews
- Evaluates model using a confusion matrix

---

## ▶️ How to Run

1. **Clone the repo:**
   ```bash
   git clone https://github.com/your-ZeeshanAbbasii/movie_review_sentiment.git
   cd movie_review_sentiment

2.	Install dependencies:

	pip install -r requirements.txt

3.	Run the notebook:
Open cleaned_notebook.ipynb in Jupyter Notebook and run all cells.

4.	Make predictions interactively:
Use the provided predict_interactive() function to enter reviews and get real-time sentiment predictions.

⸻

🧪 Evaluation
	•	Model is evaluated using a confusion matrix.
	•	Accuracy, precision, and recall are calculated.
	•	You may extend the evaluation to include ROC curve and AUC if desired.

