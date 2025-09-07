# zap-security-actions
# ZAP Security Actions

[![ZAP Full Scan Single Random URL](https://github.com/incyi/zap-security-actions/actions/workflows/zap-security-scan.yml/badge.svg)](https://github.com/incyi/zap-security-actions/actions/workflows/zap-security-scan.yml)

This repository contains a **GitHub Actions workflow** to perform a **full OWASP ZAP scan** on a random URL from a list, generate a report, and upload it as an artifact.

---

## Features

- Automatically selects a **random URL** from `data/list.csv`.
- Supports **custom ZAP rules** via `.zap/rules.json`.
- Generates **HTML reports** (`zap-full-report.html`) for each run.
- Optional GitHub issue creation from ZAP findings.
- Works with **submodules** (or normal folders) containing URLs.
- Unique artifact names for each run to prevent overwriting.

---

## Workflow Details

The workflow file is located at:

