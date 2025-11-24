# Ymaps Points

A small demo project for displaying organization and clinic locations on **Yandex Maps 3.0**.

## What it does

* Dynamically loads **Yandex Maps API 3.0** via JavaScript (without placing `<script src="...">` directly in the markup).
* Creates a map in **vector mode** with strict global bounds to prevent the user from scrolling beyond the allowed area.
* Loads and displays markers from a **GeoJSON FeatureCollection** (`Point` features).
  Currently, the dataset is included directly in `index.html` (or optionally in `data.json`).
* Each marker:

  * uses a custom PNG icon,
  * opens an information alert on click containing organization details (city, name, address, email, phone).

## Project structure

```
ymaps-points/
  index.html     — main page containing map initialization and logic
  index.js       — optional separated JavaScript file for map logic
  data.json      — optional GeoJSON dataset with point data
  README.md      — project documentation
```
