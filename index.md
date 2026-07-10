---
layout: single
author_profile: true
classes: wide
permalink: /
---

<div class="about-section">

  <img class="about-photo-float" src="/assets/images/profile.jpg" alt="He-Yen (Louis) Hsieh">

  <p>
    Hi, I’m He-Yen (Louis) Hsieh, a Ph.D. candidate in Computer Science at Harvard University, advised by
    <a href="https://www.eecs.harvard.edu/htk/">Prof. H. T. Kung</a>.
  </p>

  <p>
    I enjoy building machine learning algorithms that make AI models smaller, faster, and easier to adapt.
    My work spans efficient AI, generative AI, large language models, and computer vision, with recent projects
    in model adaptation, post-training quantization, knowledge distillation, efficient inference, gaze estimation,
    and personalization.
  </p>

  <p>
    Before and during my Ph.D., I have been fortunate to work with researchers at Intel, Reality Labs Research at Meta,
    Adobe Research, and Academia Sinica. My work has been published at CVPR, AAAI, ECCV, WACV, ICIP, and ICASSP.
  </p>

  <p>
    I’m always happy to connect with people interested in efficient AI, model compression, generative models,
    or research ideas for making AI smaller, faster, easier to adapt, and still accurate.
  </p>

</div>

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
        <div class="node-tags">AR/VR · On-device AI · Personalization · Human-computer interaction</div>
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
          <span class="project-meta">AR/VR · Edge AI · 5-shot adaptation · Model Compression</span>
        </a>

        <a class="project-node" href="#dft-gaze-few-shot-gaze-personalization">
          <div class="project-head">
            <span class="project-title">DFT Gaze</span>
            <span class="project-year">2025</span>
          </div>
          <span class="project-desc">
            A tiny 281K-parameter gaze model for accurate real-time personalization.
          </span>
          <span class="project-meta">AR/VR · Real-time eye tracking · Edge AI · Model Compression</span>
        </a>

      </div>
    </div>

    <div class="tree-branch branch-compression">
      <a class="tree-node branch-node" href="#model-compression">
        <div class="node-title">Model Compression</div>
        <div class="node-desc">
          Reducing model size and inference cost for deployment.
        </div>
        <div class="node-tags">LLM deployment · Quantization · Efficient inference · Edge AI</div>
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
          <span class="project-meta">LLM deployment · Low-bit quantization · Memory-efficient inference</span>
        </a>

        <a class="project-node" href="#dft-gaze-compact-vision-model-design">
          <div class="project-head">
            <span class="project-title">DFT Gaze</span>
            <span class="project-year">2025</span>
          </div>
          <span class="project-desc">
            Compresses gaze estimation into a small model that can still personalize.
          </span>
          <span class="project-meta">AR/VR · Real-time eye tracking · Edge AI · Model Compression</span>
        </a>

        <a class="project-node" href="#edit-faster-diffusion-language-model-inference">
          <div class="project-head">
            <span class="project-title">EDIT</span>
            <span class="project-year">2025</span>
          </div>
          <span class="project-desc">
            Early termination for faster diffusion language model inference.
          </span>
          <span class="project-meta">Reasoning LLMs · Test-time compute · Efficient inference</span>
        </a>

      </div>
    </div>

    <div class="tree-branch branch-generative">
      <a class="tree-node branch-node" href="#generative-ai">
        <div class="node-title">Generative AI</div>
        <div class="node-desc">
          Building personalized and controllable generative systems.
        </div>
        <div class="node-tags">Creative AI · Synthetic data · Personalized generation · Gaze-guided interactive AI</div>
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
          <span class="project-meta">Creative AI · Personalized generation · Few-shot generation</span>
        </a>

        <a class="project-node" href="#gen4gen-generative-ai-for-training-data-synthesis">
          <div class="project-head">
            <span class="project-title">Gen4Gen</span>
            <span class="project-year">2025</span>
          </div>
          <span class="project-desc">
            Synthetic data generation for improving downstream vision models.
          </span>
          <span class="project-meta">Synthetic data · Vision model training · Data generation</span>
        </a>

        <a class="project-node" href="#gazegen-gaze-guided-generation">
          <div class="project-head">
            <span class="project-title">GazeGen</span>
            <span class="project-year">2024</span>
          </div>
          <span class="project-desc">
            Gaze-guided image and video generation.
          </span>
          <span class="project-meta">Interactive AI · Gaze control · Multimodal generation</span>
        </a>

      </div>
    </div>

    <div class="tree-branch branch-vision">
      <a class="tree-node branch-node" href="#computer-vision">
        <div class="node-title">Computer Vision</div>
        <div class="node-desc">
          Object detection, video anomaly detection, and action localization
        </div>
        <div class="node-tags">Video understanding · Object detection · Action localization · Few-shot learning</div>
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
          <span class="project-meta">Video understanding · Safety AI · Weak supervision</span>
        </a>

        <a class="project-node" href="#adaptive-image-transformer-one-shot-object-detection">
          <div class="project-head">
            <span class="project-title">Adaptive Image Transformer</span>
            <span class="project-year">2021</span>
          </div>
          <span class="project-desc">
            One-shot object detection for new categories.
          </span>
          <span class="project-meta">Object detection · Data-efficient vision · One-shot learning</span>
        </a>

        <a class="project-node" href="#temporal-action-detection">
          <div class="project-head">
            <span class="project-title">Temporal action detection</span>
            <span class="project-year">2020–2023</span>
          </div>
          <span class="project-desc">
            One-shot temporal action detection with zoom-in attention.
          </span>
          <span class="project-meta">Video understanding · Action localization · Zoom-in attention · One-shot learning</span>
        </a>

      </div>
    </div>

  </div>
