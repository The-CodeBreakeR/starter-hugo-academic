---
title: "Minimizing the Size of the Uncertainty Regions for Centers of Moving Entities"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- William Evans
- Seyed Ali Tabatabaee

date: "2024-03-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-03-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 16th Latin American Theoretical Informatics Symposium*
# publication_short: In *ICW*

abstract: "In this paper, we study the problems of computing the 1-center, centroid, and 1-median of objects moving with bounded speed in Euclidean space. We can acquire the exact location of only a constant number of objects (usually one) per unit time, but for every other object, its set of potential locations, called the object's uncertainty region, grows subject only to the speed limit. As a result, the center of the objects may be at several possible locations, called the center's uncertainty region. For each of these center problems, we design query strategies to minimize the size of the center's uncertainty region and compare its performance to an optimal query strategy that knows the trajectories of the objects, but must still query to reduce their uncertainty. For the static case of the 1-center problem in R¹, we show an algorithm that queries four objects per unit time and is 1-competitive against the optimal algorithm with one query per unit time. For the general case of the 1-center problem in R¹, the centroid problem in Rᵈ, and the 1-median problem in R¹, we prove that the Round-robin scheduling algorithm is the best possible competitive algorithm. For the center of mass problem in Rᵈ, we provide an O(log n)-competitive algorithm. In addition, for the general case of the 1-center problem in Rᵈ (d ≥ 2), we argue that no algorithm can guarantee a bounded competitive ratio against the optimal algorithm."

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Link
  url: https://link.springer.com/chapter/10.1007/978-3-031-55598-5_18

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
