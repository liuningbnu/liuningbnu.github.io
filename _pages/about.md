---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  .section {
    margin-bottom: 2.2rem;
  }
  
  /* 与CV页面一致的蓝色标题分割线 */
  .section-title {
    margin: 0 0 1.2rem 0;
    font-size: 1.6rem;
    color: #2c3e50;
    padding-bottom: 0.5rem;
    border-bottom: 2px solid #3498db;
  }
  
  .about-content {
    line-height: 1.65;
    font-size: 1.05rem;
    color: #34495e;
  }
  
  .research-image {
    text-align: center;
    margin: 1.6rem auto;
    max-width: 70%;
  }
  
  .research-image img {
    max-width: 100%;
    height: auto;
    border-radius: 4px;
    display: block;
  }
  
  /* 保留时间线设计 */
  .news-container {
    position: relative;
    padding-left: 20px;
    margin-top: 1.5rem;
  }
  
  .news-container::before {
    content: '';
    position: absolute;
    left: 6px;
    top: 0;
    bottom: 0;
    width: 2px;
    background: #3498db;
  }
  
  .news-item {
    position: relative;
    padding: 0.8rem 0 0.8rem 30px;
    margin-bottom: 0.5rem;
  }
  
  .news-item::before {
    content: "";
    position: absolute;
    left: -1px;
    top: 20px;
    width: 14px;
    height: 14px;
    border-radius: 50%;
    background: #3498db;
    border: 2px solid white;
  }
  
  .news-date {
    font-weight: 600;
    color: #2c3e50;
    display: block;
    margin-bottom: 0.25rem;
    font-size: 0.95rem;
  }
  
  .news-content {
    font-size: 1.02rem;
    color: #3d5266;
    line-height: 1.55;
  }
  
  .journal-name {
    font-style: italic;
  }
  
  .visitor-counter {
    text-align: right;
    margin: 1.8rem 0;
    font-size: 0.92rem;
    color: #5a6c7d;
  }
  
  .research-list {
    padding-left: 1.6rem;
    margin: 1rem 0;
  }
  
  .research-list li {
    margin-bottom: 0.6rem;
    font-size: 1.03rem;
  }
</style>

<div class="section">
  <h2 class="section-title">个人简介</h2>
  
  <div class="about-content">
    <p>你好！我是刘宁，欢迎来到我的主页！我出生于1995年，自幼热爱自然和物理，曾在小学时就自行制作过天文望远镜。在北京师范大学物理学系获理论物理博士学位。目前在高校从事物理教学和研究工作，主讲课程有量子力学，广义相对论和大学物理等。我的研究聚焦于利用玻色-爱因斯坦凝聚体(BEC)这一高度可控的量子系统，来模拟和探究更广泛的物理现象。通过精确调控BEC中的相互作用、拓扑结构和非平衡动力学，我们能够：</p>
    
    <ul class="research-list">
      <li>模拟凝聚态系统中的准粒子行为（如极化子、声子）</li>
      <li>模拟引力系统中的集体行为</li>
      <li>研究量子多体系统的非平衡相变</li>
      <li>验证统计物理基本理论在量子领域的表现</li>
    </ul>
    
    <p>这种"量子模拟"方法使我们能够在纯净的实验环境中，获得对复杂物理系统本质的新洞察。</p>
    
    <div class="research-image">
      <img src="/images/BEC.png" alt="研究关键词云图">
    </div>
  </div>
</div>

<div class="section">
  <h2 class="section-title">近期发表</h2>
  
  <div class="news-container">
    <div class="news-item">
      <span class="news-date">2025年3月10日</span>
      <span class="news-content">
        论文 "Phase behaviors and dynamics of active particle systems in double-well potential" 被<span class="journal-name">Physica A: Statistical Mechanics and its Applications</span>接收（通讯作者）
      </span>
    </div>
    
    <div class="news-item">
      <span class="news-date">2024年10月9日</span>
      <span class="news-content">
        论文 "力学定律的发展：积分和微分定律的视角" 被<span class="journal-name">《大学物理》</span>杂志接收（独立作者）
      </span>
    </div>
    
    <div class="news-item">
      <span class="news-date">2024年8月29日</span>
      <span class="news-content">
        论文 "Weak and strong coupling polarons in binary Bose–Einstein condensates" 被<span class="journal-name">Physica Scripta</span>接收（独立作者）
      </span>
    </div>
    
    <div class="news-item">
      <span class="news-date">2023年9月3日</span>
      <span class="news-content">
        论文 "Polarons in binary Bose–Einstein condensates" 被<span class="journal-name">Journal of Statistical Mechanics: Theory and Experiment</span>接收（第一作者）
      </span>
    </div>
  </div>
</div>

<div class="visitor-counter">
  <span id="busuanzi_container_site_uv">本站访客数：<span id="busuanzi_value_site_uv"></span></span>
</div>

<script async src="//busuanzi.ibruce.info/busuanzi/2.3/busuanzi.pure.mini.js"></script>
