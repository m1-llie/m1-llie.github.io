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

Hi! I am a master student at Tsinghua University, advised by [Prof. Yu Jiang](https://sites.google.com/site/jiangyu198964/home), working with folks at [WingTecher Lab - Software System Security Assurance Group](http://wingtecher.com/homeen). 
I am interested in the intersection of security, software systems, and data. To understand and mitigate evolving computer security threats, I work to design and develop practical tools to detect and defend against a wide range of vulnerabilities in software and systems, e.g., attack investigation (IEEE S&P "Oakland" 23, **ICSE'24**), detection (**IP&M 2022**, FSE'25), and defense (EMSOFT'22, **ISSTA'25**). I am also working on an LLM for Security project with [Prof. Grant Ho](https://people.cs.uchicago.edu/~grantho/) at UChicago from summer 2024.

<!-- My research journey explores both established and emerging domains, aiming to contribute to the broader field of computer security through innovative solutions. -->

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

In my free time, I am into table tennis, running, science fictions, and livehouse band performance.

A special thank you goes to [Yihao](https://www.usenix.org/conference/usenixsecurity24/presentation/chen-yihao) for taking this profile photo.


# News
**[Jan 2025]** *RansomRadar* is accepted to FSE'25. This year's conference will be co-located with ISSTA'25 in Norway. 🎉

**[Dec 2024]** *Remembrall* is accepted to ISSTA'25. Let's meet in Trondheim, Norway next June. 🎉

**[July 2024]** I am spending this summer at the University of Chicago as a visiting student researcher, hosted by [Prof. Grant Ho](https://people.cs.uchicago.edu/~grantho/). Excited!

**[April 2024]** Gave a talk in ICSE'24 research track. Shout out to the new friends I met in Lisbon!

**[Oct 2023]** *MarauderMap* is accepted to ICSE'24. Let's meet in Lisbon, Portugal next April. 🎉

**[March 2023]** *Animagus* is accepted to IEEE S&P "Oakland" 23. 🎉

**[Sep 2022]** New journey begins at Tsinghua University!

**[June 2022]** Graduated from Sichuan University. Bye, Chengdu. Bye, pandas.🐼🐼🐼 [Ceremony](https://mp.weixin.qq.com/s/8xPnhNNIVBTAbcWJ0B3YuQ) / [Vlog](https://mp.weixin.qq.com/s/5hp2exmWC_AVrnt6am6Xjw)

**[June 2022]** Selected as 'Top 10 Undergraduate of 2022'. Thank you for everyone who supports me! [News](https://mp.weixin.qq.com/s/GsRuXo34gxnd-dSp1M1lqg)

**[May 2022]** Gave a talk in the School of Cyber Science and Engineering, SCU. [News 网安菁英](https://mp.weixin.qq.com/s/XEt_xmzoEWVw0ZTpsEhDfA)



# Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISSTA'25</div><img src='images/issta25.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Preventing Disruption of System Backup Against Ransomware Attacks**

**Yiwei Hou**, Lihua Guo, Chijin Zhou, Quan Zhang, Wenhuan Liu, Chengnian Sun, Yu Jiang

The 34th ACM SIGSOFT International Symposium on Software Testing and Analysis (ISSTA'25)

<!-- [PDF](http://wingtecher.com/themes/WingTecherResearch/assets/papers/paper_from_24/MarauderMap_ICSE24.pdf) / [Dataset](https://github.com/THU-WingTecher/MarauderMap) / [Code](https://github.com/m1-llie/MarauderMap-code) / [Slides](https://m1llie.tech/files/ICSE24-MarauderMap.pdf) / [DOI](https://doi.org/10.1145/3597503.3639090)

Acceptance Rate: 234/1051=22.3% -->
First-round Direct Acceptance: 23/553=4.16%
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">FSE'25</div><img src='images/fse25.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Ransomware Detection Through Temporal Correlation Between Encryption and I/O Behavior**

Lihua Guo, **Yiwei Hou**, Chijin Zhou, Quan Zhang, Yu Jiang

The 33rd ACM International Conference on the Foundations of Software Engineering (FSE'25)

<!-- [PDF](http://wingtecher.com/themes/WingTecherResearch/assets/papers/paper_from_24/MarauderMap_ICSE24.pdf) / [Dataset](https://github.com/THU-WingTecher/MarauderMap) / [Code](https://github.com/m1-llie/MarauderMap-code) / [Slides](https://m1llie.tech/files/ICSE24-MarauderMap.pdf) / [DOI](https://doi.org/10.1145/3597503.3639090)

Acceptance Rate: 234/1051=22.3% -->
First-round Direct Acceptance: 70/612=11.43%
</div>
</div>


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

The 44th IEEE Symposium on Security and Privacy (IEEE S&P "Oakland" 23)

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
**Excellent Comprehensive Scholarship**, Tsinghua University (2022, 2023, 2024)

**Deng Feng Fund for Conference Travel**, Tsinghua University (2024)

**Outstanding Undergraduate Award**, Sichuan Province (Top 3% in the province) (2022)

**'Top 10 Undergraduate of the Year'**, Sichuan University (Top 0.03% in the univ.) (2022)

**National Scholarship**, Ministry of Education of China (Top 0.2% in China) (2019, 2020)




# Education
Sep 2022 - June 2025(expected), M.Eng. in Software Engineering, **Tsinghua University**. GPA 3.90/4.0

Sep 2018 - June 2022, B.Eng. in Cybersecurity, **Sichuan University**. GPA 3.96/4.0, Ranked 1/172



# Academic Service
**[Teaching Assistant]** Model-driven Software Development, Tsinghua University, Fall 2024, Course No.44100662 (for ~80 undergraduates)

**[Journal Reviewer]** Information Processing & Management

**[Artifact Evaluation Committee]** CCS'23, ISSTA'24

**[External Reviewer]** EMSOFT(2022,2024), ICSE(2024,2025), FSE(2024,2025), ISSTA(2024,2025)



<span style="color:#808080;word-break: break-all;">Last updated on March 3, 2025. Thanks to [Yi Ren](https://rayeren.github.io/) for the awesome website template [AcadHomepage](https://github.com/RayeRen/acad-homepage.github.io). </span>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2024 Spring at Tsinghua</div><img src='images/spring.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICSE24 in Lisbon</div><img src='images/ICSE24-attendence.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICSE24 in Lisbon</div><img src='images/ICSE24-attendence-2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
