---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A Self-supervised GAN for Unsupervised Few-shot Object Recognition"
authors: []
date: 2020-08-16T12:43:28-07:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-08-16T12:43:28-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Internation Conference on Pattern Recognition (ICPR), 2020"
publication_short: "ICPR 2020"

abstract: "This paper addresses unsupervised few-shot object recognition, where all training images are unlabeled, and test images are divided into queries and a few labeled support images per object class of interest. The training and test images do not share object classes.  We extend the vanilla GAN with two loss functions, both aimed at self-supervised learning. The first is a reconstruction loss that enforces the discriminator to reconstruct the probabilistically sampled latent code which has been used for generating the ``fake'' image. The second is a triplet loss that enforces the discriminator to output image encodings that are closer for more similar images. Evaluation, comparisons, and detailed ablation studies are done in the context of few-shot classification. Our approach significantly outperforms the state of the art on the Mini-Imagenet and Tiered-Imagenet datasets."

# Summary. An optional shortened abstract.
summary: "ICPR 2020"

tags: [Unsupervised Learning, Few-shot Learning]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf:
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
