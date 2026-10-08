# Font Changer Telegram Bot

Telegram bot that converts user text into many stylish Unicode font styles.

## Files
- `main.py` — bot entry point
- `requirements.txt` — Python dependency
- `Procfile` — worker command for supported deployment platforms
- `runtime.txt` — Python runtime
- `.gitignore` — excludes local/generated files

## Environment variable
Set:

`BOT_TOKEN=YOUR_BOTFATHER_TOKEN`

Do not put the bot token directly inside `main.py` or commit it to GitHub.

## Run locally
```bash
pip install -r requirements.txt
export BOT_TOKEN="YOUR_BOTFATHER_TOKEN"
python main.py
```

On Windows:
```powershell
$env:BOT_TOKEN="YOUR_BOTFATHER_TOKEN"
python main.py
```

## Deploy
Push this folder to GitHub, then deploy it as a background worker/service on your hosting platform and add `BOT_TOKEN` as an environment variable.
