# Search-tally


# Search Tally

A companion app to Presence Scanner. It logs how many searches you've run for each username, broken down by platform, and keeps a running tally.

## Running it

Open `search-tally.html` in any browser. No install, no server, no dependencies.

## Using it

1. Type a username into the field (with or without `@`).
2. Click a platform button. Each one does two things at once:
   - Opens that platform's search for the username in a new tab.
   - Adds one to that username's tally for that platform.
3. The table on the right shows every username you've searched, a column per platform, a row total, and a grand total across everyone.

Use **Remove** on a row to drop a username, or **Reset all** to clear the whole table.

## Where the data lives

Counts are saved in your browser's local storage, tied to this specific file. That means:
- They'll still be there next time you open `search-tally.html` on the same device and browser.
- They won't carry over to a different browser, device, or if you clear browsing data.
- They're private to your browser — nothing is sent anywhere.

## What this does and doesn't measure

This counts **searches you've run through this app** — a personal log of your own activity. It does not, and cannot, tell you:
- How many times *other people* have searched your name or handle.
- Actual result counts or rankings from X, Instagram, TikTok, Facebook, or YouTube.

No platform exposes "how often someone was searched" data to a browser-side tool like this — not even to the account owner. The tally here is strictly about your own outgoing searches, not incoming search volume.
