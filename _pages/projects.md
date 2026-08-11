---
layout: page
title: Research
nav: true
nav_order: 2
permalink: /research/
---

Our lab focuses on **stem cell and organoid development and application**.
We use human iPSC‑derived organoid models to recapitulate human tissue development, disease mechanism and drug evaluation.

## 1. Human Vascular Organoids
Generation and optimization of iPSC‑derived vascular organoids; study of vascular development regulation, endothelial‑mesenchymal interaction, vascular injury and repair, as well as aberrant vascular behaviors within tumor microenvironment and tumor‑vascular crosstalk.

## 2. Bone / Bone‑marrow Organoid
iPSC‑based bone‑marrow niche organoid construction; hematopoietic microenvironment and bone‑related disorders.

## 3. Multi‑Organoid Integration Systems
Assembly of coupled multi‑organoid complexes, integrating vascular systems with tumor organoids and immune‑cell components to reconstruct complex pathological niches. Combining gene editing, spatial transcriptomics and multi‑scale imaging to dissect key regulatory networks underlying disease progression.

## 4. Technology Translation
Establish organoid‑based drug screening platform for anti‑tumor drug assessment, target validation and immunotherapy response prediction; explore applications for vascular‑related disease modeling. We also pursue GMP‑compliant 3D culture systems and standardized cell repositories to support future clinical translation and industrial‑oriented development.

<!-- Research Image Gallery -->
<div class="research-gallery">

  <div class="research-image">
    <img src="{{ '/assets/img/VO1.png' | relative_url }}" alt="Vascular Organoid">
  </div>

  <div class="research-image">
    <img src="{{ '/assets/img/VO2.png' | relative_url }}" alt="Vascular Organoid">
  </div>

  <div class="research-image">
    <img src="{{ '/assets/img/VO3.png' | relative_url }}" alt="Vascular Organoid">
  </div>

</div>

<style>
  .research-gallery {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 22px;
    margin-top: 40px;
    margin-bottom: 30px;
    align-items: center;
  }

  .research-image {
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .research-image img {
    width: 100%;
    height: 230px;
    object-fit: contain;
    border-radius: 12px;
    display: block;
    transition: transform 0.25s ease;
  }

  .research-image img:hover {
    transform: scale(1.03);
  }

  /* Tablet */
  @media (max-width: 768px) {
    .research-gallery {
      gap: 14px;
    }

    .research-image img {
      height: 180px;
    }
  }

  /* Mobile */
  @media (max-width: 520px) {
    .research-gallery {
      grid-template-columns: 1fr;
      gap: 18px;
    }

    .research-image img {
      height: auto;
      max-height: 260px;
    }
  }
</style>
