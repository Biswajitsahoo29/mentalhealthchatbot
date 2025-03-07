# mentalhealthchatbot
A mental health chatbot designed to provide support and resourses for mental well-being using NLP techniques.This project is developed in google colab and deployed using streamlit for an interactive web interface.

# DEMO
[click here to watch](https://raw.githubusercontent.com/Biswajitsahoo29/mentalhealthchatbot/main/app%20-%20Google%20Chrome%202025-03-07%2021-17-28.mp4)

## features
 **Chatbot Interface:**  
  Provides an interactive chatbot interface for mental health support.

- **NLP-Powered Responses:**  
  Uses TF-IDF vectorization and cosine similarity to find the best response to user queries.

- **Streamlit Integration:**  
  The chatbot is deployed via Streamlit for a web-based interface.

- **Expandable Architecture:**  
  The code is structured so you can easily swap in more advanced NLP models later.
  
## installation
**Clone the Repository**  
   ```bash
   git clone https://github.com/Biswajitsahoo29/mentalhealthchatbot.git
   cd mentalhealthchatbot
**check the pythonversion**
python -m venv venv
venv\Scripts\activate
**Install Dependencies**
pip install -r requirements.txt

## run the chatbot
You have two options to run the chatbot:

Option A: Run via Google Colab

Open friendlychatbot.ipynb in Google Colab.
Run each cell in sequence to load data, process text, and launch the chatbot.
The final cell will launch the Streamlit interface for a web-based experience.

option B: If you have converted the notebook code to a Python file (e.g., app.py), run
streamlit run app.py









