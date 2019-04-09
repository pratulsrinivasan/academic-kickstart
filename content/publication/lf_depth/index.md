+++
title = "Shape Estimation from Shading, Defocus, and Correspondence Using Light-Field Angular Coherence"
date = 2015-06-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Michael W. Tao", "Pratul P. Srinivasan", "Sunil Hadap", "Szymon Rusinkiewicz", "Jitendra Malik", "Ravi Ramamoorthi"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
# 7 = Thesis
# 8 = Patent
publication_types = ["2", "1"]

# Publication name and optional abbreviated version.
publication = "In *IEEE Transactions on Pattern Matching and Machine Intelligence* and *Conference on Computer Vision and Pattern Recognition (CVPR)*."
publication_short = "In *IEEE PAMI* and *CVPR*"

# Abstract and optional shortened version.
abstract = "Light-field cameras are quickly becoming commodity items, with consumer and industrial applications. They capture many nearby views simultaneously using a single image with a micro-lens array, thereby providing a wealth of cues for depth recovery: defocus, correspondence, and shading. In particular, apart from conventional image shading, one can refocus images after acquisition, and shift one’s viewpoint within the sub-apertures of the main lens, effectively obtaining multiple views. We present a principled algorithm for dense depth estimation that combines defocus and correspondence metrics. We then extend our analysis to the additional cue of shading, using it to refine fine details in the shape. By exploiting an all-in-focus image, in which pixels are expected to exhibit angular coherence, we define an optimization framework that integrates photo consistency, depth consistency, and shading consistency. We show that combining all three sources of information: defocus, correspondence, and shading, outperforms state-of-the-art light-field depth estimation algorithms in multiple scenarios."

# Summary. An optional shortened abstract.
summary = "*IEEE PAMI 2017* and *CVPR 2015*. Jointly considering defocus, correspondence, and shading estimates better depth from light fields."

# Is this a featured publication? (true/false)
featured = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
# url_pdf = "https://cseweb.ucsd.edu/~ravir/normals_PAMI.pdf"
# url_preprint = "http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf"
url_code = "https://people.eecs.berkeley.edu/~pratul/CVPR15_LF_DEPTH_SHADING.zip"
# url_dataset = "http://people.duke.edu/~sf59/Srinivasan_BOE_2014_dataset.htm"
# url_project = "#"
# url_slides = "#"
# url_video = "#"
# url_poster = "#"
# url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
links = [{name = "Journal Link", url = "https://ieeexplore.ieee.org/document/7452621"}, {name = "Journal Article PDF", url = "https://cseweb.ucsd.edu/~ravir/normals_PAMI.pdf"}, {name = "Conference Paper PDF", url = "https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Tao_Depth_From_Shading_2015_CVPR_paper.pdf"}]

# Digital Object Identifier (DOI)
doi = ""

# Does this page contain LaTeX math? (true/false)
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  # caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  preview_only = true
  focal_point = "Center"
+++

## Example Results
[Example Results](depth_results.png)
