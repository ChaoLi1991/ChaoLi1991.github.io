---
title: "1 . Self-Supervised Adversarial Hashing Networks for Cross-Modal Retrieval [CVPR'18]"
permalink: /publication/2018-02-20-Self-Supervised Adversarial Hashing Networks for Cross-Modal Retrieval
excerpt: '[PDF](https://arxiv.org/pdf/1804.01223.pdf), [Code](https://github.com/ChaoLi1991/ChaoLi1991.github.io/tree/master/files/SSAH), [Project](/publication/2018-02-20-Self-Supervised Adversarial Hashing Networks for Cross-Modal Retrieval)'
---

---
# Title
__Self-Supervised Adversarial Hashing Networks for Cross-Modal Retrieval [CVPR'2018]__  

---
# Abstract
Thanks to the success of deep learning, cross-modal retrieval has made significant progress recently. However, there still remains a crucial bottleneck: how to bridge the modality gap to further enhance the retrieval accuracy. In this paper, we propose a self-supervised adversarial hashing (__SSAH__) approach, which lies among the early attempts to incorporate adversarial learning into cross-modal hashing in a self-supervised fashion. The primary contribution of this work is that two adversarial networks are leveraged to maximize the semantic correlation and consistency of the representations between different modalities. In addition, we harness a self-supervised semantic network to discover high-level semantic information in the form of multi-label annotations. Such information guides the feature learning process and preserves the modality relationships in both the common semantic space and the Hamming space. Extensive experiments carried out on three benchmark datasets validate that the proposed SSAH surpasses the state-of-the-art methods.

---
# Framework
![image](https://github.com/ChaoLi1991/ChaoLi1991.github.io/blob/master/files/SSAH/SSAH.png)

---
# Download
[Paper](https://arxiv.org/pdf/1804.01223.pdf)  
[Code](https://github.com/ChaoLi1991/ChaoLi1991.github.io/tree/master/files/SSAH)  
Dataset: [MIRFLICKR-25K](http://press.liacs.nl/mirflickr/), [NUS-WIDE](http://lms.comp.nus.edu.sg/research/NUS-WIDE.htm), [MS COCO](http://cocodataset.org/#download)

---
# Citation
@article{li2018self,  
  title={Self-Supervised Adversarial Hashing Networks for Cross-Modal Retrieval},  
  author={Li, Chao and Deng, Cheng and Li, Ning and Liu, Wei and Gao, Xinbo and Tao, Dacheng},  
  journal={arXiv preprint arXiv:1804.01223},  
  year={2018}  
}
