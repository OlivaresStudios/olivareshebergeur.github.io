# olivareshebergeur.github.io

Public host for the files the studio's publishing tool must expose for a moment: an Instagram Reel is created from a
public URL, so `series/publish_day.sh` (repo builds-videos) puts the video and its cover here, waits until
https://olivaresstudios.github.io/olivareshebergeur.github.io/<file> answers, and removes them right after.

Each host and each removal is a single commit pushed with `--force` over the previous one, so the history never keeps
old videos. Only these base files stay: index.html / 404.html (to https://olivaresstudios.eu), robots.txt, .nojekyll.
The studio's site itself is https://olivaresstudios.eu (Cloudflare Pages).
