---
permalink: /
title: "Welcome to Pan Li's website"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.htmlrave
---

ABOUT ME
======
I’m a 3rd year PhD candidate in the Department of Technology, Operations and Statistics (TOPS) within the Lenoard N. Stern School of Business at the New York University. My research focuses on recommender systems, where I aim to improve the design of recommendation models as well as studying their impact on consumers. The algorithms that I developed have been deployed in several companies, including
* Baidu (serving intelligent recruitment applications)
* Alibaba (serving short video recommendations)

Methodology: Deep Learning, Machine Learning, Econometrics, Online A/B Test, Causal Inference
You can find my CV here.

Education
======
* B.S. in Mathematics and Computer Science (Minor), University of Science and Technology of China, 2017
* Ph.D in Information System, New York University, Stern School of Business, 2022 (expected)

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Industrial Experience
======
* Alibaba Inc., Research Intern, June 2019 - August 2019
  * Department: Youku Video Recommendation Team
  * Task: Constructing unexpected recommender system to break through filter bubbles
  * Result: Online A/B test shows significantly improvements in video view
  * The proposed model has been deployed for serving short video recommendations.

* Sinovation Ventures, Research Intern, June 2017 - August 2017
  * Department: Artificial Intelligence Lab
  * Task: Combining GAN with Seq2Seq Model for automatic lyric generation
  * Result: Significantly improves the generation perfromance
 
* Baidu Inc., Research Intern, October 2016 - March 2017
  * Department: Baidu Big Data Lab
  * Task: Constructing recruitment system to match available jobs with suitable applicants
  * Result: Sigificantly improves matching efficiency and accuracy
  * The proposed model has been deployed for serving intelligent recruitment applications
