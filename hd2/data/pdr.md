---
layout: default
title: HD2 PDR Source Catalog
permalink: /hd2/data/pdr/
---

<div class="page-header">
    <div class="container">
        <h1 class="page-title">HD² PDR Source Catalog</h1>
        <p class="page-subtitle">Column Descriptions and Details</p>
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
    
    <section class="content-section">
        <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 2rem;">
            <h2 class="section-title" style="margin: 0;">Catalog Description</h2>
            <div>
                <a href="{{ '/hd2/release/pdr/HD2_pilotDR_HI_catalog.fits.README.md' | relative_url }}" class="btn btn-outline-primary" style="margin-right: 8px;" target="_blank">View README</a>
                <a href="{{ '/hd2/release/pdr/HD2_pilotDR_HI_catalog.fits' | relative_url }}" class="btn btn-primary" download>Download FITS Catalog</a>
            </div>
        </div>
        
        <p>This catalog contains <strong>339 extragalactic HI sources</strong> detected in the pilot survey of FAST Hundred-Deg² HI Deep (HD²) Survey, corresponding to <a href="https://iopscience.iop.org/article/10.3847/1538-4365/ae7331#apjsae7331t5" target="_blank">Table 5 of Xu et al. 2026</a> in the FITS format.</p>

        <div class="alert alert-info">
            <strong>The published version </strong> of this table can be downloaded via <a href="https://content.cld.iop.org/journals/0067-0049/285/1/25/revision1/apjsae7331t5_mrt.txt" target="_blank">this link</a> in txt format.<br>
        </div>
        
        <div class="info-box">
            <p><strong>Title:</strong> The FAST Hundred-Deg² HI Deep (HD²) Survey: Early Results from the Pilot Survey<br>
            <strong>Authors:</strong> Xu C., Jing Y., Wang J., Zou H., Du W., Yu N., Guo H., Liu Z., Chen Q., Liang T., Hou Z., Xu Y., Li X., Hu H., Liu Z., Zhao P., Fang T., Gao L., Guo Q., Gu Q., Jiang Z., Kang X., Kong X., Li C., Pan J., Wang T., Zhou Y., Wang W., Wang J.<br>
            <strong>Paper:</strong> <a href="https://arxiv.org/abs/2605.23686" target="_blank">arXiv:2605.23686</a> <br>
            <strong>Version:</strong> Pre-release (2026/05, v2.6)<br>
            <strong>Contact:</strong> For questions regarding the catalog, please contact Chen Xu (xuchen[at]nao.cas.cn).</p>
        </div>

        <div class="alert alert-warning">
            <strong>Important:</strong> The catalog presented on this page is not the published version provided by ApJS. We have added several extra columns for convenience, including <em>Peak flux density</em>, <em>Notes</em>, and <em>internal IDs</em> based on the original published table.
        </div>

    </section>
    
    <section class="content-section">
        <h2 class="section-title">Columns</h2>
        
        <table>
            <thead>
                <tr>
                    <th>Column</th>
                    <th>Unit</th>
                    <th>Description</th>
                </tr>
            </thead>
            <tbody>
                <tr><td>HGCN</td><td>---</td><td>Unique identifier in Hundred-deg² Galaxy Catalog</td></tr>
                <tr><td>Name</td><td>---</td><td>Source name; format of Jhhmmss.s +ddmmss</td></tr>
                <tr><td>HIRAdeg</td><td>deg</td><td>Flux-weighted HI centroid right ascension (J2000)</td></tr>
                <tr><td>HIDEdeg</td><td>deg</td><td>Flux-weighted HI centroid declination (J2000)</td></tr>
                <tr><td>OCRAdeg</td><td>deg</td><td>Right ascension of most probable optical counterpart (J2000)</td></tr>
                <tr><td>OCDEdeg</td><td>deg</td><td>Declination of most probable optical counterpart (J2000)</td></tr>
                <tr><td>VHel</td><td>km/s</td><td>Heliocentric HI velocity measured <sup>(1)</sup></td></tr>
                <tr><td>VOC</td><td>km/s</td><td>Heliocentric velocity of optical counterpart</td></tr>
                <tr><td>Zcmb</td><td>---</td><td>Redshift in the CMB reference frame</td></tr>
                <tr><td>W50</td><td>km/s</td><td>HI line width at 50% of peak flux <sup>(1)</sup></td></tr>
                <tr><td>e_W50</td><td>km/s</td><td>Uncertainty in W50</td></tr>
                <tr><td>W20</td><td>km/s</td><td>HI line width at 20% of peak flux <sup>(1)</sup></td></tr>
                <tr><td>HIflux</td><td>Jy km/s</td><td>Integrated HI flux</td></tr>
                <tr><td>e_HIflux</td><td>Jy km/s</td><td>Uncertainty in HIflux</td></tr>
                <tr><td>Speak</td><td>mJy</td><td>Peak flux density</td></tr>
                <tr><td>RMS</td><td>mJy</td><td>RMS noise of spatially integrated HI spectrum</td></tr>
                <tr><td>SNR</td><td>---</td><td>Signal-to-noise ratio</td></tr>
                <tr><td>V85cog</td><td>km/s</td><td>HI line width enclosing 85% of total flux <sup>(2)</sup></td></tr>
                <tr><td>e_V85cog</td><td>km/s</td><td>Uncertainty in V85cog</td></tr>
                <tr><td>HIfluxcog</td><td>Jy km/s</td><td>Total HI <sup>(2)</sup></td></tr>
                <tr><td>e_HIfluxcog</td><td>Jy km/s</td><td>Uncertainty in HIfluxcog</td></tr>
                <tr><td>SNRcog</td><td>---</td><td>Signal-to-noise ratio from curve-of-growth measurement</td></tr>
                <tr><td>Dis</td><td>Mpc</td><td>Distance derived from Cosmicflows-4</td></tr>
                <tr><td>logMHI</td><td>solMass</td><td>Logarithm of HI mass in solar unit</td></tr>
                <tr><td>e_logMHI</td><td>solMass</td><td>Uncertainty in logMHI</td></tr>
                <tr><td>HIcode</td><td>---</td><td>HI detection category code; G=good, L=low S/N</td></tr>
                <tr><td>OCcode</td><td>---</td><td>Optical counterpart category code <sup>(3)</sup></td></tr>
                <tr><td>PbestOC</td><td>---</td><td>Probability of the best optical counterpart</td></tr>
                <tr><td>PbestOCRef</td><td>---</td><td>Reference optical survey used for counterpart matching</td></tr>
                <tr><td>No.</td><td>---</td><td>Internal running sequence number</td></tr>
                <tr><td>sofia_id</td><td>---</td><td>SoFiA source id</td></tr>
                <tr><td>Notes</td><td>---</td><td>Additional notes just for reference</td></tr>
            </tbody>
        </table>
        
        <div class="info-box" style="margin-top: 2rem;">
            <h3 class="info-box-title">Notes</h3>
            <ul style="margin-bottom: 0;">
                <li><strong>(1)</strong>: By method given in Springob et al. 2005 [<a href="https://ui.adsabs.harvard.edu/abs/2005ApJS..160..149S/abstract" target="_blank">2005ApJS..160..149S</a>].</li>
                <li><strong>(2)</strong>: From curve-of-growth method in Yu et al. 2020 [<a href="https://ui.adsabs.harvard.edu/abs/2020ApJ...898..102Y/abstract" target="_blank">2020ApJ...898..102Y</a>].</li>
                <li><strong>(3)</strong>: G = good; B = bad; C = confused; U = uncertain.</li>
            </ul>
        </div>
    </section>
</div>
