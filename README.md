# 💎 Kendra Scott Client Manager

A Progressive Web App (PWA) built to streamline personalized client outreach for a Kendra Scott sales specialist at Dillard's. Designed, conceived, and developed to solve a real workflow problem — no coding background required to build it, just problem-solving instincts and the right tools.

> **Live app:** [andreacmiranda.github.io/ks-clientmanager](https://andreacmiranda.github.io/ks-clientmanager/)

---

## 🌟 The Problem

As a Kendra Scott specialist, building client relationships means remembering birthdays, knowing when new pieces arrive, and reaching out personally — all while working a full retail shift. Doing this manually across a growing client book was slow, inconsistent, and easy to forget.

## 💡 The Solution

A fully offline-capable PWA that lives on my phone's home screen like a native app. It manages my client database, generates personalized text messages in seconds, and gives me instant access to brand knowledge — all in one place.

---

## ✨ Features

### 📋 Client Database
- Add, search, and filter clients by name, phone, birthday month, and preferences
- Birthday month highlighting so you never miss a discount opportunity
- Dashboard stats showing total clients, birthday count, and most common months

### 📸 AI-Powered Photo Import
- Upload a photo of a handwritten client list
- Claude AI (vision model) reads the handwriting and extracts structured data automatically
- Editable review table lets you verify and correct before saving — no blind trust in AI
- Turns a 30-minute manual data entry job into under 60 seconds

### 💬 Message Composer
- 4 pre-built templates: Birthday discount, New arrivals, Promotion, and Introduction
- Auto-fills client name into the message
- Product image attachment via drag & drop or paste (Ctrl+V)
- iMessage-style bubble preview before sending
- One-tap to open Messages app with the text pre-loaded

### 🔍 Product Search
- Search any Kendra Scott product by name
- Generates a working Dillard's search URL instantly
- Correct URL format reverse-engineered from live site structure

### 📚 Brand Knowledge Base
- Birthstones by month with direct Dillard's search links for each stone's Elisa pendant
- All 6 metal/finish types with care instructions
- 7 key selling points with talking points
- Top 5 best sellers with pricing and stats (the Elisa sells one per minute globally)
- Buyer demographics by age group
- Objection handling scripts for the 4 most common customer pushbacks

### 📅 Reminders
- Shows all clients with birthdays in the current month
- One-tap to launch a pre-composed birthday message to all of them at once

---

## 🛠️ Built With

| Technology | Purpose |
|---|---|
| HTML5 | App structure |
| CSS3 | Styling, responsive layout, animations |
| Vanilla JavaScript | All app logic, state management |
| Web Storage API (localStorage) | Client data persistence — stays on device, never uploaded |
| Claude API (Anthropic) | AI vision for handwritten client list import |
| Service Worker API | Offline functionality and caching |
| Web App Manifest | PWA installability — home screen icon, standalone display |

---

## 🔒 Privacy & Security

Client data (names, phone numbers, birthdays) is stored exclusively in the browser's `localStorage` on the user's device. It is never transmitted to any server, never stored in this repository, and never accessible to anyone else. The app code is public; the data is private.

---

## 📱 Installation (Add to Home Screen)

1. Open the [live app](https://andreacmiranda.github.io/ks-clientmanager/) in Safari on iPhone
2. Tap the **Share** button (box with arrow)
3. Tap **"Add to Home Screen"**
4. Tap **Add**

The app installs with a custom icon and opens fullscreen — no browser bar, no App Store required.

---

## 💼 About This Project

This app was built collaboratively using AI-assisted development as a tool — similar to how a developer might use Stack Overflow, documentation, or a senior colleague. The core of the project came from identifying a real problem in my daily work, designing a solution, making product decisions, and iterating based on real usage.

Skills demonstrated:
- **Product thinking** — identified a genuine workflow gap and designed a solution around it
- **Technical communication** — learned to read, understand, and modify HTML/CSS/JS code
- **AI literacy** — used AI tools strategically for both development assistance and as an in-app feature (vision import)
- **Iteration** — debugged real issues (encoding bugs, broken URLs, UX improvements) across multiple versions

---

## 👩‍💻 Author

**Andrea Miranda**
Kendra Scott Sales Specialist, Dillard's Tallahassee
Aspiring tech professional

[LinkedIn](https://www.linkedin.com/in/andreacmirandaa/) · [GitHub](https://github.com/andreacmiranda)

---

*Built with curiosity, Claude AI, and a lot of client sheets to manage.*
