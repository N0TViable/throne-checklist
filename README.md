# Throne & Liberty Mini Game Checklist

A dungeon cooldown tracker and Tumgir Hollow run log for Throne & Liberty.

**Live page:** https://n0tviable.github.io/throne-checklist/

Created by n0tviable · Server: Distortion

## What it does

**Dungeon gates.** Eight dungeons, each on a 30-minute cooldown. Check one when you
clear it and it counts down live, then unseals itself and pings you with a chime and a
toast. Forgot to check the box on the way out? Click the countdown and type the time
left, or `-12` for "I finished 12 minutes ago."

**Tumgir Hollow run log.** Records Abyss Contract Tokens before and after (tokens used
calculates itself), Sollant acquired, skill cores, weapon mastery points, and which of
the four buffs you ran: Mastery Report, Abundance Fruit, Golden Apple Pie, Black Anvil.
Totals and averages update live, including Sollant per token spent. Every figure in the
table is clickable if you need to correct it later.

## Your data stays yours

This page **makes zero network requests**. No fetch, no XHR, no WebSocket, no external
scripts, fonts, or images, no analytics, no `eval`. Nothing you type leaves your browser.

Don't take my word for it. Open DevTools (F12), go to the Network tab, and use the page.
The list stays empty. The whole thing is a single file with no dependencies, so you can
read every line of it in this repo.

Your runs are saved in your own browser's local storage. Nobody else can see them, and
they never reach a server, because there is no server.

## Keeping your log

Browser storage is per-browser and per-device, and clearing site data wipes it. Use
**Save a copy with my data** to download a complete HTML file with your runs and timers
baked in. Open that file anywhere and everything is there. There's also a save code you
can copy and paste to move your log between machines, plus CSV export.

## Running it offline

Download `index.html` and open it from your own disk. It behaves identically. The
hosted version exists so you don't have to trust a downloaded file.
