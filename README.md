# default-python-structure
Default python project strucutre


## Installation

### Install uv

Follow the instructions below to install uv on your system:

- **MacOS/Linux:**  
    Open your terminal and run:
    ```
    curl -LsSf https://astral.sh/uv/install.sh | sh
    ```

- **Windows:**  
    Open PowerShell and run:
    ```
    powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
    ```

### Create virtual environment

```
uv venv .venv_project_name -p 3.11
source .venv_project_name/bin/activate
```

### Install packages

```
uv pip install
uv pip install -E dev
```

