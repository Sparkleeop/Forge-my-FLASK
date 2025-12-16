# Forge My Flask (FMF)

Forge My Flask (FMF) is a lightweight CLI tool that scaffolds Flask projects in seconds.  
It helps you quickly bootstrap Flask web applications or Flask API projects using a clean and practical project structure.

FMF is designed to be beginner friendly while still following patterns used in real Flask projects.

---

## Features

- Create Flask web applications with templates and static files
- Create Flask API projects using blueprints
- Interactive and non interactive CLI usage
- Clean and consistent project structure
- No configuration required
- Works on Windows, Linux, and macOS

---

## Project Types

### Web App

Generates a Flask project with:
- `app.py`
- `templates/`
- `static/`
- `requirements.txt`

Best suited for traditional Flask applications that use HTML templates.

### API

Generates a Flask API project with:
- Application factory pattern
- Blueprint based routing
- Example health endpoint
- Utility helpers for JSON responses
- `requirements.txt`

Best suited for REST APIs and backend services.

---

## Installation

Install FMF from PyPI:

```bash
pip install forge-my-flask
````

Run the CLI:

```bash
fmf
```

### Windows note

If the `fmf` command is not recognized, use:

```bash
python -m fmf
```

This can happen if the Python Scripts directory is not added to PATH.

---

## Usage

### Interactive mode

Run:

```bash
fmf
```

You will be prompted to select a project type:

```
Forge My Flask (FMF)

1. API Project
2. WebApp Project
```

Follow the prompts and enter a project name. FMF will generate the project automatically.

---

### Non interactive mode

Create projects directly from the command line:

```bash
fmf init api my_api_project
fmf init web my_web_project
```

This skips the menu and scaffolds the project immediately.

---

## Example Output

### Web App Structure

```
my_web_project/
├── app.py
├── requirements.txt
├── templates/
│   └── index.html
└── static/
    └── style.css
```

### API Structure

```
my_api_project/
├── app.py
├── config.py
├── requirements.txt
├── routes/
│   ├── __init__.py
│   └── health.py
└── utils/
    └── response.py
```

---

## Why FMF

Flask provides flexibility, but that flexibility often leads to inconsistent project layouts and repeated boilerplate.

FMF solves this by providing a simple and consistent starting point that can be extended as projects grow.

---

## Roadmap

Planned improvements include:

* Additional CLI flags such as `--no-install`
* Environment based configuration

---

## Contributing

Contributions are welcome.

If you find a bug or have a suggestion, feel free to open an issue or submit a pull request.

---

## License

MIT License

---

## Author

Built by Sparklee
