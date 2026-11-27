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
.rp-intro { display:grid; grid-template-columns:260px minmax(0,1fr); gap:46px; align-items:start; padding:56px 0 38px; }
.rp-photo { width:100%; aspect-ratio:4/5; object-fit:cover; object-position:center; border-radius:18px; background:#edf0eb; box-shadow:0 5px 18px #17212b15; }
.rp-home .rp-name { font-size:clamp(32px,4vw,52px); letter-spacing:.13em; font-weight:400; line-height:1.15; margin:0 0 14px; color:var(--ink); border:0; padding:0; }
.rp-name strong { font-weight:800; }
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
.rp-education { font-size:14px; line-height:1.75; color:var(--muted); }
.rp-footer { background:#eef0eb; border-top:1px solid #c9cec7; margin-top:36px; padding:55px 0 40px; }
.rp-footer-grid { display:grid; grid-template-columns:1.4fr 1fr 1fr; gap:45px; }
.rp-footer-name { font-size:25px; font-weight:700; margin-bottom:16px; }
.rp-home .rp-footer-description { font:15px/1.8 Georgia,serif; color:var(--muted); max-width:280px; margin:0; }
.rp-footer-label { font:11px monospace; letter-spacing:2px; color:var(--muted); margin-bottom:14px; }
.rp-home .rp-footer a { display:block; width:fit-content; font:15px/2 Georgia,serif; color:var(--ink); text-decoration:none; }
.rp-home .rp-footer a:hover { text-decoration:underline; }
.rp-copyright { border-top:1px solid #c9cec7; margin-top:45px; padding-top:20px; font:11px monospace; color:var(--muted); }
@media(max-width:850px) { .rp-intro { grid-template-columns:200px minmax(0,1fr); gap:28px; } .rp-card { padding:16px; } }
@media(max-width:640px) { .rp-container { padding:0 22px; } .rp-intro { grid-template-columns:1fr; padding-top:32px; } .rp-photo { max-width:220px; } .rp-cards,.rp-footer-grid { grid-template-columns:1fr; } .rp-card + .rp-card { border-left:0; border-top:1px solid var(--line); } .rp-news-row { grid-template-columns:1fr; gap:5px; } .rp-footer-grid { gap:24px; } }
</style>

<div class="rp-home">
  <main class="rp-container">
    <section class="rp-intro" aria-label="Introduction">
      <img class="rp-photo" src="{{ '/images/portrait.jpg' | relative_url }}" alt="Robi Paul" />
      <div>
        <h1 class="rp-name">ROBI <strong>PAUL</strong></h1>
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
    <section class="rp-section">
      <div class="rp-section-head"><h2>Recent news</h2><a class="rp-more" href="{{ '/news/' | relative_url }}">View all news &rarr;</a></div>
      <div class="rp-news-row"><span class="rp-date">NOV 2026</span><span>Paper accepted to <strong>ACM Transactions on Design Automation of Electronic Systems (TODAES).</strong></span></div>
      <div class="rp-news-row"><span class="rp-date">OCT 2026</span><span>Paper accepted to <strong>ACM Journal on Emerging Technologies in Computing Systems (JETC).</strong></span></div>
      <div class="rp-news-row"><span class="rp-date">SEP 2026</span><span>Paper accepted to <strong>IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (TCAD).</strong></span></div>
    </section>
    <section class="rp-section">
      <div class="rp-section-head"><h2>Education</h2></div>
      <div class="rp-education"><strong>Ph.D. in Computer Engineering</strong><br>Rochester Institute of Technology · In progress<br><br><strong>B.Sc. in Electrical Engineering</strong><br>Shahjalal University of Science and Technology, Sylhet, Bangladesh · 2022</div>
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
