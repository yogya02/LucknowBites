# LucknowBites
A mobile app that helps visitors and students discover the famous food of Lucknow, with a map, what to order and walking directions.

## Overview

The best local food spots in Lucknow are hidden in narrow lanes and are hard to find online. LucknowBites shows kebab stalls, chaat corners and sweet shops of the old city on a map, along with what to order, opening hours and directions.

The result is a working Android app with more than 60 spots, which friends visiting Lucknow used as their food guide.

## Features

- Map of food spots across the old city.
- Spots sorted by distance from your current location.
- A card for each spot with dishes, price range and opening hours.
- One-tap directions to the spot.
- Filter for vegetarian options.
- "Open now" switch that compares the current time with each spot's opening hours.

## Tech Stack

| Area | Tools |
|------|-------|
| Framework | Flutter |
| Language | Dart |
| Database | Firebase |
| Maps | Google Maps API |

## How It Works

The app is written in Flutter, so the same code can run on Android and iPhone. Food spots are stored in a Firebase database with their location, dishes, price range and opening hours. The app reads the user's location, sorts spots by distance and draws them on a Google Map. Tapping a spot opens its card with directions.

The "open now" switch compares the current time with each spot's opening hours, and the vegetarian filter hides spots with no vegetarian dishes.

## Getting Started

**Prerequisites:**

- [Flutter SDK](https://docs.flutter.dev/get-started/install)
- A Firebase project with a database set up
- A Google Maps API key

```bash
git clone <your-repo-url>
cd LucknowBites
flutter pub get
```

Add your own Firebase configuration files and Maps API key. Do not commit these keys to a public repository.

## Usage

```bash
flutter run
```

1. Allow location access when asked.
2. Browse the map or the list of nearby spots.
3. Use the filters for vegetarian or open-now spots.
4. Tap a spot to see what to order and get directions.

## Results

A working Android app with 60+ spots, used by friends visiting Lucknow.

## What I Learned

- Building one app for Android and iPhone with Flutter.
- Structuring data in Firebase and reading it by location.
- Working with the Google Maps API and device location.

## Author

**Yogya Mandhyan** · Reg. No. 26BDS0096
B.Tech CSE (Data Science), VIT Vellore
yogya.mandhyan2026@vitstudent.ac.in
