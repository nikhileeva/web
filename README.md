# Web Application Testing

## Artifacts
- **Test Plan:** [Google Sheets](https://docs.google.com/spreadsheets/d/18Sy0gBUFcY_VxyVwmf29pFg8-IZw4F86RxDCtUiEk7g/edit?gid=0#gid=0)
- **Checklist:** [Google Sheets](https://docs.google.com/spreadsheets/d/1LSmyHlZGCR0kUfBhj7vCvJeBw1h3GnfdUmKkL1uQgMs/edit?gid=1595243412#gid=1595243412)
- **Test Cases:** [PDF (Qase export)](https://github.com/nikhileeva/web/blob/main/Web%20App%20Testing.pdf)
- **Defects Report:** [Excel](https://github.com/nikhileeva/web/blob/main/Defects%20report.xlsx)
- **Test Run:** [G101 — 2025-09-19 (PDF)](https://github.com/nikhileeva/web/blob/main/G101-Test%2Brun%2B2025_09_19.pdf)


## Charles Proxy Highlights

### Desktop (demoshopping.ru)
- **Rewrite Body:** `GET /getCart`: `quantity: 2` → `quantity: 500`return `quantity/count = 500`.
- **Rewrite Status (prod only):** `200 OK` → `403 Forbidden` for `demoshopping.ru`; other domains work normally.
- **Map Remote (env switch):** `https://demoshopping.ru/*` → `https://qa.demoshopping.ru/*`.

- **Video:** [Desktop (Google Drive)](https://drive.google.com/file/d/1Z43XVxYxUFmCHAI4N9iCwVlcpfLjAP-R/view?usp=sharing) 


