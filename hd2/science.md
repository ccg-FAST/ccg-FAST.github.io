---
layout: default
title: HD2 Science
---

<div class="page-header">
    <div class="container">
        <h1 class="page-title">HD2 Science</h1>
        <p class="page-subtitle">Scientific Goals and Research Topics</p>
    </div>
</div>

<div class="container">
    <!-- Survey Navigation -->
    <nav class="survey-nav">
        <a href="{{ '/hd2/' | relative_url }}" class="survey-nav-link">Overview</a>
        <a href="{{ '/hd2/science' | relative_url }}" class="survey-nav-link active">Science</a>
        <a href="{{ '/hd2/observation' | relative_url }}" class="survey-nav-link">Observation</a>
        <a href="{{ '/hd2/publications' | relative_url }}" class="survey-nav-link">Publications</a>
        <a href="{{ '/hd2/data' | relative_url }}" class="survey-nav-link">Data</a>
    </nav>
    
    <!-- Main Science Goals -->
    <section class="content-section">
        <h2 class="section-title">Primary Science Goals</h2>
        
        <p>The HD2 survey is designed to address several key questions in extragalactic HI astronomy. Our deep observations of 100 square degrees will enable breakthrough studies in the following areas:</p>
        
        <h3 class="section-subtitle">1. The HI Mass Function</h3>
        <p>One of the fundamental statistical measures in extragalactic astronomy, the HI mass function describes the number density of galaxies as a function of their HI mass. HD2 will:</p>
        <ul>
            <li>Extend measurements to lower HI masses than previous surveys</li>
            <li>Constrain the faint-end slope of the mass function</li>
            <li>Compare with theoretical predictions from cosmological simulations</li>
            <li>Study the evolution of the HI mass function with redshift</li>
        </ul>
        
        <h3 class="section-subtitle">2. Cosmic HI Density</h3>
        <p>The comoving HI density ($\Omega_{\rm HI}$) traces the evolution of neutral gas in the universe. Our survey will:</p>
        <ul>
            <li>Provide precise measurements of $\Omega_{\rm HI}$ at z ~ 0</li>
            <li>Compare with higher redshift measurements from damped Lyman-alpha systems</li>
            <li>Test models of gas consumption and replenishment in galaxies</li>
        </ul>
        
        <h3 class="section-subtitle">3. Large-Scale Structure</h3>
        <p>HI-selected galaxies trace the underlying matter distribution differently than optically-selected samples. We will study:</p>
        <ul>
            <li>Clustering properties of HI-selected galaxies</li>
            <li>HI content variation with environment (field vs. group vs. cluster)</li>
            <li>Filamentary structures in the cosmic web traced by neutral hydrogen</li>
            <li>Redshift-space distortions and peculiar velocities</li>
        </ul>
    </section>
    
    <!-- Secondary Science -->
    <section class="content-section">
        <h2 class="section-title">Secondary Science Topics</h2>
        
        <div class="card-grid">
            <div class="card">
                <div class="card-header">
                    <div class="card-icon">🌊</div>
                    <h3 class="card-title">Tidal Features</h3>
                </div>
                <div class="card-body">
                    <p class="card-text">Search for HI tidal tails and bridges indicating galaxy interactions and mergers in the local universe.</p>
                </div>
            </div>
            
            <div class="card">
                <div class="card-header">
                    <div class="card-icon">💫</div>
                    <h3 class="card-title">Star Formation</h3>
                </div>
                <div class="card-body">
                    <p class="card-text">Investigate the relationship between HI content, molecular gas, and star formation activity using multi-wavelength data.</p>
                </div>
            </div>
            
            <div class="card">
                <div class="card-header">
                    <div class="card-icon">🎯</div>
                    <h3 class="card-title">Dark Matter</h3>
                </div>
                <div class="card-body">
                    <p class="card-text">Use HI rotation curves to constrain the dark matter distribution in detected galaxies and test modified gravity theories.</p>
                </div>
            </div>
            
            <div class="card">
                <div class="card-header">
                    <div class="card-icon">🔭</div>
                    <h3 class="card-title">Low Surface Brightness</h3>
                </div>
                <div class="card-body">
                    <p class="card-text">Detect low surface brightness galaxies that may be missed by optical surveys but are rich in neutral hydrogen.</p>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Expected Outcomes -->
    <section class="content-section">
        <h2 class="section-title">Expected Outcomes</h2>
        
        <table>
            <thead>
                <tr>
                    <th>Science Product</th>
                    <th>Expected Yield</th>
                    <th>Timeline</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>HI-detected galaxies</td>
                    <td>[To be estimated]</td>
                    <td>After data release 1</td>
                </tr>
                <tr>
                    <td>Spectra with S/N > 5</td>
                    <td>[To be estimated]</td>
                    <td>After data release 1</td>
                </tr>
                <tr>
                    <td>HI mass function measurement</td>
                    <td>Extended to lower masses</td>
                    <td>DR1 + 6 months</td>
                </tr>
                <tr>
                    <td>Clustering analysis</td>
                    <td>Power spectrum, correlation function</td>
                    <td>DR1 + 12 months</td>
                </tr>
            </tbody>
        </table>
    </section>
    
    <!-- Collaborations -->
    <section class="content-section">
        <h2 class="section-title">Multi-wavelength Collaborations</h2>
        
        <p>The HD2 survey region has been or will be observed by several other facilities, enabling rich multi-wavelength science:</p>
        
        <ul>
            <li><strong>Optical spectroscopy:</strong> SDSS, DESI, and other surveys for redshift confirmation and stellar population analysis</li>
            <li><strong>Infrared:</strong> WISE, Spitzer, and Herschel data for dust and stellar mass estimates</li>
            <li><strong>CO observations:</strong> Molecular gas measurements to complement HI data</li>
            <li><strong>UV:</strong> GALEX data for star formation rate indicators</li>
            <li><strong>Radio continuum:</strong> Synchrotron emission and star formation tracers</li>
        </ul>
    </section>
    
    <!-- Editing Note -->
    <section class="content-section">
        <div class="info-box">
            <h3 class="info-box-title">Editing This Page</h3>
            <p>This page contains the scientific goals of the HD2 survey. To update:</p>
            <ol>
                <li>Edit <code>hd2/science.md</code> in your repository</li>
                <li>Add specific science goals, expected yields, and timelines</li>
                <li>Include any relevant equations using LaTeX syntax (add <code>math: true</code> to the front matter)</li>
                <li>Update the expected outcomes table with realistic estimates</li>
            </ol>
        </div>
    </section>
</div>
