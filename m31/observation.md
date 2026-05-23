---
layout: default
title: M31 Observations
---

<div class="page-header">
    <div class="container">
        <h1 class="page-title">FAST-M31 Observations</h1>
        <p class="page-subtitle">Observation Strategy and Status</p>
    </div>
</div>

<div class="container">
    <!-- Survey Navigation -->
    <nav class="survey-nav">
        <a href="{{ '/m31/' | relative_url }}" class="survey-nav-link">Overview</a>
        <a href="{{ '/m31/science' | relative_url }}" class="survey-nav-link">Science</a>
        <a href="{{ '/m31/observation' | relative_url }}" class="survey-nav-link active">Observation</a>
        <a href="{{ '/m31/publications' | relative_url }}" class="survey-nav-link">Publications</a>
        <a href="{{ '/m31/data' | relative_url }}" class="survey-nav-link">Data</a>
    </nav>
    
    <!-- Survey Region -->
    <section class="content-section">
        <h2 class="section-title">Survey Region</h2>
        
        <p>The FAST-M31 survey targets a ~700 deg² region centered on the Andromeda Galaxy (M31), extending out to a projected radius of ~160 kpc. This area encompasses the M31 disk, its extensive halo, known satellite galaxies, and potential tidal structures connecting to M33. The region was selected to map the circumgalactic medium (CGM) of a major spiral galaxy with unprecedented sensitivity.</p>
        
        <div class="figure-container" style="text-align: center; margin: 2rem 0;">
            <img src="{{ '/assets/images/M31_area.png' | relative_url }}" alt="M31 Survey Footprint" style="max-width: 100%; height: auto; border-radius: 8px; box-shadow: 0 4px 6px rgba(0,0,0,0.1);">
            <p class="figure-caption" style="margin-top: 1rem; font-size: 0.95rem; line-height: 1.6; color: #666;">
                <strong>Figure:</strong> The M31 survey's observed sky region. The orange dashed line indicates the first-year sky coverage, with the second and third year coverage extending to the blue area. The red ellipses mark the locations of M31 and M33, while the red five-pointed star identifies the calibrator source 3C48. The purple circle denotes a 160 kpc radius from the center of M31. The green line at declination +36° represents the ALFALFA coverage limit (south of 36° only), which largely coincides with the background grayscale image showing SDSS g-band optical coverage. (<em>Credit: Xu, Yiwei & Xu, Chen in prep.</em>)
            </p>
        </div>
    </section>

    <!-- Observation Status -->
    <section class="content-section">
        <h2 class="section-title">Observation Status</h2>
        
        <table>
            <thead>
                <tr>
                    <th>Year</th>
                    <th>Area</th>
                    <th>Status</th>
                    <th>Period</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Y1 (ZD2021_4)</td>
                    <td>593 deg²</td>
                    <td>Complete</td>
                    <td>Sep 2021 – Feb 2022</td>
                </tr>
                <tr>
                    <td>Y2 (ZD2022_4)</td>
                    <td>685 deg²</td>
                    <td>Complete</td>
                    <td>Oct 2022 – Feb 2023</td>
                </tr>
                <tr>
                    <td>Y3 (ZD2023_4)</td>
                    <td>685 deg²</td>
                    <td>Complete</td>
                    <td>Sep 2023 – Feb 2024</td>
                </tr>
            </tbody>
        </table>
    </section>
    
    <!-- Observation Strategy -->
    <section class="content-section">
        <h2 class="section-title">Observation Strategy</h2>
        
        <h3 class="section-subtitle">Scanning Mode</h3>
        <p>The M31 survey uses FAST's 19-beam receiver in drift scan mode. The telescope remains stationary pointing at a fixed declination while Earth's rotation scans the sky, keeping the zenith angle constant and ensuring stable gain throughout each session. The receiver is rotated by 23.4° so that all 19 beams provide uniform Nyquist spatial sampling across the survey field. Each drift scan session lasts ~2.5 hours, with ~68 scans per pass and ~170 hours per year. The flux calibrator 3C 48 is observed every 10 days.</p>
        
        <h3 class="section-subtitle">Calibration</h3>
        <p>Data are processed using the <strong>HiFAST</strong> pipeline, ensuring consistency across FAST HI surveys.</p>
        <ul>
            <li><strong>Noise diode calibration:</strong> A ~10 K noise diode is injected for 2 s every 5 min for antenna temperature calibration.</li>
            <li><strong>Flux calibration:</strong> 3C 48 observed every 10 days as the primary flux density calibrator.</li>
        </ul>
    </section>

    <!-- Technical Details -->
    <section class="content-section">
        <h2 class="section-title">Technical Details</h2>
        
        <table>
            <thead>
                <tr>
                    <th>Parameter</th>
                    <th>Value</th>
                    <th>Notes</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Telescope</td>
                    <td>FAST</td>
                    <td>Five-hundred-meter Aperture Spherical radio Telescope</td>
                </tr>
                <tr>
                    <td>Receiver / Beams</td>
                    <td>19-beam L-band</td>
                    <td>Receiver rotated 23.4° for uniform sky sampling</td>
                </tr>
                <tr>
                    <td>Beam size (FWHM)</td>
                    <td>~2.9 arcmin</td>
                    <td>~660 pc at M31 distance (780 kpc)</td>
                </tr>
                <tr>
                    <td>R.A. range (3-pass)</td>
                    <td>23h 38m – 01h 48m</td>
                    <td>593 deg²</td>
                </tr>
                <tr>
                    <td>R.A. range (2-pass)</td>
                    <td>23h 18m – 01h 48m</td>
                    <td>685 deg²</td>
                </tr>
                <tr>
                    <td>Decl. range</td>
                    <td>+29° 00′ – +53° 30′</td>
                    <td>Covers M31 halo out to 160 kpc</td>
                </tr>
                <tr>
                    <td>System temperature</td>
                    <td>19 – 23 K</td>
                    <td>FAST L-band receiver</td>
                </tr>
                <tr>
                    <td>Gain</td>
                    <td>14 – 16 K Jy⁻¹</td>
                    <td></td>
                </tr>
                <tr>
                    <td>Velocity range</td>
                    <td>-1000 – 24,000 km s⁻¹</td>
                    <td>HVCs and background galaxies</td>
                </tr>
                <tr>
                    <td>Spectral resolution</td>
                    <td>1.6 / 4.8 / 10 km s⁻¹</td>
                    <td>Native / rebinned / Hann-smoothed</td>
                </tr>
                <tr>
                    <td>Map rms sensitivity</td>
                    <td>0.8 / 1.0 mJy beam⁻¹</td>
                    <td>At 4.8 / 1.6 km s⁻¹</td>
                </tr>
                <tr>
                    <td>Grid pixel size</td>
                    <td>1 arcmin</td>
                    <td></td>
                </tr>
            </tbody>
        </table>
    </section>
    
    <!-- Data Reduction -->
    <section class="content-section">
        <h2 class="section-title">Data Reduction Pipeline</h2>
        
        <p>The M31 survey data reduction follows the certified <strong>HiFAST</strong> pipeline architecture, as detailed in the technical papers by <a href="{{ '/m31/publications' | relative_url }}">Jing et al. 2024, Liu et al. 2024, Xu et al. 2025, and Chen et al. 2026 </a>. </p>
    </section>
</div>
