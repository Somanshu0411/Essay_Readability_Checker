# Chapter Readability Checker

A free, browser-based tool that helps writers evaluate the readability of essays, chapters, and other text. It provides readability estimates and text statistics to help authors identify passages that may be difficult for readers.

## Preview

![Chapter Readability Checker screenshot](screenshots/app-preview.png)

## Features

- **Flesch Reading Ease:** Estimates how easy a passage is to read.
- **Flesch–Kincaid Grade Level:** Estimates the U.S. school grade level needed to understand the text.
- **Text statistics:** Calculates word count, sentence count, and average words per sentence.
- **Difficult sentence detection:** Highlights five sentences that score as the most challenging according to the project's heuristic.
- **Privacy-friendly processing:** Analyzes text locally in the browser without sending it to a backend server.
- **Responsive interface:** Includes a dark-themed interface designed for convenient use.

## Technologies Used

- HTML — page structure
- CSS — layout and styling
- JavaScript — text analysis and readability calculations
- Git and GitHub — version control and project hosting

## Getting Started

### Run locally

1. Clone or download this repository.
2. Open the project folder.
3. Open `index.html` in a modern web browser.
4. Paste your text into the tool and review the results.

No backend server is required for the current implementation.

## How It Works

The application analyzes the text using word and sentence statistics, then applies readability formulas to estimate reading difficulty.

The difficult-sentence ranking uses a local heuristic based on factors such as sentence length, syllable density, and longer words. It does not understand literary meaning or guarantee that a highlighted sentence will be difficult for every reader.

## Limitations

- Readability formulas provide estimates rather than definitive judgments.
- Grade-level estimates do not represent a reader's actual ability.
- Sentence segmentation and syllable counting may be imperfect for unusual words, abbreviations, and complex punctuation.
- The difficult-sentence ranking is a heuristic, not a semantic analysis.

## Future Improvements

- Add automated tests for text statistics and readability calculations.
- Improve sentence segmentation and syllable-counting accuracy.
- Add sample texts so users can explore the tool immediately.
- Publish a live demo using GitHub Pages.
- Improve accessibility and add clearer explanations of the readability scores.

## Development Acknowledgment

ChatGPT assisted with the initial implementation. The project can be tested and improved through manual verification and further development.

## Author

**Somanshu Kumar**

- GitHub: https://github.com/Somanshu0411
- LinkedIn: https://www.linkedin.com/in/somanshu-kumar-8446a9310/
