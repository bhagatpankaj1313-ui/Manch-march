# Manch March — official website

Free static website for the Manch March game. Plain HTML, CSS and JavaScript —
no build step, no database, no paid hosting.

## What is here

- `index.html` — home, with Play Online and APK download buttons
- `play.html` — the game embedded (iframe to `game.html`)
- `game.html` — the current web release (v259)
- `download.html` — Android APK download (v260, about 1.9 MB, Android 7.0+)
- `manch-march-v260.apk` — the Android release
- `features.html`, `gallery.html`, `how-to-play.html`, `updates.html`,
  `feedback.html`, `faq.html`, `about.html`, `privacy-policy.html`,
  `terms.html`, `contact.html`
- `blog/` — development notes (what the game is, ally chain, controls)
- `shots/` — real in-game screenshots (WebP; PNG originals beside them)
- `sitemap.xml`, `robots.txt`, `favicon.svg`

## How to publish

1. Create a public GitHub repository named `manch-march`.
2. Push every file in this folder to the repository's main branch.
3. In the repository: Settings → Pages → deploy from the main branch.
4. The site goes live at `https://bhagatpankaj1313-ui.github.io/manch-march/`.
5. Add that URL in AdSense (Connect your site), then paste the AdSense
   snippet over the `<!-- AdSense: ... -->` placeholder in each page head.

## Notes

- Game progress on the web version lives in the visitor's own browser
  (local storage) and is never sent anywhere.
- The APK is served from this repository so the download works the moment
  Pages is live; it can move to a GitHub Release later.
