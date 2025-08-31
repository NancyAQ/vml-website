---
title: "Hebrew Paleography and Segmentation"
people: ["Rachel Amar (MS Student)", "Dr. Benjamin Isaac"]
description: "Applying semantic segmentation techniques to separate text from background and identify different scribal hands in Hebrew manuscripts."
github: "https://github.com/AI-Computer-Vision-BGU/hebrew-seg"
---
### Project Overview
The goal of this project is to create accurate pixel-level segmentation of Hebrew manuscripts, distinguishing between text, decorations, annotations, and the document background. A key challenge is the complex, often degraded appearance of these historical sources.

### Key Tasks
1.  **Text/Background Separation:** Using U-Net architectures to create binary masks isolating text regions.
2.  **Scribal Hand Identification:** Going beyond simple segmentation, we are training models to classify different writing styles within the same document, which is crucial for textual scholars.
3.  **Noise and Degradation Handling:** Developing techniques that are robust to stains, bleed-through from the other side of the page, and physical damage.

### Datasets
We are working with digitized collections from the National Library of Israel and partnering with paleographers from the Department of Jewish History to create accurate ground truth labels.

### Applications
The output of this project will provide a foundational tool for digital humanities scholars, enabling large-scale analysis of writing styles, manuscript provenance, and automated transcription efforts.