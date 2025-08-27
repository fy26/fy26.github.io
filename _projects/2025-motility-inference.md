---
title: Image-based motility and stress inference in tissues
tagline: Extract cell velocity and stress from static segmented images
#year: 2025
#venue: In preparation
thumb: /assets/img/motility-inference-thumb.png
weight: 30
---

**Motivation**: Cell motility is a defining feature of both tumor progression and immune defense.
In tumors, cancer cells migrate along extracellular matrix fibers, invade surrounding tissues,
and intravasate into blood vessels, leading to metastasis. Pro-tumor macrophages further promote
this process by remodeling the matrix and establishing signaling loops that enhance carcinoma 
invasion. Conversely, effective immune responses rely on motile lymphocytes and macrophages that 
infiltrate tissues, navigate dense tumor microenvironments, and engage with target cells. 

**Ongoing work**: To capture these dynamics, we are developing a non-equilibrium motility inference
framework that extracts velocity fields and mechanical stresses from static histological images—addressing 
a key gap in how we measure mechanical transitions in living systems. 
Unlike conventional force inference methods that assume mechanical equilibrium, 
our approach accounts for net forces and motion, revealing the inherently dynamic behaviors of 
tissues. It also complements RNA velocity, which links transcript dynamics to cell fate transitions 
and is most effective in developing embryos. By contrast, our mechanics-based framework directly connects 
physical forces to motility, making it uniquely suited to tumor microenvironments where mechanical cues 
strongly dictate cell behavior. It enables analysis of how velocity and force distributions vary across 
cell types and regions without the need for time-lapse imaging or external perturbation. When integrated 
with spatial transcriptomics data of a breast tumor ([A. Janesick et al., 2023](https://www.nature.com/articles/s41467-023-43458-x)), as shown in Fig. 1, the method reveals that 
vascular endothelial cells exhibit the highest velocities, consistent with active tumor vascularization. 
Boxplot analysis further shows that immune cells are more motile than tumor cells, suggesting enhanced 
immune response relative to tumor progression.

![Healing of a microtubule–motor network](/assets/img/motility-inference-intro.png){: .center width="800px"}
Figure 1: Motility inference from breast tumor images uncovers tumor progression and immune responses.


---

#### Preprint in preparation