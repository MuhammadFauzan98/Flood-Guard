# Flood-Guard

Flood-Guard is a lightweight Flask web application to monitor and report flood alerts, provide resources, and coordinate volunteers and NGOs.

## Features

- Web UI for viewing alerts and resources
- Simple user authentication pages (`login`, `register`)
- Map view and interactive scripts under `static/js`
- NGO and volunteer dashboards

## Requirements

- Python 3.10+ (tested)
- See `requirements.txt` for Python dependencies

## Installation (Windows)

1. Create a virtual environment and activate it:

```powershell
python -m venv venv
venv\Scripts\Activate.ps1  # PowerShell
# or
venv\Scripts\activate.bat   # cmd.exe
```

2. Install dependencies:

```powershell
pip install -r requirements.txt
```

## Running the app (development)

Option 1 — run directly:

```powershell
python app.py
```

Option 2 — using `flask` (if `FLASK_APP` is configured):

```powershell
set FLASK_APP=app.py
set FLASK_ENV=development
flask run
```

The app will be available at `http://127.0.0.1:5000/` by default.

## Project structure

- `app.py` — application entrypoint
- `database.py` — database helpers
- `requirements.txt` — Python dependencies
- `templates/` — HTML templates
- `static/` — CSS and JavaScript

## Notes & Next steps

- Add tests and CI for automated checks
- Consider adding a `Procfile` / Dockerfile for deployment

## License

This repository does not include a license file. Add one if you intend to publish or share widely.
