---
layout: default
title: Home
---

<!-- Hero Section -->
<section class="hero">
    <div class="container">
        <h1 class="hero-title">HI Survey conducted by CCG@NAOC</h1>
        <p class="hero-subtitle">Medium-coverage HI Deep surveys with the Five-hundred-meter Aperture Spherical radio Telescope (FAST), by Computational Cosmology Group @ NAOC</p>
        <div class="hero-actions">
            <a href="{{ '/hd2/' | relative_url }}" class="btn btn-primary">The FAST Hundred-deg² HI Deep (HD²) Survey</a>
            <a href="{{ '/m31/' | relative_url }}" class="btn btn-secondary">The FAST M31 HI Deep Survey</a>
        </div>
    </div>
</section>

<!-- About HI Surveys -->
<section class="container">
    <div class="content-section">
        <h2 class="section-title">About HI Surveys</h2>
        
        <p>Neutral hydrogen (HI) is the most abundant element in the universe and serves as a fundamental tracer of cosmic structure. The 21-cm hyperfine transition line of HI provides a unique window into the distribution, kinematics, and physical conditions of gas in galaxies, enabling studies of galaxy formation, evolution, and cosmology.</p>
        
        <p>The <a href="https://fast.bao.ac.cn/" target="_blank" rel="noopener">FAST</a> (Five-hundred-meter Aperture Spherical radio Telescope), located in Guizhou Province, China, is the world's largest single-dish radio telescope. With its unprecedented sensitivity and large collecting area, FAST opens new frontiers for HI astronomy, allowing us to probe fainter and more distant HI emissions than ever before.</p>
        
        <div class="info-box">
            <h3 class="info-box-title">Why FAST for HI?</h3>
            <ul>
                <li><strong>World-leading sensitivity:</strong> 300m effective aperture provides unmatched collecting area</li>
                <li><strong>Wide frequency coverage:</strong> 1.0 - 1.5 GHz for the L band receiver, covering redshifted HI lines to z = 0.4 </li>
                <li><strong>19-beam receiver:</strong> Efficient large-area surveys with the L-band array</li>
                <li><strong>Excellent sky coverage:</strong> Accessible to declinations between -14° and +66°</li>
            </ul>
        </div>
    </div>
</section>

