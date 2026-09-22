# Peakachu

## Summary
Chromatin loop calling tool used as one arm of the loop-calling benchmark (alongside cLoops2 and FitHiChIP) on the CRC cluster.

## Why to Use
_What Peakachu offers vs. cLoops2/FitHiChIP — fill in based on your benchmarking rationale._

## When to Use
_Input data type it expects, when it was the right choice in the comparison._

## How to Use
```
# conda env setup (separate env from cloops2/fithichip)
conda create -n peakachu ...
```
```
# hic2cool conversion to .mcool
hic2cool convert ...
```
```
# Peakachu run command
```
- Current results: CD8 = 2013, Texh_Prog = 871, Texh_Term = 781

## Quirks / Gotchas
- **Requires `.mcool` input**: had to convert from Hi-C format via `hic2cool` first — fill in exact conversion command/flags used
- _Any other install/runtime quirks worth noting._

## Output Interpretation
- _What the output loop calls represent, how loop counts feed into the benchmarking table for Aaron._
