# 🎓 NRI-NIAT College Student Dashboard

A **modern, professional, and fully responsive** College Student Dashboard built with **pure HTML5 and CSS3** — no JavaScript, no frameworks.

---

## 👤 Student Details

| Field       | Value                            |
|-------------|----------------------------------|
| Name        | Sreegeshnuram                    |
| University  | NRI – NIAT, Guntur (Autonomous)  |
| Course      | B.Tech CSE                       |
| Year        | 1st Year – Semester 1            |
| Batch       | 2024 – 2028                      |

---

## 📁 Project Structure

```
college-student-dashboard/
├── index.html      ← Main dashboard page (all sections)
├── style.css       ← All styles (no inline CSS)
├── README.md       ← This file
└── images/         ← Place profile images here (optional)
```

---

## 🚀 How to Run

### Option 1 – Open directly in browser
1. Download or clone the project folder.
2. Double-click **`index.html`** to open it in any modern browser (Chrome, Firefox, Edge, Brave).
3. No server or installation needed!

### Option 2 – VS Code Live Server
1. Install [VS Code](https://code.visualstudio.com/).
2. Install the **Live Server** extension.
3. Right-click `index.html` → **"Open with Live Server"**.

### Option 3 – Python local server
```bash
# Python 3
python -m http.server 8000
# Open: http://localhost:8000
```

---

## 🌐 GitHub Push Guide (Assignment Submission)

```bash
# Step 1: Initialize git inside the project folder
cd "college-student-dashboard"
git init

# Step 2: Add all files
git add .

# Step 3: First commit
git commit -m "🎓 Initial commit: NRI-NIAT Student Dashboard for Sreegeshnuram"

# Step 4: Create a repo on GitHub (https://github.com/new)
# Then link it:
git remote add origin https://github.com/YOUR-USERNAME/college-student-dashboard.git

# Step 5: Push to GitHub
git branch -M main
git push -u origin main
```

> **Tip:** Replace `YOUR-USERNAME` with your actual GitHub username.

---

## 📋 Features

### ✅ Sections
- 🏠 **Dashboard** – Welcome banner + 4 stats cards (Attendance, Marks, Subjects, Semester)
- 👤 **Profile** – Full student profile with avatar, roll number, email, branch
- 📅 **Attendance** – CSS circular progress ring (82%) + subject-wise bar charts + monthly summary table
- 📊 **Marks** – Subject-wise score cards with progress bars and grades + internal assessment table + CGPA
- 🕐 **Timetable** – Complete weekly timetable (Mon–Sat, all periods, color-coded by subject)
- 📚 **Subjects** – All 6 Semester-1 subjects with credits and faculty names
- 🔔 **Notifications** – Assignment reminders with urgency tags (Urgent / Upcoming / Done)
- 📢 **Announcements** – College notices (Annual Day, Exam Schedule, Hackathon, Sports Week, Guest Lecture)

### ✅ Design
- 🎨 **Color scheme:** Navy Blue + Purple + White
- 📱 **Responsive:** Desktop → Tablet → Mobile (CSS Grid + Flexbox)
- 🌙 CSS-only sidebar toggle (hamburger menu on mobile)
- ✨ Hover animations on cards, nav links, and announcement rows
- 🔄 CSS `@keyframes` floating animation on welcome banner
- 🔵 CSS `conic-gradient` circular progress (pure CSS, no SVG)
- 🔡 Google Fonts: **Inter** (clean, modern, beginner-friendly)
- 💬 Fully commented code (suitable for assignment submission)

---

## 🛠️ Technologies Used

| Technology | Usage |
|------------|-------|
| HTML5      | Semantic page structure, sections, tables |
| CSS3       | Layouts (Grid, Flexbox), animations, responsive design |
| CSS Variables | Centralized color and spacing management |
| Google Fonts | Inter typeface (loaded via CDN) |

> ❌ No JavaScript · ❌ No React · ❌ No Bootstrap · ❌ No Backend

---

## 📸 Sections Preview

| Section | Description |
|---------|-------------|
| Sidebar | Fixed navigation with profile mini-card |
| Welcome Banner | Gradient hero with floating emoji animation |
| Stats Cards | 4 animated cards with colored top borders |
| Attendance | Circular ring (CSS conic-gradient) + horizontal bars |
| Marks | Score cards with grade badges + summary table |
| Timetable | Full color-coded weekly schedule |
| Subjects | Cards with faculty info + credits summary row |
| Notifications | Urgency-tagged reminder cards (2-column layout) |
| Announcements | Dated announcement feed with category tags |
| Footer | University info + student name + copyright |

---

## 👨‍💻 Author

**Sreegeshnuram**  
B.Tech CSE · 1st Year · NRI-NIAT, Guntur  
Roll No: 24A91A0501  
Academic Year: 2024–2028

---

## 📄 License

This project is submitted as an academic assignment for **NRI – NIAT (Autonomous), Guntur**.  
Free to use for educational and personal portfolio purposes.
