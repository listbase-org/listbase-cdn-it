# Turismo (Tourism)

4 datasets — 204 records

> Browse at [listbase.org/it/tourism/](https://listbase.org/it/tourism/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Comuni delle Dolomiti UNESCO (Municipalities of the UNESCO Dolomites)](it-comuni-dolomiti-unesco.json) | 102 | 24 KB | [CSV](it-comuni-dolomiti-unesco_IT.csv) | [Excel](it-comuni-dolomiti-unesco_IT.xlsx) | [View](https://listbase.org/it/tourism/it-comuni-dolomiti-unesco/) |
| [Comuni delle Dolomiti UNESCO in Trentino-Alto Adige (UNESCO Dolomites municipalities in Trentino-Alto Adige)](it-trentino-alto-adige-comuni-dolomiti-unesco.json) | 48 | 12 KB | [CSV](it-trentino-alto-adige-comuni-dolomiti-unesco_IT.csv) | [Excel](it-trentino-alto-adige-comuni-dolomiti-unesco_IT.xlsx) | [View](https://listbase.org/it/tourism/it-trentino-alto-adige-comuni-dolomiti-unesco/) |
| [Comuni delle Dolomiti UNESCO in Veneto (UNESCO Dolomites municipalities in Veneto)](it-veneto-comuni-dolomiti-unesco.json) | 43 | 11 KB | [CSV](it-veneto-comuni-dolomiti-unesco_IT.csv) | [Excel](it-veneto-comuni-dolomiti-unesco_IT.xlsx) | [View](https://listbase.org/it/tourism/it-veneto-comuni-dolomiti-unesco/) |
| [Comuni delle Dolomiti UNESCO in Friuli-Venezia Giulia (UNESCO Dolomites municipalities in Friuli-Venezia Giulia)](it-friuli-venezia-giulia-comuni-dolomiti-unesco.json) | 11 | 5 KB | [CSV](it-friuli-venezia-giulia-comuni-dolomiti-unesco_IT.csv) | [Excel](it-friuli-venezia-giulia-comuni-dolomiti-unesco_IT.xlsx) | [View](https://listbase.org/it/tourism/it-friuli-venezia-giulia-comuni-dolomiti-unesco/) |

## Quick Start

```bash
# List all tourism datasets
curl https://cdn.it.listbase.org/index.json | jq '.datasets[] | select(.category=="tourism") | .id'

# Fetch a dataset
curl https://cdn.it.listbase.org/tourism/it-comuni-dolomiti-unesco.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/it/tourism/)
