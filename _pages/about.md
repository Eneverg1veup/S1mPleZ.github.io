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

我将博士毕业于湖南长沙的 国防科技大学 计算机学院。硕士毕业于湖南长沙的 中南大学 计算机学院。本科毕业于黑龙江哈尔滨的 东北林业大学 信息与计算机工程学院（现计算机与控制工程学院）。
 <a href='https://scholar.google.com/citations?user=fsP1ywIAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=引用"></a>。

我的研究领域包括：
- 自然语言处理
- 人工智能
- 大语言模型
- 阿尔兹海默症文本检测
- 上下文学习
  


<span class='anchor' id='-xl'></span>

# 🎓 学历
- *2024.06 - 至今*, <a href="https://www.nudt.edu.cn/"><img class="png" src="/images/nudt_logo.png" width="23pt"></a> 国防科技大学 计算机学院, 湖南长沙, 博士
- *2021.06 - 2024.9*, <a href="https://www.csu.edu.cn/"><img class="svg" src="/images/csu_logo.svg" width="23pt"></a> 中南大学 计算机学院, 湖南长沙, 硕士
- *2017.09 - 2021.06*, <a href="https://www.nefu.edu.cn/"><img class="png" src="/images/NEFU_LOGO.png" width="20pt"></a> 东北林业大学 信息与计算机工程学院（现计算机与控制工程学院）, 黑龙江哈尔滨, 本科
 
<span class='anchor' id='-lwzl'></span>

# 📝 论文专利

