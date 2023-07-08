---
title: 'NAUTILUS: Automated RESTful API Vulnerability Detection'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Gelei Deng
  - Zhiyi Zhang
  - Yuekang Li
  - Yi Liu
  - Tianwei Zhang
  - Yang Liu
  - Guo Yu
  - Dongjin Wang

date: '2023-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-07-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: In *Wowchemy Conference*
publication_short: In *USENIX Security 2023*

abstract: RESTful APIs have become arguably the most prevalent endpoint for accessing web services. Blackbox vulnerability scanners are a popular choice for detecting vulnerabilities in web services automatically. Unfortunately, they suffer from a number of limitations in RESTful API testing. Particularly, existing tools cannot effectively obtain the relations between API operations, and they lack the awareness of the correct sequence of API operations during testing. These drawbacks hinder the tools from requesting the API operations properly to detect potential vulnerabilities. To address this challenge, we propose NAUTILUS, which includes a novel specification annotation strategy to uncover RESTful API vulnerabilities. The annotations encode the proper operation relations and parameter generation strategies for the RESTful service, which assist NAUTILUS to generate meaningful operation sequences and thus uncover vulnerabilities that require the execution of multiple API operations in the correct sequence. We experimentally compare NAUTILUS with four state-of-art vulnerability scanners and RESTful API testing tools on six RESTful services. Evaluation results demonstrate that NAUTILUS can successfully detect an average of 141% more vulnerabilities, and cover 104% more API operations. We also apply NAUTILUS to nine real-world RESTful services, and detected 23 unique 0-day vulnerabilities with 12 CVE numbers, including one remote code execution vulnerability in Atlassian Confluence, and three high-risk vulnerabilities in Microsoft Azure, which can affect millions of users.

tags: [Testing]

# Display this page in the Featured widget?
featured: false


---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).