# Smart Study Planner — Interactive Study Scheduling & Analytics Dashboard

An interactive, responsive single-page web application designed to help students organize academic tasks, prioritize exam preparation, track daily study progress with **Chart.js** data visualizations, and receive browser notifications.

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Chart.js](https://img.shields.io/badge/Chart.js-Analytics-FF6384?style=flat&logo=chartdotjs&logoColor=white)](https://www.chartjs.org/)

---

## 🌟 Implemented Features

- **Dynamic Study Task Planner**:
  - Add, edit, and categorize study sessions by subject, deadline, estimated duration, and priority.
  - Priority ranking algorithm dynamically highlighting urgent assignments and upcoming exams.
- **Visual Productivity Analytics**:
  - Embedded **Chart.js** line chart visualizing daily completed study hours vs. targets over time.
  - Real-time productivity metrics calculating completion percentage and active study streaks.
- **Browser Push Notifications**:
  - Desktop reminder permission prompts (`Notification.requestPermission()`) alerting students of pending study blocks.
- **Data Persistence & Portability**:
  - All tasks and user states persist locally in browser `localStorage` without external server dependencies.
  - Built-in **JSON Export & Import** allowing students to back up schedules or transfer them across devices.
- **Client Authentication**:
  - Client-side signup and signin workflow (`auth.html`) managing personalized user profiles.

---

## 📁 Repository Structure

```text
Smart-Study-Planner/
├── index.html       # Primary application layout, task manager, and Chart.js analytics
├── auth.html        # Client-side user authentication and account creation interface
├── .gitignore       # Excludes editor files and OS temporary artifacts
└── README.md        # Project documentation and local running guide
```

---

## 🛠️ Tech Stack

- **Markup & Layout**: Semantic HTML5 with responsive flexbox and CSS grid styling
- **Styling**: Pure CSS3 with modern gradient themes and dark/light contrast cards
- **Logic & Storage**: Vanilla JavaScript (ES6+), DOM APIs, `localStorage`
- **Data Visualization**: [Chart.js](https://www.chartjs.org/) via CDN

---

## 🚀 Running the Project Locally

Because the project is entirely client-side with zero external build dependencies, it can be executed immediately:

### Option A: Open Directly in Browser
Simply double-click `index.html` or open it with any modern web browser (Chrome, Edge, Firefox, Safari).

### Option B: Local Static Server (Recommended)
```bash
# Clone the repository
git clone https://github.com/sujitha611/Smart-Study-Planner.git
cd Smart-Study-Planner

# Start a lightweight Python HTTP server
python -m http.server 3000
```
Open **`http://localhost:3000`** in your browser.

---

## 🧪 Testing & Verification Status

- **HTML / DOM Structure**: Verified; links between `auth.html` and `index.html` verified.
- **CDN Scripts**: Chart.js loaded via JSDelivr CDN.
- **Automated Test Suite**: No automated testing framework present in this client-side project.

---

## 👤 Author
**Battu Jaya Sujitha**  
[GitHub Profile](https://github.com/sujitha611) | [LinkedIn](https://www.linkedin.com/in/jaya-sujitha-576b7a290/)
