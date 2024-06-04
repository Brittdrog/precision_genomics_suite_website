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
      text: The Precision Genomics Suite offers an integrated workflow for multi-omic single cell analyses, whole transcriptome single cell spatial sequencing, and high resolution targeted (i.e., sub-cellular) spatial analyses.<br /> <br /> Funded by <span style="color:#7BAFD4">**[CFI-JELF](https://www.innovation.ca/apply-manage-awards/funding-opportunities/john-r-evans-leaders-fund)**</span> (<span style="color:#7BAFD4">**[Drögemöller](https://www.drogemollerlab.com/)**</span>, <span style="color:#7BAFD4">**[Kowalec](https://www.kowaleclab.com/)**</span>, and <span style="color:#7BAFD4">**[Wright](https://galenwrightlab.com/)**</span> Labs)
      

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
        - statistic: "$1.3M"
          description: |
            <br />Investments from  
            CFI, Research Manitoba, and others
        - statistic: "Tech" 
          description: |
            <br /> Xenium Analyzer <br /> 
            Visium CytAssist <br /> 
            Chromium iX <br /> 
            CellDrop Automated Cell Counter <br />
            4150 TapeStation System <br /> 
            QuantStudio6Pro Flex System 
        - statistic: "Local"
          description: | 
            <br /> Lab and data analysis assistance

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
        - title: Chromium iX
          text: Single cell/nuclei library prep
          # Upload image to `assets/media/` and reference the filename here
          image: 19_4160_chromium_344.webp
          button:
            text: Learn more
            url: equipment/chromium-ix/
        - title: Visium CytAssist
          text: Whole spatial transcriptomics
          # Upload image to `assets/media/` and reference the filename here
          image: 10x_CytAssist_Right-Side_650x650.png
          button:
            text: Learn more
            url: equipment/visium-cytassist/
        - title: Xenium Analyzer
          text: Targetted spatial transcriptomics
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
        text: Take our survery
        url: https://forms.gle/iDhvpqitDk7TnVnV7
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
