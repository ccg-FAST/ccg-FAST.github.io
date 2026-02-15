---
layout: default
title: M31 Observations
---

<div class="page-header">
    <div class="container">
        <h1 class="page-title">M31 Observations</h1>
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
    
    <!-- Observation Setup -->
    <section class="content-section">
        <h2 class="section-title">Observation Setup</h2>
        
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
                    <td>Receiver</td>
                    <td>19-beam L-band</td>
                    <td>Cryogenic receiver array</td>
                </tr>
                <tr>
                    <td>Target coordinates</td>
                    <td>RA: 00h 42m 44s, Dec: +41° 16′</td>
                    <td>Center of M31</td>
                </tr>
                <tr>
                    <td>Center frequency</td>
                    <td>~1350 MHz</td>
                    <td>Redshifted HI line</td>
                </tr>
                <tr>
                    <td>Bandwidth</td>
                    <td>[To be specified]</td>
                    <td>MHz</td>
                </tr>
                <tr>
                    <td>Frequency resolution</td>
                    <td>[To be specified]</td>
                    <td>kHz</td>
                </tr>
                <tr>
                    <td>Velocity resolution</td>
                    <td>[To be specified]</td>
                    <td>km/s</td>
                </tr>
                <tr>
                    <td>Beam size (FWHM)</td>
                    <td>~2.9 arcmin</td>
                    <td>At 1.4 GHz</td>
                </tr>
                <tr>
                    <td>Spatial resolution</td>
                    <td>~700 pc</td>
                    <td>At M31 distance (780 kpc)</td>
                </tr>
            </tbody>
        </table>
    </section>
    
    <!-- Coverage Area -->
    <section class="content-section">
        <h2 class="section-title">Coverage Area</h2>
        
        <p>The M31 survey covers the galaxy and its immediate surroundings:</p>
        
        <div class="info-box">
            <h3 class="info-box-title">Survey Footprint</h3>
            <ul>
                <li><strong>Central region:</strong> M31 disk (D25 ~ 3° × 1°)</li>
                <li><strong>Extended coverage:</strong> Outer disk and warped regions (~5° × 3°)</li>
                <li><strong>Halo coverage:</strong> To ~2° from center (search for HVCs)</li>
                <li><strong>Satellites:</strong> M32, M110, and other nearby dwarfs</li>
            </ul>
        </div>
        
        <p>A map of the observation footprint will be added here.</p>
    </section>
    
    <!-- Observation Strategy -->
    <section class="content-section">
        <h2 class="section-title">Observation Strategy</h2>
        
        <h3 class="section-subtitle">Mapping Strategy</h3>
        <p>The large angular size of M31 (~3° × 1° for the optical disk, larger in HI) requires careful planning:</p>
        <ul>
            <li><strong>On-the-fly mapping:</strong> Continuous scanning across the target</li>
            <li><strong>Beam spacing:</strong> Optimized for complete coverage with 19-beam receiver</li>
            <li><strong>Multiple passes:</strong> For noise reduction and artifact rejection</li>
            <li><strong>Reference positions:</strong> Off-source positions for baseline subtraction</li>
        </ul>
        
        <h3 class="section-subtitle">Integration Time</h3>
        <ul>
            <li><strong>Target sensitivity:</strong> [To be specified] mJy/beam</li>
            <li><strong>Integration time per position:</strong> [To be specified] hours</li>
            <li><strong>Total observation time:</strong> [To be estimated]</li>
            <li><strong>Observing schedule:</strong> [To be planned]</li>
        </ul>
        
        <h3 class="section-subtitle">Calibration</h3>
        <ul>
            <li><strong>Flux calibration:</strong> Standard calibrators (3C286, 3C48)</li>
            <li><strong>Bandpass calibration:</strong> Regular observations of calibrators</li>
            <li><strong>Gain calibration:</strong> Using continuum sources in the field</li>
            <li><strong>Baseline fitting:</strong> Polynomial fitting to remove instrumental effects</li>
        </ul>
    </section>
    
    <!-- Observation Status -->
    <section class="content-section">
        <h2 class="section-title">Observation Status</h2>
        
        <table>
            <thead>
                <tr>
                    <th>Milestone</th>
                    <th>Status</th>
                    <th>Date</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Proposal approved</td>
                    <td>✓ Complete</td>
                    <td>[Date]</td>
                </tr>
                <tr>
                    <td>Test observations</td>
                    <td>[Status]</td>
                    <td>[Date]</td>
                </tr>
                <tr>
                    <td>Central region complete</td>
                    <td>[Status]</td>
                    <td>[Date]</td>
                </tr>
                <tr>
                    <td>Disk coverage complete</td>
                    <td>[Status]</td>
                    <td>[Date]</td>
                </tr>
                <tr>
                    <td>Halo coverage complete</td>
                    <td>[Status]</td>
                    <td>[Date]</td>
                </tr>
                <tr>
                    <td>All observations complete</td>
                    <td>[Status]</td>
                    <td>[Date]</td>
                </tr>
            </tbody>
        </table>
        
        <div class="alert alert-info">
            <strong>Progress Update:</strong> [Add regular updates about observation progress here]
        </div>
    </section>
    
    <!-- Data Reduction -->
    <section class="content-section">
        <h2 class="section-title">Data Reduction Pipeline</h2>
        
        <p>The M31 survey data are processed through a specialized pipeline for extended source mapping:</p>
        
        <ol>
            <li><strong>Raw data inspection:</strong> Quality assessment and flagging</li>
            <li><strong>RFI mitigation:</strong> Automated and manual interference removal</li>
            <li><strong>Calibration application:</strong> Flux, bandpass, and gain corrections</li>
            <li><strong>Baseline subtraction:</strong> Removal of spectral baselines</li>
            <li><strong>Gridding:</strong> Conversion to 3D data cubes</li>
            <li><strong>Moment map creation:</strong> Generation of integrated intensity, velocity, and dispersion maps</li>
            <li><strong>Source finding:</strong> Detection of clouds and substructures</li>
            <li><strong>Parameter extraction:</strong> Measurement of cloud properties</li>
        </ol>
    </section>
    
    <!-- Challenges -->
    <section class="content-section">
        <h2 class="section-title">Observational Challenges</h2>
        
        <p>Observing M31 with FAST presents several challenges:</p>
        
        <div class="card-grid">
            <div class="card">
                <div class="card-header">
                    <div class="card-icon">📏</div>
                    <h3 class="card-title">Large Angular Size</h3>
                </div>
                <div class="card-body">
                    <p class="card-text">M31 spans several degrees on the sky, requiring extensive mapping. The 19-beam receiver helps, but many pointings are still needed.</p>
                </div>
            </div>
            
            <div class="card">
                <div class="card-header">
                    <div class="card-icon">📡</div>
                    <h3 class="card-title">RFI</h3>
                </div>
                <div class="card-body">
                    <p class="card-text">Radio frequency interference from satellites and terrestrial sources must be carefully identified and removed.</p>
                </div>
            </div>
            
            <div class="card">
                <div class="card-header">
                    <div class="card-icon">🌡️</div>
                    <h3 class="card-title">Baseline Stability</h3>
                </div>
                <div class="card-body">
                    <p class="card-text">Extended sources like M31 require excellent baseline stability for accurate flux recovery in the wings.</p>
                </div>
            </div>
            
            <div class="card">
                <div class="card-header">
                    <div class="card-icon">🎯</div>
                    <h3 class="card-title">Dynamic Range</h3>
                </div>
                <div class="card-body">
                    <p class="card-text">The bright central regions and faint outer halo require high dynamic range in both imaging and spectral analysis.</p>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Editing Note -->
    <section class="content-section">
        <div class="info-box">
            <h3 class="info-box-title">Editing This Page</h3>
            <p>Update this page regularly with observation progress:</p>
            <ol>
                <li>Edit <code>m31/observation.md</code></li>
                <li>Update the observation parameters table with actual values</li>
                <li>Update the status table as milestones are reached</li>
                <li>Add progress updates and any issues encountered</li>
            </ol>
        </div>
    </section>
</div>
