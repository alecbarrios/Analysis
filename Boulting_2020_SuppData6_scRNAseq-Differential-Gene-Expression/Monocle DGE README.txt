Boulting, et al. 2019, KM

DIFFERENTIAL GENE EXPRESSION WITH MONOCLE
Monocle Package Version 2.6.4

For each Seurat cluster and time point, significantly upregulated and downregulated gene expression were calculated.
Fold changes were calculated as gene expression at time point (1hr, 2hr, or 4hr) over gene expression at time point 0hr.
Fold change cutoff was 1.5.
Percentage of cells (of both groups being compared combined e.g. cluster i timepoint x vs. cluster i timepoint 0hr) cutoff was 1%.
That is, a gene must be expressed in at least 1% of the cells of the combined two comparison groups.
q-val cutoff was 0.05.

Files ending in "inducible" include only genes whose expression levels were upregulated at least 1.5-fold after stimulation.
Files ending in "decreasing" include only genes whose expression levels were downregulated at least 1.5-fold after stimulation.
Files ending in "all" include both genes whose expression levels were upregulated and genes whose expression levels were downregulated at least 1.5-fold after stimulation.

