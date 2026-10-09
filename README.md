# Chapter Readability Checker

A free, privacy-friendly web tool for authors.

## Features
- Flesch Reading Ease score
- Flesch-Kincaid Grade Level estimate
- Word and sentence counts
- Average words per sentence
- Five hardest sentences
- Fully client-side: no backend and no text upload
- Responsive dark UI

## Run locally

Open `index.html` in a browser.

## Publish for free

The project can be deployed directly with GitHub Pages:
1. Create a GitHub repository.
2. Upload `index.html`.
3. Go to Settings -> Pages.
4. Select the main branch as the deployment source.
5. GitHub will provide a public URL.

## AI tools used

The initial implementation was generated with ChatGPT and then can be tested/iterated manually.

## Limitation

Readability formulas are heuristic. The hardest-sentence ranking is a simple local heuristic based on sentence length, syllable density, and longer words; it is not a semantic understanding of literary difficulty.
