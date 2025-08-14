
# Python Environment

A Python environment is a separate and isolated workspace for Python projects. It allows you to manage dependencies, versions, and packages without conflicts across different projects.

## Why Use Python Environments?

Suppose you have two projects:
- `project1` uses FastAPI 1.4
- `project2` uses FastAPI 2.0

If FastAPI 2.0 is installed globally, `project1` may not work properly because it requires FastAPI 1.4. By using virtual environments, each project can have its own set of installed packages and dependencies, independent of what’s installed globally or in other environments.

## Benefits

- Isolates project dependencies
- Prevents version conflicts
- Simplifies package management

## Steps to Create a Python Environment (Windows)

1. **Open your VS Code terminal.**
2. **Create a new environment:**
	```powershell
	python -m venv environment_name
	```
3. **Activate the environment:**
	```powershell
	.\environment_name\Scripts\Activate.ps1
	```
	*(For Command Prompt, use: `environment_name\Scripts\activate.bat`)*
4. **Deactivate the environment:**
	```powershell
	deactivate
	```