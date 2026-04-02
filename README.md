# Build Your First AI App 🚀

**A hands-on workshop by Abdullah — from zero to a working app on your laptop in 75 minutes.**

No coding experience needed. No paid subscriptions. Just a laptop and curiosity.

---

## What you'll walk away with

- A working app running locally on your laptop
- A product requirements document (PRD) you wrote
- The prompting skill to build your next 10 ideas

---

## Before the workshop

### 1. Get your accounts ready (5 min)
- **ChatGPT**: Sign up free at [chatgpt.com](https://chatgpt.com)
- **Claude**: Sign up free at [claude.ai](https://claude.ai)

### 2. Download this repo
**Have Git?**
```bash
git clone https://github.com/abdullahtahir147/build-your-first-ai-app.git
```

**No Git?** Click the green **Code** button → **Download ZIP** → Unzip it on your Desktop

### 3. Test it works
Open `examples/` → double-click `expense-splitter.html` → it should open and work in your browser.

---

## Workshop Flow

**Step 1 → Describe your idea (ChatGPT — Prompt 1)**
Open ChatGPT. Copy **Prompt 1** from [`prompt-template.md`](prompt-template.md). Fill in your app idea, who it's for, and what you want it to do. ChatGPT will give you back a PRD with an MVP, V1, and V2 breakdown. Read it — tweak it if needed.

**Step 2 → Get your Claude prompt (ChatGPT — Prompt 2)**
Happy with the PRD? Copy **Prompt 2** from [`prompt-template.md`](prompt-template.md) and paste it into the same ChatGPT conversation. It will output a ready-to-use Claude prompt, optimised for the free plan.

**Step 3 → Build (Claude)**
Open Claude. Paste the prompt you just got. Claude generates your app as an artifact. Click the **three dots** on the artifact → **Download** → save as `my-app.html`.

**Step 4 → Run (Your Laptop)**
Double-click the HTML file. Your app opens in your browser. Locally. Offline. Yours.

**Step 5 → Iterate**
Want changes? Tell Claude what to fix. Download again. Open the new file.

---

## ⭐ Bonus — Put Your App Online

These steps are optional — your app already works without them. But if you want a real live URL to share with people, here's how.

**Bonus Step 1 → Create a GitHub account**
Sign up free at [github.com](https://github.com). Then create a new repository (click **+** → **New repository**). Give it a name, set it to Public, and hit **Create repository**.

**Bonus Step 2 → Upload your HTML file**
On your new repo page, click **Add file → Upload files**. Drag your `my-app.html` file in, **rename it `index.html`**, then click **Commit changes**.

**Bonus Step 3 → Enable GitHub Pages**
Go to your repo → **Settings → Pages**. Under *Source*, select **Deploy from a branch**, pick **main** and **/ (root)**, then hit **Save**. Wait about a minute — your app will be live at `https://yourusername.github.io/your-repo-name`.

---

## Folder Structure

```
build-your-first-ai-app/
├── README.md                       ← You are here
├── prompt-template.md              ← Copy this into ChatGPT
├── examples/
│   ├── expense-splitter.html       ← Split bills with friends
│   ├── job-finder.html             ← Track and filter job listings
│   └── news-dashboard.html         ← Personalised news feed
└── v1-demo/
    └── job-dash-live.html          ← Pulls LIVE jobs from HackerNews (needs internet)
```

---

## What's Next

- **Add features** — go back to Claude and ask for more
- **Build another app** — same process, new idea
- **Need a backend?** → check out [Lovable](https://lovable.dev), Firebase Studio, or Replit
- **Want to understand the code?** → ask Claude: *"Explain this HTML file to me line by line"*

---

**Built with ❤️ for Big Brain Bigger Laughs presents: Build Your First AI App**
