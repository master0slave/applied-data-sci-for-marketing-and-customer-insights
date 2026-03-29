
# Installation and Setup

## Prerequisites
- Python 3.8 or higher
- `uv` package manager installed

## Installation Steps

1. **Clone the repository**
    ```bash
    git clone <repository-url>
    cd applied-data-sci-for-marketing-and-customer-insights
    ```

2. **Install dependencies with uv**
    ```bash
    uv sync
    ```

3. **Activate the virtual environment**
    ```bash
    source .venv/bin/activate  # On macOS/Linux
    # or
    .venv\Scripts\activate  # On Windows
    ```

4. **Verify installation**
    ```bash
    uv pip list
    ```


## Additional Notes

- Use `uv add <package-name>` to install new packages
- Use `uv remove <package-name>` to remove packages
- Run `uv --help` for more uv commands
