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


# 😊 About Me
I’m a first year PhD student at [DVLab](https://www.dvlab.ai/), [The Chinese University of Hong Kong](https://www.cuhk.edu.hk/chinese/index.html), supervised by Professor [JIA Jiaya](https://jiaya.me/home) and Professor [YU Bei](https://www.cse.cuhk.edu.hk/~byu/). Before that, I obtained my master degree at [AIM3 Lab](https://www.ruc-aim3.com/), [Renmin University of China](https://www.ruc.edu.cn/), under the supervision of Professor [JIN Qin](http://jin-qin.com/). I received my Bachelor’s degree in 2021 from [South China University of Technology](https://www.scut.edu.cn/new/). I was awarded the National Scholarship twice during my undergraduate years and one in graduate years.

My research interest includes Computer Vision and Multi-modal Learning. I have published 3 papers at the top international AI conferences. Here is my <a href='https://scholar.google.com/citations?user=X-OlO2gAAAAJ&hl=en'>google scholar page</a>. I did internship at Tencent video processing group in 2022.

<!-- <span style="color: red;">I'm looking for Ph.D. student positions for 2024 Fall.</span> -->


# 🔥 News
- *2024.12*: &nbsp;🎉🎉 We are excited to release [Lyra](https://lyra-omni.github.io/)! 
- *2024.07*: &nbsp;🎉🎉 One paper is accepted by ACMMM 2024! 
- *2024.04*: &nbsp;🎉🎉 Receive the [Hong Kong PhD Fellowship Scheme](https://cerg1.ugc.edu.hk/hkpfs/index.html)!
- *2024.01*: &nbsp;🎉🎉 Receive the [CUHK Vice-Chancellor's PhD Scholarship Scheme](https://www.gs.cuhk.edu.hk/admissions/scholarships-fees/scholarships)!
- *2023.12*: &nbsp;🎉🎉 Receive National Scholarship!
- *2022.11*: &nbsp;🎉🎉 One paper is accepted by AAAI 2023! 
- *2022.10*: &nbsp;🎉🎉 Our team rank the 1st in Trecvid 2022 VTT task! 
- *2022.05*: &nbsp;🎉🎉 One paper is accepted by ECCV 2023!  

# 📝 Publications 


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv preprint</div><img src='images/LYRA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Lyra: An Efficient and Speech-Centric Framework for Omni-Cognition](https://arxiv.org/pdf/2412.09501)

Zhisheng Zhong*, Chengyao Wang*, **Yuqi Liu***, Senqiao Yang,
Longxiang Tang, Yuechen Zhang, Jingyao Li, Tianyuan Qu, Yanwei Li,
Yukang Chen, Shaozuo Yu, Sitong Wu, Eric Lo, Shu Liu#, Jiaya Jia

[**Project Page**](https://lyra-omni.github.io/) 
- Stronger performance: Achieve SOTA results across a variety of speech-centric tasks. 
- More versatile: Support image, video, speech/long-speech, sound understanding and speech generation.
- More efficient: Less training data, support faster training and inference.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MM 2024</div><img src='images/RTIME.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Reversed in Time: A Novel Temporal-Emphasized Benchmark for Cross-Modal Video-Text Retrieval](https://dl.acm.org/doi/10.1145/3664647.3680731)

Yang Du, **Yuqi Liu**, Qin Jin

- A benchmark aims to evaluate temporal understanding of video retrieval models.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2023</div><img src='images/TOKEN_MIX.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Token Mixing: Parameter-Efficient Transfer Learning from Image-Language to Video-Language](https://ojs.aaai.org/index.php/AAAI/article/view/25267)

**Yuqi Liu**, Luhui Xu, Pengfei Xiong, Qin Jin

[**Project Page**](https://github.com/yuqi657/video_language_model) 
- We study how to transfer knowledge from image-language model to video-language tasks. 
- We have implemented several components proposed by recent works.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Trecvid VTT 2022</div><img src='images/TRECVID_VTT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[TRECVID 2022 task: Video to Text Description
](https://www-nlpir.nist.gov/projects/tvpubs/tv22.papers/rucaim3-tencent.pdf)

Zihao Yue, **Yuqi Liu**, Liang Zhang, Linli Yao, Qin Jin

[**Project Page**](https://github.com/yuezih/BLIP4video)
- We leverage a vision-language pre-training model pre-trained on large-scale image-text datasets for video captioning.
- Our submission ranks 1st in all official evaluation metrics.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2022</div><img src='images/TS2_NET.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[TS2-Net: Token Shift and Selection Transformer for Text-Video Retrieval](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136740311.pdf) 

**Yuqi Liu**, Pengfei Xiong, Luhui Xu, Shengming Cao, Qin Jin

[**Project Page**](https://github.com/yuqi657/ts2_net) 
- TS2-Net is a text-video retrieval model based on [CLIP](https://github.com/openai/CLIP). 
- We propose our token shift transformer and token selection transformer.
</div>
</div>


# 🎖 Honors and Awards
- *2024.04* **Hong Kong PhD Fellowship Scheme**.
- *2024.01* **CUHK Vice-Chancellor's PhD Scholarship Scheme**.
- *2023.11* **National Scholarship**.
- *2019.11* **National Scholarship**.
- *2018.11* **National Scholarship**.

# 📖 Educations
- *2024.08 - 2028.06 (Expect)*, Ph.D., Department of Computer Science and Engineering, The Chinese University of Hong Kong.
- *2021.09 - 2024.06*, M.Phil., School of Information, Renmin University of China. 
- *2017.09 - 2021.06*, B.E., School of Software Engineering, South China University of Technology.

# 💻 Internships
- *2022.01 - 2022.10*, Group of video computing, Tencent, China.
- *2020.04 - 2020.10*, Group of WechatPay HK, Tencent, China.


# 📕 Teaching
- *2024 Fall*, CSCI3170