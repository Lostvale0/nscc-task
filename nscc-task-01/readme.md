# Task 1: Signup Form with Validation & Dashboard

This project is a fully functional, single-page web application built for the Newton School Coding Club recruitment task. It features a user signup form with robust client-side validation, secure password hashing, and a dynamic dashboard that stores and manages user data using the browser's local storage.

## 🚀 Live Deployment

The project is deployed and accessible live at the following link:

[**https://lostvale0.github.io/nscc-task/nscc-task-01/**](https://lostvale0.github.io/nscc-task/nscc-task-01/)

## ✨ Features

* **Modern UI**: A clean, responsive, and dark-themed interface built with Tailwind CSS.

* **Client-Side Validation**: Real-time feedback for form inputs to ensure data integrity.

* **Secure Password Hashing**: Passwords are never stored as plain text and are securely hashed using the **SHA-256** algorithm via the Web Crypto API.

* **Dynamic Dashboard**: User entries are instantly rendered in a dashboard table upon successful signup.

* **Data Persistence**: User data is saved in `localStorage`, ensuring information persists after a page refresh.

* **Delete Functionality**: Users can be removed from both the dashboard and `localStorage`.

## 💻 Technologies Used

* **HTML5**

* **Tailwind CSS**

* **JavaScript (ES6+)**

* **GitHub Actions** for Continuous Integration & Continuous Deployment (CI/CD).

## 🚀 Deployment

This project uses **GitHub Actions** for automated deployment to GitHub Pages.

1. **Trigger**: A deployment is automatically triggered on every `push` to the `main` branch.

2. **Workflow**: The GitHub Actions workflow (`/.github/workflows/deploy.yml`) checks out the code, sets up the necessary environment, and deploys the static files.

3. **Result**: The site is automatically built and published to the `gh-pages` branch, making it live at the URL provided above.

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
![Signup Form Screenshot 1](https://i.ibb.co/q3MKsZ29/1.png)
*Homepage of the Signup Form*

![Signup Form Screenshot 2](https://i.ibb.co/RkrVShYp/2.png)  
*User Dashboard*
