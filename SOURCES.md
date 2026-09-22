# SOURCES.md — every factual claim → its source (Bounty #16601 Type B quality bar)

All claims verified 2026-09-22 against live sources. No invented numbers.

1. "PowerBook G4 from 2003 earns 2.5x more than a modern Threadripper" → `Scottcjn/Rustchain` README.md: "A PowerBook G4 from 2003 earns **2.5x** more than a modern Threadripper." + multiplier table row "PowerPC G4 (2003) | **2.5x** | ANCIENT".
2. "Modern ARM NAS/SBC at 0.0005x penalty" → same README multiplier table: "Modern ARM NAS/SBC | **0.0005x** | PENALTY | Cheap, farmable, penalized".
3. "Start mining today at 0.8x; multiplier grows as hardware ages" → README: "Start mining today at 0.8x. In ten years, when that CPU is a relic and you're still running it? Your multiplier grows."
4. "Six checks: oscillator drift, cache timing, SIMD identity, thermal entropy, instruction jitter, anti-emulation" → README "Hardware Fingerprinting (6 Checks No VM Can Fake)" section + comparison table row "Clock drift, cache timing, SIMD identity, thermal entropy, instruction jitter, anti-emulation".
5. "SheepShaver VM pretending to be a G4 will fail" → README: "A SheepShaver VM pretending to be a G4 will fail. Real vintage silicon has unique aging patterns that can't be faked."
6. "20+ miners attesting, live API" → README "20+ miners attesting" + live `curl -fsS https://rustchain.org/api/miners` (verified HTTP 200, 14 miners in snapshot 2026-09-22; README states 20+).
7. "Attestation nodes: 2 always-on (Louisiana) + lab POWER8; POWER8 S824 512GB RAM" → README attestation-nodes table: "2 always-on (Louisiana) + lab POWER8" and "Node 5 — POWER8 S824 | Local Lab | First non-x86 node (IBM ppc64le, 512GB RAM)".
8. "Total supply 8,388,608 RTC (2^23), fixed forever" → README: "**Total supply: 8,388,608 RTC** (2²³ — pure binary). Fixed forever. Consensus-enforced cap." + "Compare to Bitcoin's 21M (≈2.5x more)".
9. "Sybil-resistant agent authentication; POWER8 vs Raspberry Pi provably different" → README: "Sybil-resistant agent authentication — hardware-attested agent identity" + "An agent running on a verified POWER8 server is provably different from one on a Raspberry Pi".
10. "AVAP: agents sign messages inside videos" → README: "Media created in this ecosystem can carry **AVAP** (Agent Video Attestation Protocol): agents cryptographically sign and blockchain-anchor messages *inside* the videos they exchange".
11. "Live U.S. legal-corpus determinism engagement, 1M+ units" → README: "the attestation chain for a live U.S. legal-corpus determinism engagement run by Elyan Labs for a research client: over one million units of federal and state [material]".
12. "If it runs Python, it can mine; platform list" → README: "Works on Linux (x86_64, ppc64le, aarch64, mips, sparc, m68k, riscv64, ia64, s390x), macOS (Intel, Apple Silicon, PowerPC), IBM POWER8, and Windows. If it runs Python, it can mine."
13. "Wallet identity paykurod-ltd, balance endpoint" → live `https://rustchain.org/wallet/balance?miner_id=paykurod-ltd` HTTP 200 (balance 0.0, valid identity).
14. E-waste framing is deliberately qualitative ("mountain of dead electronics") — no precise tonnage claimed, no source needed.

Deliberately NOT claimed: any benchmark numbers beyond the README table; any payout/price predictions; any traction figures.
