# AGENTS.md

## Repository overview

This repository is a collection of Python practice tasks for coursework. Each numbered folder such as `kadai_005/`, `kadai_007/`, `kadai_008/`, and `kadai_011/` contains a notebook for a specific assignment.

The root README is the main project-level overview: [README.md](README.md).

## Working conventions

- Prefer small, focused Python changes that match the assignment notebook style.
- Keep edits within the relevant `kadai_*` folder unless the task explicitly requires a new shared file.
- Treat notebooks as the primary deliverable. When adding code, prefer notebook-friendly Python that remains easy to read and run cell by cell.
- Do not introduce framework, package, or build tooling unless a task clearly requires it.
- Keep comments and explanations brief and educational.

## Validation

- There is no automated test suite in this repository by default.
- For Python code changes, validate with the smallest relevant command, such as running the affected notebook cells or checking syntax with `python -m py_compile` for any standalone `.py` files.
- If a notebook is changed, ensure the code still runs in order and does not depend on hidden state from earlier cells unless the exercise intentionally requires it.

## Agent guidance

- When responding to a task, first identify which `kadai_*` folder is involved.
- Preserve the learner-oriented structure and avoid unnecessary refactoring.
- If asked to solve a task, provide the answer in the notebook context, not by creating unrelated project scaffolding.
- Keep the final result aligned with the educational purpose of the repository: clear, correct, and easy to follow Python practice work.
