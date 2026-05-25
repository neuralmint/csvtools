# csvtools

CSV utilities for the terminal. View, filter, clean, and convert CSV files with zero dependencies.

## Install

```bash
curl -L https://raw.githubusercontent.com/neuralmint/csvtools/main/csvtools -o /usr/local/bin/csvtools
chmod +x /usr/local/bin/csvtools
```

## Usage

```
csvtools view <file>         Pretty-print CSV in a table
csvtools head <file> [n]     First n rows (default 10)
csvtools cols <file>         List column names with types
csvtools filter <f> <c> <v>  Filter rows where column = value
csvtools stats <file>        Numeric column statistics
csvtools to-json <file>      Convert to JSON
csvtools to-md <file>        Convert to Markdown table
csvtools clean <file>        Remove empty rows
```

## Requirements

- Python 3.6+
- No external dependencies

## License

MIT

---

**Donations:** `bc1q6ud0w3036ye2vfzkftwywarqswqu3jehs4nqe7` (BTC)
