# 🚆 Elementary Chatbot using Basic NLP for Indian Railways

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![NLTK](https://img.shields.io/badge/NLTK-NLP-green.svg)
![Beginner Friendly](https://img.shields.io/badge/Level-Beginner-brightgreen)
![Open Source](https://img.shields.io/badge/Open%20Source-Yes-orange)
![Status](https://img.shields.io/badge/Project-Completed-success)

---

## 📌 Project Overview

This project is a **simple rule-based chatbot** built using **Natural Language Processing (NLP)** concepts to answer **frequently asked questions related to Indian Railways**.

The chatbot uses **NLTK**, basic preprocessing, and keyword matching techniques to understand user queries and provide appropriate responses.

---

## 🎯 Features

- 🤖 Elementary NLP-based chatbot  
- 🧠 Text preprocessing (tokenization, stopword removal, lemmatization)  
- 🔍 Keyword-based matching for user queries  
- 🚆 Railway-related FAQs support  
- 🧪 Beginner-friendly and easy to understand  

---

## 🛠️ Tech Stack

- **Language:** Python  
- **Libraries:**  
  - NLTK  
  - Regex  
- **Platform:** Google Colab / Local Python Environment  

---

## 🧩 How It Works

1. User enters a railway-related question  
2. Input is preprocessed:
   - Punctuation removal  
   - Lowercasing  
   - Stopword removal  
   - Lemmatization  
3. Keywords are matched with predefined question–answer pairs  
4. The most relevant response is displayed  

---

## ▶️ How to Run the Project

### 1️⃣ Install Dependencies
```bash
pip install nltk
2️⃣ Download NLTK Resources
python
Copy code
import nltk
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('wordnet')
nltk.download('omw-1.4')
3️⃣ Run the Chatbot
python
Copy code
tellme_bot()
Type your query and press Enter.
Press q to exit.

💬 Sample Input & Output
Input

css
Copy code
CAN I RESERVE RAILWAYS BOOKING
Output

nginx
Copy code
Recently internet reservation facility has started on Indian Railways. 
The website http://www.irctc.co.in is operational...
📂 Project Structure
cpp
Copy code
📁 Elementary-Chatbot-using-basic-NLP-for-Indian-Railways
 ├── README.md
 ├── Elementary Chatbot using basic NLP for Indian Railways.ipynb
🚀 Future Enhancements
Add more railway-related queries

Improve matching using cosine similarity / TF-IDF

Convert to web-based chatbot

Integrate live railway APIs

🤝 Contribution
Contributions are welcome!
Feel free to:

Fork this repository

Create a new branch

Submit a Pull Request

👩‍💻 Author
Shravani P. Deshpande
📌 Computer Engineering Student
📌 Interested in NLP, AI & Software Development

⭐ If you like this project
Don’t forget to star ⭐ the repository and share it with others!
