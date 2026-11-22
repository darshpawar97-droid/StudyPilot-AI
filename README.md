# StudyPilot AI — AI-Based Study Planner

A responsive student study-planner web app. Add tasks, assign subjects, track completion, and generate a 7-day study schedule.

## Current demo features
- Responsive dashboard and navigation
- Create tasks with subject, deadline, and estimated study time
- Mark tasks complete and track progress
- Priority-based 7-day study plan generator
- Saves demo data in the browser using localStorage

## Run / preview
Open `index.html` in a browser, or serve the repository using a static web server.

## Publish with GitHub Pages
A GitHub Actions workflow is included at `.github/workflows/deploy.yml`.
1. Open this repository's **Settings → Pages**.
2. Under **Build and deployment**, choose **GitHub Actions** as the source.
3. Open the **Actions** tab and wait for **Deploy StudyPilot AI to GitHub Pages** to finish successfully.
4. Your site will be available at https://darshpawar97-droid.github.io/StudyPilot-AI/

## Important project note
The currently published browser demo stores data locally in each browser. Its study-plan generator uses transparent deadline/effort-based scheduling rules; it does not call a hosted generative-AI model. A persistent multi-user backend and database deployment would be a separate next step.
