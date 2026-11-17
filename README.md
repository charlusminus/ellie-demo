# Ellie, interactive demo and onboarding tour

Presents Ellie without slides: one guest's journey, and the invisible work behind it.
The website lives in its own repository, https://github.com/charlusminus/ellie-site.

| Address | What it is |
|---|---|
| **https://charlusminus.github.io/ellie-demo/** | The demo: one guest's journey in six screens, the driver on WhatsApp, the coordinator's live map (`index.html`) |
| `/max/` | Earlier address of the same demo, redirects to the root and keeps `?dmc=` |
| **https://charlusminus.github.io/ellie-demo/onboarding/** | A first visit to Ellie in eleven stops, on the real screens of the application (`onboarding/index.html`) |
| `/account/`, `/demo/` | Earlier addresses, redirect to the onboarding tour and to the demo |

Published with GitHub Pages from `main`, root folder. One file per version, no build step, no tracking, `noindex`.
The earlier root demo (two sides, a maison or a DMC, with profiles) was replaced on 17/11/2026; it stays in the git
history (last version: commit `fdc0ed2`). The eight-scene version at `/story/` was removed the same day.

## The demo

- Six screens, one idea each: the guest lands; six moments of her journey (what she lives, what the agency has settled,
  what Ellie did unseen); the driver's WhatsApp conversation with Ellie; the coordinator's live map and log; who works
  in Ellie and who stays on WhatsApp; three questions to design together.
- Shown after the real application, for what is not built yet: everything about WhatsApp, the drivers' answers and the
  live map is marked "In co-design".
- Follows the Ellie charter (Cormorant Garamond and Mulish, night blue, ivory, one gold). `?dmc=Name` sets the agency's
  name; the page itself names no real company. Arrow keys to move, F for full screen, Home or the logo to start again.
- Rules: codes instead of names, a sign with a code, cars located during the ride only, never a guest.
- Pictures from `assets/img/` (generated, no faces, no text, no logos); the two portraits come from `assets/img/team/`
  (generated, not real people).
- Checked at render from 1024 x 768 to 2560 x 1300 and at 390 x 844: no scrolling on desktop, no text under 14 px,
  contrast of at least 4.5:1.

## The first visit (`onboarding/`)

- Eleven stops on the real screens of an agency account: events, the event and its modules, composing with the maison,
  guests in codes, one guest's page, the same guest on the maison's side, the day's points of attention, the kanban,
  the fleet free at a given time, one car and its conflicts, the to-do.
- The captures (`onboarding/shots/`, WebP, desktop 1440 x 900 and phone 390 x 844) come from the application's `main`
  branch run locally on 17/11/2026, with a fictional event in Bangkok (18 guests, 6 cars, invented names and bookings).
  A gold frame shows what to look at; on a desktop the capture is enlarged around it.
- Everything shown is in Ellie today. To refresh the captures, follow the recipe in the brain (`ellie-en-local`).

## Shared

- **Logo**: the official Ellie Experience wordmark redrawn as a vector, in the demo and the tour headers; tab icon in
  `assets/logo/`. The website repository holds the same files.
- Guests, hotels, cars and costs are fictional. "In Ellie today" is in the product now; "In co-design" is a proposal to
  build with the agency.
