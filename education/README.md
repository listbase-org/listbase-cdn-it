# Istruzione (Education)

1 datasets — 93 records

> Browse at [listbase.org/it/education/](https://listbase.org/it/education/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Italia — Università e istituti di istruzione superiore](it-universita.json) | 93 | 28 KB | [CSV](it-universita_IT.csv) | [Excel](it-universita_IT.xlsx) | [View](https://listbase.org/it/education/it-universita/) |

## Quick Start

```bash
# List all education datasets
curl https://cdn.it.listbase.org/index.json | jq '.datasets[] | select(.category=="education") | .id'

# Fetch a dataset
curl https://cdn.it.listbase.org/education/it-universita.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/it/education/)
