---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Music Generator Using Deep Learning"
summary: "A university team projec that is meant to use transformer based Neural Networks architecture to generate music"
authors: []
tags: 
- Machine Learning
categories: []
date: 2020-06-21T23:21:13+02:00

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

Music Generation has become an active area of research for the past decade with
dominance of Neural Networks across the AI field. Using such systems can aid
musicians and composers in the process of making music. It can also be in great
help for beginners that in a hunt for creating creative melodies and harmony during
learning. Our project tries to use state of the art approaches in tackling this problem
as a language modeling approach. Similar approaches were used in Musenet Open
AI and Musicautobot. It processes midi files and converts it to text to build the
language model. We then use the language model to predict and generate music. We used musicautobot, fastai and music 21 as tools to build the model.
We have trained two models for classic and Pop music. We forwarded some of the
model results to a musician to evaluate it and his response was that the model was
capable of building simple mono-rhythm predictions and all the measures are in a
correct tempo and beat stress, however, most of the endings of the predictions were
bad in terms of harmony and melody.
