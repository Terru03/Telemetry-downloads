# Telemetry Extractor Downloads

Public binary releases for Telemetry Extractor.

This repository does not contain the source code for the app. It exists only to host the public Windows installer and Android APK used by the download buttons on the website.

## What Telemetry Extractor Is

Telemetry Extractor is an offline telemetry workflow for action-camera, drone, and activity footage.

You can use it to:

- extract GPS, accelerometer, gyroscope, altitude, and timing data from supported videos
- inspect tracks on an interactive map or 3D globe
- graph speed, altitude, acceleration, and other data
- build telemetry overlays with gauges, text, images, and presets
- export cleaned data as GPX, CSV, KML, GeoJSON, VIRB, and JSON
- render overlay videos locally on your own device
- sync external GPX or FIT activity files with video
- work with 360 video and metadata reinjection in the Pro desktop workflow

The focus is simple:

- no cloud processing
- no subscription
- no account required to test the app
- your videos stay on your device

## Why I Built It

I built Telemetry Extractor because the existing telemetry workflow was more frustrating than it should have been.

I wanted something that:

- worked fully offline
- felt fast on real footage instead of tiny demo clips
- supported both desktop and mobile workflows
- did not force a subscription just to unlock exports
- made it easy to test the real app before paying

The result is a single app model with a free mode and optional one-time Pro keys.

## Available Apps

### Windows

Best for:

- full telemetry workflow
- long renders
- high-resolution exports
- 360 viewer and reinjection workflows

Direct download:

- [Download Windows Trial](https://github.com/Terru03/Telemetry-downloads/releases/latest/download/Telemetry-Extractor-Setup.exe)

### Android

Best for:

- mobile field testing
- on-device review and exports
- quick checks without returning to desktop

Direct download:

- [Download Android Trial](https://github.com/Terru03/Telemetry-downloads/releases/latest/download/Telemetry-Extractor-Android.apk)

## Free Vs Pro

The download is the real app, not a fake demo.

Free mode is meant to let you test the workflow properly before buying a key.

### Free

- telemetry extraction
- interactive map, charts, stats, and data table
- starter overlay gauges and starter presets
- GPX and CSV export
- 3D globe visualization
- export allowed while using 2 or fewer active overlays
- max file size: 1 GB

### Pro Desktop

- all overlay gauges
- unlimited active overlays and presets
- video rendering
- KML, GeoJSON, VIRB, and JSON export
- GPX and FIT activity sync
- 360 viewer
- Reinject Studio
- max file size: 20 GB
- 2 device activations

Price: EUR 99 one-time, VAT included

### Pro Android

- same core on-device workflow unlocked for Android
- mobile rendering and export features
- 2 device activations

Price: EUR 29 one-time, VAT included

### Bundle

- desktop key
- android key

Price: EUR 119 one-time, VAT included

## Supported Inputs

Telemetry Extractor is built for workflows around:

- GoPro Hero 6 through 13
- GoPro Max and Fusion
- DJI Avata, Osmo, Air, and Mini lines
- GPX and FIT activity files from tools like Garmin, Strava, and Wahoo
- Insta360 footage in supported workflows

## How To Use It

### 1. Install The App

- Windows: run the installer
- Android: install the APK and allow the install if Android asks for permission

### 2. Open A Video

Load a supported video from your device.

Telemetry Extractor will try to read the telemetry automatically from the source file:

- GoPro GPMF
- DJI metadata and sidecar workflows
- external GPX or FIT files when you want to sync an activity recording

### 3. Explore The Data

Use the app to:

- inspect the route on the map
- check charts and stats
- verify sensor quality
- scrub the footage while watching the telemetry line up with the video

### 4. Build The Overlay

Add and arrange gauges such as:

- speed
- altitude
- compass
- timer
- g-force
- minimap
- text and image widgets

Save presets if you want to reuse the same overlay style across videos.

### 5. Export

Depending on your edition, you can:

- export telemetry data files
- render an overlay video
- export transparent PNG frames
- sync activity files
- use 360 workflows
- reinject metadata back into edited footage

## Typical Workflows

### Action Camera Overlay

1. Load a GoPro clip
2. Extract telemetry automatically
3. Add speed, altitude, compass, and timer gauges
4. Render an overlay video for social media or YouTube

### Drone Flight Review

1. Load a DJI clip
2. Inspect route and altitude profile
3. Add a minimap and flight stats
4. Export a clean overlay render

### Ride Or Run Sync

1. Load the video
2. Import GPX or FIT data from Garmin, Strava, or Wahoo
3. Time-sync the recording with the footage
4. Export the finished overlay

### Metadata Reinjection

1. Render or edit a video
2. Use the reinjection workflow
3. Restore metadata for better compatibility in gallery and map-aware tools

## Privacy

Telemetry Extractor is built around local processing.

- videos stay on your machine or phone
- telemetry is processed locally
- exports are generated locally
- there is no cloud upload requirement

## Release Model

This repository is release-only on purpose.

- public release assets live here
- the source repository stays separate
- website download buttons point to this repository's release assets

That keeps public downloads simple without exposing the private development repository.

## Getting The Latest Build

Always use the `latest/download/...` links above or open the Releases tab:

- [Latest Release Page](https://github.com/Terru03/Telemetry-downloads/releases/latest)

## Support

If a build does not start downloading, open the latest release page and download the asset directly from there.

If the app opens but a feature stays locked, that usually means you are still in Free mode and need the matching Pro key for that platform.

## Current Release

- [v1.0.0](https://github.com/Terru03/Telemetry-downloads/releases/tag/v1.0.0)
