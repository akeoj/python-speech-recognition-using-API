# 🎤 Speech Recognition App

A simple **Speech-to-Text** application built with **Streamlit** and **SpeechRecognition** to transcribe spoken words into text. It supports multiple recognition APIs and allows users to choose their preferred language.

## 🚀 Features
- 🎙️ **Real-time Speech Recognition** using Google Speech Recognition or Sphinx (offline)
- 🌍 **Supports Multiple Languages** (User can specify language codes)
- 💾 **Save Transcriptions** to a text file
- ⏸️ **Pause & Resume Recording**
- 🔧 **Error Handling** for better user experience

## 📦 Installation
```sh
# Clone the repository
git clone https://github.com/yourusername/speech-recognition-app.git
cd speech-recognition-app

```

## ▶️ Usage
```sh
streamlit run app.py
```
Then open the link displayed in the terminal to use the app.

## 🛠 Dependencies
- `streamlit`
- `speechrecognition`
- `pyaudio` *(for microphone access)*
- `pocketsphinx` *(if using offline recognition)*

Install them with:
```sh
pip install streamlit speechrecognition pyaudio pocketsphinx
```

## 📜 Supported APIs
- **Google Speech Recognition** *(Default, requires internet)*
- **Sphinx (Offline)** *(Requires `pocketsphinx`)*

## 📌 Language Support
Provide a language code (e.g., `en-US` for English, `fr-FR` for French) in the app.

## 🎯 Roadmap
- 🔹 Add support for more Speech-to-Text APIs (e.g., Whisper, Azure, Deepgram)
- 🔹 Implement real-time transcription display
- 🔹 Improve UI with enhanced styling

## 🤝 Contributing
Feel free to fork this repository, make improvements, and submit a PR! 🚀

## 📄 License
This project is licensed under the APACHE 2.0 License.

---

💡 *Let's build amazing AI-powered applications together!*
