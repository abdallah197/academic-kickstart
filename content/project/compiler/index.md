---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Compiler"
summary: "Simplified C Compiler , a team project in My B.S. SCC compiles C code into Assembly."
authors: []
tags:
-  Compilers
categories: []
date: 2020-06-21T23:17:25+02:00

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
Consists of three stages :
  * lexer
  * parser
  * compiler

it takes C code as an input and produces an assembly code in the x86 instruction set .

Currently implemented features :

  * Arithmetic and logical operation
  * Variables
  * Switch
  * For loop
  * While loop
  * Break
  * Function definition
  * Function call
  * using Constant string
  * If statements
