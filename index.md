---
layout: single
author_profile: true
classes: wide home-page
permalink: /
---

<div class="about-section">

  <img
    class="about-photo-float"
    src="/assets/images/profile.jpg"
    alt="He-Yen (Louis) Hsieh"
  >

  <p>
    Hi, I'm He-Yen (Louis) Hsieh, a
    <strong class="about-keyword">Ph.D. candidate in Computer Science at Harvard University</strong>,
    advised by
    <a href="https://www.eecs.harvard.edu/htk/">Prof. H. T. Kung</a>.
  </p>

  <p>
    I enjoy building
    <strong class="about-keyword">machine learning algorithms</strong>
    that make AI models
    <strong class="about-impact">smaller, faster, and easier to adapt</strong>
    for real-world deployment. My work spans
    <strong class="about-keyword">efficient AI</strong>,
    <strong class="about-keyword">generative AI</strong>,
    <strong class="about-keyword">large language models</strong>, and
    <strong class="about-keyword">computer vision</strong>, with recent projects
    in model adaptation, post-training quantization, knowledge distillation,
    efficient inference, gaze estimation, and personalization.
  </p>

  <p>
    What I enjoy most is turning research ideas into working AI systems:
    <strong class="about-keyword">designing new algorithms</strong>,
    <strong class="about-keyword">building prototypes</strong>,
    and making new ideas practical.
  </p>

  <p>
    Before and during my Ph.D., I have been fortunate to work with researchers at
    <strong class="about-keyword">Intel</strong>,
    <strong class="about-keyword">Reality Labs Research at Meta</strong>,
    <strong class="about-keyword">Adobe Research</strong>, and
    <strong class="about-keyword">Academia Sinica</strong>.
    My work has been published at CVPR, AAAI, ECCV, WACV, ICIP, and ICASSP.
  </p>

  <p>
    I'm always happy to connect with people interested in efficient AI,
    model compression, generative models, or research ideas for making AI
    smaller, faster, easier to adapt, and still accurate.
  </p>

</div>

<nav class="home-section-nav" aria-label="Homepage sections">

  <span class="home-section-nav-label">
    Explore
  </span>

  <a href="#visualizing-ideas">
    <i class="fas fa-eye" aria-hidden="true"></i>
    Visualizing Ideas
  </a>

  <a href="#research-roadmap">
    <i class="fas fa-map" aria-hidden="true"></i>
    Research Roadmap
  </a>

  <a href="#how-ai-works-with-less">
    <i class="fas fa-compress-alt" aria-hidden="true"></i>
    How AI Works with Less
  </a>

</nav>

---

<h2 id="visualizing-ideas">Visualizing Ideas</h2>

I enjoy using visual diagrams, animations, and interactive demos to make technical ideas easier to understand. For example, during my time as a teaching assistant, I built a step-by-step visualization of Dijkstra's algorithm to explain graph search. I also like making research more accessible through demos, including GazeGen and Gen4Gen.

<div class="visual-demo">
  <video controls poster="/assets/images/dijkstra-thumbnail.png">
    <source src="/assets/videos/dijkstra-demo.mp4" type="video/mp4">
  </video>
  <p class="visual-demo-caption">
    Step-by-step visualization of Dijkstra's algorithm.
  </p>
</div>

---

