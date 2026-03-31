# dyslexi
Web extension tool for dyslexia
A browser extension prototype designed to make reading on the web easier for people with dyslexia. Part of The Human Factor group project at University of Edinburgh.

FEATURES
--------
Personalisation quiz:
answers five questions about how you experience reading (e.g. do letters blur? do words crowd together?) and builds a named reading profile that applies the right settings automatically.
Text tools:
change font, size, line height, word spacing, letter spacing, and alignment. Includes dyslexia-friendly fonts like OpenDyslexic and Lexend Exa.
Colour tools:
switch between high-contrast presets (Navy & Gold, Forest & Coral, Midnight & Mint, Parchment & Navy) or add a semi-transparent colour overlay to reduce visual stress.
Audio:
text-to-speech (tts) with adjustable reading speed and a word-by-word highlight that follows along as the page is read aloud.
Reading tools:
reading ruler, focus mode, sentence focus, syllable splitting (breaks long words into syl·la·bles), and a circular magnifier.
Translate:
translates the page into 20 languages using the MyMemory API. No account linking needed.
OCR:
upload a photo of printed text and extract the words using Tesseract.js directly in the browser. No data is sent anywhere.

HOW TO USE
----------
1. Download or clone this repository
2. Open index.html in any modern browser (Chrome recommended for best speech support)
3. Click the octopus icon in the top-right corner of the browser bar to open the DysLexi panel

TECH
----
Pure HTML, CSS, and basic JavaScript
Tesseract.js for in-browser OCR
MyMemory API for translation (free tier, no key required)
OpenDyslexic font loaded via CDN
All mascot illustrations made by me (Iulia) in Pixlart
