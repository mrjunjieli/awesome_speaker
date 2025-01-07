---
title: Awesome Speaker
top: true
tag:
- Speaker Verification
categories:
- Research
---


> Hi, everyone! I’m Junjie Li [[Homepage]](https://mrjunjieli.github.io/), currently a Ph.D. student at Hong Kong Polytechnic University (PolyU) 🇭🇰.
This repository aims to help students become familiar with speaker-related tasks while also serving as a resource for my own learning and development. 


Summary of speaker related tasks, like speaker recognition, verification, diarization, spoofing, privacy, voice conversion, target speaker extraction and so on. 

# Book recommendations
* Understanding Deep learning [[pdf]](https://udlbook.github.io/udlbook/)
* Computer vision: models learning and inference [[pdf]](https://udlbook.github.io/cvbook/)
* 深入浅出强化学习：原理入门 [[pdf]](https://github.com/borninfreedom/DeepLearning/blob/master/Books/%E6%B7%B1%E5%85%A5%E6%B5%85%E5%87%BA%E5%BC%BA%E5%8C%96%E5%AD%A6%E4%B9%A0%EF%BC%9A%E5%8E%9F%E7%90%86%E5%85%A5%E9%97%A8.pdf)
* Reinforcement Learning [[pdf]](http://incompleteideas.net/book/RLbook2018.pdf)


# Toolkit
* Wespeaker[![](https://img.shields.io/github/stars/wenet-e2e/wespeaker?style=social&label=Code+Stars)](https://github.com/wenet-e2e/wespeaker)
* Wespe[![](https://img.shields.io/github/stars/wenet-e2e/wesep?style=social&label=Code+Stars)](https://github.com/wenet-e2e/wesep)

# Some interesting repos
* ![MuQ](https://img.shields.io/github/stars/tencent-ailab/MuQ?style=social&label=Code+Stars)(https://github.com/tencent-ailab/MuQ)

# Speaker Recognition/Verification:

## Speaker Models
 * overview: 
   * Overview of Speaker Modeling and Its Applications: From the Lens of Deep Speaker Representation Learning
 * i-vector 
 * d-vector (frame-level): Deep neural networks for small footprint textdependent speaker verification
 * x-vector (segment-level): 
    * X-vectors: Robust dnn embeddings for speaker recognition
    * Deep Neural Network Embeddings for Text-Independent Speaker Verification
    * ECAPA-TDNN: Emphasized Channel Attention, Propagation and Aggregation in TDNN Based Speaker Verification
 * r-vector: But system description to voxceleb speaker recognition challenge 2019
 * xi-vector: Xi-Vector Embedding for Speaker Recognition
 * Transformer based: 
   * Self Multi-Head Attention for Speaker Recognition
   * LOCAL INFORMATION MODELING WITH SELF-ATTENTION FOR SPEAKER VERIFICATION
* SPEAKER RECOGNITION FROM RAW WAVEFORM WITH SINCNET 
* Self-supervised: 
   * Self-supervised speaker embeddings 
   * Neural Predictive Coding using Convolutional Neural Networks towards Unsupervised Learning of Speaker Characteristics
* PLDA: Probabilistic Linear Discriminant Analysis for Inferences About Identity 
* Reshape Dimensions Network for Speaker Recognition
* Guided Speaker Embedding
* 



 ## Aggregation Layers 
 implementation: wespeaker/models/pooling_layers
 * Temporal Average Pooling (TAP)
 * Temporal Statistics Pooling (TSTP): X-vectors: Robust dnn embeddings for speaker recognition
 * Attentive Statistics Pooling (ASP): ECAPA-TDNN: Emphasized Channel Attention, Propagation and Aggregation in TDNN Based Speaker Verification
 

 ## Datasets 
 * Voxceleb1 
 * Voxceleb2 
 * 

 ## Challenge 
 * [NIST SRE](https://sre.nist.gov/#tab_home)


# Voice Conversion 

## Non-parallel:
* CycleGAN-VC: Non-parallel Voice Conversion Using Cycle-Consistent Adversarial Networks

## Voice Anonymization
* MODELING PSEUDO-SPEAKER UNCERTAINTY IN VOICE ANONYMIZATION

# Target Speaker Extraction
* INVESTIGATION OF SPEAKER REPRESENTATION FOR TARGET-SPEAKER SPEECH PROCESSING
* 

# Speaker Diarization 

# Spoofing 
* Towards Quantifying and Reducing Language Mismatch Effects in Cross-Lingual Speech Anti-Spoofing


# Targer Speaker ASR 


# Personalized VAD 

# Others
* Emerging Properties in Self-Supervised Vision Transformers