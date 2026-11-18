---
layout: single
title: ""
permalink: /contact/
author_profile: false
classes: wide
---

<style>

/* =========================================
   HIDE SIDEBAR ON CONTACT PAGE ONLY
========================================= */

body:has(.full-contact-page) .sidebar {
  display: none !important;
}

body:has(.full-contact-page) #main {
  max-width: none !important;
  width: 100% !important;
  padding: 0 !important;
  margin: 0 !important;
}

body:has(.full-contact-page) .page {
  width: 100% !important;
  max-width: none !important;
  padding: 0 !important;
  margin: 0 !important;
  float: none !important;
}

body:has(.full-contact-page) .page__inner-wrap {
  width: 100% !important;
  max-width: none !important;
  margin: 0 !important;
}

body:has(.full-contact-page) .page__content {
  width: 100% !important;
  max-width: none !important;
  padding: 0 !important;
  margin: 0 !important;
}

body:has(.full-contact-page) .page__title {
  display: none !important;
}

/* =========================================
   PAGE LAYOUT
========================================= */

.full-contact-page {
  width: 100%;
  margin: 0;
  padding: 0;
}

.full-contact-container {
  max-width: 980px;
  width: 100%;
  margin: 0 auto;
}

/* =========================================
   DARK HEADER
========================================= */

.full-contact-hero {
  background: #0d1523;
  color: #ffffff;
  width: 100%;
  padding: 85px 30px 65px;
  box-sizing: border-box;
}

.full-contact-label {
  font-size: 12px;
  letter-spacing: 3px;
  color: #9da9ba;
  margin-bottom: 15px;
}

.full-contact-hero h1 {
  font-family: Arial, Helvetica, sans-serif;
  color: #ffffff !important;
  font-size: 48px;
  font-weight: 750;
  line-height: 1.2;
  margin: 0 0 18px;
}

.full-contact-hero p {
  font-family: Georgia, "Times New Roman", serif;
  font-size: 20px;
  font-weight: 400;
  color: #b8c0cd;
  line-height: 1.8;
  letter-spacing: 0.2px;
  max-width: 750px;
  margin: 0;
}

/* =========================================
   LIGHT CONTACT SECTION
========================================= */

.full-contact-body {
  background: #f2f4ef;
  color: #17212b;
  width: 100%;
  min-height: 65vh;
  padding: 90px 30px 120px;
  box-sizing: border-box;
}

/* =========================================
   TWO-COLUMN CONTACT LAYOUT
========================================= */

.contact-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  column-gap: 100px;
  row-gap: 50px;
  align-items: start;
}

/* =========================================
   CONTACT SECTIONS
========================================= */

.contact-section {
  margin-bottom: 45px;
}

.contact-section-label {
  font-family: monospace;
  font-size: 12px;
  font-weight: 500;
  letter-spacing: 2px;
  color: #788591;
  text-transform: uppercase;
  margin: 0 0 18px;
}

.contact-name {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 19px;
  font-weight: 700;
  color: #17212b;
  margin: 0 0 12px;
}

.contact-text {
  font-family: Georgia, "Times New Roman", serif;
  font-size: 17px;
  line-height: 1.8;
  color: #46515d;
  margin: 0;
}

.contact-text strong {
  color: #17212b;
}

/* =========================================
   CONTACT LINKS
========================================= */

.contact-link-list {
  display: flex;
  flex-direction: column;
  gap: 18px;
}

.contact-link {
  display: flex;
  align-items: center;
  gap: 12px;
  text-decoration: none !important;
  color: #17212b !important;
  font-family: Arial, Helvetica, sans-serif;
  font-size: 15px;
  font-weight: 500;
  transition: color 0.2s ease;
}

.contact-link:hover {
  color: #007e9e !important;
}

.contact-link-icon {
  width: 22px;
  min-width: 22px;
  color: #007e9e;
  text-align: center;
  font-size: 18px;
}

.contact-link-text {
  border-bottom: 1px solid #cfd6d0;
  padding-bottom: 4px;
}

.contact-link:hover .contact-link-text {
  border-bottom-color: #007e9e;
}

/* =========================================
   RESEARCH INTEREST SECTION
========================================= */

.contact-research {
  border-top: 1px solid #cfd6d0;
  padding-top: 28px;
}

.contact-research-title {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 19px;
  font-weight: 700;
  color: #17212b;
  margin: 0 0 12px;
}

.contact-research p {
  font-family: Georgia, "Times New Roman", serif;
  font-size: 16px;
  line-height: 1.8;
  color: #46515d;
  margin: 0 0 18px;
}

