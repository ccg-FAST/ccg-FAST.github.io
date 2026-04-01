---
layout: default
title: HD2 Survey
---

<div class="page-header">
    <div class="container">
        <h1 class="page-title">The FAST Hundred-deg² HI Deep (HD²) Survey</h1>
        <p class="page-subtitle">Deep HI Survey of 100 Square Degrees</p>
    </div>
</div>

<div class="container">
    <!-- Survey Navigation -->
    <nav class="survey-nav">
        <a href="{{ '/hd2/' | relative_url }}" class="survey-nav-link active">Overview</a>
        <a href="{{ '/hd2/science' | relative_url }}" class="survey-nav-link">Science</a>
        <a href="{{ '/hd2/observation' | relative_url }}" class="survey-nav-link">Observation</a>
        <a href="{{ '/hd2/publications' | relative_url }}" class="survey-nav-link">Publications</a>
        <a href="{{ '/hd2/data' | relative_url }}" class="survey-nav-link">Data</a>
    </nav>

    <!-- Overview -->
    <section class="content-section">
        <h2 class="section-title">Survey Overview</h2>
        
        <p>The <strong>FAST-HD² Survey</strong> (Hundred-deg² HI Deep Survey) is a medium-area deep neutral hydrogen (HI) survey carried out with the Five-hundred-meter Aperture Spherical Telescope (FAST). The full survey is designed to map a contiguous <strong>~100 deg²</strong> region within the DESI DR1 footprint, achieving an effective integration time of 20 minutes per beam and a uniform detection sensitivity of 0.28 mJy beam⁻¹ at 4.8 km s⁻¹ resolution. </p>

            
        <div style="text-align: center; margin-bottom: var(--space-8);">
            <img src="{{ '/assets/images/hd2_logo.png' | relative_url }}" alt="HD2 Logo" style="max-width: 400px; height: auto;">
        </div>
        
        <div class="info-box">
            <h3 class="info-box-title">Survey Highlights</h3>
            <ul>
                <li><strong>Full survey area:</strong> ~100 deg² (pilot: 10 deg²)</li>
                <li><strong>Full survey sensitivity:</strong> 0.28 mJy beam⁻¹ at 4.8 km s⁻¹</li>
                <li><strong>Redshift coverage:</strong> z &lt; 0.4 </li>
                <li><strong>Beam size:</strong> ~2.9 arcmin at 1.42 GHz (19-beam receiver)</li>
                <li><strong>Minimum frequency resolution:</strong> 7.6 kHz (1.6 km s⁻¹ at z = 0)</li>
                <li><strong>Expected HI detection number density:</strong> more than 30 per deg² </li>
            </ul>
        </div>
    </section>
    
    <!-- Science Goals -->
    <section class="content-section">
        <h2 class="section-title">Key Science Goals</h2>
        
        <div class="card-grid">
            <div class="card">
                <div class="card-header">
                    <div class="card-icon">📊</div>
                    <h3 class="card-title">HI Mass Function</h3>
                </div>
                <div class="card-body">
                    <p class="card-text">Extend the faint end of the HI mass function. FAST's superior sensitivity enables detection of low-mass, gas-rich dwarf galaxies that elude shallower surveys.</p>
                </div>
            </div>
            
            <div class="card">
                <div class="card-header">
                    <div class="card-icon">🌌</div>
                    <h3 class="card-title">Large-Scale Structure</h3>
                </div>
                <div class="card-body">
                    <p class="card-text">Map the spatial distribution and clustering of HI galaxies across ~100 deg² within the DESI DR1 footprint. The survey volume balances cosmic variance and statistical power, providing a robust sample for studying HI in the cosmic web and Bootes Void.</p>
                </div>
            </div>

            <div class="card">
                <div class="card-header">
                    <div class="card-icon">🔗</div>
                    <h3 class="card-title">DESI Synergy & Scaling Relations</h3>
                </div>
                <div class="card-body">
                    <p class="card-text">Combine HI detections and spectral stacking with DESI DR1 redshifts to measure HI gas fractions across stellar mass, color, SFR, and environment.</p>
                </div>
            </div>
            
            <div class="card">
                <div class="card-header">
                    <div class="card-icon">🌫️</div>
                    <h3 class="card-title">Rare & Exotic Populations</h3>
                </div>
                <div class="card-body">
                    <p class="card-text">Uncover rare systems invisible to shallow surveys: ultra-diffuse galaxies (UDGs), low surface brightness galaxies, HI-rich early-type galaxies, and dark gas clouds (RELHICs — Reionization-Limited HI Clouds) with no optical counterpart.</p>
                </div>
            </div>

            <div class="card">
                <div class="card-header">
                    <div class="card-icon">📡</div>
                    <h3 class="card-title">Cosmic HI Density &amp; Intensity Mapping</h3>
                </div>
                <div class="card-body">
                    <p class="card-text">Constrain Ω<sub>HI</sub> out to z ~ 0.3 via HI spectral stacking and intensity mapping. FAST's depth enables detection of the average HI signal from faint galaxy populations across cosmic time.</p>
                </div>
            </div>

            <div class="card">
                <div class="card-header">
                    <div class="card-icon">🏠</div>
                    <h3 class="card-title">HI–Halo Mass Relation</h3>
                </div>
                <div class="card-body">
                    <p class="card-text">Stack HI spectra of galaxy groups from the DESI Legacy Survey group catalog to measure the HI–halo mass relation and compare with simulations. This links neutral gas reservoirs to dark matter halos across a wide range of environments.</p>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Quick Links -->
    <section class="content-section">
        <h2 class="section-title">Quick Links</h2>
        
        <div class="card-grid">
            <a href="{{ '/hd2/science' | relative_url }}" class="card" style="text-decoration: none; color: inherit;">
                <div class="card-header">
                    <div class="card-icon">🔬</div>
                    <h3 class="card-title">Science Goals</h3>
                </div>
                <div class="card-body">
                    <p class="card-text">Detailed description of the scientific objectives and expected outcomes.</p>
                </div>
            </a>
            
            <a href="{{ '/hd2/observation' | relative_url }}" class="card" style="text-decoration: none; color: inherit;">
                <div class="card-header">
                    <div class="card-icon">📡</div>
                    <h3 class="card-title">Observations</h3>
                </div>
                <div class="card-body">
                    <p class="card-text">Observation strategy, setup, and current progress.</p>
                </div>
            </a>
            
            <a href="{{ '/hd2/publications' | relative_url }}" class="card" style="text-decoration: none; color: inherit;">
                <div class="card-header">
                    <div class="card-icon">📄</div>
                    <h3 class="card-title">Publications</h3>
                </div>
                <div class="card-body">
                    <p class="card-text">Papers and publications resulting from the HD2 survey.</p>
                </div>
            </a>
            
            <a href="{{ '/hd2/data' | relative_url }}" class="card" style="text-decoration: none; color: inherit;">
                <div class="card-header">
                    <div class="card-icon">💾</div>
                    <h3 class="card-title">Data Products</h3>
                </div>
                <div class="card-body">
                    <p class="card-text">Download catalogs, spectra, and other data products.</p>
                </div>
            </a>
        </div>
    </section>
    
    <!-- Contact -->
    <section class="content-section">
        <h2 class="section-title">Contact</h2>
        <p>For questions about the HD2 survey, please contact the survey PI or visit our <a href="{{ '/people' | relative_url }}">people page</a>.</p>
    </section>
</div>
