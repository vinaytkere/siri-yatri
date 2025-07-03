# 🚕 Siri Yatri – A Voice-Based Assistant for Booking Auto/Cab Inspired by Namma Yatri

Siri Yatri is an accessibility-first extension designed to help **elderly users** and **non-English speakers** book rides easily using **voice input** in their local language.

---

## 🎯 Problem It Solves

Many elderly or illiterate users:

- Cannot operate ride-hailing apps
- Cannot type or read destinations
- Struggle with OTP or fare confirmation

---

## 🧠 The Solution

Siri Yatri is a **refactored version of the open-source Namma Yatri app**, built to work as a voice-first experience. It listens, speaks, and guides users through:

1. 🎤 **Voice input** – “ನಾನು ವಿಜಯನಗರಕ್ಕೆ ಹೋಗಬೇಕು”
2. 📍 Uses current location as source
3. 📲 Auto-fills destination and proceeds to booking
4. ✅ Confirms ride automatically
5. 🔊 Reads OTP and fare **out loud** in Kannada or local language

---

## 🗣️ Target Users

- Senior citizens
- Illiterate or semi-literate users
- Non-English speakers
- Visually impaired users (future scope)

---

## 💻 Tech Stack

| Layer            | Tool/Framework                               |
| ---------------- | -------------------------------------------- |
| Voice Input      | Android STT API                              |
| Text-to-Speech   | Android TTS Engine                           |
| UI Layer         | React Native (Namma Yatri base)              |
| App Integration  | Direct code refactoring + Accessibility APIs |
| Platform Support | Android (primary)                            |

---

## 🛠️ Architecture (Simplified)

```
User (Voice) 🎤
     ↓
Siri Yatri (Refactored Namma Yatri App)
     ↓
Fill destination via voice → proceed to booking
     ↓
Monitor OTP / Fare via app logic or accessibility service
     ↓
Read OTP & fare aloud 🔊
```

---

## ✅ Key Features

- Local language voice support (e.g., Kannada)
- OTP and price reading aloud
- Auto-fills destination using voice
- Simple UI with large buttons
- No additional backend required

---

## 📦 Future Scope

- Support other languages (Hindi, Tamil, Telugu…)
- Integrate with other ride apps (Ola, Uber)
- Emergency button for family alert
- WhatsApp-based ride updates

---

## 🤝 Contribution / Contact

If you'd like to collaborate, support, or extend this idea, feel free to reach out:

- 📧 [Email](mailto\:tvinay81@gmail.com)
- 🌐 [LinkedIn](https://www.linkedin.com/in/vinay-s-a00850a0/)

---

## 🛡️ Licensing & Acknowledgements

This project is open-source and intended for public good.\
All credits to **Namma Yatri** and **Juspay** for the original rider app and open source contribution.

Siri Yatri is an independent accessibility-focused extension and not affiliated officially (yet).

