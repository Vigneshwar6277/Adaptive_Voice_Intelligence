# 🔊 Voice-Based Python Projects

This repository includes three Python-based voice-interactive applications developed for smart and accessible use cases:

- 🌐 Language Translator  
- 💬 Voice Assistant for ELRD (Elderly/Language Reading Disabled)  
- 💡 Voice-Based Appliance Control  

These projects use Python libraries such as `speech_recognition`, `pyttsx3`, `deep_translator`, and `pyserial`.

---

## 🌐 Language Translator

A voice-activated translator that listens to speech in one language and speaks out the translation in another.

### Features:
- Converts speech to text using microphone input.
- Translates text using `googletrans` or `deep_translator`.
- Converts translated text to speech using `pyttsx3` for offline playback.
- Supports multiple languages for input and output.

---

## 💬 Voice Assistant for Elderly 

A lightweight voice assistant specially tailored for elderly users and individuals with reading disabilities.

### Features:
- Responds to simple voice commands such as greetings, time, and date.
- Reads aloud predefined notes or helpful information.
- Slow and clear speech for better understanding.
- Simple and accessible interface with minimal dependencies.

---

## 💡 Voice-Based Appliance Control

A speech-enabled Python system to control household electrical appliances through voice commands.

### Features:
- Recognizes commands like “Turn on the fan” or “Switch off the light.”
- Communicates with microcontrollers (like Arduino or ESP32) via serial ports using `pyserial`.
- Gives audible confirmation using `pyttsx3` after executing each action.
- Can be integrated into home automation systems.

---

## 🧰 Dependencies

- `speechrecognition`
- `pyttsx3`
- `pyaudio`
- `deep-translator` or `googletrans`
- `pyserial` (for appliance control)

All libraries are compatible with Python 3.x and can be installed via pip.

