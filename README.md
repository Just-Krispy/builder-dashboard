# Builder Command Center

**Your daily accountability dashboard for shipping fast.**

---

## Features

✅ **Today's Focus** — Track daily tasks with checkboxes  
📅 **This Week's Goals** — Manage weekly objectives side-by-side  
🚀 **Active Projects** — Visual progress bars for all projects  
💡 **Daily Idea Generator** — Get creative project/skill/learning suggestions  
🔥 **Streak Tracker** — Compact header display of ship streaks  
🌙 **Dark Mode** — Toggle with persistent preference  
💾 **Auto-Save** — Everything persists via localStorage

---

## How to Use

1. **Open `index.html`** in your browser
2. **Add tasks** for today's focus (left card)
3. **Set weekly goals** for the week (right card)
4. **Click "Log Ship Day"** to maintain your streak (header shows stats)
5. **Generate daily ideas** for creative inspiration (projects/skills/learning)
6. **Toggle dark mode** for your preferred viewing experience

---

## Keyboard Shortcuts

- `Enter` in task input → Add task
- `Enter` in goal input → Add goal

---

## Data Persistence

All data saved automatically to browser's localStorage:
- Tasks
- Projects
- Daily wins
- Weekly goals
- Streak stats

**No backend required.** Works 100% offline.

---

## Deployment Options

### Option 1: Local Use
Just open `index.html` in your browser.

### Option 2: GitHub Pages
1. Push to GitHub repo
2. Enable GitHub Pages
3. Access from anywhere

### Option 3: Netlify/Vercel
Drag `index.html` into Netlify Drop for instant hosting.

---

## Customization

Edit the CSS variables at top of HTML:
```css
:root {
    --primary: #2d5a1b;        /* Main color */
    --accent: #8bc34a;          /* Accent color */
    --bg: #f4f7f0;              /* Background */
}
```

Edit default projects in JavaScript:
```javascript
projects: [
    { name: "Your Project", progress: 50, status: "ACTIVE" }
]
```

---

## Export/Backup

**Backup your data:**
1. Open browser console (F12)
2. Run: `console.log(localStorage.getItem('builderDashboard'))`
3. Copy the output and save to file

**Restore data:**
1. Open browser console
2. Run: `localStorage.setItem('builderDashboard', 'PASTE_DATA_HERE')`
3. Refresh page

---

## Why This Works

**Psychology:**
- Visual progress bars = motivation boost
- Daily idea generator = combat creative blocks
- Streak tracking = gamification (don't break the chain!)
- Side-by-side focus & goals = at-a-glance priorities
- Dark mode = accessibility & eye comfort

**Built on Ship-Fast Components philosophy:**
- Vanilla HTML/CSS/JS (no framework)
- Zero dependencies
- Works everywhere
- Copy-paste ready
- Accessible design (WCAG compliant)

---

## Ship Fast. Ship Often. No Excuses. 🚀
