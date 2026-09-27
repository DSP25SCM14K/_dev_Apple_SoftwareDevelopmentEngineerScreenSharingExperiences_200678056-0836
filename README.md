# Dev Kumar — Screen Sharing and Apple Platform Engineering

A responsive static portfolio centered on native Apple development, screen sharing, remote interaction, real-time media, accessibility, and performance. The screen and phone artwork is authored as animated SVG/CSS; there is no third-party image dependency.

## Run locally

Open `index.html` in a browser or serve this directory with any static HTTP server.

## GitHub Pages

This site has no build step. Configure GitHub Pages to deploy from the `main` branch and repository root (`/`).

## Role and company research

The target is Apple's Software Development Engineer: Screen Sharing Experiences role (200678056-0836), based in Cupertino. Apple's description covers iPhone Mirroring, Screen Sharing, Sidecar, and related features, with an emphasis on viewing and remote control, accessibility, technical ownership, troubleshooting, throughput, reliability, cross-functional delivery, and clear communication. The portfolio therefore foregrounds the supplied experience building capture and encoding pipelines, low-latency transport, remote input, accessibility, diagnostics, and quality-focused delivery. It does not claim Apple employment or affiliation.

Apple's ScreenCaptureKit documentation describes screen and audio streaming with fine-grained source selection, and recommends the system sharing picker for choosing content and managing streams. That informed the consent-first, capture-to-render visual narrative.

- Apple job posting 200678056-0836: https://jobs.apple.com/en-us/details/200678056-0836/software-development-engineer-screen-sharing-experiences
- ScreenCaptureKit overview: https://developer.apple.com/documentation/ScreenCaptureKit
- Apple iOS capture sample: https://developer.apple.com/documentation/screencapturekit/capturing-screen-content-on-ios
- Apple accessibility: https://www.apple.com/accessibility/

## Files

- `index.html` — page content and animated screen-sharing background illustration
- `styles.css` — responsive layout, animation, visual pipeline, and accessibility motion preference
- `script.js` — project cards, rotating focus text, and reveal motion
