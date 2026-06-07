# DFRWS Review 2026

This repository contains the data, figures, and analysis scripts supporting our systematic review of 544 publications from the Digital Forensic Research Workshop (DFRWS) conference series (2002–2025).

## Repository Contents

### Data

| File | Description |
|--------|-------------|
| `classification_framework_final.csv` | Complete classification data used in the study, including categories, subcategories, themes/objects, and tags/indicators. |
| `venue_category_matrix.csv` | Category distribution across DFRWS venues. |
| `top15_subcategories_over_time.csv` | Longitudinal trends for the most frequently occurring subcategories. |
| `top10_country_category_percent.csv` | Country-level category specialization data used for comparative analysis. |
| `heatmap_top15_subcategories.csv` | Processed data used for subcategory heatmap visualization. |
| `heatmap_top15_subcategories_long.csv` | Long-format version of the subcategory heatmap data. |

### Figures

| File | Description |
|--------|-------------|
| `network_collaboration.pdf` | Author collaboration network used in the community structure analysis. |
| `authors_network.pdf` | Author affiliation and collaboration visualization. |

### Analysis Scripts

| File | Description |
|--------|-------------|
| `analysis_script.ipynb` | Main analysis notebook used to generate statistics, figures, and tables reported in the paper. |
| `r_code_country_heatmap.txt` | R code used to generate country-level category heatmaps. |
| `r_code_subcategory_heatmap.txt` | R code used to generate subcategory heatmaps. |

## Study Overview

The study examines the evolution of digital forensics research across the DFRWS conference series between 2002 and 2025. Contributions include:

- A digital forensics classification framework.
- Longitudinal analysis of research themes categories and sub-categories.
- Country-level specialization analysis.
- Community and collaboration network analysis.
- Examination of digital forensic tool creation, adoption, accessibility, licensing, and sustainability.

## Reproducibility

All datas and scripts required to reproduce the analyses reported in the paper are included in this repository.

## Citation

If you use this data, framework, or supporting materials, please cite:

```bibtex
[Citation will be added upon publication]
```

## License

This repository is released for academic and research purposes.
