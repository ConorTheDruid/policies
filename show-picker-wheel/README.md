# Show Picker Wheel

A tiny spinner-wheel app for picking what to watch tonight — split into separate
**Movies** and **TV Shows** lists. Spin to get a random pick, then mark it
"Watched" to remove it from the list (or keep it and spin again another night).

No build step, no backend — just static HTML/CSS/JS. Lists are saved in the
browser's `localStorage`, so they persist between visits on the same device/browser.

## Running it

Open `index.html` directly in a browser, or serve the folder locally:

```
python3 -m http.server 8000
```

then visit `http://localhost:8000`.

## Notes

This currently lives inside the `policies` repo as a subfolder because the
GitHub integration in the session that built it wasn't authorized to create a
brand-new repository. Move this folder into its own repo whenever that's
convenient — it has no dependency on anything else in `policies`.
