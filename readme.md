# 🗺️ Mapping Moments with Folium: A Geolocated Map of Photos I’ve Taken

## 📍 Overview

This project uses **Folium**, a Python wrapper for Leaflet.js, to build an interactive map with markers in 3 different cities (Seattle, NYC, and Bangkok). Each map marker represents a location (e.g., the Empire State Building), and when clicked, displays a photo and location name via popup.

The goal was to do a minimal experiment with data visualization with Python (using Folium) — as practice for expanding Python understanding and future work re: spatial storytelling.

---

## 🛠️ What’s Working Now

- ✅ All markers render correctly and are clickable  
- ✅ Each popup shows a **name of place/landmark** and an associated photo  
- ✅ Tooltips allow for easy hover-preview of each location  
- ✅ Output is currently saved as an `.html` file from the Deepnote notebook  

---

## 🖼️ Current Limitations

- ⚠️ UI has no user instructions or legend.
- ⚠️ Zoomed in on NYC. To change to zoom out so it dynamicalliy shows the map zoomed out enough to show all markers.
- ⚠️ Placeholder photos from Wikipedia. 

---

## 🔗 Data Structure

Currently hardcoded in Python:

```python
# Example structure
landmarks = [
    {"name": "Empire State Building", "lat": 40.748817, "lon": -73.985428, "image": "images/empire.jpg"},
    ...
]
