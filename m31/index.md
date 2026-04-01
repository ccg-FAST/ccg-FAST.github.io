---
layout: default
title: M31 Survey
---

<div class="page-header">
    <div class="container">
        <h1 class="page-title">The FAST-M31 HI Deep Survey</h1>
        <p class="page-subtitle">HI Mapping to the halo region of the Andromeda Galaxy</p>
    </div>
</div>

<div class="container">
    <!-- Survey Navigation -->
    <nav class="survey-nav">
        <a href="{{ '/m31/' | relative_url }}" class="survey-nav-link active">Overview</a>
        <a href="{{ '/m31/science' | relative_url }}" class="survey-nav-link">Science</a>
        <a href="{{ '/m31/observation' | relative_url }}" class="survey-nav-link">Observation</a>
        <a href="{{ '/m31/publications' | relative_url }}" class="survey-nav-link">Publications</a>
        <a href="{{ '/m31/data' | relative_url }}" class="survey-nav-link">Data</a>
    </nav>
    
    <!-- Overview -->
    <section class="content-section">
        <h2 class="section-title">Survey Overview</h2>
        
        <p>The <strong>FAST-M31 Survey</strong> is a deep neutral hydrogen (HI) mapping project targeting the Andromeda Galaxy (M31) and its surrounding ~700 deg² halo region using the FAST telescope. The survey probes diffuse HI emission out to a projected radius of 160 kpc from M31's center, covering its satellite system, circumgalactic medium, and background extragalactic sources — making it the most sensitive wide-field HI survey of the Local Group to date.</p>

        <div class="figure-container" style="text-align: center; margin: var(--space-8) 0;">
            <img src="{{ '/assets/images/M31_halo.png' | relative_url }}" alt="M31 HI Halo Map" style="max-width: 100%; height: auto; border-radius: var(--radius-lg); box-shadow: var(--shadow-md);">
            <p class="figure-caption" style="margin-top: var(--space-2); font-style: italic; color: var(--text-muted);">
                FAST HI moment 0 map of the M31 halo region integrated over the velocity range of -630 to -50 km s⁻¹. (Credit: NAOC-CCG)
            </p>
        </div>

        <div class="info-box">
            <h3 class="info-box-title">Survey Highlights</h3>
            <ul>
                <li><strong>Target:</strong> M31 halo, satellites, HVCs, and background HI galaxies</li>
                <li><strong>Coverage:</strong> ~700 deg² (radius ~160 kpc from M31 center)</li>
                <li><strong>Radial velocity range:</strong> -1000 – 24,000 km s⁻¹ (z &lt; 0.08)</li>
                <li><strong>Map rms sensitivity:</strong> 0.8 mJy beam⁻¹ at 4.8 km s⁻¹</li>
                <li><strong>Beam size:</strong> ~2.9 arcmin at 1.42 GHz (~660 pc at M31)</li>
                <li><strong>Velocity resolution:</strong> 1.6 km s⁻¹ (W band), 4.8 km s⁻¹ (rebinned), 10 km s⁻¹ (Hann-smoothed)</li>
                <li><strong>Background HI detections:</strong> ~10,000 sources at z &lt; 0.08</li>
            </ul>
        </div>
    </section>
    
    <!-- Why M31 -->
    <section class="content-section">
        <h2 class="section-title">Why M31?</h2>
        
        <p>The Andromeda Galaxy offers unique advantages as a laboratory for resolved HI science in the Local Group:</p>
        
        <div class="card-grid">
            <div class="card">
                <div class="card-header">
                    <div class="card-icon">🎯</div>
                    <h3 class="card-title">Proximity</h3>
                </div>
                <div class="card-body">
                    <p class="card-text">At ~780 kpc, M31 is close enough to resolve individual HI features at ~660 pc per FAST beam — bridging the gap between resolved Local Group studies and distant galaxy surveys.</p>
                </div>
            </div>
            
            <div class="card">
                <div class="card-header">
                    <div class="card-icon">🌌</div>
                    <h3 class="card-title">Extended Halo</h3>
                </div>
                <div class="card-body">
                    <p class="card-text">FAST's large beam and single-dish sensitivity are ideal for detecting diffuse, extended HI emission in M31's halo and CGM — structures resolved out by interferometers like VLA and WSRT.</p>
                </div>
            </div>
            
            <div class="card">
                <div class="card-header">
                    <div class="card-icon">🔄</div>
                    <h3 class="card-title">Rich Interaction History</h3>
                </div>
                <div class="card-body">
                    <p class="card-text">M31's satellite system — including M33, NGC 205, Andromeda II, and dozens of dwarf galaxies — shows clear signs of tidal stripping and past interactions, traceable in HI at FAST's sensitivity.</p>
                </div>
            </div>
            
            <div class="card">
                <div class="card-header">
                    <div class="card-icon">📡</div>
                    <h3 class="card-title">Background Survey Bonus</h3>
                </div>
                <div class="card-body">
                    <p class="card-text">The deep integration over 700 deg² yields ~10,000 background HI galaxy detections — far exceeding ALFALFA and FASHI coverage in the same field — enabling independent cosmological studies.</p>
                </div>
            </div>
        </div>
    </section>
 
    
    <!-- Quick Links -->
    <section class="content-section">
        <h2 class="section-title">Quick Links</h2>
        
        <div class="card-grid">
            <a href="{{ '/m31/science' | relative_url }}" class="card" style="text-decoration: none; color: inherit;">
                <div class="card-header">
                    <div class="card-icon">🔬</div>
                    <h3 class="card-title">Science Goals</h3>
                </div>
                <div class="card-body">
                    <p class="card-text">Detailed description of the scientific objectives and expected outcomes.</p>
                </div>
            </a>
            
            <a href="{{ '/m31/observation' | relative_url }}" class="card" style="text-decoration: none; color: inherit;">
                <div class="card-header">
                    <div class="card-icon">📡</div>
                    <h3 class="card-title">Observations</h3>
                </div>
                <div class="card-body">
                    <p class="card-text">Observation strategy, setup, and current progress.</p>
                </div>
            </a>
            
            <a href="{{ '/m31/publications' | relative_url }}" class="card" style="text-decoration: none; color: inherit;">
                <div class="card-header">
                    <div class="card-icon">📄</div>
                    <h3 class="card-title">Publications</h3>
                </div>
                <div class="card-body">
                    <p class="card-text">Papers and publications resulting from the M31 survey.</p>
                </div>
            </a>
            
            <a href="{{ '/m31/data' | relative_url }}" class="card" style="text-decoration: none; color: inherit;">
                <div class="card-header">
                    <div class="card-icon">💾</div>
                    <h3 class="card-title">Data Products</h3>
                </div>
                <div class="card-body">
                    <p class="card-text">Download cubes, maps, and other data products.</p>
                </div>
            </a>
        </div>
    </section>
    
    <!-- Contact -->
    <section class="content-section">
        <h2 class="section-title">Contact</h2>
        <p>For questions about the M31 survey, please contact the survey PI or visit our <a href="{{ '/people' | relative_url }}">people page</a>.</p>
    </section>
</div>
