# FORGE Fitness System

Free offline-first personal fitness tracker.

## Android installation
1. Create a free GitHub repository named `forge-fitness`.
2. Upload `index.html`, `manifest.webmanifest`, and `sw.js` to its root.
3. Open Settings → Pages; deploy from `main` branch and `/ (root)`.
4. Open the resulting HTTPS URL in Chrome on Android.
5. Use Chrome menu → Install app / Add to Home screen.

## Custom workout splits
Open Workout → My workout splits. Create, rename, or delete custom split labels. Custom labels appear in the workout logger. Renaming updates historical entries; deleting a label keeps existing workout history.

## Data
Data is stored locally in the browser. Export backups regularly. Clearing site data may erase records. Progress photos remain in local browser storage and are not included in JSON backup.

Nutrition estimates are approximate. The coach uses rule-based suggestions, not a connected generative AI service. Notifications may be suspended by Android when the browser is in the background.