<!-- HI Survey Comparison -->
<section class="container">
    <div class="content-section">
        <h2 class="section-title">HI Survey Landscape</h2>
        
        <p>Current HI surveys span a wide range of sky coverage and depth, each optimized for different scientific goals. Wide-field surveys like <a href="http://egg.astro.cornell.edu/alfalfa/" target="_blank" rel="noopener">ALFALFA</a> (Arecibo Legacy Fast ALFA) and <a href="https://fashi.bao.ac.cn/" target="_blank" rel="noopener">FASHI</a> (FAST All Sky HI Survey) cover thousands of square degrees with moderate sensitivity, providing large statistical samples but limited to nearby galaxies (z ≲ 0.06). At the other extreme, ultra-deep surveys like <a href="https://www.atnf.csiro.au/research/AUDS/" target="_blank" rel="noopener">AUDS</a> (ASKAP Ultra Deep Survey) and <a href="https://www.atnf.csiro.au/research/FUDS/" target="_blank" rel="noopener">FUDS</a> (FAST Ultra Deep Survey) target very small areas (a few deg²) with hundreds of hours of integration, reaching high redshifts (z ~ 0.4) but may suffer from cosmic variance.</p>
        
        <p>Medium-area deep surveys fill the critical gap between these extremes. <a href="https://www.atnf.csiro.au/research/DINGO/" target="_blank" rel="noopener">DINGO</a> (Deep Investigation of Neutral Gas Origins) with ASKAP will cover 60–150 deg², while <a href="https://www.mighteesurvey.org/" target="_blank" rel="noopener">MIGHTEE-HI</a> (MeerKAT International GHz Tiered Extragalactic Exploration) and the <a href="https://www.sarao.ac.za/science/meerkat-science/meerkat-fornax-survey/" target="_blank" rel="noopener">MeerKAT Fornax Survey</a> each probe ~32 deg² and ~12 deg² respectively. These surveys offer a balance between volume and sensitivity, enabling studies of rare populations and environmental effects that are inaccessible to both wide shallow surveys and ultra-deep pencil beams.</p>

        <p>However, these interferometric surveys are still limited in sensitivity compared to single-dish telescopes. To overcome this limitation, we have initiated two complementary medium-area deep HI surveys with FAST: the <strong>HD²</strong> (Hundred-deg² HI Deep) Survey targeting extragalactic HI in a 100 deg² field overlapped with DESI, and the <strong>M31</strong> survey for resolved HI mapping in the 160 kpc radius of M31 halo. Their survey parameters—spatial resolution, sky coverage, and column density sensitivity—are compared with other HI surveys in the figure below.</p>
        
        <div class="figure-container" style="text-align: center; margin: 2rem 0;">
            <img src="assets/images/surveys.png" alt="HI Survey Comparison" style="max-width: 100%; height: auto; border-radius: 8px; box-shadow: 0 4px 6px rgba(0,0,0,0.1);">
            <p class="figure-caption" style="margin-top: 1rem; font-size: 0.95rem; line-height: 1.6; color: #666;">
                <strong>Figure:</strong> Comparison of HI surveys in terms of spatial resolution vs. column density sensitivity (left) and sky coverage vs. column density sensitivity (right). Our surveys (red squares) occupies a unique parameter space, combining arcminute-scale spatial resolution with hundreds of deg² sky coverage while achieving deep column density limits of log N<sub>HI</sub> ~ 17.5 cm<sup>-2</sup> at 20 km s<sup>-1</sup> resolution — a balance unmatched by wide-field shallow surveys or ultra-deep surveys.
            </p>
        </div>

        <div class="info-box">
            <h3 class="info-box-title">Why conduct HD² and M31 Surveys with FAST?</h3>
            <ul>
                <li><strong>Unmatched Sensitivity:</strong> FAST achieves sensitivity two orders of magnitude deeper than interferometric surveys, enabling detection of faint, extended HI emission missed by ASKAP and MeerKAT</li>
                <li><strong>Optimal Survey Volume:</strong> ~100 deg² strikes the balance between cosmic variance and statistical power, providing robust samples for galaxy evolution studies</li>
                <li><strong>Synergy with DESI:</strong> Deep optical spectroscopy from DESI enables precise optical counterpart identification and redshift confirmation, with matching rates exceeding 90% for r < 19.5 mag galaxies</li>
                <li><strong>Low-Mass Galaxy Census:</strong> Extend HI detections to stellar masses down to 10⁸ M⊙, constraining the faint end of the HI mass function and gas accretion in dwarf galaxies</li>
                <li><strong>Rare Population Discovery:</strong> Optimal for finding ultra-diffuse galaxies, low surface brightness systems, HI-rich early-types, and dark gas clouds (RELIHCs) that evade shallow surveys</li>
                <li><strong>Local Group Benchmark:</strong> The M31 survey provides resolved HI mapping of our nearest major neighbor's halo region, serving as a fundamental calibration for cosmological simulations and galaxy formation models</li>
            </ul>
        </div>
    </div>
</section>


