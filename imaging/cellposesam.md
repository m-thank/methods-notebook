# CellposeSAM v4

## Summary
Segmentation of VisiumHD DAPI lymph node data (`dapi_gray.tif`, 3229×4285, 16-bit grayscale) using CellposeSAM v4, run on a GPU node.

## Why to Use
_SAM-backed segmentation — fill in what advantage this gave over Cellpose 3 / StarDist for this dataset._

## When to Use
_When this was the preferred choice in your comparison — final pipeline tool?_

## How to Use
```
# environment setup — conda/pip commands & versions used, GPU node requirements
```
```
# command / code used to run CellposeSAM v4
```
- Input: `dapi_gray.tif` (3229×4285, 16-bit grayscale)
- Preprocessing: Gaussian blur + CLAHE
- Run on: GPU node (SLURM job — see `hpc-cluster.md`)
- Tile size comparisons run: _fill in tile sizes tested and results/tradeoffs_

## Quirks / Gotchas
- **`cell_id_offset` bug**: was snowballing across tiles/batches — fixed by _fill in the fix_
- **uint16 dtype overflow**: hit during _fill in where_ — fixed by _fill in fix_
- **Slow filtering loop**: replaced with a lookup table for speed — fill in what was being filtered and the LUT approach

## Output Interpretation
- _What the output labels/files represent._
- Evaluated using custom **Cf/P metric** — see `cfp-metric.md`
