---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Robust Scalable Part-Based Visual Tracking for UAV with Background-Aware Correlation Filter"
authors: "Changhong Fu, Yinqiang Zhang, Ran Duan, Zongwu Xie"
date: 2018-10
doi: "https://doi.org/10.1109/ROBIO.2018.8665251"

# Schedule page publish date (NOT publication's date).
publishDate: 2018-10

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "2018 IEEE International Conference on Robotics and Biomimetics"
publication_short: "ROBIO 2018"

abstract: "Robust visual tracking for the unmanned aerial vehicle (UAV) is a challenging task in different types of civilian UAV applications. Although the classical correlation filter (CF) has been widely applied for UAV object tracking, the background of the object is not learned in the classical CF. In addition, the classical CF cannot estimate the object scale changes, and it is not able to cope with object occlusion effectively. Part-based tracking approach is often used for the
visual tracker to solve the occlusion issue. However, its real-time performance for the UAV cannot be achieved due to the high
cost of object appearance updating. In this paper, a novel robust visual tracker is presented for the UAV. The object is initially
divided into multiple parts, and different background-aware correlation filters are applied for these divided object parts, respectively. An efficient coarse-to-fine strategy with structure comparison and Bayesian inference approach is proposed to locate
object and estimate the object scale changes. In addition, an adaptive threshold is presented to update each local appearance
model with a Gaussian process regression method. Qualitative and quantitative tests show that the presented visual tracking
algorithm reaches real-time performance (i.e., more than twenty frames per second) on an i7 processor with 640×360 image resolution, and performs favorably against the most popular state-of-the-art visual trackers in terms of robustness and accuracy. To the best of our knowledge, it is the first time that this novel scalable part-based visual tracker is presented, and applied for the UAV tracking applications."

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

url_pdf:
url_code: https://github.com/vision4robotics/SPBACF-Tracker
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video: https://www.youtube.com/watch?v=qm9StK3jqN4&feature=youtu.be

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
