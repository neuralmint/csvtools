<h1 align="center">📊 csvtools</h1>
<p align="center">
  <b>CSV utilities for the terminal — view, filter, clean, convert. Zero dependencies.</b>
</p>
<p align="center">
  <img src="https://img.shields.io/badge/python-3.6+-blue.svg">
  <img src="https://img.shields.io/badge/dependencies-zero-brightgreen.svg">
  <img src="https://img.shields.io/badge/license-MIT-green.svg">
</p>

## 🚀 Install

```bash
curl -L https://raw.githubusercontent.com/neuralmint/csvtools/main/csvtools -o /usr/local/bin/csvtools
chmod +x /usr/local/bin/csvtools
```

## 📋 Commands

| Command | Description |
|---------|-------------|
| `csvtools view <file>` | Pretty-print CSV as a table |
| `csvtools head <file> [n]` | Show first n rows (default 10) |
| `csvtools cols <file>` | List column names with inferred types |
| `csvtools filter <file> <col> <val>` | Filter rows where column = value |
| `csvtools stats <file>` | Numeric column statistics |
| `csvtools to-json <file>` | Convert CSV to JSON |
| `csvtools to-md <file>` | Convert to Markdown table |
| `csvtools clean <file>` | Remove empty rows |

## 💡 Example

```bash
csvtools view data.csv
csvtools filter data.csv status active
csvtools stats data.csv
```

## 💝 Donate

**BTC:** `bc1q6ud0w3036ye2vfzkftwywarqswqu3jehs4nqe7`
