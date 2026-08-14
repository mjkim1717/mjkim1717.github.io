---
title: 'Characterization of the phylogenetic relationships in bilateral breast angiosarcoma'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Minju Kim

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2024-04-05T00:00:00Z'

# Schedule page publish date (NOT publication's date).
#publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication metadata — structured fields used by citation styles and BibTeX export.
publication:
  name: "Proceedings: AACR Annual Meeting 2024"
  short_name: "AACR"

peer_reviewed: false
open_access: true
#license: CC-BY-4.0

# Awards, honors, and recognitions. Surfaced as badges on the page and in listings.
#awards:
#  - name: "Best Paper Award"
#    level: winner
#    note: "Top 5 of 8000 submissions"
#  - name: "Oral Presentation"
#    level: selected

# Funders and grants. Required by many funders for compliance reporting.
#funding:
#  - funder: "National Science Foundation"
#    grant: "NSF-2401234"
#  - funder: "European Research Council"
#    grant: "ERC-StG-101234"

abstract: |
  **Background**: Breast angiosarcoma represents around 20% of all angiosarcomas, and often spread to lung, liver, and bones. Driver mutations of angiosarcoma, specifically PTPRB, and PLCG1, are well-known as reported previously. Notably, contralateral breast is another metastatic site of the breast angiosarcoma, where an unusual location for other soft tissue sarcomas. However, it remains uncertain whether the contralateral disease originates from the primary tumor or emerges independently. Here, we present a 75-year-old woman with bilateral breast angiosarcomas to investigate the genetic relationship between the tumors.
  
  **Methods**: Irregular and heterogeneous masses were synchronously detected through breast sonography. Whole genome sequencing (WGS) was conducted at 60X coverage using bilateral total mastectomies, along with a matched normal blood sample (n=1). Single nucleotide variants (SNVs) and small indels were identified using Strelka2 and Varscan2. Subsequent filtering was performed using custom Python scripts to establish high-confidence variants. A phylogenetic tree was then reconstructed based on SNVs to trace clonal evolution and distinguish between de novo primary and metastasis. Following this, COSMIC mutational signatures were analyzed to characterize the genomic profile.
  
  **Results**: For the left breast angiosarcoma, we found 1,086 SNVs and 101 indels, while the right breast angiosarcoma had 921 SNVs and 92 indels. Despite their small size (<1.0 cm) and low FNCLCC grade (G1), these two cancers shared 600 SNVs and 135 indels as “truncal events”, indicating that one side metastasized from the other. According to the phylogenetic tree and the molecular clock of the two angiosarcomas, we estimated that the metastasis occurred during the middle stages of cancer evolution. Additionally, we identified 7 nonsynonymous SNVs (ADAMTS7, RPS15, CYP2A6, OR1S2, ARHGAP23, GNAQ, UGT2B7), five of which were shared. Remarkably, the GNAQ driver mutation exhibited a mutation at codon 209, a hotspot mutation not previously reported in breast angiosarcoma. The dominant Cosmic mutational signatures were SBS1/5 and ID1/2, all of which were associated with aging.
  
  **Conclusion**: Our findings demonstrate that bilateral breast angiosarcomas metastasized from one side to the other, as evidenced by the WGS data. This study underscores that the capability of WGS to distinguish between oligometastatic disease and multiple primary cancers, which has implications for predicting patients’ prognosis.
  
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - WGS

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
#hugoblox:
#  ids:
#    doi: 10.5555/123456

# Custom links
#links:
#  - type: pdf
#    url: ""
#  - type: code
#    url: https://github.com/HugoBlox/kit
#  - type: dataset
#    url: https://github.com/HugoBlox/kit
#  - type: slides
#    url: https://www.slideshare.net/
#  - type: source
#    url: https://github.com/HugoBlox/kit
#  - type: video
#    url: https://youtube.com

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  #caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/projects/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

