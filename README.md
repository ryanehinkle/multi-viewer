# Multi Viewer

A clean four-up browser multiview for watching multiple streams at once.

## Features

- 2×2 viewing grid
- Add or replace any pane from an interactive preview
- YouTube URL normalization to embedded players
- Twitch channel/video/clip support
- Generic iframe support for sites that allow embedding
- Click a pane to make it the active audio source
- Thin pastel-red border indicates the listening pane
- Reload, replace, focus, or remove any pane
- F11/fullscreen preview workflow
- Layout persists locally between reloads
- Responsive dark UI

## Browser limitations

Websites can opt out of being embedded using CSP or X-Frame-Options, so some arbitrary URLs will refuse to load inside any multiview website. The app includes an **Open tab** fallback for those cases.

Cross-origin browser security also means a host page cannot inspect or control every arbitrary site's internal video player. Audio switching is implemented directly for supported YouTube/Twitch embeds; generic third-party pages may keep their own audio state.

## Run locally

Just open `index.html`, or serve the folder with any static web server.

## GitHub Pages

This repository is static and can be published directly from the `main` branch root in **Settings → Pages**.
