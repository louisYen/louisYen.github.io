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

<div class="roadmap-tree">

  <div class="tree-root">
    <div class="tree-node root-node">
      <div class="node-title">Efficient AI</div>
      <div class="node-desc">Smaller, faster, easier to adapt, and still accurate.</div>
    </div>
  </div>

  <div class="tree-branches">

    <div class="tree-branch">
      <a class="tree-node branch-node" href="#efficient-model-adaptation">
        <div class="node-title">Efficient Model Adaptation</div>
        <div class="node-desc">
          Adapting compact models with only a few samples and limited trainable parameters.
        </div>
        <div class="node-tags">PEFT · SVD · Few-shot · Gaze</div>
      </a>

      <div class="project-list">
        <a class="project-node" href="#alfa-efficient-few-shot-model-adaptation">
          <span class="project-title">Alfa</span>
          <span class="project-desc">
            Achieves accurate few-shot adaptation by reusing useful low-rank patterns from pre-trained models.
          </span>
        </a>

        <a class="project-node" href="#dft-gaze-few-shot-gaze-personalization">
          <span class="project-title">DFT Gaze</span>
          <span class="project-desc">
            Combines distillation and fine-tuning into one solution for a tiny 281K-parameter personalized gaze model.
          </span>
        </a>
      </div>
    </div>

    <div class="tree-branch">
      <a class="tree-node branch-node" href="#model-compression">
        <div class="node-title">Model Compression</div>
        <div class="node-desc">
          Shrinking models and reducing inference cost through PTQ, distillation, and compact design.
        </div>
        <div class="node-tags">PTQ · LLMs · Distillation · Efficient inference</div>
      </a>

      <div class="project-list">
        <a class="project-node" href="#calibration-free-ptq-for-llms">
          <span class="project-title">Calibration-free PTQ for LLMs</span>
          <span class="project-desc">
            Makes low-bit LLM quantization practical without relying on calibration data.
          </span>
        </a>

        <a class="project-node" href="#dft-gaze-compact-vision-model-design">
          <span class="project-title">DFT Gaze</span>
          <span class="project-desc">
            Makes gaze estimation small enough for efficient deployment without losing the ability to personalize.
          </span>
        </a>

        <a class="project-node" href="#edit-faster-diffusion-language-model-inference">
          <span class="project-title">EDIT</span>
          <span class="project-desc">
            Reduces diffusion language model inference cost by stopping generation once the model has stabilized.
          </span>
        </a>
      </div>
    </div>

    <div class="tree-branch">
      <a class="tree-node branch-node" href="#generative-ai">
        <div class="node-title">Generative AI</div>
        <div class="node-desc">
          Building personalized and controllable generation systems with diffusion models, LLMs, and gaze interaction.
        </div>
        <div class="node-tags">Diffusion · Personalization · Layout · Gaze</div>
      </a>

      <div class="project-list">
        <a class="project-node" href="#personalized-text-to-image-generation">
          <span class="project-title">Personalized text-to-image generation</span>
          <span class="project-desc">
            Explores 5-shot personalized generation from only a few user-provided examples.
          </span>
        </a>

        <a class="project-node" href="#gen4gen-generative-ai-for-training-data-synthesis">
          <span class="project-title">Gen4Gen</span>
          <span class="project-desc">
            Creates diverse synthetic training data to improve downstream vision models.
          </span>
        </a>

        <a class="project-node" href="#gazegen-gaze-guided-generation">
          <span class="project-title">GazeGen</span>
          <span class="project-desc">
            Turns eye gaze into an interaction signal for guiding image and video generation.
          </span>
        </a>
      </div>
    </div>

    <div class="tree-branch">
      <a class="tree-node branch-node" href="#computer-vision">
        <div class="node-title">Computer Vision</div>
        <div class="node-desc">
          Designing vision models for gaze estimation, anomaly detection, one-shot detection, and action understanding.
        </div>
        <div class="node-tags">CVPR · ECCV · ICIP · ICASSP</div>
      </a>

      <div class="project-list">
        <a class="project-node" href="#s3r-video-anomaly-detection">
          <span class="project-title">S3R</span>
          <span class="project-desc">
            Detects unusual events in long videos by learning stronger video representations.
          </span>
        </a>

        <a class="project-node" href="#adaptive-image-transformer-one-shot-object-detection">
          <span class="project-title">Adaptive Image Transformer</span>
          <span class="project-desc">
            Detects new object categories from only one example by matching proposals with attention.
          </span>
        </a>

        <a class="project-node" href="#temporal-action-detection">
          <span class="project-title">Temporal action detection</span>
          <span class="project-desc">
            Finds actions in long videos by refining coarse temporal proposals into accurate segments.
          </span>
        </a>
      </div>
    </div>

  </div>
</div>

---

## Efficient Model Adaptation

### Alfa — Efficient few-shot model adaptation

Achieves accurate few-shot adaptation by reusing useful low-rank patterns from pre-trained models.

### DFT Gaze — Few-shot gaze personalization

Combines distillation and fine-tuning into one solution to train a tiny 281K-parameter model for accurate personalized gaze estimation.

---

## Model Compression

### Calibration-free PTQ for LLMs

Makes low-bit LLM quantization practical without relying on calibration data.

### DFT Gaze — Compact vision model design

Makes gaze estimation small enough for efficient deployment without losing the ability to personalize.

### EDIT — Faster diffusion language model inference

Reduces diffusion language model inference cost by stopping generation once the model has stabilized.

---

## Generative AI

### Personalized text-to-image generation

Explores 5-shot personalized generation from only a few user-provided examples.

### Gen4Gen — Generative AI for training data synthesis

Creates diverse synthetic training data to improve downstream vision models.

### GazeGen — Gaze-guided generation

Turns eye gaze into an interaction signal for guiding image and video generation.

---

## Computer Vision

### S3R — Video anomaly detection

Detects unusual events in long videos by learning stronger video representations.

### Adaptive Image Transformer — One-shot object detection

Detects new object categories from only one example by matching proposals with attention.

### Temporal action detection

Finds actions in long videos by refining coarse temporal proposals into accurate segments.