### 英文
---
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2026</div><img src='images/DA4ICL.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- `Puzhen Su`, Haoran Yin, Yongzhu Miao, Jintao Tang*, Shasha Li*, Ting Wang*. Beyond Plain Demos: A Demo-centric Anchoring Paradigm for In-Context Learning in Alzheimer's Disease Detection. *The 40th Annual AAAI Conference on Artificial Intelligence*. (CCF-A; Oral)  
[[网页]](https://arxiv.org/abs/2511.06826) [[预览]](https://arxiv.org/pdf/2511.06826) 

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">BIBM 2025</div><img src='images/EK_ICL.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- `Puzhen Su`, Yongzhu Miao, Haoran Yin, Jintao Tang*, Shasha Li*, Ting Wang*. Explicit Knowledge-Guided In-Context Learning for Early Detection of Alzheimer's Disease. *The 19th International Conference on Bioinformatics & Biomedicine*. (CCF-B)  
[[网页]](https://arxiv.org/abs/2511.06215) [[预览]](https://arxiv.org/pdf/2511.06215)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024</div><img src='images/SPZ.png' alt="sym" width="100%"></div></div><img src='images/outstanding paper ward.jpg' alt="sym" width="50%"></div></div>
<div class='paper-box-text' markdown="1">

- Fangfang Li, Cheng Huang, `Puzhen Su*`, Jie Yin. SPZ: A Semantic Perturbation-based Data Augmentation Method with Zonal-Mixing for Alzheimer’s Disease Detection. *In Proceedings of the 62nd Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)*, pages 15429–15439, Bangkok, T ailand. Association for Computational Linguistics. (CCF-A; Outstanding Paper Award)  
[[网页]](https://aclanthology.org/2024.acl-long.823/) [[预览]](https://aclanthology.org/2024.acl-long.823.pdf)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2023</div><img src='images/CL_DIL.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

-	Fangfang Li, `Puzhen Su`, Junwen Duan*, Weidong Xiao. Towards better representations for multi-label text classification with multi-granularity information. *In Findings of the Association for Computational Linguistics: EMNLP 2023*, pages 9470–9480, Singapore. Association for Computational Linguistics. (CCF-B)  
[[网页]](https://aclanthology.org/2023.findings-emnlp.635/) [[预览]](https://aclanthology.org/2023.findings-emnlp.635.pdf)


### 中文
---

- 	李芳芳, `苏朴真`, 段俊文*, 张师超*, 毛星亮. 多粒度信息关系增强的多标签文本分类. *软件学报*. 2023,34(12). (核心期刊)  
[[网页]](https://dx.doi.org/10.13328/j.cnki.jos.006802) [[预览]](https://kns.cnki.net/kcms2/article/abstract?v=9jT59j8Ji04IVC_Oy-SKEdbyGfGRY-MByfM27maog6Cr-KD3QCtLLtNhFuzWG3KoQHgR5tDdgDdLpookmP0ameJcyvEPyOf5CI7SxvjxL9_7JhXRDMbbIp-LBsOacCkJeSkV8U0hMNn9fjKAWg9zY-E9hNidd3R5P20dc2N4fNE4klmiM-DBTw==&uniplatform=NZKPT&language=CHS)  

### 专利
---
- 李芳芳, 黄程, `苏朴真`. 一种阿兹海默症检测方法、可读存储介质及计算机设备. [[网页]](https://kns.cnki.net/kcms2/article/abstract?v=9jT59j8Ji04UcUZMs1gZ7uUDh9yNVTOTaSlBXCiCz8IygqptKcpAmvFh9pP0zh03HqhPpiwSvezwaiOI2RSXkj_fyEA1e6wxe__5RgfUhnt0V5J9EmJrj7YoEnw8VUBtufwYKbCEu_9-nYPxB4W9E0bFhaH89zmO98KkakOW8SL2Lfv-NRD8_g==&uniplatform=NZKPT&language=CHS)
- 李芳芳, `苏朴真`, 黄惟, 康占英, 王青. 一种多标签文本分类方法及模型.[[网页]](https://kns.cnki.net/kcms2/article/abstract?v=9jT59j8Ji04UcUZMs1gZ7uUDh9yNVTOTaSlBXCiCz8IygqptKcpAmmGe0dY02ZVhksWCpyF5DhwWXGTKHHsjLyZUFfEgQAA57nOaBpKqdSk3q_I9p4gXU1GQsQ95Dop9r4Z8Vg2sujPg3VjcUX1iAc8R0aBxCp9AG6pZmNgU1eoQGByPcpwrBg==&uniplatform=NZKPT&language=CHS)
- 李芳芳, `苏朴真`, 邓晓衡, 张健. 基于预训练语言模型的法律文本类案检索方法及系统. [[网页]](https://kns.cnki.net/kcms2/article/abstract?v=9jT59j8Ji04UcUZMs1gZ7uUDh9yNVTOTaSlBXCiCz8IygqptKcpAmgwW3WbmEzq_KLC8ioTXL6UnSaQ-cjFU4m4lFBbX0RxFogh-VB5XXpqqFBi_7XG9oP0K60G-FRt9DMgdQmChB5v3nedmYWd1Ay72E6LkSdKzciAyO1y0BVWr8R3Fb8-EBQ==&uniplatform=NZKPT&language=CHS) 
- 李芳芳, `苏朴真`, 龙军, 陈先来, 徐雪松, 毛星亮. 网络大数据长文本多标签分类方法、系统、设备及介质. [[网页]](https://kns.cnki.net/kcms2/article/abstract?v=9jT59j8Ji04UcUZMs1gZ7uUDh9yNVTOTaSlBXCiCz8IygqptKcpAmrESQm2b16Y2l2cb6D2kOngs0gwYciItq_MtYGYmBcP8YVAVTDmEyKY0O525lLH8tMJmXoy8_WOs0WQs8OUCgpq7d--RNAmll4shtdaLXxRpZkyyrrG3CTSIxzkmL_Rf_Q==&uniplatform=NZKPT&language=CHS) 






<!-- 
<span class='anchor' id='-ryjx'></span>

# 🏅 荣誉奖项
- *2015.11* 获得 第十四届“挑战杯”全国大学生课外学术科技作品竞赛 `一等奖`  
- *2015.06* 获得 第十三届“挑战杯”四川大学生课外学术科技作品竞赛 `一等奖` [[新闻]](https://www.sc.gov.cn/10462/10778/10876/2015/7/1/10341562.shtml)  
- *2014.12* 获得 第四届全国大学生工程训练综合能力竞赛（四川赛区） `一等奖`  

<span class='anchor' id='-xshy'></span>

# 🏛️ 学术会议
- *2021.10*, 全国电磁无损检测技术研讨会 暨 中国机械工程学会无损检测分会电磁专业技术大会第十一届第四次全体会议, 陕西西安, 受邀报告
- *2019.09*, 第十九届国际应用电磁学与力学会议 (ISEM 2019), 江苏南京, 海报
- *2017.10*, 第六届中国国际管道会议 (CIPC 2017), 河北廊坊

<span class='anchor' id='-gzsx'></span>

# 💻 工作实习
- *2018.05 - 2020.02*, 重庆长江轴承股份有限公司, 重庆
- *2020.11.25 - 2020.12.02*, 湖北新冶钢有限公司, 湖北黄石
- *2017.6 - 2021.1*, 制造装备数字化国家工程研究中心, 湖北武汉 -->
