<div align="center">

<img src="icon.svg" width="96" alt="The Hemogoblin icon" />

# Hemogoblin

**The website for Hemogoblin, a cycle tracker for iPhone, iPad and Apple Watch.**

The privacy policy, the terms of use, the support page and every rule behind the app's estimates,
served by GitHub Pages at **[chungus-actual.github.io/hemogoblin](https://chungus-actual.github.io/hemogoblin/)**.
The app's source isn't here.

![GitHub Pages](https://img.shields.io/badge/hosted%20on-GitHub%20Pages-222222?logo=github)
![Static HTML](https://img.shields.io/badge/static-HTML%20%2B%20CSS-9a2a57)
![No JavaScript](https://img.shields.io/badge/JavaScript-none-lightgrey)
![No trackers](https://img.shields.io/badge/trackers-none-lightgrey)

<img src="readme/home-light.jpg" width="49%" alt="The home page in the light theme" />
<img src="readme/home-dark.jpg" width="49%" alt="The home page in the dark theme" />

</div>

---

## The pages

| Page | Address | What it covers |
|---|---|---|
| **Home** | [/](https://chungus-actual.github.io/hemogoblin/) | What Hemogoblin is, and a card for each page below |
| **Privacy Policy** | [/privacy/](https://chungus-actual.github.io/hemogoblin/privacy/) | No accounts, no servers, no analytics, no ads, no trackers; the app makes no network connections and the developer never receives cycle data |
| **Terms of Use** | [/terms/](https://chungus-actual.github.io/hemogoblin/terms/) | Not a medical device and not birth control; the license is Apple's standard EULA, which these terms add to |
| **Support** | [/support/](https://chungus-actual.github.io/hemogoblin/support/) | The support address and common questions: moving to a new iPhone, backups and passphrases, Apple Health, the Watch |
| **How estimates work** | [/estimates/](https://chungus-actual.github.io/hemogoblin/estimates/) | Every rule behind every date the app shows, for Hemogoblin 1.1 |

## On a phone

| | | |
|:---:|:---:|:---:|
| <img src="readme/privacy-phone-light.jpg" width="100%" alt="The privacy policy on a phone, light theme" /><br><sub>Privacy Policy, light</sub> | <img src="readme/estimates-phone-dark.jpg" width="100%" alt="How estimates work on a phone, dark theme" /><br><sub>How estimates work, dark</sub> | <img src="readme/support-phone-dark.jpg" width="100%" alt="Support on a phone, dark theme" /><br><sub>Support, dark</sub> |

## How it's built

| | |
|---|---|
| **Files** | One `index.html` per page, a shared `style.css` and `icon.svg` |
| **Scripts** | None; the support questions open with plain `<details>` |
| **Requests** | None to third parties: no web fonts, CDNs or analytics. The only links out are Apple's standard EULA and GitHub's privacy statement |
| **Themes** | Light and dark, following the system setting (`prefers-color-scheme`) |
| **Hosting** | GitHub Pages from `main`, repository root; `.nojekyll` serves the files as they are |

## Editing

| Task | How |
|---|---|
| Preview | Open `index.html` in a browser, or `python3 -m http.server` in the repository and visit `localhost:8000` |
| Publish | Push to `main`; Pages redeploys within a minute or two |
| Change a policy | Update the "Effective" date at the top of `privacy/` or `terms/` along with the wording |
| Change an estimate rule | Update `estimates/` together with the app release that changes the rule, and its version line |

`readme/` holds the images on this page. Pages serves it like any other folder; no page links to it.

## Contact

[hemogoblinappsupport@gmail.com](mailto:hemogoblinappsupport@gmail.com)
