---
layout: single
title: ""
permalink: /news/
author_profile: false
classes: wide
---

<style>

/* =========================================
   HIDE SIDEBAR ON NEWS PAGE ONLY
========================================= */

body:has(.full-news-page) .sidebar {
  display: none !important;
}

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

/* =========================================
   PAGE LAYOUT
========================================= */

.full-news-page {
  width: 100%;
  margin: 0;
  padding: 0;
}

.full-news-container {
  max-width: 980px;
  width: 100%;
  margin: 0 auto;
}

/* =========================================
   DARK HEADER
========================================= */

.full-news-hero {
  background: #0d1523;
  color: #ffffff;
  width: 100%;
  padding: 85px 30px 65px;
  box-sizing: border-box;
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

/* =========================================
   LIGHT NEWS SECTION
========================================= */

.full-news-body {
  background: #f2f4ef;
  color: #17212b;
  width: 100%;
  min-height: 65vh;
  padding: 75px 30px 110px;
  box-sizing: border-box;
}

/* =========================================
   THREE-COLUMN NEWS LAYOUT
========================================= */

.full-news-item {
  display: grid;
  grid-template-columns: 105px 150px minmax(0, 1fr);
  column-gap: 28px;
  align-items: start;
  border-top: 1px solid #cfd6d0;
  padding: 28px 0;
}

.full-news-item:last-child {
  border-bottom: 1px solid #cfd6d0;
}

/* Date */

.full-news-date {
  color: #788591;
  font-size: 12px;
  letter-spacing: 1px;
  padding-top: 5px;
  font-weight: 500;
  text-transform: uppercase;
}

/* Image */

.full-news-image {
  width: 150px;
  height: 105px;
  object-fit: contain;
  background: #ffffff;
  border-radius: 3px;
  display: block;
  margin: 0;
}

/* News text container */

.full-news-details {
  min-width: 0;
}

/* News headline */

.full-news-title {
  font-size: 19px;
  line-height: 1.4;
  font-weight: 700;
  color: #16202a;
  margin: 0 0 8px;
}

/* News description */

.full-news-description {
  color: #46515d;
  font-size: 16px;
  line-height: 1.7;
  margin: 0;
  font-family: Georgia, "Times New Roman", serif;
}

/* Paper links */

.full-news-description a {
  color: #007e9e;
  text-decoration: underline;
}

.full-news-description a:hover {
  color: #005d75;
}

/* =========================================
   RESPONSIVE DESIGN
========================================= */

/* Tablet */

@media (max-width: 850px) {

  .full-news-item {
    grid-template-columns: 85px 120px minmax(0, 1fr);
    column-gap: 18px;
  }

  .full-news-image {
    width: 120px;
    height: 90px;
  }

  .full-news-title {
    font-size: 18px;
  }

}

/* Mobile */

@media (max-width: 600px) {

  .full-news-hero {
    padding: 55px 22px;
  }

  .full-news-hero h1 {
    font-size: 32px;
  }

  .full-news-hero p {
    font-size: 17px;
  }

  .full-news-body {
    padding: 40px 22px 70px;
  }

  .full-news-item {
    grid-template-columns: 1fr;
    gap: 14px;
    padding: 25px 0;
  }

  .full-news-date {
    padding-top: 0;
  }

  .full-news-image {
    width: 170px;
    height: auto;
    max-height: 120px;
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

  <!-- =====================================
       FULL-WIDTH HEADER
  ====================================== -->

  <section class="full-news-hero">

    <div class="full-news-container">

      <div class="full-news-label">
        NEWS
      </div>

      <h1>What's been happening</h1>

      <p>
        Research publications, academic achievements.
      </p>

    </div>

  </section>


  <!-- =====================================
       NEWS CONTENT
  ====================================== -->

  <section class="full-news-body">

    <div class="full-news-container">


      <!-- =================================
           OCTOBER 2026 - ACM JETC
      ================================== -->

      <article class="full-news-item">

        <div class="full-news-date">
          27 OCT 2026
        </div>

        <img
          src="{{ '/images/Jetc.png' | relative_url }}"
          alt="ACM JETC announcement placeholder"
          class="full-news-image"
          loading="lazy"
        >

        <div class="full-news-details">

          <h2 class="full-news-title">
            Paper Accepted to ACM JETC
          </h2>

          <p class="full-news-description">
            Our paper <strong>SBLLocking: Localization of Optical Side-Channel Leakage in Logic-Locked Integrated Circuits through Structure-based Learning</strong> has been accepted to
            the ACM Journal on Emerging Technologies
            in Computing Systems.
            <a href="https://robi-paul.github.io/files/SBLLocking.pdf">
              Read Paper
            </a>
          </p>

        </div>

      </article>


      <!-- =================================
           NEW IEEE TCAD PAPER SLOT
           BEFORE IEEE TIFS
      ================================== -->

      <article class="full-news-item">

        <div class="full-news-date">
          6 SEP 2026
        </div>

        <img
          src="{{ '/images/tcad.png' | relative_url }}"
          alt="IEEE TCAD journal"
          class="full-news-image"
          loading="lazy"
        >

        <div class="full-news-details">

          <h2 class="full-news-title">
            Paper Accepted to IEEE TCAD
          </h2>

          <p class="full-news-description">
            Our paper <strong>Physical Reservoir Computing with Electric Double Layer Transistors for Anomaly Detection using Power Analysis</strong>
            has been accepted to
            IEEE Transactions on Computer-Aided Design
            of Integrated Circuits and Systems.
            <a href="https://robi-paul.github.io/files/RadScan.pdf">
              Read Paper
            </a>
          </p>

        </div>

      </article>


      <!-- =================================
           FEBRUARY 2026 - IEEE TIFS
      ================================== -->

      <article class="full-news-item">

        <div class="full-news-date">
          1 Feb 2026
        </div>

        <img
          src="{{ '/images/Tifs.png' | relative_url }}"
          alt="IEEE TIFS journal"
          class="full-news-image"
          loading="lazy"
        >

        <div class="full-news-details">

          <h2 class="full-news-title">
            Paper Accepted to IEEE TIFS
          </h2>

          <p class="full-news-description">
            Our paper <strong>AdvScan: Black-Box Adversarial Example Detection at Runtime through Power Analysis</strong> has been accepted to
            the IEEE Transactions on Information Forensics and Security.

            <a href="https://robi-paul.github.io/files/AdvScan.pdf">
              Read Paper
            </a>
          </p>

        </div>

      </article>


      <!-- =================================
           OCTOBER 2025 - IEEE TCAD
      ================================== -->

      <article class="full-news-item">

        <div class="full-news-date">
          11 OCT 2025
        </div>

        <img
          src="{{ '/images/tcad.png' | relative_url }}"
          alt="IEEE TCAD journal"
          class="full-news-image"
          loading="lazy"
        >

        <div class="full-news-details">

          <h2 class="full-news-title">
            Paper Accepted to IEEE TCAD
          </h2>

          <p class="full-news-description">
            Our paper <strong>DSMLock: Low Overhead Logic Locking for System Security with Design Space Modeling</strong> has been accepted to
            the IEEE Transactions on Computer-Aided Design
            of Integrated Circuits and Systems.

            <a href="https://robi-paul.github.io/files/DSMLock.pdf">
              Read Paper
            </a>
          </p>

        </div>

      </article>


      <!-- =================================
           DECEMBER 2024 - IEEE HOST 2025
      ================================== -->

      <article class="full-news-item">

        <div class="full-news-date">
          8 DEC 2024
        </div>

        <img
          src="{{ '/images/host2025.png' | relative_url }}"
          alt="IEEE HOST 2025 Conference and Expo"
          class="full-news-image"
          loading="lazy"
        >

        <div class="full-news-details">

          <h2 class="full-news-title">
            Paper Accepted to IEEE HOST 2025
          </h2>

          <p class="full-news-description">
            Our paper <strong>Michscan: Black-Box Neural Network Integrity Checking at Runtime Through Power Analysis</strong> has been accepted to
            the IEEE International Symposium on
            Hardware Oriented Security and Trust
            (HOST 2025).

            <a href="https://robi-paul.github.io/files/MichScan.pdf">
              Read Paper
            </a>
          </p>

        </div>

      </article>


      <!-- =================================
           NOVEMBER 2024 - JHSS
      ================================== -->

      <article class="full-news-item">

        <div class="full-news-date">
          20 Nov 2024
        </div>

        <img
          src="{{ '/images/jhass.png' | relative_url }}"
          alt="Journal of Hardware and Systems Security"
          class="full-news-image"
          loading="lazy"
        >

        <div class="full-news-details">

          <h2 class="full-news-title">
            Paper Accepted to Journal of Hardware
            and Systems Security
          </h2>

          <p class="full-news-description">
            Our paper <strong>Mitigating Electro-Optical Frequency Mapping Attacks on Logic-Locked Integrated Circuits</strong> has been accepted to
            the Journal of Hardware and Systems
            Security.

            <a href="https://robi-paul.github.io/files/adjoining_gate_jhass.pdf">
              Read Paper
            </a>
          </p>

        </div>

      </article>


    </div>

  </section>

</div>
