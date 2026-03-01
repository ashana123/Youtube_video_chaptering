# Automatic Chapter Generation for Hindi-English YouTube Videos

This repository implements an end-to-end pipeline for automatic chapter generation on long-form Hindi-English (code-switched) YouTube videos using transcripts and semantic segmentation.

The work is based on our published research paper:


Automated Youtube Video Chapter…

# Overview

Long-form multilingual videos are difficult to navigate. This project proposes a novel pipeline that automatically segments videos into semantically meaningful chapters using audio transcripts, linguistic cues, and transformer-based models.

The system is designed specifically for Hindi-English code-switched content, addressing the lack of multilingual chaptering tools in existing research.

# Methodology

The pipeline follows these key steps:

Extract audio from YouTube videos

Generate timestamped transcripts using Whisper ASR

Clean and normalize transcripts

Detect semantic topic shifts and segment chapters

Generate chapter summaries and titles using transformer models

Output structured chapters in JSON format

This approach leverages temporal cues, semantic embeddings, and keyword extraction for coherent chapter segmentation. 

Automated Youtube Video Chapter…

# Evaluation

The generated chapters are evaluated using:

BLEU score (title-summary relevance)

Flesch Reading Ease (readability)

Temporal coherence metrics

Human evaluation on relevance and coherence

The results demonstrate promising performance for bilingual video understanding and segmentation. 

Automated Youtube Video Chapter…

# Dataset

The dataset consists of 437 Hindi-English YouTube videos (~20GB) with natural code-switching across domains like podcasts, interviews, and educational content. 

Automated Youtube Video Chapter…

Due to size limitations, the audio dataset is hosted externally:
👉 [https://drive.google.com/drive/my-drive]

# Tech Stack

Whisper ASR (transcription)

HuggingFace Transformers (summarization & translation)

KeyBERT (title extraction)

Python, FFmpeg, PyTorch

# Contributions

First pipeline for automatic chaptering of Hindi-English code-switched videos

Medium-scale bilingual dataset creation

Multilingual transcript segmentation and title generation framework

# Future Work

Future improvements include:

Fine-tuned multilingual transformer models

Adaptive segmentation based on semantic density

Incorporation of multimodal visual cues for better boundary detection 

Automated Youtube Video Chapter…

# Citation

If you use this work, please cite the paper:

Automatic Chapter Generation for Hindi-English YouTube Videos
Ashana Agarwal, Avani Gupta

This README is concise, research-backed, and professional — ideal for recruiters and academic reviewers.

Sources
