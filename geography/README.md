# Geografia (Geography)

10 datasets — 14,493 records

> Browse at [listbase.org/it/geography/](https://listbase.org/it/geography/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Comuni italiani (Municipalities of Italy)](it-comuni.json) | 7,904 | 2388 KB | [CSV](it-comuni_IT.csv) | [Excel](it-comuni_IT.xlsx) | [View](https://listbase.org/it/geography/it-comuni/) |
| [Stazioni ferroviarie d'Italia](it-stazioni-ferroviarie.json) | 5,073 | 2067 KB | [CSV](it-stazioni-ferroviarie_IT.csv) | [Excel](it-stazioni-ferroviarie_IT.xlsx) | [View](https://listbase.org/it/geography/it-stazioni-ferroviarie/) |
| [Laghi in Italia](it-laghi.json) | 576 | 144 KB | [CSV](it-laghi_IT.csv) | [Excel](it-laghi_IT.xlsx) | [View](https://listbase.org/it/geography/it-laghi/) |
| [Isole in Italia](it-isole.json) | 537 | 132 KB | [CSV](it-isole_IT.csv) | [Excel](it-isole_IT.xlsx) | [View](https://listbase.org/it/geography/it-isole/) |
| [Cascate e rapide in Italia](it-cascate.json) | 140 | 95 KB | [CSV](it-cascate_IT.csv) | [Excel](it-cascate_IT.xlsx) | [View](https://listbase.org/it/geography/it-cascate/) |
| [Province d'Italia (Provinces of Italy)](it-province.json) | 107 | 29 KB | [CSV](it-province_IT.csv) | [Excel](it-province_IT.xlsx) | [View](https://listbase.org/it/geography/it-province/) |
| [It Cognomi](it-cognomi.json) | 100 | 17 KB | [CSV](it-cognomi_IT.csv) | [Excel](it-cognomi_IT.xlsx) | [View](https://listbase.org/it/geography/it-cognomi/) |
| [It Nomi](it-nomi.json) | 20 | 4 KB | [CSV](it-nomi_IT.csv) | [Excel](it-nomi_IT.xlsx) | [View](https://listbase.org/it/geography/it-nomi/) |
| [Regioni d'Italia (Regions of Italy)](it-regioni.json) | 20 | 8 KB | [CSV](it-regioni_IT.csv) | [Excel](it-regioni_IT.xlsx) | [View](https://listbase.org/it/geography/it-regioni/) |
| [Vulcani in Italia](it-vulcani.json) | 16 | 5 KB | [CSV](it-vulcani_IT.csv) | [Excel](it-vulcani_IT.xlsx) | [View](https://listbase.org/it/geography/it-vulcani/) |

## Quick Start

```bash
# List all geography datasets
curl https://cdn.it.listbase.org/index.json | jq '.datasets[] | select(.category=="geography") | .id'

# Fetch a dataset
curl https://cdn.it.listbase.org/geography/it-comuni.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/it/geography/)
