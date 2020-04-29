---
title: "Long-term tracking algorithm using deep features and a single shot multibox detector"
date: 2018-01-01
publishDate: 2020-04-28T03:24:27.060039Z
authors: ["Jianing Zhang", "Sicong Jiang", "Yunzhou Zhang"]
publication_types: ["2"]
abstract: "The ability for computers to target and track objects within video sequences has attracted increasing amounts of attention in recent years. Many tracking algorithms adopt correlation filtering-based algorithms, in which targeting of features in the previous video frame is essential to predicting the target's position in the next frame. A serious problem in tracking is drift. If drift occurs in the present frame, it becomes increasingly difficult to correct this error in later frames, which can lead to loss of the tracked target and greatly reduced tracking accuracy and stability. To solve this problem and improve tracking performance, we propose an algorithm that incorporates deep features. A sparse representation method is used to filter deep features and improve their complexity. Then, a Siamese network is used to judge the similarities between the target and template and determine a confidence level. Next, a single shot multibox detector (SSD) is introduced to support tracking, which is activated when the confidence level falls below a certain threshold. The correct target can be found by scanning the present frame using the detector and then updating the template. The confidence level is then reduced and the SSD continues working to resolve the drift. Tracking stability and accuracy are greatly improved after the redetection process. We use large-scale benchmark datasets to demonstrate that the proposed approach performs better than existing state-of-the-art approaches."
featured: false
publication: "*Journal of Electronic Imaging*"
---

