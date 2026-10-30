# CDRA CO2 Conversion Calculator

A single-page calculator, built for Premier Recycle around 2020, that turns tons of recycled construction and demolition material into CO2 savings and everyday equivalents.

**Live (GitHub Pages):** https://adithrestha.github.io/cdracalculator.github.io/

## What it does

Enter tons of **metal, concrete, plastic, drywall, OCC (cardboard), and wood**. For each material it shows:

- Tons of CO2 saved
- Light bulbs' worth of energy saved
- Gallons of gas saved
- Vehicles taken off the road
- Homes' electricity

A Chart.js line chart compares the materials.

## Files

- `index.html` — form and results table
- `script.js` — conversion factors (the `*Rate` variables) and the calculation and chart logic
- `css/` — Bootstrap and custom styles

No build step or server is needed. Open `index.html` in a browser.

## Notes

- Chart.js 2.5.0 is loaded from cdnjs, which still serves that version.
- The conversion factors are hard-coded and undocumented. Cite their source (likely the EPA WARM model or CDRA) before reusing the numbers.
