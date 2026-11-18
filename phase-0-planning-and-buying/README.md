# Phase 0: Planning and buying

**Status:** 🔄 In progress

## What
Deciding the design, researching fair prices and buying the parts. Nothing is built yet and no parts have been bought.

## Why
The budget is tight (under $100 if possible, about $130 max) and the Raspberry Pi Zero 2 W only has 512MB of RAM. Picking parts that actually work together before buying anything saves money and returns.

## Goal
Every part on the [main checklist](../README.md#parts-checklist-finished-display-only) in hand, within budget.

## The design so far
- **Layout:** Google Calendar on the top two-thirds, Google Tasks bottom left, weather card bottom right.
- **Background:** a slow pixel-art animation (falling leaves or stars), drawn with a small canvas or CSS animation at 10-12 fps. No big GIFs, no blur, nothing heavy.
- **Computer:** Raspberry Pi Zero 2 W booting straight into Chromium in kiosk mode. Upgrade to a Pi 4 only if the Zero 2 W lags.
- **Screen:** 15.6" 1080p portable USB-C monitor, ideally thin and matte, ideally bought used.
- **Power:** always plugged into the wall through one 2-port charger, USB-C to the monitor and USB-A to the Pi. Portability doesn't matter.
- **Data:** Google Calendar (private iCal link or API), Google Tasks, and Open-Meteo for weather.
- **Remote access:** Tailscale plus key-based SSH only. Nothing exposed to the public internet.

## Rough budget (November 2026 estimates, may be out of date)

| Part | Rough price |
|---|---|
| Portable 15.6" 1080p monitor (used) | ~$40-60 |
| Raspberry Pi Zero 2 W (local seller) | $16 |
| 32GB microSD | ~$6-8 |
| Mini HDMI cable | ~$5-8 |
| 2-port charger, 30W+ USB-C + USB-A | ~$12-20 |
| Short USB-C + micro-USB cables | ~$5-8 |
| Velcro / adhesive strips | ~$5-8 |
| **Total** | **~$90-130** |

The monitor is the biggest swing in the budget. Only the Pi price is confirmed; the rest are rough guesses still to be checked.

## Things to check before buying
- **Monitor input:** some portable monitors have a mini-HDMI port instead of full-size HDMI. That decides whether I need a mini-to-full or a mini-to-mini HDMI cable.
- **Monitor power:** it should run from a plain USB-C power port (not only from a laptop's USB-C video port). The 30W+ USB-C port on the charger covers this.
- **Pi power:** the Zero 2 W wants a solid 5V around 2.5A over micro-USB. A weak USB-A port can cause undervoltage warnings and slowdowns.
- **Used monitors:** check for dead pixels, backlight bleed, and that the included cables and power work.

## Parts used in this phase
None yet.

## Blog days
_No day posts yet._
