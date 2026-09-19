# Methods Notebook

Running log of tools, pipelines, and methods used across lab projects. Each file follows the same format: **Summary → Why to Use → When to Use → How to Use → Quirks/Gotchas → Output Interpretation**.

## [`imaging/`](./imaging) — Cell Segmentation
- [`stardist.md`](./imaging/stardist.md) — StarDist segmentation
- [`cellpose3.md`](./imaging/cellpose3.md) — Cellpose 3
- [`cellposesam.md`](./imaging/cellposesam.md) — CellposeSAM v4
- [`cfp-metric.md`](./imaging/cfp-metric.md) — Custom Cf/P segmentation quality metric
- `custom tiling method (to be added)` — CellposeSAM add on

## [`chromatin-architecture/`](./chromatin-architecture) — Chromatin Loop Calling
- [`cloops2.md`](./chromatin-architecture/cloops2.md) — cLoops2
- [`peakachu.md`](./chromatin-architecture/peakachu.md) — Peakachu
- [`fithichip.md`](./chromatin-architecture/fithichip.md) — FitHiChIP

## [`general-setup/`](./general-setup) — Infrastructure
- [`hpc-cluster.ipynb`](./general-setup/hpc-cluster.ipynb) — CRC cluster / SLURM / JupyterLab setup
- [`slurm-sbatch.md`](./general-setup/slurm-sbatch.md) — sbatch scripts and job submission
- [`conda-envs.md`](./general-setup/conda-envs.md) — conda environment management

## [`cs-fundamentals/`](./cs-fundamentals) — CS Fundamentals
- [`search-algorithms.md`](./cs-fundamentals/search-algorithms.md) — BFS, DFS, Dijkstra, A*, Greedy, IDS
- [`pca.md`](./cs-fundamentals/pca.md) — math & projection

## [`statistics/`](./statistics) — Statistical Methods
- [`hypothesis-testing.md`](./statistics/hypothesis-testing.md) — T-test, Fisher exact, p-value, q-value
- [`distributions.md`](./statistics/distributions.md) — Poisson, Negative Binomial, Gamma-Poisson
- [`multiple-testing.md`](./statistics/multiple-testing.md) — FWER, FDR, Benjamini-Hochberg

## [`rna-seq/`](./rna-seq) — RNA-seq & Expression Analysis
- [`normalization.md`](./rna-seq/normalization.md) — RPM, RPKM, TPM, FPKM, size factors
- [`alignment.md`](./rna-seq/alignment.md) — Kallisto pseudoalignment vs quasi-mapping
- [`differential-expression.md`](./rna-seq/differential-expression.md) — DESeq2, edgeR, limma-voom

## [`r/`](./r) — R Methods
- [`deseq2.Rmd`](./r/deseq2.Rmd) — DESeq2 differential expression
- [`edger.Rmd`](./r/edger.Rmd) — edgeR
- [`limma-voom.Rmd`](./r/limma-voom.Rmd) — limma-voom

## [`matlab/`](./matlab) — MATLAB
- [`basics.md`](./matlab/basics.md) — syntax notes, key differences from Python

## [`ai-ml/`](./ai-ml) — AI/ML Tools
_Placeholder — to be filled in as new tools are added._

---
*Last updated: 2026-09-19*