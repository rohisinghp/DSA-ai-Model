# 💬 gyaanAI – Your Personal DSA & Programming Chat Assistant

gyaanAI is an AI-powered web-based chatbot designed specifically for answering questions related to **Data Structures and Algorithms (DSA)** and **programming languages** like C, C++, Java, and Python.

It’s powered by Google's **Gemini 1.5 Flash API**, and provides precise, code-based responses. If the user asks anything unrelated to programming or DSA, it responds rudely and concisely (just as instructed 😉).

---

## 🚀 Features

- 🎯 Focused only on DSA and programming topics.
- 💬 Chat interface with history.
- 🤖 Gemini 1.5 Flash API integration.
- 🧠 System instruction to keep responses on-topic.
- 🧾 LocalStorage-based chat persistence.
- 🎨 Beautiful dark-themed UI built with pure HTML, CSS & JavaScript.

---

## 📸 Screenshot
<img width="1079" height="566" alt="image" src="https://github.com/user-attachments/assets/8add3669-c5f7-4c19-807d-186b88d150fb" />

---

## 🛠️ Technologies Used

- HTML5, CSS3 (custom theme, no frameworks)
- Vanilla JavaScript
- Google Gemini API (`gemini-1.5-flash` model)

---

## ⚙️ Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/rohitsinghp/gyaanAI.git
   cd gyaanAI

2. **Add gemini api key**
   
const GEMINI_API_KEY = "YOUR_GEMINI_API_KEY";
Open in Browser

Just open index.html in your browser. No server setup needed!

**🧠 How It Works**

Uses Google Gemini API to generate responses.
Each conversation is saved to localStorage with a unique ID.
System instruction ensures responses are limited strictly to DSA/programming.
If users ask unrelated questions, the model replies rudely (as per instruction 😈).

**✨ Example Prompts**

What is the time complexity of merge sort?
How do I reverse a linked list in C++?
Explain recursion with code in Python.


**🚫 Limitations**

Only answers DSA/programming questions. All other topics are rejected rudely.
Requires an internet connection to call Gemini API.
No server-side logic – all runs in-browser.


🧑‍💻 Author

Created by Rohit Singh👨‍💻
Part of a learning journey into AI + Frontend + APIs.

**📄 License**

This project is open-source and available under the MIT License.
