# Wangechii

A deployed multimedia website that presents images and video through a simple, shareable browsing experience.

[Live demo](https://wangechii.vercel.app) · [Source code](https://github.com/ryanilahalwa/Wangechii)

> A completed first deployment demonstrating frontend fundamentals, multimedia asset organization, responsive presentation, and public delivery with Vercel.

## Recruiter quick scan

| Area | Evidence |
|---|---|
| Frontend | HTML5, CSS3, JavaScript, static site structure |
| User experience | Simple shareable presentation of image and video content |
| Media | Organized photo and video assets for browser delivery |
| Deployment | Public Vercel deployment with a working live demo |
| Quality focus | Responsive design, accessibility, media performance, browser compatibility |
| Current level | Completed first deployed website and foundation for further frontend refinement |

## Overview

Wangechii is a compact static website focused on presenting personal multimedia content with a clear, shareable browsing experience. The project demonstrates the ability to take a small idea from a local HTML page to a publicly accessible deployment.

## What I built

- Designed a static website around multimedia content.
- Structured image and video assets for browser delivery.
- Created a simple navigation and presentation experience.
- Organized the site entry point and media files under the `Wangechi/` directory.
- Published the project publicly using Vercel.
- Added repository documentation and contribution guidance.

## Features

- Photo and video presentation in one shareable website.
- Static frontend structure with a focused user experience.
- Local media assets organized for predictable relative paths.
- Public deployment accessible through the live demo link.

## Technology stack

- **Structure:** HTML5
- **Styling:** CSS3
- **Behaviour:** JavaScript
- **Media:** JPEG images and MP4 video assets
- **Deployment:** Vercel

## Project structure

```text
Wangechi/
├── index.html
├── photo1.jpeg ... photo6.jpeg
├── video1.mp4 ... video5.mp4
└── supporting multimedia assets
```

The site entry point and media assets are kept together so that relative paths remain easy to understand during local development and deployment.

## Quality and accessibility

The project is a foundation for frontend quality practice. The next formal review should cover:

- semantic HTML structure;
- keyboard navigation;
- meaningful alternative text for images;
- readable colour and text presentation;
- responsive behaviour across mobile and desktop widths;
- video controls and captions where appropriate;
- browser compatibility for local media playback.

These items are documented as improvement areas rather than claims that every accessibility criterion has already been completed.

## Performance considerations

Because the project contains image and video assets, performance considerations include:

- reducing image and video file sizes;
- using responsive media dimensions;
- avoiding unnecessary media downloads;
- testing loading behaviour on slower connections;
- converting suitable images to modern formats such as WebP or AVIF;
- adding lazy loading where it does not harm the browsing experience.

## Local development

Clone the repository and open `Wangechi/index.html` in a browser, or serve the repository with a local static server so that relative media paths behave consistently.

```bash
git clone https://github.com/ryanilahalwa/Wangechii.git
cd Wangechii
```

A local static server can be used for development when direct file opening is not sufficient.

## Deployment

The project is deployed publicly through Vercel:

**Live demo:** https://wangechii.vercel.app

## Current status and roadmap

**Completed first deployed website.** Planned improvements include:

- formal responsive-design testing;
- keyboard and screen-reader accessibility review;
- media compression and modern image formats;
- reusable components if the site grows beyond a single page;
- improved navigation and descriptive metadata;
- performance checks using browser developer tools.

## Lessons learned

This project strengthened my experience with static web structure, visual presentation, multimedia asset organization, relative file paths, deployment, and documenting a finished project for other developers and recruiters.

## Kurzbeschreibung

Wangechii ist eine bereitgestellte Multimedia-Website mit HTML, CSS und JavaScript. Das Projekt zeigt praktische Erfahrungen mit responsivem Webdesign, der Organisation von Bild- und Videodateien sowie der Veröffentlichung einer funktionsfähigen Website mit Vercel. Weitere Verbesserungen sind für Barrierefreiheit, Medienoptimierung und Performance geplant.

## Contributing

Contribution guidance is available in [`CONTRIBUTING.md`](./CONTRIBUTING.md). Suggestions focused on accessibility, responsive behaviour, media performance, and documentation are especially welcome.

## License

No explicit open-source license is currently declared in the repository. Add a license before inviting external reuse of the source code.
