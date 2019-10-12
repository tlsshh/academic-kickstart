---
title: "Inductive transfer learning from surface normal estimation for intrinsic image decomposition"
authors:
- Jundan Luo, Zhaoyang Huang
date: 2019-10-10T11:23:53+08:00
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

abstract: The project aims to decompose an indoor single image into a shading image and a reflectance image based on deep neural networks. To solve two main problems in shading estimation, we propose to do inductive transfer learning with inductive biases from surface normal estimation. Our proposed framework significantly improves the realism of the image editing application. To our knowledge, we outperform the state-of-the-art works in shading estimation.

# Summary. An optional shortened abstract.
summary: The project leverages deep neural networks to decompose an indoor single image into a shading image and a reflectance image.

tags: ["AR", "computer vision", "intrinsic image decomposition", "shading estimation"]
featured: false

links:
url_video: 'https://www.youtube.com/watch?v=htht3CGYiHk'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'the original input image (small) and the editted image (large): [**longer editted image sequences \[video\]**](https://www.youtube.com/watch?v=htht3CGYiHk)'
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
##### Our goal is to resolve two main problems in shading estimation:
  - Distinguishing shading from reflectance -> inductive biases from surface normal estimation
  - Lack of training data -> inductive transfer learning