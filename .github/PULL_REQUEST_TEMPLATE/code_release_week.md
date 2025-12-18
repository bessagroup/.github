<!-- Code Release Week PR template (optional) -->

# Code Release Week Checklist

This checklist is intended to help reviewers evaluate code repositories during Code Release Week. Reviewers should go through each section and mark the corresponding checkboxes based on their assessment of the repository.

---

## Quality of GitHub repository `README.md` file

- [ ] **Is the content properly structured and does it contain the minimum expected sections: Summary, Statement of need, Authorship, Getting started, Community Support, License?**

- [ ] **Is the content grammatically well-written, clear, and easily understandable?**

- [ ] **Is the high-level functionality and purpose of the project clear for a diverse, non-specialist audience?**

- [ ] **Does it contain a clear statement of need that illustrates the purpose of the project?**

- [ ] **Does it contain a set of key references for the user/developer (e.g., paper, documentation, installation, benchmarks, tutorials)?**

---

## Project Structure and Files

- [ ] **Does the project include a `src/<project_name>` folder where the whole code is contained?**

- [ ] **Does the project include the `pyproject.toml` file?**

- [ ] **Does the project include the `LICENSE` file (with contents of an OSI approved license)?**

- [ ] **Does the project include the `MANIFEST.in` file?**

- [ ] **Does the project include a `.gitignore` file?**

- [ ] **Does the project include a `Makefile` with common targets such as `build`, `test`, `lint`, and `docs`?**

- [ ] **Does the project include a `docs/` documentation folder containing the required files to generate HTML documentation?**

---

## Code Quality

- [ ] **Is the code compliant with the Coding Fundamentals of the BRG Python Coding Style?**

- [ ] **Is the code compliant with the docstring format of the BRG Python Coding Style?**

- [ ] **Does the code include docstrings for all modules, functions, and classes?**

- [ ] **Does the code include comments explaining non-trivial code blocks?**

- [ ] **Does the code pass the Ruff check (compliance with BRG Python Coding Style)?**

---

## Documentation Quality

- [ ] **Can the documentation be successfully built?**

- [ ] **Is the content grammatically well-written, clear, and easily understandable?**

- [ ] **Is the high-level functionality and purpose of the project clear for a diverse, non-specialist audience?**

- [ ] **Does it contain a clear statement of need that illustrates the purpose of the project?**

- [ ] **Does it contain clear installation instructions that follow standard procedures?**

- [ ] **Does it include sufficient documentation to understand the core functionality of the code?**

- [ ] **Does it include an automatically generated API that contains the complete documentation of the code (modules, classes, functions)?**

---

## Benchmarks, Testing, and Distribution

- [ ] **Can the code be successfully installed by following the provided instructions?**

- [ ] **Does it include a simple example usage that illustrates how to use the code?**

- [ ] **Does the project include a set of benchmarks that cover the core functionality of the code?**

- [ ] **Does the project include a test suite?**

- [ ] **Can the Python package distribution be successfully built?**

- [ ] **(Optional if code is public) Can the Python package distribution be successfully installed from PyPI?**

---

## Group Presentation

- [ ] **Overall quality of the group presentation**  
  Each presentation has a maximum of 1h00m:
  - Part 1 – Short presentation (max 15 min): Context, Statement of Need, Method overview, Code purpose/audience/goals  
  - Part 2 – Code presentation (max 30 min): Illustrative benchmark, Code structure, Class diagram  
  - Part 3 – Feedback & Discussion (max 15 min): Priority order – Reviewer → Presenter → Open discussion
