# Manuscript-aligned biopsy-resection notebooks

These five notebooks contain the analyses supporting the final revised paper.
Unrelated, superseded, and reviewer-only branches have been removed; alternative
visualizations of included analyses have generally been retained.

| Notebook | Retained code cells | Removed code cells |
| --- | ---: | ---: |
| `01_rnaseq_biopsy_resection_clean.ipynb` | 145 | 35 |
| `02_proteomics_biopsy_resection_clean.ipynb` | 166 | 12 |
| `03_phosphoproteomics_biopsy_resection_clean.ipynb` | 136 | 12 |
| `04_tumor_reference_pca_hoshida_clean.ipynb` | 104 | 39 |
| `05_nontumor_reference_pca_clean.ipynb` | 51 | 0 |

See `MANUSCRIPT_ALIGNMENT.md` for the figure map and an auditable removal log.
The supplied `sample_mapping_BvR.csv` is included unchanged.

## Rerun checklist

1. Restore the original relative directory layout and raw inputs documented at
   the top of each notebook.
2. Create `figures/` and `gct_files/` where required.
3. Use the original conda environment; record it with `conda env export` or
   `pip freeze` for the repository.
4. Restart the kernel and run each notebook from top to bottom.
5. Compare regenerated numerical tables and figures with the final submitted
   versions. Date-based filenames may change even when results are identical.

No numerical rerun was performed during cleanup because the raw data were not
available. Structural validation confirms that retained code and outputs are
unchanged.
