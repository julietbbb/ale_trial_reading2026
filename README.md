# Reading Ale Trail 2026 — Pub Ranker

A simple, single-page web app for ranking the pubs on the Reading Ale Trail using head-to-head comparisons.

## How it works

You're shown two pubs at a time and pick whichever you'd rather visit. The app uses a binary insertion sort under the hood, so it takes around 90 comparisons to produce a fully ordered ranking of all 21 pubs. A live leaderboard updates as you go, and once you're done you can copy and share your final results.

## Running it

Just open `index.html` in a browser — no build step or server required.

## Pub images

Images are loaded from a GitHub repository:

```
https://raw.githubusercontent.com/julietbbb/aletrail_2026/main/Images/
```

Each pub has a corresponding `.jpeg` file there. If an image fails to load, a 🍺 placeholder is shown instead.

## Pubs included

24 pubs across Reading and the surrounding villages, including entries from both the Reading and South Oxfordshire CAMRA branches.

## Tech

Plain HTML
