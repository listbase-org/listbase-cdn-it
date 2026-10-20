# Lingua (Language)

2 datasets — 637 records

> Browse at [listbase.org/it/language/](https://listbase.org/it/language/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Lingue del mondo (591)](it-lingue.json) | 591 | 54 KB | [CSV](it-lingue_IT.csv) | [Excel](it-lingue_IT.xlsx) | [View](https://listbase.org/it/language/it-lingue/) |
| [Aziende remote-friendly — settore Marketing & Scrittura (Marketing & Scrittura sector)](it-aziende-remote-marketing-writing.json) | 46 | 20 KB | [CSV](it-aziende-remote-marketing-writing_IT.csv) | [Excel](it-aziende-remote-marketing-writing_IT.xlsx) | [View](https://listbase.org/it/language/it-aziende-remote-marketing-writing/) |

## Quick Start

```bash
# List all language datasets
curl https://cdn.it.listbase.org/index.json | jq '.datasets[] | select(.category=="language") | .id'

# Fetch a dataset
curl https://cdn.it.listbase.org/language/it-lingue.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/it/language/)
