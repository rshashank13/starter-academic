---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Federated Algorithm with Bayesian Approach: Omni-Fedge"
authors:
  - admin
  - B. N. Bharath
date: 2021-05-13T00:00:00Z
doi: "10.1109/ICASSP39728.2021.9413571"

# Schedule page publish date (NOT publication's date).
publishDate: 2022-11-18T22:58:46-08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "ICASSP 2021 - 2021 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)"
publication_short: "ICASSP 2021"

abstract: "In this paper, we consider the problem of Federated Learning (FL) under non-i.i.d data setting. We provide an improved estimate of the empirical loss at each node by using a weighted average of losses across nodes with a penalty term. These uneven weights to different nodes are assigned by taking a novel Bayesian approach to the problem where the problem of learning for each device/node is cast as maximizing the likelihood of a joint distribution. This joint distribution is for losses of nodes obtained by using data across devices for a given neural network of a node. We then provide a PAC learning guarantee on the objective function which reveals that the true average risk is no more than the proposed objective and the error term. We leverage this guarantee to propose an algorithm called Omni-Fedge. Using MNIST and Fashion MNIST data-sets, we show that the performance of the proposed algorithm is significantly better than existing algorithms."

# Summary. An optional shortened abstract.
summary: "We considered the problem of FL under a non-i.i.d data setting and provided a sound theoretical framework for the proposed algorithm based on a novel Bayesian approach. We also introduced a new complexity measure as a consequence of the PAC bound. Using MNIST and Fashion MNIST data-sets, we showed that the performance of the proposed algorithm is significantly better than existing algorithms with better generalization."

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

url_pdf: "https://ieeexplore.ieee.org/document/9413571"
url_code: "https://github.com/ksanu1998/Omni-Fedge/tree/main/Code"
# url_dataset:
url_poster: "https://github.com/ksanu1998/Omni-Fedge/blob/main/Explanation/ICASSP_Poster.pdf"
# url_project:
url_slides: "https://github.com/ksanu1998/Omni-Fedge/blob/main/Explanation/ICASSP_Slides.pdf"
# url_source:
url_video: "https://github.com/ksanu1998/Omni-Fedge/blob/main/Explanation/ICASSP_Presentation.mp4"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
# image:
#   caption: ""
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: ""
---
