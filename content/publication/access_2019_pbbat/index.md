---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Part-Based Background-Aware Tracking for UAV With Convolutional Features"
authors: ["Changhong Fu", "Yinqiang Zhang","Ziyuan Huang", "Ran Duan", "Zongwu Xie"]
date: 2019-06-13
doi: "https://doi.org/10.1109/ACCESS.2019.2922703"

# Schedule page publish date (NOT publication's date).
publishDate: 2019-06-13

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Access"
publication_short: "Access"

abstract: "In recent years, visual tracking is a challenging task in UAV applications. The standard correlation filter (CF) has been extensively applied for UAV object tracking. However, the CF-based tracker severely suffers from boundary effects and cannot effectively cope with object occlusion, which results in suboptimal performance. Besides, it is still a tough task to obtain an appearance model precisely with hand-crafted features. In this paper, a novel part-based tracker is proposed for the UAV. With successive cropping operations, the tracking object is separated into several parts. More specially, the background-aware correlation filters with different cropping matrices are applied. To estimate the translation and scale variation of the tracking object, a structured comparison, and a Bayesian inference approach are proposed, which jointly achieve a coarse-to-fine strategy. Moreover, an adaptive mechanism is used to update the local appearance model of each part with a Gaussian process regression method. To construct a better appearance model, features extracted from the convolutional neural network are utilized instead of hand-crafted features. Through extensive experiments, the proposed tracker reaches competitive performance on 123 challenging UAV image sequences and outperforms other 20 popular state-of-the-art visual trackers in terms of overall performance and different challenging attributes."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "access_2019_pbbat.pdf"
url_code: https://github.com/vision4robotics/PBBAT-Tracker
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video: https://youtu.be/4v5ob9YzYgE

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "Right"
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
