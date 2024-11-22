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

I am currently a master student at Tsinghua University, Beijing, China, advised by [Prof. Yu Jiang](https://sites.google.com/site/jiangyu198964/home). I am proud to be a member of the [Software System Security Assurance Group - WingTecher Lab](http://wingtecher.com/homeen). Previously, I received my bachelor's degree from Sichuan University, Chengdu, China.

<!-- I am interested in the intersection of data, security and system, with a focus on program analysis, malware analysis and mitigation, data and privacy protection, fuzzing, and IoT security.  -->
I am interested in the intersection of security, software systems, and data. To understand and mitigate evolving computer security threats, I work to design and develop practical tools to detect and defend against a wide range of vulnerabilities in software and systems, e.g., attack investigation (S&P Oakland'23, **ICSE'24**), detection (ICCCN'21, **IP&M 2022**, FSE'25-InSubmission), and defense (EMSOFT'22, **ISSTA'25-InSubmission**). I am also working on an LLM4Sec project with [Prof. Grant Ho](https://people.cs.uchicago.edu/~grantho/) at UChicago from summer 2024.

<!-- My research journey explores both established and emerging domains, aiming to contribute to the broader field of computer security through innovative solutions. -->

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

In my free time, I'm into table tennis, running, science fictions, and livehouse band performance.

<span style="color:#8b0000;word-break: break-all;">I am applying to Ph.D. programs for 2025 Fall, with a focus on Security / SE. I would appreciate any information you can [provide](https://forms.gle/AePyPfaubzpnghCS6)!</span>


# News
- *07/2024*: &nbsp;I am spending this summer at the University of Chicago as a visiting student researcher, hosted by [Prof. Grant Ho](https://people.cs.uchicago.edu/~grantho/). Excited!
- *04/2024*: &nbsp;Gave a talk in ICSE'24 research track. Shout out to the new friends I met in Lisbon!
- *10/2023*: &nbsp;MarauderMap is accepted to ICSE'24. Let's meet in Lisbon, Portugal next April. 🎉
- *03/2023*: &nbsp;Animagus is accepted to S&P Oakland'23. 🎉
- *09/2022*: &nbsp;New journey begins at Tsinghua University!
- *08/2022*: &nbsp;Midas is accepted to EMSOFT'22. 🎉
- *07/2022*: &nbsp;CJI-Framework is accepted to IP&M. 🎉
- *06/2022*: &nbsp;Graduated from Sichuan University. Bye, Chengdu. Bye, pandas.🐼🐼🐼 [Ceremony](https://mp.weixin.qq.com/s/8xPnhNNIVBTAbcWJ0B3YuQ) / [Vlog](https://mp.weixin.qq.com/s/5hp2exmWC_AVrnt6am6Xjw)
- *06/2022*: &nbsp;Selected as 'Top 10 Undergraduate of 2022'. Thank you for everyone who supports me! [News](https://mp.weixin.qq.com/s/GsRuXo34gxnd-dSp1M1lqg)
- *05/2022*: &nbsp;Gave a talk in the School of Cyber Science and Engineering, SCU. [News 网安菁英](https://mp.weixin.qq.com/s/XEt_xmzoEWVw0ZTpsEhDfA)



# Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICSE'24</div><img src='images/icse24.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**An Empirical Study of Data Disruption by Ransomware Attacks**

**Yiwei Hou**, Lihua Guo, Chijin Zhou, Yiwen Xu, Zijing Yin, Shanshan Li, Chengnian Sun, Yu Jiang

The 46th IEEE/ACM International Conference on Software Engineering (ICSE'24)

[PDF](http://wingtecher.com/themes/WingTecherResearch/assets/papers/paper_from_24/MarauderMap_ICSE24.pdf) / [Dataset](https://github.com/THU-WingTecher/MarauderMap) / [Code](https://github.com/m1-llie/MarauderMap-code) / [Slides](https://m1llie.tech/files/ICSE24-MarauderMap.pdf) / [DOI](https://doi.org/10.1145/3597503.3639090)

Acceptance Rate: 234/1051=22.3%
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Oakland'23</div><img src='images/sp23.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Limits of I/O Based Ransomware Detection: An Imitation Based Attack**

Chijin Zhou, Lihua Guo, **Yiwei Hou**, Zhenya Ma, Quan Zhang, Mingzhe Wang, Zhe Liu, Yu Jiang

The 44th IEEE Symposium on Security and Privacy (IEEE S&P / Oakland'23)

[PDF](http://wingtecher.com/themes/WingTecherResearch/assets/papers/animagus-SP23.pdf) / [Code](https://github.com/ChijinZ/Animagus) / [Talk](https://www.youtube.com/watch?v=cDC0Vwieez0) / [DOI](https://doi.ieeecomputersociety.org/10.1109/SP46215.2023.00170)

Acceptance Rate: 195/1147=17.0%

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMSOFT'22</div><img src='images/emsoft22.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**MIDAS: Safeguarding IoT Devices Against Malware via Real-Time Behavior Auditing**

Yiwen Xu, Zijing Yin, **Yiwei Hou**, Jianzhong Liu, Yu Jiang

The 22nd ACM SIGBED International Conference on Embedded Software (EMSOFT'22)

IEEE Transactions on Computer Aided Design of Integrated Circuits & Systems (TCAD 2022)

[PDF](http://wingtecher.com/themes/WingTecherResearch/assets/papers/Emsoft22_Midas.pdf) / [Talk](https://www.youtube.com/watch?v=aVdYldzkVks) / [DOI](https://doi.org/10.1109/TCAD.2022.3200908)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IP&M 59(5)</div><img src='images/ipm22.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Identification of Chinese Dark Jargons in Telegram Underground Markets Using Context-oriented and Linguistic Features**

**Yiwei Hou**, Hailin Wang, Haizhou Wang

Information Processing and Management (IP&M 2022 59(5))

[PDF](https://www.sciencedirect.com/science/article/abs/pii/S030645732200142X) / [Code](https://github.com/m1-llie/CJI-Framework) / [Dataset](https://github.com/m1-llie/TUMCC) / [DOI](https://doi.org/10.1016/j.ipm.2022.103033)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCCN'21</div><img src='images/icccn21.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**A Novel Framework of Identifying Chinese Jargons for Telegram Underground Markets**

Hailin Wang, **Yiwei Hou**, Haizhou Wang

The 30th IEEE International Conference on Computer Communications and Networks (ICCCN'21)

[PDF](https://ieeexplore.ieee.org/abstract/document/9522221) / [DOI](https://doi.org/10.1109/ICCCN52240.2021.9522221)

</div>
</div>



# Honors and Awards
- Deng Feng Fund for International Conference Travel, Tsinghua University (2024)
- Excellent Comprehensive Scholarship, Tsinghua University (2022, 2023, 2024)
- Outstanding Social Service Scholarship, Tsinghua University (2023)
- Outstanding Undergraduate Award, Sichuan Province (2022)
- ‘Top 10 Undergraduate of 2022’, Sichuan University (Top 0.03% in SCU) (2022)
- National Scholarship, Ministry of Education of China (Top 0.2% in China) (2019, 2020)
- 1st Prize in the National College Student Information Security Contest, China Internet Development Foundation (2020)
- Cybersecurity Merit Student Scholarship, Sichuan University (2019)



# Education
- *09/2022 - 06/2025(expected)*, M.Eng. in Software Engineering, Tsinghua University. GPA 3.90/4.0
- *09/2018 - 06/2022*, B.Eng. in Cybersecurity, Sichuan University. GPA 3.96/4.0, Ranked 1/172
- *07/2019*, Summer Session in EECS, University of California, Berkeley.



# Service
- Teaching Assistant: Model-driven Software Development@Tsinghua, Fall 2024, Course No.44100662
- Journal Reviewer: Information Processing & Management
- Artifact Evaluation Committee (AEC): CCS'23, ISSTA'24
- External Reviewer: EMSOFT'22, ICSE'24, FSE'24, ISSTA'24, EMSOFT'24, ICSE'25, FSE'25



<span style="color:#808080;word-break: break-all;">Webpage Last Updated: Nov 3, 2024</span>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2024 Spring in THU</div><img src='images/spring.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICSE24 in Lisbon</div><img src='images/ICSE24-attendence.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICSE24 in Lisbon</div><img src='images/ICSE24-attendence-2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
