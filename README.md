# 🤖 Friendly AI Bot

A simple and beginner-friendly **AI chatbot** built using **Python, Streamlit, and Ollama**.
The chatbot allows users to ask questions and receive helpful, friendly, and simple answers from the **Llama 3.2** AI model.

## 🌟 Features

* 🤖 AI-powered chatbot
* 💬 Ask questions using a simple text box
* 🧠 Uses the Llama 3.2 model through Ollama
* 😊 Friendly and encouraging responses
* 🎨 Custom CSS styling
* ⚡ Simple and fast Streamlit interface
* 🐍 Built using Python
* 👩‍💻 Beginner-friendly project

## 🛠️ Technologies Used

* **Python**
* **Streamlit** – For creating the web interface
* **Ollama** – For running the AI model locally
* **Llama 3.2** – AI language model
* **HTML/CSS** – For customizing the appearance

## 📁 Project Structure

```text
Friendly-AI-Bot/
│
├── app.py
├── style.css
├── requirements.txt
└── README.md
```

### `app.py`

Contains the main Python code for the Streamlit chatbot.

### `style.css`

Contains custom CSS used to style the chatbot interface.

### `requirements.txt`

Contains the Python libraries required to run the project.

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Friendly-AI-Bot.git
```

Go to the project folder:

```bash
cd Friendly-AI-Bot
```

### 2. Install Required Python Packages

```bash
pip install streamlit ollama
```

Or, if you have a `requirements.txt` file:

```bash
pip install -r requirements.txt
```

## 🧠 Install Ollama

Download and install Ollama from:

**https://ollama.com/**

After installing Ollama, download the Llama 3.2 model:

```bash
ollama pull llama3.2
```

You can check whether the model is available using:

```bash
ollama list
```

## ▶️ How to Run

Run the Streamlit application using:

```bash
streamlit run app.py
```

The application will open in your browser.

Usually, it will be available at:

```text
http://localhost:8501
```

## 💻 How It Works

The application follows these simple steps:

```text
User enters a question
        ↓
Clicks "Ask AI"
        ↓
Streamlit sends the question
        ↓
Ollama processes the question
        ↓
Llama 3.2 generates the answer
        ↓
AI answer is displayed on the webpage
```

## 📝 Example

**User:**

```text
What is Python?
```

**AI:**

```text
Python is a beginner-friendly programming language
used to build websites, applications, automation tools,
AI systems, and many other things.
```

## 🎨 Custom Styling

The project uses a separate `style.css` file to customize the appearance of the chatbot.

Example:

```css
.answer-box {
    background-color: #f0f2f6;
    padding: 20px;
    border-radius: 10px;
    margin-top: 20px;
}
```

You can modify `style.css` to change:

* Background colors
* Fonts
* Button styles
* Answer box
* Text colors
* Borders
* Spacing

## 📦 Requirements

Example `requirements.txt`:

```text
streamlit
ollama
```

## 🔐 Important Note

This project uses **Ollama locally**, so the Llama 3.2 model needs to be installed on the computer running the application.

If you deploy the application to a cloud platform such as Streamlit Community Cloud, a locally installed Ollama model will **not automatically be available** there. You would need a remotely accessible AI API/service or another deployment setup.

## 🚀 Future Improvements

Some features that can be added in the future:

* 💬 Chat history
* 🎤 Voice input
* 🔊 Text-to-speech
* 🌙 Dark mode
* 📱 Mobile-friendly design
* 🧹 Clear chat button
* 📋 Copy answer button
* 🤖 Multiple AI models
* 👤 User login
* 💾 Save conversations

## 🎯 Learning Outcomes

By building this project, you can learn:

* Python programming
* Streamlit basics
* Working with AI models
* Ollama integration
* HTML and CSS customization
* Git and GitHub
* Basic chatbot development

## 👩‍💻 Author

**Bhargavi**

This project was created as a beginner-friendly AI chatbot project to learn Python, Streamlit, and AI integration.

## ⭐ Support

If you find this project useful, consider giving the repository a ⭐ on GitHub!

---

### 📌 Project Status

**Status:** 🚀 Working Project

**Built with:** Python + Streamlit + Ollama + Llama 3.2
