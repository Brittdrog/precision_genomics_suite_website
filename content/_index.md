---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Precision Genomics Suite
      text: From the **[Wright](https://galenwrightlab.com/)**, **[Drögemöller](https://www.drogemollerlab.com/)**, and **[Kowalec](https://www.kowaleclab.com/)** Labs

    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: xenium_brain_example.png
          filters:
            brightness: 0.5
  - block: stats
    content:
      items:
        - statistic: "$1 328 074"
          description: |
            Invesments from  
            CFI, Research Manitoba, and others
        - statistic: "3"
          description: |
            State of the art
            single-cell and spatial transcriptiomics machines
        - statistic: "3k+"
          description: |
            Discord community  
            for support

    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]

  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: Chromium-iX
          text: Single Cell Expression and ATAC
          feature_icon: bolt
          features:
            - "Sequence any 10x Genomics single cell experiment (low-throughput)"
          # Upload image to `assets/media/` and reference the filename here
          image: 19_4160_chromium_344.webp
          button:
            text: Learn more
            url: equipment/chromium-ix/
        - title: Visium CytAssist
          text: Whole Spatial Transcriptomics
          feature_icon: bolt
          features:
            - "Target tissue sections for whole transcriptomic analyses"
          # Upload image to `assets/media/` and reference the filename here
          image: 10x_CytAssist_Right-Side_650x650.png
          button:
            text: Learn more
            url: equipment/visium-cytassist/
        - title: Xenium Analyzer
          text: Targetted Spatial Transcriptomics
          feature_icon: bolt
          features:
            - "Study single-cell gene expression spatially"
          # Upload image to `assets/media/` and reference the filename here
          image: Xenium-analyzer-instrument.png
          button:
            text: Learn more
            url: equipment/xenium-analyzer/
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"


  - block: cta-card
    content:
      title: Contact us for more details!
      text: 
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
