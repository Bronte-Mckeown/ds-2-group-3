# Group Assignment: Data Science Project (Group 3)

## Repository Rules and Guidelines

Welcome to the repository for our group assignment! To ensure smooth collaboration and maintain the quality of our work, please adhere to the following rules and guidelines.

### 1. Repository Structure

- **data/**: Contains datasets used for the project.
- **notebooks/**: Jupyter notebooks.
- **scripts/**: Python scripts.
- **results/**: Output files, including models, evaluation metrics, and visualizations.
- **docs/**: Documentation related to the project.
- **submission/**: Where we will upload final documents for submission (i.e., report).
- **README.md**: Overview of the project and guidelines (this file).

### 2. Branching Strategy

- **main**: The main branch should always be in a stable state.
- **feature/**: For new features. Each feature should have its own branch (e.g., `feature/data-cleaning`).
- **bugfix/**: For fixing bugs.
- **docs/**: For documentation updates.

### 3. Commit Messages

- Write clear and concise commit messages.
- Try to follow the convention: `Type: Short Description (fixes issue# if applicable)`
  - **Types**: `feat` (new feature), `fix` (bug fix), `docs` (documentation), `style` (formatting), `refactor` (code restructuring), `test` (adding tests), `chore` (miscellaneous).

### 4. Code Quality

- Follow PEP 8 guidelines for Python code.
- Include comments and docstrings to explain code functionality.
- Use meaningful variable and function names.
- Apply DRY principle (Do Not Repeat Yourself).

### 5. Data Management

- **data/raw/**: Contains raw, unprocessed data obtained directly from the sources.
- **data/processed/**: Contains data that has been cleaned and processed.
- Include information on the sources of the datasets, in this [source.md](data/source.md) file.
- Include information on the steps and transformations applied to the raw data, in this [derivation.md](data/derivation.md) file.

### 6. Pull Requests

- Create a pull request (PR) for all changes.
- Include a clear description of the changes made.
- Request at least one team member to review the PR.
- Address review comments and make necessary changes before merging.

### 7. Issue Tracking

- Use GitHub Issues to track tasks, enhancements, and bugs.
- Provide a clear description and label the issue appropriately (e.g., `enhancement`, `bug`, `question`).

### 8. Collaboration

- Regularly update your local branch with the latest changes from the `main` branch.
- Attend scheduled meetings and participate actively in discussions.
- Check Slack regularly.
- Stick to commitments and let team members know in advance if you are strugling.

### 9. Documentation

- Maintain up-to-date documentation in the `docs/` directory.
- Document key decisions, workflows, and methodologies.
- Include instructions for running scripts and reproducing results.
- We can then use all this info in final report.

### 10. Environment Setup

- Use a virtual environment to manage dependencies.
- Provide a `requirements.txt` file for installing dependencies.
- Include setup instructions in the README associated with your code.

