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

I am actively looking for Ph.D. position starting in Spring/Fall 2025. If you have any relative information please feel free to contact me!

Education
------
* M.S. in Electrical and Computer Engineering, UCLA, 2023.
* B.Eng. in Automation, Tongji University, 2021.

News
------
* <span class="inline-code">[Jul. 2024]</span> Join the [<i>HCI Research Summer Camp</i>](https://synteraction.org/news/conclusion-2024-chiang-mai-research-camp-.html) in Chiang Mai. Thrilled to meet many new interesting friends!
* <span class="inline-code">[Jun. 2024]</span> My first paper [<i>Medusa3D</i>](../files/Medusa3D.pdf) is accepted to [<i>MobileHCI'24</i>](https://mobilehci.acm.org/2024/). See you in Melbourne!

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
    .inline-code {
      background: none;
      font-size: 16px; 
      font-family: monospace;
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

<!--This is the front page of a website that is powered by the [Academic Pages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the respository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this repository](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads! An older version of this template powers my own personal website at [stuartgeiger.com](http://stuartgeiger.com), which uses [this Github repository](https://github.com/staeiou/staeiou.github.io).-->

<!--A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).-->

<!--Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section-->


<!--For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).-->

<!--**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.-->

<!--How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.-->

