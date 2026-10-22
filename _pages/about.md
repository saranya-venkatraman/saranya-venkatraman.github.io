---
permalink: /
author_profile: false
---
<style>
  @import url('https://fonts.googleapis.com/css2?family=Lato:ital,wght@0,400;0,700;1,400&family=Manrope:wght@700&display=swap');

  /* ---------- Reset the theme chrome on this page ---------- */
  .masthead, .page__footer, .page__inner-wrap > header, .page__meta { display: none !important; }
  html, body { background: #f4f7fc !important; }
  body { padding: 0 !important; margin: 0 !important; color: #1a1a1a; font-family: Lato, Arial, Tahoma, sans-serif !important; }
  #main { max-width: none !important; width: 100% !important; margin: 0 !important; padding: 0 !important; }
  .page { float: none !important; width: 100% !important; padding: 0 !important; margin: 0 !important; }
  .page__inner-wrap, .page__content { margin: 0 !important; padding: 0 !important; }
  .page__content { font-family: Lato, Arial, Tahoma, sans-serif !important; font-size: 16px !important; color: #1a1a1a; }
  .page__content a { border: none !important; }

  /* ---------- Top bar ---------- */
  .sv-topbar { background: #fff; border-bottom: 1px solid #e0dbd6; position: sticky; top: 0; z-index: 10; }
  .sv-topbar-inner { max-width: 1100px; margin: 0 auto; padding: 0 24px; height: 62px; display: flex; align-items: center; justify-content: flex-end; }
  .sv-topbar ul { list-style: none; display: flex; margin: 0 !important; padding: 0 !important; }
  .sv-topbar li { margin: 0 !important; padding: 0 !important; display: flex; align-items: center; }
  .sv-topbar li + li::before { content: ""; width: 1px; height: 16px; background: #e0dbd6; }
  .sv-topbar a { font-size: 13px; font-weight: 500; color: #1a1a1a !important; text-decoration: none !important; padding: 0 20px; }
  .sv-topbar li:last-child a { padding-right: 0; }
  .sv-topbar a:hover, .sv-topbar a.active { color: #1a3a52 !important; }

  /* ---------- Main column ---------- */
  .sv-wrap { max-width: 780px; margin: 0 auto; padding: 48px 24px 20px; box-sizing: border-box; }
  .sv-header-row { display: flex; align-items: flex-start; gap: 24px; margin-bottom: 44px; }
  .sv-photo { width: 96px !important; height: 96px !important; border-radius: 50%; object-fit: cover; flex-shrink: 0; display: block; margin: 0 !important; }
  .sv-header-text { flex: 1 1 0%; min-width: 0; }
  .page__content h1.sv-name { font-family: Manrope, -apple-system, "Segoe UI", Arial, sans-serif !important; font-size: 36px !important; font-weight: 700 !important; color: #1a1a1a !important; letter-spacing: -0.01em; line-height: 1.1 !important; margin: 0 0 8px !important; padding: 0 !important; border: none !important; }
  .page__content p.sv-role { font-size: 14px !important; color: #5e5e5e !important; margin: 0 0 12px !important; line-height: 1.5 !important; }
  .page__content p.sv-role strong { font-weight: 600; color: #3d3d3d; }
  ul.sv-social { display: flex; align-items: center; list-style: none; margin: 0 !important; padding: 0 !important; }
  ul.sv-social li { margin: 0 !important; padding: 0 !important; }
  .page__content a.sv-social-link { display: inline-flex; align-items: center; justify-content: center; padding: 6px 12px 6px 0; color: #5e5e5e !important; text-decoration: none !important; }
  .page__content a.sv-social-link:hover { color: #1a3a52 !important; }
  .sv-social-link svg { width: 15px; height: 15px; vertical-align: middle; }

  hr.sv-hr { border: none !important; border-top: 1px solid #e0dbd6 !important; margin: 20px 0 24px !important; padding: 0; height: 0; background: none; }

  .sv-bio p { color: #1a1a1a !important; font-size: 16px !important; line-height: 1.7 !important; margin: 0 0 16px !important; text-align: left !important; }
  .sv-bio p:last-child { margin-bottom: 0 !important; }
  .page__content .sv-bio a, .page__content .sv-inline a { color: #1a3a52 !important; text-decoration: underline !important; text-decoration-color: rgba(26,58,82,0.35) !important; text-underline-offset: 2px; }
  .page__content .sv-bio a:hover, .page__content .sv-inline a:hover { text-decoration-color: #1a3a52 !important; }

  /* ---------- Sections ---------- */
  .sv-bio + .sv-section { margin-top: 40px; }
  .sv-section + .sv-section { margin-top: 40px; }
  .page__content h2.sv-section-label { font-family: Lato, Arial, Tahoma, sans-serif !important; font-size: 11px !important; font-weight: 600 !important; text-transform: uppercase; letter-spacing: 0.12em; color: #5e5e5e !important; margin: 0 0 16px !important; padding: 0 0 14px !important; border: none !important; border-bottom: 1px solid #e0dbd6 !important; line-height: 1.5 !important; }
  ul.sv-list { list-style: none !important; padding: 0 !important; margin: 0 !important; }
  ul.sv-list > li { margin: 0 0 18px !important; padding: 0 !important; list-style: none !important; }
  ul.sv-list > li::marker { content: none; }
  .page__content .sv-item-title, .page__content a.sv-item-title { color: #1a1a1a !important; text-decoration: none !important; font-weight: 500; font-size: 15px; line-height: 1.73; }
  .page__content .sv-item-title strong { font-weight: 700; }
  .page__content a.sv-item-title:hover { color: #1a3a52 !important; text-decoration: underline !important; text-underline-offset: 2px; }
  .page__content p.sv-item-summary { color: #737e86 !important; font-size: 16px !important; line-height: 1.625 !important; margin: 2px 0 0 !important; }
  .page__content p.sv-item-meta { color: #5e5e5e !important; font-size: 13px !important; margin: 4px 0 0 !important; line-height: 1.5 !important; }
  .page__content p.sv-item-meta a { color: #1a3a52 !important; text-decoration: none !important; font-weight: 500; }
  .page__content p.sv-item-meta a:hover { text-decoration: underline !important; }
  /* Paper thumbnails */
  ul.sv-list > li.sv-pub { display: flex; gap: 16px; align-items: flex-start; }
  .page__content a.sv-thumb { flex: 0 0 150px; width: 150px; height: 100px; display: block; background: #fff; border: 1px solid #e3e7ee; border-radius: 4px; overflow: hidden; margin-top: 4px; }
  .sv-thumb img { width: 100% !important; height: 100% !important; object-fit: contain; padding: 4px; box-sizing: border-box; display: block; margin: 0 !important; }
  .sv-pub-body { flex: 1 1 0%; min-width: 0; }
  .sv-award { color: #9a5b13; font-weight: 600; }
  .page__content a.sv-view-all { color: #1a3a52 !important; text-decoration: none !important; font-weight: 500; font-size: 14px; display: inline-block; margin-top: 2px; }
  .page__content a.sv-view-all:hover { text-decoration: underline !important; text-underline-offset: 2px; }
  .sv-dot { color: #b5b0aa; margin: 0 4px; }

  .sv-inline p { font-size: 16px !important; line-height: 1.7 !important; margin: 0 0 16px !important; color: #1a1a1a !important; text-align: left !important; }

  .sv-image-row { display: grid; grid-template-columns: repeat(3, minmax(0, 140px)); gap: 10px; margin-top: 8px; }
  .sv-image-row img { width: 100%; aspect-ratio: 3 / 4; object-fit: cover; object-position: center top; border-radius: 4px; display: block; margin: 0 !important; }
  .sv-image-row img.sv-img-wide { object-position: 65% center; }

  .sv-footer { color: #6b6b6b; font-size: 13px; border-top: 1px solid #e0dbd6; margin-top: 64px; padding-top: 24px; }

  @media (max-width: 600px) {
    .sv-topbar a { padding: 0 12px; }
    .sv-header-row { flex-direction: column; gap: 16px; }
    ul.sv-list > li.sv-pub { gap: 12px; }
    .page__content a.sv-thumb { flex-basis: 100px; width: 100px; height: 68px; }
    .sv-photo { width: 88px !important; height: 88px !important; }
    .page__content h1.sv-name { font-size: 30px !important; }
  }
</style>

<nav class="sv-topbar" aria-label="Site">
  <div class="sv-topbar-inner">
    <ul>
      <li><a href="/" class="active">Home</a></li>
      <li><a href="#exp-label">Experience</a></li>
      <li><a href="#pubs-label">Publications</a></li>
      <li><a href="/files/CV_Venkatraman_Oct_2026.pdf">CV</a></li>
    </ul>
  </div>
</nav>

<div class="sv-wrap">

  <header class="sv-header-row">
    <img class="sv-photo" src="/images/profile.png" alt="Saranya Venkatraman">
    <div class="sv-header-text">
      <h1 class="sv-name">Saranya Venkatraman</h1>
      <p class="sv-role"><strong>Applied Scientist</strong> · Amazon</p>
      <nav aria-label="Social links">
        <ul class="sv-social">
          <li><a class="sv-social-link" href="mailto:saranya132@gmail.com" aria-label="Email" title="Email"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5"><rect x="2" y="4" width="20" height="16" rx="2"></rect><path d="M2 7l10 7 10-7"></path></svg></a></li>
          <li><a class="sv-social-link" href="https://scholar.google.com/citations?user=qrvxwt4AAAAJ&amp;hl=en" aria-label="Google Scholar" title="Google Scholar" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M5.242 13.769L0 9.5 12 0l12 9.5-5.242 4.269C17.548 11.249 14.978 9.5 12 9.5c-2.977 0-5.548 1.748-6.758 4.269zM12 10a7 7 0 1 0 0 14 7 7 0 0 0 0-14z"></path></svg></a></li>
          <li><a class="sv-social-link" href="https://github.com/saranya-venkatraman" aria-label="GitHub" title="GitHub" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0 1 12 6.844a9.59 9.59 0 0 1 2.504.337c1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.202 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.02 10.02 0 0 0 22 12.017C22 6.484 17.522 2 12 2z"></path></svg></a></li>
          <li><a class="sv-social-link" href="https://www.linkedin.com/in/saranyaven" aria-label="LinkedIn" title="LinkedIn" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433a2.062 2.062 0 0 1-2.063-2.065 2.064 2.064 0 1 1 2.063 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"></path></svg></a></li>
          <li><a class="sv-social-link" href="/files/CV_Venkatraman_Oct_2026.pdf" aria-label="CV" title="CV" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linejoin="round"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"></path><path d="M14 2v6h6M8 13h8M8 17h5"></path></svg></a></li>
        </ul>
      </nav>
    </div>
  </header>

  <hr class="sv-hr">

  <div class="sv-bio">
    <p>I'm an Applied Scientist at Amazon, where I build and evaluate agentic AI systems. My current work focuses on <em>user simulation</em>: building agentic "twins" of users. I completed my PhD at Penn State University, advised by <a href="https://pike.psu.edu/dongwon/">Prof. Dongwon Lee</a> in the <a href="https://pike.psu.edu/index.html">PIKE research group</a>, and was a Visiting Scholar at New York University in <a href="https://hhexiy.github.io">Prof. He He</a>'s group. My PhD research focused on <em>machine-generated text detection, authorship attribution, and obfuscation</em> for Large Language Models (LLMs), and on what does or doesn't make LLM-generated text "human-like."</p>
    <p>Along the way, I was a research intern at Google, Samsung, and Cadence, building RL, NLP, and ML solutions for dialogue-based recommenders, voice assistants, and hardware design layouts. I'm broadly curious about cognitively plausible architectures for language applications, and always happy to connect.</p>
  </div>

  <section class="sv-section" aria-labelledby="exp-label">
    <h2 class="sv-section-label" id="exp-label">Experience</h2>
    <ul class="sv-list">
      <li>
        <span class="sv-item-title">Applied Scientist, Amazon</span>
        <p class="sv-item-summary">Building LLM-powered agentic twins of customers to simulate shopping behavior and evaluate experiences at scale.</p>
        <p class="sv-item-meta">Feb 2025 – Present</p>
      </li>
      <li>
        <span class="sv-item-title">Research Intern, Google (Google Assistant)</span>
        <p class="sv-item-summary">Built an RL (hierarchical Soft Actor-Critic) recommender dialogue agent that learns user preferences and suggests items from a marketplace.</p>
        <p class="sv-item-meta">May – Sept 2020</p>
      </li>
      <li>
        <span class="sv-item-title">Research Intern, Samsung Research America</span>
        <p class="sv-item-summary">Built a semantic-search intent-to-action service for Bixby, deployed end-to-end on mobile devices.</p>
        <p class="sv-item-meta">May – Aug 2018</p>
      </li>
      <li>
        <span class="sv-item-title">Machine Learning Intern, Cadence Design Systems</span>
        <p class="sv-item-summary">Built feature-extraction and ML pipelines for chip layout images, using hierarchical clustering for assisted labeling.</p>
        <p class="sv-item-meta">May – Aug 2017</p>
      </li>
    </ul>
  </section>

  <section class="sv-section" aria-labelledby="pubs-label">
    <h2 class="sv-section-label" id="pubs-label">Selected publications</h2>
    <ul class="sv-list">
      <li class="sv-pub">
        <a class="sv-thumb" href="https://cdn.amazon.science/d9/3b/f8deb9734e34a2dd9239f335ac76/scipub-approval152134-48355376-agentwin-an-endtoend-framework-for-building-agentic-twins-of-mobile-users.pdf" target="_blank" rel="noopener" tabindex="-1" aria-hidden="true"><img src="/images/agentwin.png" alt="" loading="lazy"></a>
        <div class="sv-pub-body">
          <a class="sv-item-title" href="https://cdn.amazon.science/d9/3b/f8deb9734e34a2dd9239f335ac76/scipub-approval152134-48355376-agentwin-an-endtoend-framework-for-building-agentic-twins-of-mobile-users.pdf" target="_blank" rel="noopener"><strong>AgenTwin</strong>: An End-to-End Framework for Building Agentic Twins of Mobile Users</a>
          <p class="sv-item-summary">Saranya Venkatraman, Thanh Tran, Shunyan Luo, Devin Chen, Yuning Wu, Kai Wei, Allie Colin, Guido Imbens, Ido Rosen, Christine Ambrose</p>
          <p class="sv-item-meta">COLM 2026 Workshop on Agent Behavior<span class="sv-dot">·</span><a href="https://cdn.amazon.science/d9/3b/f8deb9734e34a2dd9239f335ac76/scipub-approval152134-48355376-agentwin-an-endtoend-framework-for-building-agentic-twins-of-mobile-users.pdf" target="_blank" rel="noopener">PDF</a></p>
        </div>
      </li>
      <li class="sv-pub">
        <a class="sv-thumb" href="https://arxiv.org/abs/2406.12665" target="_blank" rel="noopener" tabindex="-1" aria-hidden="true"><img src="/images/collabstory.png" alt="" loading="lazy"></a>
        <div class="sv-pub-body">
          <a class="sv-item-title" href="https://arxiv.org/abs/2406.12665" target="_blank" rel="noopener"><strong>CollabStory</strong>: Multi-LLM Collaborative Story Generation and Authorship Analysis</a>
          <p class="sv-item-summary">Saranya Venkatraman, Nafis Irtiza Tripto, Dongwon Lee</p>
          <p class="sv-item-meta">NAACL Findings 2025<span class="sv-dot">·</span><a href="https://arxiv.org/pdf/2406.12665" target="_blank" rel="noopener">PDF</a><span class="sv-dot">·</span><a href="https://github.com/saranya-venkatraman/multi_llm_story_writing">Code</a></p>
        </div>
      </li>
      <li class="sv-pub">
        <a class="sv-thumb" href="https://arxiv.org/pdf/2310.06202.pdf" target="_blank" rel="noopener" tabindex="-1" aria-hidden="true"><img src="/images/gptwho.png" alt="" loading="lazy"></a>
        <div class="sv-pub-body">
          <a class="sv-item-title" href="https://arxiv.org/pdf/2310.06202.pdf" target="_blank" rel="noopener"><strong>GPT-who</strong>: An Information Density-based Machine-Generated Text Detector</a>
          <p class="sv-item-summary">Saranya Venkatraman, Adaku Uchendu, Dongwon Lee</p>
          <p class="sv-item-meta">NAACL Findings 2024<span class="sv-dot">·</span><a href="https://arxiv.org/pdf/2310.06202" target="_blank" rel="noopener">PDF</a><span class="sv-dot">·</span><a href="https://github.com/saranya-venkatraman/gpt-who">Code</a></p>
        </div>
      </li>
      <li class="sv-pub">
        <a class="sv-thumb" href="https://arxiv.org/pdf/2311.08374" target="_blank" rel="noopener" tabindex="-1" aria-hidden="true"><img src="/images/ship.png" alt="" loading="lazy"></a>
        <div class="sv-pub-body">
          <a class="sv-item-title" href="https://arxiv.org/pdf/2311.08374" target="_blank" rel="noopener"><strong>A Ship of Theseus</strong>: Curious Cases of Paraphrasing in LLM-Generated Texts</a>
          <p class="sv-item-summary">Nafis Irtiza Tripto, Saranya Venkatraman, Dominik Macko, Robert Moro, Ivan Srba, Adaku Uchendu, Thai Le, Dongwon Lee</p>
          <p class="sv-item-meta">ACL 2024<span class="sv-dot">·</span><a href="https://arxiv.org/pdf/2311.08374" target="_blank" rel="noopener">PDF</a></p>
        </div>
      </li>
      <li class="sv-pub">
        <a class="sv-thumb" href="https://ojs.aaai.org/index.php/AAAI/article/view/29901" target="_blank" rel="noopener" tabindex="-1" aria-hidden="true"><img src="/images/alison.png" alt="" loading="lazy"></a>
        <div class="sv-pub-body">
          <a class="sv-item-title" href="https://ojs.aaai.org/index.php/AAAI/article/view/29901" target="_blank" rel="noopener"><strong>ALISON</strong>: Fast and Effective Stylometric Authorship Obfuscation</a>
          <p class="sv-item-summary">Eric Xing, Saranya Venkatraman, Thai Le, Dongwon Lee</p>
          <p class="sv-item-meta">AAAI 2024<span class="sv-dot">·</span><a href="https://arxiv.org/pdf/2402.00835" target="_blank" rel="noopener">PDF</a><span class="sv-dot">·</span><a href="https://github.com/ericx003/alison">Code</a></p>
        </div>
      </li>
      <li class="sv-pub">
        <a class="sv-thumb" href="https://tngoon.github.io/docs/pubs/Ngoon_etal_2024_CHI.pdf" target="_blank" rel="noopener" tabindex="-1" aria-hidden="true"><img src="/images/cis.png" alt="" loading="lazy"></a>
        <div class="sv-pub-body">
          <a class="sv-item-title" href="https://tngoon.github.io/docs/pubs/Ngoon_etal_2024_CHI.pdf" target="_blank" rel="noopener"><strong>ClassInSight</strong>: Designing Conversation Support Tools to Visualize Classroom Discussion for Personalized Teacher Professional Development</a>
          <p class="sv-item-summary">Tricia J Ngoon, S Sushil, Angela Stewart, Ung-Sang Lee, Saranya Venkatraman, Neil Thawani, Prasenjit Mitra, Sherice Clarke, John Zimmerman, Amy Ogan</p>
          <p class="sv-item-meta">CHI 2024<span class="sv-dot">·</span><a href="https://tngoon.github.io/docs/pubs/Ngoon_etal_2024_CHI.pdf" target="_blank" rel="noopener">PDF</a></p>
        </div>
      </li>
    </ul>
    <a class="sv-view-all" href="https://scholar.google.com/citations?user=qrvxwt4AAAAJ&amp;hl=en" target="_blank" rel="noopener">All publications on Google Scholar →</a>
  </section>

  <section class="sv-section" aria-labelledby="tut-label">
    <h2 class="sv-section-label" id="tut-label">Tutorials</h2>
    <ul class="sv-list">
      <li>
        <a class="sv-item-title" href="https://adauchendu.github.io/Tutorials/" target="_blank" rel="noopener">Catch Me If You GPT: Tutorial on Deepfake Texts</a>
        <p class="sv-item-meta">NAACL 2024</p>
      </li>
      <li>
        <a class="sv-item-title" href="https://artificial-text-detection.github.io/ATD_Tutorial.pdf" target="_blank" rel="noopener">Tutorial on Artificial Text Detection</a>
        <p class="sv-item-meta">INLG 2022</p>
      </li>
    </ul>
  </section>

  <section class="sv-section" aria-labelledby="beyond-label">
    <h2 class="sv-section-label" id="beyond-label">Misc.</h2>
    <div class="sv-inline">
      <p>Outside work, I run, snowboard, and collect vinyl records. In another life, I sang Indian Classical music and a cappella.</p>
    </div>
    <div class="sv-image-row">
      <img src="/images/running.png" alt="Running">
      <img src="/images/snowboard2.jpg" alt="Snowboarding">
      <img class="sv-img-wide" src="/images/vinyl.png" alt="Vinyl records">
    </div>
  </section>

  <footer class="sv-footer">© 2026 Saranya Venkatraman</footer>

</div>
