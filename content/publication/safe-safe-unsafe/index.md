---
title: "Safe + Safe = Unsafe? Exploring How Safe Images Can Be Exploited to Jailbreak Large Vision-Language Models"
authors:
- Chenhang Cui
- admin
- An Zhang
- Jingnan Zheng
- Yicong Li
- Lianli Gao
- Tianwei Zhang
- Tat-Seng Chua
date: "2025-12-02T00:00:00Z"
doi: "10.48550/arXiv.2411.11496"

publishDate: "2025-12-02T00:00:00Z"

publication_types: ["paper-conference"]

publication: "Advances in Neural Information Processing Systems 38 (NeurIPS 2025)"
publication_short: "NeurIPS 2025"

abstract: "This work shows that individually safe images can be combined with prompts to trigger unsafe behavior in large vision-language models. It introduces Safety Snowball Agent, an agent-based framework that uses model reasoning and tool use to generate or retrieve benign-looking visual context and progressively induce harmful outputs."

summary: "NeurIPS 2025 work showing how safe images can combine into multimodal jailbreaks through the Safety Snowball effect."

tags:
- Large Vision-Language Models
- AI Security
- AI Safety
- Multimodal AI

featured: true

links:
- name: arXiv
  url: https://arxiv.org/abs/2411.11496
- name: Code
  url: https://github.com/gzcch/Safety_Snowball_Agent
url_pdf: 'https://arxiv.org/pdf/2411.11496'
url_code: 'https://github.com/gzcch/Safety_Snowball_Agent'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

image:
  caption: ''
  focal_point: ""
  preview_only: false

projects:
- safety-snowball-agent

slides: ""
---

This paper identifies a multimodal safety failure mode where safe visual inputs can snowball into unsafe model behavior when combined with additional safe images and prompts. Safety Snowball Agent operationalizes this observation as a tool-using jailbreak framework for evaluating LVLM guardrails.
