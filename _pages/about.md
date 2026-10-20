---
permalink: /
author_profile: false
---
<style>
  @import url('https://fonts.googleapis.com/css2?family=Lato:wght@400;600;700&family=Playfair+Display:wght@400&display=swap');

  /* ---------- Reset the theme chrome on this page ---------- */
  .masthead, .page__footer, .page__inner-wrap > header, .page__meta { display: none !important; }
  html, body { background: #fdfdfc !important; }
  body { padding: 0 !important; margin: 0 !important; color: #1a1a1a; font-family: Lato, Arial, Tahoma, sans-serif !important; }
  #main { max-width: none !important; width: 100% !important; margin: 0 !important; padding: 0 !important; }
  .page { float: none !important; width: 100% !important; padding: 0 !important; margin: 0 !important; }
  .page__inner-wrap, .page__content { margin: 0 !important; padding: 0 !important; }
  .page__content { font-family: Lato, Arial, Tahoma, sans-serif !important; font-size: 16px !important; color: #1a1a1a; }
  .page__content a { border: none !important; }

  /* ---------- Top bar ---------- */
  .ep-topbar { background: #fff; border-bottom: 1px solid #e0dbd6; position: sticky; top: 0; z-index: 10; }
  .ep-topbar-inner { max-width: 1100px; margin: 0 auto; padding: 0 24px; height: 62px; display: flex; align-items: center; justify-content: flex-end; }
  .ep-topbar ul { list-style: none; display: flex; margin: 0 !important; padding: 0 !important; }
  .ep-topbar li { margin: 0 !important; padding: 0 !important; display: flex; align-items: center; }
  .ep-topbar li + li::before { content: ""; width: 1px; height: 16px; background: #e0dbd6; }
  .ep-topbar a { font-size: 13px; font-weight: 600; color: #1a1a1a !important; text-decoration: none !important; padding: 0 20px; }
  .ep-topbar li:last-child a { padding-right: 0; }
  .ep-topbar a:hover, .ep-topbar a.active { color: #1a3a52 !important; }

  /* ---------- Main column ---------- */
  .ep-wrap { max-width: 680px; margin: 0 auto; padding: 48px 24px 20px; box-sizing: border-box; }
  .ep-header-row { display: flex; align-items: flex-start; gap: 24px; margin-bottom: 44px; }
  .ep-photo { width: 96px !important; height: 96px !important; border-radius: 50%; object-fit: cover; flex-shrink: 0; display: block; margin: 0 !important; }
  .ep-header-text { flex: 1 1 0%; min-width: 0; }
  .page__content h1.ep-name { font-family: "Playfair Display", Georgia, serif !important; font-size: 48px !important; font-weight: 400 !important; color: #1a1a1a !important; letter-spacing: -0.02em; line-height: 1.1 !important; margin: 0 0 8px !important; padding: 0 !important; border: none !important; }
  .page__content p.ep-role { font-size: 14px !important; color: #5e5e5e !important; margin: 0 0 12px !important; line-height: 1.5 !important; }
  .page__content p.ep-role strong { font-weight: 600; color: #3d3d3d; }
  ul.ep-social { display: flex; align-items: center; list-style: none; margin: 0 !important; padding: 0 !important; }
  ul.ep-social li { margin: 0 !important; padding: 0 !important; }
  .page__content a.ep-social-link { display: inline-flex; align-items: center; justify-content: center; padding: 6px 12px 6px 0; color: #5e5e5e !important; text-decoration: none !important; }
  .page__content a.ep-social-link:hover { color: #1a3a52 !important; }
  .ep-social-link svg { width: 15px; height: 15px; vertical-align: middle; }

  hr.ep-hr { border: none !important; border-top: 1px solid #e0dbd6 !important; margin: 20px 0 24px !important; padding: 0; height: 0; background: none; }

  .ep-bio p { color: #1a1a1a !important; font-size: 16px !important; line-height: 1.7 !important; margin: 0 0 16px !important; text-align: left !important; }
  .ep-bio p:last-child { margin-bottom: 0 !important; }
  .page__content .ep-bio a, .page__content .ep-inline a { color: #1a3a52 !important; text-decoration: underline !important; text-decoration-color: rgba(26,58,82,0.35) !important; text-underline-offset: 2px; }
  .page__content .ep-bio a:hover, .page__content .ep-inline a:hover { text-decoration-color: #1a3a52 !important; }

  /* ---------- Sections ---------- */
  .ep-bio + .ep-section { margin-top: 40px; }
  .ep-section + .ep-section { margin-top: 40px; }
  .page__content h2.ep-section-label { font-family: Lato, Arial, sans-serif !important; font-size: 11px !important; font-weight: 600 !important; text-transform: uppercase; letter-spacing: 0.12em; color: #5e5e5e !important; margin: 0 0 16px !important; padding: 0 0 14px !important; border: none !important; border-bottom: 1px solid #e0dbd6 !important; line-height: 1.5 !important; }
  ul.ep-list { list-style: none !important; padding: 0 !important; margin: 0 !important; }
  ul.ep-list > li { margin: 0 0 18px !important; padding: 0 !important; list-style: none !important; }
  ul.ep-list > li::marker { content: none; }
  .page__content .ep-item-title, .page__content a.ep-item-title { color: #1a1a1a !important; text-decoration: none !important; font-weight: 600; font-size: 15px; line-height: 1.5; }
  .page__content a.ep-item-title:hover { color: #1a3a52 !important; text-decoration: underline !important; text-underline-offset: 2px; }
  .page__content p.ep-item-summary { color: #8a8a8a !important; font-size: 15px !important; line-height: 1.6 !important; margin: 4px 0 0 !important; }
  .page__content p.ep-item-summary strong { color: #5e5e5e; font-weight: 600; }
  .page__content p.ep-item-meta { color: #5e5e5e !important; font-size: 13px !important; margin: 4px 0 0 !important; line-height: 1.5 !important; }
  .page__content p.ep-item-meta a { color: #1a3a52 !important; text-decoration: none !important; font-weight: 600; }
  .page__content p.ep-item-meta a:hover { text-decoration: underline !important; }
  .ep-award { color: #9a5b13; font-weight: 600; }
  .ep-dot { color: #b5b0aa; margin: 0 4px; }

  .ep-inline p { font-size: 16px !important; line-height: 1.7 !important; margin: 0 0 16px !important; color: #1a1a1a !important; text-align: left !important; }

  .ep-image-row { display: grid; grid-template-columns: repeat(4, 1fr); gap: 10px; margin-top: 8px; }
  .ep-image-row img { width: 100%; aspect-ratio: 1 / 1; object-fit: cover; border-radius: 4px; display: block; }

  .ep-footer { color: #6b6b6b; font-size: 13px; border-top: 1px solid #e0dbd6; margin-top: 64px; padding-top: 24px; }

  @media (max-width: 600px) {
    .ep-topbar a { padding: 0 12px; }
    .ep-header-row { flex-direction: column; gap: 16px; }
    .ep-photo { width: 88px !important; height: 88px !important; }
    .page__content h1.ep-name { font-size: 40px !important; }
    .ep-image-row { grid-template-columns: repeat(2, 1fr); }
  }
</style>

<nav class="ep-topbar" aria-label="Site">
  <div class="ep-topbar-inner">
    <ul>
      <li><a href="/" class="active">Home</a></li>
      <li><a href="#pubs-label">Publications</a></li>
      <li><a href="#exp-label">Experience</a></li>
      <li><a href="/files/CV_Venkatraman_Oct_2026.pdf">CV</a></li>
    </ul>
  </div>
</nav>

<div class="ep-wrap">

  <header class="ep-header-row">
    <img class="ep-photo" src="/images/profile.png" alt="Saranya Venkatraman">
    <div class="ep-header-text">
      <h1 class="ep-name">Saranya Venkatraman</h1>
      <p class="ep-role"><strong>Applied Scientist</strong> · Amazon</p>
      <nav aria-label="Social links">
        <ul class="ep-social">
          <li><a class="ep-social-link" href="mailto:saranya132@gmail.com" aria-label="Email" title="Email"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5"><rect x="2" y="4" width="20" height="16" rx="2"></rect><path d="M2 7l10 7 10-7"></path></svg></a></li>
          <li><a class="ep-social-link" href="https://scholar.google.com/citations?user=qrvxwt4AAAAJ&amp;hl=en" aria-label="Google Scholar" title="Google Scholar" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M5.242 13.769L0 9.5 12 0l12 9.5-5.242 4.269C17.548 11.249 14.978 9.5 12 9.5c-2.977 0-5.548 1.748-6.758 4.269zM12 10a7 7 0 1 0 0 14 7 7 0 0 0 0-14z"></path></svg></a></li>
          <li><a class="ep-social-link" href="https://github.com/saranya-venkatraman" aria-label="GitHub" title="GitHub" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0 1 12 6.844a9.59 9.59 0 0 1 2.504.337c1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.202 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.02 10.02 0 0 0 22 12.017C22 6.484 17.522 2 12 2z"></path></svg></a></li>
          <li><a class="ep-social-link" href="https://www.linkedin.com/in/saranyaven" aria-label="LinkedIn" title="LinkedIn" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433a2.062 2.062 0 0 1-2.063-2.065 2.064 2.064 0 1 1 2.063 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"></path></svg></a></li>
          <li><a class="ep-social-link" href="/files/CV_Venkatraman_Oct_2026.pdf" aria-label="CV" title="CV" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linejoin="round"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"></path><path d="M14 2v6h6M8 13h8M8 17h5"></path></svg></a></li>
        </ul>
      </nav>
    </div>
  </header>

  <hr class="ep-hr">

  <div class="ep-bio">
    <p>I'm an Applied Scientist at Amazon, where I build and evaluate agentic AI systems. My current work focuses on <em>user simulation</em>: building agentic "twins" of users. I completed my PhD at Penn State University, advised by <a href="https://pike.psu.edu/dongwon/">Prof. Dongwon Lee</a> in the <a href="https://pike.psu.edu/index.html">PIKE research group</a>, and was a Visiting Scholar at New York University in <a href="https://hhexiy.github.io">Prof. He He</a>'s group. My PhD research focused on <em>machine-generated text detection, authorship attribution, and obfuscation</em> for Large Language Models (LLMs), and on what does or doesn't make LLM-generated text "human-like."</p>
    <p>Along the way, I was a research intern at Google, Samsung Research America, and Cadence Design Systems, building RL, NLP, and ML solutions for dialogue-based recommenders, voice assistants, and hardware design layouts. I'm broadly curious about cognitively plausible architectures for language applications, and always happy to connect.</p>
  </div>

  <section class="ep-section" aria-labelledby="pubs-label">
    <h2 class="ep-section-label" id="pubs-label">Publications</h2>
    <ul class="ep-list">
      <li>
        <a class="ep-item-title" href="https://cdn.amazon.science/d9/3b/f8deb9734e34a2dd9239f335ac76/scipub-approval152134-48355376-agentwin-an-endtoend-framework-for-building-agentic-twins-of-mobile-users.pdf" target="_blank" rel="noopener">AgenTwin: An End-to-End Framework for Building Agentic Twins of Mobile Users</a>
        <p class="ep-item-summary"><strong>Saranya Venkatraman</strong>, Thanh Tran, Shunyan Luo, Devin Chen, Yuning Wu, Kai Wei, Allie Colin, Guido Imbens, Ido Rosen, Christine Ambrose</p>
        <p class="ep-item-meta">COLM 2026 Workshop on Agent Behavior</p>
      </li>
      <li>
        <a class="ep-item-title" href="https://arxiv.org/abs/2406.12665" target="_blank" rel="noopener">CollabStory: Multi-LLM Collaborative Story Generation and Authorship Analysis</a>
        <p class="ep-item-summary"><strong>Saranya Venkatraman</strong>, Nafis Irtiza Tripto, Dongwon Lee</p>
        <p class="ep-item-meta">NAACL Findings 2025<span class="ep-dot">·</span><a href="https://github.com/saranya-venkatraman/multi_llm_story_writing">Code</a></p>
      </li>
      <li>
        <a class="ep-item-title" href="https://arxiv.org/pdf/2310.06202.pdf" target="_blank" rel="noopener">GPT-who: An Information Density-based Machine-Generated Text Detector</a>
        <p class="ep-item-summary"><strong>Saranya Venkatraman</strong>, Adaku Uchendu, Dongwon Lee</p>
        <p class="ep-item-meta">NAACL Findings 2024<span class="ep-dot">·</span><a href="https://github.com/saranya-venkatraman/gpt-who">Code</a></p>
      </li>
      <li>
        <a class="ep-item-title" href="https://arxiv.org/pdf/2311.08374" target="_blank" rel="noopener">A Ship of Theseus: Curious Cases of Paraphrasing in LLM-Generated Texts</a>
        <p class="ep-item-summary">Nafis Irtiza Tripto, <strong>Saranya Venkatraman</strong>, Dominik Macko, Robert Moro, Ivan Srba, Adaku Uchendu, Thai Le, Dongwon Lee</p>
        <p class="ep-item-meta">ACL 2024</p>
      </li>
      <li>
        <a class="ep-item-title" href="https://ojs.aaai.org/index.php/AAAI/article/view/29901" target="_blank" rel="noopener">ALISON: Fast and Effective Stylometric Authorship Obfuscation</a>
        <p class="ep-item-summary">Eric Xing, <strong>Saranya Venkatraman</strong>, Thai Le, Dongwon Lee</p>
        <p class="ep-item-meta">AAAI 2024<span class="ep-dot">·</span><a href="https://github.com/ericx003/alison">Code</a></p>
      </li>
      <li>
        <a class="ep-item-title" href="https://tngoon.github.io/docs/pubs/Ngoon_etal_2024_CHI.pdf" target="_blank" rel="noopener">ClassInSight: Designing Conversation Support Tools to Visualize Classroom Discussion for Personalized Teacher Professional Development</a>
        <p class="ep-item-summary">Tricia J Ngoon, S Sushil, Angela Stewart, Ung-Sang Lee, <strong>Saranya Venkatraman</strong>, Neil Thawani, Prasenjit Mitra, Sherice Clarke, John Zimmerman, Amy Ogan</p>
        <p class="ep-item-meta">CHI 2024</p>
      </li>
      <li>
        <a class="ep-item-title" href="https://aclanthology.org/2023.emnlp-main.848/" target="_blank" rel="noopener">The Sentiment Problem: A Critical Survey towards Deconstructing Sentiment Analysis</a>
        <p class="ep-item-summary">Pranav Narayanan Venkit*, Mukund Srinath*, Sanjana Gautam, <strong>Saranya Venkatraman</strong>, Vipul Gupta, Rebecca J Passonneau, Shomir Wilson</p>
        <p class="ep-item-meta">EMNLP 2023<span class="ep-dot">·</span><span class="ep-award">Outstanding Paper Award</span><span class="ep-dot">·</span><a href="https://github.com/PranavNV/The-Sentiment-Problem/tree/main">Data</a></p>
      </li>
      <li>
        <a class="ep-item-title" href="https://aclanthology.org/2023.findings-eacl.70/" target="_blank" rel="noopener">How do decoding algorithms distribute information in dialogue responses?</a>
        <p class="ep-item-summary"><strong>Saranya Venkatraman</strong>, He He, David Reitter</p>
        <p class="ep-item-meta">EACL Findings 2023<span class="ep-dot">·</span><a href="https://huggingface.co/datasets/saranya132/dialog_uid_gpt2">Dataset</a></p>
      </li>
      <li>
        <a class="ep-item-title" href="/files/BOA-2021.pdf" target="_blank" rel="noopener">ClassInSight: Automating Analysis of Classroom Dialogue to Support Teacher Noticing and Reflection</a>
        <p class="ep-item-summary"><strong>Saranya Venkatraman</strong>, Prasenjit Mitra, Sherice N. Clarke, Andrea Gomoll, Zaynab Gates, Sushil S, Tarang Tripathi, Amy Ogan</p>
        <p class="ep-item-meta">EARLI 2021<span class="ep-dot">·</span><a href="https://github.com/saranya-venkatraman/classinsight-language">Code</a></p>
      </li>
    </ul>
  </section>

  <section class="ep-section" aria-labelledby="tut-label">
    <h2 class="ep-section-label" id="tut-label">Tutorials</h2>
    <ul class="ep-list">
      <li>
        <a class="ep-item-title" href="https://adauchendu.github.io/Tutorials/" target="_blank" rel="noopener">Catch Me If You GPT: Tutorial on Deepfake Texts</a>
        <p class="ep-item-meta">NAACL 2024</p>
      </li>
      <li>
        <a class="ep-item-title" href="https://artificial-text-detection.github.io/ATD_Tutorial.pdf" target="_blank" rel="noopener">Tutorial on Artificial Text Detection</a>
        <p class="ep-item-meta">INLG 2022</p>
      </li>
    </ul>
  </section>

  <section class="ep-section" aria-labelledby="exp-label">
    <h2 class="ep-section-label" id="exp-label">Experience</h2>
    <ul class="ep-list">
      <li>
        <span class="ep-item-title">Applied Scientist, Amazon</span>
        <p class="ep-item-summary">Building and evaluating agentic AI systems, with a focus on user simulation.</p>
        <p class="ep-item-meta">Feb 2025 – Present</p>
      </li>
      <li>
        <span class="ep-item-title">Research Intern, Google (Google Assistant)</span>
        <p class="ep-item-summary">Built a recommender dialogue agent using hierarchical Soft Actor-Critic for a hybrid action space.</p>
        <p class="ep-item-meta">May – Aug 2020</p>
      </li>
      <li>
        <span class="ep-item-title">Research Intern, Samsung Research America</span>
        <p class="ep-item-summary">Built an NLU intent-to-action service for Bixby using semantic similarity and word embeddings.</p>
        <p class="ep-item-meta">May – Aug 2018</p>
      </li>
      <li>
        <span class="ep-item-title">Machine Learning Intern, Cadence Design Systems</span>
        <p class="ep-item-summary">Built ML pipelines for proprietary chip layout images and a hierarchical clustering prototype.</p>
        <p class="ep-item-meta">May – Aug 2017</p>
      </li>
    </ul>
  </section>

  <section class="ep-section" aria-labelledby="beyond-label">
    <h2 class="ep-section-label" id="beyond-label">Beyond research</h2>
    <div class="ep-inline">
      <p><strong>Support for students.</strong> As a first-generation student, I know college and graduate school bring challenges that aren't always visible to others, from financial concerns to simply feeling out of place. I've also navigated advisor transitions during my PhD; James McLaughlin's post <a href="https://www.jfmclaughlin.org/blog/when-your-advisor-leaves">"When your advisor leaves"</a> is a useful starting point if you're in a similar situation. If you're facing any of these challenges, feel free to reach out by email. I'm happy to help.</p>
      <p><strong>Other interests.</strong> In my free time, I enjoy running, biking, snowboarding, and listening to and collecting vinyl records. In another life, I was a singer trained in Indian Classical Vocals and part of an a cappella group.</p>
    </div>
    <div class="ep-image-row">
      <img src="/images/running.png" alt="Running">
      <img src="/images/biking.png" alt="Biking">
      <img src="/images/snowboard1.png" alt="Snowboarding">
      <img src="/images/vinyl.png" alt="Vinyl records">
    </div>
  </section>

  <footer class="ep-footer">© 2026 Saranya Venkatraman</footer>

</div>
