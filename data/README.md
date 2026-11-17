# Dataset files

This folder contains the two source tables and their merged version.

| File | Rows | Columns | Purpose |
|---|---:|---:|---|
| `vehicle_info.csv` | 4,340 | 9 | Vehicle attributes |
| `vehicle_sales.csv` | 4,340 | 5 | Selling price and usage attributes |
| `Cars_info.csv` | 4,340 | 13 | Combined dataset for Python notebooks |

The tables are joined using `vehicle_uid` (one-to-one match). `Cars_info.csv` is the merged output used by the notebooks.

Keep these files in this folder so the notebooks' relative paths work when Jupyter is started from the repository root.
