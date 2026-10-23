# Before publishing

This upload bundle contains the files supplied for the project: README, Online Retail II dataset archive, business requirements document, prerequisite installation guide, dashboard PDF preview, dashboard images, and Power BI theme JSON.

The editable Power BI `.pbix` report, SQL scripts, and Python notebook were not among the supplied files. Add them if available before describing this repository as fully reproducible. Suggested folders:

- `01_sql/` — ordered SQL scripts for import, cleaning, deduplication, and validation
- `02_python/` — RFM segmentation notebook and `requirements.txt`
- `03_powerbi/` — editable `.pbix` report

Check dataset licensing and attribution before publishing, and keep large derived exports out of Git unless they are necessary. Never commit credentials, tokens, or private customer data.
