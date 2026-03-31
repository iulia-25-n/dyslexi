# DysLexi
Web extension tool for dyslexia
A browser extension prototype designed to make reading on the web easier for people with dyslexia. Part of The Human Factor group project at University of Edinburgh.

FEATURES
--------
1. Personalisation quiz: answers five questions about how you experience reading (e.g. do letters blur? do words crowd together?) and builds a named reading profile that applies the right settings automatically.
2. Text tools: change font, size, line height, word spacing, letter spacing, and alignment. Includes dyslexia-friendly fonts like OpenDyslexic and Lexend Exa.
3. Colour tools: switch between high-contrast presets (Navy & Gold, Forest & Coral, Midnight & Mint, Parchment & Navy) or add a semi-transparent colour overlay to reduce visual stress.
4. Audio: text-to-speech (TTS) with adjustable reading speed and a word-by-word highlight that follows along as the page is read aloud.
5. Reading tools: reading ruler, focus mode, sentence focus, syllable splitting (breaks long words into syl-la-bles), and a circular magnifier.
6. Translate: translates the page into 20 languages using the MyMemory API. No account linking needed.
7. OCR: upload a photo of printed text and extract the words using Tesseract.js directly in the browser. No data is sent anywhere.

HOW TO USE
----------
1. Download or clone this repository
2. Open index.html in any modern browser (Chrome recommended for best speech support)
3. Click the octopus icon in the top-right corner of the browser bar to open the DysLexi panel

TECH
----
1. Pure HTML, CSS, and basic JavaScript
2. Tesseract.js for in-browser OCR
3. MyMemory API for translation (free tier, no key required)
4. OpenDyslexic font loaded via CDN
5. All mascot illustrations made by me (Iulia) in Pixlart
