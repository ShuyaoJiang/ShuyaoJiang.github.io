---
title:          "Distinguishability-guided Test Program Generation for WebAssembly Runtime Performance Testing"
date:           2025-03-04 00:00:00 +0800
selected:       true
pub:            >-
                The 32nd IEEE International Conference on Software Analysis, Evolution and Reengineering, Montreal, QC, Canada, Mar. 4-7, 2025.
pub_pre:        >-
                <span class="badge badge-pill badge-custom badge-success">SANER'25</span> 
abstract: >-
  WebAssembly (Wasm) is a binary instruction format designed as a portable compilation target, which has been widely used on both the web and server sides in recent years. As high performance is a critical design goal of Wasm, it is essential to conduct performance testing for Wasm runtimes. However, existing research on Wasm runtime performance testing still suffers from insufficient high-quality test programs. To solve this problem, we propose a novel test program generation approach WarpGen. It first extracts code snippets from historical issue-triggering test programs as initial operators, then inserts an operator into a seed program to synthesize a new test program. To verify the quality of generated programs, we propose an indicator called distinguishability, which refers to the ability of a test program to distinguish abnormal performance of specific Wasm runtimes. We apply WarpGen for performance testing on four Wasm runtimes and verify its effectiveness compared with baseline approaches. In particular, WarpGen has identified seven new performance issues in three Wasm runtimes.
# cover:          
authors:
  - Shuyao Jiang
  - Ruiying Zeng
  - Yangfan Zhou
  - Michael R. Lyu
links:
  Paper: https://shuyaojiang.github.io/files/SANER25/SANER25_WarpGen.pdf
  arXiv: https://arxiv.org/abs/2412.20100
  Slides: https://shuyaojiang.github.io/files/SANER25/SANER25_WarpGen_Slides.pdf
  Project: https://github.com/ShuyaoJiang/WarpGen
  DOI: https://doi.org/10.1109/SANER64311.2025.00078
  BibTex: https://shuyaojiang.github.io/files/SANER25/SANER25_bibtex.txt
---