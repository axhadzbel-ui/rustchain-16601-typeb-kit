# Storyboard — "The Blockchain Where Old Hardware Outearns New" (Type B, #16601)

Format: 16:9, 1080p. Human captures each shot per instructions; narration sections map to script.md timestamps.

## Shot 1 — Hook: depreciation curve (0:00–0:25)
- **Visual:** screen recording of a simple chart (any spreadsheet): new-CPU price line falling year over year, 2003→2026. Cut to photo of a PowerBook G4 (own photo or generated still, rights-held).
- **Overlay text:** "2003 PowerBook G4 — earns 2.5x a Threadripper".
- **Capture:** spreadsheet screen capture, 10 s; crossfade to G4 still.

## Shot 2 — Problem: two races (0:25–1:20)
- **Visual:** split screen — left, terminal running `htop` on a modern many-core box (power-race metaphor); right, a staking dashboard (capital-race metaphor, any public explorer, no login).
- **Overlay text:** "Race for electricity / Race for capital".
- **Capture:** two 8 s screen recordings, side-by-side in edit.

## Shot 3 — E-waste mountain (0:25–1:20, B-roll under problem)
- **Visual:** rights-held still or generated image of stacked old desktops/CRTs; slow zoom.
- **Capture:** single still, Ken Burns effect, 6 s.

## Shot 4 — Mechanism: the six checks (1:20–2:30)
- **Visual:** full-screen terminal, live: `curl -fsS https://rustchain.org/api/miners` — real output scrolling (20+ miners visible). Highlight one `antiquity_multiplier` field.
- **Capture:** real terminal recording, no staging. 15 s. Source: live endpoint (see SOURCES.md).

## Shot 5 — Multiplier table (1:20–2:30, under mechanism)
- **Visual:** screen capture of the RustChain README multiplier table (PowerPC G4 2.5x ANCIENT / Modern ARM NAS 0.0005x PENALTY), slow scroll.
- **Capture:** browser recording of github.com/Scottcjn/Rustchain README section, 10 s.

## Shot 6 — G4 vs Threadripper (1:20–2:30, payoff beat)
- **Visual:** side-by-side stills: PowerBook G4 and a Threadripper workstation; animated "2.5x" badge on the G4 side.
- **Capture:** stills + motion graphic, 6 s.

## Shot 7 — Attestation nodes (2:30–3:20)
- **Visual:** terminal: second curl — `curl -fsS "https://rustchain.org/wallet/balance?miner_id=paykurod-ltd"` showing `amount_rtc` + live explorer at rustchain.org/explorer in browser.
- **Capture:** real recordings, 12 s total.

## Shot 8 — Fixed supply (2:30–3:20)
- **Visual:** fullscreen text card: "8,388,608 RTC — 2^23 — fixed forever" with binary-rain background (generated, rights-held).
- **Capture:** motion graphic, 8 s.

## Shot 9 — Agent identity (2:30–3:20)
- **Visual:** diagram (draw or generate): POWER8 server icon vs Raspberry Pi icon, checkmark vs cross, labeled "silicon-level fingerprint".
- **Capture:** static diagram, slow push-in, 8 s.

## Shot 10 — Close: closet machine (3:20–4:00)
- **Visual:** human opens closet, pulls out an old laptop, plugs it in; screen lights with a terminal running the miner install; final card with repo + SOURCES.md link.
- **Capture:** live-action 15 s + end card 5 s.
