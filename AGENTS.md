# AGENTS

## Purpose

`Jenga-Legal/` hosts static legal and policy pages such as privacy, terms, and data deletion information.

## Key Folders

- Repository root HTML files: deployable pages
- `icons/`: favicon and app icon assets
- `README.md`: minimal repo-level context

## Codex Rules

- Keep the repo static. Do not introduce a build system unless explicitly requested.
- Preserve public page URLs and filenames unless the task explicitly calls for a redirect or rename.
- Favor plain HTML, conservative asset changes, and deploy-safe edits.
- Do not assume app runtime dependencies from `Jenga/` or `Jenga_Mobile/`; this repo is intentionally standalone.
