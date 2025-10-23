---
title:          "Boosting Neural Commit Message Generation with Code Semantic Analysis"
date:           2019-11-11 00:00:00 +0800
selected:       true
pub:            >-
                The 34th IEEE/ACM International Conference on Automated Software Engineering, San Diego, CA, USA, Nov. 11-15, 2019.
pub_pre:        >-
                <span class="badge badge-pill badge-custom badge-success">ASE'19</span> 
# pub_post:       'Under review.'
# pub_last:       '<span class="badge badge-pill badge-custom badge-secondary">Conference</span><span class="badge badge-pill badge-custom badge-warning">Poster</span>'
abstract: >-
  It has been long suggested that commit messages can greatly facilitate code comprehension. However, developers may not write good commit messages in practice. Neural machine translation (NMT) has been suggested to automatically generate commit messages. Despite the efforts in improving NMT algorithms, the quality of the generated commit messages is not yet satisfactory. This paper, instead of improving NMT algorithms, suggests that proper preprocessing of code changes into concise inputs is quite critical to train NMT. We approach it with semantic analysis of code changes. We collect a real-world dataset with 50k+ commits of popular Java projects, and verify our idea with comprehensive experiments. The results show that preprocessing inputs with code semantic analysis can improve NMT significantly. This work sheds light to how to apply existing DNNs designed by the machine learning community, e.g., NMT models, to complete software engineering tasks.
# cover:          
authors:
  - Shuyao Jiang
links:
  Paper: https://shuyaojiang.github.io/publications/ase19/ase19-src-paper.pdf
  Poster: https://shuyaojiang.github.io/publications/ase19/src-poster.pdf
  Slides: https://shuyaojiang.github.io/publications/ase19/src-slides.pdf
  DOI: https://doi.org/10.1109/ASE.2019.00162
  BibTex: https://shuyaojiang.github.io/publications/ase19/ase19-bibtex.txt
---