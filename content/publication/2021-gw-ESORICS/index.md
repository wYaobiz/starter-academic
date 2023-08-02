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

abstract: "Blockchain-based Internet of Things (BC-IoT) brings the advantages of blockchain into traditional IoT systems. In BC-IoT, the smart contract has been widely used for automatic, trusted, and decentralized applications. Smart contracts require frequent adjust and fast update due to various reasons, such as inevitable code bugs, changes of applications, or security requirements. However, previous smart contract architecture and updating mechanism are low speed and cause high overhead, because they are based on recompilation and redeployment in BC-IoT. Meanwhile, smart contract execution is so time consuming due to contract instruction dispatching and operand loading in the stack-based Ethereum virtual machine (EVM). To address these issues, we propose a new smart contract architecture and optimization mechanism for BC-IoTs, ATOM, which provides architectural supports to update contract economically and fast executing in instructionwise for the first time, to the best of our knowledge. We design a compact Application-oriented Instruction (AoI) set to describe application operations. We can construct the bytecode of smart contract from application by directly assembling templates prebuilt upon the AoIs rather than by compilation. We also present an optimized mechanism for AoI execution to enable access addressable storage place rather than the indirect access through stack. We perform ATOM on a BC-IoT testbed based on private Ethereum and Hyperledger Burrow. The experimental results highlight that ATOM is more efficient than state-of-the-art approaches. ATOM can reduce update latency by 62.7%, ledger size by 70%, and gas usage by 90% on average, respectively. Compared with the traditional smart contract architecture, ATOM can improve EVM Memory access efficiency significantly by up to 10× and achieve improvement of execution efficiency with up to 1.6×."

---
