---
title: "Syllabus: Portable Curricula for Reinforcement Learning Agents"
authors:
  - Ryan Sullivan
  - admin
  - Ameen Ur Rahmen
  - Xinchen Yang
  - Junyun Huang
  - Aayush Verma
  - Nistha Mitra
  - John P. Dickerson
date: "2024-11-19T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-11-19T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["preprint"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ArXiv preprint

abstract: Curriculum learning has been a quiet yet crucial component of many of the high-profile successes of reinforcement learning. Despite this, none of the major reinforcement learning libraries directly support curriculum learning or include curriculum learning implementations. These methods can improve the capabilities and robustness of RL agents, but often require significant, complex changes to agent training code. We introduce Syllabus, a library for training RL agents with curriculum learning, as a solution to this problem. Syllabus provides a universal API for curriculum learning algorithms, implementations of popular curriculum learning methods, and infrastructure for easily integrating them with distributed training code written in nearly any RL library. Syllabus provides a minimal API for each of the core components of curriculum learning, dramatically simplifying the process of designing new algorithms and applying existing algorithms to new environments. We demonstrate that the same Syllabus code can be used to train agents written in multiple different RL libraries on numerous domains. In doing so, we present the first examples of curriculum learning in NetHack and Neural MMO, two of the premier challenges for single-agent and multi-agent RL respectively, achieving strong results compared to state of the art baselines.

# Summary. An optional shortened abstract.
summary: Syllabus provides a universal API for curriculum learning algorithms, implementations of popular curriculum learning methods, and infrastructure for easily integrating them with distributed training code written in nearly any RL library. Syllabus provides a minimal API for each of the core components of curriculum learning, dramatically simplifying the process of designing new algorithms and applying existing algorithms to new environments.

tags:
  - Source Themes
featured: true

links:
  - name: ArXiv
    url: https://arxiv.org/abs/2411.11318
url_pdf: https://arxiv.org/pdf/2411.11318
url_code: https://github.com/RyanNavillus/Syllabus/tree/b88c2fcba4658545e156188c85f48f0b1e54aab2
# url_dataset: "#"
# url_poster: "#"
# url_project: ""
# url_slides: ""
# url_source: "#"
# url_video: "#"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)"
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - internal-project
# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
