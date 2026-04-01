---
layout: default
title: M31 Data
---

<div class="page-header">
    <div class="container">
        <h1 class="page-title">M31 Data Products</h1>
        <p class="page-subtitle">Download Cubes, Maps, and Catalogs</p>
    </div>
</div>

<div class="container">
    <!-- Survey Navigation -->
    <nav class="survey-nav">
        <a href="{{ '/m31/' | relative_url }}" class="survey-nav-link">Overview</a>
        <a href="{{ '/m31/science' | relative_url }}" class="survey-nav-link">Science</a>
        <a href="{{ '/m31/observation' | relative_url }}" class="survey-nav-link">Observation</a>
        <a href="{{ '/m31/publications' | relative_url }}" class="survey-nav-link">Publications</a>
        <a href="{{ '/m31/data' | relative_url }}" class="survey-nav-link active">Data</a>
    </nav>
    
    <!-- Data Release -->
    <section class="content-section">
        <h2 class="section-title">Data Releases</h2>
        
        <div class="alert alert-warning">
            <strong>Currently Not Released</strong>  <br>
        </div>
        
    </section>
    
    <!-- Data Cubes -->
    <section class="content-section">
        <h2 class="section-title">HI Data Cubes</h2>
        
        <p>The primary data product is the 3D HI data cube covering the M31 halo.</p>
        
        <div class="data-card">
            <span class="data-icon">🧊</span>
            <div class="data-info">
                <div class="data-title">M31 HI Data Cube </div>
                <div class="data-meta">FITS cube | Currently Not Released</div>
            </div>
            <div class="data-action">
                <a href="#" class="btn btn-primary disabled" onclick="return false;">Download</a>
            </div>
        </div>
        
        <div class="alert alert-warning">
            <strong>Currently Not Released:</strong> Data cubes are currently restricted to project members. For research collaboration or specific spectra requests, please contact the PI.
        </div>
    </section>
    
    <!-- Moment Maps -->
    <section class="content-section">
        <h2 class="section-title">Moment Maps</h2>
        
        <p>Moment maps derived from the data cube:</p>
        
        <div class="data-card">
            <span class="data-icon">🗺️</span>
            <div class="data-info">
                <div class="data-title">Moment 0 - Integrated Intensity</div>
                <div class="data-meta">FITS image | Total HI column density | Currently Not Released</div>
            </div>
            <div class="data-action">
                <a href="#" class="btn btn-primary disabled" onclick="return false;">Download</a>
            </div>
        </div>
        
        <div class="data-card">
            <span class="data-icon">🗺️</span>
            <div class="data-info">
                <div class="data-title">Moment 1 - Velocity Field</div>
                <div class="data-meta">FITS image | Mean line-of-sight velocity | Currently Not Released</div>
            </div>
            <div class="data-action">
                <a href="#" class="btn btn-primary disabled" onclick="return false;">Download</a>
            </div>
        </div>
        
        <div class="data-card">
            <span class="data-icon">🗺️</span>
            <div class="data-info">
                <div class="data-title">Moment 2 - Velocity Dispersion</div>
                <div class="data-meta">FITS image | Velocity dispersion | Currently Not Released</div>
            </div>
            <div class="data-action">
                <a href="#" class="btn btn-primary disabled" onclick="return false;">Download</a>
            </div>
        </div>
    </section>
    
    <!-- HVC Catalog -->
    <section class="content-section">
        <h2 class="section-title">High-Velocity Cloud Catalog</h2>
        
        <div class="data-card">
            <span class="data-icon">📋</span>
            <div class="data-info">
                <div class="data-title">M31 HVC Catalog</div>
                <div class="data-meta">FITS table | Ongoing</div>
            </div>
            <div class="data-action">
                <a href="#" class="btn btn-primary disabled" onclick="return false;">Download</a>
            </div>
        </div>

        <!-- Background Sources -->
        <h2 class="section-title">Background HI Sources</h2>
        
        <div class="data-card">
            <span class="data-icon">📡</span>
            <div class="data-info">
                <div class="data-title">Background HI Source Catalog</div>
                <div class="data-meta">FITS/CSV format | Extra-galactic sources | Ongoing</div>
            </div>
            <div class="data-action">
                <a href="#" class="btn btn-primary disabled" onclick="return false;">Download</a>
            </div>
        </div>
        
        <div class="data-card">
            <span class="data-icon">📉</span>
            <div class="data-info">
                <div class="data-title">HI Spectra of Background Sources</div>
                <div class="data-meta">FITS format | 1D extracted spectra | Ongoing</div>
            </div>
            <div class="data-action">
                <a href="#" class="btn btn-primary disabled" onclick="return false;">Contact PI</a>
            </div>
        </div>
    </section>
    
    <!-- Data Policy -->
    <section class="content-section">
        <h2 class="section-title">Data Policy</h2>
        
        <h3 class="section-subtitle">Usage Rights</h3>
        <p>The M31 survey data policy is currently under discussion. Project members have priority access to the data products.</p>
        
        <h3 class="section-subtitle">Citation Requirements</h3>
        <p>Publications using M31 survey data should cite the following papers:</p>
        <ul>
            <li>HiFAST pipeline papers (Jing et al. 2024; Liu et al. 2024; Xu et al. 2025; Chen et al. 2026)</li>
            <li>Relevant M31 paper </li>
        </ul>
        
        <h3 class="section-subtitle">Acknowledgment Text</h3>
        <div class="alert alert-info">
            <em>"This research made use of data from the FAST M31 Survey, conducted by the CCG group. The Five-hundred-meter Aperture Spherical radio Telescope (FAST) is a national major science research facility in China, operated by the National Astronomical Observatories, Chinese Academy of Sciences.
            We acknowledge the support from the FAST-M31 survey team (Computational Cosmology Group, NAOC). The M31 survey data were reduced using the HiFAST pipeline. "</em>
        </div>
    </section>
    
    <!-- Contact -->
    <section class="content-section">
        <h2 class="section-title">Data Access Questions</h2>
        <p>For questions about data products, format, or access issues, please contact PI or visit our <a href="{{ '/people' | relative_url }}">people page</a>.</p>
    </section>

</div>
