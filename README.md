=================== README_Translator ===================

# CodeAlpha_Translator

## 📌 Overview
A Language Translation Tool built with Flask, developed as **Task 1** of the **CodeAlpha Artificial Intelligence Internship (2026)**. It translates text between multiple languages using Google Translate via the `deep-translator` library.

## ✨ Features
- Select source and target language
- Auto-detect source language
- Swap languages with one click
- Copy translated text
- Text-to-speech for the translation

## 🛠️ Tech Stack
- Python 3, Flask
- deep-translator
- HTML, CSS, JavaScript

## 📂 Project Structure
```
CodeAlpha_Translator/
├── app.py
├── requirements.txt
└── README.md
```

## ⚙️ Installation & Usage
```
git clone https://github.com/YOUR_USERNAME/CodeAlpha_Translator.git
cd CodeAlpha_Translator
pip install -r requirements.txt
python app.py
```
Open **http://127.0.0.1:5000** in your browser.

## 📸 Screenshots
(Add screenshot here)

## 👨‍💻 Author
**Rahul Pal** – BCA Student


=================== README_FAQ_Chatbot ===================

# CodeAlpha_FAQ_Chatbot

## 📌 Overview
An FAQ Chatbot developed as **Task 2** of the **CodeAlpha Artificial Intelligence Internship (2026)**. It understands a user's question and returns the most relevant answer from a set of FAQs using NLP.

## ⚙️ How It Works
1. Preprocess text with NLTK (tokenization, stopword removal, lemmatization)
2. Convert questions to vectors using **TF-IDF**
3. Find the best match using **cosine similarity**
4. Return the answer of the closest FAQ

## ✨ Features
- Works in terminal and as a web chat UI
- FAQs stored in an easy-to-edit `faqs.json`
- Handles differently worded questions

## 🛠️ Tech Stack
- Python 3, NLTK, scikit-learn, Flask

## 📂 Project Structure
```
CodeAlpha_FAQ_Chatbot/
├── chatbot.py      # terminal chatbot + core logic
├── app.py          # Flask web UI
├── faqs.json       # FAQ data
├── requirements.txt
└── README.md
```

## ⚙️ Installation & Usage
```
git clone https://github.com/YOUR_USERNAME/CodeAlpha_FAQ_Chatbot.git
cd CodeAlpha_FAQ_Chatbot
pip install -r requirements.txt
python chatbot.py    # terminal chat
python app.py        # web UI at http://127.0.0.1:5000
```

## 📸 Screenshots
(Add screenshot here)

## 👨‍💻 Author
**Rahul Pal** – BCA Student


=================== README_Object_Detection_Tracking ===================

# CodeAlpha_Object_Detection_Tracking

## 📌 Overview
Real-time object detection and tracking, developed as **Task 4** of the **CodeAlpha Artificial Intelligence Internship (2026)**. It detects objects with **YOLOv8** and tracks them across frames with **Deep SORT**, showing labels and unique tracking IDs.

## ✨ Features
- Real-time detection from webcam or video file
- Class labels with bounding boxes
- Unique tracking ID for each object
- Built with OpenCV for display

## 🛠️ Tech Stack
- Python 3
- Ultralytics (YOLOv8), deep-sort-realtime, OpenCV

## 📂 Project Structure
```
CodeAlpha_Object_Detection_Tracking/
├── main.py
├── requirements.txt
└── README.md
```

## ⚙️ Installation & Usage
```
git clone https://github.com/YOUR_USERNAME/CodeAlpha_Object_Detection_Tracking.git
cd CodeAlpha_Object_Detection_Tracking
pip install -r requirements.txt
python main.py              # webcam
python main.py video.mp4    # video file
```
Press **q** to quit.

## 📸 Screenshots
(Add screenshot here)

## 👨‍💻 Author
**Rahul Pal** – BCA Student


