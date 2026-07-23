---
layout: archive
title: "Overview"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

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
    <p>M.S. with Thesis in Electrical and Computer Engineering, supervised by Prof. Mohamed-Slim Alouini. Thuwal, Saudi Arabia.</p>
    <p class="cv-gpa"><strong>GPA:</strong> 4.00/4.00</p>
  </div>
  <div class="cv-item">
    <div class="cv-item__header">
      <h3>University of Electronic Science and Technology of China (UESTC)</h3>
      <span>Sept. 2019 - Jul. 2023</span>
    </div>
    <p>B.Eng. in Communication Engineering. Chengdu, China.</p>
    <p class="cv-gpa"><strong>GPA:</strong> 3.93/4.00</p>
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
  <div class="overview-publications">
    <article class="overview-publication">
      <figure class="overview-publication__figure">
        <img src="/images/publications/capa-orientation-figure.png" alt="Geometry of two arbitrarily oriented continuous aperture arrays" loading="lazy">
        <figcaption>CAPA system geometry · Figure 1</figcaption>
      </figure>
      <div class="overview-publication__content">
        <p class="overview-publication__venue">IEEE Communications Letters · 2026</p>
        <h3 class="overview-publication__title"><a href="https://ieeexplore.ieee.org/document/11614098">Channel Power Gain Analysis and Orientation Optimization of a Point-to-Point Continuous Aperture Array (CAPA) System</a></h3>
        <p class="overview-publication__authors">X. Cui and Q.-U.-A. Nadeem</p>
        <h4 class="overview-publication__abstract-title">Abstract</h4>
        <p class="overview-publication__abstract">Continuous aperture arrays (CAPAs) revolutionize conventional multiple-input multiple-output (MIMO) architectures by modeling the radiating aperture as a continuous current distribution rather than a finite set of discrete elements. These spatially-continuous surfaces enable fine-grained manipulation of electromagnetic (EM) wavefronts to improve communication performance by increasing the channel gain and the available degrees-of-freedom (DoF). In contrast to existing literature that focuses on near-field DoF analysis, we derive a semi-closed-form expression for the near-field channel power gain (CPG) of a point-to-point CAPA-based communications system over the dyadic Green's function based channel, incorporating polarization effects. We show that the expression can dramatically decrease the computational complexity compared to evaluating the original integral-based formula, accelerating CPG-based analysis and optimization. We further use the derived expression to find the optimal orientations of transmit (Tx) and receive (Rx) CAPAs under different system geometries. Simulation results validate the accuracy and implementation speed of the derived expression. They further show that the optimal orientation is not always parallel, but varies depending on the relative misalignment and distance between Tx and Rx CAPAs.</p>
      </div>
    </article>

    <article class="overview-publication">
      <figure class="overview-publication__figure">
        <img src="/images/publications/capacity-saturation-figure-1.png" alt="Projected non-uniform spherical wave channel for a uniform linear array" loading="lazy">
        <figcaption>PNUSW channel model · Figure 1</figcaption>
      </figure>
      <div class="overview-publication__content">
        <p class="overview-publication__venue">IEEE Wireless Communications Letters · 2026</p>
        <h3 class="overview-publication__title"><a href="https://arxiv.org/abs/2503.18118">Channel Capacity Saturation Point and Beamforming Acceleration for Near-Field XL-MIMO Multiuser Communications</a></h3>
        <p class="overview-publication__authors">X. Cui, K.-H. Park, and M.-S. Alouini</p>
        <h4 class="overview-publication__abstract-title">Abstract</h4>
        <p class="overview-publication__abstract">One of the most important technologies in the fifth generation (5G) and the sixth generation (6G) is massive multiple input multiple outputs (MIMO) or extremely large-scale MIMO (XL-MIMO). With the evolving high-frequency technologies in millimeter band or teraHz band, the communication scene is changing into near-field rather than the conventional far-field scenario. In this letter, instead of advertising the XL-MIMO in the near-field, we appeal that a limit should be set on the size of the antenna array, beyond which the channel capacity will not show a significant increase. We show capacity saturation point can be analytically determined. Moreover, we propose a new beamforming algorithm that relieves the heavy computation due to the large antenna size even around the saturation point. Numerical results are provided to validate our analysis and show the performance of our newly proposed beamforming scheme.</p>
      </div>
    </article>

    <article class="overview-publication">
      <figure class="overview-publication__figure">
        <img src="/images/publications/near-field-xl-mimo-figure-2.png" alt="Uniform rectangular array geometry with two users" loading="lazy">
        <figcaption>URA system geometry · Figure 2</figcaption>
      </figure>
      <div class="overview-publication__content">
        <p class="overview-publication__venue">IEEE Open Journal of the Communications Society · 2024</p>
        <h3 class="overview-publication__title"><a href="https://ieeexplore.ieee.org/document/10810362">Near-Field Analysis of Extremely Large-Scale MIMO: Power, Correlation, and User Selection</a></h3>
        <p class="overview-publication__authors">X. Cui, K.-H. Park, and M.-S. Alouini</p>
        <h4 class="overview-publication__abstract-title">Abstract</h4>
        <p class="overview-publication__abstract">With the fast development of communication technology, mobile networks have been evolving from the fifth generation (5G) to the sixth generation (6G). One of the most important technologies in 5G is massive multiple input multiple output (MIMO). In 6G, it has been extended to extremely large-scale MIMO (XL-MIMO) over the TeraHz band, which makes it easier for users to fall into the near-field communication range. However, the previous performance analysis based on the far-field assumption can be very inaccurate under the near-field scenario. Hence, it is necessary to use the near-field channel models to redo these analyses. In this work, we summarize previous analytical results on received signal-to-noise ratio for specific near-field wave models. Then, we derive the generalized formula for the received power of different wave models and antenna structures. We newly derive our closed-form formula for the correlation between different users by the stationary phase method. These results can be applied to different beam-forming schemes and the multipath case. Based on these analytical results, we manage to make a sum rate analysis for different antenna arrays and near-field channel models in a multi-user XL-MIMO system. Finally, with the modification by our analytical result, we show a dramatic speed-up of the previous user selection algorithm, while reaching the same sum rate.</p>
      </div>
    </article>

    <article class="overview-publication">
      <figure class="overview-publication__figure">
        <img src="/images/publications/oam-misalignment-figure-1.png" alt="Geometric system model for misaligned orbital angular momentum transmitter and receiver arrays" loading="lazy">
        <figcaption>OAM misalignment model · Figure 1</figcaption>
      </figure>
      <div class="overview-publication__content">
        <p class="overview-publication__venue">IEEE Open Journal of the Communications Society · 2024</p>
        <h3 class="overview-publication__title"><a href="https://ieeexplore.ieee.org/abstract/document/10418466">Effect of Random Misalignment in the Capacity of Millimeter-Wave OAM</a></h3>
        <p class="overview-publication__authors">X. Cui, K.-H. Park, and M.-S. Alouini</p>
        <h4 class="overview-publication__abstract-title">Abstract</h4>
        <p class="overview-publication__abstract">Since the discovery of vortex beams by Allen et al., there has been a growing interest in exploring the applications of orbital angular momentum (OAM) in communication. Among all these researches, especially radio frequency (RF) wireless communication based on OAM should be one of the most promising research topics since the frequency resource is increasingly scarce and OAM can provide us with a new degree of freedom besides frequency, time, and space. In the context of wireless communication, millimeter wave and terahertz communication have gained extensive attention to harness spectrum resources. However, due to the short wavelength at these frequencies, line of sight (LOS) channels dominate. OAM, even in LOS channels, offers an additional degree of freedom compared to conventional multiple input multiple output systems. Yet, there are strict requirements for free-space OAM, one of which is the strict alignment between antenna arrays. To the best of our knowledge, there has not been any work about the capacity analysis of OAM communication under random misalignment. In this article, we obtain accurate closed-form intensity for a given misalignment value for both indoor and outdoor situations. Moreover, based on these intensity formulas, we analyze the average capacity under 2-D Gaussian random misalignment numerically and validate its accuracy by simulation. Besides, we illustrate that the Gauss-Laguerre quadrature can be used to reduce the computation complexity in the real environment. Moreover, we analyze the relationship between the average capacity and system parameters such as the array radii, signal-to-noise ratio, and misalignment distribution standard deviation for both indoor and outdoor situations. At last, we verify our work is also effective for the concentric circular array. This work could be a reference to the implementation of a practical RF OAM communication system.</p>
      </div>
    </article>
  </div>
