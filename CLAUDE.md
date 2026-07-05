# yerry262.github.io

## Project Overview

Jerry Steele's main GitHub Pages site. This is the primary web presence and landing page for all of Jerry's projects and online presence.

## Purpose

- **Central Hub**: Links to all major projects and portfolios
- **Professional Presence**: GitHub Pages hosting
- **Portfolio Showcase**: Highlights key work and accomplishments
- **Navigation**: Easy access to all project sites

## What's Hosted Here

This repository serves as the main GitHub Pages domain at [https://yerry262.github.io](https://yerry262.github.io), which provides:

- Navigation to all project sites
- Brief introduction and bio
- Project links and descriptions
- Contact information
- Resume and credentials

## Subdomains & Project Sites

Project-specific sites are hosted on subdomains:

### Featured Projects
- **Spotify Visualizer**: [/Spotify-Webapp-Visualizer](https://yerry262.github.io/Spotify-Webapp-Visualizer)
- **Cancer Atlas**: [/CancerProgressionAtlas](https://yerry262.github.io/CancerProgressionAtlas)
- **Smart Home**: [/SmartHouse2524](https://yerry262.github.io/SmartHouse2524)
- **Connect 4**: [/Connect4](https://yerry262.github.io/Connect4)
- **ChainChat**: [/ChainChat](https://yerry262.github.io/ChainChat)
- **Home Run Derby**: [/HomeRunDerby](https://yerry262.github.io/HomeRunDerby)
- **Modern Thesaurus**: [/Modern-thesaurus](https://yerry262.github.io/Modern-thesaurus)
- **Personal Website**: [/Personal_Website](https://yerry262.github.io/Personal_Website)

## Tech Stack

- **Hosting**: GitHub Pages
- **Domain**: yerry262.github.io
- **Architecture**: Static site (can be Jekyll-based or React SPA)
- **Deployment**: Automatic from repository

## Structure

```
yerry262.github.io/
├── index.html              # Main landing page
├── README.md              # GitHub repo description
├── CLAUDE.md              # This file
├── css/                   # Styles
├── js/                    # Scripts
├── assets/                # Images and media
└── [project-dirs]/        # Individual project builds
```

## How It Works

1. Each project repository contains a build output
2. Project builds are deployed to subdirectories
3. Main index.html serves as landing page
4. GitHub Pages handles automatic hosting

## Deployment

Projects deploy to this domain via:

1. GitHub Actions workflows in each project repo
2. Automated builds on push to main
3. Deploy step copies build output to appropriate subdirectory
4. Changes go live immediately (usually within minutes)

## Adding New Projects

To add a new project site:

1. Update main index.html with project link
2. Create project build directory on main branch
3. Push project site contents to subdirectory
4. Verify at yerry262.github.io/project-name

## Navigation

The main site provides:
- **Featured Projects**: Highlighted current work
- **All Projects**: Complete list of active projects
- **About**: Biography and contact info
- **Skills**: Technical expertise overview
- **Contact**: Email and social links

## Performance

- Fast page loads (static hosting)
- CDN-backed by GitHub's infrastructure
- HTTPS enabled
- Mobile-responsive design

## SEO & Analytics

- Clean URLs for all projects
- Meta tags for social sharing
- Open Graph support
- Optional analytics integration

## Customization

To update the main landing page:

1. Edit index.html for structure
2. Update CSS in css/ directory
3. Add new images to assets/
4. Commit and push to main branch
5. Changes deploy automatically

## Known Limitations

- Static site only (no backend needed)
- Custom domains require CNAME setup
- Large projects should be versioned separately
- Build artifacts from other repos take disk space

## Future Enhancements

- Unified search across all projects
- Project showcase with thumbnails
- Dark mode toggle
- Project filtering and tags
- Blog or news section
- Development blog

## Links & References

- **GitHub Profile**: [@yerry262](https://github.com/yerry262)
- **GitHub Help**: [GitHub Pages docs](https://docs.github.com/en/pages)
- **Main Site URL**: https://yerry262.github.io
- **Contact**: jerry21steele@gmail.com

## Last Updated

2026-07-05
