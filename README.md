# LAKSHMAN_AI-AND-TEXT-INTERFACE
# Lakshman AI: Voice and Text Command Interface

## 🚀 Overview
**Lakshman AI** is a Python-based virtual assistant that enables hands-free operation using **voice and text commands**. It integrates **speech recognition, text-to-speech conversion, web automation, Wikipedia search, media playback, and camera access** to enhance user productivity and accessibility.

---
## 🔥 Features
- **🎙️ Speech Recognition & Response**  
  - Uses **Google Speech Recognition API** for voice command processing.  
  - Converts text to speech using **pyttsx3**.

- **🌐 Web Automation**  
  - Opens frequently used websites like **YouTube, Google, WhatsApp Web, ChatGPT, and online news portals**.  
  - Supports custom URLs for personalized access.

- **📖 Wikipedia Search**  
  - Allows users to search Wikipedia through voice commands.  
  - Retrieves and reads out short summaries.

- **🎵 Media & File Handling**  
  - Plays random songs from a predefined directory.  
  - Opens local applications like **VS Code and Photo Viewer**.

- **⏳ Time Announcement**  
  - Fetches and announces the **current time** on request.

- **📸 Camera Access**  
  - Captures and saves photos using the **webcam**.

---
## 🛠️ Installation & Setup
### Prerequisites
Ensure you have **Python 3.x** installed along with the following dependencies:
```bash
pip install speechrecognition pyttsx3 pyaudio wikipedia opencv-python
```

### Running the Assistant
1. Clone the repository:
```bash
git clone https://github.com/yourusername/lakshman-ai.git
```
2. Navigate to the project directory:
```bash
cd lakshman-ai
```
3. Run the script:
```bash
python lakshman.py
```

---
## 🎯 Usage Examples
- **"Open YouTube"** → Opens YouTube in the default web browser.
- **"Wikipedia Albert Einstein"** → Retrieves and reads a summary of Albert Einstein.
- **"Open music"** → Plays a random song from the local directory.
- **"The time"** → Announces the current time.
- **"Open camera"** → Captures a photo using the webcam.

---
## ⚙️ Technologies Used
- **Python Libraries:**
  - `speech_recognition` → Recognizes voice commands.
  - `pyttsx3` → Converts text to speech.
  - `webbrowser` → Opens web pages.
  - `wikipedia` → Fetches summaries from Wikipedia.
  - `os` → Handles file and application execution.
  - `random` → Plays random songs.
  - `time` → Introduces time delays.
  - `pyaudio` → Enables microphone input.
  - `opencv-python` → Captures images using the webcam.

---
## 📌 Future Enhancements
- Add **email sending functionality**.
- Implement **calendar and reminder features**.
- Improve **natural language understanding** for more conversational interactions.

---
## 🤝 Contributing
Contributions are welcome! Feel free to fork the repository and submit a **pull request**.