</section>

<section class="cv-section compact">
  <h2>Conferences</h2>
  <ul>
    <li>IEEE Communication Theory Workshop (CTW), Murano, Venice, Italy, May 4-7, 2025.</li>
    <li>Abu Dhabi 6G Summit, Abu Dhabi, UAE, Nov. 14-15, 2024.</li>
    <li>5th KAUST 6G Summit, Thuwal, Saudi Arabia, Nov. 4-5, 2024.</li>
    <li>4th KAUST 6G Summit, Thuwal, Saudi Arabia, Nov. 27-29, 2023.</li>
  </ul>
</section>

<section class="cv-section compact">
  <h2>Academic Service</h2>
  <div class="reviewer-groups">
    <div class="reviewer-group">
      <h3>Journal Reviewer</h3>
      <ul>
        <li>IEEE Transactions on Communications</li>
        <li>IEEE Open Journal of the Communications Society</li>
        <li>IEEE Transactions on Mobile Computing</li>
      </ul>
    </div>
    <div class="reviewer-group">
      <h3>Conference Reviewer</h3>
      <ul>
        <li>2026 IEEE International Conference on Communications Workshops</li>
      </ul>
    </div>
  </div>
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
  <dl class="skill-table">
    <div>
      <dt>Languages</dt>
      <dd>C, MATLAB, Python, LaTeX</dd>
    </div>
    <div>
      <dt>Software</dt>
      <dd>MATLAB, Keil5, Mathematica</dd>
    </div>
    <div>
      <dt>Research Areas</dt>
      <dd>Wireless communication, near-field communication, XL-MIMO, continuous aperture arrays</dd>
    </div>
    <div>
      <dt>ML Framework</dt>
      <dd>PyTorch</dd>
    </div>
  </dl>
</section>
