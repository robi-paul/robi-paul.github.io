
---
layout: single
title: ""
permalink: /publications/
author_profile: false
classes: wide
---

<style>

/* =========================================
   REMOVE SIDEBAR AND THEME WIDTH LIMITS
========================================= */

body:has(.full-publications-page) .sidebar {
  display: none !important;
}

body:has(.full-publications-page) #main,
body:has(.full-publications-page) .page,
body:has(.full-publications-page) .page__inner-wrap,
body:has(.full-publications-page) .page__content {
  width: 100% !important;
  max-width: none !important;
  padding: 0 !important;
  margin: 0 !important;
}

body:has(.full-publications-page) .page {
  float: none !important;
}

body:has(.full-publications-page) .page__title {
  display: none !important;
}

/* =========================================
   MAIN PAGE
========================================= */

.full-publications-page {
  width: 100%;
  margin: 0;
  padding: 0;
}

.pub-container {
  max-width: 980px;
  width: 100%;
  margin: 0 auto;
}

/* =========================================
   DARK HEADER
========================================= */

.pub-hero {
  background: #0d1523;
  color: #ffffff;
  width: 100%;
  padding: 85px 30px 65px;
  box-sizing: border-box;
}

.pub-hero-label {
  font-size: 12px;
  letter-spacing: 3px;
  color: #9da9ba;
  margin-bottom: 15px;
  text-transform: uppercase;
}

.pub-hero h1 {
  color: #ffffff !important;
  font-size: 48px;
  font-weight: 750;
  line-height: 1.2;
  margin: 0;
}

/* =========================================
   LIGHT PUBLICATIONS AREA
========================================= */

.pub-body {
  background: #f2f4ef;
  color: #17212b;
  width: 100%;
  min-height: 70vh;
  padding: 75px 30px 110px;
  box-sizing: border-box;
}

/* =========================================
   YEAR GROUPS
========================================= */

.pub-year-group {
  margin-bottom: 48px;
}

.pub-year {
  color: #df6a21;
  font-family: monospace;
  font-size: 13px;
  font-weight: 500;
  letter-spacing: 2px;
  margin: 0 0 4px;
  padding-top: 16px;
  border-top: 1px solid #cfd6d0;
}

/* =========================================
   PUBLICATION ROW
========================================= */

.pub-item {
  display: grid;
  grid-template-columns: minmax(0, 1fr) auto;
  column-gap: 25px;
  align-items: start;
  padding: 22px 0;
  border-bottom: 1px solid #d9ded9;
}

.pub-item:last-child {
  border-bottom: none;
}

.pub-details {
  min-width: 0;
}

/* Publication title */

.pub-title {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 17px;
  font-weight: 700;
  color: #17212b;
  line-height: 1.45;
  margin: 0 0 6px;
}

/* Authors */

.pub-authors {
  font-family: Georgia, "Times New Roman", serif;
  font-size: 15px;
  line-height: 1.6;
  color: #46515d;
  margin: 0 0 5px;
}

.pub-myname {
  font-weight: 700;
  color: #17212b;
}

/* Journal or conference */

.pub-venue {
  font-family: Georgia, "Times New Roman", serif;
  font-style: italic;
  font-size: 15px;
  line-height: 1.6;
  color: #788591;
  margin: 0;
}

/* =========================================
   DOI AND PDF LINKS
========================================= */

.pub-links {
  display: flex;
  gap: 15px;
  align-items: center;
  justify-content: flex-end;
  padding-top: 5px;
  white-space: nowrap;
}

.pub-links a {
  font-family: monospace;
  font-size: 11px;
  font-weight: 500;
  letter-spacing: 1.5px;
  color: #788591;
  text-decoration: none;
  border-bottom: 1px solid #cfd6d0;
  padding-bottom: 3px;
}

.pub-links a:hover {
  color: #df6a21;
  border-bottom-color: #df6a21;
}

/* =========================================
   RESPONSIVE DESIGN
========================================= */

@media (max-width: 700px) {

  .pub-hero {
    padding: 55px 22px;
  }

  .pub-hero h1 {
    font-size: 34px;
  }

  .pub-body {
    padding: 40px 22px 70px;
  }

  .pub-item {
    grid-template-columns: 1fr;
    gap: 12px;
  }

  .pub-title {
    font-size: 16px;
  }

  .pub-authors,
  .pub-venue {
    font-size: 14px;
  }

  .pub-links {
    justify-content: flex-start;
    padding-top: 0;
  }

}

</style>