<h2 id="research-roadmap">Research Roadmap</h2>

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
        <div class="node-title">Efficient AI Deployment</div>
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
        <div class="node-tags">Creative AI · Synthetic data · Personalized generation · Gaze-guided interactive AI · Few-shot learning</div>
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
          <span class="project-meta">Synthetic data · Vision model training · Data generation · Few-shot generation</span>
        </a>

        <a class="project-node" href="#gazegen-gaze-guided-generation">
          <div class="project-head">
            <span class="project-title">GazeGen</span>
            <span class="project-year">2024</span>
          </div>
          <span class="project-desc">
            Gaze-guided image and video generation.
          </span>
          <span class="project-meta">Interactive AI · Gaze control · Multimodal generation · Few-shot learning</span>
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
          Adapts gaze models to new users and domains with only 5 samples by reusing pre-trained knowledge, making the model 5× smaller while keeping or improving accuracy. The same low-rank adaptation idea also extends to diffusion-based language models for reasoning.
        </p>
        <div class="detail-use">
          <div class="detail-use-title">
            <i class="fas fa-lightbulb"></i> Use when
          </div>
          
            <div class="detail-use-list">
              <li>A pre-trained model needs compact adaptation.</li>
              <li>Only a few target samples are available.</li>
              <li>More trainable capacity is needed without increasing inference-time model size.</li>
          </div>
        </div>
        <div class="detail-tags">AAAI'26 · Model adaptation · Gaze estimation</div>

        <div class="detail-links">
          <a href="https://arxiv.org/pdf/2603.08445" class="detail-link">
            <i class="fas fa-file-pdf"></i> Paper
          </a>
        </div>
      </article>

      <article id="dft-gaze-few-shot-gaze-personalization" class="detail-card">
        <div class="detail-head">
          <h3>DFT Gaze — Few-shot gaze personalization</h3>
          <span class="detail-year">2025</span>
        </div>
        <p>
          Compresses gaze estimation to a tiny 281K-parameter model, keeping 90% of the precision of a 10× larger model while supporting real-time personalization on edge devices.
        </p>

        <div class="detail-use">
          <div class="detail-use-title">
            <i class="fas fa-lightbulb"></i> Use when
          </div>
          
            <div class="detail-use-list">
              <li>A large vision model is too slow for real-time deployment.</li>
              <li>Personalization is needed with only a few user samples.</li>
              <li>A compact model must stay accurate under edge-device constraints.</li>
          </div>
        </div>
        <div class="detail-tags">ICIP'25 (Spotlight) · 5-shot · Model compression</div>

        <div class="detail-links">
          <a href="https://www.eecs.harvard.edu/htk/static/files/2025-icip-hsieh-li-zhang-ting-chang-de%20salvo-liu-kung.pdf" class="detail-link">
            <i class="fas fa-file-pdf"></i> Paper
          </a>
        </div>
      </article>

    </div>
  </section>

  <section id="model-compression" class="detail-section branch-compression">
    <h2>Efficient AI Deployment</h2>
    <div class="detail-grid">

      <article id="calibration-free-ptq-for-llms" class="detail-card">
        <div class="detail-head">
          <h3>Calibration-free PTQ for LLMs</h3>
          <span class="detail-year">Ongoing</span>
        </div>
        <p>
          Makes 3-/4-bit LLM deployment easier when calibration data is unavailable or hard to collect.
        </p>

        <div class="detail-use">
          <div class="detail-use-title">
            <i class="fas fa-lightbulb"></i> Use when
          </div>
        
          <div class="detail-use-list">
            <li>Make small LLMs even smaller with low-bit quantization.</li>
            <li>Quantize without calibration data for deployment budgets.</li>
          </div>
        </div>
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

        <div class="detail-use">
          <div class="detail-use-title">
            <i class="fas fa-lightbulb"></i> Use when
          </div>
          
            <div class="detail-use-list">
              <li>A large vision model is too slow for real-time deployment.</li>
              <li>Personalization is needed with only a few user samples.</li>
              <li>A compact model must stay accurate under edge-device constraints.</li>
          </div>
        </div>
        <div class="detail-tags">ICIP'25 (Spotlight) · Distillation · Edge AI</div>

        <div class="detail-links">
          <a href="https://www.eecs.harvard.edu/htk/static/files/2025-icip-hsieh-li-zhang-ting-chang-de%20salvo-liu-kung.pdf" class="detail-link">
            <i class="fas fa-file-pdf"></i> Paper
          </a>
        </div>
      </article>

      <article id="edit-faster-diffusion-language-model-inference" class="detail-card">
        <div class="detail-head">
          <h3>EDIT — Faster diffusion language model inference</h3>
          <span class="detail-year">2025</span>
        </div>
        <p>
          Speeds up diffusion-based language model reasoning by stopping inference once generation has stabilized.
        </p>

        <div class="detail-use">
          <div class="detail-use-title">
            <i class="fas fa-lightbulb"></i> Use when
          </div>
      
          <ul class="detail-use-list">
            <li>Diffusion-based language models use more inference steps than needed.</li>
            <li>Reasoning tasks need faster generation under test-time compute budgets.</li>
          </ul>
        </div>
        <div class="detail-tags">NeurIPS OPT'25 · LLMs · Efficient inference</div>

        <div class="detail-links">
          <a href="https://arxiv.org/pdf/2512.00670" class="detail-link">
            <i class="fas fa-file-pdf"></i> Paper
          </a>
          <a href="https://github.com/louisYen/EDIT" class="detail-link">
            <i class="fab fa-github"></i> Code
          </a>
        </div>
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

        <div class="detail-use">
          <div class="detail-use-title">
            <i class="fas fa-lightbulb"></i> Use when
          </div>
      
          <ul class="detail-use-list">
            <li>Personalized generation is needed from only a few examples.</li>
            <li>Multiple user-provided concepts must appear in one generated image.</li>
          </ul>
        </div>
        <div class="detail-tags">Personalization · Text-to-image · Diffusion models · Few-shot generation</div>
      </article>

      <article id="gen4gen-generative-ai-for-training-data-synthesis" class="detail-card">
        <div class="detail-head">
          <h3>Gen4Gen — Generative AI for training data synthesis</h3>
          <span class="detail-year">2025</span>
        </div>
        <p>
          Builds a generative pipeline to create diverse synthetic training data for stronger downstream vision models.
        </p>

        <div class="detail-use">
          <div class="detail-use-title">
            <i class="fas fa-lightbulb"></i> Use when
          </div>
        
          <ul class="detail-use-list">
            <li>Generative models can be used to build a data synthesis pipeline.</li>
            <li>Real training data is limited, expensive, or hard to collect.</li>
          </ul>
        </div>
        <div class="detail-tags">BMVC'25 · Generative AI · Data synthesis · Few-shot generation</div>

        <div class="detail-links">
          <a href="https://bmva-archive.org.uk/bmvc/2025/assets/papers/Paper_28/paper.pdf" class="detail-link">
            <i class="fas fa-file-pdf"></i> Paper
          </a>
          <a href="https://github.com/louisYen/Gen4Gen" class="detail-link">
            <i class="fab fa-github"></i> Code
          </a>
        </div>
      </article>

      <article id="gazegen-gaze-guided-generation" class="detail-card">
        <div class="detail-head">
          <h3>GazeGen — Gaze-guided generation</h3>
          <span class="detail-year">2024</span>
        </div>
        <p>
          Turns gaze into a natural control signal for interactive image and video generation.
        </p>

        <div class="detail-use">
          <div class="detail-use-title">
            <i class="fas fa-lightbulb"></i> Use when
          </div>
      
          <ul class="detail-use-list">
            <li>User intent should guide generation without heavy manual interaction.</li>
            <li>Gaze can serve as a lightweight control signal for interactive AI systems.</li>
          </ul>
        </div>
        <div class="detail-tags">Generative AI · Gaze estimation · Interaction · Few-shot learning</div>

        <div class="detail-links">
          <a href="https://arxiv.org/pdf/2411.04335" class="detail-link">
            <i class="fas fa-file-pdf"></i> Paper
          </a>
          <a href="https://github.com/louisYen/GazeGen-demo" class="detail-link">
            <i class="fas fa-play-circle"></i> Demo
          </a>
        </div>
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

        <div class="detail-use">
          <div class="detail-use-title">
            <i class="fas fa-lightbulb"></i> Use when
          </div>
        
          <ul class="detail-use-list">
            <li>Video understanding needs to scale without dense frame-level labels.</li>
            <li>Rare events must be detected from compact normal-pattern representations.</li>
          </ul>
        </div>
        <div class="detail-tags">ECCV'22 · Video anomaly detection</div>

        <div class="detail-links">
          <a href="https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136730727.pdf" class="detail-link">
            <i class="fas fa-file-pdf"></i> Paper
          </a>
          <a href="https://github.com/louisYen/S3R" class="detail-link">
            <i class="fab fa-github"></i> Code
          </a>
        </div>
      </article>

      <article id="adaptive-image-transformer-one-shot-object-detection" class="detail-card">
        <div class="detail-head">
          <h3>Adaptive Image Transformer — One-shot object detection</h3>
          <span class="detail-year">2021</span>
        </div>
        <p>
          Recognizes new object categories from only one example, making detection more flexible.
        </p>


        <div class="detail-use">
          <div class="detail-use-title">
            <i class="fas fa-lightbulb"></i> Use when
          </div>
          <ul class="detail-use-list">
            <li>New object categories must be detected from only one example.</li>
            <li>Full training data is unavailable for every new class.</li>
          </ul>
        </div>
        <div class="detail-tags">CVPR'21 · Object detection · One-shot learning</div>

        <div class="detail-links">
          <a href="https://openaccess.thecvf.com/content/CVPR2021/papers/Chen_Adaptive_Image_Transformer_for_One-Shot_Object_Detection_CVPR_2021_paper.pdf" class="detail-link">
            <i class="fas fa-file-pdf"></i> Paper
          </a>
          <a href="https://github.com/CAIVIAC/AIT" class="detail-link">
            <i class="fab fa-github"></i> Code
          </a>
        </div>
      </article>

      <article id="temporal-action-detection" class="detail-card">
        <div class="detail-head">
          <h3>Temporal action detection</h3>
          <span class="detail-year">2020–2023</span>
        </div>
        <p>
          Finds actions in long videos from only one example, using zoom-in attention to refine coarse-to-fine action locations.
        </p>

        <div class="detail-use">
          <div class="detail-use-title">
            <i class="fas fa-lightbulb"></i> Use when
          </div>
          <ul class="detail-use-list">
            <li>Long videos need action localization with limited examples.</li>
            <li>Coarse video cues must be refined into precise temporal action boundaries.</li>
          </ul>
        </div>
        <div class="detail-tags">ICASSP'23 · One-shot learning · Action detection · Zoom-in attention</div>

        <div class="detail-links">
          <a href="https://ieeexplore.ieee.org/document/10095638" class="detail-link">
            <i class="fas fa-file-pdf"></i> ICASSP 2023
          </a>
        </div>
      </article>

    </div>
  </section>

