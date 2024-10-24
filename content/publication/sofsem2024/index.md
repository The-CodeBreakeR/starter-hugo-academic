---
title: "Fractional Bamboo Trimming and Distributed Windows Scheduling"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Arash Beikmohammadi
- William Evans
- Seyed Ali Tabatabaee

date: "2024-02-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-02-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 49th International Conference on Current Trends in Theory and Practice of Computer Science (SOFSEM)*
# publication_short: In *ICW*

abstract: This paper studies two related scheduling problems fractional bamboo trimming and distributed windows scheduling. In the fractional bamboo trimming problem, we are given n bamboos with different growth rates and cut fractions. At the end of each day, we can cut a fraction of one bamboo. The goal is to design a perpetual schedule of cuts to minimize the height of the tallest bamboo ever. For this problem, we present a 2-approximation algorithm. In addition, we prove upper bounds on the approximation factors of well-known algorithms Reduce-Max and Reduce-Fastest(x) for this problem. In the closely related windows scheduling problem, given a multiset of positive integers W = {w₁, ..., wₙ}, we want to schedule n pages on broadcasting channels such that the time interval between any two consecutive appearances of the i-th page (1 ≤ i ≤ n) is at most wᵢ. The goal of this problem is to minimize the number of channels. We provide an algorithm for the windows scheduling problem that uses at most ⌈(d(W) + 1) / 0.75⌉ channels, where d(W) = ∑(i=1 to n)(1/wᵢ). When d(W) ≤ 46, our algorithm guarantees a smaller upper bound on the number of channels than the best-known algorithm in the literature. We also describe the first approximation algorithm for the windows scheduling problem in a distributed setting, where input data is partitioned among a set of m machines. Furthermore, we introduce patterns of some multisets with d(W) ≤ 1 for which windows scheduling on one channel (i.e., pinwheel scheduling) is impossible.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Link
  url: https://link.springer.com/chapter/10.1007/978-3-031-52113-3_5

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
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
