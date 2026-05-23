---
layout: default
title: HD2 Data
---

<div class="page-header">
    <div class="container">
        <h1 class="page-title">HD² Data Products</h1>
        <p class="page-subtitle">Data Catalogs and Data Policy</p>
    </div>
</div>

<div class="container">
    <!-- Survey Navigation -->
    <nav class="survey-nav">
        <a href="{{ '/hd2/' | relative_url }}" class="survey-nav-link">Overview</a>
        <a href="{{ '/hd2/science' | relative_url }}" class="survey-nav-link">Science</a>
        <a href="{{ '/hd2/observation' | relative_url }}" class="survey-nav-link">Observation</a>
        <a href="{{ '/hd2/publications' | relative_url }}" class="survey-nav-link">Publications</a>
        <a href="{{ '/hd2/data' | relative_url }}" class="survey-nav-link active">Data</a>
    </nav>
    
    <!-- Data Release -->
    <section class="content-section">
        <h2 class="section-title">Data Releases</h2>
        
        <div class="alert alert-info">
            <strong> 🎉 Our pilot survey data release is available! (May 2026)</strong> <br>
        </div>
        
        <table>
            <thead>
                <tr>
                    <th>Release</th>
                    <th>Date</th>
                    <th>Coverage</th>
                    <th>Description</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>PDR (z &lt; 0.09)</td>
                    <td>public on May 2026</td>
                    <td>10 deg²</td>
                    <td>pilot data release, 9 passes (~7.3 min/beam) </td>
                </tr>
                <tr>
                    <td>DR1</td>
                    <td>Planned</td>
                    <td>100 deg²</td>
                    <td>Y1+Y2 Wide, 9 passes (~7.3 min/beam) </td>
                </tr>
                <tr>
                    <td>DR2</td>
                    <td>Planned</td>
                    <td>100 deg²</td>
                    <td>Planned</td>
                </tr>
            </tbody>
        </table>
    </section>
    
    <!-- Source Catalogs -->
    <section class="content-section">
        <h2 class="section-title">Source Catalogs</h2>
        
        <div class="data-card">
            <span class="data-icon">📊</span>
            <div class="data-info">
                <div class="data-title">HD2 PDR Source Catalog</div>
                <div class="data-meta">FITS format | See Xu et al. (2026) for details</div>
            </div>
            <div class="data-action">
                <a href="{{ '/hd2/data/pdr/' | relative_url }}" class="btn btn-primary">View Details</a>
            </div>
        </div>
        
    </section>
    
    <!-- HI Spectra Access -->
    <section class="content-section">
        <h2 class="section-title">HI Spectra</h2>
        
        <p>The calibrated HI spectra for individual sources from the HD² survey are available upon reasonable request to the Principal Investigator (PI).</p>
        
        <div class="data-card">
            <span class="data-icon">📈</span>
            <div class="data-info">
                <div class="data-title">HD2 PDR HI Spectra</div>
                <div class="data-meta">FITS format | 1D extracted spectra | See Xu et al. (2026) for details</div>
            </div>
            <div class="data-action">
                <a href="{{ '/people' | relative_url }}" class="btn btn-primary">Contact PI</a>
            </div>
        </div>
        
        <div class="alert alert-info">
            <strong>Note:</strong> When requesting data, please provide a brief description of your scientific project and the specific sources or regions of interest.
        </div>
    </section>
    
    <!-- Data Policy -->
    <section class="content-section">
        <h2 class="section-title">Data Policy</h2>
        
        <h3 class="section-subtitle">Usage Rights</h3>
        <p><strong>We welcome everyone in the community to use our public data for scientific research!</strong> For data that has not yet been released, the HD² survey data policy is currently under discussion. In principle, survey members have priority access to the unpublic data for scientific analysis and publication.</p>
        
        <h3 class="section-subtitle">Citation Requirements</h3>
        <p>If you use HD2 data in your research, please cite the <a href="{{ '/hd2/publications' | relative_url }}">following papers</a> (PDR and DR1):</p>
        
        <div class="alert alert-info">
            <p><strong>Pilot Data Release (PDR) Paper:</strong><br>
            Chen Xu, Yingjie Jing, Jie Wang, et al., "The FAST Hundred-Deg² HI Deep (HD²) Survey: Early Results from the Pilot Survey"</p>
            
            <p><strong>First Data Release (DR1) Paper:</strong><br>
            Waiting :D </p>

            <p><strong>HiFAST pipeline papers:</strong><br>
            Jing et al. 2024; Liu et al. 2024; Xu et al. 2025; Chen et al. 2026</p>
        </div>
        
        <h3 class="section-subtitle">Acknowledgment Text</h3>
        <p>Additionally, please acknowledge the FAST telescope and the CCG group in your publications using the template below:</p>

        <div class="info-box" style="margin-top: var(--space-4);">
            <h3 class="info-box-title">Acknowledgement Template</h3>
            <p style="font-style: italic; line-height: 1.8;">
                This work made use of the data from FAST (Five-hundred-meter Aperture Spherical radio Telescope) (<a href="https://cstr.cn/31116.02.FAST" target="_blank">https://cstr.cn/31116.02.FAST</a>). FAST is a Chinese national mega-science facility, operated by National Astronomical Observatories, Chinese Academy of Sciences.
                We acknowledge the support from the FAST-HD² survey team (Computational Cosmology Group, NAOC). The HD² survey data were reduced using the HiFAST pipeline. 
            </p>
        </div>
    </section>
    
    <!-- Contact -->
    <section class="content-section">
        <h2 class="section-title">Data Access Questions</h2>
        <p>For questions about data products, format, or access issues, please contact PI or visit our <a href="{{ '/people' | relative_url }}">people page</a>.</p>
    </section>
    
</div>
