
## Spam Email Detection using Machine Learning

This project implements a **Spam Email/SMS Detection System** using **Machine Learning** and **Natural Language Processing (NLP)**. The model classifies messages as either **Spam** or **Ham (Not Spam)** with high accuracy.

### Key Features

* Preprocessing of text data (lowercasing, punctuation & number removal).
* **TF-IDF Vectorization** with unigrams, bigrams, and trigrams for feature extraction.
* **LinearSVC (Support Vector Machine)** with class balancing for robust classification.
* Evaluation using **Accuracy, Precision, Recall, F1-score**, and **Confusion Matrix** visualization.
* Sample predictions on custom input messages.

### Tech Stack

* **Python**
* **Pandas, NumPy, Matplotlib, Seaborn** (data handling & visualization)
* **NLTK** (stopwords)
* **scikit-learn** (ML models & evaluation)

### Results

* Achieves high accuracy on the **SMS Spam Collection dataset**.
* Detects spammy messages like *“You have a chance to become a millionaire”* while recognizing legitimate ones like *“Hey, are we still meeting today?”*.

### How to Run

1. Clone this repository.
2. Install dependencies:
   pip install -r requirements.txt
3. Run the notebook or Python script to train and test the model.
