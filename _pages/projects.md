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
<!-- Vascular Organoid Image Gallery -->
<div class="research-gallery">

  <div class="research-image">
    <img
      src="{{ '/assets/img/VO1.png' | relative_url }}"
      alt="Human Vascular Organoids"
    >
  </div>

  <div class="research-image">
    <img
      src="{{ '/assets/img/VO2.png' | relative_url }}"
      alt="Vascular Organoid Immunofluorescence"
    >
  </div>

  <div class="research-image">
    <img
      src="{{ '/assets/img/VO3.png' | relative_url }}"
      alt="Vascular Organoid Immunofluorescence"
    >
  </div>

</div>

<style>
  /* ================================
     Vascular Organoid Image Gallery
     ================================ */

  .research-gallery {
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 24px;

    margin-top: 42px;
    margin-bottom: 35px;
  }

  .research-image {
    height: 190px;

    display: flex;
    align-items: center;
    justify-content: center;

    flex-shrink: 1;
    min-width: 0;
  }

  .research-image img {
    height: 190px;
    width: auto;

    max-width: 100%;
    object-fit: contain;

    display: block;

    transition: transform 0.25s ease;
  }

  /* Slight enlargement when hovering */
  .research-image img:hover {
    transform: scale(1.025);
  }

  /* ================================
     Tablet
     ================================ */

  @media (max-width: 900px) {
    .research-gallery {
      gap: 14px;
    }

    .research-image {
      height: 150px;
    }

    .research-image img {
      height: 150px;
    }
  }

  /* ================================
     Mobile
     ================================ */

  @media (max-width: 600px) {
    .research-gallery {
      flex-direction: column;
      gap: 20px;

      margin-top: 30px;
      margin-bottom: 25px;
    }

    .research-image {
      width: 100%;
      height: auto;
    }

    .research-image img {
      width: auto;
      height: auto;

      max-width: 100%;
      max-height: 240px;
    }
  }
</style>
