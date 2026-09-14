# ⚡ Advance Focus Timer
**The most advanced, yet beautifully simple focus timer and analytics platform.**

[![Live Demo](https://img.shields.io/badge/Live_Demo-Click_Here-00ffff?style=for-the-badge)](https://focus-tracker-pro.web.app/)

> **Note:** This repository serves as a portfolio showcase. The proprietary source code is kept in a separate, private repository to protect the intellectual property.

![Main Dashboard Screenshot](<img width="1919" height="1079" alt="Screenshot 2026-09-14 102229" src="https://github.com/user-attachments/assets/a484cea4-c68e-4fd2-a1bc-b05e74dffd95" />
)

## 📖 The Story: Why I Built This
I built Focus Tracker Pro out of frustration. I could never find a focus tracker that did exactly what I needed—most were either too basic, filled with clutter, or lacked meaningful data insights. 

I wanted something different: a tool that was incredibly clean and simple on the surface, but powered by an advanced data engine underneath. I wanted an application that didn't just count down time, but actually helped users analyze their performance, stay motivated during tough days, and maintain absolute control over their digital footprint.

## ✨ Core Features & Architecture

### 📊 Advanced Performance Analytics
The app doesn't just track time; it analyzes behavior.
* **Daily & Weekly Graphs:** See your exact performance metrics mapped out beautifully day by day.
* **The Compare Graph:** A dedicated engine that compares your current week to your last week. It instantly tells you if you are falling behind or pulling ahead of your previous baseline.
* **Macro Trends (Months & Years):** Zoom out to yearly views to easily spot the days you dropped productivity, burned out, or just didn't feel like working.

![Analytics Screenshot](<img width="1919" height="1079" alt="Screenshot 2026-09-13 233616" src="https://github.com/user-attachments/assets/0342bccf-90e4-4287-a1fc-270b3008f626" />
)

### 🗓️ Heatmaps, Goals & Streaks
Visualizing consistency is the key to building habits.
* **Calendar Heatmap:** A GitHub-style contribution grid that visually proves exactly how far you’ve come. 
* **Daily Goals & Streak Logic:** Set a target daily hour goal. The custom streak engine calculates your consistency, giving you immediate feedback on your momentum.

### 🎯 Task Handler & Motivation Engine
* **Prioritized Task Handler:** A clean, distraction-free module to pin down your most critical tasks for the day or the month.
* **The Motivation Pill:** A built-in feature designed to deliver exactly what users need when the work gets tough and motivation fades.

### 🌍 The Live Global Network (Custom 3D Engine)
To gamify productivity, I engineered a custom 3D globe using **D3.js Orthographic Projections**.
* **Global Leaderboard:** Compares your daily focus time against an active global network.
* **Data Trajectories:** Live focus sessions are visualized as glowing green data packets traveling across great-circle arcs between global coordinates. 
* *Technical Highlight:* Built custom spherical math to handle horizon clipping, allowing data arcs to flawlessly wrap around the silhouette edges of the globe into empty space before realistically disappearing behind the earth's mass.

![Globe GIF](<img width="720" height="406" alt="0914 (1)" src="https://github.com/user-attachments/assets/42c8f177-97b8-41c2-8090-f3dc4b2fdb3c" />
)

### 🔒 Absolute Data Privacy (The 3-Tap Wipe)
User trust is paramount. Everything related to a user's account and history is stored securely, but more importantly, **it can be destroyed instantly**.
* Users are always just 2-3 taps away from completely wiping their existence from the database. 
* It is a permanent, non-reversible deletion directly from the server. No hidden retention, no jumping through hoops.

## 🛠️ Tech Stack
* **Frontend:** React 18, TypeScript, Vite
* **Styling:** Tailwind CSS, Glassmorphism CSS Masking/Filters
* **Data Visualization:** D3.js (Geo, Interpolate, Path), Recharts
* **Backend & Auth:** Firebase Auth, Cloud Firestore (secured via strict RBAC rules)

---
*Designed and Engineered by Anwar Sheikh*
