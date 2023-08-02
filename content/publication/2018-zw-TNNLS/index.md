---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "A deep learning approach to competing risks representation in peer-to-peer lending"
authors: ["Fei Tan", "Xiurui Hou", "Jie Zhang", "Zhi Wei", "Zhenyu Yan"]

date: 2018-10-10T10:48:23-04:00
# doi: "10.1109/TNNLS.2018.2870573"

# Schedule page publish date (NOT publication's date).
publishDate: 2018-10-10T10:48:23-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "2018 IEEE Transactions on Neural Networks and Learning Systems"
publication_short: "TNNLS 2018"

abstract: "Online peer-to-peer (P2P) lending is expected to benefit both investors and borrowers due to their low transaction cost and the elimination of expensive intermediaries. From the lenders' perspective, maximizing their return on investment is an ultimate goal during their decision-making procedure. In this paper, we explore and address a fundamental problem underlying such a goal: how to represent the two competing risks, charge-off and prepayment, in funded loans. We propose to model both potential risks simultaneously, which remains largely unexplored until now. We first develop a hierarchical grading framework to integrate two risks of loans both qualitatively and quantitatively. Afterward, we introduce an end-to-end deep learning approach to solve this problem by breaking it down into multiple binary classification subproblems that are amenable to both feature representation and risks learning. Particularly, we leverage deep neural networks to jointly solve these subtasks, which leads to the in-depth exploration of the interaction involved in these tasks. To the best of our knowledge, this is the first attempt to characterize competing risks for loans in P2P lending via deep neural networks. The comprehensive experiments on real-world loan data show that our methodology is able to achieve an appealing investment performance by modeling the competition within and between risks explicitly and properly. The feature analysis based on saliency maps provides useful insights into payment dynamics of loans for potential investors intuitively."

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
