# Meridian Clock · 子午流注钟

An interactive Chinese meridian clock inspired by a traditional wall clock. Client-side HTML, CSS, JavaScript and SVG in a self-contained `index.html`. No framework, build step, external scripts, analytics or backend.

## Features

- Live analogue hour, minute and second hands with a 24-hour digital display.
- Two six-sector meridian rings, yin-yang centre and current-period highlight.
- Singapore, device, China and UTC timezone options.
- Clickable and keyboard-accessible sectors and a bilingual twelve-period guide.
- Responsive phone and desktop layout.

## Run locally

Open `index.html` in a modern browser, or serve this directory using any static HTTP server. All content and assets are inline.

## Deployment

GitHub Pages publishes from `main`, repository root. No API keys, server or custom domain is required.

## Content and limitations

Time/meridian mapping source: https://zh.wikipedia.org/wiki/%E5%AD%90%E5%8D%88%E6%B5%81%E6%B3%A8

This is a cultural illustration of traditional Chinese medicine, not a medical instrument, diagnosis, treatment or health recommendation. Times use the selected civil timezone, not solar time. Live time depends on the user's device clock. The inspiration photo's smaller health/lifestyle slogans are not included.

## Verification

All 24 hours, every two-hour boundary, the midnight crossover (23:00–01:00), and Singapore/UTC conversions were tested. The live preview was checked on phone and desktop with sector exploration, return to live time and timezone changes.
