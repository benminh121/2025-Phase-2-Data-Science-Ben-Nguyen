## How to Run This Project
This project uses a pyproject.toml file to manage dependencies. You can use either poetry or uv to set up the environment. Please, remember to install uv if you haven't already.

1. **Clone the repository:**

```bash
git clone <repo-url>
cd <repo-name>
```

2. **Create a virtual environment using `pyproject.toml`:**

```bash
uv sync
```

_(Which will create its own .venv/, activate it, and install the dependencies in the `pyproject.toml` file.)_

Alternatively, activate the virtual environment

```bash
source .venv/bin/activate
```