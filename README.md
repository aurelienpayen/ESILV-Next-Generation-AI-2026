# ESILV — Next Generation AI 2026

## Team Information

- **School:** ESILV
- **Course:** Next Generation AI
- **Subgroup:** To be confirmed
- **Team members:** To be confirmed

## Course Information

- **Topic 1:** Agent-based AI — Didier Parisot
- **Topic 2:** Symbolic AI — Philippe Bonnard
- **Student kit version:** `2026-10-18-students-1`

## Development Environment

- **Operating system:** Windows
- **Python version:** 3.13.16
- **Environment:** Python virtual environment (`.venv`)
- **Dependencies:** `requests`, `python-dotenv`

## Installation

From the `kit-td1` directory:

```powershell
py -3.13 -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install requests
```

API keys for Groq and OpenRouter must be configured as environment variables. Never commit API keys or local environment files.

## Preparation Verification

- Python environment configured
- Groq and OpenRouter API access verified
- Five required models successfully tested (5/5)
- Database integrity verified with `verify-data.py`

Verification commands:

```powershell
python verify-data.py
python check_access.py
```

The API access check was completed successfully on the earlier student kit. The updated kit's database integrity check also passed.

## Practical Sessions

- **TD 1:** Multi-model comparison and SQL evaluation
- **TD 2:** Voting and routing strategies
- **TD 3:** Cost analysis and AI system design

## Reports

Reports will be added after each session:

- `reports/td1.md`
- `reports/td2.md`
- `reports/td3.md`

## Reproducibility

All experiments, prompts, references, results and execution traces will be documented as the sessions progress.

The original SQLite database must remain unchanged.

## Academic Integrity

AI-assisted coding may be used with appropriate documentation. All results must be independently verified, and failed attempts must be retained.
