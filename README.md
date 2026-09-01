# PageSpeed Insights Chrome Extension

A Chrome extension that runs Google's PageSpeed Insights API against the current tab and surfaces performance, accessibility, best-practices, and SEO scores — without leaving the browser.

> 🕰️ **Note:** Built while learning TypeScript and browser-extension development.

## Features
- One-click analysis of the current tab's URL
- Performance, accessibility, best-practices, and SEO scores at a glance
- Detailed metrics and improvement suggestions
- Link to the full PageSpeed Insights report

## Tech stack
`TypeScript` `Chrome Extension APIs` `Google PageSpeed Insights API`

## Setup
```bash
git clone https://github.com/<username>/website-performance-analyzer.git
cd website-performance-analyzer
npm install
```
1. Rename `src/config.example.ts` → `src/config.ts` and add your own PageSpeed Insights API key
2. `npm run build`
3. In Chrome, go to `chrome://extensions`, enable Developer mode, click "Load unpacked," and select the `dist` folder

## Usage
1. Click the extension icon
2. Click "Analyze" to run PageSpeed Insights on the current tab
3. Review scores and suggestions, or click "View Full Report" for details

## License
MIT
