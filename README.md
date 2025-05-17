# Solar Challenge Week 1

This repository contains the setup for the Solar Challenge Week 1 project, including a Python virtual environment, GitHub Actions CI, and folder structure for data analysis tasks.

## Folder Structure

```
├── .vscode/
│   └── settings.json
├── .github/
│   └── workflows/
│       └── ci.yml
├── .gitignore
├── requirements.txt
├── README.md
├── src/
├── notebooks/
│   ├── __init__.py
│   └── README.md
├── tests/
│   ├── __init__.py
└── scripts/
    ├── __init__.py
    └── README.md
```

## Setup Instructions

1. **Clone the Repository**

   ```bash
   git clone https://github.com/MubarekAdem/solar-challenge-week1.git
   cd solar-challenge-week1
   ```

2. **Set Up Python Virtual Environment**Using `venv`:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Verify Setup**Run the following to ensure Python and dependencies are set up:

   ```bash
   python --version
   pip list
   ```

## Running Tests

Tests are located in the `tests/` folder. To run them:

```bash
pytest tests/
```

## Contributing

- Create a new branch for your work: `git checkout -b feature/your-feature-name`
- Commit changes and push to GitHub.
- Open a Pull Request to merge into `main`.
