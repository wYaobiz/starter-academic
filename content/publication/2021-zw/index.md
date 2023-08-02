---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "St-trader: A spatial-temporal deep neural network for modeling stock market movement"
authors: ["Xiurui Hou", "Kai Wang", "Cheng Zhong", "Zhi Wei"]
date: 2023-07-04T10:48:23-04:00
doi: "10.1109/jas.2021.1003976"

# Schedule page publish date (NOT publication's date).
publishDate: 2023-07-04T10:48:23-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "2021 IEEE/CAA Journal of Automatica Sinica"
# publication_short: "ICCS 2023"

abstract: "Stocks that are fundamentally connected with each other tend to move together. Considering such common trends is believed to benefit stock movement forecasting tasks. However, such signals are not trivial to model because the connections among stocks are not physically presented and need to be estimated from volatile data. Motivated by this observation, we propose a framework that incorporates the inter-connection of firms to forecast stock prices. To effectively utilize a large set of fundamental features, we further design a novel pipeline. First, we use variational autoencoder (VAE) to reduce the dimension of stock fundamental information and then cluster stocks into a graph structure (fundamentally clustering). Second, a hybrid model of graph convolutional network and long-short term memory network (GCN-LSTM) with an adjacency graph matrix (learnt from VAE) is proposed for graph-structured stock market forecasting. Experiments on minute-level U.S. stock market data demonstrate that our model effectively captures both spatial and temporal signals and achieves superior improvement over baseline methods. The proposed model is promising for other applications in which there is a possible but hidden spatial dependency to improve time-series prediction."

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
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

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
