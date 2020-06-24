---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Offinsive tweets classification"
summary: "A school project aimed to classify offensive and non offensive tweets using Machine Learning models like SVM and Naive Bayes"
authors: []
tags: 
- Machine Learning.
categories: []
date: 2019-07-21T23:17:15+02:00

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
## School Assignment


### Task Description
The task to be completed within this project is to develop and evaluate a system that processes

a single tweet and decides whether or not the tweet contains offensive language. This task

could be tackled as a binary text classification problem. To this end,  a dataset of

tweets annotated for offensiveness is provided in the repo. The files “train.tsv” and “dev.tsv” all have the same format.

The second column (text) contains the text of a tweet, the first column (label) contains an

offensiveness label:

* (NOT) Not Offensive - This post does not contain offense or profanity.

* (OFF) Offensive - This post contains offensive language or a targeted (veiled or direct)

offense

The table below shows a few examples of tweets that

have been annotated as offensive.

1/4

1 @USER Liberals are all Kookoo !!!

2 @USER @USER Most stupid tweet yet...and yes...its a libtard

3 @USER I bet the first ones she calls when she is being robbed is those

very same police . People are freaking stupid ...

4 @USER @USER Go home you’re drunk!!! @USER #MAGA #Trump2020 URL




### Baseline Classifier

Naive bayes and svm classifiers were used as models.
[link](https://github.com/abdallah197/Offensive-Language-Detection-on-Twitter) to the repo.
