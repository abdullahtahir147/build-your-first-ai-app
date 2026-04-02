# Prompt Templates for ChatGPT

Two prompts. Run them in order. Replace everything in **[BRACKETS]** with your own idea.

---

## Prompt 1 — Describe your idea, get a PRD

Paste this into ChatGPT first.

```
I want to build a simple web app. Here's my idea:

**App name:** [e.g. "Habit Tracker"]
**What it does:** [e.g. "Lets me check off up to 5 daily habits and shows a weekly streak"]
**Who it's for:** [e.g. "Just me, for personal use"]
**Key features I want:** [e.g. "Add/remove habits, check them off each day, see a streak counter"]
**Design (optional):** [e.g. "Minimal, dark mode, greens and greys"]

I'm going to build this using free Claude AI. The first version will be a single HTML file — all the HTML, CSS, and JavaScript in one file, no backend, no database, no API keys.

Please write me a Product Requirements Document (PRD) that includes:
- A one-sentence description of the app
- Who it's for
- A breakdown of versions: MVP (the absolute minimum that works), V1 (nice to have additions), V2 (future ideas)
- Any design notes

Keep each version focused and realistic for a single HTML file.
```

---

**Read the PRD.** Check the MVP scope feels right — not too big, not too small. You can ask ChatGPT to adjust it before moving on.

---

## Prompt 2 — Get the Claude prompt

Once you're happy with the PRD, paste this into the **same ChatGPT conversation**.

```
Great. Now write me a prompt I can paste directly into Claude (free plan) to build the MVP as a single HTML file.

The prompt must:
- Be short and direct — free Claude has limited tokens, so no waffle
- Tell Claude to put all HTML, CSS, and JavaScript in one file
- Use localStorage to save any data
- Require no API keys and no internet connection
- Work by simply double-clicking the file in a browser
- Match the design vibe from the PRD

Output the Claude prompt only — no explanation, no intro text.
```

---

**Copy the prompt ChatGPT gives you → open Claude → paste it in → your app is built.**

---

## Example Ideas

- **Workout timer** — set rounds, rest, and exercises. Beeps when time's up.
- **Flashcard maker** — create cards, flip them, mark what you know.
- **Mood tracker** — log your mood daily, see a weekly chart.
- **Packing list** — check off trip items, save lists for reuse.
- **Pomodoro timer** — 25 min work / 5 min break with a counter.
- **Book tracker** — log books you've read, rate them, add notes.
- **Bill splitter** — enter a total, add people, split evenly or custom.
- **Daily journal** — write an entry each day, browse past ones.
- **Recipe scaler** — paste a recipe, change servings, all amounts update.
- **Language flashcards** — English ↔ another language, with spaced repetition.
