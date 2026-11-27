---
permalink: /
title: ""
layout: single
author_profile: false
classes: wide
redirect_from:
  - /about/
  - /about.html
---

<style>
body:has(.rp-home) { background:#fff !important; margin-bottom:0 !important; padding-bottom:0 !important; color-scheme:light; }
body:has(.rp-home) .sidebar, body:has(.rp-home) .page__title, body:has(.rp-home) .page__footer { display:none !important; }
body:has(.rp-home) #main, body:has(.rp-home) .page, body:has(.rp-home) .page__inner-wrap, body:has(.rp-home) .page__content { width:100% !important; max-width:none !important; margin:0 !important; padding:0 !important; float:none !important; }
.rp-home { --ink:#17212b; --muted:#63717e; --accent:#42685f; --line:#cbd2d6; color:var(--ink); background:#fff; font-family:Arial, sans-serif; }
.rp-home * { box-sizing:border-box; }
.rp-container { max-width:1240px; margin:0 auto; padding:0 36px; }
.rp-intro { display:grid; grid-template-columns:210px minmax(0,1fr); gap:36px; align-items:start; padding:56px 0 38px; }
.rp-photo { width:100%; aspect-ratio:4/5; object-fit:cover; object-position:center; border-radius:18px; background:#edf0eb; box-shadow:0 5px 18px #17212b15; }
.rp-home .rp-name { font-size:clamp(28px,3vw,40px); letter-spacing:.02em; font-weight:600; line-height:1.15; margin:0 0 14px; color:var(--ink); border:0; padding:0; }
.rp-kicker { font-size:13px; letter-spacing:2px; font-weight:700; text-transform:uppercase; color:var(--accent); margin-bottom:14px; }
.rp-affiliation { font-size:15px; color:var(--muted); line-height:1.7; }
.rp-home .rp-bio { font-size:16px; line-height:1.8; margin:20px 0 14px; color:var(--ink); }
.rp-tags,.rp-links { display:flex; flex-wrap:wrap; gap:6px; margin:16px 0 0; }
.rp-tags span { border:1px solid var(--line); padding:6px 9px; font-size:12px; color:var(--muted); }
.rp-links { gap:0; }
.rp-home .rp-links a { display:inline-block; border:1px solid var(--line); padding:11px 15px; margin:0 -1px -1px 0; font-size:10px; font-weight:700; letter-spacing:1.5px; color:var(--ink); text-decoration:none; }
.rp-home .rp-links a:hover { background:var(--ink); color:#fff; }
.rp-section { padding:30px 0; border-top:1px solid var(--line); }
.rp-home .rp-section-title { text-align:center; font-size:14px; font-weight:500; letter-spacing:3px; text-transform:uppercase; margin:0 0 26px; border:0; padding:0; color:var(--ink); }
.rp-cards { display:grid; grid-template-columns:repeat(3,minmax(0,1fr)); border:1px solid var(--line); }
.rp-card { padding:24px; background:#fafbfa; }
.rp-card + .rp-card { border-left:1px solid var(--line); }
.rp-card-label { color:var(--accent); font-size:10px; font-weight:700; letter-spacing:2px; text-transform:uppercase; }
.rp-home .rp-card h3 { font-size:17px; margin:10px 0; color:var(--ink); }
.rp-home .rp-card p { font-size:14px; line-height:1.75; color:var(--muted); margin:0; }
.rp-news-row { display:grid; grid-template-columns:110px 1fr; gap:20px; padding:16px 0; border-top:1px solid #e3e7e8; font-size:15px; line-height:1.6; }
.rp-date { font-size:11px; font-weight:600; letter-spacing:1px; color:var(--muted); }
.rp-section-head { display:flex; align-items:center; justify-content:space-between; gap:16px; margin-bottom:20px; }
.rp-home .rp-section-head h2 { font-size:19px; margin:0; padding:0; border:0; }
.rp-home .rp-more { font-size:13px; color:var(--accent); text-decoration:none; }
/* Compact collaborators */
.rp-collaborators { display:grid; gap:12px; border-top:1px solid var(--line); padding-top:16px; }
.rp-collaborator-group { display:grid; grid-template-columns:180px minmax(0,1fr); gap:16px; align-items:baseline; font-size:15px; line-height:1.7; }
.rp-collaborator-label { font-weight:600; color:var(--ink); }
.rp-home .rp-collaborator-names a { color:var(--accent); text-decoration:none; }
.rp-home .rp-collaborator-names a:hover { text-decoration:underline; }
@media(max-width:640px) { .rp-collaborator-group { grid-template-columns:1fr; gap:3px; } }
.rp-footer { background:#eef0eb; border-top:1px solid #c9cec7; margin-top:36px; padding:55px 0 40px; }
.rp-footer-grid { display:grid; grid-template-columns:1.4fr 1fr 1fr; gap:45px; }
.rp-footer-name { font-size:25px; font-weight:700; margin-bottom:16px; }
.rp-home .rp-footer-description { font:15px/1.8 Georgia,serif; color:var(--muted); max-width:280px; margin:0; }
.rp-footer-label { font:11px monospace; letter-spacing:2px; color:var(--muted); margin-bottom:14px; }
.rp-home .rp-footer a { display:block; width:fit-content; font:15px/2 Georgia,serif; color:var(--ink); text-decoration:none; }
.rp-home .rp-footer a:hover { text-decoration:underline; }
.rp-copyright { border-top:1px solid #c9cec7; margin-top:45px; padding-top:20px; font:11px monospace; color:var(--muted); }
@media(max-width:850px) { .rp-intro { grid-template-columns:175px minmax(0,1fr); gap:28px; } .rp-card { padding:16px; } }
@media(max-width:640px) { .rp-container { padding:0 22px; } .rp-intro { grid-template-columns:1fr; padding-top:32px; } .rp-photo { max-width:175px; } .rp-cards,.rp-footer-grid { grid-template-columns:1fr; } .rp-card + .rp-card { border-left:0; border-top:1px solid var(--line); } .rp-news-row { grid-template-columns:1fr; gap:5px; } .rp-footer-grid { gap:24px; } }

/* Filterable latest news */
.rp-news-head { display:flex; align-items:center; justify-content:space-between; flex-wrap:wrap; gap:12px; padding-bottom:12px; border-bottom:1px solid var(--ink); }
.rp-home .rp-news-head h2 { font-size:15px; letter-spacing:2px; text-transform:uppercase; margin:0; padding:0; border:0; }
.rp-news-head h2::before { content:""; display:inline-block; width:7px; height:7px; background:var(--accent); border-radius:50%; margin-right:10px; vertical-align:2px; }
.rp-news-filters { display:flex; flex-wrap:wrap; gap:3px; }
.rp-news-filters button { font:12px Arial,sans-serif; color:var(--muted); background:transparent; border:1px solid transparent; padding:7px 10px; cursor:pointer; }
.rp-news-filters button[aria-pressed="true"] { border-color:var(--ink); color:var(--ink); }
.rp-news-filters button:hover { color:var(--ink); background:#f5f7f6; }
.rp-home .rp-news-row { display:flex; align-items:baseline; gap:12px; padding:14px 0; border-top:0; border-bottom:1px solid var(--line); font-size:14px; color:var(--muted); }
.rp-news-row .rp-date { flex:0 0 118px; font-size:12px; font-weight:400; letter-spacing:0; }
.rp-news-tag { flex:none; border:1px solid #8b8173; padding:3px 7px; font-size:9px; font-weight:600; letter-spacing:1.1px; text-transform:uppercase; color:#776b59; }
.rp-news-copy { flex:1; min-width:0; }
.rp-news-copy strong { color:var(--ink); }
.rp-home .rp-news-row[hidden], .rp-home .rp-news-toggle[hidden], .rp-home .rp-news-empty[hidden] { display:none !important; }
.rp-news-actions { display:flex; justify-content:space-between; align-items:center; gap:16px; margin-top:16px; }
.rp-news-toggle { border:0; border-bottom:1px solid var(--muted); padding:0 0 4px; background:transparent; color:var(--ink); font:600 13px Arial,sans-serif; cursor:pointer; }
.rp-news-empty { font-size:14px; color:var(--muted); padding:16px 0; }
.rp-news-filters button:focus-visible,.rp-news-toggle:focus-visible { outline:2px solid var(--accent); outline-offset:2px; }
@media(max-width:640px) { .rp-home .rp-news-row { flex-wrap:wrap; gap:8px; } .rp-news-row .rp-date { flex-basis:auto; } .rp-news-copy { flex-basis:100%; } }

</style>

<div class="rp-home">
  <main class="rp-container">
    <section class="rp-intro" aria-label="Introduction">
      <img class="rp-photo" src="{{ '/images/portrait.jpg' | relative_url }}" alt="Robi Paul" />
      <div>
        <h1 class="rp-name">Robi Paul</h1>
        <div class="rp-kicker">Ph.D. Student &nbsp; | &nbsp; Hardware Security</div>
        <div class="rp-affiliation">Graduate Research Assistant · <strong>Rochester Institute of Technology</strong><br>Department of Computer Engineering</div>
        <p class="rp-bio">I am a Ph.D. student in Computer Engineering at the Rochester Institute of Technology (RIT), advised by Prof. Michael Zuzak. My research explores the intersection of hardware security, physical side-channel analysis, and trustworthy machine learning. I investigate how physical information leakage can be leveraged to understand, attack, and protect computing systems.</p>
        <div class="rp-tags"><span>Hardware Security</span><span>Side-Channel Analysis</span><span>AI Security</span><span>Digital VLSI/CAD</span></div>
        <div class="rp-links">
          <a href="https://scholar.google.com/citations?user=7Z14CtUAAAAJ" target="_blank" rel="noopener noreferrer">SCHOLAR</a>
          <a href="https://github.com/robi-paul" target="_blank" rel="noopener noreferrer">GITHUB</a>
          <a href="https://orcid.org/0000-0002-7367-8432" target="_blank" rel="noopener noreferrer">ORCID</a>
          {% if site.author.linkedin %}<a href="https://www.linkedin.com/in/{{ site.author.linkedin }}/" target="_blank" rel="noopener noreferrer">LINKEDIN</a>{% endif %}
          <a href="mailto:rp7248@rit.edu">EMAIL</a>
        </div>
      </div>
    </section>
    <section class="rp-section">
      <h2 class="rp-section-title">Research directions</h2>
      <div class="rp-cards">
        <article class="rp-card"><div class="rp-card-label">Physical security</div><h3>Side-Channel Analysis</h3><p>Leveraging physical leakage for security monitoring, anomaly detection, and system characterization.</p></article>
        <article class="rp-card"><div class="rp-card-label">Trustworthy AI</div><h3>Machine Learning Security</h3><p>Investigating vulnerabilities and developing defenses for machine learning on embedded platforms.</p></article>
        <article class="rp-card"><div class="rp-card-label">Secure hardware</div><h3>Digital VLSI &amp; CAD</h3><p>Exploring logic locking, hardware protection, and security-aware design automation.</p></article>
      </div>
      <p style="text-align:right;margin:16px 0 0;"><a class="rp-more" href="{{ '/research/' | relative_url }}">Explore my research &rarr;</a></p>
    </section>
    <section class="rp-section" id="rp-latest-news">
      <div class="rp-news-head">
        <h2>Latest news</h2>
        <div class="rp-news-filters" role="group" aria-label="Filter news">
          <button type="button" data-filter="all" aria-pressed="true">All</button>
          <button type="button" data-filter="publication" aria-pressed="false">Publications</button>
          <button type="button" data-filter="conference" aria-pressed="false">Conferences</button>
          <button type="button" data-filter="teaching" aria-pressed="false">Teaching</button>
          <button type="button" data-filter="phd" aria-pressed="false">PhD</button>
          <button type="button" data-filter="service" aria-pressed="false">Service</button>
        </div>
      </div>
      <div id="rp-news-list">
        <!-- Add new entries at the top. Use space-separated categories when needed. -->
        <div class="rp-news-row" data-category="publication">
          <span class="rp-date">Nov 22, 2026</span>
          <span class="rp-news-tag">Publication</span>
          <span class="rp-news-copy">Paper accepted to <strong>ACM Transactions on Design Automation of Electronic Systems (TODAES).</strong></span>
        </div>
        <div class="rp-news-row" data-category="publication">
          <span class="rp-date">Oct 27, 2026</span>
          <span class="rp-news-tag">Publication</span>
          <span class="rp-news-copy">Paper accepted to <strong>ACM Journal on Emerging Technologies in Computing Systems (JETC).</strong></span>
        </div>
        <div class="rp-news-row" data-category="publication">
          <span class="rp-date">Sep 6, 2026</span>
          <span class="rp-news-tag">Publication</span>
          <span class="rp-news-copy">Paper accepted to <strong>IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (TCAD).</strong></span>
        </div>
        <div class="rp-news-row" data-category="publication">
          <span class="rp-date">Feb 1, 2026</span>
          <span class="rp-news-tag">Publication</span>
          <span class="rp-news-copy">Paper accepted to <strong>IEEE Transactions on Information Forensics and Security (TIFS).</strong></span>
        </div>
        <div class="rp-news-row" data-category="publication">
          <span class="rp-date">Oct 11, 2025</span>
          <span class="rp-news-tag">Publication</span>
          <span class="rp-news-copy">Paper accepted to <strong>IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (TCAD).</strong></span>
        </div>
        <div class="rp-news-row" data-category="publication conference" hidden>
          <span class="rp-date">Dec 8, 2024</span>
          <span class="rp-news-tag">Publication</span>
          <span class="rp-news-copy">Paper accepted to <strong>IEEE International Symposium on Hardware Oriented Security and Trust (HOST 2025).</strong></span>
        </div>
        <div class="rp-news-row" data-category="publication" hidden>
          <span class="rp-date">Nov 20, 2024</span>
          <span class="rp-news-tag">Publication</span>
          <span class="rp-news-copy">Paper accepted to <strong>Journal of Hardware and Systems Security (JHSS).</strong></span>
        </div>
      </div>
      <p class="rp-news-empty" role="status" hidden>No news in this category yet.</p>
      <div class="rp-news-actions">
        <button class="rp-news-toggle" type="button" aria-controls="rp-news-list" aria-expanded="false">Show all 7</button>
        <a class="rp-more" href="{{ '/news/' | relative_url }}">View full news page &rarr;</a>
      </div>
    </section>
    <script>
    (function () {
      const section = document.getElementById('rp-latest-news');
      if (!section) return;
      const rows = Array.from(section.querySelectorAll('.rp-news-row'));
      const filters = Array.from(section.querySelectorAll('[data-filter]'));
      const toggle = section.querySelector('.rp-news-toggle');
      const empty = section.querySelector('.rp-news-empty');
      const limit = 5;
      let active = 'all';
      let expanded = false;
      function render() {
        const matches = rows.filter(row => active === 'all' || row.dataset.category.split(/\s+/).includes(active));
        const visible = new Set(expanded ? matches : matches.slice(0, limit));
        rows.forEach(row => { row.hidden = !visible.has(row); });
        filters.forEach(button => button.setAttribute('aria-pressed', String(button.dataset.filter === active)));
        empty.hidden = matches.length !== 0;
        toggle.hidden = matches.length <= limit;
        toggle.textContent = expanded ? 'Show less' : 'Show all ' + matches.length;
        toggle.setAttribute('aria-expanded', String(expanded));
      }
      filters.forEach(button => button.addEventListener('click', function () {
        active = button.dataset.filter;
        expanded = false;
        render();
      }));
      toggle.addEventListener('click', function () { expanded = !expanded; render(); });
      render();
    })();
    </script>
    <section class="rp-section">
      <div class="rp-section-head"><h2>Collaborators</h2></div>
      <div class="rp-collaborators">
        <!-- Replace each placeholder URL and name with the actual collaborator. -->
        <div class="rp-collaborator-group">
          <span class="rp-collaborator-label">Faculty:</span>
          <span class="rp-collaborator-names"><a href="https://example.com/faculty-1" target="_blank" rel="noopener noreferrer">Gen Dow</a>, <a href="https://example.com/faculty-2" target="_blank" rel="noopener noreferrer">Gen Dow</a></span>
        </div>
        <div class="rp-collaborator-group">
          <span class="rp-collaborator-label">Student Researchers:</span>
          <span class="rp-collaborator-names"><a href="https://example.com/student-1" target="_blank" rel="noopener noreferrer">Gen Dow</a>, <a href="https://example.com/student-2" target="_blank" rel="noopener noreferrer">Gen Dow</a></span>
        </div>
      </div>
    </section>
  </main>
  <footer class="rp-footer">
    <div class="rp-container">
      <div class="rp-footer-grid">
        <div><div class="rp-footer-name">Robi Paul</div><p class="rp-footer-description">Hardware security, machine learning, and trustworthy computing.</p></div>
        <div><div class="rp-footer-label">FIND ME</div><a href="https://www.google.com/maps/search/?api=1&amp;query=Rochester+New+York" target="_blank" rel="noopener noreferrer">Rochester, New York</a></div>
        <div><div class="rp-footer-label">ELSEWHERE</div><a href="mailto:rp7248@rit.edu">rp7248@rit.edu</a>{% if site.author.linkedin %}<a href="https://www.linkedin.com/in/{{ site.author.linkedin }}/" target="_blank" rel="noopener noreferrer">LinkedIn</a>{% endif %}<a href="https://scholar.google.com/citations?user=7Z14CtUAAAAJ" target="_blank" rel="noopener noreferrer">Google Scholar</a></div>
      </div>
      <div class="rp-copyright">&copy; Robi Paul</div>
    </div>
  </footer>
</div>
