# Stack-Exercise
# Onboarding Project Assignment

Welcome to the team! Please complete this small project to get familiar with our tech stack before you start.

If you get stuck on any step, skip it and move to the next one if possible. You can come back to it later.

## Objective

Build a simple full-stack application with a backend API and frontend interface, using our standard tools. The goal is to explore modular app development, containerization, testing, and automation workflows.

## Tech Stack

- Frontend: Angular (in an Nx workspace/ monorepo)
- Backend: NestJS (Node.js) (in an Nx workspace/ monorepo)
- Database: Any open-source document-oriented DB (e.g., CouchDB, FerretDB)
- Search Engine: Elasticsearch
- Containerization: Docker, Docker Compose
- CI/CD: GitHub Actions

Note: Please avoid using any paid services. If something requires a license or subscription, skip it or use a free/open-source alternative.

## Project Description – Task Manager App

Create a basic Task Manager with the following functionality:

Users can:
- Create tasks with title, description, status, createdAt
- View a list of tasks
- Update task status
- Delete tasks

Optional: Add basic JWT-based login for users

## Implementation Requirements

Backend (NestJS):
- REST API with full CRUD for tasks
- Use DTOs and input validation
- Store tasks in a document-based database
- Index tasks in Elasticsearch for full-text search

Frontend (Angular):
- Display task list and add/edit form
- Use Angular HttpClient to consume the API
- Add form validation for required fields
- Optionally include a search bar powered by the backend

Docker:
- Containerize backend and database
- Provide a docker-compose.yml to run services locally

## Optional Enhancements

CI/CD (GitHub Actions):
Add GitHub Actions workflow to:
- Run nx lint
- Run unit tests
- Run E2E tests
- Check code formatting (nx format:check)

Kubernetes (Optional):
Create Helm charts for backend deployment
Include manifests/templates for:
- Deployment
- Service
- ConfigMap or Secrets
- (Optional) Ingress

Extras:
- Use shared Nx libraries for interfaces or constants
- Add Jest unit tests for services/components
- Add Playwright or Cypress for E2E testing

## Submission Instructions

- Push your project to a private GitHub repository
- We'll walk through your codebase together during your onboarding
