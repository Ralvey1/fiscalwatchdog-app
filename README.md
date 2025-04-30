# Fiscal Watchdog  
A 990 Audit Analyzer for Nonprofit Oversight

Fiscal Watchdog is an open-source tool designed to scan nonprofit IRS Form 990 data and highlight financial red flags. It helps advocates, journalists, auditors, and community members hold nonprofit organizations accountable—especially those receiving public funding or administering critical programs like 340B.

Built by advocates, for advocates.

---

# Features

- Scan IRS 990 financials (PDF or data)
- Flag:
  - Miscellaneous expenses over 10%
  - Professional fees over 3% without disclosure
  - Supplies exceeding 25% of total expenses
  - 340B program misuse risks
  - Governance and audit conflicts
- Export an Excel audit report with red flags and suggested questions
- User-friendly desktop interface (Python-based GUI)
- Custom logo and brand options for local watchdog orgs

---

# How to Use

1. Download and install Python 3.11+
2. Install dependencies:
   ```bash
   pip install pandas openpyxl tkinter
