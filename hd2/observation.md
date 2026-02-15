---
layout: default
title: HD2 Observations
---

<div class="page-header">
    <div class="container">
        <h1 class="page-title">HD2 Observations</h1>
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
                    <td>System temperature</td>
                    <td>~20 K</td>
                    <td>Typical L-band value</td>
                </tr>
            </tbody>
        </table>
    </section>
    
    <!-- Survey Region -->
    <section class="content-section">
        <h2 class="section-title">Survey Region</h2>
        
        <p>The HD2 survey targets a 100 square degree region of the sky. The exact coordinates and footprint will be specified here:</p>
        
        <div class="info-box">
            <h3 class="info-box-title">Survey Footprint</h3>
            <ul>
                <li><strong>RA range:</strong> [To be specified] - [To be specified]</li>
                <li><strong>Dec range:</strong> [To be specified] - [To be specified]</li>
                <li><strong>Galactic latitude:</strong> [To be specified]</li>
                <li><strong>Total area:</strong> ~100 deg²</li>
            </ul>
        </div>
        
        <p>A map of the survey region will be added here once observations begin.</p>
    </section>
    
    <!-- Observation Strategy -->
    <section class="content-section">
        <h2 class="section-title">Observation Strategy</h2>
        
        <h3 class="section-subtitle">Scanning Mode</h3>
        <p>The HD2 survey uses [scanning mode to be specified - e.g., drift scan, on-the-fly mapping, or pointed observations] to efficiently cover the 100 square degree area.</p>
        
        <h3 class="section-subtitle">Integration Time</h3>
        <ul>
            <li><strong>Target integration time per beam:</strong> [To be specified] hours</li>
            <li><strong>Total observation time:</strong> [To be estimated]</li>
            <li><strong>Observing schedule:</strong> [To be planned]</li>
        </ul>
        
        <h3 class="section-subtitle">Calibration</h3>
        <ul>
            <li><strong>Flux calibration:</strong> Using standard calibrators (e.g., 3C286, 3C48)</li>
            <li><strong>Bandpass calibration:</strong> Observed at regular intervals</li>
            <li><strong>Gain calibration:</strong> Using nearby continuum sources</li>
            <li><strong>RFI monitoring:</strong> Continuous monitoring and flagging</li>
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
                    <td>Commissioning observations</td>
                    <td>[Status]</td>
                    <td>[Date]</td>
                </tr>
                <tr>
                    <td>First science observations</td>
                    <td>[Status]</td>
                    <td>[Date]</td>
                </tr>
                <tr>
                    <td>25% complete</td>
                    <td>[Status]</td>
                    <td>[Date]</td>
                </tr>
                <tr>
                    <td>50% complete</td>
                    <td>[Status]</td>
                    <td>[Date]</td>
                </tr>
                <tr>
                    <td>75% complete</td>
                    <td>[Status]</td>
                    <td>[Date]</td>
                </tr>
                <tr>
                    <td>Observations complete</td>
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
        
        <p>The HD2 survey data are processed through a custom pipeline that includes:</p>
        
        <ol>
            <li><strong>Raw data inspection:</strong> Quality checks and flagging</li>
            <li><strong>RFI mitigation:</strong> Automated and manual flagging of radio frequency interference</li>
            <li><strong>Calibration:</strong> Application of flux, bandpass, and gain calibrations</li>
            <li><strong>Gridding:</strong> Conversion to data cubes with appropriate pixelization</li>
            <li><strong>Baseline fitting:</strong> Removal of spectral baselines</li>
            <li><strong>Source finding:</strong> Automated detection of HI sources</li>
            <li><strong>Parameterization:</strong> Measurement of source properties (flux, velocity, width)</li>
            <li><strong>Catalog generation:</strong> Compilation of reliable source catalogs</li>
        </ol>
        
        <p>The pipeline software and documentation will be made available upon request.</p>
    </section>
    
    <!-- Editing Note -->
    <section class="content-section">
        <div class="info-box">
            <h3 class="info-box-title">Editing This Page</h3>
            <p>Update this page regularly with observation progress:</p>
            <ol>
                <li>Edit <code>hd2/observation.md</code></li>
                <li>Update the observation parameters table with actual values</li>
                <li>Fill in the survey region coordinates</li>
                <li>Update the status table as milestones are reached</li>
                <li>Add progress updates and any issues encountered</li>
            </ol>
        </div>
    </section>
</div>
