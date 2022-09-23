---
layout: page
title: 'Unicolor'
permalink: /unicolor/
---

# A Unified Framework for Multi-Modal Colorization with Transformer

Zhitong Huang $$^{1 \dagger}$$,  Nanxuan Zhao $$^{2 \dagger}$$ ,  Jing Liao $$^{1*}$$

<sub>
$$^1$$ : City University of Hong Kong, Hong Kong SAR, China &emsp; $$^2$$ : University of Bath, Bath, United Kingdom
</sub>
<br />
<sub>
$$^\dagger$$ : Both authors contributed equally to this research &emsp;&emsp; $$^*$$ : Corresponding author
</sub>

**Paper**: https://arxiv.org/abs/2209.11223  **Code**: coming soon...

### Video
<iframe
    width="720"
    height="405"
    src="https://www.youtube.com/embed/s4KVWqqGYBc"
    frameborder="0"
    allow="autoplay; encrypted-media"
    allowfullscreen
>
</iframe>

### Abstract
![alt text](./figures/teaser.png)

We propose the first unified framework *UniColor* to support colorization in multiple modalities, including both unconditional and conditional ones, such as stroke, exemplar, text, and even a mix of them. Rather than learning a separate model for each type of condition, we introduce a two-stage colorization framework for incorporating various conditions into a single model. In the first stage, multi-modal conditions are converted into a common representation of hint points. Particularly, we propose a novel CLIP-based method to convert the text to hint points. In the second stage, we propose a Transformer-based network composed of *Chroma-VQGAN* and *Hybrid-Transformer* to generate diverse and high-quality colorization results conditioned on hint points. Both qualitative and quantitative comparisons demonstrate that our method outperforms state-of-the-art methods in every control modality and further enables multi-modal colorization that was not feasible before. Moreover, we design an interactive interface showing the effectiveness of our unified framework in practical usage, including automatic colorization, hybrid-control colorization, local recolorization, and iterative color editing.