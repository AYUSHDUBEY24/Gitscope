# 🚀 GitScope – GitHub Repository Analytics Dashboard

GitScope is a web-based GitHub analytics dashboard that helps users explore GitHub repositories, track repository activity, and understand audience engagement through a clean and interactive interface.

This project is developed as part of a **DevOps practical project**, demonstrating key DevOps concepts such as Git version control, CI automation using GitHub Actions, automated builds, Docker containerization, and Docker Compose.

## ✨ Features

- **GitHub Authentication:** Sign in using GitHub.
- **Repository Analytics:** Explore GitHub repositories and their details.
- **Dashboard Overview:** View repository-related information in one place.
- **Audience Insights:** Explore audience and follower-related information.
- **Docker Support:** Run the application using Docker containers.
- **Automated CI Workflow:** Validate backend tests and frontend builds using GitHub Actions.

## 🛠️ Technology Stack

| Component | Technology |
|---|---|
| Frontend | Next.js, React, TypeScript |
| Backend | Python, FastAPI |
| Database | MongoDB |
| Authentication | Firebase Authentication |
| Version Control | Git & GitHub |
| CI Automation | GitHub Actions |
| Containerization | Docker |
| Container Orchestration | Docker Compose |

## 📚 DevOps Concepts Implemented

This project demonstrates the following DevOps concepts:

### 1. Git & GitHub
- Version control for source code.
- Tracking project changes through commits.
- Hosting and managing source code on GitHub.

### 2. GitHub Actions (Continuous Integration)
- Automated workflow execution on push and pull requests.
- Backend and frontend validation.
- Automatic execution of CI jobs.

### 3. Automated Build
- Frontend dependency installation.
- TypeScript type checking.
- Production build generation.

### 4. Docker
- Containerization of frontend and backend services.
- Consistent application environment.

### 5. Docker Compose
- Managing multiple application containers.
- Running frontend and backend together.
- Simplified local application setup.

## 📁 Project Structure

```text
GitScope/
│
├── .github/
│   └── workflows/
│       └── ci.yml
│
├── backend/
│   ├── app/
│   ├── tests/
│   ├── requirements.txt
│   └── requirements-dev.txt
│
├── frontend/
│   ├── app/
│   ├── components/
│   ├── package.json
│   └── package-lock.json
│
├── docker-compose.yml
├── README.md
└── .gitignore
```

## ⚙️ Local Setup

### Prerequisites

Make sure you have installed:

- Git
- Docker Desktop
- Node.js (for local frontend development)
- Python (for local backend development)

### 1. Clone the Repository

```bash
git clone https://github.com/AYUSHDUBEY24/Gitscope.git
```

### 2. Navigate to the Project

```bash
cd Gitscope
```

### 3. Configure Environment Variables

Configure the required environment variables for the backend and frontend.

Create the required `.env` files using the project's environment configuration.

**Note:** Never commit API keys, passwords, or secret credentials to GitHub.

### 4. Run Using Docker Compose

```bash
docker compose up --build
```

This command builds the required images and starts the application containers.

To stop the application:

```bash
docker compose down
```

## 🔄 GitHub Actions Workflow

GitScope uses GitHub Actions for Continuous Integration.

The workflow is located at:

```text
.github/workflows/ci.yml
```

It runs automatically when code is pushed to the `main` branch or a pull request targets `main`.

### CI Pipeline Includes

**Backend Job**
- Checkout source code.
- Set up Python.
- Install dependencies.
- Execute backend unit tests.

**Frontend Job**
- Checkout source code.
- Set up Node.js.
- Install dependencies.
- Run TypeScript checks.
- Generate production build.

## 🎯 Project Objective

The main objective of GitScope is to demonstrate how DevOps practices can be applied to a real-world web application.

The project focuses on source code management, automated CI workflows, build validation, containerization, and local multi-container application deployment.

## 👨‍💻 Author

**Ayush Dubey**

GitHub: [AYUSHDUBEY24](https://github.com/AYUSHDUBEY24)

---

⭐ If you find this project useful, consider giving it a star!