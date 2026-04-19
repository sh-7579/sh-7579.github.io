---
layout: about
title: ""
permalink: /

selected_papers: false
social: false

announcements:
  enabled: false
  scrollable: true
  limit: 5

latest_posts:
  enabled: false
  scrollable: true
  limit: 3
---

<style>
  body {
    background-color: #f8f9fa !important;
    color: #2d2d2d !important;
  }

  .profile-card {
    background: #ffffff;
    border-radius: 20px;
    padding: 48px 40px;
    box-shadow: 0 4px 24px rgba(0,0,0,0.06);
    margin-bottom: 32px;
    display: flex;
    align-items: center;
    gap: 48px;
  }

  .profile-card img {
    width: 140px;
    height: 140px;
    border-radius: 50%;
    object-fit: cover;
    flex-shrink: 0;
    box-shadow: 0 4px 16px rgba(0,0,0,0.10);
  }

  .profile-info h1 {
    font-size: 2.2rem;
    font-weight: 800;
    color: #1a237e;
    margin: 0 0 6px 0;
    letter-spacing: -0.02em;
  }

  .profile-info .affiliation {
    font-size: 0.95rem;
    color: #5c6bc0;
    font-weight: 600;
    margin-bottom: 20px;
  }

  .profile-info .social-links {
    display: flex;
    gap: 20px;
  }

  .profile-info .social-links a {
    color: #555;
    transition: color 0.2s;
  }

  .profile-info .social-links a:hover {
    color: #1a237e;
  }

  .section-card {
    background: #ffffff;
    border-radius: 16px;
    padding: 28px 32px;
    box-shadow: 0 2px 12px rgba(0,0,0,0.04);
    margin-bottom: 24px;
  }

  .section-card h3 {
    font-size: 1.05rem;
    font-weight: 700;
    color: #1a237e;
    margin: 0 0 20px 0;
    padding-bottom: 10px;
    border-bottom: 2px solid #e8eaf6;
    text-transform: uppercase;
    letter-spacing: 0.05em;
  }

  .timeline {
    list-style: none;
    padding: 0;
    margin: 0;
  }

  .timeline li {
    display: flex;
    gap: 20px;
    padding: 10px 0;
    border-bottom: 1px solid #f0f0f0;
    line-height: 1.6;
    color: #444;
  }

  .timeline li:last-child {
    border-bottom: none;
    padding-bottom: 0;
  }

  .timeline .year {
    font-weight: 700;
    color: #5c6bc0;
    white-space: nowrap;
    min-width: 110px;
    font-size: 0.9rem;
    padding-top: 2px;
  }

  .interests-list {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
  }

  .interests-list li {
    background: #e8eaf6;
    color: #1a237e;
    font-weight: 600;
    font-size: 0.88rem;
    padding: 6px 16px;
    border-radius: 20px;
  }

  .pub-entry {
    padding: 12px 0;
    line-height: 1.8;
    color: #444;
    border-bottom: 1px solid #f0f0f0;
  }

  .pub-entry:last-of-type {
    border-bottom: none;
  }

  .pub-img-wrap {
    margin-top: 20px;
    background: #fafafa;
    border: 1px solid #efefef;
    border-radius: 10px;
    padding: 16px;
    text-align: center;
  }

  .pub-img-wrap img {
    width: 100%;
    max-width: 760px;
    border-radius: 6px;
  }

  .pub-img-wrap p {
    font-size: 0.82em;
    color: #888;
    font-style: italic;
    margin: 12px 0 0 0;
  }

  @media (max-width: 600px) {
    .profile-card {
      flex-direction: column;
      text-align: center;
      padding: 36px 24px;
      gap: 24px;
    }
    .profile-info .social-links {
      justify-content: center;
    }
    .timeline li {
      flex-direction: column;
      gap: 4px;
    }
  }
</style>

<div class="profile-card">
  <img src="{{ '/assets/img/my_icon.jpg' | relative_url }}" alt="Hiroki Sawada">
  <div class="profile-info">
    <h1>Hiroki Sawada</h1>
    <p class="affiliation">Tohoku NLP Group</p>
    <div class="social-links">
      <a href="mailto:sawada.hiroki.s4@dc.tohoku.ac.jp"><i class="fas fa-envelope fa-lg"></i></a>
      <a href="https://github.com/sh-7579"><i class="fab fa-github fa-lg"></i></a>
      <a href="https://twitter.com/SH_nlp"><i class="fab fa-twitter fa-lg"></i></a>
    </div>
  </div>
</div>

<div class="section-card">
  <h3>Biography</h3>
  <ul class="timeline">
    <li>
      <span class="year">2026 – 現在</span>
      <span>東北大学大学院情報科学研究科システム情報科学専攻 修士課程</span>
    </li>
    <li>
      <span class="year">2022 – 2026</span>
      <span>東北大学工学部 卒業</span>
    </li>
    <li>
      <span class="year">2003 – 2022</span>
      <span>富山県出身</span>
    </li>
  </ul>
</div>

<div class="section-card">
  <h3>Research Interests</h3>
  <ul class="interests-list">
    <li>Natural Language Processing</li>
    <li>Interpretability of Large Language Models</li>
    <li>Brain-Inspired NLP</li>
  </ul>
</div>

<div class="section-card">
  <h3>Awards & Honors</h3>
  <ul class="timeline">
    <li>
      <span class="year">2026</span>
      <span><a href="https://www.aie.tohoku.ac.jp/" target="_blank" style="color: #444; text-decoration: underline;">東北大学人工知能エレクトロニクス卓越大学院プログラム</a> 採択</span>
    </li>
    <li>
      <span class="year">2025</span>
      <span><a href="https://www.ieice.org/tohoku/award/images/2025awards.pdf" target="_blank" style="color: #444; text-decoration: underline;">電子情報通信学会東北支部 優秀学生表彰</a></span>
    </li>
  </ul>
</div>

<div class="section-card">
  <h3>Domestic Conferences</h3>
  <div class="pub-entry">
    <span style="font-weight: 700;">澤田紘希</span>, 佐々木睦史, 坂口慶祐, Benjamin Heinzerling,
    <span style="font-weight: 700;">"言語モデルにおける共参照解決を担う注意ヘッドの分析"</span>,<br>
    言語処理学会第32回年次大会 (NLP2026), March 2026.
  </div>
  <div class="pub-img-wrap">
    <img src="{{ '/assets/img/attention_viz.png' | relative_url }}" alt="Attention Visualization">
    <p>図1：共参照解決を担う注意ヘッド（Attention Head）の可視化例</p>
  </div>
</div>
