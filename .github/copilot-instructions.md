# Copilot Instructions for AI Agents

## Project Overview
This workspace is a collection of Python notebooks focused on basic Python concepts, data types, and function parameters. The structure is organized by topic, with each folder containing related Jupyter notebooks. There is no monolithic application or complex service architecture—each notebook is self-contained and intended for educational or exploratory use.

## Directory Structure
- `my_py_basic/`: Introductory Python notebooks
- `py/1st/`: Notebooks on function parameters and arguments
- `python_data_types/`: Notebooks on Python data types

## Key Patterns and Conventions
- **Notebook-centric workflow:** All code is in `.ipynb` files. Each notebook is independent; there are no cross-notebook imports or shared modules.
- **Python version:** Use the default Python environment configured for the workspace. No explicit versioning or virtual environment setup is present.
- **No external dependencies:** Notebooks do not require third-party packages. Use only Python built-in types and functions unless explicitly instructed otherwise.
- **Naming conventions:** Notebook filenames describe their content (e.g., `parameter&argument.ipynb`, `python_data_types.ipynb`).
- **Code style:** Follow PEP8 for Python code. Use clear comments and simple examples suitable for beginners.

## Developer Workflows
- **Editing:** Make changes directly in notebook cells. Do not refactor across files.
- **Testing:** There are no automated tests. Validate code by running cells interactively.
- **Debugging:** Use print statements and cell outputs for debugging. No advanced debugging tools are configured.
- **Builds:** No build process is required.

## Integration Points
- **No external APIs or services:** All code is local and self-contained.
- **No data persistence:** Notebooks do not read/write external files or databases.

## Example Patterns
- Demonstrate Python concepts with simple code snippets:
  ```python
  # Example: Print a string
  print("hello world")
  ```
- Use markdown cells for explanations and code cells for examples.

## How to Contribute
- Add new notebooks in the appropriate topic folder.
- Keep each notebook focused on a single concept.
- Do not introduce external dependencies unless necessary for a new topic.

---
If any section is unclear or missing, please provide feedback for further refinement.
