---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

<section class="cv-intro">
  <div>
    <p class="profile-eyebrow">Updated April 2026</p>
    <h2>Xiangyu Cui</h2>
    <p>Ph.D. student in Electrical and Computer Engineering at New York University Abu Dhabi, currently based in New York.</p>
  </div>
  <div class="cv-intro__actions">
    <a class="btn btn--primary" href="/files/Xiangyu_Cui_CV_April_2026.pdf"><i class="fa-solid fa-file-pdf icon-pad-right" aria-hidden="true"></i>Download CV</a>
    <a class="btn btn--inverse" href="mailto:xc3212@nyu.edu"><i class="fa-solid fa-envelope icon-pad-right" aria-hidden="true"></i>Email</a>
  </div>
</section>

<section class="cv-section">
  <h2>Education</h2>
  <div class="cv-item">
    <div class="cv-item__header">
      <h3>New York University Abu Dhabi</h3>
      <span>Aug. 2025 - Present</span>
    </div>
    <p>Ph.D., supervised by Prof. Qurrat-Ul-Ain Nadeem. Abu Dhabi, UAE; New York, US.</p>
  </div>
  <div class="cv-item">
    <div class="cv-item__header">
      <h3>King Abdullah University of Science and Technology (KAUST)</h3>
      <span>Aug. 2023 - Jul. 2025</span>
    </div>
    <p>M.S. with Thesis in Electrical and Computer Engineering, supervised by Prof. Mohamed-Slim Alouini. GPA: 4.00/4.00. Thuwal, Saudi Arabia.</p>
  </div>
  <div class="cv-item">
    <div class="cv-item__header">
      <h3>University of Electronic Science and Technology of China (UESTC)</h3>
      <span>Sept. 2019 - Jul. 2023</span>
    </div>
    <p>B.Eng. in Communication Engineering. GPA: 3.93/4.00. Chengdu, China.</p>
  </div>
</section>

<section class="cv-section">
  <h2>Research Experience</h2>
  <div class="cv-item">
    <div class="cv-item__header">
      <h3>Channel Power Gain Analysis and Orientation Optimization for CAPA Systems</h3>
      <span>Aug. 2025 - Apr. 2026</span>
    </div>
    <p class="item-meta">Advisor: Prof. Qurrat-Ul-Ain Nadeem | New York University Abu Dhabi</p>
    <ul>
      <li>Studied point-to-point continuous aperture array (CAPA) systems where transmit and receive apertures are modeled as continuous current distributions rather than discrete antenna elements.</li>
      <li>Derived a semi-closed-form expression for near-field channel power gain under a dyadic Green's function based channel model with polarization effects.</li>
      <li>Analyzed how CAPA orientation, aperture size, propagation distance, and transceiver misalignment affect received channel gain.</li>
      <li>Showed that optimal Tx/Rx aperture orientation is not always parallel and depends on the relative geometry between the two CAPAs.</li>
      <li>Validated the expression through numerical simulations with substantially lower computational complexity than direct integral evaluation and densely sampled discrete MIMO approximation.</li>
    </ul>
  </div>

  <div class="cv-item">
    <div class="cv-item__header">
      <h3>Channel Capacity Saturation and Beamforming Acceleration for Near-Field XL-MIMO</h3>
      <span>Aug. 2024 - Jul. 2025</span>
    </div>
    <p class="item-meta">Advisor: Prof. Mohamed-Slim Alouini | CTL, KAUST</p>
    <ul>
      <li>Investigated capacity saturation in near-field XL-MIMO multiuser communications, showing that excessive array growth can lead to marginal capacity improvement.</li>
      <li>Derived analytical criteria for determining the capacity saturation point and choosing practical array sizes.</li>
      <li>Proposed a low-complexity beamforming algorithm that reduces computational burden while maintaining near-optimal performance around the saturation point.</li>
      <li>Validated the theoretical analysis and beamforming design through numerical simulations for near-field multiuser XL-MIMO systems.</li>
      <li>Published the work in IEEE Wireless Communications Letters.</li>
    </ul>
  </div>

  <div class="cv-item">
    <div class="cv-item__header">
      <h3>Near-Field Performance Analysis for XL-MIMO</h3>
      <span>Aug. 2023 - Sept. 2024</span>
    </div>
    <p class="item-meta">Advisor: Prof. Mohamed-Slim Alouini | CTL, KAUST</p>
    <ul>
      <li>Analyzed extremely large-scale MIMO systems where conventional far-field assumptions become inaccurate.</li>
      <li>Summarized existing received SNR results for several near-field wave models and derived generalized received-power expressions for different channel models and array structures.</li>
      <li>Derived closed-form approximations for user-channel correlation using the stationary phase method.</li>
      <li>Applied received-power and correlation results to analyze multi-user XL-MIMO uplink sum rate.</li>
      <li>Modified a previous user-selection algorithm using analytical results, achieving significant speed-up while maintaining the same sum-rate performance.</li>
      <li>Published the work in IEEE Open Journal of the Communications Society.</li>
    </ul>
  </div>

  <div class="cv-item">
    <div class="cv-item__header">
      <h3>Performance Analysis of OAM Communication under Random Misalignment</h3>
      <span>Apr. 2022 - Jul. 2023</span>
    </div>
    <p class="item-meta">Advisor: Prof. Mohamed-Slim Alouini | CTL, KAUST</p>
    <ul>
      <li>Analyzed millimeter-wave orbital angular momentum (OAM) communication systems under practical random transceiver misalignment.</li>
      <li>Derived closed-form intensity expressions for given misalignment values in indoor and outdoor propagation scenarios.</li>
      <li>Evaluated average channel capacity under two-dimensional Gaussian random misalignment and validated the analysis through numerical simulations.</li>
      <li>Used Gauss-Laguerre quadrature to reduce computational complexity in capacity evaluation under realistic misalignment distributions.</li>
      <li>Published the work in IEEE Open Journal of the Communications Society.</li>
    </ul>
  </div>

  <div class="cv-item">
    <div class="cv-item__header">
      <h3>Specific Emitter Identification Using RF Hardware Impairments</h3>
      <span>Jan. 2022 - Jun. 2022</span>
    </div>
    <p class="item-meta">Team Project | UESTC</p>
    <ul>
      <li>Developed a specific emitter identification system that distinguished transmitters using physical-layer hardware fingerprints, including IQ imbalance and carrier leakage.</li>
      <li>Built a signal processing pipeline with digital down-conversion, FIR low-pass filtering, Costas carrier synchronization, and Gardner timing synchronization.</li>
      <li>Modeled transmitter impairments through gain imbalance, quadrature phase error, and carrier leakage, and estimated features using maximum-likelihood and statistical-property-based methods.</li>
      <li>Trained SVM classifiers with One-vs-One multi-class classification and grid-searched hyperparameters, achieving approximately 98% transmitter identification accuracy in testing.</li>
    </ul>
  </div>
