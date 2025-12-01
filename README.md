# Static Site Jenkins CI/CD Demo

This is a very simple static website (HTML/CSS) used to demonstrate a CI/CD
pipeline with Jenkins.

## Project Structure

- `index.html` : main page
- `style.css` : styles
- `Jenkinsfile` : Jenkins pipeline definition
- `README.md` : project description

The goal is to configure a Jenkins pipeline that:
1. Checks out the code from GitHub
2. (Optionally) runs simple tests
3. Packages the static files for deployment
