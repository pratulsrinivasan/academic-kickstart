+++
title = "Light Field Blind Motion Deblurring"
date = 2017-07-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Pratul P. Srinivasan", "Ren Ng", "Ravi Ramamoorthi"]

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
publication = "Oral Presentation in *Conference on Computer Vision and Pattern Recognition (CVPR)*."
publication_short = "In *CVPR*"

# Abstract and optional shortened version.
abstract = "We study the problem of deblurring light fields of general 3D scenes captured under 3D camera motion and present both theoretical and practical contributions. By analyzing the motion-blurred light field in the primal and Fourier domains, we develop intuition into the effects of camera motion on the light field, show the advantages of capturing a 4D light field instead of a conventional 2D image for motion deblurring, and derive simple methods of motion deblurring in certain cases. We then present an algorithm to blindly deblur light fields of general scenes without any estimation of scene geometry, and demonstrate that we can recover both the sharp light field and the 3D camera motion path of real and synthetically-blurred light fields."

# Summary. An optional shortened abstract.
summary = "Oral Presentation in *CVPR 2017*. Fourier theory and an algorithm to deblur light fields captured with unknown camera motion."

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
url_pdf = "https://cseweb.ucsd.edu/~ravir/pratul_lfmb.pdf"
# url_preprint = "http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf"
url_code = "https://github.com/pratulsrinivasan/Light_Field_Blind_Motion_Deblurring"
url_dataset = "https://people.eecs.berkeley.edu/~pratul/deblur_data_results.zip"
# url_project = "#"
# url_slides = "#"
url_video = "https://youtu.be/rtukre-ErmI"
# url_poster = "#"
# url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
links = [{name = "Paper on Arxiv", url = "https://arxiv.org/abs/1704.05416"}, {name = "Results GIFs", url = "https://people.eecs.berkeley.edu/~pratul/deblur_html/supplementary.html"}]

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

## Overview and Results Video
<iframe width="700" height="394" src="https://www.youtube.com/embed/rtukre-ErmI" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