</div>


---

<section class="less-ai-section" id="how-ai-works-with-less">

  <header class="less-ai-header">
    <h2>
      How Can AI Work with <span class="less-ai-title-accent">Less</span>?
    </h2>
  
    <p>
      Choose a constraint and see how my projects help an existing AI model work with less.
    </p>
  </header>
  
  <div class="less-ai-model-card">

    <div class="less-ai-model-heading">
      <strong>Your Existing AI Model</strong>
    </div>
  
    <div class="less-ai-model-bridge">
      <span>Across model types</span>
    </div>
  
    <div class="less-ai-model-types">
      <span><i class="fas fa-eye"></i> Vision</span>
      <span><i class="fas fa-comment-alt"></i> Language</span>
      <span><i class="fas fa-image"></i> Generation</span>
      <span><i class="fas fa-video"></i> Video</span>
    </div>
  
  </div>

  <div class="less-ai-question">
    What constraint does your AI face?
  </div>

  <!-- Constraint buttons -->
  <div class="less-ai-tabs" role="tablist" aria-label="AI constraints">

    <button
      type="button"
      class="less-ai-tab theme-data active"
      data-constraint="data"
      role="tab"
      aria-selected="true"
    >
      <i class="fas fa-database"></i>

      <span>
        <strong>Less Data</strong>
        <small>Learn with fewer samples or labels</small>
      </span>
    </button>

    <button
      type="button"
      class="less-ai-tab theme-parameters"
      data-constraint="parameters"
      role="tab"
      aria-selected="false"
    >
      <i class="fas fa-compress-alt"></i>

      <span>
        <strong>Less Parameters</strong>
        <small>Build smaller deployable models</small>
      </span>
    </button>

    <button
      type="button"
      class="less-ai-tab theme-compute"
      data-constraint="compute"
      role="tab"
      aria-selected="false"
    >
      <i class="fas fa-bolt"></i>

      <span>
        <strong>Less Compute</strong>
        <small>Reduce inference cost and latency</small>
      </span>
    </button>

    <button
      type="button"
      class="less-ai-tab theme-interaction"
      data-constraint="interaction"
      role="tab"
      aria-selected="false"
    >
      <i class="fas fa-hand-pointer"></i>

      <span>
        <strong>Less Interaction</strong>
        <small>Enable lightweight natural control</small>
      </span>
    </button>

  </div>

  <!-- Interactive content -->
  <div
    class="less-ai-workspace theme-data"
    id="less-ai-workspace"
    role="tabpanel"
  >

    <aside class="less-ai-project-column">

      <div class="less-ai-column-label">
        Related projects
      </div>

      <div
        class="less-ai-project-list"
        id="less-ai-project-list"
      ></div>

    </aside>

    <div class="less-ai-demo-column">

      <div class="less-ai-demo-top">

        <span
          class="less-ai-demo-category"
          id="less-ai-demo-category"
        >
          Less Data
        </span>

        <span class="less-ai-animation-label">
          <i class="fas fa-cogs" aria-hidden="true"></i>
          How it works
        </span>

      </div>

      <h3 id="less-ai-demo-title">Alfa</h3>

      <p
        class="less-ai-demo-description"
        id="less-ai-demo-description"
      ></p>

      <div
        class="less-ai-flow"
        id="less-ai-flow"
        aria-live="polite"
      >

        <div class="less-ai-flow-step">
          <span class="less-ai-step-number">1</span>
          <small id="less-ai-step-label-1">Start</small>
          <strong id="less-ai-step-value-1"></strong>
        </div>

        <div class="less-ai-flow-arrow">
          <i class="fas fa-arrow-right"></i>
        </div>

        <div class="less-ai-flow-step">
          <span class="less-ai-step-number">2</span>
          <small id="less-ai-step-label-2">Constraint</small>
          <strong id="less-ai-step-value-2"></strong>
        </div>

        <div class="less-ai-flow-arrow">
          <i class="fas fa-arrow-right"></i>
        </div>

        <div class="less-ai-flow-step">
          <span class="less-ai-step-number">3</span>
          <small id="less-ai-step-label-3">Method</small>
          <strong id="less-ai-step-value-3"></strong>
        </div>

        <div class="less-ai-flow-arrow">
          <i class="fas fa-arrow-right"></i>
        </div>

        <div class="less-ai-flow-step">
          <span class="less-ai-step-number">4</span>
          <small id="less-ai-step-label-4">Outcome</small>
          <strong id="less-ai-step-value-4"></strong>
        </div>

      </div>

      <div class="less-ai-impact">

        <span>
          <i class="fas fa-lightbulb"></i>
          Why it matters
        </span>

        <p id="less-ai-demo-impact"></p>

      </div>

    </div>

  </div>

