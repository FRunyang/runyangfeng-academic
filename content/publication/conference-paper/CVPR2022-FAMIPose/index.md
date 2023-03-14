---
title: 'Temporal Feature Alignment and Mutual Information Maximization for Video-Based Human Pose Estimation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Zhenguang Liu
  - admin
  - Haoming Chen
  - Shuang Wu
  - Yixing Gao
  - Yunjun Gao
  - Xiang Wang

# Author notes (optional)
author_notes:
  - 
  - 'Corresponding Author'

date: '2022-06-23T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-06-23T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)*
publication_short: In *CVPR 2022 (ORAL)*

abstract: Multi-frame human pose estimation has long been a compelling and fundamental problem in computer vision. This task is challenging due to fast motion and pose occlusion that frequently occur in videos. State-of-the-art methods strive to incorporate additional visual evidences from neighboring frames (supporting frames) to facilitate the pose estimation of the current frame (key frame). One aspect that has been obviated so far, is the fact that current methods directly aggregate unaligned contexts across frames. The spatial-misalignment between pose features of the current frame and neighboring frames might lead to unsatisfactory results. More importantly, existing approaches build upon the straightforward pose estimation loss, which unfortunately cannot constrain the network to fully leverage useful information from neighboring frames.

To tackle these problems, we present a novel hierarchical alignment framework, which leverages coarse-to-ﬁne deformations to progressively update a neighboring frame to align with the current frame at the feature level. We further propose to explicitly supervise the knowledge extraction from neighboring frames, guaranteeing that useful complementary cues are extracted. To achieve this goal, we theoretically analyzed the mutual information between the frames and arrived at a loss that maximizes the taskrelevant mutual information. These allow us to rank No.1 in the Multi-frame Person Pose Estimation Challenge on benchmark dataset PoseTrack2017, and obtain state-of-the-art performance on benchmarks Sub-JHMDB and PoseTrack2018. Our code is released at https://github.com/Pose-Group/FAMI-Pose, hoping that it will be useful to the community.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna 

tags: [ORAL]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openaccess.thecvf.com/content/CVPR2022/papers/Liu_Temporal_Feature_Alignment_and_Mutual_Information_Maximization_for_Video-Based_Human_CVPR_2022_paper.pdf'
url_code: 'https://github.com/Pose-Group/FAMI-Pose'
url_project: 'https://github.com/Pose-Group/FAMI-Pose'
url_video: 'https://www.bilibili.com/video/BV19P4y1M71i/?spm_id_from=333.788.recommend_more_video.-1&vd_source=a84d804ab6c69041428e81bb93f56dee'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false
---





#{{% callout note %}}
#Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
#{{% /callout %}}

#{{% callout note %}}
#Create your slides in Markdown - click the _Slides_ button to check out the example.
#{{% /callout %}}

#Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).