</div>

---

<div class="roadmap-details">

  <section id="efficient-model-adaptation" class="detail-section branch-adaptation">
    <h2>Efficient Model Adaptation</h2>
    <div class="detail-grid">

      <article id="alfa-efficient-few-shot-model-adaptation" class="detail-card">
        <div class="detail-head">
          <h3>Alfa — Efficient few-shot model adaptation</h3>
          <span class="detail-year">2026</span>
        </div>
        <p>
          Adapts to new domains with only 5 samples by reusing pre-trained knowledge, making the model 5× smaller while keeping or improving accuracy.
        </p>
        <div class="detail-tags">AAAI'26 · Model adaptation · Gaze estimation</div>
      </article>

      <article id="dft-gaze-few-shot-gaze-personalization" class="detail-card">
        <div class="detail-head">
          <h3>DFT Gaze — Few-shot gaze personalization</h3>
          <span class="detail-year">2025</span>
        </div>
        <p>
          Compresses gaze estimation to a tiny 281K-parameter model, keeping 90% of the precision of a 10× larger model while supporting real-time personalization on edge devices.
        </p>
        <div class="detail-tags">ICIP'25 (Spotlight) · 5-shot · Model compression</div>
      </article>

    </div>
  </section>

  <section id="model-compression" class="detail-section branch-compression">
    <h2>Model Compression</h2>
    <div class="detail-grid">

      <article id="calibration-free-ptq-for-llms" class="detail-card">
        <div class="detail-head">
          <h3>Calibration-free PTQ for LLMs</h3>
          <span class="detail-year">Ongoing</span>
        </div>
        <p>
          Makes 3-/4-bit LLM deployment easier when calibration data is unavailable or hard to collect.
        </p>
        <div class="detail-tags">LLMs · PTQ · Quantization</div>
      </article>

      <article id="dft-gaze-compact-vision-model-design" class="detail-card">
        <div class="detail-head">
          <h3>DFT Gaze — Compact vision model design</h3>
          <span class="detail-year">2025</span>
        </div>
        <p>
          Compresses gaze estimation to a tiny 281K-parameter model, keeping 90% of the precision of a 10× larger model while supporting real-time personalization on edge devices.
        </p>
        <div class="detail-tags">ICIP'25 (Spotlight) · Distillation · Edge AI</div>
      </article>

      <article id="edit-faster-diffusion-language-model-inference" class="detail-card">
        <div class="detail-head">
          <h3>EDIT — Faster diffusion language model inference</h3>
          <span class="detail-year">2025</span>
        </div>
        <p>
          Speeds up diffusion-based language model reasoning by stopping inference once generation has stabilized.
        </p>
        <div class="detail-tags">NeurIPS OPT'25 · LLMs · Efficient inference</div>
      </article>

    </div>
  </section>

  <section id="generative-ai" class="detail-section branch-generative">
    <h2>Generative AI</h2>
    <div class="detail-grid">

      <article id="personalized-text-to-image-generation" class="detail-card">
        <div class="detail-head">
          <h3>Personalized text-to-image generation</h3>
          <span class="detail-year">2023</span>
        </div>
        <p>
          Few-shot personalized generation from only a few user-provided examples.
        </p>
        <div class="detail-tags">Personalization · Text-to-image · Diffusion models</div>
      </article>

      <article id="gen4gen-generative-ai-for-training-data-synthesis" class="detail-card">
        <div class="detail-head">
          <h3>Gen4Gen — Generative AI for training data synthesis</h3>
          <span class="detail-year">2025</span>
        </div>
        <p>
          Builds a generative pipeline to create diverse synthetic training data for stronger downstream vision models.
        </p>
        <div class="detail-tags">BMVC'25 · Generative AI · Data synthesis</div>
      </article>

      <article id="gazegen-gaze-guided-generation" class="detail-card">
        <div class="detail-head">
          <h3>GazeGen — Gaze-guided generation</h3>
          <span class="detail-year">2024</span>
        </div>
        <p>
          Turns gaze into a natural control signal for interactive image and video generation.
        </p>
        <div class="detail-tags">Generative AI · Gaze estimation · Interaction</div>
      </article>

    </div>
  </section>

  <section id="computer-vision" class="detail-section branch-vision">
    <h2>Computer Vision</h2>
    <div class="detail-grid">

      <article id="s3r-video-anomaly-detection" class="detail-card">
        <div class="detail-head">
          <h3>S3R — Video anomaly detection</h3>
          <span class="detail-year">2022</span>
        </div>
        <p>
          Detects abnormal events in videos with weaker supervision, reducing the need for heavy manual annotation.
        </p>
        <div class="detail-tags">ECCV'22 · Video anomaly detection</div>
      </article>

      <article id="adaptive-image-transformer-one-shot-object-detection" class="detail-card">
        <div class="detail-head">
          <h3>Adaptive Image Transformer — One-shot object detection</h3>
          <span class="detail-year">2021</span>
        </div>
        <p>
          Recognizes new object categories from only one example, making detection more flexible.
        </p>
        <div class="detail-tags">CVPR'21 · Object detection · One-shot learning</div>
      </article>

      <article id="temporal-action-detection" class="detail-card">
        <div class="detail-head">
          <h3>Temporal action detection</h3>
          <span class="detail-year">2020–2023</span>
        </div>
        <p>
          Finds actions in long videos from only one example, using zoom-in attention to refine coarse-to-fine action locations.
        </p>
        <div class="detail-tags">ICASSP'23 · One-shot learning · Action detection · Zoom-in attention</div>
      </article>

    </div>
  </section>

</div>
