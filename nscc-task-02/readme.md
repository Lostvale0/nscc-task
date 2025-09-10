# Task 2: Interactive Quiz App

This project is a dynamic, single-page web application created for the Newton School Coding Club recruitment task. It features an interactive multiple-choice quiz that provides instant feedback and scoring upon submission.

## 🚀 Live Deployment

A live version of this project can be accessed at the following link

[**https://lostvale0.github.io/nscc-task/nscc-task-02/**](https://lostvale0.github.io/nscc-task/nscc-task-02/)

## ✨ Features

* **Modern UI**: A clean, responsive, and dark-themed interface built with Tailwind CSS.
* **Interactive Quiz**: Features 5 multiple-choice questions dynamically loaded from a JavaScript object.
* **Instant Scoring**: Calculates and displays the final score immediately after submission.
* **Detailed Feedback**: Shows a question-by-question breakdown of correct and incorrect answers.
* **Restart Functionality**: Allows users to easily clear their results and retake the quiz.

## 💻 Technologies Used

* **HTML5**
* **Tailwind CSS**
* **JavaScript (ES6+)**
* **GitHub Actions** for Continuous Integration & Continuous Deployment (CI/CD).

## 🚀 Deployment

This project uses **GitHub Actions** for automated deployment to GitHub Pages.

1.  **Trigger**: A deployment is automatically triggered on every `push` to the `main` branch.
2.  **Workflow**: The GitHub Actions workflow (`/.github/workflows/deploy.yml`) checks out the code, sets up the necessary environment, and deploys the static files.
3.  **Result**: The site is automatically built and published to the `gh-pages` branch, making it live at the URL provided above.

This CI/CD pipeline ensures that the live version is always in sync with the latest changes in the `main` branch.

## 🛠️ Local Environment Setup

To run this project on your local machine:

1. Clone the repository:
   ```bash
   git clone https://github.com/lostvale0/nscc-task.git
   ```
2. Navigate to the project folder:
    ```bash
   cd nscc-task/nscc-task-01
    ```

3. Open the `index.html` file in any modern web browser (like Google Chrome, Firefox, or Microsoft Edge).

## 🖼️ Screenshots

![Quiz App Screenshot 1](https://i.ibb.co/S4xYZRQJ/9h-V28fp-R3a.png)
*The main quiz interface where users select their answers.*

![Quiz App Screenshot 2](https://i.ibb.co/DH9ymWMK/image.png)
*The results screen showing the final score and detailed feedback.*
