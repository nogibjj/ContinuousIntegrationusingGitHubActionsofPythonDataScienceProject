# Continuous Integration using GitHub Actions of Python Data Science Project: Individual Project One
### by Rakeen Rouf

[![Format](https://github.com/nogibjj/ContinuousIntegrationusingGitHubActionsofPythonDataScienceProject/actions/workflows/format.yml/badge.svg)](https://github.com/nogibjj/ContinuousIntegrationusingGitHubActionsofPythonDataScienceProject/actions/workflows/format.yml) [![Lint](https://github.com/nogibjj/ContinuousIntegrationusingGitHubActionsofPythonDataScienceProject/actions/workflows/lint.yml/badge.svg)](https://github.com/nogibjj/ContinuousIntegrationusingGitHubActionsofPythonDataScienceProject/actions/workflows/lint.yml) [![OnInstall](https://github.com/nogibjj/ContinuousIntegrationusingGitHubActionsofPythonDataScienceProject/actions/workflows/install.yml/badge.svg)](https://github.com/nogibjj/ContinuousIntegrationusingGitHubActionsofPythonDataScienceProject/actions/workflows/install.yml) [![Test](https://github.com/nogibjj/ContinuousIntegrationusingGitHubActionsofPythonDataScienceProject/actions/workflows/test.yml/badge.svg)](https://github.com/nogibjj/ContinuousIntegrationusingGitHubActionsofPythonDataScienceProject/actions/workflows/test.yml)

---

**Summary**

This project demonstrates how to set up Continuous Integration (CI) using GitHub Actions for a Python-based Data Science project. This project serves as a reference for setting up Continuous Integration in Data Science projects, ensuring code quality and consistency. 

By implementing a CI/CD workflow, you can achieve the following benefits:

- **Automated Testing:** Ensure that your code is thoroughly tested before it gets deployed, reducing the likelihood of bugs or issues in production.

- **Streamlined Deployment:** Automate the deployment process, making it faster, more reliable, and consistent across different environments.

- **Code Quality Checks:** Enforce code quality standards and best practices, ensuring that your project maintains high standards of readability, maintainability, and performance.

- **Simplified Collaboration:** Facilitate seamless code sharing and transfer between team members and environments, making it easier to collaborate on projects.

With the option to develop in the cloud using GitHub Code Spaces, you can further enhance your productivity and eliminate the need for local setup and configuration.

---

**What is Code Spaces?**

GitHub Code Spaces provides cloud-hosted development environments for your repositories. It allows you to develop entirely in the cloud, eliminating the need for local setup and configuration.

---
**Project Structure**

- **Jupyter Notebook**:
  - Contains cells that perform descriptive statistics using Polars or Panda.
  - Validated using the nbval plugin for pytest.

- **Python Script**:
  - Executes the same descriptive statistics using Polars or Panda.

- **lib.py**:
  - Holds shared code used by both the script and the notebook.

- **Makefile**:
  - Executes four commands:
    - Run all tests (notebook, script, and lib)
    - Format code with Python black
    - Lint code with Ruff
    - Install dependencies via `pip install -r requirements.txt`

- **test_script.py**:
  - Contains tests for the script.

- **test_lib.py**:
  - Includes tests for the library.

- **Pinned requirements.txt**:
  - Specifies exact versions of dependencies.
