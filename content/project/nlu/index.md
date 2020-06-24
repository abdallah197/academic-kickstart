---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Neural Natural Language Understanding for Arabic Dialogue Systems"
summary: "B.S thesis, we built an NLU (using Neural Networks) for Arabic home automation assistants. we used CNN and BiLSTM in text classification and NER to build the NLU."
authors: []
tags: 
- Machine Learning. 
categories: []
date: 2018-01-21T23:16:49+02:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
Natural Language Understanding (NLU) is considered a core component in implementing dialogue systems. NLU has been greatly enhanced by deep learning techniques such as word embeddings and deep neural network architectures, but current NLP methods for Arabic language dialogue action classification or semantic decoding is mostly based on handcrafted rule-based systems and methods that use feature engineering, but without the benefit of any form of distributed representation of words. This paper presents an approach to use deep learning techniques for text classification and Named Entity Recognition for the domain of home automation in Arabic. To this end, we present an NLU module that can further be integrated with Automatic Speech Recognition (ASR), a Dialogue Manager (DM) and a Natural Language Generator (NLG) module to build a fully working dialogue system. The paper further describes our process of collecting and annotating the data, structuring the intent classifier and entity extractor models, and finally the evaluation of these methods on different benchmarks.
[link](https://github.com/abdallah197/NLU--ArabicDialogueSystems) to the repo
