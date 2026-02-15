---
layout: default
title: HD2 Data
---

<div class="page-header">
    <div class="container">
        <h1 class="page-title">HD2 Data Products</h1>
        <p class="page-subtitle">Download Catalogs, Spectra, and Images</p>
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
            <strong>Current Release:</strong> Data Release 1 (DR1) - [Status: Planned/In Progress/Released]<br>
            <strong>Release Date:</strong> [Date]<br>
            <strong>Coverage:</strong> [Percentage] of the full survey area
        </div>
        
        <table>
            <thead>
                <tr>
                    <th>Release</th>
                    <th>Date</th>
                    <th>Coverage</th>
                    <th>Status</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>DR1</td>
                    <td>[Date]</td>
                    <td>[X] deg²</td>
                    <td>[Status]</td>
                </tr>
                <tr>
                    <td>DR2</td>
                    <td>Planned</td>
                    <td>[X] deg²</td>
                    <td>Planned</td>
                </tr>
                <tr>
                    <td>Final</td>
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
            <span class="data-icon">📋</span>
            <div class="data-info">
                <div class="data-title">HD2 DR1 Source Catalog</div>
                <div class="data-meta">FITS format | [N] sources | [Size] MB</div>
            </div>
            <div class="data-action">
                <a href="#" class="btn btn-primary">Download</a>
            </div>
        </div>
        
        <div class="data-card">
            <span class="data-icon">📊</span>
            <div class="data-info">
                <div class="data-title">HD2 DR1 Source Catalog (CSV)</div>
                <div class="data-meta">CSV format | [N] sources | [Size] MB</div>
            </div>
            <div class="data-action">
                <a href="#" class="btn btn-primary">Download</a>
            </div>
        </div>
        
        <h3 class="section-subtitle">Catalog Columns</h3>
        <table>
            <thead>
                <tr>
                    <th>Column</th>
                    <th>Unit</th>
                    <th>Description</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>ID</td>
                    <td>-</td>
                    <td>Unique source identifier</td>
                </tr>
                <tr>
                    <td>RA</td>
                    <td>deg</td>
                    <td>Right Ascension (J2000)</td>
                </tr>
                <tr>
                    <td>DEC</td>
                    <td>deg</td>
                    <td>Declination (J2000)</td>
                </tr>
                <tr>
                    <td>GLON</td>
                    <td>deg</td>
                    <td>Galactic longitude</td>
                </tr>
                <tr>
                    <td>GLAT</td>
                    <td>deg</td>
                    <td>Galactic latitude</td>
                </tr>
                <tr>
                    <td>VEL</td>
                    <td>km/s</td>
                    <td>Heliocentric velocity</td>
                </tr>
                <tr>
                    <td>VEL_ERR</td>
                    <td>km/s</td>
                    <td>Velocity uncertainty</td>
                </tr>
                <tr>
                    <td>FLUX</td>
                    <td>Jy km/s</td>
                    <td>Integrated flux</td>
                </tr>
                <tr>
                    <td>FLUX_ERR</td>
                    <td>Jy km/s</td>
                    <td>Flux uncertainty</td>
                </tr>
                <tr>
                    <td>W50</td>
                    <td>km/s</td>
                    <td>Line width at 50% of peak</td>
                </tr>
                <tr>
                    <td>W20</td>
                    <td>km/s</td>
                    <td>Line width at 20% of peak</td>
                </tr>
                <tr>
                    <td>S/N</td>
                    <td>-</td>
                    <td>Signal-to-noise ratio</td>
                </tr>
                <tr>
                    <td>LOGMHI</td>
                    <td>M☉</td>
                    <td>Log of HI mass (for known distance)</td>
                </tr>
            </tbody>
        </table>
    </section>
    
    <!-- Data Cubes -->
    <section class="content-section">
        <h2 class="section-title">Data Cubes</h2>
        
        <p>The following data cubes are available for download. Each cube covers a portion of the HD2 survey area.</p>
        
        <div class="data-card">
            <span class="data-icon">🧊</span>
            <div class="data-info">
                <div class="data-title">HD2 Cube - Field 1</div>
                <div class="data-meta">FITS cube | RA: [X]-[Y], Dec: [A]-[B] | [Size] GB</div>
            </div>
            <div class="data-action">
                <a href="#" class="btn btn-primary">Download</a>
            </div>
        </div>
        
        <div class="data-card">
            <span class="data-icon">🧊</span>
            <div class="data-info">
                <div class="data-title">HD2 Cube - Field 2</div>
                <div class="data-meta">FITS cube | RA: [X]-[Y], Dec: [A]-[B] | [Size] GB</div>
            </div>
            <div class="data-action">
                <a href="#" class="btn btn-primary">Download</a>
            </div>
        </div>
        
        <div class="alert alert-warning">
            <strong>Note:</strong> Data cubes are large files (several GB each). Please ensure you have sufficient storage and bandwidth before downloading.
        </div>
    </section>
    
    <!-- Spectra -->
    <section class="content-section">
        <h2 class="section-title">Individual Spectra</h2>
        
        <p>Spectra for individual detected sources are available in the following formats:</p>
        
        <div class="data-card">
            <span class="data-icon">📈</span>
            <div class="data-info">
                <div class="data-title">HD2 DR1 Spectra (ASCII)</div>
                <div class="data-meta">ASCII format | [N] spectra | [Size] MB</div>
            </div>
            <div class="data-action">
                <a href="#" class="btn btn-primary">Download</a>
            </div>
        </div>
        
        <div class="data-card">
            <span class="data-icon">📈</span>
            <div class="data-info">
                <div class="data-title">HD2 DR1 Spectra (FITS)</div>
                <div class="data-meta">FITS format | [N] spectra | [Size] MB</div>
            </div>
            <div class="data-action">
                <a href="#" class="btn btn-primary">Download</a>
            </div>
        </div>
    </section>
    
    <!-- Ancillary Data -->
    <section class="content-section">
        <h2 class="section-title">Ancillary Data</h2>
        
        <div class="data-card">
            <span class="data-icon">🗺️</span>
            <div class="data-info">
                <div class="data-title">HD2 Coverage Map</div>
                <div class="data-meta">PNG/PDF format | Survey footprint visualization</div>
            </div>
            <div class="data-action">
                <a href="#" class="btn btn-primary">Download</a>
            </div>
        </div>
        
        <div class="data-card">
            <span class="data-icon">📋</span>
            <div class="data-info">
                <div class="data-title">Observation Log</div>
                <div class="data-meta">ASCII format | Observation dates and parameters</div>
            </div>
            <div class="data-action">
                <a href="#" class="btn btn-primary">Download</a>
            </div>
        </div>
    </section>
    
    <!-- Data Policy -->
    <section class="content-section">
        <h2 class="section-title">Data Policy</h2>
        
        <h3 class="section-subtitle">Usage Rights</h3>
        <p>HD2 data products are released under [specify license, e.g., CC BY 4.0]. Users are free to:</p>
        <ul>
            <li>Use the data for any research purpose</li>
            <li>Share and redistribute the data</li>
            <li>Create derivative works</li>
        </ul>
        
        <h3 class="section-subtitle">Citation Requirements</h3>
        <p>Publications using HD2 data must include the following citations:</p>
        <ul>
            <li>[Primary survey paper citation]</li>
            <li>Appropriate acknowledgment of the FAST telescope</li>
        </ul>
        
        <h3 class="section-subtitle">Acknowledgment Text</h3>
        <div class="alert alert-info">
            <em>"This research made use of data from the HD2 Survey, a FAST HI survey conducted by the CCG group. The Five-hundred-meter Aperture Spherical radio Telescope (FAST) is a national major science research facility in China, operated by the National Astronomical Observatories, Chinese Academy of Sciences."</em>
        </div>
    </section>
    
    <!-- Contact -->
    <section class="content-section">
        <h2 class="section-title">Data Access Questions</h2>
        <p>For questions about data products, format, or access issues, please contact [contact email] or visit our <a href="{{ '/people' | relative_url }}">people page</a>.</p>
    </section>
    
    <!-- Editing Note -->
    <section class="content-section">
        <div class="info-box">
            <h3 class="info-box-title">Managing Data Downloads</h3>
            <p>To add or update data products:</p>
            <ol>
                <li>Upload data files to your repository (consider using Git LFS for large files)</li>
                <li>Update the download links in <code>hd2/data.md</code></li>
                <li>Update file sizes and source counts</li>
                <li>For very large files, consider hosting externally (e.g., Zenodo, institutional repository) and linking here</li>
            </ol>
        </div>
    </section>
</div>
