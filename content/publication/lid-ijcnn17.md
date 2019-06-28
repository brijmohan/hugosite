+++
title = "Significance of neural phonotactic models for large-scale spoken language identification"
date = 2017-05-14T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["**Brij Mohan Lal Srivastava**", "Hari Vydana", "Anil Kumar Vuppala", "Manish Shrivastava"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "In *30th International Joint Conference on Neural Networks*, IEEE."
publication_short = "In *IJCNN*"

# Abstract and optional shortened version.
abstract = "Language identification (LID) is vital frontend for spoken dialogue systems operating in diverse linguistic settings to reduce recognition and understanding errors. Existing LID systems which use low-level signal information for classification do not scale well due to exponential growth of parameters as the classes increase. They also suffer performance degradation due to the inherent variabilities of speech signal. In the proposed approach, we model the language-specific phonotactic information in speech using recurrent neural network for developing an LID system. The input speech signal is tokenized to phone sequences by using a common language-independent phone recognizer with varying phonetic coverage. We establish a causal relationship between phonetic coverage and LID performance. The phonotactics in the observed phone sequences are modeled using statistical and recurrent neural network language models to predict language-specific symbol from a universal phonetic inventory. Proposed approach is robust, computationally light weight and highly scalable. Experiments show that the convex combination of statistical and recurrent neural network language model (RNNLM) based phonotactic models significantly outperform a strong baseline system of Deep Neural Network (DNN) which is shown to surpass the performance of i-vector based approach for LID. The proposed approach outperforms the baseline models in terms of mean F1 score over 176 languages. Further we provide significant information-theoretic evidence to analyze the mechanism of the proposed approach."
abstract_short = "Existing LID systems which use low-level signal information for classification do not scale well due to exponential growth of parameters as the classes increase. They also suffer performance degradation due to the inherent variabilities of speech signal. In the proposed approach, we model the language-specific phonotactic information in speech using recurrent neural network for developing an LID system. We establish a causal relationship between phonetic coverage and LID performance. The proposed approach outperforms the baseline models in terms of mean F1 score over 176 languages. Further we provide significant information-theoretic evidence to analyze the mechanism of the proposed approach."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's filename without extension.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
#   Otherwise, set `projects = []`.
#projects = ["example-external-project"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "https://ieeexplore.ieee.org/abstract/document/7966114"
#url_preprint = "http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf"
#url_code = "#"
#url_dataset = "#"
#url_project = "#"
#url_slides = "#"
#url_video = "#"
#url_poster = "#"
#url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = ""

# Does this page contain LaTeX math? (true/false)
math = true

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "headers/lid-ijcnn17.png"
#caption = "My caption :smile:"

+++

#More detail can easily be written here using *Markdown* and $\rm \LaTeX$ math code.
