# 📚 RevEdge — Your Revision. Your Edge.

> A smart, spaced-repetition revision tracker for competitive exam aspirants — CAT, GMAT, GRE, UPSC, JEE, NEET, and more. Built as a zero-dependency, single HTML file that works on any device including iPhone.

---

## ✨ Live Demo

Deploy on Netlify in 30 seconds — drag & drop `index.html` at [netlify.com](https://netlify.com)https://rev-edge-dhavalpatel.netlify.app/

Netlify: https://rev-edge-dhavalpatel.netlify.app/
Vercel : https://revedge1-dhavalpatel-pxiuu550p-dhavalpatelpms-projects.vercel.app/
---

## 🎯 What is RevEdge?

RevEdge is a **mobile-first revision companion** that uses the science of **spaced repetition** to ensure you never forget what you've learned. Instead of cramming, you revise each topic at the exact right moment — just before you're about to forget it.

### The Science Behind It
After you learn a topic, RevEdge schedules your revisions at increasing intervals:

```
Learn → 2 days → 3 days → 5 days → 7 days → 10 days → ✨ Mastered
```

This mirrors the **Ebbinghaus Forgetting Curve** — the most proven method to move knowledge from short-term to long-term memory.

---

## 📱 Features

### 🏠 Home Tab
- Personalised greeting with time-based message
- **Primary exam countdown** with progress bar
- Secondary & tertiary exam countdowns
- Today's revision due cards with one-tap completion
- Section-wise progress bars (VARC / DILR / Quants)
- Quick stats — Streak 🔥 · Due Today 📚 · Mastered ✨

### 📚 Subjects Tab
- Full **Section → Topic → Subtopic** hierarchy
- Add unlimited custom sections, topics, and subtopics
- Swipe left to delete · Tap ✏️ to edit names
- **Mark as Learned** to start the revision clock
- 📝 Formula notes per subtopic
- Spaced repetition stage badge on every subtopic
- Shows next revision date countdown

### 🔄 Revise Tab
- Today's complete revision queue sorted by urgency
- Visual 5-stage progress bar per subtopic
- Overdue indicator with days count
- Expand to view formula notes inline
- **"Revised! ✓"** button advances to next stage automatically
- Session progress bar with completion celebration 🎉

### 📊 Stats Tab
- **Mastery ring chart** — overall % mastered
- Per-section mastery rings (VARC / DILR / Quants)
- **35-day activity heatmap** (like GitHub contributions)
- Current streak & best streak counters
- Total revisions count
- Stage distribution breakdown chart

### 🤖 AI Coach Tab
- Powered by **Groq + Llama 3.3 70B** (ultra-fast responses)
- Knows your full personal syllabus as context
- Quick-tap suggestion chips for common doubts
- Full chat history per session
- Great for: formula explanations, strategy tips, concept clearing

---

## 🗂️ Default Syllabus (CAT / GMAT Preset)

| Section | Topics | Subtopics |
|---------|--------|-----------|
| 📖 VARC | Reading Comprehension, Verbal Ability | RC Inference, Tone, Para Jumbles, Para Summary, OOC, TITA |
| 🔢 DILR | Data Interpretation, Logical Reasoning | Tables, Bar Charts, Pie Charts, Seating, Blood Relations, Puzzles, Venn Diagrams |
| 🧮 Quants | Arithmetic, Algebra, Geometry, Modern Math | Profit & Loss, Percentages, Equations, Progressions, Triangles, P&C, Probability + 15 more |

> You can also start from scratch and build a 100% custom syllabus for **any exam** — UPSC, JEE, NEET, CA, CFA, GATE, etc.

---

## 🚀 Getting Started

### Option 1 — Netlify (Recommended, 2 minutes)
1. Download `index.html` from this repo
2. Go to [netlify.com](https://netlify.com) → Sign up free
3. Drag & drop `index.html` onto the Netlify dashboard
4. Get your live URL (e.g. `revedge-yourname.netlify.app`)
5. Open on iPhone Safari → **Share → Add to Home Screen** 📱

### Option 2 — GitHub Pages (5 minutes)
1. Fork this repository
2. Go to **Settings → Pages**
3. Source: Deploy from branch → `main` → `/ (root)`
4. Your app will be live at `https://yourusername.github.io/RevEdge`

### Option 3 — Local
Just open `index.html` in any browser. No server needed.

---

## 📲 iPhone Setup (Add to Home Screen)

1. Open your deployed URL in **Safari** (must be Safari, not Chrome)
2. Tap the **Share button** (box with arrow at bottom)
3. Scroll down → tap **"Add to Home Screen"**
4. Name it **RevEdge** → tap **Add**
5. It now appears on your home screen like a native app ✅

> All your data is saved in the browser's `localStorage` — it persists across sessions on the same device.

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Framework | React 18 (via CDN, no build step) |
| Styling | Pure inline CSS with CSS-in-JS |
| AI Coach | Groq API · Llama 3.3 70B Versatile |
| Storage | Browser `localStorage` |
| Fonts | Sora (Google Fonts) |
| Build | Zero — single `.html` file |

---

## 🔑 API Keys

The app uses **Groq** for the AI Coach tab.

- Get your free key at [console.groq.com](https://console.groq.com)
- Groq free tier: **14,400 requests/day** — more than enough
- Replace the key in `index.html` → search for `GROQ_KEY=`

```js
const GROQ_KEY = "gsk_your_key_here";
```

---

## 📁 Project Structure

```
RevEdge/
│
├── index.html          ← The entire app (single file)
└── README.md           ← This file
```

---

## 🗺️ Roadmap

- [ ] Cloud sync (Firebase / Supabase)
- [ ] Image upload for formula sheets
- [ ] Push notifications for daily 7 AM reminder
- [ ] PDF formula sheet generator
- [ ] Offline PWA support
- [ ] Multiple device sync
- [ ] Custom spaced repetition intervals
- [ ] Mock test integration
- [ ] Leaderboard with friends

---

## 🙌 Built For

Any student preparing for a competitive exam who wants to stop forgetting what they study and start building lasting mastery — one revision at a time.

> *"The secret of getting ahead is getting started."*

---

## 📄 License

MIT License — free to use, modify, and share.

---

<div align="center">
  <strong>Made with ❤️ by Dhaval Patel, for every exam aspirant grinding it out</strong><br/>
  <sub>RevEdge — Your Revision. Your Edge.</sub>
</div>
