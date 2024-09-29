- [Awesome Speaker In Speech Field](#awesome-speaker-in-speech-field)
  * [Book recommendations](#book-recommendations)
  * [Speaker Recognition/Verification:](#speaker-recognition-verification-)
    + [Toolkit](#toolkit)
    + [Speaker Models](#speaker-models)
    + [Aggregation Layers](#aggregation-layers)
    + [Datasets](#datasets)
  * [Voice Vonversion](#voice-vonversion)
  * [Target Speaker Extraction](#target-speaker-extraction)
  * [Speaker Diarization](#speaker-diarization)
  * [Spoofing](#spoofing)


# Awesome Speaker In Speech Field 
> Hi, everyone! I’m Junjie Li [[Homepage]](https://mrjunjieli.github.io/), currently a Ph.D. student at Hong Kong Polytechnic University (PolyU) 🇭🇰.
This repository aims to help students become familiar with speaker-related tasks while also serving as a resource for my own learning and development. 


Summary of speaker related tasks, like speaker recognition, verification, diarization, spoofing, voice conversion, target speaker extraction and so on. 

## Book recommendations
* Understanding Deep learning [[pdf]](https://udlbook.github.io/udlbook/)
* Computer vision: models learning and inference [[pdf]](https://udlbook.github.io/cvbook/)


## Speaker Recognition/Verification:

### Toolkit 
* [Wespeaker](https://github.com/wenet-e2e/wespeaker)

### Speaker Models
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

 ### Aggregation Layers 
 implementation: wespeaker/models/pooling_layers
 * Temporal Average Pooling (TAP)
 * Temporal Statistics Pooling (TSTP): X-vectors: Robust dnn embeddings for speaker recognition
 * Attentive Statistics Pooling (ASP): ECAPA-TDNN: Emphasized Channel Attention, Propagation and Aggregation in TDNN Based Speaker Verification
 * 

 ### Datasets 


## Voice Vonversion 

## Target Speaker Extraction

## Speaker Diarization 

## Spoofing 