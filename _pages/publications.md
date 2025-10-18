---
layout: default
permalink: /publications/
title: "Publications"
excerpt: ""
author_profile: true
---
# 📖 Publications

1. **Fandi Gou**, Haikuo Du, Chenyu Zhao and Yunze Cai, *[A Policy-Guided Reinforcement Learning Method for Encirclement
Control in Multiobstacle Environment](https://ieeexplore.ieee.org/document/11006133)*. In IEEE Transactions on Neural Networks and Learning Systems (TNNLS), vol. 36, no. 9, pp. 17034-17046, 2025.

See work description [here](/publications/encirclement2025/).

## Subpages

Below are the publication subpages in this section. This list is generated automatically from pages whose URL contains "/publications/" (excluding this index page).

<ul>
{% assign pubs = site.pages | where_exp: "p", "p.url contains '/publications/' and p.url != '/publications/'" %}
{% for p in pubs %}
	<li><a href="{{ p.url }}">{{ p.title }}</a></li>
{% endfor %}
</ul>

<!--  
3. Keke Huang, Yimin Shi, Dujian Ding, Yifei Li, **Yang Fei**, Laks Lakshmanan, Xiaokui Xiao, ThriftLLM: On Cost-Effective Selection of Large Language Models for Optimal Query Performance, ([Preprint](https://arxiv.org/abs/2501.04901)), Oct 2024. -->

<!-- Shengyue Yao\*, **Yang Fei\***, Shanzhe Lei, Xuhong Wang, Lin Yilun, Yu Qiao, *Optimizing Organization in Multi-Agent Systems via a Time and Task Sensitive Strategy $T^2$SO: Theoretical and Practical Evidences*, (Submitted to **AAAI'25**), Aug 2024. -->
