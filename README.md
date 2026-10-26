---
title: Plagx Writing Companion
emoji: ✍️
colorFrom: blue
colorTo: indigo
sdk: static
app_file: index.html
pinned: false
license: mit
short_description: Free citation generator, draft checker & grammar hints
---

# Plagx Writing Companion

**A free, browser-based academic writing utility by [Plagiarism Checker X](https://plagiarismcheckerx.com/).**

Plagx Writing Companion helps students, researchers and writers polish academic drafts. You can generate citations, check your draft, get grammar and style hints, match in-text citations to your reference list and estimate reading time, all in one page with no sign-up.

### 👉 [Click here for the live demo](https://plagiarismcheckerx.github.io/plagx-writing-companion/)

---

## Features

### 1. Draft checks and reading time

Paste your draft to see live statistics:

- Word, character, sentence and paragraph counts
- **Reading time** (about 238 words per minute) and **speaking time** (about 130 words per minute)
- Average sentence length
- **Flesch Reading Ease** score

For a more detailed readability analysis, try the [Plagiarism Checker X Readability Checker](https://plagiarismcheckerx.com/readability-checker).

### 2. Grammar and style hints

Rule-based hints update as you type. They flag:

- Repeated words ("the the")
- Possible passive voice
- Filler words (_very, really, basically, actually_…)
- Common mistakes (_could of → could have_, _alot → a lot_, _irregardless_)
- Contractions and subjective phrasing ("I think") that academic writing usually avoids
- Spacing problems, lowercase sentence starts and very long sentences (over 35 words)

### 3. Citation generator

Creates formatted references in **APA, MLA, Chicago and Harvard** for:

- Books
- Journal articles (volume, issue, pages, DOI)
- Websites (including accessed date)

Enter one or more authors as `Last, First; Last, First`. Click **Copy** to copy the formatted citation.

### 4. Reference matching

Paste your body text and your reference list side by side. The tool finds author–year citations such as `(Smith, 2020)`, `(Smith & Lee, 2019; Khan et al., 2021)` and `Smith (2020)`, then reports:

- Citations in your text that are **missing from the reference list**
- References in your list that are **never cited**

---

## How it works

- **100% client-side.** The tool is plain HTML, CSS and JavaScript. All processing happens in your browser.
- **Private by design.** Your text is never uploaded, stored or sent to any server. No account, cookies or tracking scripts are used by the tool itself.
- **Offline-friendly.** Download the repository and open `index.html` in any modern browser.
- **Rule-based, not AI.** Hints and citation formats come from transparent pattern rules. Always review the output against your institution's style guide.

### Project structure

```
├── index.html   # Page layout and tabs
├── demo/
│   ├── demo.css  # Styling (light and dark mode)
│   ├── demo.js   # Draft checks, hints, citations, reference matching
│   └── demo.html # Page body used by the JSFiddle demo
├── README.md
└── LICENSE      # MIT
```

### Run locally

```bash
git clone https://github.com/plagiarismcheckerx/plagx-writing-companion.git
cd plagx-writing-companion
# open index.html in your browser
```

---

## What this tool does not do

This companion **does not** check for plagiarism or detect AI-generated text. To check complete documents for plagiarism and AI-generated content, use **[Plagiarism Checker X](https://plagiarismcheckerx.com/)**. You can [download Plagiarism Checker X](https://plagiarismcheckerx.com/download) for desktop.

---

## Contributing

Issues and pull requests for bug fixes, more citation styles or new style hints are welcome.

## License

[MIT](LICENSE) © 2026 Plagiarism Checker X
