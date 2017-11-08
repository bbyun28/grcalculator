#### Case A: Multiple measurements per row

Necessary columns:

  + **cell_line** = name of the cell line used in the experiment
  + **treatment** = name of the treatment used in the experiment
  + **concentration** = concentration value (not log-transformed) of the treatment (all concentrations must be positive numbers)
  + **cell_count** = treated cell count (end of assay) - measure of cell number in the treated well at the end of the assay
  + **cell\_count\_\_ctrl** - control cell count (end of assay) - measure of cell number in the control well (e.g. untreated or DMSO-treated) from the same plate at the end of the assay

You may use a surrogate of cell number (such as CellTiter-Glo® staining) for the 'cell counts'.

You may include additional columns to be used for grouping the dose-response experiments.

When your file is uploaded, another popup will open in which you can type the division times for the cell lines used as well as the assay duration.
