# Methods Notebook

Running log of tools, pipelines, and methods used across lab projects. Each file follows the same format: **Summary → Why to Use → When to Use → How to Use → Quirks/Gotchas → Output Interpretation**.

## [`imaging/`](./methods/imaging) — Cell Segmentation
- [`stardist.md`](./methods/imaging/stardist.md) — StarDist segmentation
- [`cellpose3.md`](./methods/imaging/cellpose3.md) — Cellpose 3
- [`cfp-metric.md`](./methods/imaging/cfp-metric.md) — Custom Cf/P segmentation quality metric
- [`cellposesam/`](./methods/imaging/cellposesam/) — CellposeSAM v4
  - [`cellposesam.md`](./methods/imaging/cellposesam/cellposesam.md) — overview, parameters, usage
  - [`tiling-issue.md`](./methods/imaging/cellposesam/tiling-issue.md) — fragmentation problem at tile boundaries
  - [`centroid-tiling.ipynb`](./methods/imaging/cellposesam/centroid-tiling.ipynb) — custom centroid-based tiling solution

## [`chromatin-architecture/`](./methods/chromatin-architecture) — Chromatin Loop Calling
- [`cloops2.md`](./methods/chromatin-architecture/cloops2.md) — cLoops2
- [`peakachu.md`](./methods/chromatin-architecture/peakachu.md) — Peakachu
- [`fithichip.md`](./methods/chromatin-architecture/fithichip.md) — FitHiChIP

## [`general-setup/`](./methods/general-setup) — Infrastructure
- [`hpc-cluster.ipynb`](./methods/general-setup/hpc-cluster.ipynb) — CRC cluster / SLURM / JupyterLab setup
- [`slurm-sbatch.md`](./methods/general-setup/slurm-sbatch.md) — sbatch scripts and job submission
- [`conda-envs.md`](./methods/general-setup/conda-envs.md) — conda environment management

## [`cs-fundamentals/`](./cs-fundamentals) — CS Fundamentals
- [`search-algorithms.ipynb`](./cs-fundamentals/search-algorithms.ipynb) — BFS, DFS, Dijkstra, A*, Greedy, IDS

## [`statistics/`](./statistics) — Statistical Methods
- [`hypothesis-testing.ipynb`](./statistics/hypothesis-testing.ipynb) — T-test, Fisher exact, p-value, q-value
- [`distributions.ipynb`][22] — Poisson, Negative Binomial, Gamma-Poisson
- [`multiple-testing.ipynb`](./statistics/multiple-testing.ipynb) — FWER, FDR, Benjamini-Hochberg

## [`rna-seq/`](./rna-seq) — RNA-seq & Expression Analysis
- [`normalization.ipynb`](./rna-seq/normalization.ipynb) — RPM, RPKM, TPM, FPKM, size factors
- [`differential-expression.ipynb`](./rna-seq/differential-expression.ipynb) — DESeq2, edgeR, limma-voom, Kallisto, Salmon
- [`pca.ipynb`](./cs-fundamentals/pca.ipynb) — math & projection
- [`sva.ipynb`](./cs-fundamentals/sva) — math & projection

## [`r/`](./r) — R Methods
- [`deseq2.Rmd`](./r/deseq2.Rmd) — DESeq2 differential expression
- [`edger.Rmd`](./r/edger.Rmd) — edgeR
- [`limma-voom.Rmd`](./r/limma-voom.Rmd) — limma-voom

## [`matlab/`](./matlab) — MATLAB
- [`basics.md`](./matlab/basics.md) — syntax notes, key differences from Python

## [`ai-ml/`](./methods/ai-ml) — AI/ML Tools
_Placeholder — to be filled in as new tools are added._

---
*Last updated: 2026-09-19*
[22]: ./statistics/distributions.ipynb
