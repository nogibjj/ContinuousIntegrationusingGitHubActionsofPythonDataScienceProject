# Continuous Integration using GitHub Actions of Python Data Science Project: Individual Project One
### by Rakeen Rouf

[![Format](https://github.com/nogibjj/ContinuousIntegrationusingGitHubActionsofPythonDataScienceProject/actions/workflows/format.yml/badge.svg)](https://github.com/nogibjj/ContinuousIntegrationusingGitHubActionsofPythonDataScienceProject/actions/workflows/format.yml) [![Lint](https://github.com/nogibjj/ContinuousIntegrationusingGitHubActionsofPythonDataScienceProject/actions/workflows/lint.yml/badge.svg)](https://github.com/nogibjj/ContinuousIntegrationusingGitHubActionsofPythonDataScienceProject/actions/workflows/lint.yml) [![OnInstall](https://github.com/nogibjj/ContinuousIntegrationusingGitHubActionsofPythonDataScienceProject/actions/workflows/install.yml/badge.svg)](https://github.com/nogibjj/ContinuousIntegrationusingGitHubActionsofPythonDataScienceProject/actions/workflows/install.yml) [![Test](https://github.com/nogibjj/ContinuousIntegrationusingGitHubActionsofPythonDataScienceProject/actions/workflows/test.yml/badge.svg)](https://github.com/nogibjj/ContinuousIntegrationusingGitHubActionsofPythonDataScienceProject/actions/workflows/test.yml)

---

**Walk Through Youtube Video**
[Youtube](https://youtu.be/YduYJFkaXa0)

---
**Summary**

This project serves as an illustrative guide for implementing Continuous Integration (CI) using GitHub Actions in Python-based Data Science projects. By adopting CI, it helps maintain code quality and consistency throughout the development process. The workflows include linting, formatting, installing dependencies, and running tests, ensuring that these critical steps are automatically executed with every push and pull request to the repository.

---
**Project Structure**

- **Jupyter Notebook(src/DescriptiveStats.ipynb)**:
  - Contains cells that perform descriptive statistics using Pandas.
  - Validated using the nbval plugin for pytest.

- **Python Script(src/script_descriptive_stats.py)**:
  - Executes the same descriptive statistics using Pandas.

- **lib.py(src/lib.py)**:
  - Holds shared code used by both the script and the notebook.

- **Makefile**:
  - Contains four commands:
    - Test: Run all tests (notebook, script, and lib)
    - Format: Format code with Python black
    - Lint: Lint code with Ruff
    - Install: Install dependencies via `pip install -r requirements.txt`

- **test_script.py(tests/test_script_descriptive_stats.py)**:
  - Contains tests for the script.

- **test_lib.py(tests/test_lib.py)**:
  - Includes tests for the library.

- **Pinned requirements.txt**:
  - Specifies exact versions of dependencies.

---
