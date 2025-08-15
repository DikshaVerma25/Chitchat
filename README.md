# 🌍 Chitchat (Working Title)

A **speech-focused language learning app** that helps users learn new words and practice speaking through daily conversations.  
The app introduces **10 new words each day**, then engages the user in a **guided spoken conversation** using both the new and previously learned vocabulary.  
The goal is to make language learning **interactive, natural, and fun**.

---

## 📌 Objective
The main objective of this application is to help users:
- Build vocabulary through **daily word learning**.
- Improve **speaking and listening skills** by holding real conversations.
- Retain learned words using **spaced repetition** and repeated usage.
- Practice consistently with **5–10+ minutes of speech-focused sessions**.

---

## ✨ Features
- **Daily Vocabulary Delivery** – 10 new words/day with meaning, pronunciation, and example sentences.
- **Speech Recognition** – Understands and transcribes user’s spoken responses in the target language.
- **Speech Synthesis** – Generates natural-sounding speech for conversation prompts.
- **Guided Conversation Mode** – Conversations that adapt to the user’s vocabulary level.
- **Cumulative Learning** – Each conversation reuses old words while adding new ones.
- **Pronunciation Feedback** – Detects and highlights mispronounced words.
- **Custom Session Length** – Choose 5, 10, or more minutes per day.

---

## 🛠 Tech Stack
**Frontend:**
- React Native (cross-platform mobile) or Flutter
- Audio recording & playback support

**Backend:**
- Node.js or Python (FastAPI)
- Database: Firebase Firestore / Supabase

**Speech Recognition (ASR):**
- OpenAI Whisper API  
  or  
- Google Speech-to-Text

**Speech Synthesis (TTS):**
- Google Cloud TTS / Azure Neural TTS / Amazon Polly

**AI Conversation Engine:**
- GPT-based LLM with controlled vocabulary prompts

---

## 🚀 How It Works
1. **Learn** – App presents 10 new words with audio + examples.
2. **Repeat** – User practices pronunciation; app checks accuracy.
3. **Talk** – Engage in 5–10+ min guided spoken conversation.
4. **Review** – End-of-session recap with performance stats.

---

## 📅 Roadmap
- [ ] Speech recognition prototype
- [ ] TTS integration
- [ ] Vocabulary dataset integration
- [ ] Conversation engine
- [ ] Progress tracking
- [ ] Pronunciation scoring
- [ ] Beta release

---

## 🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first  
to discuss what you would like to change.

---

## 📄 License
[MIT License](LICENSE)
