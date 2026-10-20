# ListBase CDN — Italiano (it)

Open dataset collection for **Italiano** (Italian).
443 datasets across 12 categories with 135,120 total records.

> Browse and download at [https://listbase.org/it/](https://listbase.org/it/)

## Categories

| Category | Datasets |
|----------|----------|
| [Cultura e religione (Culture & Religion)](culture/) | 2 |
| [Istruzione (Education)](education/) | 1 |
| [Intrattenimento (Entertainment)](entertainment/) | 1 |
| [Ambiente (Environment)](environment/) | 2 |
| [Cibo (Food & Nutrition)](food/) | 1 |
| [Geografia (Geography)](geography/) | 10 |
| [Lingua (Language)](language/) | 2 |
| [Riferimento (Reference)](reference/) | 381 |
| [Sport (Sports)](sports/) | 14 |
| [Tecnologia (Technology)](tech/) | 3 |
| [Turismo (Tourism)](tourism/) | 4 |
| [Trasporto (Transport)](transport/) | 22 |

## Usage

### Browse on the web
Visit [listbase.org/it/](https://listbase.org/it/) to search, preview, and download in Excel, CSV, or PDF.

### Fetch via CDN
```bash
# Dataset index (metadata only)
curl https://cdn.it.listbase.org/index.json

# Full dataset (JSON)
curl https://cdn.it.listbase.org/geography/th-central-provinces.json

# Download as Excel or CSV
curl -O https://cdn.it.listbase.org/geography/th-central-provinces_IT.xlsx
curl -O https://cdn.it.listbase.org/geography/th-central-provinces_IT.csv

# Build dump (metadata + sample rows, gzipped)
curl https://cdn.it.listbase.org/dump.json.gz | gunzip
```

### Use in JavaScript
```js
const res = await fetch('https://cdn.it.listbase.org/geography/th-central-provinces.json');
const data = await res.json();
console.log(data.name);    // "ภาคกลาง — จังหวัดในภาคกลาง"
console.log(data.rows);    // [{ ... }, ...]
```

## File Structure

```
├── index.json              # Dataset index (metadata + file info)
├── dump.json.gz            # Build dump (metadata + 20 sample rows per dataset)
├── {category}/
│   ├── README.md           # Category overview
│   ├── {dataset}.json      # Full dataset with rows
│   ├── {dataset}_IT.csv   # CSV download
│   └── {dataset}_IT.xlsx  # Excel download
```

## Dataset JSON Format

Each `.json` file contains:

| Field | Description |
|-------|-------------|
| `id` | Unique dataset identifier |
| `name` | Dataset name |
| `description` | What this dataset contains |
| `category` | Category (e.g. geography, finance) |
| `source` | Data source attribution |
| `updated` | Last updated date |
| `record_count` | Number of records |
| `columns` | Column definitions (key, label, type) |
| `rows` | Array of data records |

## License

Data is provided under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
See individual dataset `source` fields for original data attribution.

---

Part of [ListBase](https://listbase.org) — Free Reference Tables & Lists
