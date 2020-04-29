---
title: "Long-term tracking algorithm with the combination of multi-feature fusion and YOLO"
date: 2018-01-01
publishDate: 2020-04-28T03:11:01.126499Z
authors: ["Sicong Jiang", "Yunzhou Zhang","Xiaobo Liu"]
publication_types: ["1"]
abstract: "In recent year correlation filtering based algorithms have achieved significant performance in tracking. In traditional, the previous frame has been trained in order to get the prediction position of the next frame. However, in experiments we find that once the present frame drifts, the latter frame will be affected and accumulate error, which can cause the loss of the target eventually. In that case, the tracker cannot track a target for a long time. To solve these problems and design an efficient long-term tracking algorithm, we propose a long-term tracking algorithm by combining the short-term tracker and the YOLO v2 detector. We use the SURF algorithm to get the similarity of the tracking result and the current contrast template, once the similarity is lower than a threshold, the YOLO v2 will be activated and find the right target through a three-stage cascade selecting mechanism we designed before, then the short-term tracker will be restarted and the contrast template will be updated. In this way, the short-term tracker can be transformed to a long-term tracker which is able to track a target for a long time in complex circumstance. Besides, we also adopt the compound feature to improve our short-term tracker, so our algorithm has better accuracy and robustness. The experimental results demonstrate the proposed approach outperforms state-of-the-art approaches on large-scale benchmark datasets."
featured: false
publication: "*Chinese Conference on Image and Graphics Technologies*"
---

