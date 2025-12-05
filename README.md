🚀 Web Developer Internship Assignment - ATH Innovations

Submitted by: Kunal Jagdish Nerkar

Date: December 6, 2025

📋 Project Overview

This is a Single-Page Application (SPA) built to fulfill the selection assignment for the Web Developer Internship at ATH Innovations.

The application features a seamless user experience with three distinct views (Home, Form, Display), client-side routing, form validation, and data persistence using localStorage. It was built using a mobile-first approach with Tailwind CSS for rapid, modern styling.

🔗 Live Demo

https://studentkunal.github.io/ath_assignment/

🛠️ Tech Stack

HTML5: Semantic structure.

CSS3 (Tailwind CSS): Utility-first styling for responsiveness and modern UI.

JavaScript (Vanilla): DOM manipulation, client-side routing, and State Management.

Git: Version control.

📜 Development Workflow & Git Command History

This project was built incrementally. Below is the log of the Git commands and development steps taken to ensure a clean commit history, as per the assignment rules.

Step 1: Initialization

I started by setting up the project directory and initializing Git.

git init
git add .
git commit -m "chore: Initialize project and set up file structure"


Step 2: Homepage Implementation

I created the index.html file and integrated Tailwind CSS via CDN. I designed the Hero section with a responsive background and a Call-to-Action button.

git add index.html
git commit -m "feat: Create Homepage with responsive hero section and Tailwind setup"


Step 3: Form Page & Validation

I added the page-form section hidden by default. I implemented the input fields (Name, Email, Title, Description) and added HTML5 validation attributes.

git add index.html
git commit -m "feat: Add Form Page structure with required input fields"


Step 4: Logic & Data Persistence

I wrote the JavaScript logic to handle the form submission event. Instead of a server, I used localStorage to save the JSON data and created a custom showMessage() function to replace default browser alerts.

git add index.html
git commit -m "feat: Implement form handling, validation logic, and localStorage"


Step 5: Display Page & Routing

I created the page-display section to read from localStorage and show the data in a card. I also finalized the Maps() function to switch between the three views without refreshing the page.

git add index.html
git commit -m "feat: Complete Display Page logic and client-side routing system"


Step 6: Final Polish & Cleanup

I adjusted the mobile responsiveness, added a "Clear Data" button, and ensured the code was formatted correctly.

git add index.html
git commit -m "style: Polish UI responsiveness and clean up code structure"


Step 7: Push to GitHub

Finally, I connected the local repository to GitHub and pushed the main branch.

git branch -M main
git remote add origin https://github.com/studentkunal/ath_assignment.git
git push -u origin main


✨ Features

1. Homepage

ATH Innovations Internship Assignment

A clean, functional mini web application with three pages to evaluate coding ability, UI skills, and structure.

"Start Submission" button that routes to the form.

2. Form Page

Fields: Full Name, Email, Project Title, Description.

Validation: Prevents submission of empty fields and checks email format.

UX: Custom non-blocking success/error notifications (No alert()).

3. Display Page

Data Retrieval: Fetches submission data from Local Storage.

Responsive Card: Displays data in a clean layout that works on mobile and desktop.

State Persistence: Data remains available even if the page is refreshed.

💡 Experience & Reflection

(Note to Reviewer: This is the reflection required by the assignment)

During this task, I reinforced my understanding of Single Page Application (SPA) architecture using only vanilla JavaScript. The main challenge was implementing a routing system without a framework; I solved this by using a state-based approach where CSS classes (hidden) toggle visibility based on user interaction. I also learned how to effectively use localStorage to persist data across these views, simulating a real backend experience while keeping the application lightweight and fast.