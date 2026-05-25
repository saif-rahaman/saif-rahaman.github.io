---
permalink: /
title: "About me"
excerpt: "About me"
layout: archive
author_profile: true
classes: wide
sidebar: false
redirect_from: 
  - /about/
  - /about.html

feature_row:
  - title: "Education"
    excerpt: >
      <div style="display: flex; flex-direction: column; gap: 15px;">
        <div style="display: flex; align-items: center;">
          <img src="/images/cmu-logo.png" alt="CMU" style="width: 80px; height: 80px; object-fit: contain; margin-right: 20px;">
          <span><strong>Ph.D. in Chemical Engineering, 2021</strong><br>Carnegie Mellon University</span>
        </div>
        <div style="display: flex; align-items: center;">
          <img src="/images/iitb-logo.png" alt="IIT" style="width: 80px; height: 80px; object-fit: contain; margin-right: 20px;">
          <span><strong>B.Tech in Chemical Engineering, 2016</strong><br>Indian Institute of Technology, Bombay</span>
        </div>
      </div>
  - title: "Research Interests"
    excerpt: "<ul><li>Optimization & Control</li><li>Power Systems</li><li>Numerical Methods</li></ul>"
---  

Currently, I am a staff scientist at the <a href = "https://www.lanl.gov/org/ddste/aldsc/theoretical/applied-mathematics-plasma-physics/index.php" target="_blank" style="text-decoration:none"> Applied Math & Plasma Physics </a> group in Los Alamos National Lab (LANL), USA. Previously, I did my post-doctoral research at the <a href = "https://cnls.lanl.gov/External/" target="_blank" style="text-decoration:none"> Center for Nonlinear Studies (CNLS)</a> here at LANL. I am also a part of the <a href = "https://lanl-ansi.github.io/" target="_blank" style="text-decoration:none"> Advanced Network Science Initiative (ANSI) </a> working with <a href = "https://azlotnik.github.io/" target="_blank" style="text-decoration:none"> Anatoly Zlotnik </a> and <a href = "https://kaarthiksundar.github.io/" target="_blank" style="text-decoration:none"> Kaarthik Sundar</a>. I currently work on modeling and optimization of energy network systems including gas pipeline networks with a focus on blending hydrogen and natural gas in existing pipeline infrastructure. I am also interested in algorithms and applications for <b> mathematical programing with equilibrium constraints (MPECs) </b> which are used to solve optimization problems with variational inequalities.

I obtained my PhD working with Prof. <a href = "http://numero.cheme.cmu.edu/" target="_blank" style="text-decoration:none"> Lorenz Biegler </a> in Chemical Engineering from Carnegie Mellon University, Pittsburgh in 2021. My PhD project was in developing detailed heat exchanger design models and incorporating them in large flowsheet optimization models using trust-region methods. I also worked on modeling multi-component phase change heat exchangers using MPECs in heat integration optimization models among other things.

Prior to that, I completed my Bachelors (with Honors) in Chemical Engineering (minor in Electrical Engineering) from Indian Institute of Technology Bombay in India 2016.

In my free time, I watch sports (Soccer, F1 and NFL) and listen to music (mostly Hard Rock). I also like playing soccer and hiking with friends.

Please feel free to contact me via <a href = "mailto:srkazi@alumni.cmu.edu" target="_blank" style="text-decoration:none">Email</a> or <a href = "https://www.linkedin.com/in/saif-rahaman-7b895379/" target="_blank" style="text-decoration:none">LinkedIn</a>.

{% include feature_row %}

<style>
  /* 1. Fully override the theme's feature_row structure */
  .feature_row {
    display: grid !important;
    grid-template-columns: 2fr 1fr !important; /* Adjust ratios here */
    gap: 40px !important; /* Prevents overlap */
    max-width: 100% !important;
  }

  /* 2. Reset the individual items so they don't fight the grid */
  .feature__item {
    display: block !important;
    width: 100% !important;
    padding: 0 !important;
    margin: 0 !important;
  }

  /* 3. Force content to stay within its own grid column */
  .feature__item-excerpt {
    width: 100% !important;
  }

  /* 4. Fix for the Education text wrapping */
  .feature__item-excerpt span {
    white-space: nowrap !important;
  }
</style>

