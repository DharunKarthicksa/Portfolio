# Dharun Karthick SA — Portfolio

A single-page personal portfolio site — Data & AI Engineer at iLink Digital (Microsoft Fabric, Real-Time Intelligence, Databricks, Power BI). Built with plain HTML, CSS, and JavaScript — no build step, no dependencies.

## Structure

- `index.html` — the entire site (styles and scripts inlined).

## Editing

All content lives in `index.html`, organized by section:

- Hero — name, tagline, and at-a-glance stats
- About — bio and quick-facts card
- Skills — tag groups for languages, data engineering, platforms, and AI
- Certifications — Microsoft and Databricks credentials
- Projects — iWeave, GreenSky, and Digital Twin / RTI showcases
- Experience — roles at iLink Digital and education
- Contact — email, LinkedIn, and GitHub links

## Running locally

Just open `index.html` in a browser, or serve it:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploying with GitHub Pages

1. Push this repo to GitHub (see push instructions).
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to *Deploy from a branch*.
4. Choose branch `main` and folder `/ (root)`, then **Save**.
5. Your site will be live at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

For a personal site at `https://<your-username>.github.io`, name the repository exactly `<your-username>.github.io`.
