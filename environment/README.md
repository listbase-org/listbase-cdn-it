# Ambiente (Environment)

2 datasets — 1,143 records

> Browse at [listbase.org/it/environment/](https://listbase.org/it/environment/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Centrali elettriche in Italia](it-centrali-elettriche.json) | 1,139 | 597 KB | [CSV](it-centrali-elettriche_IT.csv) | [Excel](it-centrali-elettriche_IT.xlsx) | [View](https://listbase.org/it/environment/it-centrali-elettriche/) |
| [Centrali nucleari in Italia](it-centrali-nucleari.json) | 4 | 5 KB | [CSV](it-centrali-nucleari_IT.csv) | [Excel](it-centrali-nucleari_IT.xlsx) | [View](https://listbase.org/it/environment/it-centrali-nucleari/) |

## Quick Start

```bash
# List all environment datasets
curl https://cdn.it.listbase.org/index.json | jq '.datasets[] | select(.category=="environment") | .id'

# Fetch a dataset
curl https://cdn.it.listbase.org/environment/it-centrali-elettriche.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/it/environment/)
