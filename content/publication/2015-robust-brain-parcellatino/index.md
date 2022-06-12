---
title: 'Robust brain parcellation using sparse representation on resting-state fMRI'
authors:
  - Yu Zhang
  - Svenja Caspers
  - admin
  - Yong Fan
  - Ming Song
  - Cirong Liu
  - Yin Mo
  - Christian Roski
  - Simon Eickhoff
  - Katrin Amunts
  - Tianzi Jiang
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
date: '2015-11-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: '*Brain Structure Function*'
publication_short: 'Brain Struct Funct'

abstract: Resting-state fMRI (rs-fMRI) has been widely used to segregate the brain into individual modules based on the presence of distinct connectivity patterns. Many parcellation methods have been proposed for brain parcellation using rs-fMRI, but their results have been somewhat inconsistent, potentially due to various types of noise. In this study, we provide a robust parcellation method for rs-fMRI-based brain parcellation, which constructs a sparse similarity graph based on the sparse representation coefficients of each seed voxel and then uses spectral clustering to identify distinct modules. Both the local time-varying BOLD signals and whole-brain connectivity patterns may be used as features and yield similar parcellation results. The robustness of our method was tested on both simulated and real rs-fMRI datasets. In particular, on simulated rs-fMRI data, sparse representation achieved good performance across different noise levels, including high accuracy of parcellation and high robustness to noise. On real rs-fMRI data, stable parcellation of the medial frontal cortex (MFC) and parietal operculum (OP) were achieved on three different datasets, with high reproducibility within each dataset and high consistency across these results. Besides, the parcellation of MFC was little influenced by the degrees of spatial smoothing. Furthermore, the consistent parcellation of OP was also well corresponding to cytoarchitectonic subdivisions and known somatotopic organizations. Our results demonstrate a new promising approach to robust brain parcellation using resting-state fMRI by sparse representation.


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags:
#   - Source Themes
featured: false

links:
- name: "DOI"
  url: "https://link.springer.com/article/10.1007/s00429-014-0874-x"
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'parcellation scheme'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---
