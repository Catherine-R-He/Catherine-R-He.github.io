---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a third-year computer science PhD student at [Vislang Lab](https://www.vislang.ai), [Rice University](https://csweb.rice.edu/), advised by [Prof. Vicente Ordóñez](http://vicenteordonez.com). Prior to this, I obtained a BSc degree (First Class Honours) from [City University of Hong Kong](https://www.cityu.edu.hk/), where I had the privilege of working with [Prof. Rynson W.H. Lau](https://www.cs.cityu.edu.hk/~rynson/) and [Prof. Antoni B. Chan](https://www.cs.cityu.edu.hk/~abchan/).

My primary research interests lie in computer vision, with a focus on efficient algorithms under less or multimodal supervision. During my PhD, I have worked on multimodal understanding and reasoning with RL, efficient generative models for images and videos, and multi-agent systems for UI navigation.

I will graduate in May 2027 and am actively looking for **full-time research roles** in industry. Do not hesitate to reach out if you would like to chat!

<!-- # 🔥 News -->
# News
- \[*01/2026*\] I joined ByteDance as a research scientist intern.
- \[*09/2025-01/2026*\] I will serve as a reviewer for ICLR 2026, CVPR 2026, and ECCV 2026.
- \[*07/2025*\] Our paper ["Learning from Synthetic Data for Visual Grounding"](https://catherine-r-he.github.io/SynGround/) is accepted to BMVC 2025.
- \[*05/2025*\] I joined Amazon AWS AI Labs as a research intern this summer.
- \[*05/2025*\] I have been recognized as an [Outstanding Reviewer at CVPR 2025](https://cvpr.thecvf.com/Conferences/2025/ProgramCommittee#all-outstanding-reviewer).
- \[*08/2024-03/2025*\] I will serve as a reviewer for T-PAMI, IJCV, ICLR 2025, CVPR 2025, ICML 2025, ICCV 2025, and NeurIPS 2025.
- \[*11/2024*\] I have been awarded the Ken Kennedy Institute 2024/25 Ken Kennedy-HPE Cray Graduate Fellowship.
- \[*11/2024*\] I have been recognized as a [top reviewer at NeurIPS 2024](https://neurips.cc/Conferences/2024/ProgramCommittee#top-reviewers).
- \[*02/2024*\] Our paper ["Improved Visual Grounding through Self-Consistent Explanations"](https://catherine-r-he.github.io/SelfEQ/) is accepted to CVPR 2024.
- \[*08/2023-05/2024*\] I will serve as a reviewer for ICLR 2024, CVPR 2024, ICML 2024, ECCV 2024, and NeurIPS 2024.
- \[*08/2023*\] I started my PhD study at VisLang Lab, Rice University.
- \[*08/2023*\] I won the first runner-up prize in the IEEE (Hong Kong) Computational Intelligence Chapter Final Year Project Competition 2022-2023.
- \[*06/2023*\] I graduated from City University of Hong Kong with First Class Honours.
<!-- - \[*04/2023*\] I will serve as a reviewer for NeurIPS 2023.-->


<!-- # 📖 Educations -->
# Education
- *2023 - 2027 (Expected)*, PhD in Computer Science, Rice University.
- *2019 - 2023*, BSc in Computer Science (First Class Honours), City University of Hong Kong.


# Work Experience
- *Jan 2026 - Present*, Research Scientist Intern, ByteDance (NextGen Recommendation Team @ TikTok Data).
- *May 2025 - Nov 2025*, Applied Scientist Intern, Amazon AWS AI Labs (Amazon Quick Science Team @ Agentic AI).

# Preprints
<div class='paper-box'><div class='paper-box-image'><div><img src='images/NoiseShift.png' alt="NoiseShift teaser" width=150px></div></div>
<div class='paper-box-text' markdown="1">
**NoiseShift: Resolution-Aware Noise Recalibration for Better Low-Resolution Image Generation** [[Paper]](https://arxiv.org/abs/2510.02307) <br />
**Ruozhen He**, Moayed Haji-Ali, Ziyan Yang, Vicente Ordonez<br />
October, 2025. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/GViT.png' alt="GViT teaser" width=150px></div></div>
<div class='paper-box-text' markdown="1">
**GViT: Representing Images as Gaussians for Visual Recognition** [[Paper]](https://arxiv.org/abs/2506.23532) <br />
Jefferson Hernandez, **Ruozhen He**, Guha Balakrishnan, Alexander C. Berg, Vicente Ordonez<br />
June, 2025. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/Fairness-survey-Teaser.png' alt="Fairness survey teaser" width=150px></div></div>
<div class='paper-box-text' markdown="1">
**Fairness and Bias Mitigation in Computer Vision: A Survey** [[Paper]](https://arxiv.org/abs/2408.02464) <br />
Sepehr Dehdashtian\*, **Ruozhen He**\*, Yi Li, Guha Balakrishnan, Nuno Vasconcelos,<br /> Vicente Ordonez, Vishnu Naresh Boddeti (*Joint First Authors) <br />
August, 2024. 
</div>
</div>

<!-- # 📝 Publications  -->
# Publications 
<div class='paper-box'><div class='paper-box-image'><div><img src='images/SynGround-Teaser.png' alt="SynGround teaser" width=150px></div></div>
<div class='paper-box-text' markdown="1">
**Learning from Synthetic Data for Visual Grounding** [[Paper]](https://arxiv.org/abs/2403.13804) [[Project Page]](https://catherine-r-he.github.io/SynGround/) <br />
**Ruozhen He**, Ziyan Yang, Paola Cascante-Bonilla, Alexander C. Berg, Vicente Ordóñez <br />
The British Machine Vision Conference. **BMVC 2025**.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><img src='images/CVPR2024-SelfEQ.png' alt="CVPR 2024 Paper Improved Visual Grounding through Self-Consistent Explanations" width=150px></div></div>
<div class='paper-box-text' markdown="1">
**Improved Visual Grounding through Self-Consistent Explanations** [[Paper]](https://arxiv.org/abs/2312.04554) [[Code]](https://github.com/uvavision/SelfEQ) [[Project Page]](https://catherine-r-he.github.io/SelfEQ/) <br />
**Ruozhen He**, Paola Cascante-Bonilla, Ziyan Yang, Alexander C. Berg, Vicente Ordóñez <br />
The IEEE/CVF Conference on Computer Vision and Pattern Recognition.  **CVPR 2024**. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/AAAI23-WCOD.png' alt="AAAI-23 Paper Weakly-Supervised Camouflaged Object Detection with Scribble Annotations" width=150px></div></div>
<div class='paper-box-text' markdown="1">
**Weakly-Supervised Camouflaged Object Detection with Scribble Annotations** [[Paper]](https://arxiv.org/abs/2207.14083) [[Code]](https://github.com/dddraxxx/Weakly-Supervised-Camouflaged-Object-Detection-with-Scribble-Annotations) [[Dataset]](https://github.com/dddraxxx/Weakly-Supervised-Camouflaged-Object-Detection-with-Scribble-Annotations) <br />
**Ruozhen He**\*, Qihua Dong\*, Jiaying Lin, Rynson W.H. Lau (*Joint First Authors)  <br />
Proceedings of the AAAI Conference on Artificial Intelligence. **AAAI-23**. <font color='red'> (~Oral Presentation) </font>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/AAAI23-EfficientMirror.png' alt="AAAI-23 Paper Efficient Mirror Detection via Multi-level Heterogeneous Learning" width=150px></div></div>
<div class='paper-box-text' markdown="1">
**Efficient Mirror Detection via Multi-level Heterogeneous Learning** [[Paper]](https://arxiv.org/abs/2211.15644) [[Code]](https://github.com/Catherine-R-He/HetNet)  
**Ruozhen He**, Jiaying Lin, Rynson W.H. Lau  
Proceedings of the AAAI Conference on Artificial Intelligence. **AAAI-23**. <font color='red'> (~Oral Presentation) </font>
</div>
</div>

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# Service
- CVPR 2024/2025/2026, Reviewer
- ICCV 2025, Reviewer
- ECCV 2024/2026, Reviewer
- NeurIPS 2023/2024/2025, Reviewer
- ICLR 2024/2025/2026, Reviewer
- ICML 2024/2025, Reviewer
- T-PAMI, Reviewer
- IJCV, Reviewer

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->
<!-- 
# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->
