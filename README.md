# litmus — a tone test for your text

A lightweight, browser-based text analysis tool. No data leaves your browser.

## Features
- Sentiment analysis (positive / negative / neutral) per sentence
- Character breakdown (uppercase, lowercase, digits, punctuation, symbols)
- Word tokenization
- File upload support — `.txt`, `.docx`, `.pdf`
- Sample texts to try instantly

## Live Demo
> After enabling GitHub Pages, your app will be live at:
> `https://<your-username>.github.io/<your-repo-name>/`

## How to Use
1. Type or paste text into the input box, **or** upload a `.txt`, `.docx`, or `.pdf` file
2. Click **"Test it →"** to run the analysis
3. View results: character trace, ingredient rings, sentence reactions, word molecules, and pH reading

## Tech
- Pure HTML, CSS, JavaScript — no frameworks, no build step
- [Mammoth.js](https://github.com/mwilliamson/mammoth.js) for `.docx` parsing
- [PDF.js](https://mozilla.github.io/pdf.js/) for `.pdf` parsing
- Google Fonts: Space Grotesk, Sora, Space Mono

## License
MIT
