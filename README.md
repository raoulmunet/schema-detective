# Schema Detective

Infer a practical schema from CSV or JSON data directly in your browser.

## What it does

- Detects likely scalar types: integer, decimal, boolean, date, timestamp and string.
- Reports nulls, uniqueness and sample values.
- Suggests candidate key columns.
- Generates starter SQL DDL for Oracle, PostgreSQL, SQL Server and MySQL.

## Usage

Open `index.html` through GitHub Pages or any local static web server, paste or load sample data, then choose **Analyze schema**.

## Privacy

All analysis runs locally in the browser. Files are not uploaded to a server.

## Local run

```bash
python3 -m http.server 8765
```

Then open http://127.0.0.1:8765/.

## License

MIT
