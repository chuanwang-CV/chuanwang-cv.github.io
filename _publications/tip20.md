---
title: "Text Co-Detection in Multi-View Scene"
collection: publications
permalink: /publication/tip20
excerpt: "We address the corresponding text detection task and propose a novel text co-detection method to identify the co-occurring texts among multi-view scene images with compositions of detection and correspondence under large environmental variations.<br/><img src='/images/text1.png' width='800' height='300' align=center>"
date: 2020-02-26
venue: 'IEEE Transactions on Image Processing'
#paperurl: 'http://academicpages.github.io/files/TIP2017.pdf'


---

Multi-view scene analysis has been widely explored in computer vision, including numerous practical applications. The texts in multi-view scenes are often detected by following the
existing text detection method in a single image, which however ignores the multi-view corresponding constraint. The multi-view correspondences may contain structure, location information
and assist difficulties induced by factors like occlusion and perspective distortion, which are deficient in the single image scene.  In our text co-detection method, the visual and
geometrical correspondences are designed to explore texts holding high pairwise representation similarity and guide the exploitation of texts with geometrical correspondences, simultaneously.
To guarantee the pairwise consistency among multiple images, we additionally incorporate the cycle consistency constraint, which guarantees alignments of text correspondences in the
image set. Finally, text correspondence is represented by a permutation matrix and solved via positive semidefinite and low-rank constraints. Moreover, we also collect a new text
co-detection dataset consisting of multi-view image groups obtained from the same scene with different photographing conditions.
<br/> <img src='/images/text2.png' width="800" height = "200" align=center>


[Download paper here](http://academicpages.github.io/files/tip20.pdf)
Recommended citation: Chuan Wang, Huazhu Fu, Liang Yang, Xiaochun Cao: Text Co-Detection in Multi-View Scene. IEEE Trans. Image Process. 29: 4627-4642 (2020).
