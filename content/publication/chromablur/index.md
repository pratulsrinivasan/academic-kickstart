+++
title = "ChromaBlur: Rendering Chromatic Eye Aberration Improves Accommodation and Realism"
date = 2017-11-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Steven A. Cholewiak", "Gordon S. Love", "Pratul P. Srinivasan", "Ren Ng", "Martin S. Banks"]

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
publication = "In *ACM Transactions on Graphics (SIGGRAPH Asia)*."
publication_short = "In *SIGGRAPH Asia*"

# Abstract and optional shortened version.
abstract = "Computer-graphics engineers and vision scientists want to generate images that reproduce realistic depth-dependent blur. Current rendering algorithms take into account scene geometry, aperture size, and focal distance, and they produce photorealistic imagery as with a high-quality camera. But to create immersive experiences, rendering algorithms should aim instead for perceptual realism. In so doing, they should take into account the significant optical aberrations of the human eye. We developed a method that, by incorporating some of those aberrations, yields displayed images that produce retinal images much closer to the ones that occur in natural viewing. In particular, we create displayed images taking the eye's chromatic aberration into account. This produces different chromatic effects in the retinal image for objects farther or nearer than current focus. We call the method ChromaBlur. We conducted two experiments that illustrate the benefits of ChromaBlur. One showed that accommodation (eye focusing) is driven quite effectively when ChromaBlur is used and that accommodation is not driven at all when conventional methods are used. The second showed that perceived depth and realism are greater with imagery created by ChromaBlur than in imagery created conventionally. ChromaBlur can be coupled with focus-adjustable lenses and gaze tracking to reproduce the natural relationship between accommodation and blur in HMDs and other immersive devices. It may thereby minimize the adverse effects of vergence-accommodation conflicts."

# Summary. An optional shortened abstract.
summary = "*SIGGRAPH Asia 2017*. Considering the eye's aberrations when rendering increases realism and helps drive accomodation in VR."

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
url_pdf = "http://bankslab.berkeley.edu/publications/Files/chromablur_rendering_chromatic17.pdf"
# url_preprint = "http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf"
# url_code = "https://github.com/pratulsrinivasan/Light_Field_Blind_Motion_Deblurring"
# url_dataset = "https://people.eecs.berkeley.edu/~pratul/deblur_data_results.zip"
# url_project = "#"
# url_slides = "#"
url_video = "https://youtu.be/oGZgEmkmvvg"
# url_poster = "#"
# url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
links = [{name = "Project Page", url = "http://bankslab.berkeley.edu/publications/chromablur/"}]

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

