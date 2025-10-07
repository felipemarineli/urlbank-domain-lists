# URLBank Domain Lists (Head & Tail)

This repository contains the normalized and deduplicated domain lists used in the *URLBank: Data-Driven URL Discovery via Temporal Link Graphs* (Industrial Track, ACM 2025) paper.

- `data/head.txt` — Head sources (`n=2,440`)
- `data/tail.txt` — Tail sources (`n=2,798`)

## Description
Each file lists one domain per line in plain UTF-8 text.  
Domains are normalized by:
- Removing `http://` or `https://` prefixes
- Stripping leading `www.`

These lists correspond to the *head* (high-value editorial) and *tail* (long-tail) segments used in the paper’s large-scale evaluation.

### License
This work is licensed under the Creative Commons Attribution–NonCommercial 4.0 International License (CC BY-NC 4.0).

### Citation
If you use these lists, please cite:

Marineli, F., Cetorelli, V., Crescenzi, V., Furche, T., and Guo, X. (2025).  
*URLBank: Data-Driven URL Discovery via Temporal Link Graphs.*  
Industrial Track, ACM. DOI: TBA.