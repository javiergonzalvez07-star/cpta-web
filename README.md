# Applied Technical Projects Club Website

Official website repository for the **Club de Proyectos Técnicos Aplicados (CPTA)**, a student-led initiative created to help multidisciplinary teams turn technical ideas into structured, documented, and presentable projects.

The site communicates the club's mission, project groups, members, activities, and outcomes through a static website built with Hugo and deployed using GitHub Pages.

## About the club

CPTA was founded to create a practical environment where students can work beyond isolated coursework and develop projects that combine areas such as:

- mathematics;
- physics;
- engineering;
- data analysis;
- programming;
- simulation;
- scientific communication.

The emphasis is on completing a full technical cycle:

```text
problem definition
→ research and modelling
→ implementation or experiment
→ analysis
→ documentation
→ presentation
```

## Initial project groups

The first club cycle included teams working on topics such as:

- **Brownian motion** — stochastic and physical modelling;
- **airport operations** — computer vision, queueing theory, simulation, and operational dashboards;
- **sports analytics** — data-driven analysis of sporting performance and decisions.

## Website purpose

The website acts as the public documentation layer for the club:

- explain the club's objectives;
- present active project groups;
- introduce team members;
- publish project summaries and outcomes;
- provide a visible record of student-led technical work;
- support future recruitment and collaboration.

## Technology stack

- Hugo
- Markdown
- HTML / CSS
- Hugo Profile theme
- GitHub Actions
- GitHub Pages

## Deployment

The site is built and deployed automatically through GitHub Actions when changes are pushed to `main`.

The workflow:

1. checks out the repository and theme submodule;
2. installs Hugo Extended;
3. builds the static website;
4. uploads the generated site as a Pages artifact;
5. deploys it to GitHub Pages.

## Run locally

### Prerequisites

- Git
- Hugo Extended

Clone the repository including the theme submodule:

```bash
git clone --recurse-submodules https://github.com/javiergonzalvez07-star/cpta-web.git
cd cpta-web
```

Start the local development server:

```bash
hugo server -D
```

Open the local URL shown in the terminal.

## Repository structure

```text
.
├── .github/workflows/   # GitHub Pages deployment
├── archetypes/          # Hugo content templates
├── assets/              # Source styles and site assets
├── content/             # Club and project content
├── static/              # Images and static resources
├── themes/              # Hugo theme submodule
└── config.*             # Hugo site configuration
```

## Project-management value

This repository represents more than a website. It documents experience in:

- founding and coordinating a technical student initiative;
- organising multidisciplinary teams;
- defining project deliverables;
- communicating technical work to a broader audience;
- maintaining a public documentation platform;
- automating deployment with GitHub Actions.

## Contributing

Club members can contribute by:

1. creating a branch;
2. adding or updating project content;
3. checking the site locally;
4. opening a pull request with a clear description of the change.

## Maintainer

**Javier Gonzálvez Sempere**  
Founder and director of the Club de Proyectos Técnicos Aplicados.

- Portfolio: https://javiergonzalvez07-star.github.io/
- GitHub: https://github.com/javiergonzalvez07-star
