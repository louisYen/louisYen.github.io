---
layout: single
author_profile: true
classes: wide
permalink: /
---

Hi, I’m He-Yen (Louis) Hsieh, a Ph.D. researcher in Computer Science at Harvard University, advised by [Prof. H. T. Kung](https://www.eecs.harvard.edu/htk/).

I enjoy building machine learning algorithms that make AI models smaller, faster, and easier to adapt. My work spans efficient AI, generative AI, large language models, and computer vision, with recent projects in model adaptation, post-training quantization, knowledge distillation, efficient inference, gaze estimation, and personalization.

Before and during my Ph.D., I have been fortunate to work with researchers at Intel, Reality Labs Research at Meta, Adobe Research, and Academia Sinica. My work has been published at CVPR, AAAI, ECCV, WACV, ICIP, and ICASSP.

I’m always happy to connect with people interested in efficient AI, model compression, generative models, or research ideas for making AI smaller, faster, easier to adapt, and still accurate.


---

## Research Roadmap

My research centers on making AI practical under limited data, compute, and memory. I started from computer vision problems such as detection, video understanding, and anomaly detection, then expanded into gaze estimation, generative AI, and efficient learning systems. More recently, my work focuses on efficient adaptation and compression for vision and language models.

<div class="roadmap-tree">

  <div class="tree-root">
    <div class="tree-node root-node">
      <div class="node-title">Efficient AI</div>
      <div class="node-desc">Smaller, faster, easier to adapt, and still accurate.</div>
    </div>
  </div>

  <div class="tree-branches">

    <div class="tree-branch branch-adaptation">
      <a class="tree-node branch-node" href="#efficient-model-adaptation">
        <div class="node-title">Efficient Model Adaptation</div>
        <div class="node-desc">
          Adapting compact models with only a few samples.
        </div>
        <div class="node-tags">PEFT/LoRA · Cross-domain adaptation · Gaze estimation</div>
      </a>

      <div class="project-list">

        <a class="project-node" href="#alfa-efficient-few-shot-model-adaptation">
          <div class="project-head">
            <span class="project-title">Alfa</span>
            <span class="project-year">2026</span>
          </div>
          <span class="project-desc">
            Few-shot cross-domain gaze adaptation by attending to pre-trained weights and learning new patterns.
          </span>
          <span class="project-meta">AAAI'26 · Model adaptation · Gaze estimation</span>
        </a>

        <a class="project-node" href="#dft-gaze-few-shot-gaze-personalization">
          <div class="project-head">
            <span class="project-title">DFT Gaze</span>
            <span class="project-year">2025</span>
          </div>
          <span class="project-desc">
            A tiny 281K-parameter gaze model for accurate real-time personalization.
          </span>
          <span class="project-meta">ICIP'25 (Spotlight) · 5-shot · Model compression</span>
        </a>

      </div>
    </div>

    <div class="tree-branch branch-compression">
      <a class="tree-node branch-node" href="#model-compression">
        <div class="node-title">Model Compression</div>
        <div class="node-desc">
          Reducing model size and inference cost for deployment.
        </div>
        <div class="node-tags">PTQ · Distillation · Efficient inference</div>
      </a>

      <div class="project-list">

        <a class="project-node" href="#calibration-free-ptq-for-llms">
          <div class="project-head">
            <span class="project-title">Calibration-free PTQ for LLMs</span>
            <span class="project-year">Ongoing</span>
          </div>
          <span class="project-desc">
            Low-bit LLM quantization without relying on calibration data.
          </span>
          <span class="project-meta">LLMs · PTQ · Quantization</span>
        </a>

        <a class="project-node" href="#dft-gaze-compact-vision-model-design">
          <div class="project-head">
            <span class="project-title">DFT Gaze</span>
            <span class="project-year">2025</span>
          </div>
          <span class="project-desc">
            Compresses gaze estimation into a small model that can still personalize.
          </span>
          <span class="project-meta">ICIP'25 (Spotlight) · Distillation · Edge AI</span>
        </a>

        <a class="project-node" href="#edit-faster-diffusion-language-model-inference">
          <div class="project-head">
            <span class="project-title">EDIT</span>
            <span class="project-year">2025</span>
          </div>
          <span class="project-desc">
            Early termination for faster diffusion language model inference.
          </span>
          <span class="project-meta">NeurIPS OPT'25 · LLMs · Efficient inference</span>
        </a>

      </div>
    </div>

    <div class="tree-branch branch-generative">
      <a class="tree-node branch-node" href="#generative-ai">
        <div class="node-title">Generative AI</div>
        <div class="node-desc">
          Building personalized and controllable generative systems.
        </div>
        <div class="node-tags">Personalization · Data synthesis · Gaze-guided interaction</div>
      </a>

      <div class="project-list">

        <a class="project-node" href="#personalized-text-to-image-generation">
          <div class="project-head">
            <span class="project-title">Personalized text-to-image generation</span>
            <span class="project-year">2023</span>
          </div>
          <span class="project-desc">
            Few-shot personalized generation from only a few user-provided examples.
          </span>
          <span class="project-meta">Personalization · Text-to-image · Diffusion models</span>
        </a>

        <a class="project-node" href="#gen4gen-generative-ai-for-training-data-synthesis">
          <div class="project-head">
            <span class="project-title">Gen4Gen</span>
            <span class="project-year">2025</span>
          </div>
          <span class="project-desc">
            Synthetic data generation for improving downstream vision models.
          </span>
          <span class="project-meta">BMVC'25 · Generative AI · Data synthesis</span>
        </a>

        <a class="project-node" href="#gazegen-gaze-guided-generation">
          <div class="project-head">
            <span class="project-title">GazeGen</span>
            <span class="project-year">2024</span>
          </div>
          <span class="project-desc">
            Gaze-guided image and video generation.
          </span>
          <span class="project-meta">Generative AI · Gaze estimation · Interaction</span>
        </a>

      </div>
    </div>

    <div class="tree-branch branch-vision">
      <a class="tree-node branch-node" href="#computer-vision">
        <div class="node-title">Computer Vision</div>
        <div class="node-desc">
          From few-shot detection to gaze and video understanding.
        </div>
        <div class="node-tags">Few-shot learning · Detection · Video understanding</div>
      </a>

      <div class="project-list">

        <a class="project-node" href="#s3r-video-anomaly-detection">
          <div class="project-head">
            <span class="project-title">S3R</span>
            <span class="project-year">2022</span>
          </div>
          <span class="project-desc">
            Video anomaly detection with weakly and self-supervised learning.
          </span>
          <span class="project-meta">ECCV'22 · Video anomaly detection</span>
        </a>

        <a class="project-node" href="#adaptive-image-transformer-one-shot-object-detection">
          <div class="project-head">
            <span class="project-title">Adaptive Image Transformer</span>
            <span class="project-year">2021</span>
          </div>
          <span class="project-desc">
            One-shot object detection for new categories.
          </span>
          <span class="project-meta">CVPR'21 · Object detection · One-shot learning</span>
        </a>

        <a class="project-node" href="#temporal-action-detection">
          <div class="project-head">
            <span class="project-title">Temporal action detection</span>
            <span class="project-year">2020–2023</span>
          </div>
          <span class="project-desc">
            Action localization in long videos across multiple settings.
          </span>
          <span class="project-meta">ICIP'20 · WACV'22 · ICASSP'23</span>
        </a>

      </div>
    </div>

  </div>
</div>

---

## Efficient Model Adaptation

### Alfa — Efficient few-shot model adaptation

Few-shot cross-domain gaze adaptation by attending to already learned pre-trained weights and learning new task-specific patterns.

### DFT Gaze — Few-shot gaze personalization

Combines distillation and fine-tuning into one solution to train a tiny 281K-parameter model for accurate personalized gaze estimation.

---

## Model Compression

### Calibration-free PTQ for LLMs

Low-bit LLM quantization without relying on calibration data.

### DFT Gaze — Compact vision model design

Compresses gaze estimation into a small model that can run efficiently while keeping strong personalization ability.

### EDIT — Faster diffusion language model inference

Reduces diffusion language model inference cost by stopping generation once the model has stabilized.

---

## Generative AI

### Personalized text-to-image generation

Few-shot personalized generation from only a few user-provided examples.

### Gen4Gen — Generative AI for training data synthesis

Creates diverse synthetic training data to improve downstream vision models.

### GazeGen — Gaze-guided generation

Uses eye gaze as an interaction signal to guide image and video generation.

---

## Computer Vision

### S3R — Video anomaly detection

Detects unusual events in long videos through weakly and self-supervised video representation learning.

### Adaptive Image Transformer — One-shot object detection

Detects new object categories from only one example.

### Temporal action detection

Finds actions in long videos by refining coarse temporal proposals into accurate action segments.