</section>

<section class="cv-section">
  <h2>Publications</h2>
  <ol class="publication-list">
    <li>X. Cui, K.-H. Park, and M.-S. Alouini, "Channel Capacity Saturation Point and Beamforming Acceleration for Near-Field XL-MIMO Multiuser Communications," <em>IEEE Wireless Communications Letters</em>, vol. 15, pp. 1390-1394, 2026.</li>
    <li>X. Cui, K.-H. Park, and M.-S. Alouini, "Near-Field Analysis of Extremely Large-Scale MIMO: Power, Correlation, and User Selection," <em>IEEE Open Journal of the Communications Society</em>, vol. 6, pp. 252-270, 2024.</li>
    <li>X. Cui, K.-H. Park, and M.-S. Alouini, "Effect of Random Misalignment in the Capacity of Millimeter-Wave OAM," <em>IEEE Open Journal of the Communications Society</em>, vol. 5, pp. 1141-1154, 2024.</li>
  </ol>
</section>

<section class="cv-section compact">
  <h2>Conferences</h2>
  <ul>
    <li>4th KAUST 6G Summit, Thuwal, Saudi Arabia, Nov. 27-29, 2023.</li>
    <li>5th KAUST 6G Summit, Thuwal, Saudi Arabia, Nov. 4-5, 2024.</li>
    <li>Abu Dhabi 6G Summit, Abu Dhabi, UAE, Nov. 14-15, 2024.</li>
    <li>IEEE Communication Theory Workshop (CTW), Murano, Venice, Italy, May 4-7, 2025.</li>
  </ul>
</section>

<section class="cv-section compact">
  <h2>Honors and Awards</h2>
  <ul>
    <li>National Scholarship of China (Top 1%), Dec. 2020 and Nov. 2021.</li>
    <li>Excellent Student Scholarship of UESTC, Dec. 2020 and Nov. 2021.</li>
    <li>First Prize, Electronic Design Contest of UESTC, Nov. 2019.</li>
    <li>Third Prize, National Electronic Design Contest, Sichuan Province, Oct. 2020.</li>
    <li>First Prize, National College Students Mobile Communication 5G Technology Contest, Sichuan Province, May 2020.</li>
    <li>Excellent Prize, National College Students Mobile Communication 5G Technology Contest, Jul. 2020.</li>
  </ul>
</section>

<section class="cv-section">
  <h2>Technical Skills</h2>
  <div class="skill-cloud">
    <span>C</span>
    <span>MATLAB</span>
    <span>Python</span>
    <span>LaTeX</span>
    <span>Mathematica</span>
    <span>Keil5</span>
    <span>PyTorch</span>
    <span>Wireless communication</span>
    <span>Near-field communication</span>
    <span>XL-MIMO</span>
    <span>Continuous aperture arrays</span>
  </div>
</section>
