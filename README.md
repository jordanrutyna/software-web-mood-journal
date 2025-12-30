# Daily Mood Journal 📝

A simple journaling web app that allows users to log their mood, write daily reflections, receive an inspirational quote, and review past entries directly in the browser.

This project was built as a **foundational portfolio project** to practice core frontend concepts using vanilla web technologies.

---

## ✨ Features

- Select a mood using emoji-based buttons
- Write and save journal entries
- Fetch a daily piece of advice using a public API
- Persist entries and quotes using browser `localStorage`
- View a list of past entries, sorted by most recent
- Edit or delete previous entries
- Clean, card-based UI with hover actions
- Fully responsive layout (desktop & mobile)

---

## 🛠️ Tech Stack

- **HTML5** – semantic structure
- **CSS3** – layout, styling, hover effects
- **JavaScript (Vanilla)** – DOM manipulation, events, state handling
- **Browser APIs**
  - `localStorage` for persistence
  - `fetch()` for API requests
- **Advice Slip API** – public advice/quote source

---

## 📦 Data Persistence

All journal entries and associated quotes are stored locally in the browser using `localStorage`.  
Each entry is saved with unique timestamp-based key, allows multiple entries per day.

> No backend or database is used, intended for lightweight frontend project.

---

## 🌐 API Notes

Quotes are fetched from the **Advice Slip API**, which supports browser-based requests without authentication or CORS issues.

```txt
https://api.adviceslip.com/advice