/* =========================================
   EMAIL BUTTON
========================================= */

.contact-email-button {
  display: inline-block;
  background: #0d1523;
  color: #ffffff !important;
  font-family: Arial, Helvetica, sans-serif;
  font-size: 14px;
  font-weight: 600;
  padding: 12px 22px;
  border-radius: 3px;
  text-decoration: none !important;
  transition: background 0.2s ease;
}

.contact-email-button:hover {
  background: #007e9e;
  color: #ffffff !important;
}

/* =========================================
   MOBILE RESPONSIVE
========================================= */

@media (max-width: 700px) {

  .full-contact-hero {
    padding: 55px 22px;
  }

  .full-contact-hero h1 {
    font-size: 34px;
  }

  .full-contact-hero p {
    font-size: 17px;
  }

  .full-contact-body {
    padding: 50px 22px 80px;
  }

  .contact-grid {
    grid-template-columns: 1fr;
    gap: 15px;
  }

  .contact-section {
    margin-bottom: 35px;
  }

  .contact-text {
    font-size: 16px;
  }

  .contact-link {
    font-size: 14px;
  }

}

</style>


<div class="full-contact-page">

  <!-- =====================================
       FULL-WIDTH HEADER
  ====================================== -->

  <section class="full-contact-hero">

    <div class="full-contact-container">

      <div class="full-contact-label">
        CONTACT
      </div>

      <h1>Get in touch</h1>

      <p>
        I'm always happy to connect about research,
        collaborations, and academic opportunities.
      </p>

    </div>

  </section>


  <!-- =====================================
       CONTACT CONTENT
  ====================================== -->

  <section class="full-contact-body">

    <div class="full-contact-container">

      <div class="contact-grid">


        <!-- =================================
             LEFT COLUMN
        ================================== -->

        <div>

          <!-- AFFILIATION -->

          <section class="contact-section">

            <h2 class="contact-section-label">
              AFFILIATION
            </h2>

            <h3 class="contact-name">
              Robi Paul
            </h3>

            <p class="contact-text">
              Ph.D. Student<br>
              Department of Computer Engineering<br>
              Rochester Institute of Technology<br>
              Rochester, New York, USA
            </p>

          </section>


          <!-- RESEARCH AREAS -->

          <section class="contact-section">

            <h2 class="contact-section-label">
              RESEARCH AREAS
            </h2>

            <p class="contact-text">
              Hardware Security<br>
              Side-Channel Analysis<br>
              Machine Learning Security<br>
              Digital VLSI/CAD
            </p>

          </section>

        </div>


        <!-- =================================
             RIGHT COLUMN
        ================================== -->

        <div>

          <!-- DIRECT CONTACT -->

          <section class="contact-section">

            <h2 class="contact-section-label">
              DIRECT
            </h2>

            <div class="contact-link-list">

              <!-- EMAIL -->

              <a
                href="mailto:rp7248@rit.edu"
                class="contact-link"
              >
                <span class="contact-link-icon">
                  ✉
                </span>

                <span class="contact-link-text">
                  rp7248@rit.edu
                </span>
              </a>


              <!-- GOOGLE SCHOLAR -->

              <a
                href="https://scholar.google.com/citations?user=7Z14CtUAAAAJ"
                target="_blank"
                rel="noopener noreferrer"
                class="contact-link"
              >
                <span class="contact-link-icon">
                  🎓
                </span>

                <span class="contact-link-text">
                  Google Scholar
                </span>
              </a>


              <!-- GITHUB -->

              <a
                href="https://github.com/robi-paul"
                target="_blank"
                rel="noopener noreferrer"
                class="contact-link"
              >
                <span class="contact-link-icon">
                  ⌘
                </span>

                <span class="contact-link-text">
                  GitHub
                </span>
              </a>

            </div>

          </section>


          <!-- RESEARCH COLLABORATION -->

          <section class="contact-research">

            <h2 class="contact-research-title">
              Research & Collaboration
            </h2>

            <p>
              I welcome discussions on hardware
              security, side-channel analysis,
              and security challenges in
              machine learning systems.
            </p>

            <p>
              Feel free to reach out by email
              regarding research discussions,
              potential collaborations, or
              academic opportunities.
            </p>

            <a
              href="mailto:rp7248@rit.edu"
              class="contact-email-button"
            >
              Send an Email
            </a>

          </section>

        </div>


      </div>

    </div>

  </section>

</div>
