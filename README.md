# Rostock Sky

A single-page weather view for Rostock: today plus the next three days, focused on
**cloud cover**, **UV index** and **visibility**, with temperature, rain, wind, sunshine
and the Baltic water temperature at Warnemünde.

- Data: [Open-Meteo](https://open-meteo.com/) forecast + marine APIs (free, no key, CC BY 4.0), fetched in the browser.
- The hour-by-hour band colours each hour from clear blue to overcast grey (dark at night). Hover, tap or use the arrow keys to read any hour.
- Daily cloud and visibility figures are daylight averages / ranges.
- Refreshes every 15 minutes; the last result is cached locally for offline viewing.

No build step — it's one `index.html`. Deploy with GitHub Pages from the `main` branch, root folder.
