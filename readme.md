# Sanskrit Quest: The Golden Path 🕉️

A modern, gamified web application designed to teach Sanskrit to non-Indian language speakers through immersive, interactive gameplay. Built with a high-fidelity "Cinematic Glassmorphism" UI, it combines proven language acquisition methods with RPG elements.

![Version](https://img.shields.io/badge/version-1.0.0-gold)
![License](https://img.shields.io/badge/license-MIT-blue)
![Tech](https://img.shields.io/badge/built%20with-HTML5%20%7C%20CSS3%20%7C%20JS-orange)
![AI Assisted](https://img.shields.io/badge/AI-Assisted-purple)

## 📖 Overview

**Sanskrit Quest** bridges the gap between ancient knowledge and modern digital learning. Based on pedagogical research for second-language acquisition, it guides users from the basics of the Devanagari script to constructing simple sentences and reading ancient verses.

The entire application is a **single-file HTML5** project, making it ultra-portable, offline-capable, and easy to deploy.

## ✨ Key Features

### 🎓 Structured Curriculum (Year 1 Level)
- **Script Mastery:** Progressive lessons for Vowels, Consonants, and Conjuncts.
- **Grammar Core:** Interactive paradigms for Noun Cases (*Vibhakti*) and Verb Roots (*Dhatu*).
- **Sandhi & Reading:** dedicated modules for phonetic fusion rules and subhāṣita (verses).

### 🎮 Gamification Engine
- **XP & Leveling System:** Earn experience for every correct answer to rank up.
- **Streak Tracking:** incentivizes daily practice.
- **Achievements:** 6 unique unlockable badges stored permanently.
- **Story Mode:** A branching dialogue RPG where you must speak correct Sanskrit to progress through the story.

### 🎨 Modern UI/UX
- **Cinematic Glassmorphism:** High-end, frosted-glass aesthetic with realistic textures (Gold/Stone).
- **Animation Engine:** Staggered entrances, particle effects for victories, and haptic visual feedback.
- **Responsive Design:** Fully optimized for Desktop, Tablet, and Mobile.

## 🛠️ Technical Implementation

- **Stack:** Pure HTML5, CSS3, and Vanilla JavaScript (ES6+).
- **Storage:** Uses `localStorage` to persist user progress (XP, unlocked lessons, vocabulary) without a backend database.
- **Single Page Application (SPA):** Dynamic DOM manipulation ensures a seamless experience without page reloads.

## 🚀 Quick Start

### Running Locally
1. Download `sanskrit_master_edition.html`.
2. Open the file in any modern web browser (Chrome, Firefox, Safari, Edge).
3. Start playing! No server or installation required.

### Deployment
Since this is a static file, you can deploy it instantly on:
- **GitHub Pages:** Upload to your repo and enable Pages.
- **Netlify/Vercel:** Drag and drop the HTML file.

## 📚 Pedagogical Approach

The game follows a **"Chunking & Active Recall"** methodology:
1. **Introduction:** Concepts are introduced in small, manageable blocks (e.g., 5 vowels at a time).
2. **Active Recall:** Immediate "Trials" (quizzes) force the user to retrieve information, strengthening neural pathways.
3. **Spaced Repetition:** The "Training Grounds" (Memory Match, Flashcards) allow users to review vocabulary intervals.

## 🤖 Acknowledgements

This project was architected and developed with the collaborative assistance of **Claude** (Anthropic) and **Gemini** (Google) AIs. 

These AI models assisted in:
- **Pedagogical Research:** Synthesizing effective methods for teaching Sanskrit to non-native speakers.
- **Code Generation:** Generating the HTML5 game engine, CSS animations, and JavaScript logic.
- **Content Creation:** Structuring the first-year Sanskrit curriculum, including vocabulary lists and grammar paradigms.

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
