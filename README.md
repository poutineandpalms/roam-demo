# Roam — Browser Demo

**Roam** is an interactive voice tourist guide prototype: put your phone in your pocket, walk or drive through a city, and an AI guide narrates the interesting places around you — tuned to your taste.

This page hosts a **browser demo** of the Roam Flutter prototype. The real iOS/Android app uses GPS and runs with the screen off; browsers can't do background location, so this demo showcases the **Demo/Simulation mode**: draw a path on the map, pick a speed, hit play, and the guide narrates as if you were moving along that route.

## What to try

1. Open the demo and tap **Try demo mode — simulate a walk**.
2. Tap the map to drop waypoints and draw a route.
3. Choose a speed (stroll / walk / bike / drive) and press **Play**.
4. The guide speaks about the places along your path, using on-device speech and free map data (OpenStreetMap, Wikipedia).

## Notes

- This is an early prototype for testing the concept, not a finished product.
- The full app (native iOS/Android build) is developed separately; this demo exists so the idea can be tried instantly in a browser.
- Map tiles: © [OpenStreetMap](https://www.openstreetmap.org/copyright) contributors.

## Tech

Built with [Flutter](https://flutter.dev). Source for the native prototype lives in a separate private repo.
