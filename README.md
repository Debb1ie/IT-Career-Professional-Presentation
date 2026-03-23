# IT Career Insights — Interactive Presentation

> An interactive, browser-based presentation on industry insights and career guidance for aspiring IT professionals. Built as a single HTML file with zero dependencies.

---

## Overview

This is a fully self-contained presentation tool designed for live sessions, classroom use, or self-study. It covers 31 topic slides across the IT career journey — from joining communities as a student, to building a long-term career in tech — followed by a visual dashboard summary and a closing thank you screen.

**Total slides: 33**
- Slides 1–31: Topic content with interactive flashcards
- Slide 32: Visual dashboard summary
- Slide 33: Thank You & contact

---

## Features

### Presentation
- 33 slides with smooth animated transitions
- Slide progress bar at the top
- Dark mode and light mode toggle (top right)
- Animated starfield background with shooting stars

### Navigation
- **Arrow buttons** at the bottom bar (prev / next / first / last)
- **Hover arrows** — hover the left or right edge of the screen to reveal clickable navigation arrows
- **Keyboard** — `←` `→` arrow keys, `Space` to advance, `Home` / `End` to jump to first or last
- **Swipe** — swipe left/right on touch devices
- **Dot indicators** — click any dot at the bottom to jump to that slide
- **Slide search** — type a slide number in the bottom-left input and press `Enter` to jump directly

### Flashcards
- Each bullet point is a flippable flashcard
- **Front** shows the topic title
- **Back** reveals a detailed explanation with a Lucide-style SVG icon
- Click or tap any card to flip it; cards auto-reset when navigating away

### Dashboard (Slide 32)
- Animated count-up for slides completed and total flashcards
- Bar chart: top 8 sections ranked by flashcard count
- Donut chart: topic category breakdown across 5 categories
- Learning path timeline: 6 key milestones from student to first job

---

## How to Use

1. Open `presentation.html` in any modern browser — no server or install needed
2. Use arrow keys or hover the screen edges to navigate
3. Click any flashcard to flip it and read the detail
4. Type a slide number in the bottom-left box and press `Enter` to jump
5. Toggle between dark and light mode using the switch in the top-right corner

---

## Slide Topics

| # | Topic |
|---|-------|
| 1 | Welcome (Title) |
| 2 | My Journey as a Student Leader in Tech |
| 3 | Why Tech Communities Matter |
| 4 | The Reality of the IT Industry |
| 5 | The Gap Between School and Industry |
| 6 | Career Paths in the IT Industry |
| 7 | What Companies Are Actually Looking For |
| 8 | Why Projects Matter More Than Grades |
| 9 | The Importance of Building a Portfolio Early |
| 10 | How Students Can Stand Out in Tech |
| 11 | Learning Beyond the Classroom |
| 12 | The Role of Networking in Tech Careers |
| 13 | Volunteering in Tech Events |
| 14 | Leadership Opportunities in Tech Communities |
| 15 | The Power of Collaboration |
| 16 | Mistakes Students Commonly Make |
| 17 | Choosing Your Specialization |
| 18 | The Importance of Soft Skills in Tech |
| 19 | Preparing for Internships and Jobs |
| 20 | The Future of the Tech Industry |
| 21 | Message to Aspiring IT Professionals |
| 22 | How Hackathons Help You Grow Faster |
| 23 | What I Learned from Organizing Tech Events |
| 24 | How Students Can Build Confidence in Tech |
| 25 | The Importance of Asking Questions |
| 26 | How to Start Even If You Feel Behind |
| 27 | The Role of Mentorship in Tech Careers |
| 28 | Real Challenges Students Face in Learning Tech |
| 29 | How Communities Help Solve These Challenges |
| 30 | Building a Long-Term Career in Technology |
| 31 | Final Reflection: Your Next Step in Tech |
| 32 | Dashboard — Visual Summary |
| 33 | Thank You |

---

## Tech Stack

- **Pure HTML / CSS / JavaScript** — zero frameworks, zero npm, zero build step
- **Google Fonts** — Playfair Display, DM Sans, Space Mono (loaded via CDN)
- **Canvas API** — starfield and shooting star animation
- **CSS custom properties** — full dark/light theming
- **CSS 3D transforms** — flashcard flip animation (`rotateY`)
- **MutationObserver** — triggers dashboard bar and counter animations on slide entry

---

## Browser Support

Works in all modern browsers: Chrome, Firefox, Safari, Edge. Requires JavaScript enabled.

---

## Contact

**Presenter:** P. Manucom  
**Email:** pmanucom@devcon.ph  
**Organization:** DEVCON Manila

---

*Part of DEVCON Manila · Keep Building*
