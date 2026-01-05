---
title: "MASTERKEY: Automated Jailbreaking of Large Language Model Chatbots"
authors:
- admin
- Yi Liu
- Yuekang Li
- Kailong Wang
- Ying Zhang
- Zefeng Li
- Haoyu Wang
- Tianwei Zhang
- Yang Liu
date: "2024-02-26T00:00:00Z"
doi: "10.14722/ndss.2024.24188"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-02-26T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings 2024 Network and Distributed System Security Symposium (NDSS)"
publication_short: "NDSS 2024"

abstract: "Large Language Models (LLMs) have revolutionized Artificial Intelligence services due to their exceptional proficiency in understanding and generating human-like text. However, LLM chatbots are susceptible to jailbreak attacks, where malicious users manipulate prompts to elicit inappropriate or sensitive responses. This work presents MASTERKEY, a comprehensive framework that offers an in-depth understanding of jailbreak attacks and countermeasures. We introduce an automatic generation method for jailbreak prompts, leveraging a fine-tuned LLM to validate the potential of automated jailbreak generation across various commercial LLM chatbots, achieving a 21.58% success rate compared to 7.33% by existing methods."

# Summary. An optional shortened abstract.
summary: "A comprehensive framework for automated jailbreaking of Large Language Model chatbots, featuring novel attack methodologies and systematic analysis of defense mechanisms."

tags:
- Large Language Models
- AI Security
- Jailbreak Attacks
- AI Safety

featured: true

links:
- name: NDSS
  url: https://www.ndss-symposium.org/ndss-paper/masterkey-automated-jailbreaking-of-large-language-model-chatbots/
url_pdf: masterkey.pdf
url_code: 'https://github.com/LLMSecurity/MasterKey'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'MASTERKEY Framework Architecture'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- llm-security

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

This work presents MASTERKEY, a systematic approach to understanding and exploiting vulnerabilities in Large Language Model chatbots. The framework introduces novel methodologies for automated jailbreak attack generation and provides comprehensive analysis of existing defense mechanisms.

**Key Contributions:**
- Novel time-based attack strategy inspired by SQL injection techniques
- Automated jailbreak prompt generation achieving 21.58% success rate
- Comprehensive evaluation across mainstream chatbots (ChatGPT, Bard, Bing Chat, Ernie)
- Systematic analysis of defense mechanisms in commercial LLM services

**Impact:** This research has informed major service providers about critical vulnerabilities and contributed to strengthening LLM security measures across the industry.