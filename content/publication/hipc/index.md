---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Characterizing the Performance of Deep Learning Workloads on Accelerated Edge Computing Devices"
authors:
  - Prashanthi S.K
  - admin
  - Aakash Khochare
  - Yogesh Simmhan
date: 2021-11-17T23:18:41-08:00
# doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-11-18T23:18:41-08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "28th IEEE International Conference on High Performance Computing, Data & Analytics Student Research Symposium"
publication_short: "HiPC (SRS) 2021"

abstract: "Deep Learning (DL) models have had a significant impact on domains like autonomous vehicles, urban safety and Internet of Things (IoT) by enabling low-latency inferencing on edge computing devices, close to the data source. With the massive growth in sensor and camera data from such domains, the need to maintain freshness of models through retraining, and the heightened attention to privacy, training of DL models on GPU-accelerated low-power edges like NVIDIA Jetson through techniques like federated learning is gaining importance. Such training is resource-intensive and can stress the capacity of an edge’s resources like GPU, CPU, memory and storage. While previous studies have profiled the resource usage and identified bottlenecks of ML workloads on accelerated Cloud VMs and server, such a characterization has been absent for edge devices whose field-deployments are rapidly increasing. In this work, we closely examine a ML model training on the Nvidia Jetson Xavier AGX and Xavier NX. We vary several training and device parameters such as dataset size, I/O threads and storage device, and measure the CPU and GPU compute time and utilization, fetch stalls, and end-to-end time to understand the bottlenecks in the training pipeline. Our analysis identifies several interesting insights on the effect of storage medium and caching on the training time in the edge."

# Summary. An optional shortened abstract.
summary: "In this paper, we have closely examined the system charac- teristics of ML Model training on Nvidia Jetson Xavier AGX and Xavier NX platforms. We provide a detailed analysis of the role the storage subsystem plays in model training on edge devices. We demonstrated the significance of pipelining and parallelism in avoiding data fetch stalls. Further, we analysed the role played by the Linux cache in avoiding fetch stalls on multiple dataset sizes.
"

# tags: []
# categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

# url_pdf:
# url_code:
# url_dataset:
# url_poster:
# url_project:
# url_slides:
# url_source:
# url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
# image:
#   caption: ""
#   focal_point: "Left"
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
