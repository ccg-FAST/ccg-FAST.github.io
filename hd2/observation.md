---
layout: default
title: HD2 Observations
---

<div class="page-header">
    <div class="container">
        <h1 class="page-title">HD² Observations</h1>
        <p class="page-subtitle">Observation Strategy and Status</p>
    </div>
</div>

<div class="container">
    <!-- Survey Navigation -->
    <nav class="survey-nav">
        <a href="{{ '/hd2/' | relative_url }}" class="survey-nav-link">Overview</a>
        <a href="{{ '/hd2/science' | relative_url }}" class="survey-nav-link">Science</a>
        <a href="{{ '/hd2/observation' | relative_url }}" class="survey-nav-link active">Observation</a>
        <a href="{{ '/hd2/publications' | relative_url }}" class="survey-nav-link">Publications</a>
        <a href="{{ '/hd2/data' | relative_url }}" class="survey-nav-link">Data</a>
    </nav>
    
    
    <!-- Survey Region -->
    <section class="content-section">
        <h2 class="section-title">Survey Region</h2>
        
        <p>The HD² survey targets a contiguous ~100 deg² region at declination ~43°, selected for its low zenith angle at FAST (<26.4°, ensuring optimal aperture efficiency) and reduced RFI contamination compared to equatorial fields. The field lies within the DESI DR1 footprint and overlaps with HSC-SSP wide-field imaging in its northern portion.</p>
        
        <div class="figure-container" style="text-align: center; margin: 2rem 0;">
            <img src="{{ '/assets/images/HD2_area.png' | relative_url }}" alt="HD2 Survey Footprint" style="max-width: 100%; height: auto; border-radius: 8px; box-shadow: 0 4px 6px rgba(0,0,0,0.1);">
            <p class="figure-caption" style="margin-top: 1rem; font-size: 0.95rem; line-height: 1.6; color: #666;">
                <strong>Figure:</strong> Sky distribution of HD² survey fields overlaid on DESI DR1 spectroscopic completeness (yellow = completeness ~1.0; purple = ~0.4). Red box: HSC-SSP wide field. Orange: Pilot Survey (10 deg²). Blue solid: Y1 shallow (77 deg²). Dark blue solid: Y1 deep (6 deg²). Light blue dashed: Y2 shallow (22.4 deg²). Green dashed: Y2 medium-deep (46 deg²). (Credit: Xu, Chen)
            </p>
        </div>

    </section>

    <!-- Observation Status -->
    <section class="content-section">
        <h2 class="section-title">Observation Status</h2>
        
        <table>
            <thead>
                <tr>
                    <th>Milestone</th>
                    <th>Area</th>
                    <th>Depth (passes)</th>
                    <th>Status</th>
                    <th>Period</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Pilot Survey</td>
                    <td>10 deg²</td>
                    <td>9 passes (~7.3 min/beam)</td>
                    <td>✓ Complete</td>
                    <td>Jul–Aug 2023</td>
                </tr>
                <tr>
                    <td>Y1 Shallow</td>
                    <td>77 deg²</td>
                    <td>9 passes (~7.3 min/beam)</td>
                    <td>✓ Complete</td>
                    <td>Aug 2024 – Apr 2025</td>
                </tr>
                <tr>
                    <td>Y1 Deep</td>
                    <td>6 deg²</td>
                    <td>36 passes (~29 min/beam)</td>
                    <td>✓ Complete</td>
                    <td>May–Jun 2025</td>
                </tr>
                <tr>
                    <td>Y2 Shallow (100 deg² complete)</td>
                    <td>23 deg²</td>
                    <td>9 passes</td>
                    <td>✓ Complete</td>
                    <td>Mar 2026</td>
                </tr>
                <tr>
                    <td>Y2 Medium-deep</td>
                    <td>46 deg²</td>
                    <td>18 passes (~14.6 min/beam)</td>
                    <td>⏳ In progress</td>
                    <td>Expected 2027</td>
                </tr>
                <tr>
                    <td>Full Survey (24+ passes)</td>
                    <td>100 deg²</td>
                    <td>24 passes (~20 min/beam)</td>
                    <td>🔭 Planned</td>
                    <td>~2028</td>
                </tr>
            </tbody>
        </table>
        
        <div class="alert alert-info">
            <strong>Progress Update:</strong> As of March 2026, the full 100 deg² footprint has been observed to a shallow depth of 9 drift-scan passes (rms ~ 0.45 mJy beam⁻¹). Observations are ongoing to deepen coverage toward the final survey sensitivity of 0.28 mJy beam⁻¹, with completion expected around 2028.
        </div>
    </section>
    
    <!-- Observation Strategy -->
    <section class="content-section">
        <h2 class="section-title">Observation Strategy</h2>
        
        <h3 class="section-subtitle">Scanning Mode</h3>
        <p>HD² uses the FAST 19-beam receiver in Multibeam On-The-Fly (OTF) mapping mode, scanning in right ascension at 5″ s⁻¹ — approximately one-third of the drift scan speed, so each OTF pass is equivalent to 3 drift scan passes in depth. Each observing session covers a ~4.4 deg² strip over ~3.2 hours, with the zenith angle kept below 26.4° to maintain optimal telescope efficiency. Successive passes are offset in declination by at least 1/6 of the beam spacing to ensure uniform Nyquist sampling. The flux calibrator 3C 286 is observed every 10 days.</p>
        
        <h3 class="section-subtitle">Layered Depth Strategy</h3>
        <p>HD² adopts a tiered observing strategy to balance area coverage and integration depth across its multi-year program:</p>
        <ul>
            <li><strong>Shallow tier (9 passes):</strong> rms ~ 0.45 mJy beam⁻¹ at 4.8 km s⁻¹ — matches the pilot survey depth, covering the full 100 deg²</li>
            <li><strong>Medium tier (18 passes):</strong> rms ~ 0.32 mJy beam⁻¹ — covering ~46 deg² in Year 2</li>
            <li><strong>Deep tier (24+ passes):</strong> rms ~ 0.28 mJy beam⁻¹ — full survey target sensitivity over 100 deg², equivalent to ~20 min integration per beam</li>
            <li><strong>Deepest tier (36 passes):</strong> rms ~ 0.23 mJy beam⁻¹ — 6 deg² ultra-deep field in Year 1</li>
        </ul>
    
        <h3 class="section-subtitle">Calibration</h3>
        <p>The HD² survey data are processed using the <a href="https://hifast.readthedocs.io/en/v1.4/index.html" target="_blank"><strong>HiFAST</strong></a> pipeline.
        </p>
        <ul>
            <li><strong>Noise diode calibration:</strong> High-power (~10 K) noise diode injected for 2 s every 5 min for antenna temperature calibration, see <a href="https://www.sciengine.com/SCPMA/doi/10.1007/s11433-023-2335-0" target="_blank">Jing et al. 2024 (SCPMA)</a> for details.</li>
            <li><strong>Flux Calibration & Gain:</strong> Impact of observing modes and ambient temperature on FAST gain, along with standard flux calibration procedures using 3C 286, are presented in <a href="https://iopscience.iop.org/article/10.1088/1674-4527/ad30b5" target="_blank">Liu et al. 2024 (RAA)</a>.</li>
            <li><strong>Baseline and bandpass:</strong> Low-order polynomial baseline subtraction per spectrum, followed by MedMed bandpass correction</li>
            <li><strong>RFI flagging:</strong> Strong RFI between 1.15–1.30 GHz excluded; shared RFI mask applied across all beams</li>
            <li><strong>Standing Wave & RFI:</strong> Methods for removing standing waves and mitigating periodic RFI are described in <a href="https://iopscience.iop.org/article/10.1088/1674-4527/ad9685" target="_blank">Xu et al. 2025 (RAA)</a>.</li>
        </ul>
    </section>

    <!-- Observation Setup -->
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
                    <td>R.A. range</td>
                    <td>14<sup>h</sup>00<sup>m</sup>00<sup>s</sup> – 15<sup>h</sup>04<sup>m</sup>00<sup>s</sup></td>
                    <td>Full survey coverage</td>
                </tr>
                <tr>
                    <td>Dec. range</td>
                    <td>36° 43' 30'' – 45° 00' 00''</td>
                    <td>Full survey coverage</td>
                </tr>
                <tr>
                    <td>Receiver / Beams</td>
                    <td>19-beam L-band</td>
                    <td>Cryogenic receiver array</td>
                </tr>
                <tr>
                    <td>Beam size (FWHM)</td>
                    <td>~2.9 arcmin</td>
                    <td>At 1.42 GHz</td>
                </tr>
                <tr>
                    <td>Polarizations</td>
                    <td>2 (XX, YY)</td>
                    <td>Dual polarization</td>
                </tr>
                <tr>
                    <td>Gain</td>
                    <td>14 – 16 K Jy⁻¹</td>
                    <td>from Liu et al. 2024 </td>
                </tr>
                <tr>
                    <td>System temperature (T<sub>sys</sub>)</td>
                    <td>19 – 23 K</td>
                    <td>FAST L-band receiver</td>
                </tr>
                <tr>
                    <td>Full frequency range</td>
                    <td>1000 – 1500 MHz</td>
                    <td>W band backend</td>
                </tr>
                <tr>
                    <td>Full spectral channels</td>
                    <td>65,536</td>
                    <td>W band backend </td>
                </tr>
                <tr>
                    <td>Redshift range</td>
                    <td>0.001 – 0.09 & ~0.3</td>
                    <td>HI redshift (low & high)</td>
                </tr>
                <tr>
                    <td>Channel resolution</td>
                    <td>7.6 kHz / 22.8 kHz</td>
                    <td>W band / after down-sample</td>
                </tr>
                <tr>
                    <td>Spectral resolution (z=0)</td>
                    <td>1.6 / 4.8 / 10 km s⁻¹</td>
                    <td>W band / down-sample / Hann smooth</td>
                </tr>
                <tr>
                    <td>Expected map median rms</td>
                    <td>0.28 mJy beam⁻¹</td>
                    <td>At 4.8 km s⁻¹ resolution</td>
                </tr>
                <tr>
                    <td>Expected spectral median rms</td>
                    <td>0.28 mJy</td>
                    <td>At 10 km s⁻¹ resolution</td>
                </tr>
                <tr>
                    <td>Grid pixel size</td>
                    <td>1 arcmin</td>
                    <td>Data cube pixelation</td>
                </tr>
            </tbody>
        </table>
    </section>
    
    <!-- Data Reduction -->
    <section class="content-section">
        <h2 class="section-title">Data Reduction Pipeline</h2>
        
        <p>The detailed data reduction procedures and the performance of the pipeline are described in the series of <strong>HiFAST</strong> publications: 
            <a href="https://www.sciengine.com/SCPMA/doi/10.1007/s11433-023-2335-0" target="_blank">Jing et al. 2024 (Paper I)</a>, 
            <a href="https://iopscience.iop.org/article/10.1088/1674-4527/ad30b5" target="_blank">Liu et al. 2024 (Paper II)</a>, 
            <a href="https://iopscience.iop.org/article/10.1088/1674-4527/ad9685" target="_blank">Xu et al. 2025 (Paper III)</a>, and
            <a href="https://iopscience.iop.org/article/10.1088/1674-1056/ad9092" target="_blank">Chen et al. 2026 (Paper IV)</a>.
            The further details on the survey implementation can be found in <strong>Xu et al. (submitted to ApJS)</strong>.
        </p>
    </section>
    
</div>
