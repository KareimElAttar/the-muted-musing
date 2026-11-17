# The Muted Musing — Astraea Atlas MVP

A player-facing, read-only Atlas of Astraea, built for **The Muted Musing** D&D campaign.

## Features
- Original Astraea map with approximate clickable location markers
- Searchable region directory
- Zoom and drag navigation
- A separate "Beyond the map" section for True Tartarus and Lab 2
- Brief player-safe lore and "How to get there" notes, with unknown routes labeled honestly
- Mobile-friendly responsive layout

## Required map image (one-time upload)
The website expects **`assets/astraea.png`**, using the original Astraea image supplied by the DM.

1. In GitHub, open this repository and choose **Add file → Upload files**.
2. Upload the image with the path `assets/astraea.png`. If the GitHub browser upload adds it to the repository root, use the GitHub web editor to move it into the `assets` folder, or upload it using a local Git client.
3. Commit the image to `main`.

Until that image exists, the page shows a placeholder while the rest of the Atlas remains accessible.

## Publish with GitHub Pages
Open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**; select **main** and **/(root)**, then Save. The eventual site URL is normally:
https://kareimelattar.github.io/the-muted-musing/

The repository is public. **Do not upload DM-only lore or secrets.**

## Current limitations
- No accounts or Supabase in v0.1.
- The region names and map labels are taken from the supplied Astraea map. Markers are approximate, and boundaries/distances are not authoritative.
- Route information is only included where player-safe sources support it.
- The UI is an MVP, not an approved final design.
- The content has been checked against player-safe baselines from The Muted Musing Astraea DM FAQ & Knowledge Matrix, with special care to exclude unrelated Wires of Fate canon.

## Next iteration
Refine visual design and map interaction with player feedback; add a connected-location schema and source-backed routes before adding private accounts.
