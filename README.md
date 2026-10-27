
# ci-cd-final-project

This repository contains the CI/CD Tools and Practices final project for the Coursera course.

## Project Overview

This project demonstrates continuous integration using GitHub Actions, code linting with Flake8, unit testing with Nose, and task automation using Tekton.

## Technologies Used

- Python
- GitHub Actions
- Flake8
- Nose
- Tekton

## Continuous Integration

The GitHub Actions workflow runs when code is pushed to the main branch or when a pull request targets the main branch. It installs dependencies, checks code quality with Flake8, and runs unit tests with Nose.

## Tekton Tasks

The Tekton tasks include a cleanup task to remove previous workspace files and a test task to install dependencies and run unit tests with Nose.
