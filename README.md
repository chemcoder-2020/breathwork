# Breathwork pacer

Static single-page pacer for a fixed 7-slot daily breathwork schedule (8am-9pm),
built to raise resting HRV. Each session pairs a visual breathing ring with a
pre-rendered guided audio track (voice labels on the first two cycles, tones after).

Deep links: `#0800` `#0930` `#1100` `#1300` `#1600` `#1830` `#2030`

- `index.html` - the pacer (audio drives the visual clock, so they stay in sync)
- `audio/*.ogg` - one exact-timed guided track per slot
- Fallback: if audio is blocked, tone cues run off an internal clock

Sessions: 08:00 box 4-4-4-4 | 09:30 sighs + in4/out6 | 11:00 resonance 5.5/5.5 |
13:00 coherent in4/out6 (12m) | 16:00 box | 18:30 in4/out8 | 20:30 4-7-8 (12m)
