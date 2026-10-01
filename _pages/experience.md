---
layout: page
title: Experience
permalink: /experience/
description: Research and professional experience
nav: true
nav_order: 4
---

<style>
  .experience-section {
    margin-top: 2rem;
    margin-bottom: 1.5rem;
    font-size: 1.5rem;
    font-weight: 600;
  }

  .experience-timeline {
    border-left: 2px solid var(--global-divider-color, #ddd);
    margin-left: 7px;
    padding-left: 28px;
  }

  .experience-entry {
    position: relative;
    margin-bottom: 24px;
    padding: 24px;
    border: 1px solid var(--global-divider-color, #ddd);
    border-radius: 12px;
    background: var(--global-card-bg-color, var(--global-bg-color));
  }

  .experience-entry::before {
    content: "";
    position: absolute;
    left: -36px;
    top: 30px;
    width: 12px;
    height: 12px;
    border-radius: 50%;
    background: var(--global-theme-color, #a41e35);
    border: 3px solid var(--global-bg-color, #fff);
    box-sizing: content-box;
  }

  .experience-logo-link {
    display: inline-block;
    max-width: 100%;
    margin-bottom: 18px;
    padding: 12px 16px;
    background: #fff;
    border-radius: 6px;
  }

  .experience-logo {
    display: block;
    height: auto;
    max-width: 100%;
  }

  .experience-heading {
    display: flex;
    justify-content: space-between;
    align-items: baseline;
    flex-wrap: wrap;
    gap: 8px 16px;
    margin-bottom: 8px;
  }

  .experience-role {
    margin: 0;
    font-size: 1.2rem;
    font-weight: 600;
  }

  .experience-date {
    color: var(--global-text-color-light, #666);
    font-size: 0.9rem;
  }

  .experience-institution {
    margin-bottom: 4px;
    font-weight: 500;
  }

  .experience-school {
    margin-bottom: 6px;
    font-size: 0.95rem;
  }

  .experience-school a {
    color: var(--global-theme-color, #a41e35);
  }

  .experience-location {
    margin-bottom: 16px;
    color: var(--global-text-color-light, #666);
    font-size: 0.9rem;
  }

  .experience-entry ul {
    margin-bottom: 0;
    padding-left: 20px;
    line-height: 1.7;
  }

  .experience-entry li + li {
    margin-top: 6px;
  }

  @media (max-width: 576px) {
    .experience-timeline {
      padding-left: 20px;
    }

    .experience-entry {
      padding: 18px;
    }

    .experience-entry::before {
      left: -28px;
    }
  }
</style>

<h2 class="experience-section">Research Experience</h2>

<div class="experience-timeline">

  <article class="experience-entry">
    <a class="experience-logo-link"
       href="https://engineering.temple.edu/"
       target="_blank"
       rel="noopener noreferrer">
      <img class="experience-logo"
           src="{{ '/assets/img/temple-logo.svg' | relative_url }}"
           alt="Visit Temple University College of Engineering"
           style="width: 200px;">
    </a>
    <div class="experience-heading">
      <h3 class="experience-role">Research Assistant</h3>
      <span class="experience-date">2025–Present</span>
    </div>
    <div class="experience-institution">Temple University</div>
    <div class="experience-school">
      <a href="https://engineering.temple.edu/"
         target="_blank" rel="noopener noreferrer">
        College of Engineering
      </a>
    </div>
    <div class="experience-location">Philadelphia, PA</div>
    <ul>
      <li>Conduct research in biomedical signal processing and machine learning for healthcare applications.</li>
      <li>Develop deep learning methods for tracheal sound denoising and the preservation of respiratory signal characteristics.</li>
    </ul>
  </article>

  <article class="experience-entry">
    <a class="experience-logo-link"
       href="https://case.edu/engineering/"
       target="_blank"
       rel="noopener noreferrer">
      <img class="experience-logo"
           src="{{ '/assets/img/cwru-logo.svg' | relative_url }}"
           alt="Visit Case School of Engineering"
           style="width: 280px;">
    </a>
    <div class="experience-heading">
      <h3 class="experience-role">Research Assistant</h3>
      <span class="experience-date">Sep 2023–Dec 2024</span>
    </div>
    <div class="experience-institution">Case Western Reserve University</div>
    <div class="experience-school">
      <a href="https://case.edu/engineering/"
         target="_blank" rel="noopener noreferrer">
        Case School of Engineering
      </a>
    </div>
    <div class="experience-location">Cleveland, OH</div>
    <ul>
      <li>Conducted research on graph neural networks, including graph convolutional networks (GCNs).</li>
      <li>Investigated model interpretability to better understand graph-based predictions.</li>
    </ul>
  </article>

  <article class="experience-entry">
    <a class="experience-logo-link"
       href="https://case.edu/weatherhead/"
       target="_blank"
       rel="noopener noreferrer">
      <img class="experience-logo"
           src="{{ '/assets/img/cwru-logo.svg' | relative_url }}"
           alt="Visit Weatherhead School of Management"
           style="width: 280px;">
    </a>
    <div class="experience-heading">
      <h3 class="experience-role">Research Assistant</h3>
      <span class="experience-date">Aug 2022–Dec 2022</span>
    </div>
    <div class="experience-institution">Case Western Reserve University</div>
    <div class="experience-school">
      <a href="https://case.edu/weatherhead/"
         target="_blank" rel="noopener noreferrer">
        Weatherhead School of Management
      </a>
    </div>
    <div class="experience-location">Cleveland, OH</div>
    <ul>
      <li>Collected and organized data from more than 200 financial research papers.</li>
      <li>Applied BERT-based models to text classification and information extraction.</li>
    </ul>
  </article>

</div>

<h2 class="experience-section">Industry Experience</h2>

<div class="experience-timeline">

  <article class="experience-entry">
    <a class="experience-logo-link"
       href="http://www.greatwallhn.com.cn/en/"
       target="_blank"
       rel="noopener noreferrer">
      <img class="experience-logo"
           src="{{ '/assets/img/greatwall-logo.png' | relative_url }}"
           alt="Visit Hunan Great Wall Computer System website"
           style="width: 220px;">
    </a>
    <div class="experience-heading">
      <h3 class="experience-role">Test Engineer Intern</h3>
      <span class="experience-date">Jul 2020–Sep 2020</span>
    </div>
    <div class="experience-institution">Hunan Great Wall Computer System Co., Ltd.</div>
    <div class="experience-location">Changsha, China</div>
    <ul>
      <li>Developed automated tests for ATM software using Python and Pytest.</li>
      <li>Designed and executed test cases covering transactions, system stability, and fault tolerance.</li>
    </ul>
  </article>

</div>
