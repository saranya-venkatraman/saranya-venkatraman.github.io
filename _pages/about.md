---
permalink: /
author_profile: true
redirect_from:
  - /about/
  - /about.html
  - /research/
  - /misc/
---
<style>
  html { scroll-behavior: smooth; }
  @media (prefers-reduced-motion: reduce) { html { scroll-behavior: auto; } }
  .page__content h2.section-title {
    color: #5F9EA0;
    border-bottom: 2px solid #5F9EA0;
    padding-bottom: 6px;
    margin-top: 2.5em;
    scroll-margin-top: 80px;
  }
  .page__content h3.subsection { color: #555; margin-top: 1.5em; font-size: 1.05em; }
  .page__content a { color: #1976d2; text-decoration: none; }
  .page__content a:hover { text-decoration: underline; }
  .intro p { text-align: justify; }

  .news-item { margin-bottom: 14px; border-left: 3px solid #5F9EA0; padding-left: 10px; }
  .news-item p { margin: 0; font-size: 0.95em; }
  details.more-news summary { cursor: pointer; color: #5F9EA0; margin: 10px 0; font-weight: bold; }

  .pub { display: flex; gap: 20px; align-items: center; padding: 16px 0; border-bottom: 1px solid #e5e5e5; }
  .pub:last-child { border-bottom: none; }
  .pub-img { flex: 0 0 34%; }
  .pub-img img { max-width: 100%; height: auto; border-radius: 6px; box-shadow: 0 1px 4px rgba(0,0,0,0.2); }
  .pub-text { flex: 1; font-size: 0.95em; line-height: 1.5; }
  .pub-text .title { font-weight: bold; font-size: 1.05em; display: block; margin-bottom: 4px; }
  .pub-text .venue { font-style: italic; }
  .pub-text a { margin-right: 8px; font-weight: bold; }

  .job { padding: 12px 0; border-bottom: 1px solid #e5e5e5; }
  .job:last-child { border-bottom: none; }
  .job-head { display: flex; justify-content: space-between; flex-wrap: wrap; gap: 4px 16px; }
  .job-head strong { font-size: 1.05em; }
  .job-dates { color: #757575; font-size: 0.9em; }
  .job p { margin: 4px 0 0; font-size: 0.95em; }

  .image-row { display: flex; gap: 10px; flex-wrap: wrap; margin-top: 10px; }
  .image-row img { width: calc(25% - 8px); min-width: 120px; border-radius: 6px; }

  @media (max-width: 700px) {
    .pub { flex-direction: column; align-items: flex-start; }
    .pub-img { flex-basis: auto; width: 100%; }
  }
</style>

<div class="intro">
<p>Hello! I'm an Applied Scientist at Amazon, where I build and evaluate agentic AI systems. My current work focuses on <em>user simulation</em>: building agentic "twins" of real users so that AI agents can be tested and improved before they reach customers.</p>

<p>I completed my PhD at Penn State University, advised by <a href="https://pike.psu.edu/dongwon/" target="_blank">Prof. Dongwon Lee</a> in the <a href="https://pike.psu.edu/index.html" target="_blank">PIKE research group</a>, and was a Visiting Scholar at New York University in <a href="https://hhexiy.github.io" target="_blank">Prof. He He</a>'s group. My PhD research focused on <em>machine-generated text detection, authorship attribution, and obfuscation</em> for Large Language Models (LLMs), and on what does or doesn't make LLM-generated text "human-like."</p>

<p>Along the way, I was a research intern at Google, Samsung Research America, and Cadence Design Systems, building RL, NLP, and ML solutions for dialogue-based recommenders, voice assistants, and hardware design layouts.</p>

<p>I'm always happy to connect with people working on agentic AI, LLM evaluation, user modeling, or human-AI interaction.</p>
</div>

<h2 id="news" class="section-title">News</h2>

<div class="news-item"><p><b>Oct 2026</b> - Presenting <em>AgenTwin: An End-to-End Framework for Building Agentic Twins of Mobile Users</em> at the COLM 2026 Workshop on Agent Behavior (Oct 9)</p></div>
<div class="news-item"><p><b>Feb 2025</b> - Joined Amazon as an Applied Scientist</p></div>
<div class="news-item"><p><b>Jan 2025</b> - <a href="https://arxiv.org/abs/2406.12665" target="_blank">CollabStory: Multi-LLM Collaborative Story Generation and Authorship Analysis</a> accepted to <em>NAACL Findings 2025</em></p></div>
<div class="news-item"><p><b>Dec 2024</b> - Completed my PhD at Penn State University</p></div>

<details class="more-news">
<summary>Earlier news</summary>
<div class="news-item"><p><b>Jun 2024</b> - New preprint titled <a href="https://arxiv.org/abs/2406.12665" target="_blank">CollabStory: Multi-LLM Collaborative Story Generation and Authorship Analysis</a> is available on arXiv</p></div>
<div class="news-item"><p><b>May 2024</b> - Paper on paraphrased text authorship titled <a href="https://arxiv.org/abs/2311.08374" target="_blank">A Ship of Theseus: Curious Cases of Paraphrasing in LLM-Generated Texts</a> accepted to <em>ACL 2024</em></p></div>
<div class="news-item"><p><b>Apr 2024</b> - Attended the Women in Cybersecurity Conference <a href="https://www.wicys.org/events/wicys-2024/" target="_blank">WiCyS</a> in Nashville, TN</p></div>
<div class="news-item"><p><b>Mar 2024</b> - Won the Graduate Student Award for Excellence in Teaching Support (College of IST, Penn State) 2023-2024 for the course <em>"Socially Responsible Artificial Intelligence"</em></p></div>
<div class="news-item"><p><b>Mar 2024</b> - Paper on using statistical psycholinguistic features to detect Deepfake Texts, <a href="https://browse.arxiv.org/abs/2310.06202" target="_blank">GPT-who: An Information Density-based Machine-Generated Text Detector</a>, accepted to <em>NAACL Findings 2024</em></p></div>
<div class="news-item"><p><b>Mar 2024</b> - Paper titled <a href="https://tngoon.github.io/docs/pubs/Ngoon_etal_2024_CHI.pdf" target="_blank">ClassInSight: Designing Conversation Support Tools to Visualize Classroom Discussion for Personalized Teacher Professional Development</a> accepted to <em>CHI 2024</em></p></div>
<div class="news-item"><p><b>Feb 2024</b> - Paper on authorship obfuscation using syntactic stylometry titled <a href="https://ojs.aaai.org/index.php/AAAI/article/view/29901" target="_blank">ALISON: Fast and Effective Stylometric Authorship Obfuscation</a> at <em>AAAI 2024</em></p></div>
<div class="news-item"><p><b>Dec 2023</b> - Outstanding Paper Award for <a href="https://aclanthology.org/2023.emnlp-main.848/" target="_blank">The Sentiment Problem: A Critical Survey towards Deconstructing Sentiment Analysis</a> at <em>EMNLP 2023</em></p></div>
<div class="news-item"><p><b>Nov 2023</b> - New preprint titled <a href="https://arxiv.org/abs/2311.08374" target="_blank">A Ship of Theseus: Curious Cases of Paraphrasing in LLM-Generated Texts</a> is available on arXiv</p></div>
<div class="news-item"><p><b>Oct 2023</b> - Tutorial titled <a href="https://adauchendu.github.io/Tutorials/" target="_blank">Catch Me If You GPT: Tutorial on Deepfake Texts</a> accepted to <a href="https://2024.naacl.org/program/tutorials/" target="_blank"><em>NAACL 2024</em></a></p></div>
<div class="news-item"><p><b>May 2023</b> - Paper on evaluation of decoding algorithms titled <a href="https://aclanthology.org/2023.findings-eacl.70/" target="_blank">How do decoding algorithms distribute information in dialogue responses?</a> at <em>EACL Findings 2023</em></p></div>
</details>

<h2 id="experience" class="section-title">Experience</h2>

<div class="job">
  <div class="job-head"><strong>Applied Scientist, Amazon</strong><span class="job-dates">Feb 2025 - Present</span></div>
  <p>Building and evaluating agentic AI systems, with a focus on user simulation. Work includes AgenTwin, an end-to-end framework for building agentic twins of mobile shoppers (COLM 2026 Workshop on Agent Behavior).</p>
</div>
<div class="job">
  <div class="job-head"><strong>Research Intern, Google (Google Assistant)</strong><span class="job-dates">May - Aug 2020</span></div>
  <p>Built a recommender dialogue agent using hierarchical Soft Actor-Critic for a hybrid action space, learning user preferences through conversation and suggesting marketplace items. Ran ablations on agent design and simulated data using TF-Agents and Google Vizier.</p>
</div>
<div class="job">
  <div class="job-head"><strong>Research Intern, Samsung Research America</strong><span class="job-dates">May - Aug 2018</span></div>
  <p>Built an NLU intent-to-action service for Bixby using semantic similarity and word embeddings. Deployed it as a REST API and integrated it end-to-end with mobile devices.</p>
</div>
<div class="job">
  <div class="job-head"><strong>Machine Learning Intern, Cadence Design Systems</strong><span class="job-dates">May - Aug 2017</span></div>
  <p>Built ML pipelines for proprietary chip layout images and a hierarchical clustering prototype for assisted labeling, reaching 75% accuracy across four abstraction levels.</p>
</div>

<h2 id="research" class="section-title">Research</h2>

<h3 class="subsection">At Amazon</h3>

<div class="pub">
  <div class="pub-img"><img src="/images/agentwin.png" alt="Overview figure for AgenTwin"></div>
  <div class="pub-text">
    <span class="title">AgenTwin: An End-to-End Framework for Building Agentic Twins of Mobile Users</span>
    Authors: <strong>Saranya Venkatraman</strong>, Thanh Tran, Shunyan Luo, Devin Chen, Yuning Wu, Kai Wei, Allie Colin, Guido Imbens, Ido Rosen, Christine Ambrose<br>
    <span class="venue">COLM 2026 Workshop on Agent Behavior</span><br>
    <a href="https://cdn.amazon.science/d9/3b/f8deb9734e34a2dd9239f335ac76/scipub-approval152134-48355376-agentwin-an-endtoend-framework-for-building-agentic-twins-of-mobile-users.pdf">[paper]</a>
  </div>
</div>

<h3 class="subsection">PhD research</h3>

<div class="pub">
  <div class="pub-img"><img src="/images/collabstory.png" alt="Overview figure for CollabStory"></div>
  <div class="pub-text">
    <span class="title">CollabStory: Multi-LLM Collaborative Story Generation and Authorship Analysis</span>
    Authors: <strong>Saranya Venkatraman</strong>, Nafis Irtiza Tripto, Dongwon Lee<br>
    <span class="venue">NAACL Findings 2025</span><br>
    <a href="https://arxiv.org/abs/2406.12665">[paper]</a><a href="https://github.com/saranya-venkatraman/multi_llm_story_writing">[code]</a>
  </div>
</div>

<div class="pub">
  <div class="pub-img"><img src="/images/gptwho.png" alt="Overview figure for GPT-who"></div>
  <div class="pub-text">
    <span class="title">GPT-who: An Information Density-based Machine-Generated Text Detector</span>
    Authors: <strong>Saranya Venkatraman</strong>, Adaku Uchendu, Dongwon Lee<br>
    <span class="venue">NAACL Findings 2024</span><br>
    <a href="https://arxiv.org/pdf/2310.06202.pdf">[paper]</a><a href="https://github.com/saranya-venkatraman/gpt-who">[code]</a>
  </div>
</div>

<div class="pub">
  <div class="pub-img"><img src="/images/ship.png" alt="Overview figure for A Ship of Theseus"></div>
  <div class="pub-text">
    <span class="title">A Ship of Theseus: Curious Cases of Paraphrasing in LLM-Generated Texts</span>
    Authors: Nafis Irtiza Tripto, <strong>Saranya Venkatraman</strong>, Dominik Macko, Robert Moro, Ivan Srba, Adaku Uchendu, Thai Le, Dongwon Lee<br>
    <span class="venue">ACL 2024</span><br>
    <a href="https://arxiv.org/pdf/2311.08374">[paper]</a>
  </div>
</div>

<div class="pub">
  <div class="pub-img"><img src="/images/alison.png" alt="Overview figure for ALISON"></div>
  <div class="pub-text">
    <span class="title">ALISON: Fast and Effective Stylometric Authorship Obfuscation</span>
    Authors: Eric Xing, <strong>Saranya Venkatraman</strong>, Thai Le, Dongwon Lee<br>
    <span class="venue">AAAI 2024</span><br>
    <a href="https://ojs.aaai.org/index.php/AAAI/article/view/29901">[paper]</a><a href="https://github.com/ericx003/alison">[code]</a>
  </div>
</div>

<div class="pub">
  <div class="pub-img"><img src="/images/cis.png" alt="Overview figure for ClassInSight (CHI 2024)"></div>
  <div class="pub-text">
    <span class="title">ClassInSight: Designing Conversation Support Tools to Visualize Classroom Discussion for Personalized Teacher Professional Development</span>
    Authors: Tricia J Ngoon, S Sushil, Angela Stewart, Ung-Sang Lee, <strong>Saranya Venkatraman</strong>, Neil Thawani, Prasenjit Mitra, Sherice Clarke, John Zimmerman, Amy Ogan<br>
    <span class="venue">CHI 2024</span><br>
    <a href="https://tngoon.github.io/docs/pubs/Ngoon_etal_2024_CHI.pdf">[paper]</a>
  </div>
</div>

<div class="pub">
  <div class="pub-img"><img src="/images/uid_decoding.png" alt="Overview figure for decoding algorithms paper"></div>
  <div class="pub-text">
    <span class="title">How do decoding algorithms distribute information in dialogue responses?</span>
    Authors: <strong>Saranya Venkatraman</strong>, He He, David Reitter<br>
    <span class="venue">EACL Findings 2023</span><br>
    <a href="https://aclanthology.org/2023.findings-eacl.70/">[paper]</a><a href="https://huggingface.co/datasets/saranya132/dialog_uid_gpt2">[dataset]</a>
  </div>
</div>

<div class="pub">
  <div class="pub-img"><img src="/images/sentiment.png" alt="Overview figure for The Sentiment Problem"></div>
  <div class="pub-text">
    <span class="title">The Sentiment Problem: A Critical Survey towards Deconstructing Sentiment Analysis</span>
    Authors: Pranav Narayanan Venkit<sup>*</sup>, Mukund Srinath<sup>*</sup>, Sanjana Gautam, <strong>Saranya Venkatraman</strong>, Vipul Gupta, Rebecca J Passonneau, Shomir Wilson<br>
    <span class="venue">EMNLP 2023 (Outstanding Paper Award)</span><br>
    <a href="https://aclanthology.org/2023.emnlp-main.848/">[paper]</a><a href="https://github.com/PranavNV/The-Sentiment-Problem/tree/main">[data]</a>
  </div>
</div>

<div class="pub">
  <div class="pub-img"><img src="/images/earli_cis.png" alt="Overview figure for ClassInSight (EARLI 2021)"></div>
  <div class="pub-text">
    <span class="title">ClassInSight: Automating Analysis of Classroom Dialogue to Support Teacher Noticing and Reflection</span>
    Authors: <strong>Saranya Venkatraman</strong>, Prasenjit Mitra, Sherice N. Clarke, Andrea Gomoll, Zaynab Gates, Sushil S, Tarang Tripathi, Amy Ogan<br>
    <span class="venue">EARLI 2021</span><br>
    <a href="https://saranya-venkatraman.github.io/files/BOA-2021.pdf">[paper]</a><a href="https://github.com/saranya-venkatraman/classinsight-language">[code]</a>
  </div>
</div>

<h3 class="subsection">Tutorials</h3>
<p><a href="https://adauchendu.github.io/Tutorials/" target="_blank">Catch Me If You GPT: Tutorial on Deepfake Texts</a>, NAACL 2024<br>
Tutorial on Artificial Text Detection, INLG 2022</p>

<h2 id="beyond" class="section-title">Beyond Research</h2>

<p style="text-align: justify;"><b>Support for students.</b> As a first-generation student, I know college and graduate school bring challenges that aren't always visible to others, from financial concerns to simply feeling out of place. I've also navigated advisor transitions during my PhD; James McLaughlin's post <a href="https://www.jfmclaughlin.org/blog/when-your-advisor-leaves" target="_blank">"When your advisor leaves"</a> is a useful starting point if you're in a similar situation. If you're facing any of these challenges, feel free to reach out by email. I'm happy to help.</p>

<p style="text-align: justify;"><b>Other interests.</b> In my free time, I enjoy running, biking, snowboarding, and listening to and collecting vinyl records. In another life, I was a singer trained in Indian Classical Vocals and part of an a cappella group.</p>

<div class="image-row">
  <img src="/images/running.png" alt="Running">
  <img src="/images/biking.png" alt="Biking">
  <img src="/images/snowboard1.png" alt="Snowboarding">
  <img src="/images/vinyl.png" alt="Vinyl records">
</div>

<h2 id="cv" class="section-title">CV</h2>
<p>You can <a href="/files/Resume_Saranya_Venkatraman.pdf" target="_blank">download my CV here</a>.</p>
