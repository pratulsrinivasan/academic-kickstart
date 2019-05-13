+++
title = "Local Light Field Fusion: Practical View Synthesis with Prescriptive Sampling Guidelines"
date = 2019-02-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["ben-mildenhall*", "pratul-srinivasan*", "rodrigo-cayon", "nima-kalantari", "ravi-ramamoorthi", "ren-ng", "abhishek-kar", "*: co-first authors"]

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
publication_types = ["1","2"]

# Publication name and optional abbreviated version.
publication = "In *SIGGRAPH*."
publication_short = "In *SIGGRAPH*"

# Abstract and optional shortened version.
abstract = "We present a practical and robust deep learning solution for capturing and rendering novel views of complex real world scenes for virtual exploration. Previous approaches either require intractably dense view sampling or provide little to no guidance for how users should sample views of a scene to reliably render high-quality novel views. Instead, we propose an algorithm for view synthesis from an irregular grid of sampled views that first expands each sampled view into a local light field via a multiplane image (MPI) scene representation, then renders novel views by blending adjacent local light fields. We extend traditional plenoptic sampling theory to derive a bound that specifies precisely how densely users should sample views of a given scene when using our algorithm. In practice, we apply this bound to capture and render views of real world scenes that achieve the perceptual quality of Nyquist rate view sampling while using up to 4000x fewer views. We demonstrate our approach's practicality with an augmented reality smartphone app that guides users to capture input images of a scene and viewers that enable realtime virtual exploration on desktop and mobile platforms."

# Summary. An optional shortened abstract.
summary = "*SIGGRAPH 2019*. Light field theory and algorithm for rendering new views of complex scenes."

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
# url_pdf = ""
# url_preprint = ""
url_code = "https://github.com/Fyusion/LLFF"
# url_dataset = ""
url_project = "http://people.eecs.berkeley.edu/~bmild/llff/index.html"
# url_slides = "#"
url_video = "https://www.youtube.com/watch?v=LY6MgDUzS3M&feature=youtu.be"
# url_poster = "#"
# url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
links = [{name = "Arxiv", url = "https://arxiv.org/abs/1905.00889"}]

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
  focal_point = "Center"
  preview_only = true
+++

