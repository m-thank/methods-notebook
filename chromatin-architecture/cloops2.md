# cLoops2

## Summary
Chromatin loop calling tool used as one arm of the loop-calling benchmark (alongside Peakachu and FitHiChIP) on the CRC cluster.

## Why to Use
_What cLoops2 offers vs. Peakachu/FitHiChIP — fill in based on your benchmarking rationale._

## When to Use
_Input data type it expects, when it was the right choice in the comparison._

## How to Use
```
# conda env setup (separate env from peakachu/fithichip)
conda create -n cloops2 ...
```
```
# HiC-Pro allValidPairs -> BEDPE conversion
```
```
# cLoops2 run command
```
- Current results: Texh_Prog = 2375, Texh_Term = 1707

## Quirks / Gotchas
- **Undocumented strand column requirement**: input BEDPE needs a strand column that isn't mentioned in the docs — fill in exact format expected
- **Hardcoded significance thresholds**: had to override defaults — fill in which parameter/flag and what value you used

## Output Interpretation
- _What the output loop calls represent, how loop counts feed into the benchmarking table for Aaron._