</section>


<script>
document.addEventListener("DOMContentLoaded", function () {

  const constraints = {

    data: {
      label: "Less Data",
      theme: "theme-data",

      projects: [
        {
          title: "Alfa",
          icon: "fas fa-project-diagram",
        
          description:
            "Adapts a compact pre-trained model to a new user or domain using only five unlabeled target samples, without increasing inference-time model size.",
        
          steps: [
            ["Model", "Pre-trained model, compressed 5×"],
            ["Constraint", "5 unlabeled samples; more adaptation capacity needed"],
            ["Method", "Attend to pre-trained filters with compact low-rank adaptation"],
            ["Outcome", "More training capacity, no inference-time size growth"]
          ],
        
          impact:
            "Enables few-shot adaptation under both data and deployment constraints, adding training capacity without enlarging the deployed model."
        },

        {
          title: "DFT Gaze",
          icon: "fas fa-eye",
        
          description:
            "Compresses a pre-trained gaze model to 281K parameters, then personalizes it with only a few user samples for real-time on-device inference.",
        
          steps: [
            ["Model", "Pre-trained gaze model"],
            ["Constraint", "Few user samples and real-time limits"],
            ["Method", "Distill and fine-tune a compact student"],
            ["Outcome", "281K personalized gaze model"]
          ],
        
          impact:
            "Brings personalized gaze estimation to resource-constrained devices with only a few user samples."
        },

        {
          title: "Adaptive Image Transformer",
          icon: "fas fa-search",

          description:
            "Detects an unseen object category from only one reference image by adapting visual features to the target object.",

          steps: [
            ["Start", "Existing object detector"],
            ["Constraint", "One reference image"],
            ["Method", "Adaptive feature matching"],
            ["Outcome", "Detect a new object category"]
          ],

          impact:
            "Useful when new visual categories appear faster than complete training datasets can be collected."
        },

        {
          title: "Temporal Action Detection",
          icon: "fas fa-film",

          description:
            "Finds an action in a long video from one support example and progressively refines its temporal boundaries.",

          steps: [
            ["Start", "Long untrimmed video"],
            ["Constraint", "One action example"],
            ["Method", "Attention zooming"],
            ["Outcome", "Localized matching action interval"]
          ],

          impact:
            "Supports one-shot temporal localization when dense action annotations are unavailable."
        },

        {
          title: "S3R",
          icon: "fas fa-video",

          description:
            "Learns compact normal-pattern representations from weak supervision and reconstructs features to identify abnormal events.",

          steps: [
            ["Start", "Large video corpus"],
            ["Constraint", "Weak labels; scarce rare-event examples"],
            ["Method", "Reconstruct features from a sparse normal-pattern dictionary"],
            ["Outcome", "Detect anomalies from reconstruction residuals"]
          ],

          impact:
            "Scales video anomaly detection without requiring dense frame-level labels across large video collections."
        },

        {
          title: "Gen4Gen",
          icon: "fas fa-images",

          description:
            "Uses generative models as a data pipeline to create diverse image-text pairs for personalized generation.",

          steps: [
            ["Start", "Limited image-text data"],
            ["Constraint", "Insufficient training diversity"],
            ["Method", "Generative data pipeline"],
            ["Outcome", "More training pairs and stronger generation"]
          ],

          impact:
            "Turns a generative model into a data engine when real examples are limited or difficult to collect."
        },

        {
          title: "Personalized Generation",
          icon: "fas fa-palette",
        
          description:
            "Learns multiple user-provided concepts from only a few images for controllable personalized generation.",
        
          steps: [
            ["Start", "General image generator"],
            ["Constraint", "Few images per concept"],
            ["Method", "Few-shot multi-concept personalization"],
            ["Outcome", "Controllable personalized generation"]
          ],
        
          impact:
            "Learns multiple personalized concepts from only a few examples and generates them in new images."
        }
      ]
    },


    parameters: {
      label: "Less Parameters",
      theme: "theme-parameters",

      projects: [
        {
          title: "Alfa",
          icon: "fas fa-project-diagram",
        
          description:
            "Adapts a compact pre-trained model to a new user or domain using only five unlabeled target samples, without increasing inference-time model size.",
        
          steps: [
            ["Model", "Pre-trained model, compressed 5×"],
            ["Constraint", "5 unlabeled samples; more adaptation capacity needed"],
            ["Method", "Attend to pre-trained filters with compact low-rank adaptation"],
            ["Outcome", "More training capacity, no inference-time size growth"]
          ],
        
          impact:
            "Enables few-shot adaptation under both data and deployment constraints, adding training capacity without enlarging the deployed model."
        },

        {
          title: "DFT Gaze",
          icon: "fas fa-eye",
        
          description:
            "Compresses a pre-trained gaze model to 281K parameters, then personalizes it with only a few user samples for real-time on-device inference.",
        
          steps: [
            ["Model", "Pre-trained gaze model"],
            ["Constraint", "Few user samples and real-time limits"],
            ["Method", "Distill and fine-tune a compact student"],
            ["Outcome", "281K personalized gaze model"]
          ],
        
          impact:
            "Brings personalized gaze estimation to resource-constrained devices with only a few user samples."
        },

        {
          title: "Calibration-free Post-training Quantization (PTQ)",
          icon: "fas fa-microchip",
        
          description:
            "Makes small LLMs even smaller with 3-/4-bit post-training quantization, without calibration data.",
        
          steps: [
            ["Model", "Small LLM"],
            ["Constraint", "Limited deployment memory"],
            ["Method", "Calibration-free 3-/4-bit PTQ"],
            ["Outcome", "Smaller low-bit LLM"]
          ],
        
          impact:
            "Reduces memory requirements for local or resource-constrained LLM deployment without calibration data."
        }
      ]
    },


    compute: {
      label: "Less Compute",
      theme: "theme-compute",

      projects: [
        {
          title: "EDIT",
          icon: "fas fa-stopwatch",

          description:
            "Reduces unnecessary test-time computation by stopping diffusion language model inference once generation stabilizes.",

          steps: [
            ["Start", "Diffusion language model"],
            ["Constraint", "Too many inference steps"],
            ["Method", "Detect generation stabilization"],
            ["Outcome", "Stop early with fewer steps"]
          ],

          impact:
            "Speeds up reasoning without spending the full inference budget on every example."
        },

        {
          title: "Alfa",
          icon: "fas fa-project-diagram",
        
          description:
            "Adapts a compact pre-trained model to a new user or domain using only five unlabeled target samples, without increasing inference-time model size.",
        
          steps: [
            ["Model", "Pre-trained model, compressed 5×"],
            ["Constraint", "5 unlabeled samples; more adaptation capacity needed"],
            ["Method", "Attend to pre-trained filters with compact low-rank adaptation"],
            ["Outcome", "More training capacity, no inference-time size growth"]
          ],
        
          impact:
            "Enables few-shot adaptation under both data and deployment constraints, adding training capacity without enlarging the deployed model."
        },

        {
          title: "DFT Gaze",
          icon: "fas fa-eye",
        
          description:
            "Compresses a pre-trained gaze model to 281K parameters, then personalizes it with only a few user samples for real-time on-device inference.",
        
          steps: [
            ["Model", "Pre-trained gaze model"],
            ["Constraint", "Few user samples and real-time limits"],
            ["Method", "Distill and fine-tune a compact student"],
            ["Outcome", "281K personalized gaze model"]
          ],
        
          impact:
            "Brings personalized gaze estimation to resource-constrained devices with only a few user samples."
        },

        {
          title: "Calibration-free Post-training Quantization (PTQ)",
          icon: "fas fa-microchip",

          description:
            "Reduces weight precision to support lighter low-bit inference for small language models.",

          steps: [
            ["Start", "Small full-precision LLM"],
            ["Constraint", "Memory and data movement"],
            ["Method", "3-/4-bit quantization"],
            ["Outcome", "Lighter low-bit inference"]
          ],

          impact:
            "Reduces model memory and data movement for local or resource-constrained language-model deployment."
        }
      ]
    },


    interaction: {
      label: "Less Interaction",
      theme: "theme-interaction",

      projects: [
        {
          title: "GazeGen",
          icon: "fas fa-magic",

          description:
            "Uses gaze as a lightweight control signal for interactive image and video generation.",

          steps: [
            ["Start", "Image or video generator"],
            ["Constraint", "Heavy manual interaction"],
            ["Method", "Gaze-conditioned control"],
            ["Outcome", "Hands-free visual generation"]
          ],

          impact:
            "Lets users control generative AI simply by looking, without repeated mouse or touch interaction."
        },

        {
          title: "DFT Gaze",
          icon: "fas fa-eye",
        
          description:
            "Compresses a pre-trained gaze model to 281K parameters, then personalizes it with only a few user samples for real-time on-device inference.",
        
          steps: [
            ["Model", "Pre-trained gaze model"],
            ["Constraint", "Few user samples and real-time limits"],
            ["Method", "Distill and fine-tune a compact student"],
            ["Outcome", "281K personalized gaze model"]
          ],
        
          impact:
            "Brings personalized gaze estimation to resource-constrained devices with only a few user samples."
        },

        {
          title: "Personalized Generation",
          icon: "fas fa-palette",
        
          description:
            "Learns multiple user-provided concepts from only a few images for controllable personalized generation.",
        
          steps: [
            ["Start", "General image generator"],
            ["Constraint", "Few images per concept"],
            ["Method", "Few-shot multi-concept personalization"],
            ["Outcome", "Controllable personalized generation"]
          ],
        
          impact:
            "Learns multiple personalized concepts from only a few examples and generates them in new images."
        }
      ]
    }
  };


  const tabs =
    document.querySelectorAll(".less-ai-tab");

  const workspace =
    document.getElementById("less-ai-workspace");

  const projectList =
    document.getElementById("less-ai-project-list");

  const categoryElement =
    document.getElementById("less-ai-demo-category");

  const titleElement =
    document.getElementById("less-ai-demo-title");

  const descriptionElement =
    document.getElementById("less-ai-demo-description");

  const impactElement =
    document.getElementById("less-ai-demo-impact");

  const flowElement =
    document.getElementById("less-ai-flow");


  function replayFlowAnimation() {
    flowElement.classList.remove("replay");

    void flowElement.offsetWidth;

    flowElement.classList.add("replay");
  }


  function renderProject(project, projectIndex) {

    titleElement.textContent =
      project.title;

    descriptionElement.textContent =
      project.description;

    impactElement.textContent =
      project.impact;

    project.steps.forEach(function (step, index) {
      const stepNumber = index + 1;

      document.getElementById(
        "less-ai-step-label-" + stepNumber
      ).textContent = step[0];

      document.getElementById(
        "less-ai-step-value-" + stepNumber
      ).textContent = step[1];
    });

    document
      .querySelectorAll(".less-ai-project-button")
      .forEach(function (button, index) {
        button.classList.toggle(
          "active",
          index === projectIndex
        );
      });

    replayFlowAnimation();
  }


  function renderConstraint(constraintKey) {

    const constraint =
      constraints[constraintKey];

    workspace.className =
      "less-ai-workspace " + constraint.theme;

    categoryElement.textContent =
      constraint.label;

    projectList.innerHTML = "";

    constraint.projects.forEach(function (project, index) {

      const button =
        document.createElement("button");

      button.type = "button";

      button.className =
        "less-ai-project-button" +
        (index === 0 ? " active" : "");

      button.innerHTML =
        '<i class="' +
        project.icon +
        '"></i><span>' +
        project.title +
        "</span>";

      button.addEventListener("click", function () {
        renderProject(project, index);
      });

      projectList.appendChild(button);
    });

    renderProject(
      constraint.projects[0],
      0
    );
  }


  tabs.forEach(function (tab) {

    tab.addEventListener("click", function () {

      const constraintKey =
        tab.dataset.constraint;

      tabs.forEach(function (item) {

        const isActive =
          item === tab;

        item.classList.toggle(
          "active",
          isActive
        );

        item.setAttribute(
          "aria-selected",
          isActive ? "true" : "false"
        );
      });

      renderConstraint(constraintKey);
    });
  });


  renderConstraint("data");

});
</script>
