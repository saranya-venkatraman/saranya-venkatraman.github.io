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
  :root {
    --accent: #374151;
    --accent-light: #f3f4f6;
    --accent-mid: #6b7280;
    --link: #374151;
    --highlight-bg: #fefce8;
    --highlight-text: #92400e;
    --line: #e5e7eb;
  }
  html { scroll-behavior: smooth; }
  @media (prefers-reduced-motion: reduce) { html { scroll-behavior: auto; } }

  .page__content a { color: var(--link); text-decoration: none; border-bottom: 1px solid var(--line); }
  .page__content a:hover { border-bottom-color: var(--accent); }
  .page__content a:focus-visible { outline: 2px solid var(--accent); outline-offset: 2px; }

  .intro p {
    text-align: justify;
    background: var(--accent-light);
    border-left: 3px solid var(--accent-mid);
    border-radius: 0 6px 6px 0;
    padding: 16px 20px;
  }

  .page__content h2.section-title {
    color: #1f2937;
    border-bottom: 2px solid var(--line);
    padding-bottom: 6px;
    margin-top: 2.5em;
    scroll-margin-top: 80px;
    font-weight: 600;
    letter-spacing: -0.01em;
  }
  .page__content h3.subsection { color: #1f2937; margin-top: 1.5em; font-size: 1.05em; }


  .job {
    background: #fff;
    border: 1px solid var(--line);
    border-left: 3px solid var(--accent-mid);
    border-radius: 0 6px 6px 0;
    padding: 12px 16px;
    margin-bottom: 12px;
  }
  .job.current { background: var(--accent-light); }
  .job-head { display: flex; justify-content: space-between; flex-wrap: wrap; gap: 4px 16px; align-items: baseline; }
  .job-head strong { font-size: 1.05em; color: #1f2937; }
  .job-dates { color: var(--accent-mid); font-size: 0.85em; }
  .job p { margin: 6px 0 0; font-size: 0.95em; }

  .pub { display: flex; gap: 20px; align-items: center; padding: 18px 0; border-bottom: 1px solid var(--line); }
  .pub-img { flex: 0 0 34%; }
  .pub-img img { max-width: 100%; height: auto; border-radius: 6px; box-shadow: 0 1px 4px rgba(0,0,0,0.08); }
  .pub-text { flex: 1; font-size: 0.95em; line-height: 1.5; }
  .pub-text .title { font-weight: 600; font-size: 1.05em; display: block; margin-bottom: 4px; color: #1f2937; }
  .venue, .award {
    display: inline-block; font-size: 0.8em; font-weight: 600;
    padding: 1px 8px; border-radius: 10px; margin: 4px 4px 4px 0;
  }
  .venue { background: var(--accent-light); color: var(--accent); }
  .award { background: var(--highlight-bg); color: var(--highlight-text); }
  .pub-text > a {
    display: inline-block; font-size: 0.85em; font-weight: 600;
    border: 1px solid var(--accent); border-radius: 4px;
    padding: 0 6px; margin: 2px 6px 0 0;
    border-bottom: 1px solid var(--accent);
  }
  .pub-text > a:hover { background: var(--accent); color: #fff; text-decoration: none; border-bottom-color: var(--accent); }

  ul.tutorials { list-style: none; margin-left: 0; padding-left: 0; }
  ul.tutorials li { margin-bottom: 8px; }

  .image-row { display: flex; gap: 10px; flex-wrap: wrap; margin-top: 10px; }
  .image-row img { width: calc(25% - 8px); min-width: 120px; border-radius: 6px; }

  @media (max-width: 700px) {
    .pub { flex-direction: column; align-items: flex-start; }
    .pub-img { flex-basis: auto; width: 100%; }
    .intro p { text-align: left; }
  }
</style>

<div class="intro">
<p>Hello! I'm an Applied Scientist at Amazon, where I build and evaluate agentic AI systems. My current work focuses on <em>user simulation</em>: building agentic "twins" of users. I completed my PhD at Penn State University, advised by <a href="https://pike.psu.edu/dongwon/" target="_blank">Prof. Dongwon Lee</a> in the <a href="https://pike.psu.edu/index.html" target="_blank">PIKE research group</a>, and was a Visiting Scholar at New York University in <a href="https://hhexiy.github.io" target="_blank">Prof. He He</a>'s group. My PhD research focused on <em>machine-generated text detection, authorship attribution, and obfuscation</em> for Large Language Models (LLMs), and on what does or doesn't make LLM-generated text "human-like." Along the way, I was a research intern at Google, Samsung Research America, and Cadence Design Systems, building RL, NLP, and ML solutions for dialogue-based recommenders, voice assistants, and hardware design layouts. I'm broadly curious about cognitively plausible architectures for language applications, and always happy to connect.</p>
</div>



<h2 id="experience" class="section-title">Experience</h2>

<div class="job current">
  <div class="job-head"><strong>Applied Scientist, Amazon</strong><span class="job-dates">Feb 2025 - Present</span></div>
  <p>Building and evaluating agentic AI systems, with a focus on user simulation.</p>
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

<div class="pub">
  <div class="pub-img"><img src="/images/agentwin.png" alt="Overview figure for AgenTwin"></div>
  <div class="pub-text">
    <span class="title">AgenTwin: An End-to-End Framework for Building Agentic Twins of Mobile Users</span>
    Authors: <strong>Saranya Venkatraman</strong>, Thanh Tran, Shunyan Luo, Devin Chen, Yuning Wu, Kai Wei, Allie Colin, Guido Imbens, Ido Rosen, Christine Ambrose<br>
    <span class="venue">COLM 2026 Workshop on Agent Behavior</span><br>
    <a href="https://cdn.amazon.science/d9/3b/f8deb9734e34a2dd9239f335ac76/scipub-approval152134-48355376-agentwin-an-endtoend-framework-for-building-agentic-twins-of-mobile-users.pdf">[paper]</a>
  </div>
</div>

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
    <span class="venue">EMNLP 2023</span> <span class="award">Outstanding Paper Award</span><br>
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
<ul class="tutorials">
  <li><a href="https://adauchendu.github.io/Tutorials/" target="_blank">Catch Me If You GPT: Tutorial on Deepfake Texts</a> <span class="venue">NAACL 2024</span></li>
  <li><a href="https://artificial-text-detection.github.io/ATD_Tutorial.pdf" target="_blank">Tutorial on Artificial Text Detection</a> <span class="venue">INLG 2022</span></li>
</ul>

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
<p>You can <a href="/files/CV_Venkatraman_Oct_2026.pdf" target="_blank">download my CV here</a>.</p>
