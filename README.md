# zip-api-python

VS Code workspace settings for this project are stored in `.vscode/settings.json`.

Important: Do not commit machine-specific paths (for example `python.defaultInterpreterPath`). Each contributor should set their own interpreter locally.

How contributors should configure Python
- Open VS Code Command Palette → `Python: Select Interpreter` and choose your environment.
- To avoid committing a local path, do not add `python.defaultInterpreterPath` to `.vscode/settings.json`.
- If you want a local project-only setting, keep it in a local workspace settings file that is ignored by git or set it in your user settings.

Example (DO NOT commit):
```json
{
  // "python.defaultInterpreterPath": "C:\\Users\\you\\AppData\\Local\\Programs\\Python\\Python39\\python.exe"
}
```

If you want to provide a reusable hint for contributors, add a section in this README with a project‑recommended interpreter name (not an absolute path), e.g.:
- Recommended interpreter: `python3.11` or `venv` (choose whatever your project uses)
