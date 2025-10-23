---
title:          "Towards Usable Neural Comment Generation via Code-Comment Linkage Interpretation: Method and Empirical Study"
date:           2023-04-01 00:00:00 +0800
selected:       true
pub:            >-
                IEEE Transactions on Software Engineering, vol. 49, no. 4, pp. 2239-2254, Apr. 2023.
pub_pre:        >-
                <span class="badge badge-pill badge-custom badge-success">TSE'23</span> 
abstract: >-
  Code comment is important to facilitate code comprehension for developers. Recent studies suggest to generate comments automatically with deep learning, in particular, based on neural machine translation models. However, such a promising Neural Comment Generation (NCG) technique suffers from unsatisfactory performance, as well as poor usability, i.e., developers cannot easily understand and modify the auto-generated comments. This paper suggests that a proper interpretation of how the comments are generated can significantly improve the usability of NCG approaches. We propose a novel model-independent framework, namely CCLink, to interpret the auto-generated comments. CCLink generates a set of code mutants and obtains their corresponding comments. Based on these data, several contribution mining algorithms are designed to infer the key elements in code that contributes to the generation of the key phrases in the comments. The links between code and its auto-generated comment can thus be constructed. This in turn allows CCLink to visualize the links as the comment interpretations to developers. It greatly facilitates manual verification and correction of the comments. We examine the performance of CCLink with different contribution mining algorithms, NCG approaches, and real-world datasets. We also conduct an empirical study on 32 experienced Java programmers to evaluate the effectiveness of CCLink. The results show that CCLink is promising in making NCG more usable with a proper interpretation of the auto-generated comments.  
# cover:          
authors:
  - Shuyao Jiang
  - Jiacheng Shen
  - Shengnan Wu
  - Yu Cai
  - Yue Yu
  - Yangfan Zhou
links:
  Paper: https://shuyaojiang.github.io/publications/tse23/TSE23_CCLink.pdf
  Project: https://github.com/CCLink-demo
  DOI: https://doi.org/10.1109/TSE.2022.3214859
  BibTex: https://shuyaojiang.github.io/publications/tse23/tse23-bibtex.txt
---