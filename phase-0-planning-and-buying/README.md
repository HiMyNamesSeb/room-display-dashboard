# Phase 0: Planning and buying

**Status:** 🔄 In progress

## What
Deciding the design, researching fair prices and buying the parts. The parts are picked (Day 1), but nothing is built or bought yet.

## Why
The budget is tight (under $100 if possible, about $130 max) and the Raspberry Pi Zero 2 W only has 512MB of RAM. Picking parts that actually work together before buying anything saves money and returns.

## Goal
Every part on the [main checklist](../README.md#parts-checklist-finished-display-only) in hand, within budget.

## The design so far
- **Layout:** Google Calendar on the top two-thirds, Google Tasks bottom left, weather card bottom right.
- **Background:** a slow pixel-art animation (falling leaves or stars), drawn with a small canvas or CSS animation at 10-12 fps. No big GIFs, no blur, nothing heavy.
- **Computer:** Raspberry Pi Zero 2 W booting straight into Chromium in kiosk mode. Upgrade to a Pi 4 only if the Zero 2 W lags.
- **Screen:** WGK 15.6" 1080p portable monitor, matte, bought new on Amazon.
- **Power:** always plugged into the wall through one 2-port charger, USB-C to the monitor and USB-A to the Pi. Portability doesn't matter.
- **Data:** Google Calendar (private iCal link or API), Google Tasks, and Open-Meteo for weather.
- **Remote access:** Tailscale plus key-based SSH only. Nothing exposed to the public internet.

## Parts picked (Day 1, November 2026 prices, may be out of date)

| Part | Item | Price | Where |
|---|---|---|---|
| Monitor | WGK 15.6" W156F1, 1080p IPS, matte, mini HDMI + 2x USB-C, VESA, 2.7 lb | $44.99 | [Amazon B0DCYBR34X](https://www.amazon.com/dp/B0DCYBR34X) (returns until Jan 31 2027) |
| Computer | Raspberry Pi Zero 2 W | $16 (hoped) | Local seller |
| Video cable | Mini HDMI to mini HDMI, ~3 ft | ~$6-10 | Amazon (search: mini HDMI to mini HDMI cable 3ft) |
| microSD | SanDisk Ultra 32GB (SDSDQUAN-032G-G4A) | ~$8-10 | [Walmart 180605232](https://www.walmart.com/ip/180605232) |
| Charger | Anker 33W 2-port (1 USB-C + 1 USB-A), includes USB-C cable | ~$25 | [Walmart 5236700627](https://www.walmart.com/ip/5236700627) |
| USB-C cable | Included with the monitor and charger | $0 | - |
| Micro-USB cable | ~1 ft | ~$3-6 | Amazon (search: short micro USB cable 1ft) |
| Mount | Heavy-duty Velcro, rated 5 lb+ | $0 (already have) | - |
| **Total** | | **~$103-112 before NC tax** | |

Only the monitor price is firm. The Pi is the riskiest part: online stores (PiShop, Adafruit, SparkFun) are out of stock and eBay resellers want $50-90. The only local listing is a set where the Pi is valued at $16, so I'm hoping the seller will sell just the Pi.

## Things to check before buying
- **Pi at pickup:** the board must say "Zero 2 W" and have the square RP3A0 chip. The older Zero W is too slow.
- **Monitor return window:** before Jan 31 2027, test that it powers on from the charger, shows the Pi over mini HDMI, and comes back on HDMI after unplugging and replugging power.
- **Monitor input:** ✅ settled. The WGK has mini HDMI, same as the Pi, so it's a mini-to-mini cable.
- **Monitor power:** it should run from a plain USB-C power port (not only from a laptop's USB-C video port). The 30W+ USB-C port on the charger covers this.
- **Pi power:** the Zero 2 W wants a solid 5V around 2.5A over micro-USB. A weak USB-A port can cause undervoltage warnings and slowdowns.
- **New monitor:** I picked a new one, not used. Still check for dead pixels and backlight bleed when it arrives.

## Parts used in this phase
None yet.

## Blog days
- [Day 1 - Planning Before Buying](https://github.com/HiMyNamesSeb/Blogs/blob/main/room-display-dashboard/d1-planning-before-buying.md)
