# Forge My Flask (FMF)

Forge My Flask (FMF) is a lightweight CLI tool that scaffolds Flask projects in seconds.  
It helps you quickly bootstrap **Flask web apps** or **Flask API projects** with a clean, sensible structure — without boilerplate fatigue.

FMF is designed to be beginner-friendly while still following patterns used in real-world Flask projects.

---

## Features

- Create Flask **Web App** projects (templates + static)
- Create Flask **API** projects (blueprints, JSON responses)
- Clean, opinionated project structure
- Zero configuration required
- Works on Windows, Linux, and macOS
- Simple interactive CLI

---

## Project Types

### Web App
Generates a Flask project with:
- `app.py`
- `templates/`
- `static/`
- `requirements.txt`

Best suited for traditional Flask apps with HTML templates.

### API
Generates a Flask API project with:
- Application factory (`create_app`)
- Blueprint-based routing
- Example health endpoint
- Clean separation of routes and utilities
- `requirements.txt`

Ideal for REST APIs and backend services.

---

## Installation

> Coming soon via PyPI.

For now, clone the repository:

```bash
git clone https://github.com/yourusername/forge-my-flask.git
cd forge-my-flask
