# Get started

## Installation

To get started with this project, follow these steps to set up your environment and install the necessary dependencies using `uv`.

### Prerequisites

*   **uv**: Ensure you have `uv` installed. If not, you can install it via pip:
    ```bash
    pip install uv
    ```

### Install Dependencies

Navigate to the project directory and install the required packages:

```bash
uv sync
```

This command will install `pandas`, `numpy`, `matplotlib`, and other libraries, which are essential for data analysis in this project.

## To avoid .ipynb metadata inconsistencies, use:
```
nbstripout --install
```