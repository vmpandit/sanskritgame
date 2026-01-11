# Sanskrit Quest: The Grand Master Edition 🕉️

A comprehensive, gamified web application designed to take users from absolute beginner to advanced proficiency in Sanskrit. This **Grand Master Edition** combines the foundational "Golden Path" (Year 1) with the advanced "Master's Path" (Year 2) into a single, seamless single-page application (SPA).

![Version](https://img.shields.io/badge/version-2.0.0-GrandMaster)
![License](https://img.shields.io/badge/license-MIT-blue)
![Tech](https://img.shields.io/badge/built%20with-HTML5%20%7C%20CSS3%20%7C%20JS-orange)
![AI Assisted](https://img.shields.io/badge/AI-Assisted-purple)

## 📖 Overview

**Sanskrit Quest** bridges the gap between ancient knowledge and modern digital learning. Based on pedagogical research for second-language acquisition, it guides users from the basics of the Devanagari script to reading classical texts like the *Bhagavad Gītā* and *Hitopadeśa*.

The entire application is a **single-file HTML5** project, making it ultra-portable, offline-capable, and easy to deploy.

## ✨ Key Features

### 🎓 Complete 2-Year Curriculum
The game features **28 progressive lessons** split into two major arcs:

#### **Year 1: The Foundation**
- **Script Mastery:** Vowels, Consonants, Conjuncts, and Diacritics.
- **Grammar Core:** Noun Cases (*Vibhakti*) and Verb Roots (*Dhatu*).
- **Sandhi Rules:** Vowel and Visarga phonetic fusion.
- **Reading:** Simple sentences and ancient mottos (*Subhāṣita*).

#### **Year 2: Advanced Mastery**
- **Compounds (Samāsa):** Tatpuruṣa, Dvandva, and Bahuvrīhi construction.
- **Advanced Verbs:** Optative Mood (*Vidhilin*) and Passive Voice (*Karmani Prayoga*).
- **Participles:** Present and Past Passive Participles.
- **Prosody (Chandas):** Recognizing and scanning the Anuṣṭubh meter.
- **Classical Texts:** Excerpts from the *Hitopadeśa* and *Bhagavad Gītā*.

### 🎮 Interactive Mini-Games
- **🧠 Memory Match:** Test your recall of vocabulary unlocked during Year 1 lessons.
- **🔨 Compound Builder:** Drag-and-drop mechanics to construct complex Sanskrit compound words (Year 2).
- **🎵 Meter Master:** A rhythm-based game to identify long/short syllable patterns in poetry.
- **↩️ Voice Transformer:** Convert active voice sentences into passive voice.
- **🛤️ The Journey (RPG):** A branching dialogue adventure where you interact with a Sage using the skills you've learned.

### 🎨 Modern UI/UX
- **Cinematic Glassmorphism:** High-end, frosted-glass aesthetic with realistic textures (Gold/Stone).
- **Animation Engine:** Staggered list entrances, particle explosion effects for victories, and haptic visual feedback.
- **Responsive Design:** Fully optimized for Desktop, Tablet, and Mobile.

## 🛠️ Technical Implementation

- **Stack:** Pure HTML5, CSS3, and Vanilla JavaScript (ES6+).
- **Storage:** Uses `localStorage` to persist user progress (XP, unlocked lessons, vocabulary, achievements) without a backend database.
- **Single Page Application (SPA):** Dynamic DOM manipulation ensures a seamless experience without page reloads.

## 🚀 Quick Start

### Running Locally
1. Download `sanskrit_grand_master.html`.
2. Open the file in any modern web browser (Chrome, Firefox, Safari, Edge).
3. Start playing! No server or installation required.

### Deployment
Since this is a static file, you can deploy it instantly on:
- **GitHub Pages:** Upload to your repo and enable Pages.
- **Netlify/Vercel:** Drag and drop the HTML file.

## 📚 Pedagogical Approach

The game follows a **"Chunking & Active Recall"** methodology:
1. **Introduction:** Concepts are introduced in small, manageable blocks.
2. **Active Recall:** Immediate "Trials" (quizzes) force the user to retrieve information, strengthening neural pathways.
3. **Spaced Repetition:** The "Training Grounds" (Memory Match, Flashcards) allow users to review vocabulary at intervals.

## 🤖 Acknowledgements

This project was architected and developed with the collaborative assistance of **Claude** (Anthropic) and **Gemini** (Google) AIs. 

These AI models assisted in:
- **Pedagogical Research:** Synthesizing effective methods for teaching Sanskrit to non-native speakers.
- **Code Generation:** Generating the HTML5 game engine, CSS animations, and JavaScript logic.
- **Content Creation:** Structuring the complete 2-year curriculum, including vocabulary lists and grammar paradigms.

## 🤝 Contributing

Contributions are welcome! If you'd like to add new lessons or mini-games:
1. Fork the repository.
2. Locate the `gameData` object in the `<script>` section.
3. Add a new object to the `lessons` array following the existing schema.
4. Submit a Pull Request.

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.

---
*Created as an innovative educational tool for Sanskrit preservation and global learning.*
