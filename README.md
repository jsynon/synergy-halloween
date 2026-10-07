# 🎃 Neverwinter Halloween Fashion Spectacular

> A responsive, dark-fantasy landing page and automated countdown for the **Wanted Alliance Costume Contest**, presented by **Synergy**.

Live finale streaming on [Twitch](https://www.twitch.tv/thenolanian) — **Saturday, October 24th at 8:00 PM Eastern**.

---

## ✨ Key Features

* ⏳ **Real-Time Countdown:** Dynamic timer counting down to the live finale stream, with automatic phase switching when the stream goes live or finishes.
* 🌍 **Local Time Zone Auto-Conversion:** Uses native browser localization (`Intl.DateTimeFormat`) to translate Eastern Time into the exact local time zone of whoever opens the page.
* 🏆 **Prize & Event Showcase:** Clean visual cards highlighting the **50 Million Astral Diamond** prize pool, the exclusive **Frightfully Fashionable** title, and viewer choice giveaways.
* 📅 **Automated Event Timeline:** A 3-step sequence covering Sign-ups, Qualifying Round (Oct 17), and the Live Finale (Oct 24). Completed steps automatically visually dim once their date passes.
* 🚀 **Zero Maintenance:** Built as a standalone vanilla HTML/CSS/JS file. No external dependencies, build tools, or server-side scripts required.

---

## 🛠️ Tech Stack

* **HTML5** (Semantic structure, accessibility markup)
* **CSS3** (Custom properties, flexbox/grid layout, responsive design)
* **Vanilla JavaScript** (Countdown logic, local time formatting, step-status tracking)
* **Google Fonts** (*Cinzel*, *Cinzel Decorative*, *Cormorant Garamond*, *Cormorant SC*)

---

## 🚀 Quick Start / Deployment

Since this project consists of a single static HTML document, it requires zero build steps and can be hosted instantly.

### Local Preview
1. Clone or download this repository.
2. Open `index.html` directly in any modern Web Browser.

### Hosting on GitHub Pages
1. Go to your repository settings on GitHub.
2. Navigate to **Pages** in the side menu.
3. Set the source branch to `main` (or `master`) and folder to `/ (root)`.
4. Save — your page will be live in under a minute!

---

## ⚙️ Configuration & Customization

All event dates and stream links are centralized at the bottom of `index.html` inside the `<script>` block:

```javascript
// Finale Date & Stream Window
var target = new Date("2026-10-24T20:00:00-04:00").getTime();

// Sign-up Deadline (End of Oct 10 Eastern)
var signupClose = new Date("2026-10-11T00:00:00-04:00").getTime();
