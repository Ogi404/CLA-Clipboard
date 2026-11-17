# CLA Clipboard

A tablet clipboard for recording what happens during a Brazilian jiu-jitsu training session, one tap at a time, without leaving the mat.

**Open it:** https://ogi404.github.io/CLA-Clipboard/

## What it does

- Set up the athletes for a session, then pick the session day, game, round and focal athlete.
- Record each observed action with a single tap. The buttons describe what was seen, not what the athlete intended.
- Every entry is saved in the browser as you go, so a closed tab or a flat battery doesn't lose the session.
- Undo the last entry if you tap the wrong button.
- Export the session as tab-separated values: copy it, preview it, or download it, then paste it straight into a spreadsheet.

## How it's built

- One self-contained `index.html` file. No build step, no dependencies, no server.
- Works offline once the page has loaded.
- Data stays on the device in the browser's local storage. Nothing is sent anywhere.

## Run it locally

Download `index.html` and open it in a browser.

## Notes

This is a companion tool to a separate coaching app, which is private. The session content in this version (games, rounds and outcome buttons) is set up for one specific training block, so treat it as a working example and adapt the lists in the file for your own sessions.
