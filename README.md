# DREAD FEED (web, $0 build)

One HTML file. No accounts, no backend, no monthly costs, no code installs.

## Run it
Open `dread-feed.html` in any browser (double-click it, or open it on your phone).
Everything is saved in that browser only.

## Make it yours (3 things)
1. **Your Ko-fi link**: near the top of `dread-feed.html`, in the CONFIG block,
   replace `https://ko-fi.com/YOUR_KOFI_LINK` with your real Ko-fi page.
2. **Your videos**: drop your `.mp4` files in the same folder and set each clip's
   `src` in the `CLIPS` list (e.g. `src: "they-left-the-door-open.mp4"`). Titles,
   descriptions, intensity, warnings and which 5 are free are all edited there too.
3. **Unlock codes**: in the same CONFIG block, `NIGHTMARE1/2/3` are sample codes.
   Change them to your own. When someone pays you on Ko-fi, you text or email them
   the code for the clip they bought; they type it in and the clip unlocks on their
   device. This is the whole payment flow: Ko-fi holds the money, you hand out codes.

## What it does
- 18+ age gate with a content warning (covers you with platforms and viewers).
- Vertical dark feed, intensity/shock badges, content warning tags per clip.
- Four reactions per clip (scream / jump / laugh / fear) that earn Scarecoin and
  advance a Dread Rank. All stored locally in the viewer's browser.
- First 5 clips free. Locked clips blur and show a pay-for-$0.99 sheet that opens
  your Ko-fi and takes an unlock code.
- Footer credits the work to Beautiful Chaos.

## Hosting it (free)
GitHub Pages serves this for $0 from a public repo. One ask before that: it would
be live on the open web under your account, so it only happens on your say-so.
