---
layout: page
title: Vec2Text
description: Reconstructing text sequences from just its embeddings.
img: assets/img/vec2text.png
importance: 1
category: Academic
related_publications: true
---

<div style="text-align: center;">
    {% include figure.liquid loading="lazy" path="assets/img/vec2text.png" title="Vec2Text" class="img-fluid rounded z-depth-1" width="80%" %}
</div>

<div style="float: right; width: 50%; margin-left: 20px; margin-bottom: 20px;">
    <div class="embed-responsive embed-responsive-16by9">
        <iframe src="/assets/pdf/Text%20Embeddings%20Reveal%20(Almost)%20As%20Much%20As%20Text%20-%20Reproduction.pdf#toolbar=1&navpanes=1&scrollbar=1&view=FitH" width="100%" height="300px" frameborder="0"></iframe>
    </div>
</div>

This project reproduces findings from the study "Text Embeddings Reveal (Almost) As Much As Text" {% cite morris2023textembeddingsrevealalmost %}, which highlights privacy risks in text embeddings by demonstrating their potential for reconstructing original text. Using a transformer-based encoder-decoder model with iterative correction, Vec2Text achieves high accuracy in embedding inversion, confirmed by BLEU and Token F1 scores across various datasets.

Our analysis validates the original study's claims on in-domain data, explores factors like beam width and sequence length, and assesses computational trade-offs. These findings emphasise the need to balance privacy, performance, and efficiency in text embedding systems.
