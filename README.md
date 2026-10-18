# My CI/CD Website

## Project Overview

This project demonstrates a complete CI/CD pipeline using Jenkins to automatically build, test, and deploy a static website on an AWS EC2 instance.

Whenever code is pushed to the GitHub repository, Jenkins automatically:
1. Checks out the latest code
2. Tests if the website files are present
3. Deploys the website to the EC2 server

## Tech Stack

- Jenkins
- GitHub
- AWS EC2
- HTML
- Shell Scripting

## Pipeline Stages

- Checkout : Pulls the latest code from GitHub
- Build : No build required
- Test : Checks if index.html exists
- Deploy : Deploys website to EC2

## How It Works

Developer → Push to GitHub → Jenkins → Deploy to EC2 → Website Live

## Project Structure

- Jenkinsfile
- index.html
- README.md

## Skills Demonstrated

- Jenkins Pipeline
- GitHub Integration
- AWS EC2
- CI/CD
- Automated Deployment

## Project Status

Completed

Author: Vishvajeet Shinde