# TC Acoustic — Retail Distribution Audits

Audit, tracking, and reporting tools for TC Acoustic retail distribution across **Singapore, Malaysia, Hong Kong, and Thailand** — covering **Sonos**, **Marshall**, and **Bowers & Wilkins** at retailers including Harvey Norman, Best Denki, Challenger, Powerbuy, Dotlife, and others.

🥇 Goal: bring every store-brand pair to Gold standard (≥90% audit score).

## 🔗 Live tools

👉 **[Open the home page](https://tcacousticrtm.github.io/Retail-Distribution-Audits/)**

| Tool | Audience | Purpose |
| --- | --- | --- |
| [Audit Dashboard](https://tcacousticrtm.github.io/Retail-Distribution-Audits/TC_Retail_Distribution_Store_Audit_Dashboard.html) | Manager | View all audits, track Gold KPIs, send CM reports |
| [Audit Scorecard](https://tcacousticrtm.github.io/Retail-Distribution-Audits/Retail_Distribution_Audit_Scorecard.html) | CM | In-store audit submission with section-level scoring + notes |
| [TC Direct Store Audits](https://tcacousticrtm.github.io/TC-Direct-Store-Audits/) | Manager | Separate audit tool for TC Direct stores |
| [CM Photo Upload](https://tcacousticrtm.github.io/Retail-Distribution-Audits/CM_Photo_Upload%20%281%29.html) | CM | Weekly photo submissions by section |
| [Setup Guide](https://tcacousticrtm.github.io/Retail-Distribution-Audits/Google_Sheet_Setup_Guide.html) | Admin | Google Sheet + Apps Script setup reference |

## 📁 Repository structure

```
index.html                                       — Landing page
TC_Retail_Distribution_Store_Audit_Dashboard.html — Manager dashboard
Retail_Distribution_Audit_Scorecard.html         — CM in-store scorecard
CM_Photo_Upload (1).html                         — Photo upload tool
Google_Sheet_Setup_Guide.html                    — Setup reference
README.md                                        — This file
```

## ⚙️ Backend

- **Data:** Google Sheets (Raw Data, CM Contacts, country tabs, per-CM tabs)
- **Submissions & reports:** Google Apps Script web app
- **Notifications:** Telegram bot (`@tcretailaudit_bot`) — weekly, monthly, and on-demand audit reports grouped by Channel → Store → Brand
- **Photo storage:** Google Drive (auto-organized by country / year / week / section)

## 🏆 Scoring framework

Audits are scored across six sections (A–F) on the **Retail Distribution Audit Scorecard v3** framework with tier-based weighting:

- **Gold:** ≥90%
- **A / B / C / D / E:** progressively lower bands
- **Tier 1 / 2 / 3** stores have different Gold-coverage targets (70% / 40% / 20%)

## 🛠 Maintenance

Files are versioned via Git history — old versions remain recoverable through `git log` without cluttering the active filename. To update a tool, replace the file at its existing path. The URL stays the same; CMs don't need to update bookmarks.

---

_Maintained by Sylvia · TC Acoustic Retail Marketing_
