---
permalink: /
author_profile: false
---
<style>
  /* Hide the theme masthead and footer on this page */
  .masthead { display: none !important; }
  .page__footer { display: none !important; }
  body { padding-top: 0; padding-bottom: 0; }

  /* Centered single-column layout */
  #main { max-width: 680px; margin: 40px auto; padding: 0 20px; }
  .page { float: none; width: 100%; }

  /* Header block: photo + name + links */
  .site-header { text-align: center; margin-bottom: 2em; }
  .site-header img { width: 160px; height: 160px; border-radius: 50%; object-fit: cover; margin-bottom: 12px; }
  .site-header h1 { font-size: 1.8em; margin: 0 0 2px; font-weight: 700; color: #111; }
  .site-header .subtitle { color: #555; font-size: 1em; margin: 0 0 10px; }
  .site-header .links { font-size: 0.95em; }
  .site-header .links a { color: #1a0dab; text-decoration: none; margin: 0 6px; }
  .site-header .links a:hover { text-decoration: underline; }
  .site-header .links .sep { color: #999; margin: 0 2px; }

  /* Body text */
  .page__content { font-size: 1em; line-height: 1.7; color: #333; }
  .page__content p { margin-bottom: 1em; text-align: justify; }
  .page__content a { color: #1a0dab; text-decoration: none; border-bottom: none; }
  .page__content a:hover { text-decoration: underline; }

  /* Section headings */
  .page__content h2 { font-size: 1.3em; font-weight: 700; color: #111; border-bottom: 1px solid #ddd; padding-bottom: 4px; margin-top: 2em; margin-bottom: 0.8em; }
  .page__content h3 { font-size: 1.1em; font-weight: 600; color: #111; margin-top: 1.5em; margin-bottom: 0.5em; }

  /* Publications: plain text list */
  .pub-item { margin-bottom: 1.2em; line-height: 1.6; }
  .pub-item .pub-title { font-weight: 600; color: #111; }
  .pub-item .pub-authors { color: #333; }
  .pub-item .pub-venue { font-style: italic; color: #555; }
  .pub-item .pub-award { font-weight: 600; color: #b45309; }
  .pub-item .pub-links a { color: #1a0dab; font-size: 0.95em; margin-right: 6px; }

  /* Experience: simple list */
  .exp-item { margin-bottom: 0.8em; }
  .exp-item strong { color: #111; }
  .exp-item .exp-dates { color: #777; font-size: 0.9em; }

  /* Hobby images */
  .image-row { display: flex; gap: 10px; flex-wrap: wrap; margin-top: 10px; }
  .image-row img { width: calc(25% - 8px); min-width: 100px; border-radius: 4px; }

  @media (max-width: 600px) {
    .site-header img { width: 120px; height: 120px; }
    .page__content p { text-align: left; }
    .image-row img { width: calc(50% - 6px); }
  }
</style>

<div class="site-header">
  <img src="/images/profile.png" alt="Saranya Venkatraman">
  <h1>Saranya Venkatraman</h1>
  <p class="subtitle">Applied Scientist, Amazon</p>
  <div class="links">
    <a href="mailto:saranya132@gmail.com">Email</a> <span class="sep">/</span>
    <a href="https://scholar.google.com/citations?user=qrvxwt4AAAAJ&hl=en">Google Scholar</a> <span class="sep">/</span>
    <a href="https://github.com/saranya-venkatraman">GitHub</a> <span class="sep">/</span>
    <a href="https://www.linkedin.com/in/saranyaven">LinkedIn</a> <span class="sep">/</span>
    <a href="/files/CV_Venkatraman_Oct_2026.pdf">CV</a>
  </div>
</div>

I'm an Applied Scientist at Amazon, where I build and evaluate agentic AI systems. My current work focuses on *user simulation*: building agentic "twins" of users. I completed my PhD at Penn State University, advised by [Prof. Dongwon Lee](https://pike.psu.edu/dongwon/) in the [PIKE research group](https://pike.psu.edu/index.html), and was a Visiting Scholar at New York University in [Prof. He He](https://hhexiy.github.io)'s group. My PhD research focused on *machine-generated text detection, authorship attribution, and obfuscation* for Large Language Models (LLMs), and on what does or doesn't make LLM-generated text "human-like."

Along the way, I was a research intern at Google, Samsung Research America, and Cadence Design Systems, building RL, NLP, and ML solutions for dialogue-based recommenders, voice assistants, and hardware design layouts. I'm broadly curious about cognitively plausible architectures for language applications, and always happy to connect.

## Research

<div class="pub-item">
  <span class="pub-title">AgenTwin: An End-to-End Framework for Building Agentic Twins of Mobile Users</span><br>
  <span class="pub-authors"><strong>Saranya Venkatraman</strong>, Thanh Tran, Shunyan Luo, Devin Chen, Yuning Wu, Kai Wei, Allie Colin, Guido Imbens, Ido Rosen, Christine Ambrose</span><br>
  <span class="pub-venue">COLM 2026 Workshop on Agent Behavior</span><br>
  <span class="pub-links"><a href="https://cdn.amazon.science/d9/3b/f8deb9734e34a2dd9239f335ac76/scipub-approval152134-48355376-agentwin-an-endtoend-framework-for-building-agentic-twins-of-mobile-users.pdf">[paper]</a></span>
</div>

<div class="pub-item">
  <span class="pub-title">CollabStory: Multi-LLM Collaborative Story Generation and Authorship Analysis</span><br>
  <span class="pub-authors"><strong>Saranya Venkatraman</strong>, Nafis Irtiza Tripto, Dongwon Lee</span><br>
  <span class="pub-venue">NAACL Findings 2025</span><br>
  <span class="pub-links"><a href="https://arxiv.org/abs/2406.12665">[paper]</a> <a href="https://github.com/saranya-venkatraman/multi_llm_story_writing">[code]</a></span>
</div>

<div class="pub-item">
  <span class="pub-title">GPT-who: An Information Density-based Machine-Generated Text Detector</span><br>
  <span class="pub-authors"><strong>Saranya Venkatraman</strong>, Adaku Uchendu, Dongwon Lee</span><br>
  <span class="pub-venue">NAACL Findings 2024</span><br>
  <span class="pub-links"><a href="https://arxiv.org/pdf/2310.06202.pdf">[paper]</a> <a href="https://github.com/saranya-venkatraman/gpt-who">[code]</a></span>
</div>

<div class="pub-item">
  <span class="pub-title">A Ship of Theseus: Curious Cases of Paraphrasing in LLM-Generated Texts</span><br>
  <span class="pub-authors">Nafis Irtiza Tripto, <strong>Saranya Venkatraman</strong>, Dominik Macko, Robert Moro, Ivan Srba, Adaku Uchendu, Thai Le, Dongwon Lee</span><br>
  <span class="pub-venue">ACL 2024</span><br>
  <span class="pub-links"><a href="https://arxiv.org/pdf/2311.08374">[paper]</a></span>
</div>

<div class="pub-item">
  <span class="pub-title">ALISON: Fast and Effective Stylometric Authorship Obfuscation</span><br>
  <span class="pub-authors">Eric Xing, <strong>Saranya Venkatraman</strong>, Thai Le, Dongwon Lee</span><br>
  <span class="pub-venue">AAAI 2024</span><br>
  <span class="pub-links"><a href="https://ojs.aaai.org/index.php/AAAI/article/view/29901">[paper]</a> <a href="https://github.com/ericx003/alison">[code]</a></span>
</div>

<div class="pub-item">
  <span class="pub-title">ClassInSight: Designing Conversation Support Tools to Visualize Classroom Discussion for Personalized Teacher Professional Development</span><br>
  <span class="pub-authors">Tricia J Ngoon, S Sushil, Angela Stewart, Ung-Sang Lee, <strong>Saranya Venkatraman</strong>, Neil Thawani, Prasenjit Mitra, Sherice Clarke, John Zimmerman, Amy Ogan</span><br>
  <span class="pub-venue">CHI 2024</span><br>
  <span class="pub-links"><a href="https://tngoon.github.io/docs/pubs/Ngoon_etal_2024_CHI.pdf">[paper]</a></span>
</div>

<div class="pub-item">
  <span class="pub-title">The Sentiment Problem: A Critical Survey towards Deconstructing Sentiment Analysis</span><br>
  <span class="pub-authors">Pranav Narayanan Venkit*, Mukund Srinath*, Sanjana Gautam, <strong>Saranya Venkatraman</strong>, Vipul Gupta, Rebecca J Passonneau, Shomir Wilson</span><br>
  <span class="pub-venue">EMNLP 2023</span> · <span class="pub-award">Outstanding Paper Award</span><br>
  <span class="pub-links"><a href="https://aclanthology.org/2023.emnlp-main.848/">[paper]</a> <a href="https://github.com/PranavNV/The-Sentiment-Problem/tree/main">[data]</a></span>
</div>

<div class="pub-item">
  <span class="pub-title">How do decoding algorithms distribute information in dialogue responses?</span><br>
  <span class="pub-authors"><strong>Saranya Venkatraman</strong>, He He, David Reitter</span><br>
  <span class="pub-venue">EACL Findings 2023</span><br>
  <span class="pub-links"><a href="https://aclanthology.org/2023.findings-eacl.70/">[paper]</a> <a href="https://huggingface.co/datasets/saranya132/dialog_uid_gpt2">[dataset]</a></span>
</div>

<div class="pub-item">
  <span class="pub-title">ClassInSight: Automating Analysis of Classroom Dialogue to Support Teacher Noticing and Reflection</span><br>
  <span class="pub-authors"><strong>Saranya Venkatraman</strong>, Prasenjit Mitra, Sherice N. Clarke, Andrea Gomoll, Zaynab Gates, Sushil S, Tarang Tripathi, Amy Ogan</span><br>
  <span class="pub-venue">EARLI 2021</span><br>
  <span class="pub-links"><a href="https://saranya-venkatraman.github.io/files/BOA-2021.pdf">[paper]</a> <a href="https://github.com/saranya-venkatraman/classinsight-language">[code]</a></span>
</div>

### Tutorials

- [Catch Me If You GPT: Tutorial on Deepfake Texts](https://adauchendu.github.io/Tutorials/), *NAACL 2024*
- [Tutorial on Artificial Text Detection](https://artificial-text-detection.github.io/ATD_Tutorial.pdf), *INLG 2022*

## Experience

<div class="exp-item"><strong>Applied Scientist, Amazon</strong> <span class="exp-dates">· Feb 2025 – Present</span><br>Building and evaluating agentic AI systems, with a focus on user simulation.</div>

<div class="exp-item"><strong>Research Intern, Google (Google Assistant)</strong> <span class="exp-dates">· May – Aug 2020</span><br>Built a recommender dialogue agent using hierarchical Soft Actor-Critic for a hybrid action space.</div>

<div class="exp-item"><strong>Research Intern, Samsung Research America</strong> <span class="exp-dates">· May – Aug 2018</span><br>Built an NLU intent-to-action service for Bixby using semantic similarity and word embeddings.</div>

<div class="exp-item"><strong>Machine Learning Intern, Cadence Design Systems</strong> <span class="exp-dates">· May – Aug 2017</span><br>Built ML pipelines for proprietary chip layout images and a hierarchical clustering prototype.</div>

## Beyond Research

**Support for students.** As a first-generation student, I know college and graduate school bring challenges that aren't always visible to others, from financial concerns to simply feeling out of place. I've also navigated advisor transitions during my PhD; James McLaughlin's post ["When your advisor leaves"](https://www.jfmclaughlin.org/blog/when-your-advisor-leaves) is a useful starting point if you're in a similar situation. If you're facing any of these challenges, feel free to reach out by email. I'm happy to help.

**Other interests.** In my free time, I enjoy running, biking, snowboarding, and listening to and collecting vinyl records. In another life, I was a singer trained in Indian Classical Vocals and part of an a cappella group.

<div class="image-row">
  <img src="/images/running.png" alt="Running">
  <img src="/images/biking.png" alt="Biking">
  <img src="/images/snowboard1.png" alt="Snowboarding">
  <img src="/images/vinyl.png" alt="Vinyl records">
</div>
