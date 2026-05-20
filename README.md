# Generative-Recommendation-Learning
✍️ A personalized yet publicly accessible repository dedicated to Generative Recommendation. This repo will be constantly updated and enriched with paper lists, technical roadmaps, and the reconstruction & implementation of relevant baselines throughout my learning journey. 

✏️ Notably, the term "Generative Recommendation" is broadly construed here: while SID-based Generative Recommendation serves as the core focus, the repo also places significant emphasis on Agentic Recommendation and other non-sequential recommendation tasks. Diffusion-based generative recommendation will be supplemented in future updates as I advance my learning in this domain. Additionally, a clear distinction is maintained between academic and industrial papers to facilitate targeted exploration.

---

- [❤️Papers](#papers)
  - [__🧀Generative Recommendation__](#genrec)
    - [Surveys](#genrec_surveys)
    - [🔥Based on SID](#genrec_sid) - 
      - [Train from Scratch (Encoder-Decoder)](#genrec_sid_ed)
      - [Align with LLMs (Decoder-only)](#genrec_sid_d)
      - [Diffusion Language Models](#genrec_sid_diff)
      - [Technology Classification](#genrec_sid_tech)
        - [Tokenization](#genrec_sid_tech_token) 
        - [CF Injection](#genrec_sid_tech_cf)
        - [Dense Fusion](#genrec_sid_tech_dense) 
        - [Reasoning](#genrec_sid_tech_reason) 
          - [Latent](#genrec_sid_tech_reason_latent)
          - [Explicit](#genrec_sid_tech_reason_explicit) 
        - [RL](#genrec_sid_tech_rl) 
        - [Personalization](#genrec_sid_tech_personal) 
      - [Cold-Start](#genrec_sid_cold)
      - [Views](#genrec_sid_views)
      - [Industrial](#genrec_sid_indus)
        - [Kuaishou](#genrec_sid_indus_kuaishou)
        - [Tencent](#genrec_sid_indus_tencent)
    - [Based on Title](#genrec_title)
    - [Rating](#genrec_rating)
    - [CTR](#genrec_ctr)
    - [Rank](#genrec_rank)
    - [Diffusion Model](#genrec_diff)
  - [__🧀Agentic Recommendation__](#agentic)
    - [Surveys](#agentic_surveys)
  - [__🧀LLM Enhanced Recommendation__](#enhanced)
    - [Surveys](#enhanced_surveys)
- [❤️‍🔥Codes_Exp](#codes)
- [📂Resources](#resources)
- [❤️Peoples_follow](#peoples)

---

<!-- 顶级标题 -->
<h1 id="papers">❤️Papers</h1>
<hr>

<!-- 中间分类标题（下面有子标题）用隐形锚点 + Markdown 二级标题 -->
<a id="genrec"></a>
## 🧀 Generative Recommendation

<!-- 叶子节点：Surveys -->
<br>

---
<h3 align="center" id="genrec_surveys">Surveys</h3>
---

<br>

<!-- 中间分类：Based on SID -->
<a id="genrec_sid"></a>
### 🔥 Based on SID

<!-- 叶子节点：Train from Scratch (Encoder-Decoder) -->
<br>

---
<h4 align="center" id="genrec_sid_ed">Train from Scratch (Encoder-Decoder)</h4>
---

<br>

<!-- 叶子节点：Align with LLMs (Decoder-only) -->
<br>

---
<h4 align="center" id="genrec_sid_d">Align with LLMs (Decoder-only)</h4>
---

<br>

<!-- 叶子节点：Diffusion Language Models -->
<br>

---
<h4 align="center" id="genrec_sid_diff">Diffusion Language Models</h4>
---

<br>

<!-- 中间分类：Technology Classification -->
<a id="genrec_sid_tech"></a>
#### Technology Classification

<!-- 叶子节点：Tokenization -->
<br>

---
<h5 align="center" id="genrec_sid_tech_token">Tokenization</h5>
---

<br>

<!-- 叶子节点：CF Injection -->
<br>

---
<h5 align="center" id="genrec_sid_tech_cf">CF Injection</h5>
---

<br>

<!-- 叶子节点：Dense Fusion -->
<br>

---
<h5 align="center" id="genrec_sid_tech_dense">Dense Fusion</h5>
---

<br>

<!-- 中间分类：Reasoning -->
<a id="genrec_sid_tech_reason"></a>
##### Reasoning

<!-- 叶子节点：Latent -->
<br>

---
<h6 align="center" id="genrec_sid_tech_reason_latent">Latent</h6>
---

<br>

<!-- 叶子节点：Explicit -->
<br>

---
<h6 align="center" id="genrec_sid_tech_reason_explicit">Explicit</h6>
---

<br>

<!-- 叶子节点：RL -->
<br>

---
<h5 align="center" id="genrec_sid_tech_rl">RL</h5>
---

<br>

<!-- 叶子节点：Personalization -->
<br>

---
<h5 align="center" id="genrec_sid_tech_personal">Personalization</h5>
---

<br>

<li>
  <p>
    <a href="https://arxiv.org/abs/2605.18771"><img src="https://img.shields.io/badge/arXiv-2605.18771-green?style=flat" alt="arXiv"></a>
    &nbsp;&nbsp;<strong>LWGR: Lagrangian-Constrained Personalized World Knowledge for Generative Recommendation</strong>
    &nbsp;
    [<a href="https://arxiv.org/pdf/2605.18771" target="_blank">paper</a>]
    [code]
  </p>
  <p>Lingyu Mu<sup>∗</sup>, Hao Deng<sup>∗</sup>, Haibo Xing, Kaican Lin, Zhitong Zhu, Yu Zhang, Xiaoyi Zeng, Zhengxiao Liu<sup>†</sup>, Zheng Lin<sup>†</sup>, Jinxin Hu</p>
  <p><i>Engineering, Chinese Academy of Sciences, Alibaba International Digital Commerce Group</i></p>
</li>

<!-- 叶子节点：Cold-Start -->
<br>

---
<h4 align="center" id="genrec_sid_cold">Cold-Start</h4>
---

<br>

<!-- 叶子节点：Views -->
<br>

---
<h4 align="center" id="genrec_sid_views">Views</h4>
---

<br>

<!-- 中间分类：Industrial -->
<a id="genrec_sid_indus"></a>
#### Industrial

<!-- 叶子节点：Kuaishou -->
<br>

---
<h5 align="center" id="genrec_sid_indus_kuaishou">Kuaishou</h5>
---

<br>

<!-- 叶子节点：Tencent -->
<br>

---
<h5 align="center" id="genrec_sid_indus_tencent">Tencent</h5>
---

<br>

<!-- 叶子节点：Based on Title -->
<br>

---
<h3 align="center" id="genrec_title">Based on Title</h3>
---

<br>

<!-- 叶子节点：Rating -->
<br>

---
<h3 align="center" id="genrec_rating">Rating</h3>
---

<br>

<!-- 叶子节点：CTR -->
<br>

---
<h3 align="center" id="genrec_ctr">CTR</h3>
---

<br>

<!-- 叶子节点：Rank -->
<br>

---
<h3 align="center" id="genrec_rank">Rank</h3>
---

<br>

<!-- 叶子节点：Diffusion Model -->
<br>

---
<h3 align="center" id="genrec_diff">Diffusion Model</h3>
---

<br>

<!-- 中间分类：Agentic Recommendation -->
<a id="agentic"></a>
## 🧀 Agentic Recommendation

<!-- 叶子节点：Surveys -->
<br>

---
<h3 align="center" id="agentic_surveys">Surveys</h3>
---

<br>

<!-- 中间分类：LLM Enhanced Recommendation -->
<a id="enhanced"></a>
## 🧀 LLM Enhanced Recommendation

<!-- 叶子节点：Surveys -->
<br>

---
<h3 align="center" id="enhanced_surveys">Surveys</h3>
---

<br>

<!-- 顶级标题：Codes_Exp -->
<h1 id="codes">❤️‍🔥 Codes_Exp</h1>
<hr>

<!-- 顶级标题：Resources -->
<h1 id="resources">📂 Resources</h1>
<hr>

- 资源1
- 资源2

<!-- 顶级标题：Peoples_follow -->
<h1 id="peoples">❤️ Peoples_follow</h1>
<hr>
