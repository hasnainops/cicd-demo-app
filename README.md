# CI/CD Demo Application

![CI/CD Pipeline](https://github.com/hasnainops/cicd-demo-app/actions/workflows/ci-cd.yml/badge.svg)
![Pull Request Validation](https://github.com/hasnainops/cicd-demo-app/actions/workflows/pr-validation.yml/badge.svg)

This is a simple web application demonstrating CI/CD pipelines with GitHub Actions.

## Features
- Automated testing on every commit
- Automated deployment to GitHub Pages
- Pull request validation
- Simple web interface with interactive elements

## Live Demo
🚀 [View Live Application](https://hasnainops.github.io/cicd-demo-app)

## Local Development

1. Clone the repository
2. Run:
   git clone https://github.com/hasnainops/cicd-demo-app.git
   cd cicd-demo-app
   npm test
   npm start

Open http://localhost:8000 in your browser

## CI/CD Pipeline

This project uses GitHub Actions for:
- ✅ Running automated tests
- ✅ Code quality validation
- ✅ Deploying to GitHub Pages on successful builds
- ✅ Pull request validation

## Workflow Files
- .github/workflows/ci-cd.yml - Main CI/CD pipeline
- .github/workflows/pr-validation.yml - Pull request validation
- .github/workflows/staging.yml - Staging deployment

## Project Structure
cicd-demo-app/
├── src/
│   ├── index.html
│   ├── style.css
│   └── script.js
├── tests/
│   └── test.js
├── .github/
│   └── workflows/
│       ├── ci-cd.yml
│       ├── pr-validation.yml
│       └── staging.yml
└── package.json

