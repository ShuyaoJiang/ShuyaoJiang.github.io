---
title:          "Debugging Performance Issues in WebAssembly Runtimes via Mutation-based Inference"
date:           2026-04-12 00:00:00 +0800
selected:       true
pub:            >-
                The 48th IEEE/ACM International Conference on Software Engineering, Rio de Janeiro, Brazil, Apr. 12-18, 2026.
pub_pre:        >-
                <span class="badge badge-pill badge-custom badge-success">ICSE'26</span> 
abstract: >-
  Performance debugging in WebAssembly (Wasm) runtimes is essential for ensuring the robustness of Wasm, especially since performance issues have frequently occurred in Wasm runtimes, which can significantly degrade the capabilities of hosted services. Many performance issues in Wasm runtimes result from suboptimal compilation of input Wasm programs, for which existing performance debugging methods primarily designed for application-level inefficiencies are not well-suited. In this paper, we present WarpL, a novel mutation-based approach that aims to identify the exact suboptimal instruction sequences responsible for the performance issues in Wasm runtimes, thereby narrowing down the root causes. Specifically, WarpL obtains a functionally similar mutant in which the performance issue does not manifest, and isolates the exact suboptimal instructions by comparing the machine code of the original and mutated programs. We implement WarpL as an open-source tool and evaluate it on 12 real-world performance issues across three widely used Wasm runtimes. WarpL identified the exact causes in 10 out of 12 issues. Notably, we have used WarpL to successfully diagnose six previously unknown performance issues in Wasmtime.
# cover:          
authors:
  - Ruiying Zeng
  - Shuyao Jiang
  - Wenxuan Zhao
  - Yangfan Zhou
links:

---