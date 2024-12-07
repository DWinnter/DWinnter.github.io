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

I am a undergraduate student in senior year at [College of Computer Science and Technology,](http://www.en.cs.zju.edu.cn/) [Zhejiang University](https://www.zju.edu.cn/english/). During my bachelor years, I've accomplished numerous [academic courses](https://bksy.zju.edu.cn/_upload/article/files/14/1d/ce579d614c9f9c920d21873a7c5d/62a39cc7-675e-4f14-a31e-4e406a0949ea.pdf) including Data Structures and Algorithms, Computer Architecture, Computer Networks, AI and so on. Meanwhile, I had 4 major extracurriculum acadmic/project experiences in [Human and Computer Interaction](#hci), [Data Visualization](#dv), [Cybersecurity](#cyber), and [Large Language Models](#llm). This summer, I visited University of Pennsylvania and cooperated with Prof. [Weijie Su](https://statistics.wharton.upenn.edu/profile/suw/) on a project regarding efficient tokenization for LLMs, which was now [under review](https://openreview.net/forum?id=QIBLeMtyMS&noteId=QIBLeMtyMS) in AISTATS 2025. Currently, I am working on my bachelor thesis under guidance of Prof. [Shouling Ji](https://person.zju.edu.cn/en/sji#0) and senior members in [NESA Lab](https://nesa.zju.edu.cn/).

Apart from academic education in College of Computer Science and Technology, I pursued diversity and well-rounded development as well. I took a minor in [Zhejiang University Chu-kochen Honors College](http://ckc.zju.edu.cn/ckcen/2022/0225/c44633a2500660/page.htm), with [courses](./pyfayl_cxPyfaylPdf.pdf) covering Economics and Entrepreneurship.

<span class='anchor' id='experience'></span>

# 📝 Academic and Project Experience (As leader)

<span class='anchor' id='llm'></span>

<div class='paper-box'><div class='paper-box-image' ><div><div class="badge">A high compression ratio tokenizer<br>different from BPE and others</div><img src='images/frontpage.png' alt="sym" width="100%"></div></div>

<div class='paper-box-text' markdown="1">


Crew member(s):**Dong Dong**

Director: [Weijie Su](https://statistics.wharton.upenn.edu/profile/suw/)

Research on a new tokenizer, aimed to represent more words in one token: [**Repository**](https://github.com/DWinnter/tokenizers_clique_partition)
- Proposing a new tokenization method for LLMs, with maximizaing average token length as its goal. Utilizing clique partition algorithm to find the largest-covering clique in the corpus, as the new token found for each round.
- A paper written on this topic, [Length-Maximization Tokenization for Language Models: An Approximation Algorithm](https://openreview.net/pdf?id=QIBLeMtyMS).

</div>
</div>



<span class='anchor' id='cyber'></span>

<div class='paper-box'>

<div class='paper-box-image'>
<div style="display: flex; flex-direction: column; gap: 20px;">
    <div>
        <div class="badge">Project on AIGC detection</div>
        <img src='images/20241207190836.jpg' alt="sym" width="100%">
    </div>
    <div>
        <div class="badge">Report to the Minister of Education of China</div>
        <img src='images/2024-12-07202530.png' alt="achievement" width="100%">
    </div>
</div>
</div>


<div class='paper-box-text' markdown="1">


Crew member(s): **Dong Dong**, Enhao Huang, Sijie Zhi, Pengyu Sun, Zixin Lin, Shuang Chen, Ruizi Yu, Chengming Qian, Hongyi Ren, Jiaying Ding, Chaoran Zhang, Kaichun Hu, Leyi Qian, Lingqi Jiang, Xingcan Wangyuan

Director: [Shouling Ji](https://person.zju.edu.cn/en/sji#0), [Jianhai Chen](https://person.zju.edu.cn/en/cjhe#0)

Developed a detection system for AIGC content that improves detection accuracy and robustness through multi-feature fusion and adversarial training: [**Repository**](https://github.com/DWinnter/DragonZhu)
- Key features include:
  - High-precision detection algorithm based on multi-feature fusion, combining spatial-temporal feature differences from images and audio to enhance detection performance in complex multi-modal scenarios
  - Robust detection against attacks through data augmentation and defensive distillation techniques to strengthen model resistance to adversarial attacks
- The system efficiently and accurately identifies AIGC content across multiple modalities while protecting user privacy through homomorphic encryption, providing solutions to security challenges posed by AIGC

---

**🎉 Highlights:**
- This project won the first prize in [The China International College Students' Innovation Competition (2024)](https://www.pilcchina.org/home), outstanding as the top 100 among 5140000 projects this year.
- We are selected as the only undergraduate team to report and interact with [the Minister of Education of China](https://mp.weixin.qq.com/s/ieVh0foME9xea7sK_usyYg) at the Achievement Exhibition affliated with the competition.
- We are invited to a [symposium](https://mp.weixin.qq.com/s/ceJu9Fponx0C2vQo96Sjbg) held by the headmaster of Zhejiang University, where I made an report as well.

</div>
</div>


<span class='anchor' id='dv'></span>

<div class='paper-box'>

<div class='paper-box-image'>
<div style="display: flex; flex-direction: column; gap: 20px;">
    <div>
        <div class="badge">Research training on multi-modal data visualization</div>
        <img src='images/chartgpt2.png' alt="sym" width="100%">
    </div>

</div>
</div>


<div class='paper-box-text' markdown="1">


Crew member(s): **Dong Dong**, Yanan Wang, Mingyu Zhang

Director: [Wei Chen](https://person.zju.edu.cn/en/wei_chen#0)

Developed an intelligent visual analysis system for cross-domain multi-modal data: [**Repository**](https://github.com/DWinnter/ChartGPT)

Key features include:
- A novel federated data representation mechanism that enables secure cross-domain data analysis
- Human-machine collaborative visual analysis paradigm powered by deep learning and knowledge reasoning to provide personalized visual analytics services
- Cross-task knowledge transfer framework that enables reuse of visual analytics knowledge across different scenarios through ontology construction and knowledge graphs
- Comprehensive analysis pipeline from data processing to visual exploration with excellent extensibility and user-friendliness


</div>
</div>


<span class='anchor' id='hci'></span>

<div class='paper-box'>

<div class='paper-box-image'>
<div style="display: flex; flex-direction: column; gap: 20px;">
    <div>
        <div class="badge">Research on HCI</div>
        <img src='images/Watchoff_for_CHI_00.png' alt="sym" width="100%">
    </div>

</div>
</div>


<div class='paper-box-text' markdown="1">


Crew member(s): **Dong Dong**, Zihan Yan, Zexia Yang

Director: [Guanyun Wang](https://person.zju.edu.cn/en/guanyun), [Xiang Anthony Chen](https://hci.prof/)

Participated in a research project on human-computer interaction under the guidance of Professor Wang Guanyun from Zhejiang University and Professor Xiang Anthony Chen from UCLA.

Details:
- It's my first research, at the beggining year of my college life. We investigated novel interaction design approaches to reduce over-reliance on wearable fitness trackers
- I Led software development and independently developed an Android app for an 8-week user study after self-learning Android Studio
- We Conducted comprehensive user studies across 8 weeks and 20 participants to validate the effectiveness of identity-based interface design and developed practical solutions to promote healthier relationships with fitness tracking technology
- Eventually we wrote a paper and submitted it to CHI 2023, however, unfortunately it was rejected lol. But I still think it's a good work and a valuable experience for me. You can view it if interested. [Take Off Your Sports Watch: Designing Identity-based Interface to Reduce the
Over-reliance of Physical Activity Monitoring Wearables](./_pages/Watchoff_for_CHI.pdf)

</div>
</div>

<span class='anchor' id='honors'></span>

# 🎖 Honors and Awards
- *2023.12-2024.10*, The China International College Students' Innovation Competition - Gold Award (First Prize), Third Place in Zhejiang Province, Top 100 among 5,140,000 participating teams nationwide
- *2024.10*, National Honors College Student Research Innovation Competition - Second Prize, Top 15 among 84 participating teams nationwide
- *2022, 2023, 2024*, Zhejiang University Outstanding Public Service Award, Outstanding Social Work Award and scholarship


<span class='anchor' id='education'></span>
# 📖 Educations
- *2021.09 - 2025.07(expected)*, College of Computer Science and Technology, Zhejiang University, [link](http://www.en.cs.zju.edu.cn/)
- *2018.09 - 2021.07*, Hangzhou No.2 High School, [link](https://en.wikipedia.org/wiki/Hangzhou_No._2_High_School)

<span class='anchor' id='activities'></span>
# 🌞 Hobbies and Extra-curricular Activities
