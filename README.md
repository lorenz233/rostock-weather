# Rostock Sky

A single-page weather view for Rostock: today plus the next three days, focused on
**cloud cover**, **UV index** and **visibility**, with temperature, rain, wind, sunshine
and the Baltic water temperature at Warnemünde.

- Data: [Open-Meteo](https://open-meteo.com/) forecast + marine APIs (free, no key, CC BY 4.0), fetched in the browser.
- An illustration of the current weather over the Baltic, drawn live from the data: day/night sky, sun position, moon and stars, cloud amount, rain, snow, fog and thunderstorms, plus a lighthouse that lights up at night. Animations stop if the device asks for reduced motion.
- Daily cloud and visibility figures are daylight averages / ranges.
- Refreshes every 15 minutes; the last result is cached locally for offline viewing.

No build step — it's one `index.html`. Deploy with GitHub Pages from the `main` branch, root folder.
