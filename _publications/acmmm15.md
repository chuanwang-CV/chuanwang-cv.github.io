---
title: "Deep People Counting in Extremely Dense Crowds"
collection: publications
permalink: /publication/acmmm15
excerpt: "  This project provides the first deep crowd counting work with negative sampling, and presents a new dataset with large counting range. <br/> <img src='/images/counting1.png' width='800' height = '250' align=center>"
date: 2015-11-06
venue: 'ACM MultiMedia'
#paperurl: 'http://academicpages.github.io/files/ACMMM15.pdf'
#citation: 'Chuan Wang, Hua Zhang, Liang Yang, Si Liu, Xiaochun Cao. Deep People Counting in Extremely Dense Crowds. ACM Multimedia 2015: 1299-1302'
---
People counting in extremely dense crowds is an important step for video surveillance and anomaly warning. The problem becomes especially more challenging due to the lack of training samples, severe occlusions, cluttered scenes and variation of perspective. Existing methods either resort to auxiliary human and face detectors or surrogate by estimating the density of crowds. Most of them rely on hand-crafted features, such as SIFT, HOG etc, and thus are prone to fail when density grows or the training sample is scarce. Our method has following characteristics. Firstly, it is a deep model built on CNN to automatically learn e↵ective features for counting. Besides, to weaken influence of background like buildings and trees, we purposely enrich the training data with expanded negative samples whose ground truth counting is set as zero. With these negative samples, the robustness can be enhanced.
<br/> <img src='/images/acmmm15framework.png' width="800" height = "300" align=center>


[Download paper here](http://academicpages.github.io/files/ACMMM15.pdf)

Recommended citation: Chuan Wang, Hua Zhang, Liang Yang, Si Liu, Xiaochun Cao. Deep People Counting in Extremely Dense Crowds. ACM Multimedia 2015: 1299-1302.
