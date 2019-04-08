+++
title = "Learning to Synthesize a 4D RGBD Light Field from a Single Image"
date = 2017-10-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Pratul P. Srinivasan", "Tongzhou Wang", "Ashwin Sreelal", "Ravi Ramamoorthi", "Ren Ng"]

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
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "In *International Conference on Computer Vision (ICCV)*."
publication_short = "In *ICCV*"

# Abstract and optional shortened version.
abstract = "We present a machine learning algorithm that takes as input a 2D RGB image and synthesizes a 4D RGBD light field (color and depth of the scene in each ray direction). For training, we introduce the largest public light field dataset, consisting of over 3300 plenoptic camera light fields of scenes containing flowers and plants. Our synthesis pipeline consists of a convolutional neural network (CNN) that estimates scene geometry, a stage that renders a Lambertian light field using that geometry, and a second CNN that predicts occluded rays and non-Lambertian effects. Our algorithm builds on recent view synthesis methods, but is unique in predicting RGBD for each light field ray and improving unsupervised single image depth estimation by enforcing consistency of ray depths that should intersect the same scene point."


# Summary. An optional shortened abstract.
summary = "Spotlight Presentation in *ICCV 2017*. Deep networks can promote a single image to a local neighborhood of views and depth maps."

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
url_pdf = "https://cseweb.ucsd.edu/~ravir/pratul_iccv.pdf"
# url_preprint = "http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf"
url_code = "https://github.com/pratulsrinivasan/Local_Light_Field_Synthesis"
url_dataset = "https://cseweb.ucsd.edu/~viscomp/projects/LF/papers/ICCV17/lfsyn/LF_Flowers_Dataset.tar.gz"
# url_project = "#"
# url_slides = "#"
url_video = "https://youtu.be/yLCvWoQLnms"
# url_poster = "#"
# url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
links = [{name = "Paper on Arxiv", url = "https://arxiv.org/abs/1708.03292"},{name = "Supplementary PDF", url = "https://people.eecs.berkeley.edu/~pratul/ICCV17_LF_Synthesis_Supplementary.pdf"}]

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


