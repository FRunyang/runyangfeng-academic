---
title: "GLPose: Global-Local Representation Learning for Human Pose Estimation"
authors:
- Yingying Jiao
- Haipeng Chen
- admin
- Haoming Chen
- Sifan Wu
- Yifang Yin
- Zhenguang Liu
author_notes:
- ""
- ""
- "Corresponding Author"
date: "2022-10-06T00:00:00Z"
doi: "10.1145/3519305"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-10-06T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*ACM Transactions on Multimedia Computing, Communications, and Applications*"
publication_short: "TOMM (TOMMCAP)"

abstract: Multi-frame human pose estimation is at the core of many computer vision tasks. Although state-of-the-art approaches have demonstrated remarkable results for human pose estimation on static images, their performances inevitably come short when being applied to videos. A central issue lies in the visual degeneration of video frames induced by rapid motion and pose occlusion in dynamic environments. This problem, by nature, is insurmountable for a single frame. Therefore, incorporating complementary visual cues from other video frames becomes an intuitive paradigm. Current state-of-the-art methods usually leverage information from adjacent frames, which unfortunately place excessive focus on only the temporally nearby frames. In this paper, we argue that combining global semantically similar information and local temporal visual context will deliver more comprehensive and more robust representations for human pose estimation. Towards this end, we present an effective framework, namely global-local enhanced pose estimation (GLPose) network. Our framework consists of a feature processing module that conditionally incorporates global semantic information and local visual context to generate a robust human representation and a feature enhancement module that excavates complementary information from this aggregated representation to enhance keyframe features for precise estimation. We empirically find that the proposed GLpose outperforms existing methods by a large margin and achieves new state-of-the-art results on large benchmark datasets.


tags:

featured: false

# links:
# - name: ""
#   url: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false


---

