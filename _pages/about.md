---
permalink: /
title: "Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


I'm a third year undergraduate student from [School of EECS](https://eecs.pku.edu.cn/), [Peking University](https://www.pku.edu.cn/). My research interest includes computer vision, computer graphics, machine learning, and computational photography.

I am very fortunate to be advised by [Prof. XXX](https://www.XXX.com/) of XXX Lab from [School of Computer Science](https://cs.pku.edu.cn/), Peking University. I was advised by [Prof. XX](https://XXX.pku.edu.cn/) from [School of Computer Science](https://cs.pku.edu.cn/), Peking University.

You can find my CV here: [XX's Curriculum Vitae](../assets/Curriculum_Vitae.pdf).

[Email](mailto:XX@stu.pku.edu.cn) / [Github](https://github.com/QiuDi233) / [Wechat](../images/wechat.jpg) / [CSDN](https://blog.csdn.net/qd1813100174?spm=1000.2115.3001.5343)


✳️Selected Talks
======

**Data Storytelling 用数据讲故事:**

数据新闻十年反思与回顾 // <font color=DarkGray>2023.11 复旦大学新闻晚会</font> ![image](https://github.com/W2rld/w2rld.github.io/blob/master/images/view.png)

可视化叙事前沿进展 // <font color=DarkGray>2023.11 华东政法大学传播学院 ｜ 2023.10 南京大学新闻与传播学院 | 2023.9 上海大学美术学院</font> [🔍](https://baidu.com)

用数据讲故事 // <font color=DarkGray>2023.6 南京大学艺术学院 ｜ 2021.12 字节跳动</font> 

理解数据故事的设计传达：一种用户中心的视角 // <font color=DarkGray>2021.7 GAMES-Webinar</font> 

This is the front page of a website that is powered by the [Academic Pages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the respository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this repository](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads! An older version of this template powers my own personal website at [stuartgeiger.com](http://stuartgeiger.com), which uses [this Github repository](https://github.com/staeiou/staeiou.github.io).

A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 
