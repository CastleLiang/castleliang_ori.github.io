+++
title = "Inferring Traffic Cascading Patterns"

# Date first published.
date = "2017-11-04"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["**Yuxuan Liang**", "Zhongyuan Jiang", "Yu Zheng"]
tags = ["ST Data", "Generative"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "ACM SIGSPATIAL 2017"
publication_short = "*ACM SIGSPATIAL*"

# Abstract and optional shortened version.
abstract = """There is an underlying cascading behavior over road networks. Traffic cascading patterns are of great importance to easing traffic and improving urban planning. However, what we can observe is individual traffic conditions on different road segments at discrete time intervals, rather than explicit interactions or propagation (e.g., A→B) between road segments. Additionally, the traffic from multiple sources and the geospatial correlations between road segments make it more challenging to infer the patterns. In this paper, we first model the three-fold influences existing in traffic propagation and then propose a data-driven approach, which finds the cascading patterns through maximizing the likelihood of observed traffic data. As this is equivalent to a submodular function maximization problem, we solve it by using an approximate algorithm with provable near-optimal performance guarantees based on its submodularity. Extensive experiments on real-world datasets demonstrate the advantages of our approach in both effectiveness and efficiency."""
abstract_short = "*ACM SIGSPATIAL* 2017"

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = []

# Links (optional).
url_pdf = "pdf/sigspatial-17/paper.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = "pdf/sigspatial-17/slide.pdf"
url_video = ""
url_poster = "pdf/sigspatial-17/poster.pdf"
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = "Framework of this paper"
  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Center"


+++
