🧠 MindGuard – AI Mental Health Companion
📌 Project Overview
MindGuard is an AI-powered mental wellness application designed to understand and support emotional well-being. It uses Natural Language Processing (NLP) and Machine Learning to detect emotional states from user input — whether text or speech — and provide insightful feedback, visual emotion analysis, and mental health awareness tools.

The goal is to create a compassionate, intelligent system that can serve as a digital mental health companion.

🧪 Project Description
This Jupyter Notebook contains the full implementation of MindGuard — from data preprocessing to emotion classification and visualization. It uses the GoEmotions dataset from Google and applies multi-label classification techniques to understand nuanced emotions like joy, sadness, anger, desire, approval, and more.

🧠 Key Features
🔍 Emotion detection from user input (text)

📊 Interactive emotion charts (bar/pie with hover effects)

🌙 Dark-themed, visually appealing UI design (planned)

🎯 Multi-label classification using Deep Learning

📁 Easily extendable to speech and multilingual inputs

✅ Step-by-step implementation in Jupyter Notebook

🧰 Technologies Used
Language: Python

IDE/Environment: Jupyter Notebook

Libraries & Tools:

Pandas, NumPy, Matplotlib, Seaborn

TensorFlow / Keras or PyTorch (for DL model)

Scikit-learn

NLTK / SpaCy (text preprocessing)

Plotly / Seaborn (interactive visualization)

📂 Dataset
Source: GoEmotions Dataset by Google

Details: 58k carefully labeled Reddit comments across 27 emotion categories

Processing: Cleaned, tokenized, and vectorized using NLP pipelines

🧠 Model Workflow
Data Preprocessing: Tokenization, stopword removal, padding

Exploratory Data Analysis (EDA): Distribution of emotions, word clouds

Model Building: Multi-label classification using deep learning

Evaluation Metrics: Accuracy, F1-Score, Confusion Matrix

Visualization: Emotion charts with interactive hover effects

User Input Interface: Custom function to analyze and visualize emotional content

📊 Example Output
When given a user input like:

"I'm really tired but also kind of hopeful about what's coming."

The model returns:

Emotions Detected: Sadness, Optimism, Anticipation

Confidence Scores: [0.81, 0.74, 0.62]

Graph: Interactive bar chart of emotion probabilities
