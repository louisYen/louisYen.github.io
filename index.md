---
layout: single
author_profile: true
permalink: /
---

Hi, I’m He-Yen (Louis) Hsieh, a Ph.D. researcher in Computer Science at Harvard University, advised by [Prof. H. T. Kung](https://www.eecs.harvard.edu/htk/).

I enjoy building machine learning algorithms that make AI models smaller, faster, and easier to adapt. My work spans efficient AI, generative AI, large language models, and computer vision, with recent projects in model adaptation, post-training quantization, knowledge distillation, efficient inference, gaze estimation, and personalization.

Before and during my Ph.D., I have been fortunate to work with researchers at Intel, Reality Labs Research at Meta, Adobe Research, and Academia Sinica. My work has been published at CVPR, AAAI, ECCV, WACV, ICIP, and ICASSP.

I’m always happy to connect with people interested in efficient AI, model compression, generative models, or research ideas for making AI smaller, faster, easier to adapt, and still accurate.

---

## Research Roadmap

<div class="roadmap">

  <div class="roadmap-root">
    <div class="roadmap-card root-card">
      <div class="roadmap-title">Efficient AI</div>
      <div class="roadmap-desc">
        Making AI models smaller, faster, easier to adapt, and still accurate.
      </div>
    </div>
  </div>

  <div class="roadmap-branches">

    <a class="roadmap-card" href="#efficient-model-adaptation">
      <div class="roadmap-title">Efficient Model Adaptation</div>
      <div class="roadmap-desc">
        Adapting compact models with only a few samples, without adding extra inference-time cost.
      </div>
      <div class="roadmap-tags">PEFT · SVD · Few-shot adaptation · Gaze</div>
    </a>

    <a class="roadmap-card" href="#model-compression">
      <div class="roadmap-title">Model Compression</div>
      <div class="roadmap-desc">
        Shrinking models and reducing inference cost through quantization, distillation, and compact design.
      </div>
      <div class="roadmap-tags">PTQ · LLMs · Quantization · Distillation</div>
    </a>

    <a class="roadmap-card" href="#generative-ai">
      <div class="roadmap-title">Generative AI</div>
      <div class="roadmap-desc">
        Building personalized and controllable generation systems with diffusion models, LLMs, and gaze interaction.
      </div>
      <div class="roadmap-tags">Diffusion · Personalization · Layout control · Gaze</div>
    </a>

    <a class="roadmap-card" href="#computer-vision">
      <div class="roadmap-title">Computer Vision</div>
      <div class="roadmap-desc">
        Designing vision models for gaze estimation, anomaly detection, one-shot detection, and action understanding.
      </div>
      <div class="roadmap-tags">CVPR · ECCV · ICIP · ICASSP</div>
    </a>

  </div>
</div>

---

## Efficient Model Adaptation

- **Alfa — Efficient few-shot model adaptation**  
  Achieves accurate adaptation with only a few samples by reusing useful low-rank patterns from pre-trained models.

- **DFT Gaze — Few-shot gaze personalization**  
  Combines distillation and fine-tuning into a single solution to train a tiny 281K-parameter model for accurate personalized gaze estimation.

---

## Model Compression

- **Calibration-free PTQ for LLMs**  
  Improves low-bit LLM quantization without calibration data by using the structure already stored in model weights.

- **DFT Gaze — Compact vision model design**  
  Turns a much larger gaze model into a lightweight model that can run efficiently on edge devices.

- **EDIT — Faster diffusion language model inference**  
  Reduces diffusion language model inference cost by stopping generation once the model has already become stable.

---

## Generative AI

- **Personalized text-to-image generation**  
  Explores few-shot personalized generation, where a model learns a new visual concept from only a few user-provided examples.

- **Gen4Gen — Generative AI for training data synthesis**  
  Creates diverse synthetic training data using generative models to improve downstream vision models.

- **GazeGen — Gaze-guided generation**  
  Uses eye gaze as an interaction signal to guide image and video generation.

---
