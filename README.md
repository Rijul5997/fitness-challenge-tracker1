# ⚡ FitPulse - Fitness Challenge Tracker

FitPulse is a modern, responsive, and interactive web application designed to help users log workouts, enroll in fitness challenge plans, monitor milestone progress, and manage personal fitness goals. Built completely with HTML5, Tailwind CSS, and Vanilla JavaScript, it requires no external backend servers and persists user sessions and data directly in the browser via `localStorage`.

---

## 🚀 Key Features

* **🔐 User Authentication & Role-Based Access Control (RBAC)**
  * Secure Sign-In and Registration workflows with input validation.
  * Distinct interfaces and permissions for **Participants (`user`)** and **Staff/Administrators (`admin`)**.
  * One-click instant demo login buttons for quick testing and evaluation.
* **📊 Interactive Analytics Dashboard**
  * Real-time tracking of total workouts logged, total calories burned against daily targets, active challenge count, and overall milestone completion percentage.
  * Chronological feed of recent workout sessions and active challenge progress bars.
* **🏋️ Workout Activity Management (CRUD)**
  * Log, edit, and delete daily workout sessions (Running, Strength, Yoga, HIIT, Cycling, Swimming).
  * Live search bar and category filters to quickly locate past sessions.
* **🏆 Fitness Challenge Plans & Milestone Tracking**
  * Browse available global fitness challenges by category (Cardio, Strength, Endurance).
  * Enroll in plans and interactively check off weekly milestones to dynamically update completion progress.
* **👤 Profile & Goal Customization**
  * Update personal display name, fitness proficiency level, daily calorie burn goals, and weekly workout frequency targets.
* **🛡️ Staff / Admin Control Panel**
  * Platform-wide metrics overview (total registered users, active challenges, total community workouts).
  * Directory table of all registered participants and their fitness profiles.
  * Ability to create and publish new global fitness challenges for all users.

---

## 🛠️ Technologies Used

* **HTML5:** Semantic structure and accessible form elements.
* **Tailwind CSS (via CDN):** Responsive dark-mode UI, glassmorphism panels, custom neon accents, and mobile-friendly navigation.
* **Vanilla JavaScript (ES6+):** State management, DOM manipulation, filtering logic, and persistent storage using the Web Storage API (`localStorage`).
* **FontAwesome & Google Fonts:** Crisp iconography and clean `Inter` typography.

---

## ⚡ Quick Start & Demo Credentials

Because this application is built purely with frontend web technologies, no installation, build step, or backend server is required.

### Running Locally
1. Clone or download this repository:
   ```bash
   git clone https://github.com/your-username/fitpulse-tracker.git
   ```
2. Open `fitness_tracker.html` (or `index.html`) directly in any modern web browser (Chrome, Edge, Firefox, Safari).

### Instant Demo Accounts
You can log in immediately using the pre-configured accounts on the login screen:

| Role | Email | Password | Capabilities |
| :--- | :--- | :--- | :--- |
| **Participant / User** | `user@fitness.com` | `password` | Log workouts, join challenges, update milestones, edit profile |
| **Staff / Admin** | `admin@fitness.com` | `admin123` | All user features + Admin Panel access & global challenge creation |

---

## 🌐 Deployment (GitHub Pages)

To host this project live for free using GitHub Pages:
1. Rename `fitness_tracker.html` to `index.html` in your repository root.
2. Go to your repository **Settings** > **Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**, choose your `main` branch and `/ (root)` folder, and click **Save**.
4. Your live link will be published at `https://<your-username>.github.io/<repository-name>/`.

---

## 📂 Project Structure

```text
├── index.html          # Complete single-file application (HTML, Tailwind CSS, JS)
└── README.md           # Project documentation and setup instructions
```

---

## 📝 License & Academic Submission Note
Developed as a functional software solution demonstrating clean UI/UX design, client-side state persistence, and role-based application architecture using core web standards.
