---
title: 'On the (In)Security of Secure ROS2'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Gelei Deng
  - Guowen Xu
  - Yuan Zhou
  - Tianwei Zhang
  - Yang Liu

date: '2022-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-07-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: In *Wowchemy Conference*
publication_short: In *ACM CCS 2022*

abstract: Robot Operating System (ROS) has been the mainstream platform for research and development of robotic applications. This platform is well-known for lacking security features and efficiency for distributed robotic computations. To address these issues, ROS2 is recently developed by utilizing the Data Distribution Service (DDS) to provide security support. Integrated with DDS, ROS2 is expected to establish the basis for trustworthy robotic ecosystems. In this paper, we systematically study the security of the current ROS2 implementation from three perspectives. By abstracting the key functions from the ROS2 native implementation, we first formally describe the ROS2 system communication workflow and model it using a concurrent modeling language. Second, we verify the model with some key security properties through a model checker, and successfully identify four security vulnerabilities in ROS2's native security module, Secure ROS2 (SROS2). To validate these flaws, we set up simulation and physical multi-robot testbeds running different real-world workloads developed by Open Robotics and Amazon AWS Robotics. We demonstrate that an adversary can exploit these vulnerabilities to totally invalidate the security protection offered by SROS2, and obtain unauthorized permissions or steal critical information. Third, to enhance the security of ROS2, we propose a general defense solution based on the private broadcast encryption scheme. We run different workloads and benchmarks to show the efficiency and security of our defense. Our findings have been acknowledge by ROS2 official, and the suggested mitigation has been implemented in the latest SROS2 version.

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