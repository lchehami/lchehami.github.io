---
show: true
width: 12
date: 2024-01-12 00:01:00 +0800

images:

  - src: https://www.mdpi.com/sensors/sensors-25-01067/article_deploy/html/images/sensors-25-01067-g012-550.jpg
    title: Surface Waves
    desc: SAW generation using interdigital transducers.

  - src: https://ultrananotec.com/wp-content/uploads/2022/10/SKU-108-a-9.jpg
    title: Silicon Wafer
    desc: Thin-film and silicon wafer characterization using guided ultrasonic waves.

  - src: https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQBxzoZ2c4UbBU03oEyxvKp_0hymLDJJV7lbw&s
    title: DACLOS
    desc: Diffuse wave generation and passive imaging in reverberant media.
    link: https://anr.fr/Projet-ANR-21-CE42-0002

---

<div class="p-4">

<div class="row align-items-start">

    <!-- LEFT COLUMN -->
    <div class="col-lg-7">

        <h2>ANR JCJC DACLOS</h2>

        <h5>
            Diffuse Acoustic Wave Correlation for Layer-On-Substrate Structures
        </h5>

        <div class="text-center my-4">
            <img src="https://www.logotheque-vectorielle.fr/wp-content/uploads/2022/10/logo-vectoriel-anr.jpg"
                 alt="ANR Logo"
                 class="img-fluid rounded-xl"
                 style="
                    max-width: 260px;
                    height: auto;
                    background: white;
                    padding: 18px;
                    border-radius: 14px;
                 ">
        </div>

        <hr />

        <p>
            The ANR JCJC <strong>DACLOS</strong> project investigates diffuse acoustic
            wave correlations and passive imaging approaches for complex
            Layer-on-Substrate (LOS) structures encountered in microelectronics
            and advanced materials.
        </p>

        <p>
            The project focuses on the propagation of high-frequency diffuse
            Rayleigh wavefields and their interaction with defects such as
            delaminations, adhesion losses, cracks, and thickness inhomogeneities
            in thin-film and wafer structures.
        </p>

        <p>
            DACLOS explores innovative methodologies combining diffuse wave
            correlation, guided ultrasonic waves, reverberant wavefields,
            signal processing, and passive Green’s function retrieval for
            nondestructive evaluation and structural health monitoring.
        </p>

        <hr />

        <h5>Funding</h5>

        <p>
            <strong>Agence Nationale de la Recherche (ANR)</strong><br>
            JCJC Young Researcher Project<br>
            Project reference: ANR-21-CE42-0002<br>
            Duration: March 2022 – August 2025<br>
            ANR funding: <strong>172 400 €</strong>
        </p>

        <hr />

        <h5>Coordination</h5>

        <ul>
            <li>
                <strong>Lynda Chehami</strong> – Principal Investigator
            </li>
        </ul>

        <hr />

        <h5>Main Research Topics</h5>

        <ul>
            <li>Diffuse wave correlation</li>
            <li>Passive Green’s function retrieval</li>
            <li>Guided ultrasonic waves</li>
            <li>High-frequency Rayleigh waves</li>
            <li>Thin-film and wafer characterization</li>
            <li>Structural health monitoring</li>
            <li>Nondestructive evaluation (NDT/NDE)</li>
        </ul>

        <hr />

        <h5>Wave Correlation Principle</h5>

        <p>
            In a diffuse or reverberant elastic wavefield, the cross-correlation
            between signals recorded at two receivers can be used to retrieve
            the Green’s function between these two points. This principle is at
            the core of passive imaging approaches developed in DACLOS.
        </p>

        <hr />

        <p class="small">
            Official ANR project:
            <a href="https://anr.fr/Projet-ANR-21-CE42-0002" target="_blank">
                ANR-21-CE42-0002 – DACLOS
            </a>
        </p>

    </div>

    <!-- RIGHT COLUMN -->
    <div class="col-lg-5">

        <div class="sticky-top pt-3" style="top: 90px;">

            <!-- SCIENTIFIC HERO -->
            <div class="scientific-hero position-relative mb-4 rounded-xl overflow-hidden shadow-sm"
                 style="
                    min-height: 520px;
                    background-image:
                      linear-gradient(
                        rgba(255,255,255,0.78),
                        rgba(255,255,255,0.78)
                      ),
                      url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQB0XfW-a7Qieuu-SFgf22lSmwtvO1JhadqANUMSw-2wA&s');

                    background-size: cover;
                    background-position: center;
                    background-repeat: no-repeat;
                    padding: 40px;
                    color: #111;
                 ">

                <div style="
                    position: relative;
                    z-index: 2;
                    color: #111;
                ">

                    <h5 style="color:#111; font-weight:700;">
                        Diffuse Wave Correlation
                    </h5>

                    <p style="color:#111; line-height:1.7;">
                        Passive imaging approach based on the cross-correlation of reverberated
                        wavefields recorded at different receiver positions. In diffuse media,
                        the correlation function converges toward the Green's function of the
                        structure, enabling passive characterization and imaging.
                    </p>

                    <div class="text-center small mt-3" style="color:#111;">
                        $$
                        C_{AB}(\tau)=\int_{0}^{T}u_A(t)\,u_B(t+\tau)\,dt
                        $$
                    </div>

                    <div class="p-4 text-center" style="color:#111;">
                        $$
                        \frac{\partial}{\partial t} C_{AB}(t)
                        \propto
                        G_{AB}(t) - G_{AB}(-t)
                        $$
                    </div>

                </div>

            </div>

            <!-- PROJECT GALLERY -->
            {% include widgets/carousel.html
               id="daclos-gallery"
               images=page.images
               height="420px" %}

        </div>

    </div>

</div>

</div>
