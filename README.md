# HearLink AAC — Pediatric

A small, bilingual Hindi-English augmentative and alternative communication (AAC) web prototype designed to help children express everyday needs, feelings, choices, school messages, play interests, and social messages.

## What is included

- Large, touch-friendly communication buttons and a persistent quick-message row for help, stop, yes/no, toilet, drink, food, pain, break, and getting a trusted adult.
- Topic boards for everyday words, needs, feelings, people, school, play, body/health, social communication, and personal buttons.
- Hindi/English interface toggle with example spoken phrases.
- A simple message builder: tap starter words and connectors, edit the message, then choose when to speak it.
- Local saved messages, custom buttons, speech-rate selection, available device voices, and larger text.
- Export/import of a JSON backup for personal buttons and saved messages.
- A basic service worker for offline caching after the first successful load.

## Run locally

1. Download or clone this repository.
2. Open `index.html` in a modern browser, or serve the folder with a local static server (recommended for service-worker testing).
3. Allow the browser to use speech synthesis and test the available Hindi and English voices on the target device.
4. Open **Grown-up settings** to add and export personal buttons.

GitHub Pages can host this as a static site from **Settings → Pages → Deploy from a branch → main → /(root)** after the changes have been reviewed and merged.

## Important limitations and safe use

- This is a prototype, not a clinically validated AAC system, medical device, diagnostic tool, or replacement for assessment and support by an AAC/SLP team.
- The child should remain in control of what they communicate. Adults should personalise vocabulary with the child, respect refusals, and never require speech output as proof of communication.
- The starter phrases and word combinations are examples, not a grammar engine. Review the editable message before speaking.
- Speech output depends on browser support and voices installed on the device; pronunciation, language switching, volume, and latency vary by device. Always test on the actual device.
- The app does not call emergency services, contact caregivers, or guarantee audio routing to Bluetooth devices or hearing aids. Keep a reliable, accessible way to reach a trusted adult.
- Emoji are placeholders and may be ambiguous or display differently. Replace them with familiar, culturally appropriate, licensed symbols/photos following the child's preferences and access needs.
- Data is stored in browser local storage on that device. It is not a cloud backup and can be erased by browser settings. Export backups carefully and protect files that may contain personal information.
- No user accounts or remote storage are implemented. Do not add sensitive personal or medical information unless needed.
- The app has not been fully tested across browsers, devices, switch access, screen readers, or clinical settings. Test accessibility and obtain feedback from the child and their caregivers/clinicians before relying on it.

## Files

- `index.html` — app interface, vocabulary, message builder, speech, and local settings.
- `manifest.json` — installable web-app metadata.
- `sw.js` — simple offline cache.

## License

No explicit license is currently provided. Add an appropriate license before redistributing or reusing the code.
