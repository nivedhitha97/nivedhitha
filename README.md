# Nivedhitha Parthasarathy — Portfolio

Personal portfolio of Nivedhitha Parthasarathy, a mobile engineer working across native iOS (Swift, SwiftUI) and cross-platform React Native, based in Amsterdam.

**Live site:** https://nivedhitha97.github.io/nivedhitha/

## What's on the site

- **Selected work:** four production apps I worked on at Nesh (Assetmatics, FleetLive, myTVS Drive Plus and Montra Electric Driver), each with screenshots, my contributions and store links where the app is public.
- **Experience:** Nesh, Sensiple, freelance iOS work, and my current independent projects.
- **Engineering principles:** how I structure mobile apps.
- **Contact:** email, LinkedIn and GitHub.

## Built with

Plain HTML, CSS and JavaScript in a single `index.html`. There's no framework, build step or package manager; the only external resource is Google Fonts (DM Serif Display and DM Sans).

## Project structure

```
index.html              Page markup, styles and scripts
assets/screenshots/     App screenshots used in the hero and the work carousel
```

## Updating content

All project content lives in three objects near the bottom of `index.html`:

- **`PROJECTS`:** one entry per app, with its title, tagline, description, contributions, tags and the screens to show.
- **`IMGS`:** maps a two-letter code to a screenshot file. To add a screenshot, put the image in `assets/screenshots/`, give it a code here, then list that code in the project's `screens`.
- **`STORE_LINKS`:** App Store and Google Play links, keyed by project id. Leave the list empty for apps that aren't public.

## About the screenshots

The screenshots come from the apps' public App Store and Google Play listings and from my own development builds. Customer names, photos, vehicle numbers, fleet names and addresses have been blurred. The apps belong to their respective companies and are shown only to illustrate my work on them.

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Deployment

Hosted on GitHub Pages from the root of the `main` branch. Pushing to `main` updates the live site within a few minutes.

## Related repositories

- [Smart Meal Planner](https://github.com/nivedhitha97/SmartGroceryApp): SwiftUI iOS app that builds meal plans from dietary preferences and nutrition goals (MVVM, Combine)
- [CryptoApp](https://github.com/nivedhitha97/CryptoApp): React Native and TypeScript take-home assignment (Redux, Redux Saga)

## Contact

- Email: nivedhithapsarati@gmail.com
- LinkedIn: [linkedin.com/in/nivedhithap](https://www.linkedin.com/in/nivedhithap/)
