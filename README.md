# Automated Deployment of Static Website using GitHub Actions

## Project Overview
This project demonstrates a working CI/CD pipeline that automatically deploys a static website built using HTML and CSS to GitHub Pages using GitHub Actions.

Any change pushed to the main branch triggers the pipeline and deploys the updated website without manual intervention.

## Technologies Used
- HTML
- CSS
- GitHub Actions
- GitHub Pages

## Project Structure

## CI/CD Pipeline Configuration
The CI/CD pipeline is configured using GitHub Actions.

- The workflow triggers automatically on every push to the `main` branch.
- It checks out the repository.
- Uploads the static files as an artifact.
- Deploys the website to GitHub Pages.

## Automated Deployment Demonstration
The deployment process is fully automated and works as follows:

1. Update HTML or CSS files.
2. Push changes to the `main` branch.
3. GitHub Actions workflow runs automatically.
4. The updated website is deployed to GitHub Pages.

No manual deployment steps are required.

## Live Website
The deployed website is available at:

https://<your-username>.github.io/<repository-name>/

## Outcome
- Working CI/CD pipeline configuration
- Automated deployment using GitHub Actions
- Static website successfully hosted on GitHub Pages

## Conclusion
This project fulfills the requirement of a working pipeline configuration and a demonstration of automated deployment by using GitHub Actions to deploy a static website automatically on every code push.
