---
title: "Document Alignment and Reconstruction"
people: ["Dr. Sarah Cohen", "David Levi (PhD Student)"]
description: "Developing algorithms for automatically aligning fragmented historical documents and reconstructing their original layout."
github: "https://github.com/AI-Computer-Vision-BGU/doc-align"
---
### Project Overview
This sub-project focuses on one of the most challenging problems in historical document analysis: reconstructing documents that have been damaged, torn, or fragmented over time. Our goal is to create a robust pipeline that can take images of fragments and automatically determine how they fit together.

### Technical Approach
We are exploring a multi-stage approach:
1.  **Feature Extraction:** Using deep learning models to identify unique patterns, ink strokes, and material features on the edges of fragments.
2.  **Pairwise Matching:** Implementing a graph-based algorithm to test potential matches between fragments.
3.  **Global Optimization:** Solving a jigsaw-like puzzle to find the most probable overall document structure from all pairwise matches.

### Challenges
- Non-linear deformations of aged paper and parchment.
- Missing pieces and large gaps in the material.
- Fading ink and similar visual patterns across different fragments.

### Next Steps
We are currently curating a novel dataset of artificially fragmented documents with ground truth alignment data to train and evaluate our models.