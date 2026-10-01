---
layout: page
title: Teaching
permalink: /teaching/
description: Teaching assistant experience
nav: true
nav_order: 5
---

<style>
  .teaching-school {
    margin-top: 32px;
    margin-bottom: 20px;
  }

  .teaching-logo-link {
    display: inline-block;
    max-width: 100%;
    padding: 12px 16px;
    background: #fff;
    border-radius: 6px;
    margin-bottom: 12px;
  }

  .teaching-logo {
    display: block;
    max-width: 100%;
    height: auto;
  }

  .teaching-school h2 {
    font-size: 1.4rem;
    font-weight: 600;
    margin: 0;
  }

  .teaching-grid {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 20px;
    margin-bottom: 36px;
  }

  .teaching-card {
    padding: 24px;
    border: 1px solid var(--global-divider-color, #ddd);
    border-top: 3px solid var(--global-theme-color, #a41e35);
    border-radius: 10px;
    background: var(--global-card-bg-color, var(--global-bg-color));
  }

  .teaching-code {
    display: inline-block;
    margin-bottom: 12px;
    color: var(--global-theme-color, #a41e35);
    font-size: 0.9rem;
    font-weight: 700;
    letter-spacing: 0.04em;
  }

  .teaching-card h3 {
    margin: 0 0 12px;
    font-size: 1.2rem;
    font-weight: 600;
    line-height: 1.4;
  }

  .teaching-role {
    margin-bottom: 14px;
    color: var(--global-text-color-light, #666);
    font-size: 0.9rem;
  }

  .teaching-card p {
    margin: 0;
    line-height: 1.7;
  }

  @media (max-width: 700px) {
    .teaching-grid {
      grid-template-columns: 1fr;
    }

    .teaching-card {
      padding: 20px;
    }
  }
</style>

<div class="teaching-school">
  <a class="teaching-logo-link"
     href="https://www.temple.edu/"
     target="_blank"
     rel="noopener noreferrer">
    <img class="teaching-logo"
         src="{{ '/assets/img/temple-logo.svg' | relative_url }}"
         alt="Visit Temple University website"
         style="width: 220px;">
  </a>
  <h2>Temple University</h2>
</div>

<div class="teaching-grid">

  <article class="teaching-card">
    <span class="teaching-code">ECE 2342</span>
    <h3>Circuits and Electronics I Laboratory</h3>
    <div class="teaching-role">Teaching Assistant / Lab Instructor</div>
    <p>DC and AC circuits, circuit analysis, operational amplifiers, and hands-on laboratory experiments.</p>
  </article>

  <article class="teaching-card">
    <span class="teaching-code">ECE 2613</span>
    <h3>Digital Circuit Design Laboratory</h3>
    <div class="teaching-role">Teaching Assistant / Lab Instructor</div>
    <p>Digital logic design, Verilog simulation, and FPGA-based laboratory projects.</p>
  </article>

  <article class="teaching-card">
    <span class="teaching-code">ECE 3623</span>
    <h3>Embedded System Design Laboratory</h3>
    <div class="teaching-role">Teaching Assistant / Lab Instructor</div>
    <p>Embedded system design using Verilog and programmable hardware.</p>
  </article>

</div>

<div class="teaching-school">
  <a class="teaching-logo-link"
     href="https://case.edu/"
     target="_blank"
     rel="noopener noreferrer">
    <img class="teaching-logo"
         src="{{ '/assets/img/cwru-logo.svg' | relative_url }}"
         alt="Visit Case Western Reserve University website"
         style="width: 280px;">
  </a>
  <h2>Case Western Reserve University</h2>
</div>

<div class="teaching-grid">

  <article class="teaching-card">
    <span class="teaching-code">FNCE 471</span>
    <h3>Applications in Financial Big Data</h3>
    <div class="teaching-role">Teaching Assistant</div>
    <p>Financial data analysis, statistical methods, and machine learning applications.</p>
  </article>

</div>
