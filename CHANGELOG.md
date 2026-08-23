# Synergy VR Documentation Changelog

All notable changes to the Synergy VR documentation site, based on its
[deployments](https://github.com/synergyvr-org/synergy/deployments).

The site deploys continuously from `main`, so entries are grouped by date rather
than version. Each date collects everything that went live that day. The format
is based on [Keep a Changelog](https://keepachangelog.com/).

Synergy VR is still in development, and so are these docs.

## 2026-08-23

### Added
- A **show in list** button on every row of the load order. Filter down to the mod you're after, then click its row (or the crosshair at its right edge) and the filter drops away, leaving that mod highlighted where it actually sits in the list, with its folders opened around it. That's usually the question a filter can't answer: not whether a mod is in the list, but what loads next to it.
- More in-game screenshots in the cover rotation.

### Changed
- The load order starts with its folders closed, so the page opens as an outline of the list's sections instead of fourteen hundred mod names. Hit **Expand all** if you'd rather have the lot.
- The filter box searches versions as well as mod names.
- Rewrote the Load Order intros to explain all of the above.
- Page titles sit centered on their cover images now, rather than down at the bottom.

### Fixed
- The seam between the sidebar and the topbar. Three separate hairlines ran down that edge in grays borrowed from the theme's near-black defaults, so against the slate they read as a dark, two-tone gap rather than as a border. The sidebar and the topbar are one continuous panel now.
- Button and filename pills no longer leave a gap before the punctuation that follows them.

## 2026-08-22

### Added
- The whole site! It shares a Hugo module with the [MGO docs](https://synergyvr.org/mgo/),
  so it starts out with the same shortcodes, mod list tables, and console reference,
  and supplies its own content and look.
- The RC35 load order, filterable and searchable, with every mod linked to its
  Nexus page and the raw CSV available to download. The `Testing Tools — NOT FOR
  RELEASE` section is left out, since it ships with the list but isn't really part of it.
- Cover art on the page banners, from six in-game screenshots. More to come.
- A hero image on the Introduction page, and a favicon.
- Skyrim-generic reference pages carried over from the MGO docs: the console
  reference and its command list. Several more are in the repo as drafts, waiting
  on me to strip the MGO-specific bits.
- Chapter stubs for Getting Started, Performance, How To Play, Reference, and
  Tutorials.

### Changed
- A cooler, lighter look than MGO's: slate surfaces instead of near-black, cyan
  carrying the links and accents, and ember alert-asides. The colors come from the logo
  and the MO2 palette.
- The load order's section colors follow the list's own MO2 sections: a warm
  amber-to-brown run down the content half, blue from AI Improvements onward,
  light blue for the onboarding section, and amber again at the end.
- The sidebar is lighter than the content area, rather than darker.
- Alert-asides take their color from the flame half of the logo, rather
  than the muted rust from MGO's alerts.
