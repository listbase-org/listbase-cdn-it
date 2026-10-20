# Tecnologia (Technology)

3 datasets — 1,393 records

> Browse at [listbase.org/it/tech/](https://listbase.org/it/tech/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Biblioteche in Italia](it-biblioteche.json) | 1,063 | 327 KB | [CSV](it-biblioteche_IT.csv) | [Excel](it-biblioteche_IT.xlsx) | [View](https://listbase.org/it/tech/it-biblioteche/) |
| [Aziende remote-friendly — settore Cloud & Software (Cloud & Software sector)](it-aziende-remote-cloud-software.json) | 305 | 124 KB | [CSV](it-aziende-remote-cloud-software_IT.csv) | [Excel](it-aziende-remote-cloud-software_IT.xlsx) | [View](https://listbase.org/it/tech/it-aziende-remote-cloud-software/) |
| [Comuni della provincia di Gorizia](it-gorizia-comuni.json) | 25 | 10 KB | [CSV](it-gorizia-comuni_IT.csv) | [Excel](it-gorizia-comuni_IT.xlsx) | [View](https://listbase.org/it/tech/it-gorizia-comuni/) |

## Quick Start

```bash
# List all technology datasets
curl https://cdn.it.listbase.org/index.json | jq '.datasets[] | select(.category=="tech") | .id'

# Fetch a dataset
curl https://cdn.it.listbase.org/tech/it-biblioteche.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/it/tech/)
