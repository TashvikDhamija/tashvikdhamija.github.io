---
layout: page
permalink: /experience/
title: experience
nav: true
nav_order: 3
toc:
  sidebar: left
---

<style>
.cv-section {
  margin-bottom: 2rem;
  border: 1px solid var(--global-divider-color);
  border-radius: 8px;
  padding: 1.5rem 2rem 0.75rem;
}
.cv-section > h2 {
  font-size: 1.75rem;
  border-bottom: 1px solid var(--global-divider-color);
  padding-bottom: 0.4rem;
  margin-bottom: 1.5rem;
  margin-top: 0;
}
.cv-entry { margin-bottom: 1.75rem; }
.cv-entry-head {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  gap: 1.5rem;
}
.cv-entry-title {
  font-size: 1.05rem;
  font-weight: 700;
  color: var(--global-theme-color);
  margin: 0;
}
.cv-entry-sub {
  margin: 0.15rem 0 0;
  color: var(--global-text-color);
  font-size: 0.95rem;
}
.cv-entry-area {
  margin: 0.1rem 0 0;
  font-style: italic;
  font-size: 0.9rem;
  color: var(--global-text-color-light, #aaa);
}
.cv-entry-meta {
  text-align: right;
  flex-shrink: 0;
  font-size: 0.88rem;
  color: var(--global-text-color-light, #aaa);
  line-height: 1.5;
}
.cv-entry-meta .dates {
  font-weight: 600;
  color: var(--global-text-color);
  display: block;
}
.cv-highlights {
  margin: 0.6rem 0 0 1.1rem;
  padding: 0;
}
.cv-highlights li {
  margin-bottom: 0.3rem;
  font-size: 0.93rem;
  line-height: 1.55;
}
.cw-label {
  font-weight: 600;
  font-size: 0.93rem;
  margin: 0.75rem 0 0.3rem;
}
.cw-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  column-gap: 2.5rem;
  row-gap: 0.05rem;
  font-size: 0.88rem;
  color: var(--global-text-color);
}
.skills-list {
  display: flex;
  flex-direction: column;
  gap: 0.45rem;
}
.skill-row { font-size: 0.93rem; line-height: 1.5; }
.skill-cat {
  font-weight: 700;
  color: var(--global-theme-color);
}
</style>

## Education

<div class="cv-section">

<div class="cv-entry">
  <div class="cv-entry-head">
    <div>
      <p class="cv-entry-title">Master of Science</p>
      <p class="cv-entry-sub">Carnegie Mellon University, School of Computer Science</p>
      <p class="cv-entry-area">Artificial Intelligence and Innovation &nbsp;·&nbsp; GPA: 4.08 / 4.0</p>
    </div>
    <div class="cv-entry-meta">
      <span class="dates">Sep 2024 – Present</span>
      Pittsburgh, PA
    </div>
  </div>
  <div class="cw-label">Coursework</div>
  <div class="cw-grid">
    <div>Introduction to Machine Learning (PhD)</div>
    <div>Advanced Deep Learning (PhD)</div>
    <div>Computer Vision</div>
    <div>Advanced Natural Language Processing (PhD)</div>
    <div>AI Engineering</div>
    <div>Learning for 3D Vision</div>
    <div>Deep Learning Systems</div>
    <div>Generative AI</div>
    <div>Computer Systems</div>
  </div>
</div>

<div class="cv-entry">
  <div class="cv-entry-head">
    <div>
      <p class="cv-entry-title">Bachelor of Technology</p>
      <p class="cv-entry-sub">Delhi Technological University</p>
      <p class="cv-entry-area">Electronics and Communications Engineering &nbsp;·&nbsp; GPA: 9.14 / 10.0</p>
    </div>
    <div class="cv-entry-meta">
      <span class="dates">Aug 2019 – May 2023</span>
      Delhi, India
    </div>
  </div>
  <div class="cw-label">Coursework</div>
  <div class="cw-grid">
    <div>Deep Learning</div>
    <div>Computer Vision</div>
    <div>Data Structures</div>
    <div>Algorithms</div>
    <div>Object-Oriented Programming</div>
    <div>Database Management Systems</div>
  </div>
</div>

</div>

## Experience

<div class="cv-section">

<div class="cv-entry">
  <div class="cv-entry-head">
    <div>
      <p class="cv-entry-title">ML Intern, Neuron Scalable Training</p>
      <p class="cv-entry-sub">Amazon Web Services, Annapurna Labs</p>
    </div>
    <div class="cv-entry-meta">
      <span class="dates">May 2026 – Aug 2026</span>
      Cupertino, CA, USA
    </div>
  </div>
  <ul class="cv-highlights">
    <li>Enabled diffusion and flow-matching model training on AWS Trainium by onboarding SOTA models (Stable Diffusion, FLUX, DiT, Wan) onto Neuron, Annapurna's native PyTorch backend.</li>
    <li>Implemented and optimized PyTorch ATen operators for the Neuron backend, extending native operator coverage and efficiency.</li>
    <li>Validated long-horizon training dynamics between Neuron and CUDA across text-to-image, text-to-video, and diffusion language models, ensuring convergence, numerical stability, and quality parity.</li>
  </ul>
</div>

<div class="cv-entry">
  <div class="cv-entry-head">
    <div>
      <p class="cv-entry-title">AI Entrepreneur and Researcher</p>
      <p class="cv-entry-sub">Inria Startup Studio, Universite Cote d'Azur</p>
    </div>
    <div class="cv-entry-meta">
      <span class="dates">Oct 2023 – Sep 2024</span>
      Valbonne, France
    </div>
  </div>
  <ul class="cv-highlights">
    <li>Architected a generative AI pipeline leveraging diffusion transformers and cross-modal alignment to synthesize photorealistic, audio-driven video avatars with high temporal coherence and lip-sync accuracy.</li>
    <li>Led a 5-member ML engineering team in developing an MVP launched on Product Hunt, implementing optimization strategies for real-time avatar generation and conducting iterative evaluations to improve perceptual realism and latency.</li>
    <li>Formulated go-to-market strategy via business plans, pitch decks, and financial models; showcased at VivaTech (Paris) and Bits & Pretzels (Munich) to attract partners and investors.</li>
  </ul>
</div>

<div class="cv-entry">
  <div class="cv-entry-head">
    <div>
      <p class="cv-entry-title">Computer Vision Engineer</p>
      <p class="cv-entry-sub">SwitchOn</p>
    </div>
    <div class="cv-entry-meta">
      <span class="dates">Jun 2023 – Sep 2023</span>
      Bangalore, India
    </div>
  </div>
  <ul class="cv-highlights">
    <li>Engineered one-shot anomaly detection pipelines leveraging feature embedding similarity and memory-bank architectures, achieving over 99% detection accuracy with under 1% false positives in real-time defect identification on manufacturing lines.</li>
    <li>Led design and integration of a transformer-based OCR module into the anomaly detection stack, replacing legacy classical CV approaches; delivered near-perfect text recognition accuracy for reliable automated inspection in production.</li>
    <li>Performed remote rollout and on-device validation of CV models on Linux-based embedded hardware, ensuring robust edge inference.</li>
  </ul>
</div>

<div class="cv-entry">
  <div class="cv-entry-head">
    <div>
      <p class="cv-entry-title">Undergraduate Research Intern</p>
      <p class="cv-entry-sub">Inria Centre at Université Côte d'Azur</p>
    </div>
    <div class="cv-entry-meta">
      <span class="dates">May 2022 – Jun 2023</span>
      Valbonne, France
    </div>
  </div>
  <ul class="cv-highlights">
    <li>Explored audio-to-video facial synthesis and fingerprint enhancement using generative AI; submitted 3 research papers to journals and conferences, later pursuing incubation to translate research into products.</li>
    <li>Adapted the Latent Image Animator model for audio-conditioned video synthesis via feature mapping of audio encodings to motion space; transitioned to diffusion-based models for improved temporal coherence and realism.</li>
    <li>Developed novel self-supervised losses and integrated FFT-based convolutions in FG-GAN to enhance fingerprint image quality for biometric recognition.</li>
  </ul>
</div>

</div>

## Skills

<div class="cv-section">
<div class="skills-list">
  <div class="skill-row"><span class="skill-cat">AI & ML Frameworks:&nbsp;</span>PyTorch, CUDA, JAX, TensorFlow, Keras, HuggingFace (Transformers, Diffusers, PEFT), Weights & Biases</div>
  <div class="skill-row"><span class="skill-cat">Generative AI:&nbsp;</span>Diffusion Models (DDPM, Flow Matching, CFG), Stable Diffusion, FLUX, DiT, Wan2.1, LLMs (fine-tuning, LoRA, RLHF, RAG), GANs</div>
  <div class="skill-row"><span class="skill-cat">Computer Vision:&nbsp;</span>CLIP, ViT, DINO, Object Detection, Semantic Segmentation, Image Enhancement, OpenCV</div>
  <div class="skill-row"><span class="skill-cat">ML Systems:&nbsp;</span>AWS Trainium, Neuron SDK, Distributed Training (DDP, FSDP, ZeRO), Mixed Precision (BF16/FP8), HPCs, Docker</div>
  <div class="skill-row"><span class="skill-cat">Languages & Tools:&nbsp;</span>Python, C/C++, CUDA, Bash, SQL, Git, Linux, Conda, Jupyter</div>
</div>
</div>
