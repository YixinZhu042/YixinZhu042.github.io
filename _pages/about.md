---
permalink: /
title: "Yixin Zhu | Generative AI & Embodied Intelligence"
layout: home
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

{% include base_path %}

<section class="hero-section" id="about-me" aria-labelledby="hero-title">
  <div class="hero-grid">
    <div class="hero-copy">
      <p class="eyebrow">Generative AI · Embodied Intelligence · Physical Simulation</p>
      <h1 id="hero-title">Yixin Zhu <span>祝亦欣</span></h1>
      <p class="hero-subtitle">Master's student at Nanjing University researching controllable visual generation, physically grounded rendering, and embodied AI benchmarks.</p>

      <div class="hero-actions" aria-label="Primary links">
        <a class="btn-primary" href="#publications">Research Highlights</a>
        <a class="btn-secondary" href="mailto:yixinzhu@smail.nju.edu.cn">Contact Me</a>
      </div>

      <div class="quick-facts" aria-label="Profile summary">
        <div>
          <strong>Nanjing University</strong>
          <span>School of Intelligence Science and Technology</span>
        </div>
        <div>
          <strong>Research Focus</strong>
          <span>AIGC, embodied AI, and physically grounded visual worlds</span>
        </div>
      </div>
    </div>

    <aside class="profile-card" aria-label="Contact and profile">
      <div class="profile-image-wrap">
        <img src="{{ base_path }}/images/avatar.jpg" alt="Yixin Zhu profile photo" class="profile-image">
      </div>
      <div class="profile-card-body">
        <h2>Profile Snapshot</h2>
        <ul class="profile-links">
          <li><span>Expected Graduation</span><strong>2027</strong></li>
          <li><span>Research Internship</span><strong>Tencent Hunyuan</strong></li>
          <li><span>Email</span><a href="mailto:yixinzhu@smail.nju.edu.cn">yixinzhu@smail.nju.edu.cn</a></li>
          <li><span>GitHub</span><a href="https://github.com/YixinZhu042">YixinZhu042</a></li>
          <li><span>ORCID</span><a href="https://orcid.org/0009-0000-9876-5404">0009-0000-9876-5404</a></li>
        </ul>
      </div>
    </aside>
  </div>
</section>

<section class="content-section about-block" aria-labelledby="about-title">
  <div class="section-heading">
    <p class="section-kicker">About me</p>
    <h2 id="about-title">Bridging AI and the Physical World</h2>
  </div>
  <div class="prose-card">
    <p>My name is <strong>Yixin Zhu (祝亦欣)</strong>. I am currently a 2nd-year Master's student at the School of Intelligence Science and Technology, Nanjing University, where I am fortunate to be supervised by <a href="https://wangningbei.github.io/">Prof. Beibei Wang</a>. Before that, I obtained my Bachelor's degree from Chang'an University.</p>

    <p>My research interests mainly focus on AIGC and embodied AI. My research goal is to bridge the gap between generative AI and the physical world, focusing on controllable scene editing, physics-based rendering, and high-fidelity 3D asset generation for embodied AI.</p>
  </div>
</section>

<section class="content-section" id="news" aria-labelledby="news-title">
  <div class="section-heading section-heading--row">
    <div>
      <p class="section-kicker">News</p>
      <h2 id="news-title">Latest updates</h2>
    </div>
  </div>

  <div class="timeline-card">
    <article class="timeline-item">
      <time datetime="2026-05"><span>2026</span><strong>05</strong><em>May</em></time>
      <p>I will start an algorithm research internship at Tencent Hunyuan 3D.</p>
    </article>
    <article class="timeline-item">
      <time datetime="2026-05"><span>2026</span><strong>05</strong><em>May</em></time>
      <p>VISER, a visually realistic embodied benchmark, has been released on arXiv.</p>
    </article>
    <article class="timeline-item">
      <time datetime="2026-02"><span>2026</span><strong>02</strong><em>Feb</em></time>
      <p>We have one paper accepted to CVPR 2026!</p>
    </article>
  </div>
</section>

<section class="content-section" id="publications" aria-labelledby="publications-title">
  <div class="section-heading section-heading--row">
    <div>
      <p class="section-kicker">Publications</p>
      <h2 id="publications-title">Selected research highlights</h2>
    </div>
  </div>

  <article class="publication-card publication-card--viser">
    <div class="publication-visual publication-visual--viser-image" aria-hidden="true">
      <img src="{{ base_path }}/images/VISER_teaser.png" alt="VISER teaser thumbnail">
    </div>
    <div class="publication-content">
      <p class="pub-venue">arXiv preprint, 2026</p>
      <h3><a href="https://arxiv.org/abs/2605.06311">Toward Visually Realistic Simulation: A Benchmark for Evaluating Robot Manipulation in Simulation</a></h3>
      <p class="pub-authors"><strong>Yixin Zhu</strong>, Zixiong Wang, Jian Yang, Jin Xie, Jingyi Yu, Jiayuan Gu, Beibei Wang</p>
      <div class="pub-links" aria-label="Publication links">
        <a href="https://arxiv.org/abs/2605.06311">Paper</a>
      </div>
    </div>
  </article>

  <article class="publication-card">
    <div class="publication-visual publication-visual--image" aria-hidden="true">
      <img src="{{ base_path }}/images/pipeline.png" alt="IntrinsicWeather pipeline thumbnail">
    </div>
    <div class="publication-content">
      <p class="pub-venue">IEEE/CVF Conference on Computer Vision and Pattern Recognition (<strong>CVPR</strong>), 2026</p>
      <h3><a href="https://arxiv.org/abs/2508.06982">IntrinsicWeather: Controllable Weather Editing in Intrinsic Space</a></h3>
      <p class="pub-authors"><strong>Yixin Zhu</strong>, Zuo-Liang Zhu, Jian Yang, Miloš Hašan, Jin Xie, Beibei Wang</p>
      <div class="pub-links" aria-label="Publication links">
        <a href="https://arxiv.org/abs/2508.06982">Paper</a>
        <a href="https://yixinzhu042.github.io/IntrinsicWeather/">Project Page</a>
        <a href="https://github.com/YixinZhu042/IntrinsicWeather">Code</a>
      </div>
    </div>
  </article>
</section>
