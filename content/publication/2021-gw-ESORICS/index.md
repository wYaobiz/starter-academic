---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Fair Peer-to-Peer Content Delivery via Blockchain"
authors: ["Songlin He", "Yuan Lu", "Qiang Tang", "Guiling Wang", "Chase Wu"]

date: 2021-09-30
# doi: "10.1109/TNNLS.2018.2870573"

# Schedule page publish date (NOT publication's date).
date: 2021-09-30

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "2021 26th European Symposium on Research in Computer Security"
publication_short: "ESORICS 2021"

abstract: "In comparison with conventional content delivery networks, peer-to-peer (p2p) content delivery is promising to save cost and handle high peak-demand, and can also complement the decentralized storage networks such as Filecoin. However, reliable p2p delivery requires proper enforcement of delivery fairness, i.e., the deliverers should be rewarded according to their in-time delivery. Unfortunately, most existing studies on delivery fairness are based on non-cooperative game-theoretic assumptions that are arguably unrealistic in the ad-hoc p2p setting.

We for the first time put forth an expressive yet still minimalist security notion for desired fair p2p content delivery, and give two efficient solutions FairDownload
and FairStream

via the blockchain for p2p downloading and p2p streaming scenarios, respectively. Our designs not only guarantee delivery fairness to ensure deliverers be paid (nearly) proportional to their in-time delivery but also ensure the content consumers and content providers are fairly treated. The fairness of each party can be guaranteed when the other two parties collude to arbitrarily misbehave. Moreover, the systems are efficient in the sense of attaining nearly asymptotically optimal on-chain costs and deliverer communication.

We implement the protocols and build the prototype systems atop the Ethereum Ropsten network. Extensive experiments done in LAN and WAN settings showcase their high practicality."

---
