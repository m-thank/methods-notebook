# StarDist

## Summary
_1-2 sentences: what StarDist does and what you used it for (VisiumHD DAPI lymph node segmentation)._

## Why to Use
_What StarDist is good at (e.g. star-convex shape assumption, good for round/nucleus-like objects) — fill in based on your comparison against Cellpose/CellposeSAM._

## When to Use
_What kind of data/image characteristics made you reach for StarDist over the other tools. Note if this was one arm of a segmentation tool comparison._

## How to Use
```
# environment setup — fill in conda/pip commands & versions used
```
```
# command / code used to run StarDist on dapi_gray.tif
```
- Input: `dapi_gray.tif` (3229×4285, 16-bit grayscale)
- Preprocessing applied: Gaussian blur + CLAHE
- Model/settings used: _fill in (pretrained model name, prob_thresh, nms_thresh, etc.)_

## Quirks / Gotchas
- _Fill in: any errors hit, format requirements, differences in output format vs Cellpose that mattered for downstream comparison._

## Output Interpretation
- _What the output labels/files represent, how you evaluated segmentation quality (Cf/P metric — see `cfp-metric.md`)._
