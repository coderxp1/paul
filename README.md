# Paul Hartmann — Portfolio

Static multi-page portfolio for [paulhartmann.dev](https://paulhartmann.dev), built with HTML, CSS and vanilla JavaScript.

## Run locally

Open `index.html`, or serve this directory:

```sh
python3 -m http.server 8000
```

Visit http://localhost:8000.

## Pages

- Home, Projects, Repositories, About, Pricing and Contact
- Individual pages for TuGPT, KuikChat, CoderXP, GetWink, Orba Agent and The Infected
- Privacy Policy and Terms & Conditions (review drafts)

Includes six project screenshots, mobile navigation, project search and filters, a custom PAUL HARTMANN wordmark/preloader, background scene controls and a video reel. The home experience uses video and stills, not a live interactive 3D engine. No personal portrait is included.

## Deploy to IONOS

Upload all `.html` files, `style.css`, `app.js`, and the entire `assets/` folder to the domain's configured document root. They must remain together. Do not nest the media as `assets/assets/`.

No build command, Node server, database or API keys are required. This repository does not include an authentication, payment or checkout backend. Contact buttons open email.

## Latest updates

- KuikChat links use https://www.kuikchat.io and its user-supplied screenshot is included.
- Reel caption: **Paul Hartmann — Motion Reel**.
- Visual Credits section and its footer links removed as requested.
- Complete media folder included to prevent missing logo, image and video errors.

## Editing and pre-launch review

Edit each HTML file for content, `style.css` for appearance and `app.js` for interactions. Shared navigation/footer markup is repeated across pages.

Pricing uses custom quotes; no fixed commercial rates are asserted. Legal pages are visibly marked as drafts and require verified operator details, applicable jurisdiction, effective date and review of actual hosting/data practices before being treated as final. Confirm the supplied biography and education claims. No tracking or remote social embeds are added by this source.

Reference artwork and montage were supplied for the redesign from Merci-Michel; they are not Paul's client case studies. Confirm appropriate public-use rights. The supplied KuikChat screenshot has its browser toolbar cropped; other venture screenshots were captured from the respective websites.

## Checks

Fourteen routes were checked at desktop (1440×900) and mobile (390×844). Navigation, search/filter states, mobile menu, pricing accordion, reel and scene controls were exercised. Follow-up checks covered the KuikChat update, reel caption and credits removal. Test again after deployment, including media loading and autoplay behavior on the target browser.

Pushing this repository does not itself change IONOS hosting or configure GitHub Pages.
