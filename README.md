# Generative-Recommendation-Learning

✍️ A personalized yet publicly accessible repository dedicated to Generative Recommendation. This repo will be constantly updated and enriched with paper lists, technical roadmaps, and the reconstruction & implementation of relevant baselines throughout my learning journey. 

✏️ Notably, the term "Generative Recommendation" is broadly construed here: while SID-based Generative Recommendation serves as the core focus, the repo also places significant emphasis on Agentic Recommendation and other non-sequential recommendation tasks. Diffusion-based generative recommendation will be supplemented in future updates as I advance my learning in this domain. Additionally, a clear distinction is maintained between academic and industrial papers to facilitate targeted exploration.

---

- [❤️Papers](#papers)
  - [__🧀Generative Recommendation__](#genrec)
    - [Surveys](#genrec_surveys)
    - [🔥Based on SID](#genrec_sid)
      - [Train from Scratch (Encoder-Decoder)](#genrec_sid_ed)
      - [Align with LLMs (Decoder-only)](#genrec_sid_d)
      - [MultiModal](#genrec_sid_mm)
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
      - [Accelerated Inference](#genrec_sid_accelerated)
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
    - [Conversational Rec](#genrec_conv_rec)
  - [__🧀Agentic Recommendation__](#agentic)
    - [Surveys](#agentic_surveys)
  - [__🧀LLM Enhanced Recommendation__](#enhanced)
    - [Surveys](#enhanced_surveys)
  - [__🧭Generative POI Recommendation__](#genPOIrec)
    - [LLM-based](#genPOIrec_llm)
    - [Agentic](#genPOIrec_agnetic)
- [❤️‍🔥Codes_Exp](#codes)
- [📂Resources](#resources)
- [❤️Peoples_follow](#peoples)

---

<h1 align="center" id="papers">❤️ Papers</h1>

<a id="genrec"></a>
<h2 align="center">🧀 Generative Recommendation</h2>

<a id="genrec_surveys"></a>
<h3 align="center">📋 Surveys</h3>

---

<a id="genrec_sid"></a>
<h3 align="center">🔥 Based on SID</h3>

<a id="genrec_sid_ed"></a>
<h4 align="center">Train from Scratch (Encoder-Decoder)</h4>

---

<a id="genrec_sid_d"></a>
<h4 align="center">Align with LLMs (Decoder-only)</h4>

---

<a id="genrec_sid_mm"></a>
<h4 align="center">MultiModal<br></h4>

<ul>
<li>
  <p>
    <a href="https://arxiv.org/abs/2605.18920"><img src="https://img.shields.io/badge/ICML2026-FFB300?style=flat" alt="ICML2026"></a>
    &nbsp;
    <img src="https://img.shields.io/badge/TIGER-pink?style=flat" alt="TIGER">
    &nbsp;&nbsp;<strong>SynGR: Unleashing the Potential of Cross-Modal Synergy for Generative Recommendation</strong>
    &nbsp;
    [<a href="https://arxiv.org/pdf/2605.18920v1" target="_blank">paper</a>]
    [<a href="https://github.com/gxingyu/SynGR" target="_blank">code</a>]
  </p>
  <p>
    Wei Chen<sup>1∗</sup>, Xingyu Guo<sup>1∗</sup>, Shuang Li<sup>1†</sup>, Fuwei Zhang<sup>1</sup>, Meng Yuan<sup>1</sup>, Jing Fan<sup>1</sup>, 
    Zhao Zhang<sup>2</sup>, Deqing Wang<sup>2</sup>, Fuzhen Zhuang<sup>1†</sup>
  </p>
  <p>
    <i>
      <sup>1</sup>School of Artificial Intelligence, Beihang University, Beijing, China; 
      <sup>2</sup>School of Computer Science and Engineering, Beihang University, Beijing, China
    </i>
  </p>
</li>
</ul>

---

<a id="genrec_sid_diff"></a>
<h4 align="center">Diffusion Language Models</h4>

---

<a id="genrec_sid_tech"></a>
<h4 align="center">Technology Classification</h4>

<a id="genrec_sid_tech_token"></a>
<h5 align="center">🔹 Tokenization<br></h5>

<ul>
<li>
  <p>
    <a href="https://arxiv.org/abs/2605.25330"><img src="https://img.shields.io/badge/arXiv-2605.25330-green?style=flat" alt="arXiv"></a>
    &nbsp;
    <img src="https://img.shields.io/badge/TIGER-pink?style=flat" alt="TIGER">
    &nbsp;&nbsp;<strong>How Reliable Are Semantic-ID Tokenizer Comparisons in Generative Recommendation?</strong>
    &nbsp;
    [<a href="https://arxiv.org/pdf/2605.25330" target="_blank">paper</a>]
    [code]
  </p>
  <p>
    Qian Zhang<sup>1</sup>, Lech Szymanski<sup>1</sup>, Haibo Zhang<sup>2</sup>, Jeremiah D. Deng<sup>1</sup>
  </p>
  <p>
    <i>
      <sup>1</sup>School of Computing, University of Otago, Dunedin, New Zealand;
      <sup>2</sup>University of New South Wales, Sydney, Australia
    </i>
  </p>
  <p>
    <i>📌 Collision-aware fair evaluation metrics and collision handling.</i>
  </p>
  <p>
    <i>💬 Comment: Offers limited evidence support and modest insights for representation quantification.</i>
  </p>
</li>
</ul>

---

<a id="genrec_sid_tech_cf"></a>
<h5 align="center">🔹 CF Injection</h5>

---

<a id="genrec_sid_tech_dense"></a>
<h5 align="center">🔹 Dense Fusion</h5>

---

<a id="genrec_sid_tech_reason"></a>
<h5 align="center">🧠 Reasoning</h5>

<a id="genrec_sid_tech_reason_latent"></a>
<h6 align="center">◈ Latent</h6>

---

<a id="genrec_sid_tech_reason_explicit"></a>
<h6 align="center">◈ Explicit</h6>

<ul>
<li>
  <p>
    <a href="https://arxiv.org/abs/2605.17648v1"><img src="https://img.shields.io/badge/arXiv-2605.17648-green?style=flat" alt="arXiv"></a>
    &nbsp;
    <img src="https://img.shields.io/badge/SIDReasoner-pink?style=flat" alt="SIDReasoner">
    &nbsp;&nbsp;<strong>SAPO: Step-Aligned Policy Optimization for Reasoning-Based Generative Recommendation</strong>
    &nbsp;
    [<a href="https://arxiv.org/pdf/2605.17648v1" target="_blank">paper</a>]
    [<a href="https://github.com/zhengzaiyi/SAPO" target="_blank">code</a>]
  </p>
  <p>
    Zaiyi Zheng<sup>1</sup>, Guanghui Min<sup>1</sup>, Yaochen Zhu<sup>1</sup>, Liang Wu<sup>2</sup>, Liangjie Hong<sup>2</sup>, Chen Chen<sup>1</sup>, Jundong Li<sup>1</sup>
  </p>
  <p>
    <i>
      <sup>1</sup>University of Virginia, USA;
      <sup>2</sup>Nokia, USA
    </i>
  </p>
</li>
<li>
  <p>
    <a href="https://arxiv.org/abs/2605.11553v1"><img src="https://img.shields.io/badge/arXiv-2605.11553-green?style=flat" alt="arXiv"></a>
    &nbsp;
    <img src="https://img.shields.io/badge/Agent-pink?style=flat" alt="Agent">
    &nbsp;&nbsp;<strong>TwiSTAR: Think Fast, Think Slow, Then Act, Generative Recommendation with Adaptive Reasoning</strong>
    &nbsp;
    [<a href="https://arxiv.org/pdf/2605.11553v1" target="_blank">paper</a>]
    [code]
  </p>
  <p>
    Shiteng Cao, Kaian Jiang, Yunlong Gong, Zhiheng Li
  </p>
  <p>
    <i>
      Shenzhen International Graduate School, Tsinghua University
    </i>
  </p>
</li>
</ul>

---

<a id="genrec_sid_tech_rl"></a>
<h5 align="center">🔹 RL</h5>

---

<a id="genrec_sid_tech_personal"></a>
<h5 align="center">🔹 Personalization<br></h5>

<ul>
<li>
  <p>
    <a href="https://arxiv.org/abs/2605.18771"><img src="https://img.shields.io/badge/arXiv-2605.18771-green?style=flat" alt="arXiv"></a>
    &nbsp;
    <img src="https://img.shields.io/badge/TIGER-pink?style=flat" alt="TIGER">
    &nbsp;&nbsp;<strong>LWGR: Lagrangian-Constrained Personalized World Knowledge for Generative Recommendation</strong>
    &nbsp;
    [<a href="https://arxiv.org/pdf/2605.18771" target="_blank">paper</a>]
    [code]
  </p>
  <p>
    Lingyu Mu<sup>1∗</sup>, Hao Deng<sup>2∗</sup>, Haibo Xing<sup>3</sup>, Kaican Lin<sup>2</sup>, Zhitong Zhu<sup>1</sup>, Yu Zhang<sup>2</sup>, Xiaoyi Zeng<sup>3</sup>, Zhengxiao Liu<sup>1†</sup>, Zheng Lin<sup>1†</sup>, Jinxin Hu<sup>2</sup>
  </p>
  <p>
    <i>
      <sup>1</sup>Institute of Information Engineering, Chinese Academy of Sciences, Beijing, China;
      <sup>2</sup>Alibaba International Digital Commerce Group, Beijing, China;
      <sup>3</sup>Alibaba International Digital Commerce Group, Hangzhou, China
    </i>
  </p>
</li>
</ul>

---

<a id="genrec_sid_accelerated"></a>
<h4 align="center">Accelerated Inference</h4>

---

<a id="genrec_sid_cold"></a>
<h4 align="center">Cold-Start</h4>

---

<a id="genrec_sid_views"></a>
<h4 align="center">Views</h4>

---

<a id="genrec_sid_indus"></a>
<h4 align="center">Industrial</h4>

<a id="genrec_sid_indus_kuaishou"></a>
<h5 align="center">▪️ Kuaishou</h5>

---

<a id="genrec_sid_indus_tencent"></a>
<h5 align="center">▪️ Tencent</h5>

---

<a id="genrec_title"></a>
<h3 align="center">Based on Title</h3>

---

<a id="genrec_rating"></a>
<h3 align="center">⭐ Rating</h3>

---

<a id="genrec_ctr"></a>
<h3 align="center">📊 CTR</h3>

---

<a id="genrec_rank"></a>
<h3 align="center">🏆 Rank</h3>

---

<a id="genrec_diff"></a>
<h3 align="center">🌌 Diffusion Model</h3>

---

<a id="genrec_conv_rec"></a>
<h3 align="center">💬 Conversational Rec<br></h3>

<ul>
<li>
  <p>
    <a href="https://arxiv.org/abs/2605.21987"><img src="https://img.shields.io/badge/arXiv-2605.21987-green?style=flat" alt="arXiv"></a>
    &nbsp;
    <strong>Generative Conversational Recommender System</strong>
    &nbsp;
    [<a href="https://arxiv.org/pdf/2605.21987" target="_blank">paper</a>]
    [code]
  </p>
  <p>
    Sixiao Zhang<sup>1</sup>, Mingrui Liu<sup>1</sup>, Cheng Long<sup>1∗</sup>
  </p>
  <p>
    <i>
      <sup>1</sup>College of Computing and Data Science, Nanyang Technological University, Singapore
    </i>
  </p>
</li>
</ul>

---

<a id="agentic"></a>
<h2 align="center">🧀 Agentic Recommendation</h2>

<a id="agentic_surveys"></a>
<h3 align="center">📋 Surveys</h3>

---

<a id="enhanced"></a>
<h2 align="center">🧀 LLM Enhanced Recommendation</h2>

<a id="enhanced_surveys"></a>
<h3 align="center">📋 Surveys</h3>

---

<a id="genPOIrec"></a>
<h2 align="center">🧭 Generative POI Recommendation</h2>

<a id="genPOIrec_llm"></a>
<h3 align="center">🤖 LLM-based</h3>

---

<a id="genPOIrec_agnetic"></a>
<h3 align="center">🕵️ Agentic</h3>

---

<h1 align="center" id="codes">❤️‍🔥 Codes_Exp</h1>

---

<h1 align="center" id="resources">📂 Resources</h1>

- 资源1
- 资源2

---

<h1 align="center" id="peoples">❤️ Peoples_follow</h1>
