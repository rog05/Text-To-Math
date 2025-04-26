📚 Text To Math Problem Solver and Data Search Assistant
This project is a Streamlit web app that uses LangChain and Google Gemma 2 (via Groq API) to solve complex math word problems and fetch information from Wikipedia when needed.
It provides step-by-step logical explanations and quick data searches in one simple interface!

✨ Features
Solve math word problems using LLM reasoning.

Search for information from Wikipedia directly in the chat.

Powered by LangChain tools and Google Gemma 2 model via Groq API.

Simple, interactive chat-based UI with Streamlit.

🛠️ Tech Stack
Python 🐍

Streamlit 🎈

LangChain 🔗

Google Gemma 2 via Groq API 🚀

Wikipedia API 🌐

🚀 How to Run Locally
Clone the repository

bash
Copy
Edit
git clone https://github.com/rog05/text-to-math.git
cd text-to-math
Install required packages

bash
Copy
Edit
pip install -r requirements.txt
Create a .env file (optional) or manually input your Groq API key inside the app.

Run the Streamlit app

bash
Copy
Edit
streamlit run app.py
Enter your Groq API Key in the sidebar when prompted.

🔑 Requirements
Python 3.8+

A valid Groq API Key to access the Google Gemma 2 model.

Install packages manually if requirements.txt is not available:

bash
Copy
Edit
pip install streamlit langchain langchain_groq langchain_community
🧠 How It Works
Input: Enter your math question or general query.

Process:

Math questions are solved using LLMMathChain and logical reasoning prompts.

General information queries are fetched from Wikipedia.

Output: A detailed, step-by-step solution or a summarized answer.

📸 Preview
(You can add a screenshot here later by uploading and linking an image.)

🛡️ License
This project is licensed under the MIT License.

🙌 Acknowledgements
LangChain

Streamlit

Groq

Wikipedia API

Made with ❤️ by rog05
