# AGENTS.md

## Purpose

This repository is a learning-focused collection of Python notebooks for algorithms, data structures, and interview preparation. AI agents should help with educational code changes, notebook updates, and small exercises without disturbing the course structure or learning flow.

## Repository map

- [README.md](README.md): high-level course description.
- 01-Algorithm Analysis and Big O/ through 10-Mock Interviews/: chapter-based lesson folders.
- Topic folders like Linked Lists/, Riddles/, Mock Interviews/, and Stacks, Queues and Deques/ appear to be supporting or mirrored course material; preserve their intent unless a task explicitly targets them.
- Most work happens in Jupyter notebooks, not a packaged application.

## Working conventions

- Prefer notebook-safe Python that is easy to read and study.
- Keep examples small, self-contained, and aligned with the surrounding lesson.
- Preserve chapter organization, filenames, and lesson sequencing unless the user asks for a change.
- Avoid introducing framework conventions, app structure, build tooling, or package metadata that are not already present in the repo.
- Do not assume a standard project build, test suite, or deployment pipeline exists.

## Editing guidance

- Start from the notebook or exercise folder most closely related to the request.
- Use [README.md](README.md) for project context and chapter naming.
- Favor minimal, local edits over broad refactors or cross-chapter rewrites.
- If a notebook contains a solution and a practice version, keep them consistent with the educational intent of the lesson.
- When adding or fixing code, prefer clear algorithmic explanations and standard Python idioms over unnecessary abstraction.

## Validation

- This repo does not appear to include a standard Python project config or automated test suite.
- Validate with the smallest relevant check available, such as running the affected Python snippet or a focused notebook cell.
- If no runnable project test flow exists, state that clearly instead of inventing one.

## Good default behavior

- Treat this as an educational repository first and a codebase second.
- Keep changes instructional, reproducible, and easy to follow for learners.
- Ask for clarification when a request affects multiple notebooks, duplicates, or the course structure itself.
