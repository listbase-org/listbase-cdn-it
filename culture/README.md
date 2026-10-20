# Cultura e religione (Culture & Religion)

2 datasets — 1,811 records

> Browse at [listbase.org/it/culture/](https://listbase.org/it/culture/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Musei in Italia (Museums in Italy)](it-musei.json) | 1,756 | 376 KB | [CSV](it-musei_IT.csv) | [Excel](it-musei_IT.xlsx) | [View](https://listbase.org/it/culture/it-musei/) |
| [Patrimoni mondiali dell'UNESCO in Italia](it-patrimonio-mondiale-unesco.json) | 55 | 57 KB | [CSV](it-patrimonio-mondiale-unesco_IT.csv) | [Excel](it-patrimonio-mondiale-unesco_IT.xlsx) | [View](https://listbase.org/it/culture/it-patrimonio-mondiale-unesco/) |

## Quick Start

```bash
# List all culture & religion datasets
curl https://cdn.it.listbase.org/index.json | jq '.datasets[] | select(.category=="culture") | .id'

# Fetch a dataset
curl https://cdn.it.listbase.org/culture/it-musei.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/it/culture/)
