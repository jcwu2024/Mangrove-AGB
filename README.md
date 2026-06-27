# Code and data associated with the manuscript: **Sea-level rise constrains the carbon permanence of global mangrove restoration**

The global mangrove aboveground biomass product and compiled field-observation dataset are available on Zenodo:

- `global_mangrove_agb.tif`: https://zenodo.org/records/15382912
- `Mangrove_AGB_MetaData.xlsx`: https://zenodo.org/records/15382912/files/Mangrove_AGB_MetaData.xlsx?download=1

## Layout

```text
code/figures_ms/          Main-text figure notebooks
code/figures_si/          Supplementary figure notebooks
data/main_figures/        Processed data used by the main-text figure notebooks
data/supplementary_figures/ Processed data used by the supplementary figure notebooks
figures/main_text/        Rendered main-text figure images
figures/supplementary/    Rendered supplementary figure images
```

## Main Figures

The notebooks in `code/figures_ms/` use relative paths to the processed files in `data/main_figures/`.

| Figure | Notebook | Rendered figure |
| --- | --- | --- |
| Fig. 1 | `code/figures_ms/fig01_machine_learning_agb.ipynb` | `figures/main_text/fig01_machine_learning_agb.png` |
| Fig. 2 | `code/figures_ms/fig02_future_change.ipynb` | `figures/main_text/fig02_future_change.png` |
| Fig. 3 | `code/figures_ms/fig03_change_distribution.ipynb` | `figures/main_text/fig03_change_distribution.png` |
| Fig. 4 | `code/figures_ms/fig04_country_change.ipynb` | `figures/main_text/fig04_country_change.png` |

To open the notebooks:

```bash
cd code/figures_ms
jupyter notebook
```

## Supplementary Figures

Supplementary figure notebooks are in `code/figures_si/`, with processed inputs in `data/supplementary_figures/`. Rendered images are in `figures/supplementary/` and are named in manuscript order.

## Citation

Please cite the paper and the Zenodo record when using the data product or code.
