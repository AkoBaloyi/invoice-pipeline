# Logistics Invoice Extraction Pipeline

Python project that reads a dedicated Gmail test inbox, extracts invoice and purchase-order line items from PDF attachments, writes safe CSV outputs, and avoids duplicate processing.

## Team

- Ako
- Mandisa
- Moji

No work has been assigned yet. We will decide and record tasks together when the team is ready. Everyone reviews pull requests, writes tests for their own changes, and updates documentation.

## Quick start

1. Create and activate a virtual environment: `python -m venv .venv`
2. Install packages: `pip install -r requirements.txt`
3. Copy `.env.example` to `.env` and add only your own credentials.
4. Put your Google OAuth `credentials.json` in the project root. Never commit it.
5. Run tests: `pytest`

## Project reference checklist

The project brief's earlier-sprint milestones are reference material only. We are continuing this project in the current sprint and will agree the next work together.

## Git workflow

- Do not push directly to `main`.
- Use `feature/`, `fix/`, `docs/`, or `test/` branches.
- Every pull request needs one approval from a teammate.
- Never commit `.env`, OAuth credentials, tokens, real invoices, or real client data.
