---
title:          "Bringing Managed Language Support to WebAssembly with External Library Linking"
date:           2026-07-05 00:00:00 +0800
selected:       true
pub:            >-
                ACM International Conference on the Foundations of Software Engineering, Montreal, QC, Canada, Jul. 5-9, 2026.
pub_pre:        >-
                <span class="badge badge-pill badge-custom badge-success">FSE'26</span> 
abstract: >-
  WebAssembly (Wasm) has emerged as a powerful bytecode format for running applications with near-native performance in portable and secure environments. However, while Wasm currently supports compiled languages like C, C++, and Rust, it lacks robust support for managed languages such as Python, Java, and JavaScript. This limitation hinders the deployment of applications in domains like machine learning and data processing that rely heavily on managed language ecosystems. To address this, we propose WALL-E, a novel framework to integrate managed languages into Wasm environments without complex runtime nesting or recompilation. WALL-E employs a unique external library linking strategy, using a client-server architecture to connect Wasm modules with managed language libraries running in their native runtimes. This approach preserves the native execution speed and language feature compatibility of managed languages by eliminating the overhead associated with double-layer virtual machines. Our evaluation shows that WALL-E supports ten managed languages without framework modifications and achieves hundreds of times speedup compared to runtime nesting solutions, with low communication overhead. WALL-E enhances the practicality of Wasm in cloud and edge computing, enabling efficient multi-language applications.
# cover:          
authors:
  - Shuyao Jiang
  - Ruiying Zeng
  - Yangfan Zhou
  - Michael R. Lyu
links:

---