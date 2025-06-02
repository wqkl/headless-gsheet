# headless-gsheet

A minimal static HTML page that fetches a published Google Sheet (CSV) and renders it as an HTML table.

## Usage

1. In your Google Sheet, go to **File → Publish to the web**, choose CSV format, and copy the `output=csv` URL.
2. Open `index.html` and replace the `CSV_URL` constant with your published CSV link.
3. Serve this folder (e.g. via `live-server`, `http-server`, or any static-site host).
4. Open `index.html` in your browser—your sheet data should appear in a table.
