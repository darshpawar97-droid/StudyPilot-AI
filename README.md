# StudyPilot AI

An AI-inspired study planner for students. Organize subjects, add study tasks, track progress, and generate a priority-based daily study plan.

## Features
- Dashboard with study overview and progress
- Subject and task management
- Priority-based study plan generator
- Persistent browser storage in the demo frontend
- Express + SQLite backend starter in /server

## Run locally

### Frontend
Open index.html in a browser, or serve the repository with any static web server.

### Backend API
```bash
cd server
npm install
npm start
```
The API runs at http://localhost:4000 and uses SQLite to store subjects and tasks.

## Deployment
The frontend can be hosted as a static site (for example GitHub Pages). Deploy the Express API separately on a Node.js host with persistent storage. Configure the frontend API URL before connecting it to the backend. The included browser demo works without the API and stores data in local browser storage.

## Note
The planner uses transparent priority/deadline-based scheduling rules; it is an AI-inspired academic project demo, not a connection to a hosted generative-AI model.
