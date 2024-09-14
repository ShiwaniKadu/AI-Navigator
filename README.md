# 🌟 AI - Navigator: Your Personal Voice-Powered Assistant

AI - Navigator is an advanced, voice-activated virtual assistant designed to streamline your everyday tasks. From opening websites, playing your favorite music, to fetching news, and even holding intelligent conversations, **AI - Navigator** is here to make your life easier.

### 🚀 Features
- **Web Navigation**: Open popular websites like Google, Facebook, YouTube, and LinkedIn via voice commands.
- **Music Playback**: Simply say "Play [song name]" and let AI - Navigator find and play your favorite songs.
- **News Updates**: Get the latest news headlines from top sources using the **NewsAPI** integration.
- **AI Conversations**: Engage in natural conversations using the powerful **GPT-3.5 Turbo** model by OpenAI.
- **Speech Recognition**: Powered by Google's Speech Recognition API, AI - Navigator listens to your voice commands with high accuracy.
- **Text-to-Speech Responses**: Realistic voice responses using **gTTS** and **pygame**.

---

### 🛠️ Technologies Used
- **Python**: Core language for scripting the virtual assistant.
- **SpeechRecognition**: To capture and process voice input.
- **pyttsx3**: Text-to-speech engine.
- **gTTS**: Google Text-to-Speech for converting responses into voice.
- **pygame**: For playing back the audio responses.
- **Webbrowser**: For opening websites based on user commands.
- **NewsAPI**: Fetches the latest news headlines.
- **OpenAI GPT-3.5 Turbo**: Used to generate intelligent, human-like responses in conversations.
- **Music Library**: Custom music library integration for playing songs based on user input.

---

### ⚙️ Setup and Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/YourUsername/AI-Navigator.git
    cd AI-Navigator
    ```

2. **Install Required Dependencies**:
    Ensure you have **Python 3.8+** installed, then run:
    ```bash
    pip install -r requirements.txt
    ```

3. **Configuration**:
    Add your API keys for OpenAI and NewsAPI in the `config.py` file:
    ```python
    NEWSAPI_KEY = 'your-news-api-key-here'
    OPENAI_API_KEY = 'your-openai-api-key-here'
    ```

4. **Run the Assistant**:
    Start the AI - Navigator by running the following:
    ```bash
    python main.py
    ```

---

### 🎯 How to Use

1. **Trigger the Assistant**: 
    Start by saying **"Aura"** (or customize the wake word). AI - Navigator will acknowledge and await further commands.
    
2. **Give Commands**:
    - To **open a website**: Say "Open Google," "Open Facebook," etc.
    - To **play music**: Say "Play [song name]."
    - To **fetch news**: Say "What's the news today?"
    - To **have a conversation**: Simply ask questions or give a command, and AI - Navigator will respond intelligently.

---

### 💡 Example Commands
- "Aura, open Google."
- "Play Blinding Lights."
- "Give me the latest news."
- "Tell me a joke."

---

### 🧠 AI Model Integration
The project uses **GPT-3.5 Turbo** from OpenAI, enabling advanced conversational capabilities. AI - Navigator can perform a range of tasks, making it more than just a simple voice assistant.

---

### 🤖 Future Enhancements
- **Task Management**: Adding smart reminders and task scheduling.
- **Home Automation**: Integration with IoT devices for home automation.
- **Voice Authentication**: Secure the assistant with user voice authentication.

---

### 🙏 Credits
- **OpenAI** for GPT-3.5 Turbo.
- **Google Speech API** for accurate voice recognition.
- **NewsAPI** for fetching the latest news headlines.
- **gTTS** and **pyttsx3** for text-to-speech conversion.
- All contributors to this project.

---

### 🔗 Useful Links
- [GitHub Repository](https://github.com/ShiwaniKadu/AI-Navigator)
- [OpenAI GPT-3](https://openai.com/)
- [NewsAPI](https://newsapi.org/)

---

Happy Coding! 🚀

