---
title: "Real-time multi-plane 3D reconstruction on the mobile platform"
authors:
- Jundan Luo
date: 2018-02-01T11:23:53+08:00
lastmod: 2019-10-10T11:23:53+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: []

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: The project provided multiple robust plane models with boundaries for the AR SDK user. <br> Given a 2D-structured 3D point cloud, the project aimed to cluster it into multiple separate point clouds, each reconstructing a common plane. Besides, it was an incremental plane-reconstruction method which expanded the old planes with new point clouds generated by the moving camera.

# Summary. An optional shortened abstract.
summary: The project provided multiple robust plane models with boundaries for the AR SDK user.

tags: ["AR", "computer vision", "3D plane reconstruction"]
featured: false

links:
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''#'Rabbits are jumping on the real planes: [**\[video\]Jumping rabbits!**]()'
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
#slides: example
# {{% alert note %}}
# Click the *Slides* button above to demo Academic's Markdown slides feature.
# {{% /alert %}}
---
##### There are two main difficulties:
  - Noisy and semi-dense 3D point clouds. 
  - Real-time speed requirement.