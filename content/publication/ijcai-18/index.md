+++
title = "GeoMAN: Multi-level Attention Networks for Geo-sensory Time Series Prediction"

# Date first published.
date = "2018-07-13"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["**Yuxuan Liang**", "Songyu Ke", "Junbo Zhang", "Xiuwen Yi", "Yu Zheng"]
tags = ["Attention", "Deep Learning", "ST Data"]

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
publication = "IJCAI 2018"
publication_short = "*IJCAI*"

# Abstract and optional shortened version.
abstract = """Numerous sensors have been deployed in different geospatial locations to continuously and cooperatively monitor the surrounding environment, such as the air quality. These sensors generate multiple geo-sensory time series, with spatial correlations
between their readings. Forecasting geo-sensory time series is of great importance yet very challenging as it is affected by many complex factors, i.e., dynamic spatio-temporal correlations and external factors. In this paper, we predict the readings of a geo-sensor over several future hours by using a multi-level attention-based recurrent neural network that considers multiple sensors’ readings, meteorological data, and spatial data. More specifically, our model consists of two major parts: 1) a multi-level attention mechanism to model the dynamic spatio-temporal dependencies. 2) a general fusion module to incorporate the external factors
from different domains. Experiments on two types of real-world datasets, viz., air quality data and water quality data, demonstrate that our method outperforms nine baseline methods."""

abstract_short = "*IJCAI* 2018"

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
url_pdf = "pdf/ijcai-18/paper.pdf"
url_preprint = ""
url_code = "https://github.com/yoshall/GeoMAN"
url_dataset = "https://github.com/yoshall/GeoMAN"
url_project = ""
url_slides = "pdf/ijcai-18/slide.pdf"
url_video = ""
url_poster = "pdf/ijcai-18/poster.pdf"
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
