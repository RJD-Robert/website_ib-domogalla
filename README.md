# IB Domogalla Website

Static bilingual website for `ib-domogalla.de`, prepared for GitHub Pages.

## Structure

- `index.html` - German homepage
- `en/index.html` - English homepage
- `assets/styles.css` - shared visual styling
- `impressum/index.html` - legal notice placeholder
- `datenschutz/index.html` - privacy policy placeholder
- `robots.txt` and `sitemap.xml` - basic SEO files
- `CNAME` - custom domain for GitHub Pages

## Editing content

Project and service content is written directly in `index.html` and `en/index.html`.
Search for these headings to update the main placeholders:

- `Projekte` / `Projects`
- `Leistungen` / `Services`
- `&Uuml;ber IB Domogalla` / `About IB Domogalla`
- `Kontakt` / `Contact`

The current email placeholder is `kontakt@ib-domogalla.de`. Replace it everywhere if a different address should be public.

## GitHub Pages setup

1. Push this repository to GitHub.
2. Open the repository settings.
3. Go to `Pages`.
4. Set the source to deploy from the main branch and repository root.
5. Keep the `CNAME` file if `ib-domogalla.de` should point to this site.
6. Configure the DNS records for the domain according to GitHub Pages instructions.

## Before publishing

- Replace project placeholders with real project names, locations, years and scope.
- Complete the `Impressum` and `Datenschutzerklaerung` with legally reviewed text.
- Confirm the public email address.
- Replace or extend placeholder biography text with verified professional information.
