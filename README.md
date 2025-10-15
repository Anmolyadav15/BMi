🧮 HealthTrack BMI Calculator

A modern, responsive web application designed to help users track their Body Mass Index (BMI), manage health goals, and monitor their progress using a clean, accessible interface with built-in dark mode functionality.

✨ Features

Accurate BMI Calculation: Instantly calculate BMI based on weight (kg) and height (cm/in).

Health Status Categorization: Provides feedback on the user's BMI (e.g., Underweight, Healthy, Overweight, Obese).

Persistent Data Storage: Securely save and retrieve user weight, height, and past BMI readings using Google Firestore (required for multi-user/shared data).

User Authentication: Supports anonymous and authenticated sign-ins to link data to a specific user ID.

🌒 Dark Mode Toggle: Seamlessly switch between light and dark themes for enhanced viewing comfort in different environments.

Fully Responsive Design: Optimized for desktop, tablet, and mobile devices using Tailwind CSS utility classes.

Visual History (Planned): Display a simple graph of historical BMI scores over time.

💻 Tech Stack

This project is built using a modern, scalable stack focused on real-time data persistence and a great user experience.

Frontend Structure: HTML5 provides the core structure of the application.

Styling: CSS3 and Tailwind CSS are used as a utility-first framework for rapid, responsive design and dark mode styling.

Logic: JavaScript (ES6+) handles the BMI calculation, DOM manipulation, user interactions, and all API calls.

Database: Firebase / Firestore serves as the real-time, cloud-based NoSQL database for saving user profiles and historical BMI data.

Backend (Future): Python (e.g., Flask/Django) is reserved for complex backend services, reporting, or advanced health recommendation APIs (currently a placeholder).

API: The Gemini API is intended for potential future integration for AI-powered health tips or goal setting based on BMI data.

🚀 Installation & Setup

To run this project locally, you need a web browser and an internet connection to load the external Firebase SDKs.

Clone the Repository (Conceptual):

# Replace with your actual repository link
git clone [your-repo-link]
cd healthtrack-bmi-calculator


Open in Browser:
The core application is a single index.html file (or similar structure). Simply open the main HTML file in your web browser.

Data Persistence:
The application automatically initializes Firebase and handles user authentication using the provided environment variables to ensure data persistence and security via Firestore.

🤝 Usage

Input: Enter your weight and height in the designated fields.

Calculate: Click the "Calculate BMI" button to see your result and health category.

Toggle Mode: Use the 🌓 icon in the navigation bar to instantly switch between the light and dark themes.

History: Your records are automatically saved to your user profile in Firestore.

Developed as a collaborative project.
