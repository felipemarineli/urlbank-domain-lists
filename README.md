# URLBank Domain Lists (Head & Tail)

This repository contains the normalized and deduplicated domain lists used in the *URLBank: Data-Driven URL Discovery via Temporal Link Graphs* (Industrial Track, WWW 2026) paper.

- `data/head.txt` — Head sources (`n=2,440`)
- `data/tail.txt` — Tail sources (`n=2,798`)

## Description
Each file lists one domain per line in plain UTF-8 text.  
Domains are normalized by:
- Removing `http://` or `https://` prefixes
- Stripping leading `www.`

These lists correspond to the *head* (high-value editorial) and *tail* (long-tail) segments used in the paper’s large-scale evaluation.

## License
This work is licensed under the Creative Commons Attribution–NonCommercial 4.0 International License (CC BY-NC 4.0).

## Citation

If you use these lists, please cite:

> Felipe Marineli, Valerio Cetorelli, Valter Crescenzi, Tim Furche, and Xiaonan Guo. 2026.
> URLBank: Data-Driven URL Discovery via Temporal Link Graphs. In *Proceedings of the
> ACM Web Conference 2026* (WWW '26). Association for Computing Machinery, New York, NY,
> USA, 7914–7922. https://doi.org/10.1145/3774904.3792814

```bibtex
@inproceedings{marineli2026urlbank,
  author    = {Marineli, Felipe and Cetorelli, Valerio and Crescenzi, Valter and Furche, Tim and Guo, Xiaonan},
  title     = {{URLBank}: Data-Driven {URL} Discovery via Temporal Link Graphs},
  booktitle = {Proceedings of the ACM Web Conference 2026},
  series    = {WWW '26},
  year      = {2026},
  pages     = {7914--7922},
  publisher = {Association for Computing Machinery},
  address   = {New York, NY, USA},
  isbn      = {9798400723070},
  doi       = {10.1145/3774904.3792814},
  url       = {https://doi.org/10.1145/3774904.3792814}
}
```