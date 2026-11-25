# Logistics Invoice Extraction Pipeline

Python project that reads a dedicated Gmail test inbox, extracts invoice and purchase-order line items from PDF attachments, writes safe CSV outputs, and avoids duplicate processing.

## Team

- Ako - Sprint 1: Gmail and orchestration lead
- Mandisa - Sprint 1: Extraction lead
- Moji - Sprint 1: Data quality lead

Roles rotate each sprint. Everyone reviews at least two pull requests each week, writes tests for their own work, and updates documentation.

## Quick start

1. Create and activate a virtual environment: `python -m venv .venv`
2. Install packages: `pip install -r requirements.txt`
3. Copy `.env.example` to `.env` and add only your own credentials.
4. Put your Google OAuth `credentials.json` in the project root. Never commit it.
5. Run tests: `pytest`

## Sprint 1 scope

- Configure Gmail OAuth against a dedicated test account.
- List unread emails and find PDF attachments.
- Create the InvoiceBot Gmail labels when missing.
- Generate the first eight synthetic invoices.
- Open small pull requests using the template in `.github`.

## Git workflow

- Do not push directly to `main`.
- Use `feature/`, `fix/`, `docs/`, or `test/` branches.
- Every pull request needs one approval from a teammate.
- Never commit `.env`, OAuth credentials, tokens, real invoices, or real client data.
