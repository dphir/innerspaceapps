# InnerSpace

A privacy-first reflective journaling app (prototype). InnerSpace helps people write even when they can't name what they feel, notice emotional patterns over time, and prepare for professional support if they choose to seek it.

## Status
Private MVP, under testing. It is a reflection tool, not a medical device, and it does not diagnose or treat any condition.

## Features
- **Safe Space**: a guided journal with six optional questions, followed by emotion naming where the user decides the label
- **Free writing**: reflection, gratitude, and insight notes
- **Self-awareness dashboard**: emotional trends, emotional vocabulary, and a monthly summary
- **My Journey**: history, Then & Now comparison, and a descriptive summary of change based only on the user's own writing
- Indonesian and English interface

## Privacy by design
- **Local-first**: notes are stored only in the browser on the user's device. No accounts, servers, analytics, ads, or third-party requests.
- Strict Content-Security-Policy, no referrer, and no search indexing.
- User controls: JSON export and import, and delete-all.
- Not yet encrypted at rest (planned).

## Tech
Single-file vanilla HTML, CSS, and JavaScript, packaged as a PWA (web manifest and service worker) and served as a static site.

## License
Copyright (c) 2026 [Your full name]. All rights reserved. See `LICENSE`.
