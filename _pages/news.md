---
layout: single
title: ""
permalink: /news/
author_profile: true
---

<style>
/* News page container */
.custom-news {
  width: 100%;
  margin-top: 10px;
  font-family: inherit;
}

/* Dark header */
.news-hero {
  background: #101827;
  color: #ffffff;
  padding: 55px 35px;
  margin-bottom: 0;
}

.news-hero .news-label {
  color: #92a0b3;
  font-size: 12px;
  letter-spacing: 3px;
  text-transform: uppercase;
  margin-bottom: 12px;
}

.news-hero h1 {
  color: #ffffff !important;
  font-size: 36px;
  font-weight: 750;
  line-height: 1.2;
  margin: 0 0 14px;
}

.news-hero p {
  color: #bfc7d2;
  font-size: 16px;
  line-height: 1.7;
  margin: 0;
}

/* Light news area */
.news-content {
  background: #f5f6f2;
  color: #17212b;
  padding: 35px;
}

/* Individual news rows */
.news-entry {
  display: grid;
  grid-template-columns: 110px minmax(0, 1fr);
  gap: 22px;
  padding: 25px 0;
  border-top: 1px solid #d4d9d5;
}

.news-entry:last-child {
  border-bottom: 1px solid #d4d9d5;
}

/* Date */
.news-date {
  color: #72808c;
  font-size: 12px;
  font-weight: 600;
  letter-spacing: 1px;
  text-transform: uppercase;
  padding-top: 4px;
}

/* Headline */
.news-title {
  font-size: 18px;
  font-weight: 700;
  color: #17212b;
  line-height: 1.4;
  margin: 0 0 8px;
}

/* Description */
.news-description {
  font-size: 15px;
  line-height: 1.7;
  color: #45515b;
  margin: 0;
}

/* PDF and other links */
.news-description a {
  color: #007d9c;
  text-decoration: underline;
}

/* Optional news images */
.news-image {
  max-width: 200px;
  width: 100%;
  height: auto;
  margin-top: 12px;
  border-radius: 4px;
}

/* Mobile layout */
@media (max-width: 600px) {
  .news-hero {
    padding: 35px 20px;
  }

  .news-hero h1 {
    font-size: 28px;
  }

  .news-content {
    padding: 20px;
  }

  .news-entry {
    grid-template-columns: 1fr;
    gap: 8px;
    padding: 22px 0;
  }

  .news-title {
    font-size: 17px;
  }
}
</style>

<div class="custom-news">

  <!-- Page header -->
  <header class="news-hero">
    <div class="news-label">NEWS</div>
    <h1>What's been happening</h1>
    <p>
      Research publications, academic achievements,
      and the latest updates on my work.
    </p>
  </header>

  <!-- News feed -->
  <div class="news-content">

    <!-- October 2026 -->
    <article class="news-entry">
      <div class="news-date">OCT 2026</div>
      <div>
        <h2 class="news-title">
          Paper Accepted to ACM JETC
        </h2>
        <p class="news-description">
          Our research paper has been accepted to
          the ACM Journal on Emerging Technologies
          in Computing Systems.
        </p>
      </div>
    </article>

    <!-- September 2026 -->
    <article class="news-entry">
      <div class="news-date">SEP 2026</div>
      <div>
        <h2 class="news-title">
          Paper Accepted to IEEE TCAD
        </h2>
        <p class="news-description">
          Our research paper has been accepted to
          IEEE Transactions on Computer-Aided Design
          of Integrated Circuits and Systems.
        </p>
      </div>
    </article>

    <!-- October 2025 -->
    <article class="news-entry">
      <div class="news-date">OCT 2025</div>
      <div>
        <h2 class="news-title">
          Paper Accepted to IEEE TCAD
        </h2>
        <p class="news-description">
          A new research paper has been accepted to
          IEEE Transactions on Computer-Aided Design
          of Integrated Circuits and Systems.
        </p>
      </div>
    </article>

    <!-- December 2024 -->
    <article class="news-entry">
      <div class="news-date">DEC 2024</div>
      <div>
        <h2 class="news-title">
          Paper Accepted to Journal of Hardware
          and Systems Security
        </h2>
        <p class="news-description">
          Our research paper has been accepted to
          the Journal of Hardware and Systems
          Security.
          <a href="https://robi-paul.github.io/files/adjoining_gate_jhass.pdf">
            Read Paper
          </a>
        </p>
      </div>
    </article>

    <!-- November 2024 -->
    <article class="news-entry">
      <div class="news-date">NOV 2024</div>
      <div>
        <h2 class="news-title">
          Paper Accepted to IEEE HOST 2025
        </h2>
        <p class="news-description">
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
</div>
