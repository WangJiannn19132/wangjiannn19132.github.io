---
title: "Diffuse & Refine: Intrinsic Knowledge Generation and Aggregation for Incremental Object Detection"
collection: publications
permalink: /publication/2022-04-27-paper-title-number-1
# excerpt: 'xxxx'
date: 2025-04-27
venue: 'the 34th International Joint Conference on Artificial Intelligence'
paperurl: 'http://wangjiannn19132.github.io/files/paper1.pdf'
authors: 'Jianzhou Wang, Yirui Wu*, Lixin Yuan, Wenxiao Zhang, Jun Liu, Junyang Chen, Huan Wang, and Wenhai Wang'
---

Incremental Object Detection(IOD) targets at progressively extending capability of object detectors to recognize new classes. However, representation confusion between old and new classes leads to catastrophic forgetting. To alleviate this problem, we propose DiffKA, with intrinsic knowledge generated and aggregated byforward and backward diffusion, gradually establishing rigid class boundary. With incrementalstreaming data, forward diffusion spreads information to generate potential inter-class associationsamong new- and old-class prototypes within a hierarchical tree, named as Intrinsic Correlation Tre(ICT), to store intrinsic knowledge. Afterwards, backward diffusion refines and aggregates thegenerated knowledge in ICT, explicitly establishing rigid class boundary to mitigate representationconfusion.  To keep semantic consistency with extreme IOD settings, we reorganize semantic relevanceof old- and new-class prototypes in paradigms to adaptively and effectively update DiffKA.Experiments on MS COCO dataset show DiffKA achieves state-of-the-art performance on IOD tasks withsignificant advantages.
