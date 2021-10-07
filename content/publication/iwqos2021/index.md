---
title: "Cumulus: A Secure BFT-based Sidechain for Off-chain Scaling"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Fangyu Gai
- Jianyu Niu
- Seyed Ali Tabatabaee
- Chen Feng
- Mohammad Jalalzai

date: "2021-06-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-06-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the IEEE/ACM 29th International Symposium on Quality of Service (IWQoS)*
# publication_short: In *ICW*

abstract: Sidechains enable off-chain scaling by sending transactions in a private network rather than broadcasting them in the public blockchain (i.e., the mainchain) network. To this end, classic Byzantine fault-tolerant (BFT) consensus protocols such as PBFT seem an excellent fit to fuel sidechains for their permissioned settings and inherent robustness. However, designing a secure and efficient BFT-based sidechain protocol remains an open challenge.This paper presents Cumulus, a novel BFT-based sidechain framework for blockchains to achieve off-chain scaling without compromising any security and efficiency properties of both sides’ consensus protocols. Cumulus encompasses a novel cryptographic sortition algorithm called Proof-of-Wait to fairly select sidechain nodes to communicate with the mainchain in an efficient and decentralized manner. To further reduce the operational cost, Cumulus provides an optimistic checkpointing approach in which the mainchain will not verify checkpoints unless disputes happen. Meanwhile, end-users enjoy a two-step withdrawal protocol, ensuring that they can safely collect assets back to the mainchain without relying on the BFT committee. Our experiments show that Cumulus sidechains outperform ZK-Rollup, another promising sidechain construction, achieving one and two orders of magnitude improvement in throughput and latency while retaining comparable operational cost.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Custom Link
- url: http://example.org

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
