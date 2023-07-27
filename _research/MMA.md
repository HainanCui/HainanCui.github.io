---
title: "MMA: Multi-Camera Based Global Motion Averaging"
excerpt: "To fully perceive the surrounding environment, many intelligent robots and self-driving cars are equipped with a multi-camera system. We propose tailor-made multi-camera based motion averaging system that calibrates and fuses the rigged constraints automatically. Experiments demonstrate that our algorithm achieves superior accuracy and robustness on various data sets compared to the state-of-the-art methods. <br/><img src='/images/MMA.png' width='500'>"
collection: research
date: 2022-6-28
paperurl: 'https://ojs.aaai.org/index.php/AAAI/article/view/19927/19686'
---

<div align='center'>
  <img src="/images/MMA.png" width="500">  
</div>

## Abstract

<p align = "justify">
In order to fully perceive the surrounding environment, many intelligent robots and self-driving cars are equipped with a multi-camera system. Based on this system, the structure-from-motion (SfM) technology is used to realize scene reconstruction, but the fixed relative poses between cameras in the multi-camera system are usually not considered. This paper presents a tailor-made multi-camera based motion averaging system, where the fixed relative poses are utilized to improve the accuracy and robustness of SfM. Our approach starts by dividing the images into reference images and non-reference images, and edges in view-graph are divided into four categories accordingly. Then, a multi-camera based rotating averaging problem is formulated and solved in two stages, where an iterative re-weighted least squares scheme is used to deal with outliers. Finally, a multi-camera based translation averaging problem is formulated and a l1-norm based optimization scheme is proposed to compute the relative translations of multi-camera system and reference camera positions simultaneously. Experiments demonstrate that our algorithm achieves superior accuracy and robustness on various data sets compared to the state-of-the-art methods.
</p>

## Reference

<p align = "justify">

**Hainan Cui**, and Shuhan Shen. "MMA: Multi-Camera Based Global Motion Averaging." AAAI, Vol. 36. No. 1, 2022.

</p>