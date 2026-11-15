# Ellie, interactive demo and onboarding tour

Presents Ellie without slides: your team, looked after the way your team looks after the guests.
The website lives in its own repository, https://github.com/charlusminus/ellie-site.

| Address | What it is |
|---|---|
| **https://charlusminus.github.io/ellie-demo/** | The interactive demo, a day at a maison or a DMC (`index.html`) |
| **https://charlusminus.github.io/ellie-demo/onboarding/** | An agency account to click through, with a guided first visit (`onboarding/index.html`) |
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
  arrivals; six things that go wrong and what the maison sees and does; the bill per market the week after.
- **The DMC side** ends with the five questions a maison asks before choosing an agency, and what Ellie gives the
  agency to answer each.
- **One person's day.** The first screen lets the viewer follow the whole team or one profile (for the DMC: Nok, Arun,
  Ploy, Somchai, Mai; for the maison: Claire, Mei). `?profile=arun` opens it that way.
- **Back to the start**: click the Ellie logo, or press Home.

## Shared

- **Logo**: the official Ellie Experience wordmark redrawn as a vector, in the demo and the tour headers; tab icon in
  `assets/logo/`. The website repository holds the same files.
- Guests, hotels, cars and costs are fictional. "In Ellie today" is in the product now; "In co-design" is a proposal to
  build with the agency.
