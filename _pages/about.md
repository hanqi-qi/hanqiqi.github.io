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

✨ Hi everyone! I'm a PostDoc (01.2024-) at [King's college London](https://kcl.ac.uk/), NLP Group,led by [Prof. Yulan He](https://sites.google.com/view/yulanhe). I passed my PhD viva with no corrections after a great time in University of Warwick (10.2020-04.2024), advised by Prof. Yulan He and Dr. Lin Gui. I finished my M.S. at Peking University(09.2017-07.2020) and my B.E. at Beihang University(09.2013-06.2017).
                
During Ph.D., I started my Causality Journey(10.2022-02.2023) in visiting Prof. [Kun Zhang](https://www.andrew.cmu.edu/user/kunz1/) affiliated with Causal Learning and Reasoning Group@CMU. Before Ph.D., I started my NLP journey(07.2019-10.2019) in visiting Prof. [Wenjie Li](https://www4.comp.polyu.edu.hk/~cswjli/) affiliated NLP Group @PolyU Hong Kong.

<div id="research-summary" markdown="1"> 
# 🔍 Research Summary
</div>

My research interests lie in the intersection of Machine Learning and Natural Language Processing, i.e., incorporating fundamental representation learning to enhance the **interpretability** and **reliability** of different NLP models. 
- Address the intrinsic limitations in representations learnt in Transformers, I propose (i)monosemantic neurons in alignment (DPO), [DecDPO](https://arxiv.org/abs/2406.17969); (ii)discriminative features in classification, [AddTokenUni](https://proceedings.mlr.press/v180/yan22b.html), [CaliDist](https://proceedings.mlr.press/v180/yan22b.html); (iii) representation robust to position in ICL, [InfoAC](https://arxiv.org/abs/2406.17969)
- Learn disentangled representation for: (i) conditional generation by theory-guaranteed intervention, [Matte](https://neurips.cc/virtual/2023/poster/71063) (ii) extraction of aspect and associated sentiment to build self-explainable systems, [Hint](https://direct.mit.edu/coli/article/doi/10.1162/coli_a_00459/112768/Hierarchical-Interpretation-of-Neural-Text) and [Giant](https://arxiv.org/abs/2305.05331)
- Improve the performances of applications: (i) event extraction by introduce weak supervision, [WeakExtraction](https://arxiv.org/pdf/2406.18245), [KAG](https://aclanthology.org/2021.acl-long.261.pdf) (ii) LLM reasoning by self-reflection, [Mirror](https://aclanthology.org/2024.acl-long.382.pdf).

<div id="news" markdown="1"> 
# 🔥 News
</div>

<div style="width: 100%; height: 200px; overflow-y: scroll; border: 1px solid #ccc; padding: 10px;">
09.2024: Three papers (1 first-author) are accepted by EMNLP24 Main Conference. 🎉<br> 
08.2024: I go to Bangkok, Thailand🇹🇭 for ACL24. ✈️<br> 05.2024: Two papers (1 first-author) are accepted by ACL24, one in the main conference, one in findings. <br> 
04.2024: I pass the PhD viva with no correction🎓. <br> 
01.2024: I become a PostDoc👩‍🏫 at King's College London, NLP Group. <br> 
01.2024: I finish my PhD thesis (draft) on the same day of my birthday.<br> 
01.2024: My first-author paper is finally accepted by TKDE.<br> 
12.2023: I go to New Orleans🎷, US to present our Neurips paper. <br>
07.2023: I go to Hawaii🌴, US to present our ICML-workshop paper. <br> 
07.2023: My first-author paper is accepted by Neurips (my Neurips paper).<br> 
02.2023: I go back to the UK from Abu Dhabi, UAE🇦🇪, finish my Machine Learning trip in MBZUAI. <br> 
02.2023: I attend the EMNLP23 held in Abu Dhabi, to present our Computational Linguistics paper. <br> 
01.2023: One paper is accepted by EACL23🇭🇷-findings (first time as a mentor for a master's student). <br> 
12.2022: Lionel Messi leads Argentina to win the ⚽️World Cup championship. <br> 
10.2022: I start to be a funded visiting student in Machine Learning, Department at MBZUAI🏫, Abu Dhabi, UAE, advised by Prof. Kun Zhang. <br>
08.2022: I go to Eindhoven, Netherlands🇳🇱 to present our UAI paper. <br> 
05.2022: My first-author paper is accepted by UAI23 (🥳my first ML paper) <br> 
05.2021: The first time! My first-author paper is accepted by ACL21 🌟Oral A super encouragement in my early PhD career. <br> 
10.2020: I start my PhD📚 journey at University of Warwick, UK🇬🇧. <br>
</div>


🚀 I am always open to new collaborations and engaging discussions. Feel free to reach out if you are interested in working together or just want to chat!

<!--
<a href='[https://scholar.google.com/citations?user=YmWi1lgAAAAJ](https://scholar.google.com/citations?user=YmWi1lgAAAAJ)'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>
-->

<!--
<div id="educations" markdown="1"> 
# 📖 Educations
</div>
- *2020.10 - 2024.04*, Ph.D., Th University of Warwick.
- *2017.09 - 2020.07*, Master, Peking University.
- *2013.09 - 2017.06*, Bachelor, Beihang University.
-->

<div id="publications" markdown="1"> 
# 📝 Selected Publications
</div>

(* indicates equal contribution)

<!-- Filter Buttons -->
<div id="filter-container">
  <button class="filter-btn" onclick="filterPubs('all')">All</button>
  <button class="filter-btn" onclick="filterPubs('interpretability')">Interpretability</button>
  <button class="filter-btn" onclick="filterPubs('representation')">Representation</button>
  <button class="filter-btn" onclick="filterPubs('causality')">Causality</button>
  <button class="filter-btn" onclick="filterPubs('application')">Application</button>
</div>

<div class="publication-list">
  <div class="paper-box-text interpretability representation application" markdown="1">
  <b style="color:#783F04;">Encourage or Inhibit Monosemanticity? Revisit Monosemanticity from a Feature Decorrelation Perspective
  </b>
  \\
  **H. Yan**, Y. Xiang, G Chen, Y. Wang, L. Gui, Y. He\\
  **EMNLP24, main** |  [Paper](https://arxiv.org/abs/2406.17969)
  <br>
  <span style="background-color: #d4f0f0; color: #000; padding: 2px 6px; border-radius: 4px;">Interpretability</span>  <span style="background-color: #f0d4f0; color: #000; padding: 2px 6px; border-radius: 4px;">Representation</span>  
  <br>
  </div>

  <div class="paper-box-text causality application" markdown="1">
  <b style="color:#783F04;"> Weak Reward Model Transforms Generative Models into Robust Causal Event Extraction Systems
  </b>
  \\
  I. Silva, **H. Yan**, L. Gui, Y. He\\
  **EMNLP24, main** |  [Paper](https://arxiv.org/abs/2312.09390) 
  <br>
  <span style="background-color: #f0f4d4; color: #000; padding: 2px 6px; border-radius: 4px;">Causality</span> <span style="background-color: #d4d4f0; color: #000; padding: 2px 6px; border-radius: 4px;">application</span> 
  </div>

  <div class="paper-box-text interpretability" markdown="1">
  <b style="color:#783F04;"> The Mystery and Fascination of LLMs: A Comprehensive Survey on the Interpretation and Analysis of Emergent Abilities
  </b>
  \\
  Y. Zhou, J. Li, Y.Xiang, **H.Yan**, L. Gui, Y. He\\
  **EMNLP24, main** |  [Paper](https://arxiv.org/abs/2311.00237) <br>
  <span style="background-color: #d4f0f0; color: #000; padding: 2px 6px; border-radius: 4px;">Interpretability</span>  
  <br>
  </div>

  <div class="paper-box-text application" markdown="1">
  <b style="color:#783F04;"> Mirror: A Multiple-perspective Self-Reflection Method for Knowledge-rich Reasoning
  </b>
  \\
   <strong>H. Yan</strong>, Q. Zhu, X. Wang, L. Gui, Y. He\\
  **ACL24, main** |  [Paper](https://arxiv.org/abs/2311.00237) <br>
  <span style="background-color: #d4d4f0; color: #000; padding: 2px 6px; border-radius: 4px;">application</span>  
  <br>
  </div>

  <div class="paper-box-text representation" markdown="1">
  <b style="color:#783F04;">Addressing Order Sensitivity of In-Context Demonstration Examples in Causal Language Models. 
  </b>
  \\
  Y. Xiang, **H. Yan**, L. Gui, Y. He\\
  **ACL24, findings** |  [Paper](https://arxiv.org/pdf/2402.15637) <br>
  <span style="background-color: #f0d4f0; color: #000; padding: 2px 6px; border-radius: 4px;">Representation</span> 
  <br>
  </div>
  

  <div class='paper-box-text representation causality application' markdown="1">
  <b style="color:#783F04;"> Counterfactual Generation with Identifiability Guarantee
  </b>
  \\
  <strong>H. Yan</strong>, L. Kong, L. Gui, Y. Chi, Eric. Xing, Y. He, K. Zhang\\
  **Neurips23, main** |  [Paper](https://neurips.cc/virtual/2023/poster/71063)<br>
  <span style="background-color: #f0f4d4; color: #000; padding: 2px 6px; border-radius: 4px;">Causality</span> <span style="background-color: #f0d4f0; color: #000; padding: 2px 6px; border-radius: 4px;">Representation</span>  <span style="background-color: #d4d4f0; color: #000; padding: 2px 6px; border-radius: 4px;">application</span> 
  </div>

  <div class='paper-box-text interpretability application' markdown="1">
  <b style="color:#783F04;"> Explainable Recommender with Geometric Information Bottleneck
  </b>
  \\
  <strong>H. Yan</strong>, L. Gui, M. Wang, K. Zhang and Y. He\\
  **TKDE** |  [Paper](https://arxiv.org/abs/2305.05331) <br>
    <span style="background-color: #d4f0f0; color: #000; padding: 2px 6px; border-radius: 4px;">Interpretability</span>  <span style="background-color: #d4d4f0; color: #000; padding: 2px 6px; border-radius: 4px;">application</span> 
  </div>

  <div class='paper-box-text interpretability application' markdown="1">
  <b style="color:#783F04;"> Hierarchical Interpretation of Neural Text Classification
  </b>
  \\
  <strong>H. Yan</strong>, L. Gui and Y. He \\
  **Computational Linguistics, Present at EMNLP23** |  [Paper](https://direct.mit.edu/coli/article/doi/10.1162/coli_a_00459/112768/Hierarchical-Interpretation-of-Neural-Text) <br>
  <span style="background-color: #d4f0f0; color: #000; padding: 2px 6px; border-radius: 4px;">Interpretability</span>   <span style="background-color: #d4d4f0; color: #000; padding: 2px 6px; border-radius: 4px;">application</span> 
  </div>

  <div class='paper-box-text representation' markdown="1">
  <b style="color:#783F04;"> Addressing Token Uniformity in Transformers via Singular Value Transformation
  </b>
  \\
  <strong>H. Yan</strong>, L. Gui, W. Li and Y. He \\
  **UAI22, spotlight** |  [Paper](https://proceedings.mlr.press/v180/yan22b.html)<br>
  <span style="background-color: #f0d4f0; color: #000; padding: 2px 6px; border-radius: 4px;">Representation</span>  
  </div>

  <div class='paper-box-text representation' markdown="1">
  <b style="color:#783F04;"> Distinguishability Calibration to In-Context Learning
  </b>
  \\
  H. Li, <strong>H. Yan</strong>, L. Gui, W. Li and Y. He \\
  **EACL23, findings** |  [Paper](https://arxiv.org/abs/2302.06198)<br>
   <span style="background-color: #f0d4f0; color: #000; padding: 2px 6px; border-radius: 4px;">Representation</span>  
  </div>
  
  <div class='paper-box-text causality application' markdown="1">
  <b style="color:#783F04;"> A Knowledge-Aware Graph Model for Emotion Cause Extraction
  </b>
  \\
  <strong>H. Yan</strong>, L. Gui and Y. He \\
  **ACL21, Oral** |  [Paper](https://aclanthology.org/2021.acl-long.261.pdf)<br>
  <span style="background-color: #f0f4d4; color: #000; padding: 2px 6px; border-radius: 4px;">Causality</span> <span style="background-color: #d4d4f0; color: #000; padding: 2px 6px; border-radius: 4px;">application</span> 
  </div>
</div>



<div id="honors" markdown="1"> 
# 👩‍🏫  Professional Actitives
  - Event Organiser: Co-Chair of AACL-IJCNLP (Student Research Workshop) 2022 
  - Reviewers:
    - AACL23'24
    - NAACL24'
    - EACL23'
    - EMNLP22'23'24'
    - ACL23'24'
    - UAI23'
    - AISTATS24'25'
    - NEURIPS24'
    - ICLR25'
    - NeuroComputing
    - TOIS
</div>

<div id="invited talks" markdown="1">
# 💬 Invited Talks
- <strong>Fudan University, NLP Group</strong>, 07/2024. Representation Learning and Mechanistic Interpretability
- <strong>UC San Diego, NLP Group</strong>, 02/2024. Robust and Interpretable NLP via representation learning and Path Ahead
- <strong>Yale University, NLP Group</strong> 01/2024. Robust and Interpretable NLP via representation learning and Path Ahead
- <strong>Turing AI Fellowship Event</strong>, London, 03/2023, Distinguishability Calibration to In-Context Learning 
- <strong>UKRI Fellows Workshop</strong>, University of Edinburgh, 04/2022. Interpreting Long Documents and Recommendation Systems via Latent Variable Models
</div>

<div id="Blogs" markdown="1">
# 📝 (Memo)
<a href="https://profiles.ucl.ac.uk/92965-jialin-yu"> Machine Unlearning via CausalLens and in NLP tasks</a> <br>
<a href="https://github.com/hanqi-qi/Large_language_modeling/blob/main/Reading_Material.md">Reading List For Large Language Model</a>
                <br>
                <a href="https://zhuanlan.zhihu.com/p/652269984">Induction Head_ contribute to In-context Learning</a>
                <br>
                <a href="https://github.com/hanqi-qi/NLPReadingGroup/blob/main/CausalInference/CausalInference_Intro_hanqi.pdf">Causality101</a>
                <br>
                <a href="https://github.com/hanqi-qi/NLPReadingGroup/blob/main/CausalInference/CausalInference_RS_hanqi.pdf">Debised Recommendation with Causality</a>
                <br>
                <a href="https://zhuanlan.zhihu.com/p/665841340">Identifiability101 in Causality</a>
</div>

<!-- JavaScript for Filtering -->
<script>
function filterPubs(category) {
  var papers = document.getElementsByClassName('paper-box-text');
  if (category == 'all') category = '';
  
  // Loop through all publications
  for (var i = 0; i < papers.length; i++) {
    if (papers[i].className.indexOf(category) > -1) {
      papers[i].style.display = "block"; // Show if matches category
    } else {
      papers[i].style.display = "none";  // Hide if not
    }
  }
}
</script>

<!-- Basic Styling for Buttons and Papers -->
<style>
  .filter-btn {
    background-color: #ddd;
    border: none;
    padding: 8px 16px;
    margin-right: 5px;
    cursor: pointer;
    border-radius: 5px;
  }

  .filter-btn:hover {
    background-color: #ccc;
  }

  .publication-list {
    margin-top: 20px;
  }

  .paper-box-text {
    margin-bottom: 5px;
    padding: 5px;
    border: 0px solid #ccc;
    border-radius: 0px;
    display: block;
}

</style>
