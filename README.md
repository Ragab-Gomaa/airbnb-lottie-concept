# Airbnb micro-interactions · Lottie demo

**Live demo:** https://ragab-gomaa.github.io/airbnb-lottie-concept/

An unofficial concept: six micro-interactions for the Airbnb app, built as real Lottie files.
Each file is shape layers only, with a named marker for every state, so a developer plays
`save` or `unsave` by name instead of by frame number. Drag the list, tap the heart, switch tabs:
every card on the page plays the same file a developer would ship.

| Animation | File | Markers |
|---|---|---|
| Empty Trips | `lottie/empty-trips.json` | intro · loop |
| Pull to Refresh | `lottie/pull-to-refresh.json` | pull · release · refresh · end |
| Wishlist Heart | `lottie/heart.json` | save · unsave |
| Search Loader | `lottie/search-loader.json` | loop |
| Booking Confirmed | `lottie/booking-confirmed.json` | play |
| Tab Bar Icons | `lottie/tab-*.json` (5 files) | select · deselect |

Runs on [lottie-web](https://github.com/airbnb/lottie-web) 5.12.2.

Motion by Ragab Gomaa. Unofficial concept, made for a portfolio: not affiliated with or endorsed by Airbnb, Inc.
Airbnb is a trademark of Airbnb, Inc.
