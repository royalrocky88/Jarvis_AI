Jarvis_AI/
├── app/
│ ├── **init**.py
│ ├── main.py # Flask entry‑point
│ ├── telegram_bot.py # Telegram webhook handler
│ ├── whatsapp_bot.py # WhatsApp webhook handler
│ ├── task_router.py # Intent detection & action dispatch
│ ├── github_sync.py # Commit / push to GitHub
│ ├── logger.py # Write‑log → GitHub file
│ └── utils.py # Helper functions (URL encode, slugify …)
├── .github/
│ └── workflows/
│ └── ci.yml # GitHub Actions workflow
├── requirements.txt
├── .env.example
├── Dockerfile
└── run.sh # One‑liner to start the container
