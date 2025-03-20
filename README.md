# Spam-Email-Classifier
Spam Email Classifier

Spam Email Classifier

A Python-based machine learning project that classifies emails as spam or not spam using Naïve Bayes and TF-IDF vectorization.

📌 Features

✅ Uses Scikit-Learn for text classification
✅ TF-IDF for better text representation
✅ Predicts if an email is spam or not
✅ Simple and efficient

🚀 Installation
	1.	Clone the repository:
git clone https://github.com/your-username/spam-classifier.git
cd spam-classifier

	2.	Install dependencies:
 pip install pandas numpy scikit-learn  

 	3.	Run the script:
  python spam_classifier.py

  🏆 How It Works
	1.	Loads a dataset of labeled spam and ham messages
	2.	Converts text into numerical features using TF-IDF
	3.	Trains a Naïve Bayes classifier on the dataset
	4.	Predicts if a new message is spam

✨ Example Usage

from spam_classifier import predict_spam

text = "Congratulations! You've won a $1000 gift card. Click here to claim."
print(predict_spam(text))  # Output: Spam

🛠 Requirements
	•	Python 3.x
	•	Pandas
	•	NumPy
	•	Scikit-Learn

📜 License

This project is open-source and available under the MIT License.
