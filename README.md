 AI vs Human Text Detection System
📌 Project Overview
This project is a Machine Learning-based web application that classifies whether a given text is:

Human-written
AI-generated
It uses Natural Language Processing (NLP) techniques and classification algorithms to analyze text and provide prediction, confidence score, and decision level.

🚀 Features
Text preprocessing (lowercase + punctuation removal)

TF-IDF vectorization

Machine Learning models:

Logistic Regression
Naive Bayes (for comparison)
Confidence-based decision layer:

Acceptable
Needs Review
Likely AI-generated
Web interface using Flask

Word count analysis

🗂️ Project Structure
├── app.py
├── main.py
├── dataset.csv
├── dataset1.csv
├── templates/
│   └── index.html
└── README.md
⚙️ Installation
1. Clone the repository
git clone https://github.com/your-username/ai-text-detector.git
cd ai-text-detector
2. Install dependencies
pip install flask pandas scikit-learn
▶️ How to Run
Run Flask App
python app.py
Open in browser:

http://127.0.0.1:5000/
Run Model Training (Optional)
python main.py
🧪 Model Details
Preprocessing
Convert text to lowercase
Remove punctuation
Vectorization
TF-IDF (Term Frequency - Inverse Document Frequency)
Algorithms Used
Logistic Regression (Primary)
Multinomial Naive Bayes (Comparison)
📊 Decision Logic
Confidence	Decision
≥ 0.80	Acceptable
0.60 – 0.79	Needs Review
< 0.60	Likely AI-generated
📌 Example Output
Prediction: Human
Confidence: 0.85
Decision: Acceptable
Word Count: 120
Level: High
📈 Future Improvements
Use deep learning models (LSTM, BERT)
Improve dataset quality
Add API support
Deploy on cloud
👩‍💻 Author
Deepa
