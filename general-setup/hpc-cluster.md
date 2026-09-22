# CRC Cluster / SLURM / JupyterLab

## Summary
Infrastructure setup for running segmentation and loop-calling pipelines on the CRC HPC cluster.

## Why to Use
Needed for GPU-accelerated segmentation (CellposeSAM) and cluster-scale chromatin loop calling jobs too large/slow for local compute.

## When to Use
Any job requiring GPU access, SLURM job scheduling, or persistent JupyterLab sessions on shared cluster resources.

## How to Use
```
# JupyterLab root directory config — fill in
```
```
# SLURM job submission template — fill in (partition, GPU request, time limit, etc.)
```
```
# module load commands used for each tool's environment
```

## Quirks / Gotchas
- **SSH host key errors**: resolved by _fill in fix_
- **Module loading issues**: fill in which modules conflicted and how resolved
- **JupyterLab root directory**: fill in final working config

## Output Interpretation
N/A — infrastructure reference only.
