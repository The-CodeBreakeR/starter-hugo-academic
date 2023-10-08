---
title: "A Secure Sidechain for Decentralized Trading in Internet of Things"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Fangyu Gai
- Jianyu Niu
- Mohammad Jalalzai
- Seyed Ali Tabatabaee
- Chen Feng

date: "2023-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-07-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Internet of Things Journal (IoT-J)*
# publication_short: In *ICW*

abstract: Sidechains allow transaction dissemination and execution outside the blockchain main network (i.e., the mainchain), enabling a scalable, efficient, and secure financial infrastructure for the Internet of Things (IoT) without trusting any central authority. Existing sidechains either have online requirements or rely on intensive computation on a central operator, which does not meet the needs of IoT for dynamic changes and high performance. This paper proposes an alternative sidechain construction, called Cumulus, which meets the needs of IoT by leveraging the classic Byzantine fault-tolerant (BFT) consensus protocols such as PBFT that have commonly been applied in permissioned blockchains. Cumulus builds BFT-based sidechains atop public blockchains (e.g., Ethereum) using smart contracts and ensures the bidirectional safety of users’ assets. Cumulus sidechains periodically interact with the mainchain and submit checkpoints through representatives selected in an efficient and decentralized manner. The experiments show that Cumulus sidechains outperform rollup-based sidechains, and state-of-the-art sidechain constructions, achieving two and three orders of magnitude improvement in throughput and latency while retaining comparable operational cost.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Link
  url: https://ieeexplore.ieee.org/document/10197622

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

