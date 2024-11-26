# AI Voice Assistant using OpenAI API 🎙️🤖  

This is a Python-based voice assistant that uses OpenAI's GPT models to generate intelligent responses. It combines speech recognition, text-to-speech functionality, and basic web automation to create an interactive AI assistant.

---

## Features  
- 🎤 **Speech Recognition**: Converts your voice commands into text using the `speech_recognition` library.  
- 🧠 **AI-Powered Responses**: Leverages OpenAI's GPT models for accurate and intelligent answers.  
- 🔊 **Text-to-Speech**: Converts text responses into spoken output using the `pyttsx3` library.  
- 🌐 **Web Automation**: Opens popular websites (e.g., YouTube, Google) based on voice commands.  
- 🛑 **Exit Command**: Say "bye" to terminate the program.

---

## Tech Stack  
- **Programming Language**: Python  
- **Libraries**:  
  - `speech_recognition` for voice input  
  - `pyttsx3` for voice output  
  - `webbrowser` for URL handling  
  - OpenAI API for AI-generated responses  

---

## Setup and Installation  

### Prerequisites  
- Python 3.7 or higher installed  
- An OpenAI API key ([Get it here](https://platform.openai.com/signup/))  

### Installation Steps  
1. **Clone the Repository**:  
   ```bash
   git clone https://github.com/your-repo/ai-voice-assistant.git
   cd ai-voice-assistant

2. **Install Required Libraries**:
   Install the dependencies listed in the requirements.txt file:
   ```bash
   pip install -r requirements.txt

3. **Add Your OpenAI API Key**:
   Open apikey.py./n
   Replace the placeholder with your OpenAI API key:
   ```bash
   api_data = 'your-api-key'
   
4.**Run the Application**:
```bash
   python app.py
```
/n

## Usage
- Speak a question or command into your microphone.
- The assistant will process your input, generate a response, and speak it aloud.
- **Supported commands include general questions and actions like**:
     - `What is the capital of France?`
     - `Open YouTube`
     - `Bye (to exit the program).`

### ***Example Interaction***
- User: "What is the capital of France?"
   - `Assistant: "The capital of France is Paris."`

- User: "Open YouTube"
   - `Opens YouTube in the default browser`

- User: "Bye"
  - `Program exits`

