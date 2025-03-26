---
permalink: /
title: "Tyler Griggs"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a second year Ph.D. student in Computer Science in the UC Berkeley [Sky Computing Lab](https://sky.cs.berkeley.edu/) advised by [Ion Stoica](http://people.eecs.berkeley.edu/~istoica/) and [Matei Zaharia](https://people.eecs.berkeley.edu/~matei/). Previously, I worked in Network Infrastructure at Google Cloud. Before that, I graduated from Harvard with a BA in Computer Science advised by [James Mickens](https://mickens.seas.harvard.edu/).

Along with several wonderful collaborators, I am a co-lead of [NovaSky](https://novasky-ai.github.io/posts/about-us/). Our work has been featured in [The New York Times](https://www.nytimes.com/2025/01/23/technology/deepseek-china-ai-chips.html), [The Wall Street Journal](https://www.wsj.com/tech/ai/why-distillation-has-become-the-scariest-wordfor-ai-companies-aa146ae3), and [The Information](https://www.theinformation.com/articles/why-its-cheap-and-easy-to-mimic-openais-reasoning-model).

<!-- News
======
*Feb '25:* Arxived [LLMs Can Easily Learn to Reason from Demonstrations Structure](https://arxiv.org/abs/2502.07374)
*Feb '25:* 
*Jan '25:* Released [Sky-T1-32B-Flash](https://novasky-ai.github.io/posts/reduce-overthinking/) to reduce overthinking in reasoning models
*Jan '25:* Launched [NovaSky](https://novasky-ai.github.io/posts/about-us/) -->

Projects
======

<!-- {% include projects.md %} -->

<div style="display: flex; align-items: center; margin-bottom: 1.5em;">
  <img src="{{ base_path }}/images/structure-not-content.png" alt="Structure not Content" style="width: 200px; height: auto; margin-right: 15px;">
  <div>
    <strong>LLMs Can Easily Learn to Reason from Demonstrations</strong>: Structure, not content, is what matters!<br>
    Dacheng Li*, Shiyi Cao*, <strong>Tyler Griggs*</strong>, Shu Liu*, Xiangxi Mo, Eric Tang, Sumanth Hegde, Kourosh Hakhamaneshi, Shishir G Patil, Matei Zaharia, Joseph E Gonzalez, Ion Stoica<br>
    <span style="font-style:italic">arXiv preprint</span> 
    [<a style="text-decoration:none" href="https://arxiv.org/abs/2502.07374" target="_blank">Paper</a>] 
  </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 1.5em;">
  <img src="{{ base_path }}/images/moe-lightning-thumbnail.png" alt="MoE-Lightning" style="width: 200px; height: auto; margin-right: 15px;">
  <div>
    <strong>MoE-Lightning</strong>: High-Throughput MoE Inference on Memory-constrained GPUs<br>
    Shiyi Cao, Shu Liu, <strong>Tyler Griggs</strong>, Peter Schafhalter, Xiaoxuan Liu, Ying Sheng, Joseph E Gonzalez, Matei Zaharia, Ion Stoica<br>
    <span style="font-style:italic">ASPLOS 2025</span> 
    [<a style="text-decoration:none" href="https://arxiv.org/abs/2411.11217" target="_blank">Paper</a>]
  </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 1.5em;">
  <img src="{{ base_path }}/images/sky-serve-thumbnail.png" alt="SkyServe" style="width: 200px; height: auto; margin-right: 15px;">
  <div>
    <strong>SkyServe</strong>: Serving AI Models across Regions and Clouds with Spot Instances<br>
    Ziming Mao, Tian Xia, Zhanghao Wu, Wei-Lin Chiang, <strong>Tyler Griggs</strong>, Romil Bhardwaj, Zongheng Yang, Scott Shenker, Ion Stoica<br>
    <span style="font-style:italic">EuroSys 2025</span> 
    [<a style="text-decoration:none" href="https://arxiv.org/pdf/2411.01438" target="_blank">Paper</a>]
    [<a style="text-decoration:none" href="https://github.com/skypilot-org/skypilot" target="_blank">Code</a>]
  </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 1.5em;">
  <img src="{{ base_path }}/images/melange-thumbnail.png" alt="Mélange" style="width: 200px; height: auto; margin-right: 15px;">
  <div>
    <strong>Mélange</strong>: Cost Efficient Large Language Model Serving by Exploiting GPU Heterogeneity<br>
    <strong>Tyler Griggs</strong>, Xiaoxuan Liu, Jiaxiang Yu, Doyoung Kim, Wei-Lin Chiang, Alvin Cheung, Ion Stoica<br>
    <span style="font-style:italic">arXiv preprint</span> 
    [<a style="text-decoration:none" href="https://arxiv.org/abs/2404.14527" target="_blank">Paper</a>] 
    [<a style="text-decoration:none" href="https://github.com/tyler-griggs/melange-release" target="_blank">Code</a>]
  </div>
</div>


<!-- *MoE-Lightning*: High-Throughput MoE Inference on Memory-constrained GPUs\
Shiyi Cao, Shu Liu, **Tyler Griggs**, Peter Schafhalter, Xiaoxuan Liu, Ying Sheng, Joseph E Gonzalez, Matei Zaharia, Ion Stoica\
<span style="font-style:italic">ASPLOS 2025</span> [<a style="text-decoration:none" href="https://arxiv.org/abs/2411.11217" target="_blank">Paper</a>] -->


<!-- *SkyServe*: Serving AI Models across Regions and Clouds with Spot Instances\
Ziming Mao, Tian Xia, Zhanghao Wu, Wei-Lin Chiang, **Tyler Griggs**, Romil Bhardwaj, Zongheng Yang, Scott Shenker, Ion Stoica\
<span style="font-style:italic">arXiv preprint</span> [<a style="text-decoration:none" href="https://arxiv.org/pdf/2411.01438" target="_blank">Paper</a>]

*Mélange*: Cost Efficient Large Language Model Serving by Exploiting GPU Heterogeneity\
**Tyler Griggs**, Xiaoxuan Liu, Jiaxiang Yu, Doyoung Kim, Wei-Lin Chiang, Alvin Cheung, Ion Stoica\
<span style="font-style:italic">arXiv preprint</span> [<a style="text-decoration:none" href="https://arxiv.org/abs/2404.14527" target="_blank">Paper</a>] [<a style="text-decoration:none" href="https://github.com/tyler-griggs/melange-release" target="_blank">Code</a>] -->







<!-- Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful. -->
