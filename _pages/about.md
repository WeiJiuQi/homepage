---
permalink: /
title: "Biography"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am now a research scientist at [Ant Research](https://www.antresearch.com/). Previously, I finished my Ph.D. at [Institute of Computing Technology, Chinese Academy of Sciences](http://english.ict.cas.cn/) in 2025, advised by [Prof. Xiaodong Lee](https://www.weforum.org/people/lee-xiaodong) and [Prof. Themis Palpanas](https://helios2.mi.parisdescartes.fr/~themisp/). Before that, I earned my bachelor’s degree from Nankai University in 2019.

My research focuses on high-dimensional similarity search, vector database, data interoperation, and data management. I am open to discussion or collaboration. Feel free to contact me if you are interested in my research.

Publications
======
- **Jiuqi Wei**, Xiaodong Lee, Zhenyu Liao, Themis Palpanas, Botao Peng.\
  *Subspace Collision: An Efficient and Accurate Framework for High-dimensional Approximate Nearest Neighbor Search.*\
  **Proceedings of the ACM on Management of Data (SIGMOD) 2025** ([PDF](https://dl.acm.org/doi/pdf/10.1145/3709729), [Code](https://github.com/WeiJiuQi/SuCo)).
- **Jiuqi Wei**, Xiaodong Lee, Yufan Fu, Ying Li, Botao Peng.\
  *Dominate data by yourself: a decentralized scheme for data interoperation when data is decoupled from applications.*\
  **World Wide Web Journal (WWWJ) 2025**.
- **Jiuqi Wei**, Botao Peng, Xiaodong Lee, Themis Palpanas.\
  *DET-LSH: A Locality-Sensitive Hashing Scheme with Dynamic Encoding Tree for Approximate Nearest Neighbor Search.*\
  **Proceedings of the VLDB Endowment (VLDB) 2024** ([PDF](https://dl.acm.org/doi/pdf/10.14778/3665844.3665854), [Code](https://github.com/WeiJiuQi/DET-LSH)).
- Ying Li, **Jiuqi Wei**, Ziyu Fei, Yufan Fu, Xiaodong Lee.\
  *DiSAuth: A DNS-based secure authorization framework for protecting data decoupled from applications.*\
  **Computer Networks 2024**.
- Yufan Fu, Xiaodong Lee, **Jiuqi Wei**, Ying Li, Botao Peng.\
  *Securing the internet’s backbone: A blockchain-based and incentive-driven architecture for DNS cache poisoning defense.*\
  **Computer Networks 2024**.
- Zhixian Zhuang, Xiaodong Lee, **Jiuqi Wei**, Yufan Fu, Aiyao Zhang.\
  *CBCMS: A Compliance Management System for Cross-Border Data Transfer.*
  **IEEE International Conference on Big Data (BigData) 2024**.\
- **Jiuqi Wei**, Ying Li, Yufan Fu, Youyi Zhang, Xiaodong Lee.\
  *Data interoperating architecture (DIA): Decoupling data and applications to give back your data ownership.*
  **IEEE 47th Annual Computers, Software, and Applications Conference (COMPSAC) 2023**.
- Yufan Fu, **Jiuqi Wei**, Ying Li, Botao Peng, Xiaodong Lee.\
  *TI-DNS: A Trusted and Incentive DNS Resolution Architecture based on Blockchain.*\
  **IEEE 22nd International Conference on Trust, Security and Privacy in Computing and Communications (TrustCom) 2023**.
- Ziyu Fei, Ying Li, **Jiuqi Wei**, Yufan Fu, Botao Peng, Xiaodong Lee.\
  *FlexAuth: A Decentralized Authorization System with Flexible Delegation.*\
  **IEEE 22nd International Conference on Trust, Security and Privacy in Computing and Communications (TrustCom) 2023**.

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
