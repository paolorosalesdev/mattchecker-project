# MattChecker: Exam and Quiz Checker System

A web-based quiz and exam system designed for teachers to create, manage, and automatically evaluate assessments including multiple-choice, true-or-false, short-answer, and essay-type questions using AI-based grading.

**Frontend:** HTML5, CSS3, JavaScript  
**Backend:** PHP  
**Database:** MySQL (phpMyAdmin)  
**Tools:** XAMPP, Atom  

## 📌 Status
This project was developed as a capstone system and may contain incomplete or imperfect features. It is continuously being improved as part of ongoing learning and development.

## 🚀 Project Overview
MattChecker is a centralized web-based examination system designed to automate quiz and exam creation, checking, and evaluation. It integrates AI-based logic (NLP-based similarity checking) to assist in grading open-ended responses and reduce manual workload for teachers.

### The Problem It Solves:
* **Manual Grading Load:** Reduces time spent checking exams manually.
* **Inconsistent Evaluation:** Provides more standardized scoring for open-ended answers.
* **Slow Feedback:** Speeds up result generation and performance reporting.
* **Paper-Based Exams:** Replaces traditional offline quiz systems with a digital platform.

## ✨ Key Features

### For Teachers
* **Quiz Creation:** Create multiple-choice, true-or-false, short-answer, and essay-type questions
* **Exam Management:** Edit, update, and delete quizzes and exams
* **Automated Checking:** Automatic grading for objective-type questions
* **AI Evaluation:** NLP-based checking for short-answer and essay responses
* **Performance Reports:** View student scores and analytics

### For Students
* **Online Exams:** Take quizzes and exams through a web interface
* **Instant Results:** Receive immediate or faster evaluation feedback (depending on settings)
* **Performance Tracking:** View scores and progress

## 🛠️ Technical Implementation (CRUD & Logic)
* **Frontend:** Responsive UI built with HTML5, CSS3, and JavaScript
* **Backend:** Server-side logic handled via PHP
* **Database:** Structured MySQL database managing users, exams, questions, and results
* **Core Logic:** Implements automated grading system and NLP-based answer evaluation

## ⚙️ Setup & Installation

⚠️ This repository is distributed as a ZIP file. Please follow the steps below to run the system locally.

1. **Download the repository**
   - Go to the GitHub repository
   - Download the ZIP file (`mattchecker-project.zip`)

2. **Extract the project**
   - Right-click the downloaded ZIP file
   - Click **Extract All…**
   - Extract using WinRAR, 7-Zip, or Windows Explorer

3. **Move to XAMPP directory**
   - Place the extracted folder inside: C:\xampp\htdocs\

4. **Database Setup**
- Open XAMPP and start **Apache** and **MySQL**
- Go to phpMyAdmin: http://localhost/phpmyadmin
- Create a database named: checker_db
- Import the provided `checker_db.sql` file using phpMyAdmin

5. **Configuration**
- Open the project folder
- Locate your database configuration file (e.g. `config.php`)
- Update database credentials:
  - Host: `localhost`
  - Username: `root`
  - Password: *(leave blank if using default XAMPP)*
  - Database: `checker_db`

6. **Launch**
- Open your browser
- Visit: http://localhost/mattchecker-project

---

*Developed as a Capstone Project for BS in Information Technology, Class of 2026.*
