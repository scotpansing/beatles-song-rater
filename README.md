# Work it Out — Beatles Song Rater

A web app where you rate every Beatles song on a scale of 1 to 5. 213 songs, all 14 studio albums plus Past Masters, with album artwork and links to Spotify and Apple Music for every track.

## How to use it

1. Hit **START** and you'll be shown songs one at a time in random order.
2. Rate each song from **1** (absolute favorite) to **5** (the rest).
3. Tap the album art or the "Fool on the Hill" link to see album info and listen before you rate.
4. After rating at least 20 songs, hit **Check your results so far** to see your full tier breakdown.
5. Your ratings are saved automatically in your browser — you can close the tab and come back anytime.
6. When you're done (or want to start fresh), use **START OVER**.

## Rating tiers

| Tier | Meaning |
|------|---------|
| 1 | Absolute favorites |
| 2 | Love these |
| 3 | Really like these |
| 4 | Like these |
| 5 | The rest |

## Tech

- Vanilla HTML, CSS, and JavaScript — no frameworks, no build step
- Song data (titles, album, year, streaming links) is embedded directly in `index.html` from `beatles_songs.json`
- Album artwork is stored locally in the `albumart/` folder
- Ratings are persisted in browser `localStorage`
- Links to [Spotify](https://spotify.com) and [Apple Music](https://music.apple.com) for every song

## Made by

Beatles fan Scot Pansing, inspired by plenty of conversations with his son that began as, "Would you rate this a Tier 1 Beatles song?"
