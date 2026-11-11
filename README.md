# Get Your Google Business Page

A free, step-by-step course from Reputation Reactor: claim your Google Business
Page, set it up, and get verified — one short lesson per verification method.

## What's here

- `index.html` — the whole course site (single page; entry point).
- `assets/*.pptx` — slide decks for the 7 verification methods (phone, text,
  email, video recording, live video call, postcard, instant via Search
  Console). Added via git in a separate commit — the Muse GitHub connector
  can only push text files, so binary assets don't travel with the first push.
- `assets/decks/*/*.jpg` — slide images shown in the course, also added via git.

## Deploy (Cloudflare Pages)

Connect this repo in Cloudflare Pages. Framework preset: none / static.
Build output directory: the repo root. The live site serves `index.html`.

Deploy note: the deck download links in `index.html` point at `assets/*.pptx`.
Add `download="gbp-verify-<method>.pptx"` to each link so downloaded decks
keep proper filenames.

## Domain

Intended domain: getyourgooglebusinesspage.com (not purchased yet — buy in
GoDaddy, then point it at the Cloudflare Pages site).
