# Intrattenimento (Entertainment)

1 datasets — 94 records

> Browse at [listbase.org/it/entertainment/](https://listbase.org/it/entertainment/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Comuni della provincia di Treviso](it-treviso-comuni.json) | 94 | 30 KB | [CSV](it-treviso-comuni_IT.csv) | [Excel](it-treviso-comuni_IT.xlsx) | [View](https://listbase.org/it/entertainment/it-treviso-comuni/) |

## Quick Start

```bash
# List all entertainment datasets
curl https://cdn.it.listbase.org/index.json | jq '.datasets[] | select(.category=="entertainment") | .id'

# Fetch a dataset
curl https://cdn.it.listbase.org/entertainment/it-treviso-comuni.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/it/entertainment/)
