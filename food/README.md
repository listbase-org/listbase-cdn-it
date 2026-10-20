# Cibo (Food & Nutrition)

1 datasets — 1,974 records

> Browse at [listbase.org/it/food/](https://listbase.org/it/food/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Ristoranti della Guida Michelin in Italia](it-ristoranti-michelin.json) | 1,974 | 2182 KB | [CSV](it-ristoranti-michelin_IT.csv) | [Excel](it-ristoranti-michelin_IT.xlsx) | [View](https://listbase.org/it/food/it-ristoranti-michelin/) |

## Quick Start

```bash
# List all food & nutrition datasets
curl https://cdn.it.listbase.org/index.json | jq '.datasets[] | select(.category=="food") | .id'

# Fetch a dataset
curl https://cdn.it.listbase.org/food/it-ristoranti-michelin.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/it/food/)