<!-- Survey Projects -->
<section class="container">
    <div class="content-section">
        <h2 class="section-title">Our Survey Projects</h2>
        
        <div class="card-grid">
            <!-- HD2 Survey -->
            <div class="feature-card">
                <div class="feature-card-image">🔭</div>
                <div class="feature-card-content">
                    <h3 class="feature-card-title">HD² Survey</h3>
                    <p class="feature-card-description">
                        A deep HI survey covering 100 deg² within the DESI footprint, leveraging FAST's unmatched sensitivity and DESI's high-completeness spectroscopy to detect faint HI emissions from galaxies down to 10⁸ Msun.
                    </p>
                    <div class="feature-card-links">
                        <a href="{{ '/hd2/' | relative_url }}" class="btn btn-outline">Overview</a>
                        <a href="{{ '/hd2/science' | relative_url }}" class="btn btn-outline">Science</a>
                        <a href="{{ '/hd2/publications' | relative_url }}" class="btn btn-outline">Publications</a>
                        <a href="{{ '/hd2/data' | relative_url }}" class="btn btn-outline">Data</a>
                    </div>
                </div>
            </div>
            
            <!-- M31 Survey -->
            <div class="feature-card">
                <div class="feature-card-image">🌌</div>
                <div class="feature-card-content">
                    <h3 class="feature-card-title">M31 Survey</h3>
                    <p class="feature-card-description">
                        A 700 deg² HI survey of the Andromeda Galaxy (M31) and its halo within 160 kpc, mapping the detailed distribution of neutral gas in M31's disk and halo while simultaneously enabling studies of high-velocity clouds in the Milky Way and M31 halos, supernova remnants, and serving as an extragalactic point-source survey for background HI galaxies..
                    </p>
                    <div class="feature-card-links">
                        <a href="{{ '/m31/' | relative_url }}" class="btn btn-outline">Overview</a>
                        <a href="{{ '/m31/science' | relative_url }}" class="btn btn-outline">Science</a>
                        <a href="{{ '/m31/publications' | relative_url }}" class="btn btn-outline">Publications</a>
                        <a href="{{ '/m31/data' | relative_url }}" class="btn btn-outline">Data</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- Research Focus -->
<section class="container">
    <div class="content-section">
        <h2 class="section-title">Research Focus</h2>
        
        <div class="card-grid">
            <div class="card">
                <div class="card-header">
                    <div class="card-icon">🌌</div>
                    <h3 class="card-title">Galaxy Formation & Evolution</h3>
                </div>
                <div class="card-body">
                    <p class="card-text">Investigating the low-redshift HI mass function, gas fraction scaling relations with stellar mass and star formation rate, and the role of HI as the fuel reservoir for star formation and baryon cycling in galaxies.</p>
                </div>
            </div>
            
            <div class="card">
                <div class="card-header">
                    <div class="card-icon">🔄</div>
                    <h3 class="card-title">HI Distribution & Galaxy Dynamics</h3>
                </div>
                <div class="card-body">
                    <p class="card-text">Mapping the spatial distribution of neutral hydrogen from galactic disks to extended halos, probing galaxy kinematics and mass distributions through HI rotation curves, including detailed mapping of M31's dynamics and circumgalactic medium.</p>
                </div>
            </div>
            
            <div class="card">
                <div class="card-header">
                    <div class="card-icon">💥</div>
                    <h3 class="card-title">Milky Way HI & Supernova Remnants</h3>
                </div>
                <div class="card-body">
                    <p class="card-text">Studying the Milky Way's neutral hydrogen distribution and its interaction with supernova remnants, using high-velocity cloud observations to trace feedback and gas recycling processes.</p>
                </div>
            </div>
            
            <div class="card">
                <div class="card-header">
                    <div class="card-icon">📡</div>
                    <h3 class="card-title">21cm Intensity Mapping</h3>
                </div>
                <div class="card-body">
                    <p class="card-text">Pushing toward cosmological applications by developing 21cm intensity mapping techniques at z ~ 0.3, bridging the gap between low-redshift HI surveys and future high-redshift cosmology experiments.</p>
                </div>
            </div>
        </div>
    </div>
</section>


<!-- Contact -->
<section class="container">
    <div class="content-section">
        <h2 class="section-title">Contact</h2>
        
        <p>For inquiries about our HI surveys, data access, or collaboration opportunities, please contact the CCG group or visit our <a href="{{ '/people' | relative_url }}">people page</a> for individual contact information.</p>
        
        <div class="alert alert-info">
            <strong>Data Access:</strong> Survey data products are available through the individual project pages. See <a href="{{ '/hd2/data' | relative_url }}">HD² Data</a> and <a href="{{ '/m31/data' | relative_url }}">M31 Data</a> for downloads.
        </div>
    </div>
</section>
