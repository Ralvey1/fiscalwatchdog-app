#  Fiscal Watchdog  
**A 990 Audit Analyzer for Nonprofit Oversight**

**Fiscal Watchdog** is an open-source tool that scans IRS Form 990 filings (PDF or XML) to detect financial red flags. Designed for community watchdogs, journalists, auditors, and advocates—especially in sectors like HIV care, healthcare access, and 340B oversight.

>  Built by advocates, for advocates.  
>  Rooted in transparency, equity, and public accountability.

---

##  Features

- 🔍 Scan IRS 990 financials (PDFs, OCR, or XML)
-  Auto-detect and flag:
  -  Miscellaneous expenses >10%
  -  Professional fees >3% (without details)
  -  Supplies >25% of expenses
  -  Cell phone cost per employee >$450
  -  Excessive admin costs or salaries
  -  340B program misuse risks (via pattern alerting)
  -  Governance conflicts and repeat vendor overlap
-  Calculate:
  - Clients per employee
  - Cost per employee
  - Admin cost per employee
  - Salary per client served
-  Accept folder input or pick individual PDFs
-  Generate Excel reports with flags + recommendations
-  Cross-platform GUI (Windows + macOS)
-  Custom brand/logo support for local watchdogs

---

## How to Use

### 1. Install Python 3.11+
[https://www.python.org/downloads/](https://www.python.org/downloads/)

### 2. Install dependencies
```bash
pip install pandas openpyxl pymupdf pytesseract Pillow
