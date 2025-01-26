---
title: Awesome Speech 
top: true
tag:
- Speaker Verification
- Machine Learning
categories:
- Research
---


> Hi, everyone! I’m Junjie Li [[Homepage]](https://mrjunjieli.github.io/), currently a Ph.D. student at Hong Kong Polytechnic University (PolyU) 🇭🇰.
This repository aims to help students become familiar with speech-related tasks, such as speech separation, speaker verification, ASR, TTS and so on. 


# How to write a good paper 
* [Novelty in Science](https://perceiving-systems.blog/en/news/novelty-in-science)
* [Writing a good scientific paper](https://perceiving-systems.blog/en/post/writing-a-good-scientific-paper)



# Book recommendations
* Understanding Deep learning [[pdf]](https://udlbook.github.io/udlbook/)
* Computer vision: models learning and inference [[pdf]](https://udlbook.github.io/cvbook/)
* 深入浅出强化学习：原理入门 [[pdf]](https://github.com/borninfreedom/DeepLearning/blob/master/Books/%E6%B7%B1%E5%85%A5%E6%B5%85%E5%87%BA%E5%BC%BA%E5%8C%96%E5%AD%A6%E4%B9%A0%EF%BC%9A%E5%8E%9F%E7%90%86%E5%85%A5%E9%97%A8.pdf)
* Reinforcement Learning [[pdf]](http://incompleteideas.net/book/RLbook2018.pdf)


# Self-Supervised Learning 
* [R. Tao, K. Aik Lee, R. Kumar Das, V. Hautamäki and H. Li, "Self-Supervised Speaker Recognition with Loss-Gated Learning," ICASSP 2022 - 2022 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), Singapore, Singapore, 2022, pp. 6142-6146](https://ieeexplore.ieee.org/abstract/document/9747162)
* [Chen, T., Kornblith, S., Norouzi, M. &amp; Hinton, G.. (2020). A Simple Framework for Contrastive Learning of Visual Representations. <i>Proceedings of the 37th International Conference on Machine Learning</i>, in <i>Proceedings of Machine Learning Research</i> 119:1597-1607.](https://proceedings.mlr.press/v119/chen20j.html)
* [D. Cai, W. Wang and M. Li, "An Iterative Framework for Self-Supervised Deep Speaker Representation Learning," ICASSP 2021 - 2021 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), Toronto, ON, Canada, 2021, pp. 6728-6732](https://ieeexplore.ieee.org/abstract/document/9414713?casa_token=dhDiQr_WkPUAAAAA:vvHp2Z3mAa9Lm3UQqadlqJxpMjZ0R_2U6BPV292kdeWE1oHYSk02ctnw5ZlLpbF2ZCLxeDB5Ldkr8w)
* [H. Zhang, Y. Zou and H. Wang, "Contrastive Self-Supervised Learning for Text-Independent Speaker Verification," ICASSP 2021 - 2021 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), Toronto, ON, Canada, 2021, pp. 6713-6717](https://ieeexplore.ieee.org/abstract/document/9413351?casa_token=5SEEYwW-SLgAAAAA:G0VeicwCBQmBBnOktS2mjicuwvEFOSWkKeab_mQPNP6v5L1VtNZuj6NN3ijJKlzqXlxxPBRApm1FOA)
* [He, K., Fan, H., Wu, Y., Xie, S., & Girshick, R. (2020). Momentum contrast for unsupervised visual representation learning. In Proceedings of the IEEE/CVF conference on computer vision and pattern recognition (pp. 9729-9738).](http://openaccess.thecvf.com/content_CVPR_2020/html/He_Momentum_Contrast_for_Unsupervised_Visual_Representation_Learning_CVPR_2020_paper.html)
* [Wu, Z., Xiong, Y., Yu, S. X., & Lin, D. (2018). Unsupervised feature learning via non-parametric instance discrimination. In Proceedings of the IEEE conference on computer vision and pattern recognition (pp. 3733-3742).](http://openaccess.thecvf.com/content_cvpr_2018/html/Wu_Unsupervised_Feature_Learning_CVPR_2018_paper.html)
* Cai, D., Wang, W., & Li, M. (2021, June). An iterative framework for self-supervised deep speaker representation learning. In ICASSP 2021-2021 IEEE international conference on acoustics, speech and signal processing (ICASSP) (pp. 6728-6732). IEEE.
* Hadsell, R., Chopra, S., & LeCun, Y. (2006, June). Dimensionality reduction by learning an invariant mapping. In 2006 IEEE computer society conference on computer vision and pattern recognition (CVPR'06) (Vol. 2, pp. 1735-1742). IEEE.



# Speaker Recognition/Verification:
* **Overview**
   * Wang, S., Chen, Z., Lee, K. A., Qian, Y., & Li, H. (2024). Overview of speaker modeling and its applications: From the lens of deep speaker representation learning. IEEE/ACM Transactions on Audio, Speech, and Language Processing.
* **speaker model**
   * i-vector 
   * d-vector: Variani, E., Lei, X., McDermott, E., Moreno, I. L., & Gonzalez-Dominguez, J. (2014, May). Deep neural networks for small footprint text-dependent speaker verification. In 2014 IEEE international conference on acoustics, speech and signal processing (ICASSP) (pp. 4052-4056). IEEE.
   * x-vector
      * Snyder, D., Garcia-Romero, D., Sell, G., Povey, D., & Khudanpur, S. (2018, April). X-vectors: Robust dnn embeddings for speaker recognition. In 2018 IEEE international conference on acoustics, speech and signal processing (ICASSP) (pp. 5329-5333). IEEE.
      * Snyder, D., Garcia-Romero, D., Povey, D., & Khudanpur, S. (2017, August). Deep neural network embeddings for text-independent speaker verification. In Interspeech (Vol. 2017, pp. 999-1003).
      * Desplanques, B., Thienpondt, J., & Demuynck, K. (2020). Ecapa-tdnn: Emphasized channel attention, propagation and aggregation in tdnn based speaker verification. arXiv preprint arXiv:2005.07143.
   * r-vector Zeinali, H., Wang, S., Silnova, A., Matějka, P., & Plchot, O. (2019). But system description to voxceleb speaker recognition challenge 2019. arXiv preprint arXiv:1910.12592.
* **Uncertainty** 
   * Lee, K. A., Wang, Q., & Koshinaka, T. (2021). Xi-vector embedding for speaker recognition. IEEE Signal Processing Letters, 28, 1385-1389.
   * Wang, Q., & Lee, K. A. (2024). Cosine Scoring with Uncertainty for Neural Speaker Embedding. IEEE Signal Processing Letters.
   * Chen, L., Lee, K. A., Guo, W., & Ling, Z. H. (2024, April). Modeling Pseudo-Speaker Uncertainty in Voice Anonymization. In ICASSP 2024-2024 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP) (pp. 11601-11605). IEEE.

* Ravanelli, M., & Bengio, Y. (2018, December). Speaker recognition from raw waveform with sincnet. In 2018 IEEE spoken language technology workshop (SLT) (pp. 1021-1028). IEEE.
* Zhou, D., Wang, L., Lee, K. A., Wu, Y., Liu, M., Dang, J., & Wei, J. (2020, October). Dynamic Margin Softmax Loss for Speaker Verification. In INTERSPEECH (pp. 3800-3804).
* Cai, D., & Li, M. (2024). Leveraging asr pretrained conformers for speaker verification through transfer learning and knowledge distillation. IEEE/ACM Transactions on Audio, Speech, and Language Processing.

* **softmax**
   * L-softmax: 
      Liu, W., Wen, Y., Yu, Z., & Yang, M. (2016). Large-margin softmax loss for convolutional neural networks. arXiv preprint arXiv:1612.02295.
   * A-softmax: 
      * Li, Y., Gao, F., Ou, Z., & Sun, J. (2018, November). Angular softmax loss for end-to-end speaker verification. In 2018 11th International Symposium on Chinese Spoken Language Processing (ISCSLP) (pp. 190-194). IEEE.
      * Liu, W., Wen, Y., Yu, Z., Li, M., Raj, B., & Song, L. (2017). Sphereface: Deep hypersphere embedding for face recognition. In Proceedings of the IEEE conference on computer vision and pattern recognition (pp. 212-220).
   * AM-softmax:
      * Wang, F., Cheng, J., Liu, W., & Liu, H. (2018). Additive margin softmax for face verification. IEEE Signal Processing Letters, 25(7), 926-930.
   * DAM-softmax:
      * Zhou, D., Wang, L., Lee, K. A., Wu, Y., Liu, M., Dang, J., & Wei, J. (2020, October). Dynamic Margin Softmax Loss for Speaker Verification. In INTERSPEECH (pp. 3800-3804).


 * **Datasets**
   * Vox1: Nagrani, A., Chung, J. S., Xie, W., & Zisserman, A. (2020). Voxceleb: Large-scale speaker verification in the wild. Computer Speech & Language, 60, 101027. 
   * Vox2: Chung, J. S., Nagrani, A., & Zisserman, A. (2018). Voxceleb2: Deep speaker recognition. arXiv preprint arXiv:1806.05622. 
   * SRE: [NIST SRE](https://sre.nist.gov/#tab_home)

* Tao, R., Das, R. K., & Li, H. (2020). Audio-visual speaker recognition with a cross-modal discriminative network. arXiv preprint arXiv:2008.03894.


# Text-to-Speech 

* Ju, Z., Wang, Y., Shen, K., Tan, X., Xin, D., Yang, D., ... & Zhao, S. (2024). Naturalspeech 3: Zero-shot speech synthesis with factorized codec and diffusion models. arXiv preprint arXiv:2403.03100.




# Voice Conversion 

* CycleGAN-VC: Non-parallel Voice Conversion Using Cycle-Consistent Adversarial Networks



# Speech Separation 
* Ashihara, T., Moriya, T., Horiguchi, S., Peng, J., Ochiai, T., Delcroix, M., ... & Sato, H. (2024, December). Investigation of Speaker Representation for Target-Speaker Speech Processing. In 2024 IEEE Spoken Language Technology Workshop (SLT) (pp. 423-430). IEEE.
* Veluri, B., Itani, M., Chen, T., Yoshioka, T., & Gollakota, S. (2024, May). Look Once to Hear: Target Speech Hearing with Noisy Examples. In Proceedings of the CHI Conference on Human Factors in Computing Systems (pp. 1-16).


# Speaker Diarization 

# Spoofing 
* Towards Quantifying and Reducing Language Mismatch Effects in Cross-Lingual Speech Anti-Spoofing


# Targer Speaker ASR 


# Personalized VAD 

# Others
* Emerging Properties in Self-Supervised Vision Transformers


# Music 
* MuQ: Self-Supervised Music Representation Learning with Mel Residual Vector Quantization




# Toolkit
* Wespeaker[![](https://img.shields.io/github/stars/wenet-e2e/wespeaker?style=social&label=Code+Stars)](https://github.com/wenet-e2e/wespeaker)
* Wesep[![](https://img.shields.io/github/stars/wenet-e2e/wesep?style=social&label=Code+Stars)](https://github.com/wenet-e2e/wesep)

# Some interesting repos
* MuQ[![](https://img.shields.io/github/stars/tencent-ailab/MuQ?style=social&label=Code+Stars)](https://github.com/tencent-ailab/MuQ)