# FADOHS-Framework-for-Detection-of-Hate-Speech-on-Facebook-Using-Sentiment-and-Emotion-Analysis
📌 Project Description

FADOHS is an advanced framework designed to detect and integrate unstructured hate speech data from Facebook using sentiment and emotion analysis. The system leverages Natural Language Processing (NLP) techniques to analyze social media content and identify hate speech patterns, helping in monitoring and controlling harmful online discussions.

🚀 Features

Hate Speech Detection: Uses sentiment and emotion analysis to classify hate speech.

Data Integration: Collects and processes unstructured Facebook comments/posts.

Sentiment Analysis: Analyzes text to determine positive, neutral, or negative sentiments.

Emotion Analysis: Identifies emotions such as anger, fear, joy, etc.

User Dashboard: Displays reports and visualizations of detected hate speech.

Admin Panel: Allows moderation and configuration of the system.

🛠️ Technologies Used

Programming Language: Python

Framework: Django

Database: MySQL (WAMP Server)

Libraries: NLTK, TextBlob, Scikit-learn

Frontend: HTML, CSS, JavaScript (for UI)

📥 Installation Guide

Clone the repository

git clone https://github.com/Narendra-Botha/FADOHS.git
cd FADOHS

Set up a virtual environment (optional but recommended)

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

Install dependencies

pip install -r requirements.txt

Set up the database

Install WAMP Server and start MySQL

Create a database in MySQL

Update settings.py with your MySQL credentials

Run migrations

python manage.py makemigrations
python manage.py migrate

Start the Django server

python manage.py runserver

Access the application
Open http://127.0.0.1:8000/ in your browser.

🏃 Usage

Log in as an admin to manage data and configure settings.

Upload and analyze Facebook comments for hate speech detection.

View sentiment and emotion-based insights.

Moderate flagged content via the admin panel.

👥 Contributors

Narendra Botha (Lead Developer)

[Add other team members if applicable]
