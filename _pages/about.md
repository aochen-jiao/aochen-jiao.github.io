---
permalink: /
title: "Aochen Jiao"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
About me
======
I am Aochen Jiao, currently a research assistant at [City University of Hong Kong](https://www.cityu.edu.hk/), where I am supervised by Prof. [Weitao Xu](https://weitaoxu.com) and Prof. [Shengdong Zhao](https://shengdongzhao.com). Prior to that, I obtained my Master's degree from [UCLA](https://www.ucla.edu/) and Bachelor's degree from [Tongji University](https://en.tongji.edu.cn/p/#/). 

My research interests lie in the intersection of human-computer interaction, ubiquitous computing and AR/VR, with a particular focus on enhancing human natural interaction capabilities through innovative wearable technologies. Outside the lab, I enjoy Chinese calligraphy, traveling and watching soccer matches.

I am actively looking for Ph.D. position starting in Fall 2025. If you have any relative information please feel free to contact me!

Education
------
* M.S. in Electrical and Computer Engineering, UCLA, 2023.
* B.Eng. in Automation, Tongji University, 2021.

News
------
* <span class="inline-code-news">[Jul. 2024]</span> Join the [<i>HCI Research Summer Camp</i>](https://synteraction.org/news/conclusion-2024-chiang-mai-research-camp-.html) in Chiang Mai. Thrilled to meet many new interesting friends!
* <span class="inline-code-news">[Jun. 2024]</span> My first paper [<i>Medusa3D</i>](../files/Medusa3D.pdf) is accepted to [<i>MobileHCI'24</i>](https://mobilehci.acm.org/2024/). See you in Melbourne!

<!--
<style>
  ul {
      margin-top: 0;
      padding-top: 0;
      margin-bottom: 0;
      padding-bottom: 0;
    }
  .scrolling-div {
    margin-bottom: 0;
  }
</style>
<div class="scrolling-div" style="padding: 0; height: 30px; overflow-y: scroll; width: 100%; scrollbar-width: none; -ms-overflow-style: none; margin-top: 0;">
  <ul>
    <li><b>[Jun. 2024]</b> My first paper <i>Medusa3D</i> is accepted by <i>[MobileHCI'24](https://mobilehci.acm.org/2024/)</i>.</li>
  </ul>
</div>
-->

Publication
------
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>

<body>
  <div class="container">
    <img src="../files/Medusa3D_teaser.PNG" alt="teaser" class="image">
    <div class="content">
      <p class="info">
        Medusa3D: The Watchful Eye Freezing Illegitimate Users in Virtual Reality Interactions<br>
        <strong>Aochen Jiao</strong>*, Di Duan*, and Weitao Xu <span class="nowrap">(* <i>Equal contribution</i>)</span><br>
        <i>ACM MobileHCI 2024</i> <span class="nowrap"><a href="../files/Medusa3D.pdf" class="button">PDF</a> <a href="https://doi.org/10.1145/3676515" class="button">DOI</a> <a class="button" onclick="showBibtex('bibtex-container-medusa3d')">Cite</a></span>
      </p>
    </div>
  </div>

  <div id="bibtex-container-medusa3d" style="display:none; margin-top: 10px;">
    <pre id="bibtex-entry-medusa3d" class="inline-code">
@article{jiao2024medusa3d,
  title={Medusa3D: The Watchful Eye Freezing Illegitimate Users in Virtual Reality Interactions},
  author={Jiao, Aochen and Duan, Di and Xu, Weitao},
  journal={Proceedings of the ACM on Human-Computer Interaction},
  volume={8},
  number={MHCI},
  pages={1--21},
  year={2024},
  doi={https://doi.org/10.1145/3676515},
  publisher={ACM New York, NY, USA}
}</pre>
    <a class="button" onclick="copyBibtex('bibtex-entry-medusa3d')">Copy</a>
  </div>

  <script>
    function showBibtex(containerId) {
      var bibtexContainer = document.getElementById(containerId);
      if (bibtexContainer.style.display === "none") {
        bibtexContainer.style.display = "block";
      } else {
        bibtexContainer.style.display = "none";
      }
    }

    function copyBibtex(entryId) {
      var bibtexEntry = document.getElementById(entryId).innerText;
      navigator.clipboard.writeText(bibtexEntry).then(function() {
        alert('BibTeX entry copied to clipboard!');
      }, function(err) {
        console.error('Could not copy text: ', err);
      });
    }
  </script>
</body>

<style>
    .inline-code-news {
        background: none;
        font-size: 16px; 
        font-family: monospace;
      }
  
    .inline-code {
      background: #f0f0f0;
      font-size: 12px; 
      font-family: monospace;
      padding: 10px;
      border-radius: 10px;
    }

    .container {
      display: flex;
      align-items: center;
      flex-wrap: wrap;
    }

    .image {
      width: 235px;
      height: 80px;
      margin-right: 2%;
    }

    .content {
      flex: 1;
    }

    .info {
      font-size: 15px;
      margin: 0;
    }

    .nowrap {
      white-space: nowrap; 
      display: inline-block;
    }

    .button {
      display: inline-block;
      margin-left: 10px;
      font-size: 13px;
      color: white;
      background-color: #007BFF;
      text-decoration: none;
      border-radius: 4px;
      width: 35px;
      height: 19px;
      text-align: center;
      line-height: 19px;
      cursor: pointer;
    }

    .button:hover {
      background-color: #0056b3;
    }

    .button:link, .button:visited, .button:hover, .button:active, .button, a.button {
      text-decoration: none; 
    }

    @media (max-width: 600px) {
      .container {
        display: block;
        text-align: left;
      }
      .image {
        display: block;
        margin: 0 auto 10px auto;
      }
      .content {
        width: 100%;
        text-align: left;
      }
      .info {
        text-align: left;
        margin: 0;
      }
      .nowrap {
        white-space: nowrap;
        display: inline-block;
      }
    }
  </style>
</html>
