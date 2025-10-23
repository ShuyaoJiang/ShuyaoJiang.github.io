---
title:          "Revealing Performance Issues in Server-side WebAssembly Runtimes via Differential Testing"
date:           2023-09-11 00:00:00 +0800
selected:       true
pub:            >-
                The 38th IEEE/ACM International Conference on Automated Software Engineering, Luxembourg, Luxembourg, Sep. 11-15, 2023.
pub_pre:        >-
                <span class="badge badge-pill badge-custom badge-success">ASE'23</span> 
abstract: >-
  WebAssembly (Wasm) is a bytecode format originally serving as a compilation target for Web applications. It has recently been used increasingly on the server side, e.g., providing a safer, faster, and more portable alternative to Linux containers. With the popularity of server-side Wasm applications, it is essential to study performance issues (i.e., abnormal latency) in Wasm runtimes, as they may cause a significant impact on server-side applications. However, there is still a lack of attention to performance issues in server-side Wasm runtimes. In this paper, we design a novel differential testing approach WarpDiff to identify performance issues in server-side Wasm runtimes. The key insight is that in normal cases, the execution time of the same test case on different Wasm runtimes should follow an oracle ratio. We identify abnormal cases where the execution time ratio significantly deviates from the oracle ratio and subsequently locate the Wasm runtimes that cause the performance issues. We apply WarpDiff to test five popular server-side Wasm runtimes using 123 test cases from the LLVM test suite and demonstrate the top 10 abnormal cases we identified. We further conduct an in-depth analysis of these abnormal cases and summarize seven performance issues, all of which have been confirmed by the developers. We hope our work can inspire future investigation on improving Wasm runtime implementation and thus promoting the development of server-side Wasm applications.
# cover:          
authors:
  - Shuyao Jiang
  - Ruiying Zeng
  - Zihao Rao
  - Jiazhen Gu
  - Yangfan Zhou
  - Michael R. Lyu
links:
  Paper: https://shuyaojiang.github.io/publications/ase23/ASE23_WarpDiff_Proc.pdf
  Arxiv: https://arxiv.org/abs/2309.12167
  Slides: https://shuyaojiang.github.io/publications/ase23/ASE23_WarpDiff_Slides.pdf
  Project: https://github.com/ShuyaoJiang/WarpDiff
  DOI: https://doi.org/10.1109/ASE56229.2023.00088
  BibTex: https://shuyaojiang.github.io/publications/ase23/ase23-bibtex.txt
---