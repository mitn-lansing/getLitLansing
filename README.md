# Get Lit Lansing

**Cool people, doing cool sh\*t.**

This is the website for Get Lit Lansing, Mid-Michigan’s community tech showcase. The event was previously known as Demo Camp Lansing.

## What is Get Lit Lansing?

Get Lit Lansing is where the local tech community comes together to showcase their latest creations.
Whether you've built an app, designed a website, created a gadget, or launched a startup, this is your stage to share it with fellow makers and innovators.

## Format

The night runs as an **interactive fair**. Presenters set up a table or booth, and attendees walk around, mingle, and talk directly with the people behind each project.

- Room for up to 40 presentation setups
- Screens available for presenters who want to show digital content
- Optional 5–7 minute speaking slots for anyone who would rather give a formal talk
- Lightning talk blocks (3–5 minutes each) as an alternative speaking format
- Built-in time to mingle between any formal presentations

Attendees can visit tables, attend talks, or both.

## Who it's for

MSU students and faculty (including Burgess Institute, MSU Technology, and LEAP), local tech groups and startups, local Lansing businesses, game developers, robotics clubs, and anyone working on interesting technology projects in Lansing.

## Next event

- **When:** Tuesday, November 10, 2026, 4:30 PM – 9:00 PM
- **Where:** MSU Federal Credit Union, 7th floor, [311 Abbot Rd](https://www.google.com/maps/search/?api=1&query=311+Abbot+Rd,+East+Lansing,+MI+48823), East Lansing, MI 48823
- **Cost:** Free — [RSVP on Luma](https://luma.com/nsgv3u1y)

Presenters (tables and talks) sign up through the [Get Lit Lansing presenter form](https://forms.gle/3aE34iejLinmuGDcA).
Attendees register on [Luma](https://luma.com/nsgv3u1y), or grab the [calendar invite](assets/get-lit-lansing-2026.ics).

## Site notes

Plain static HTML, served by GitHub Pages from the repo root with `.nojekyll` (no build step).

- `index.html` — the whole page; styles are inline in `<head>`, as is the `schema.org/Event` JSON-LD.
  Update the JSON-LD `startDate`/`endDate`/`offers` whenever the event details change.
- `404.html`, `robots.txt`, `sitemap.xml`, `site.webmanifest`, `favicon.ico`
- `assets/favicon.svg`, `assets/icon-*.png`, `assets/apple-touch-icon.png` — the LIT mark, drawn as
  plain rects so it stays crisp at 16px. Regenerate the PNGs from the SVGs with headless Chrome.
- `assets/og-cover.png` — 1200x630 social card, downscaled from `assets/cover-luma.png`.
- `assets/cover.html` — source for the cover images; see the comment at the top for the render command.
- `assets/get-lit-lansing-2026.ics` — calendar invite (times stored as UTC).
- `assets/sponsors/` — sponsor logos, kept local so the sponsor wall cannot break when a
  sponsor reorganizes their own site.

A "Good to know" section (parking, after-hours building access, food, accessibility) is stubbed out
in `index.html` as an HTML comment. Fill in the real details and uncomment it, along with its nav link.

## Get involved

Reach out through the [Lansing Codes](https://www.lansing.codes/) website or Slack.
