# Hi, I'm Yasser 👋

I ship software with AI coding agents doing the implementation. I decide what gets built, write the rules the agents work under, and own what reaches users: two apps on the App Store, six live web apps, one on TestFlight, across 145 repositories. Victoria, BC.

## What I'm working on

- [QR Media](https://apps.apple.com/us/app/qr-media/id1621676911) — QR code wallet and generator for iOS; keeps every code you have used and makes new ones from links or text · App Store
- [MKV2MP4 Converter](https://apps.apple.com/us/app/id6796610448) — Sandboxed Mac App Store video converter with bundled ffmpeg; approved 2026-08-09 after one rejection · App Store
- [Flight tracker](https://yanantir.web.app) — Real-time aircraft map on deck.gl with its own backend and a generated sprite set · live
- [ChineseFood](https://chinesefood-159.web.app) — Bilingual map and food-crawl planner for Chinese restaurants and groceries, with a forum · live
- **FoodVoteToday** — Group meal voting for households and small teams; Apple and Google sign-in, in-app account deletion, privacy page. An AI fridge-scan feature (0.8) was cut before 1.0 as a scope and privacy decision · TestFlight
- **Shopping Scout** — MCP server that turns Claude into a local shopping agent for Victoria

## The factory

Tooling I built so one person plus coding agents can ship like a team:

- **appship** — Expo app to TestFlight in one command: repo check, sign-in gate, simulator smoke test, build number from App Store Connect, upload, beta review
- [Bugs159](https://bugs159-fe5c1.web.app) — Central error intake every app reports to, with an admin UI; 29 apps wired through the shared reporter kit · live
- **issue-solution-cache** — 429-entry symptom/cause/solution memory, loaded into every agent session by a start hook so the same bug is never solved twice
- **ecc-pack** — Curated rule and sub-agent pack for coding agents, with an on/off switch per project
- **AppMatrix** — Command center that scans every project and runs launch, test, deploy and version actions with diagnostics

## Open source

- [sprite-orientation-classifier](https://github.com/yasser159/sprite-orientation-classifier) — TensorFlow.js CNN for classifying top-down sprite nose orientation; 148K params, 945KB, runs in Node and the browser
- [spritesmaker](https://github.com/yasser159/spritesmaker) — Parametric aircraft and vessel sprite generator: SVG templates plus Wikipedia specs to 128×128 PNG sprites
- [all-seeing-eye](https://github.com/yasser159/all-seeing-eye) — Desktop diagnostics viewer for Expo/Metro structured logs, strict core/UI split

## How I build

Every project runs under the same operating manual: plan before code, tests before "done", version bump and changelog on every change, security checklist on every server, App Store compliance designed in from day one. A start hook loads a 429-entry issue memory into each session so no bug is solved twice; every app reports errors to one central intake. The agents type. I review, gate and decide.

📫 yasser159@gmail.com
