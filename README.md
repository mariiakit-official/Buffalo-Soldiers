# Buffalo Soldiers — My Inner Army

**Live site:** https://mariiakit-official.github.io/Buffalo-Soldiers/

An interactive visual story built as a **static website**, not a video game. Eight original illustrated historical-inspired female characters embody personal and professional traits for the Buffalo Soldiers self-reflection assignment.

## Features
- Four Personal World / Dark Fantasy character cards
- Four Professional World / Hybrid Universe character cards
- Each character opens a full profile: name/rank, attributes, strengths, weaknesses, allies, conflicts, effect on relationships, needed armor, armor source, visual symbolism
- Alliance and tension cards
- Interpersonal conflict example, strategy, and desired outcome
- Personal reflection
- Responsive layout, keyboard-friendly dialog, reduced-motion support, alt text
- No build step, no database, no accounts, no gameplay

## Preview locally
Open `index.html` in a browser. For best results, serve this directory with a static file server, e.g. run `python -m http.server 8000` here and visit http://localhost:8000.

## Publish on GitHub Pages
1. Create a new **public** repository on your chosen GitHub account, e.g. `buffalo-soldiers`.
2. Upload everything in this folder **to the repository root** (including `assets/`). Or clone the repository locally, copy these files, then commit and push.
3. Go to **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select **main**, choose **/(root)** and Save.
4. Once Pages deploys, your site will usually be at `https://YOUR-USERNAME.github.io/buffalo-soldiers/` (replace username and repo name).

The site uses relative file paths and works as a project site without any adjustments.

## Personalization
Edit the `soldiers` array in `app.js` for character profiles; edit `index.html` for story sections; edit `styles.css` for layout and colors. Each artwork lives in `assets/`.

## Notes
The historical figures are **symbolic artistic inspirations**, not factual representations of their psychological characteristics. This presentation reflects the author's personal interpretation. Review first-person text for accuracy before sharing publicly.

Fonts load from Google Fonts when internet access is available and fall back to system fonts otherwise. No analytics or tracking scripts are included.
