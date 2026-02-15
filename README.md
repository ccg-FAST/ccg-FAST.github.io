# FAST HI Survey Website

This is the official website for the FAST HI Survey projects by the CCG group, hosted on GitHub Pages.

## Website Structure

```
.
├── _config.yml          # Jekyll configuration
├── _layouts/            # Page templates
│   └── default.html     # Main layout template
├── _includes/           # Reusable components
│   ├── header.html      # Site header with navigation
│   └── footer.html      # Site footer
├── assets/
│   └── css/
│       └── main.css     # Main stylesheet
├── hd2/                 # HD2 Survey pages
│   ├── index.md         # HD2 overview
│   ├── science.md       # Science goals
│   ├── observation.md   # Observation status
│   ├── publications.md  # Papers
│   └── data.md          # Data downloads
├── m31/                 # M31 Survey pages
│   ├── index.md         # M31 overview
│   ├── science.md       # Science goals
│   ├── observation.md   # Observation status
│   ├── publications.md  # Papers
│   └── data.md          # Data downloads
├── index.md             # Homepage
├── people.md            # Team members
└── links.md             # Useful links
```

## Editing Content

All pages are written in **Markdown** format, making them easy to edit. You can edit pages directly on GitHub or clone the repository and edit locally.

### Quick Editing Guide

1. **Homepage**: Edit `index.md`
2. **People page**: Edit `people.md`
3. **Links page**: Edit `links.md`
4. **HD2 pages**: Edit files in the `hd2/` folder
5. **M31 pages**: Edit files in the `m31/` folder

### Markdown Basics

```markdown
# Heading 1
## Heading 2
### Heading 3

**Bold text**
*Italic text*

[Link text](URL)

- Bullet point 1
- Bullet point 2

1. Numbered item 1
2. Numbered item 2

| Table | Header |
|-------|--------|
| Cell  | Cell   |
```

### Adding Publications

To add a new publication, edit the `hd2/publications.md` or `m31/publications.md` file and add:

```markdown
<div class="card" style="margin-bottom: var(--space-4);">
    <div class="card-body">
        <h3 class="card-title">Your Paper Title</h3>
        <p class="card-text">
            <strong>Authors:</strong> Author list<br>
            <strong>Journal:</strong> Journal name, Year<br>
            <strong>Abstract:</strong> Brief abstract
        </p>
        <div class="card-footer">
            <a href="arxiv-link" class="btn btn-outline">arXiv</a>
            <a href="journal-link" class="btn btn-outline">Journal</a>
        </div>
    </div>
</div>
```

### Adding Data Products

To add a downloadable data product, edit the `hd2/data.md` or `m31/data.md` file and add:

```markdown
<div class="data-card">
    <span class="data-icon">💾</span>
    <div class="data-info">
        <div class="data-title">Data Product Name</div>
        <div class="data-meta">Format | Size | Description</div>
    </div>
    <div class="data-action">
        <a href="download-link" class="btn btn-primary">Download</a>
    </div>
</div>
```

## Local Testing

To test the website locally before pushing to GitHub:

1. Install Jekyll (requires Ruby):
   ```bash
   gem install bundler jekyll
   ```

2. Install dependencies:
   ```bash
   bundle install
   ```

3. Run the local server:
   ```bash
   bundle exec jekyll serve
   ```

4. Open your browser to `http://localhost:4000`

## Customization

### Site Configuration

Edit `_config.yml` to change:
- Site title and description
- Navigation menu
- Default settings

### Styling

Edit `assets/css/main.css` to customize the appearance. The CSS uses CSS variables for easy theming:

```css
:root {
    --color-primary: #1a365d;    /* Main brand color */
    --color-accent: #3182ce;      /* Link and button color */
    --color-text: #2d3748;        /* Body text color */
    /* ... more variables */
}
```

## Deployment

The website is automatically deployed to GitHub Pages when you push changes to the main branch. No additional setup is required.

## Contact

For questions about the website, contact the CCG group or open an issue on GitHub.
