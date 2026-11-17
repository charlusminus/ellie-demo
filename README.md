# Ellie, interactive demo and onboarding tour

Presents Ellie without slides: your team, looked after the way your team looks after the guests.
The website lives in its own repository, https://github.com/charlusminus/ellie-site.

| Address | What it is |
|---|---|
| **https://charlusminus.github.io/ellie-demo/** | The interactive demo, a day at a maison or a DMC (`index.html`) |
| **https://charlusminus.github.io/ellie-demo/onboarding/** | An agency account to click through, with a guided first visit (`onboarding/index.html`) |
| `/max/` | A short version for a DMC, built from one guest's journey: six screens, the driver on WhatsApp, the coordinator's live map (`max/index.html`). On the `max-dmc` branch, not published yet |
| `/story/` | An earlier version of the demo in eight scenes, kept for reference |
| `/account/`, `/demo/` | Earlier addresses, redirect to the onboarding tour and to the demo |

Published with GitHub Pages from `main`, root folder. One file per version, no build step, no tracking, `noindex`.

## The demo

- Built for a projector: story on the left, a live Ellie screen on the right. Arrow keys to move, N for presenter
  notes (what to say, what to show live in Ellie, what to ask), F for full screen. No tools on screen.
- **One look, dark only**: the Ellie charter, night blue and gold, with the official logo (decision of 15/11/2026; the
  two other looks, the light theme and the header links to the website and the tour were removed).
- The agency's name can be set for a meeting with `?dmc=Name`; the page itself names no real company.
- **Two sides of the same event.** The first screen asks the viewer to choose: a maison (the guests, their journeys and
  every requirement) or a DMC (everything to deliver on the ground). `?side=maison` or `?side=dmc` opens directly on
  one side.
- **The maison side** (reworked on 15/11/2026 after the maison's feedback: concrete, no upload, visibility on the
  run-down): where the event stands three weeks, one week and one day before; the programme to approve; the first
  arrivals, with each guest's car live on a map; six things that go wrong and what the maison sees and does; the bill
  per market the week after; the guests' data after the event (encrypted, outside access closed, file returned to the
  maison, deleted with a certificate).
- **The DMC side** opens on what changed in the maison's latest guest list, follows the fleet with the drivers and
  their live map, reviews costs first (client feedback marked as later), and ends with the five questions a maison
  asks before choosing an agency, and what Ellie gives the agency to answer each.
- **The live map** is one drawing shared by both sides: a night map, cars that drive, the route ahead in gold,
  traffic in red. Motion stops when the viewer asks for reduced motion.
- **One person's day.** The first screen lets the viewer follow the whole team or one profile (for the DMC: Nok, Arun,
  Ploy, Somchai, Mai; for the maison: Claire, Mei). `?profile=arun` opens it that way.
- **Pictures**: a faded picture behind the story, one per scene, the same generated pictures as the website
  (`assets/img/`, no faces, no text, no logos). Opacity .2 keeps the muted text above 4.5:1.
- **The team**: generated portraits of the fictional team in the profile cards (`assets/img/team/`), not real people.
- **Fits the screen**: on desktop the base size follows the height of the window too, so the story on the left always
  fits without scrolling (checked on every scene, from 1100 x 640 to 2560 x 1300).
- **Back to the start**: click the Ellie logo, or press Home.

## The guest's journey (`max/`)

- Six screens, one idea each: the guest lands; six moments of her journey (what she lives, what the agency has settled,
  what Ellie did unseen); the driver's WhatsApp conversation with Ellie; the coordinator's live map and log; who works
  in Ellie and who stays on WhatsApp; three questions to design together.
- Shown after the real application, for what is not built yet: everything about WhatsApp, the drivers' answers and the
  live map is marked "In co-design".
- Follows the Ellie charter (Cormorant Garamond and Mulish, night blue, ivory, one gold). `?dmc=Name` sets the agency's
  name. Arrow keys to move, F for full screen, Home or the logo to start again.
- Rules: codes instead of names, a sign with a code, cars located during the ride only, never a guest.
- Checked at render from 1024 x 768 to 2560 x 1300 and at 390 x 844: no scrolling on desktop, no text under 14 px,
  contrast of at least 4.5:1.

## Shared

- **Logo**: the official Ellie Experience wordmark redrawn as a vector, in the demo and the tour headers; tab icon in
  `assets/logo/`. The website repository holds the same files.
- Guests, hotels, cars and costs are fictional. "In Ellie today" is in the product now; "In co-design" is a proposal to
  build with the agency.
