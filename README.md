# HydroQuantum.github.io

This site is live on [https://hydroquantum.githug.io](https://hydroquantum.githug.io)

This repository now contains a website for the quantum computing branch of Clemson University’s Hydrosystem and Hydroinformatics Research (HHR) Lab. It is structured around two core pages:

- `index.html`: landing page and site overview
- `papers/`: individual paper pages
- `about/index.html`: lab overview and member cards

## Editing guide

- Add new publications by duplicating `templates/paper-detail-template.html`, placing the new page in `papers/`, and linking it from `index.html`.
- Add or replace member images in `assets/img/members/`.
- Duplicate the member card snippet in `templates/member-card-template.html` when expanding the team section on `about/index.html`.
- Adjust the shared look and responsive behavior in `assets/css/styles.css` and `assets/js/site.js`.

## Notes

- The site content is intentionally scoped to the lab’s quantum computing work rather than the full HHR portfolio.
- Stylized SVG profile graphics are used in place of downloaded headshots.
- No framework, package manager, or external UI library is required.
