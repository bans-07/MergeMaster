# MergeMaster
# 🚀 Tech Quiz App – CI/CD + Cypress + Render Deployment

A full-stack MERN application where users can take a 10-question tech quiz and view their score. This app features Cypress component testing, GitHub Actions workflows, and automatic deployment to Render.

![App Screenshot](./screenshot.png)

## 🔗 Live Demo

**📁 GitHub Repo:** https://github.com/bans-07/MergeMaster
---

## 📦 Tech Stack

- **Frontend:** React, TypeScript, Vite, React Bootstrap
- **Backend:** Node.js, Express, MongoDB, GraphQL (Apollo Server)
- **Testing:** Cypress (Component Testing)
- **CI/CD:** GitHub Actions
- **Deployment:** Render

---

## ✅ Features

- Take a 10-question tech quiz
- View results and scores
- Save high scores
- Responsive, mobile-first UI
- Real-time component testing with Cypress
- GitHub Actions pipelines:
  - Run Cypress tests on PRs to `develop`
  - Auto-deploy to Render on merge to `main`

---

## 🧪 Cypress Test Setup

Cypress is configured to run component tests on every Pull Request to the `develop` branch.

**Run locally:**

```bash
cd client
npm run cy:component
