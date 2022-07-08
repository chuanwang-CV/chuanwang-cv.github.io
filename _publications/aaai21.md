---
title: "Why Do Attributes Propagate in Graph Convolutional Neural Networks?"
collection: publications
permalink: /publication/aaai21
excerpt: "In this paper, we aim at providing a novel explanation to the question of “Why do attributes propagate in GCNNs?”, which not only gives the essence of the oversmoothing, but also illustrates why the GCN extensions, including multiscale GCN and GCN with initial residual, can improve the performance. T<img src='/images/aaai22result.png' width='800' height='300' align=center>"
date: 2021-2-01
venue: 'AAAI'
#paperurl: 'http://academicpages.github.io/files/TIP2017.pdf'


---



<html>

  <table width="80%" style="margin-left: auto; margin-right: auto;">
    <tr>
      <td  width="50%" style="text-align:justify; text-justify:distribute-all-lines; text-align-last:justify">
      Many efforts have been paid to enhance Graph Convolutional Network from the perspective of propagation under the philosophy that “Propagation is the essence of the GCNNs”. Unfortunately, its adverse effect is over-smoothing, which makes the performance dramatically drop. To prevent the over-smoothing, many variants are presented. However, the perspective of propagation can’t provide an intuitive and unified interpretation to their effect on prevent over-smoothing.  an intuitive Graph Representation Learning (GRL) framework is presented. GRL simply constrains the node representation similar with the original attribute, and encourages the connected nodes possess similar representations (pairwise constraint). Based on the proposed GRL, exiting GCN and its extensions can be proved as different numerical optimization algorithms, such as gradient descent, of our proposed GRL framework. Inspired by the superiority of conjugate gradient descent compared to common gradient descent, a novel Graph Conjugate Convolutional (GCC) network is presented to approximate the solution to GRL with fast convergence.      
      </td>
      <td width="30%">
        <img src='/images/aaai21-2.png' width="300" height = "200" align=center>
      </td>
    </tr>
  </table>

</html>
[Download paper here](http://academicpages.github.io/files/aaai21.pdf)

Recommended citation: Chuan Wang, Hua Zhang, Liang Yang, Xiaochun Cao, Hongkai Xiong. Multiple Semantic Matching on Augmented N-Partite Graph for Object Co-Segmentation. IEEE Trans. Image Process. 26(12): 5825-5839 (2017).
