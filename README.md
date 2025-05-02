![Project Screenshot](Webpage_Screenshot.png)
Auto Deploy Static Site 🚀
Live Demo:
🌐 https://eli-sep.github.io/auto-deploy-static-site/

📌 Overview
This project showcases a fully automated deployment pipeline using GitHub Actions and GitHub Pages. Whenever you push changes to the main branch, a workflow automatically publishes the latest version to the live web using the gh-pages branch — with zero manual steps.

🛠 Technologies Used
HTML & CSS – Static site content

Git & GitHub – Version control and repo hosting

GitHub Actions – CI/CD automation

GitHub Pages – Static site hosting

📁 Project Structure
auto-deploy-static-site/
├── index.html
├── styles.css
└── .github/
  └── workflows/
    └── deploy.yml

🔄 How It Works
You push a change to the main branch

GitHub Actions runs the deploy.yml workflow

It uses peaceiris/actions-gh-pages to push your files to the gh-pages branch

GitHub Pages serves the content from gh-pages to the public web

⚙️ GitHub Actions Workflow Summary
The deployment workflow is configured to:

Trigger on every push to main

Use the GitHub token for secure access

Deploy the root directory (./) to the gh-pages branch

This setup gives you a clean and automated CI/CD process for static sites.

👤 Author
Built by @eli-sep
My first DevOps-style GitHub project using Actions + Pages 🚀
