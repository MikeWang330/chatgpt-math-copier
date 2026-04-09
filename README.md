# ChatGPT Math Copier

One-click copy math formulas from ChatGPT to Piazza, Markdown, Notion, Word, Google Docs and more.

## How It Works

1. Hover over any block equation in ChatGPT
2. Click the **Copy** button that appears
3. Choose your destination
4. Paste!

## Supported Destinations

| Destination | Format | Usage |
|---|---|---|
| 📐 Piazza | `$$LaTeX$$` | Paste directly |
| 📝 Markdown | `$LaTeX$` | Paste directly |
| 📓 Notion | Raw LaTeX | Type `$$` + Enter to create equation block, then paste |
| 📄 Word / Google Docs | PNG image | Paste directly |
| 🔣 Raw LaTeX | Source code | Universal |

## Install

- [Chrome Web Store](#) *(link coming soon)*
- Or load manually: download this repo → `chrome://extensions` → Enable Developer Mode → Load unpacked

## Privacy Policy

**ChatGPT Math Copier** respects your privacy.

- **No data collection**: This extension does not collect, store, or transmit any personal data.
- **No analytics**: No tracking, cookies, or usage analytics of any kind.
- **No accounts**: No sign-up or login required.
- **Single external request**: The only network request is to `latex.codecogs.com` to render LaTeX as a PNG image, and this happens **only** when the user explicitly clicks the "Word / Google Docs" option. No data is sent other than the LaTeX equation string.
- **Local only**: All other operations (LaTeX extraction, clipboard copy) happen entirely within your browser.

## License

MIT
