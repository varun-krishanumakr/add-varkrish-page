---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Compact representation of temporal processes in echosounder time series via matrix decomposition"
authors: ["**W-J Lee**", "V Staneva"]
date: 2020-11-30T09:00:00
doi: "10.1121/10.0002670"

# Customize
share: false
markup: md
math: true


# Schedule page publish date (NOT publication's date).
publishDate: 2020-11-30T08:30:00-08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Journal of the Acoustical Society of America"
publication_short: "J Acoust Soc Am (***Special issue on Machine Learning in Acoustics***)"

abstract: "The recent explosion in the availability of echosounder data from diverse ocean platforms has created unprecedented opportunities to observe the marine ecosystems at broad scales. However, the critical lack of methods capable of automatically discovering and summarizing prominent spatio-temporal echogram structures has limited the effective and wider use of these rich datasets. To address this challenge, we develop a data-driven methodology based on matrix decomposition that builds compact representation of long-term echosounder time series using intrinsic features in the data. In a two-stage approach, we first remove noisy outliers from the data by Principal Component Pursuit, then employ a temporally smooth Nonnegative Matrix Factorization to automatically discover a small number of distinct daily echogram patterns, whose time-varying linear combination (activation) reconstructs the dominant echogram structures. This low-rank representation provides biological information that is more tractable and interpretable than the original data, and is suitable for visualization and systematic analysis with other ocean variables. Unlike existing methods that rely on fixed, handcrafted rules, our unsupervised machine learning approach is well-suited for extracting information from data collected from unfamiliar or rapidly changing ecosystems. This work forms the basis for constructing robust time series analytics for large-scale, acoustics-based biological observation in the ocean."

# Summary. An optional shortened abstract.
summary: "We developd a data-driven methodology based on matrix
decomposition to build compact representation of long-term echosounder time
series using intrinsic features in the data."

tags: []
categories: ["sonar", "machine learning"]
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter
links:
- name: arXiv
  url: https://arxiv.org/abs/2007.02906
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, place an image named `featured.jpg/png` in your page's folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
# Set `preview_only` to `true` to just use the image for thumbnails.
image:
  caption: ""
  Placement options: 1
  focal_point: "Center"
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
