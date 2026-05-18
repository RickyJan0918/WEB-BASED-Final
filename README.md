# GradeVault Dashboard

GradeVault is a sleek, intuitive, and efficient academic grade and credit management system. Designed with a user-friendly two-tab interface, it allows students to easily log their GPAs, track earned credits, and monitor their progress toward graduation requirements in real time.

## Features

- **Course Selection & Entry (Tab 1)**:
  - Quick course selection via a dropdown menu that automatically displays the course's credit weight.
  - Strict GPA input validation supporting a `0.0 ~ 4.3` scale to ensure data accuracy.
  - Instant data commitment with the "Add Course Grade" action.
- **Grade & Credit Inquiry (Tab 2)**:
  - **Real-time GPA Calculation**: Automatically computes the cumulative weighted GPA of all added courses.
  - **Credit Progress Tracker**: Visually displays earned credits against the graduation threshold (e.g., `14 / 128` credits).
  - **Status Auto-Detection**: System automatically determines and highlights whether a course is **Passed** or **Failed** based on the entered grade.

---

### 1. Course Selection (Tab 1)
The interface where users select their enrolled courses and input their respective GPAs.

### 2. Grade Inquiry (Tab 2)
The dashboard showing the detailed grade overview table, cumulative GPA, and graduation credit progress.

---

## Tech Stack

*(Feel free to update this section based on your actual tech stack)*
- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **UI Framework**: CSS
- **State Management**: LocalStorage

---

## Getting Started

### Clone the Repository
```bash
git clone [https://github.com/RickyJan0918/GradeVault-Dashboard.git] cd GradeVault-Dashboard