<div class="full-publications-page">

  <!-- =====================================
       FULL-WIDTH HEADER
  ====================================== -->

  <section class="pub-hero">

    <div class="pub-container">

      <div class="pub-hero-label">
        PUBLICATIONS
      </div>

      <h1>The work</h1>

    </div>

  </section>


  <!-- =====================================
       PUBLICATIONS CONTENT
  ====================================== -->

  <section class="pub-body">

    <div class="pub-container">


      <!-- =================================
           YEAR 2026
      ================================== -->

      <section class="pub-year-group">

        <h2 class="pub-year">2026</h2>


        <!-- SBLLocking -->

        <article class="pub-item">

          <div class="pub-details">

            <h3 class="pub-title">
              SBLLocking: Localization of Optical
              Side-Channel Leakage in Logic-Locked
              Integrated Circuits through
              Structure-based Learning
            </h3>

            <p class="pub-authors">
              Yuyang Wang,
              <span class="pub-myname">Robi Paul</span>,
              Michael Zuzak
            </p>

            <p class="pub-venue">
              ACM Journal on Emerging Technologies
              in Computing Systems, 2026
            </p>

          </div>

          <div class="pub-links">

            <a
              href="https://doi.org/10.1145/3861159"
              target="_blank"
              rel="noopener noreferrer"
            >DOI</a>

          </div>

        </article>


        <!-- DSMLock -->

        <article class="pub-item">

          <div class="pub-details">

            <h3 class="pub-title">
              DSMLock: Low Overhead Logic Locking
              for System Security With Design
              Space Modeling
            </h3>

            <p class="pub-authors">
              <span class="pub-myname">Robi Paul</span>,
              Long Lam,
              Maksym Melnyk,
              Michael Zuzak
            </p>

            <p class="pub-venue">
              IEEE Transactions on Computer-Aided
              Design of Integrated Circuits and
              Systems, vol. 45, no. 6,
              pp. 3030–3042, 2026
            </p>

          </div>

          <div class="pub-links">

            <a
              href="https://doi.org/10.1109/TCAD.2025.3623550"
              target="_blank"
              rel="noopener noreferrer"
            >DOI</a>

          </div>

        </article>


        <!-- RadScan: replace with complete title
             and authors when available -->

        <article class="pub-item">

          <div class="pub-details">

            <h3 class="pub-title">
              RadScan
            </h3>

            <p class="pub-authors">
              Author details to be added
            </p>

            <p class="pub-venue">
              IEEE Transactions on Computer-Aided
              Design of Integrated Circuits and
              Systems, accepted 2026
            </p>

          </div>

          <div class="pub-links">
          </div>

        </article>

      </section>


      <!-- =================================
           YEAR 2025
      ================================== -->

      <section class="pub-year-group">

        <h2 class="pub-year">2025</h2>


        <!-- MichScan -->

        <article class="pub-item">

          <div class="pub-details">

            <h3 class="pub-title">
              MichScan: Black-Box Neural Network
              Integrity Checking at Runtime
              Through Power Analysis
            </h3>

            <p class="pub-authors">
              <span class="pub-myname">Robi Paul</span>,
              Michael Zuzak
            </p>

            <p class="pub-venue">
              IEEE International Symposium on
              Hardware Oriented Security and Trust
              (HOST), 2025
            </p>

          </div>

          <div class="pub-links">

            <a
              href="{{ '/files/MichScan.pdf' | relative_url }}"
              target="_blank"
              rel="noopener noreferrer"
            >PDF</a>

          </div>

        </article>


        <!-- Adjoining Gates / JHSS -->

        <article class="pub-item">

          <div class="pub-details">

            <h3 class="pub-title">
              Mitigating Electro-Optical Frequency
              Mapping Attacks on Logic-Locked
              Integrated Circuits
            </h3>

            <p class="pub-authors">
              Thomas Wojtal,
              <span class="pub-myname">Robi Paul</span>,
              Michael Zuzak
            </p>

            <p class="pub-venue">
              Journal of Hardware and Systems
              Security, 2025
            </p>

          </div>

          <div class="pub-links">

            <a
              href="https://doi.org/10.1007/s41635-025-00158-w"
              target="_blank"
              rel="noopener noreferrer"
            >DOI</a>

            <a
              href="{{ '/files/adjoining_gate_jhass.pdf' | relative_url }}"
              target="_blank"
              rel="noopener noreferrer"
            >PDF</a>

          </div>

        </article>

      </section>


    </div>

  </section>

</div>
