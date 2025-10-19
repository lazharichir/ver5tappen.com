# How Can Max Win His 5th WDC?

A lightweight single-page tool that projects the Formula 1 drivers' championship standings – and how Max can win his 5th WDC title.

**You can tweak upcoming session results and instantly see how the points race evolves.**

## Features
- Live standings panel that updates as you reorder session results or add DNFs.
- Driver list seeded with the latest base points, podiums, and wins.
- Pre-loaded schedule of remaining sessions to explore countless championship permutations.
- Shareable state via URL hash so you can collaborate on scenarios.

## Getting Started
1. Clone the repository or download the files.
2. Open `public.index.html` in any modern browser.
3. Start dragging drivers or marking DNFs to explore alternate outcomes.

No build tooling or server is required—the app is entirely static HTML, CSS (via Tailwind CDN), and vanilla JavaScript.

## Editing Data
- Base driver points, names, and teams live near the top of `index.html` inside the `driverData` array.
- Session definitions follow in the `sessionConfigs` array. Add, remove, or rename events as needed.
- Team palette colors are defined in the `teamPalette` object for quick visual tweaks.

## Contributing
Pull requests are welcome! If you plan a sizeable change, please open an issue or discussion first so we can align on scope. For PRs, include:
- A clear description of the change and motivation.
- Any manual testing steps you performed.
- Screenshots or recordings when UI changes are involved.
