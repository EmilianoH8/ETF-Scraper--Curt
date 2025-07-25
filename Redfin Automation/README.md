# Redfin Automation\nAutomated land development prospecting system.

## Project Structure

```
redfin-automation/
│
├── n8n/                        # N8N workflow files (JSON, custom scripts)
├── playwright/                 # Playwright automation scripts
├── data/                       # Downloaded CSVs and processed data
│   ├── raw/
│   └── processed/
├── processing/                 # Node.js data processing scripts
├── config/                     # Config files (ZIP codes, size ranges, etc.)
├── logs/                       # Automation and processing logs
├── .env                        # Environment variables (API keys, etc.)
├── package.json
└── README.md
```

## Setup

1. Clone the repo and run `npm install`.
2. Use Playwright scripts in `playwright/` to automate Redfin downloads.
3. Process data with scripts in `processing/`.
4. Orchestrate with N8N workflows in `n8n/`.
