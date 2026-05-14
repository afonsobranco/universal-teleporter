# Universal Teleporter

A self-contained unit and currency converter — single HTML file, no dependencies, no build step.

## Features

### Input modes
- **Standard** — `25 km`, `100°F to C`, `50 USD to EUR`
- **Formula** — `2 + 3 miles to km`, `(100-32)*5/9 c`
- **Range** — `32–212°F to C`, `0-100 kph to mph`
- **Unit chain** — `5 ft 11 in to cm`, `6 kg 200 g to lb`
- **Reverse lookup** — type just `km` to see 1 km in all units
- **Natural language** — `bucks`, `quid`, `us dollar`, `bitcoin`, `celcius`

### Conversion categories
| Category | Units |
|---|---|
| Length | m, km, mi, ft, in, cm, mm, nmi, yd |
| Weight | kg, g, mg, lb, oz, t, st |
| Temperature | °C, °F, K |
| Speed | m/s, km/h, mph, kn, fps |
| Area | m², km², ft², mi², ac, ha, in², cm² |
| Volume | L, mL, m³, ft³, gal, pt, qt, cup, fl oz, tsp, tbsp |
| Data | B, KB, MB, GB, TB, PB |
| Currency | 16 fiat currencies — live rates via frankfurter.app |
| Crypto | Top 30 by market cap — live prices via CoinGecko |
| Pressure | Pa, kPa, MPa, bar, mbar, atm, psi, Torr |
| Energy | J, kJ, cal, kcal, Wh, kWh, BTU |
| Angle | °, rad, grad, turn, arcmin, arcsec |
| Time | ms, s, min, h, day, wk, mo, yr |
| Fuel efficiency | km/L, mpg (US), mpg (UK), L/100km |

### Result card
- Sort by default / value ascending / value descending / A–Z
- ★ Pin units to the top of results (persisted)
- ⇄ Compare two values side-by-side
- ↓ Export as Markdown, CSV, or JSON
- ▦ Generate QR code for any row
- Proportion bars showing relative scale across all results
- Fraction display for cooking units (½ cup, ⅓ tbsp…)
- 7-day sparklines and 24h % change for crypto

### Other
- Dark / light mode toggle (persisted)
- EU / US number format toggle (`1.234,56` vs `1,234.56`)
- ⇅ Swap button to invert a conversion instantly
- Shareable URL — active query encoded in the hash
- Portfolio panel — enter crypto holdings, see total in USD / EUR / GBP
- Rate alerts — browser notifications when a crypto crosses a threshold
- Auto-refresh — live rates update every 5 minutes
- History trail — last 8 conversions as clickable chips
- `/` shortcut to focus the input from anywhere
- `↑` / `↓` keyboard navigation through result rows
- Multi-value paste — paste a column of numbers, all get converted
- Rotating placeholder examples

## Usage

Open `universal-teleporter.html` in any modern browser. No server, no install.

## Keyboard shortcuts

| Key | Action |
|---|---|
| `Tab` | Accept ghost-text suggestion |
| `Enter` | Expand result card |
| `Esc` | Close card / clear input |
| `↑` / `↓` | Navigate result rows |
| `/` | Focus input |

## Live data

- **FX rates** — [frankfurter.app](https://frankfurter.app) (free, no API key)
- **Crypto prices + sparklines** — [CoinGecko](https://coingecko.com) free tier (no API key)
- Falls back to bundled demo rates when offline
