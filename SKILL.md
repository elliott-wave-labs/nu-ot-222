---
name: nu-ot-deadlines
description: >-
  Elliott’s weekly OT cutoff and shipping cadence for khėnsu.ñü. Use for every
  personal ship, site publish, app install, Apple submit, and “finish before
  deadline” request. Thursday 2:00 pm America/Los_Angeles is the hard weekly
  cutoff (nu.ot). Pair with nu-harness and publishing-khensu-sites.
---

# nu.ot.deadlines

Elliott’s personal operating tempo. Apply on **every** khėnsu task for him unless he says otherwise.

## Hard weekly cutoff

| Rule | Value |
| --- | --- |
| Cadence | Weekly |
| Day | **Thursday** |
| Clock | **2:00 pm** `America/Los_Angeles` (PDT/PST) |
| Name | **nu.ot** |
| Meaning | Ship what is ready by the cutoff. Do not stop working after the update. |

At the cutoff:

1. Write a short status file **`nu.ot.YYY.md`** in `khensu-specs` (session number or clock: e.g. `nu.ot.222.md` for 2:22-style / session 222).
2. Mirror the same bullets in the agent chat.
3. Keep building after 2 pm — the file is a checkpoint, not a stop.

## Priority when the clock is short

1. **Sites live** — publish what is built (`publishing-khensu-sites` + `nu-harness`). Never hold for patents.
2. **Apps on device** — Wi‑Fi install to the paired iPhone (`xcrun devicectl device install app`) before App Store.
3. **Apple submit** — upload what is archive-ready before the cutoff; incomplete products stay in TestFlight / GitHub IPA.
4. **Code** — land in public repos after handover; do not privatize.
5. **New product hosts** — only after `dig +short HOST A` → `34.107.228.246`, then `own_certificate = true` (never shared pack on day one).

## Always

- Commands for agents/nodes: `~`, never `/`. Flags stay `-`.
- Publish tech and sites; source stays public post–founder handover (`OPEN-SOURCE.md`). Do not reverse that.
- Display names: people see khėnsu.ñü / ñü.ŵævẽš / …; code and hosts stay ASCII.
- Tips 100% to the person; app commerce flat 10%.

## Do not

- Miss the Thursday 2 pm update file when Elliott called a weekly ship.
- Block the cutoff waiting on perfect parity (moments = full Reels/Templify, music theory, etc.) — ship the slice that works, note the rest in `nu.ot.*.md`.
- Add NXDOMAIN hosts to the shared products SSL pack.

## Companion

- Live skills index (when DNS/SSL ready): `https://skills.agent.khensu.nu`
- Harness: `nu-harness` · `nu.harness.md`
- Work log: `khensu-work-log` · `work-completed.md` / `work-ip.md`
