+++
title = "HyperST-Net: Hypernetworks for Spatio-Temporal Forecasting"

# Date first published.
date = "2018-01-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Zheyi Pan", "**Yuxuan Liang**", "Junbo Zhang", "Xiuwen Yi", "Yong Yu", "Yu Zheng"]
tags = ["Deep Learning", "ST Data", "HyperNet"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["3"]

# Publication name and optional abbreviated version.
publication = "arxiv"
publication_short = "*arxiv*"

# Abstract and optional shortened version.
abstract = """Spatio-temporal (ST) data, which represent multiple time series data corresponding to different spatial locations, are ubiquitous in real-world dynamic systems, such as air quality readings. Forecasting over ST data is of great importance but challenging as it is affected by many complex factors, including spatial characteristics, temporal characteristics and the intrinsic causality between them. In this paper, we propose a general framework (HyperST-Net) based on hypernetworks for deep ST models. More specifically, it consists of three major modules: a spatial module, a temporal module and a deduction module. Among them, the deduction module derives the parameter weights of the temporal module from the spatial characteristics, which are extracted by the spatial module. Then, we design a general form of HyperST layer as well as different forms for several basic layers in neural networks, including the dense layer (HyperST-Dense) and the convolutional layer (HyperST-Conv). Experiments on three types of real-world tasks demonstrate that the predictive models integrated with our framework achieve significant improvements, and outperform the state-of-the-art baselines as well."""

abstract_short = "A short version of the abstract."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = []

# Links (optional).
url_pdf = "https://arxiv.org/pdf/1809.10889.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = "My caption"

+++
