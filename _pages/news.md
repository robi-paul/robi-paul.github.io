---
layout: single
title: ""
permalink: /news/
author_profile: false
classes: wide
---

<style>
/* Hide sidebar ONLY on the News page */
body:has(.full-news-page) .sidebar {
  display: none !important;
}

/* Remove Academic Pages content width restrictions */
body:has(.full-news-page) #main {
  max-width: none !important;
  width: 100% !important;
  padding: 0 !important;
  margin: 0 !important;
}

body:has(.full-news-page) .page {
  width: 100% !important;
  max-width: none !important;
  padding: 0 !important;
  margin: 0 !important;
  float: none !important;
}

body:has(.full-news-page) .page__inner-wrap {
  width: 100% !important;
  max-width: none !important;
  margin: 0 !important;
}

body:has(.full-news-page) .page__content {
  width: 100% !important;
  max-width: none !important;
  padding: 0 !important;
  margin: 0 !important;
}

body:has(.full-news-page) .page__title {
  display: none !important;
}

/* Full news page */
.full-news-page {
  width: 100%;
  margin: 0;
  padding: 0;
}

/* Full-width dark hero */
.full-news-hero {
  background: #0d1523;
  color: #ffffff;
  width: 100%;
  padding: 85px 30px 65px;
  box-sizing: border-box;
}

.full-news-container {
  max-width: 980px;
  width: 100%;
  margin: 0 auto;
}

.full-news-label {
  font-size: 12px;
  letter-spacing: 3px;
  color: #9da9ba;
  margin-bottom: 15px;
}

.full-news-hero h1 {
  color: #ffffff !important;
  font-size: 48px;
  font-weight: 750;
  margin: 0 0 18px;
  line-height: 1.2;
}


.full-news-hero p {
  font-family: Georgia, "Times New Roman", serif;
  font-size: 20px;
  font-weight: 400;
  font-style: normal;
  color: #b8c0cd;
  line-height: 1.8;
  letter-spacing: 0.2px;
  max-width: 850px;
  margin: 0;
}


/* Full-width light background */
.full-news-body {
  background: #f2f4ef;
  color: #17212b;
  width: 100%;
  min-height: 65vh;
  padding: 75px 30px 110px;
  box-sizing: border-box;
}

/* News rows */
.full-news-item {
  display: grid;
  grid-template-columns: 105px minmax(0, 1fr);
  gap: 35px;
  border-top: 1px solid #cfd6d0;
  padding: 28px 0;
  align-items: start;
}

.full-news-item:last-child {
  border-bottom: 1px solid #cfd6d0;
}

/* Date column */
.full-news-date {
  color: #788591;
  font-size: 12px;
  letter-spacing: 1px;
  padding-top: 5px;
  font-weight: 500;
  text-transform: uppercase;
}

/* News heading */
.full-news-title {
  font-size: 19px;
  line-height: 1.4;
  font-weight: 700;
  color: #16202a;
  margin: 0 0 6px;
}

/* News description */
.full-news-description {
  color: #46515d;
  font-size: 16px;
  line-height: 1.7;
  margin: 0;
  font-family: Georgia, serif;
}

.full-news-description a {
  color: #007e9e;
  text-decoration: underline;
}

/* Optional photo */
.full-news-image {
  width: 170px;
  max-width: 100%;
  height: auto;
  border-radius: 3px;
  float: left;
  margin: 3px 25px 12px 0;
}

/* Mobile responsive */
@media (max-width: 700px) {
  .full-news-hero {
    padding: 55px 22px;
  }

  .full-news-hero h1 {
    font-size: 32px;
  }

  .full-news-body {
    padding: 40px 22px 70px;
  }

  .full-news-item {
    grid-template-columns: 1fr;
    gap: 10px;
  }

  .full-news-title {
    font-size: 18px;
  }

  .full-news-description {
    font-size: 15px;
  }
}
</style>

<div class="full-news-page">

  <!-- FULL WIDTH HEADER -->
  <section class="full-news-hero">
    <div class="full-news-container">

      <div class="full-news-label">NEWS</div>

      <h1>What's been happening</h1>

      <p>
        Research publications, academic achievements,
        and the latest updates on my work.
      </p>

    </div>
  </section>

  <!-- FULL WIDTH NEWS CONTENT -->
  <section class="full-news-body">
    <div class="full-news-container">

      <!-- OCTOBER 2026 -->
      <article class="full-news-item">
        <div class="full-news-date">
          OCT 2026
        </div>
        <div>
          <h2 class="full-news-title">
            Paper Accepted to ACM JETC
          </h2>
          <p class="full-news-description">
            Our research paper has been accepted to
            the ACM Journal on Emerging Technologies
            in Computing Systems.
          </p>
        </div>
      </article>

      <!-- SEPTEMBER 2026 -->
      <article class="full-news-item">
        <div class="full-news-date">
          SEP 2026
        </div>
        <div>
          <h2 class="full-news-title">
            Paper Accepted to IEEE TCAD
          </h2>
          <p class="full-news-description">
            Our research paper has been accepted to
            IEEE Transactions on Computer-Aided Design
            of Integrated Circuits and Systems.
          </p>
        </div>
      </article>

      <!-- OCTOBER 2025 -->
      <article class="full-news-item">
        <div class="full-news-date">
          OCT 2025
        </div>
        <div>
          <h2 class="full-news-title">
            Paper Accepted to IEEE TCAD
          </h2>
          <p class="full-news-description">
            A new research paper has been accepted to
            IEEE Transactions on Computer-Aided Design
            of Integrated Circuits and Systems.
          </p>
        </div>
      </article>

      <!-- DECEMBER 2024 -->
      <article class="full-news-item">
        <div class="full-news-date">
          DEC 2024
        </div>
        <div>
          <h2 class="full-news-title">
            Paper Accepted to Journal of Hardware
            and Systems Security
          </h2>
          <p class="full-news-description">
            Our research paper has been accepted to
            the Journal of Hardware and Systems
            Security.
            <a href="https://robi-paul.github.io/files/adjoining_gate_jhass.pdf">
              Read Paper
            </a>
          </p>
        </div>
      </article>

      <!-- NOVEMBER 2024 -->
      <article class="full-news-item">
        <div class="full-news-date">
          NOV 2024
        </div>
        <div>
          <h2 class="full-news-title">
            Paper Accepted to IEEE HOST 2025
          </h2>
          <p class="full-news-description">
            Our research paper has been accepted to
            the IEEE International Symposium on
            Hardware Oriented Security and Trust
            (HOST 2025).
            <a href="https://robi-paul.github.io/files/michscan_host.pdf">
              Read Paper
            </a>
          </p>
        </div>
      </article>

    </div>
  </section>

</div>
