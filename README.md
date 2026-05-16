# Gateway Report - Boomerang Sensor Analyzer

Static browser app for reviewing gateway, boomerang, GPS, RSSI, and wagon health data.

## Use

Open the GitHub Pages URL, then use **Upload .xlsx / .csv** to load a gateway log export.

The app runs in the browser. Uploaded spreadsheet data is not sent to a server by this app.

## Local Preview

```bash
python3 -m http.server 8765
```

Then open:

```text
http://localhost:8765/index.html
```

## Data Files

Spreadsheet files are intentionally ignored by git. Do not commit customer, railcar, gateway, or GPS data unless your organization has approved that data for the repository.
