
<p align="center">
  <img src="assets/OmegaRR_Logo.png" width="260" alt="Omega Imbue Reroller">
</p>

<h1 align="center">OMEGA IMBUE REROLLER</h1>
<h3 align="center">ＴＥＫ ＥＤＩＴＩＯＮ</h3>

<p align="center">
  Advanced Automated Imbue Rerolling for<br>
  ARK: Survival Ascended — Omega
</p>

<p align="center">
  <img src="https://img.shields.io/badge/VERSION-2.0.0--beta-00D9FF?style=for-the-badge">
  <img src="https://img.shields.io/badge/PLATFORM-WINDOWS-0078D4?style=for-the-badge">
  <img src="https://img.shields.io/badge/STATUS-ACTIVE_DEVELOPMENT-22C55E?style=for-the-badge">
  <img src="https://img.shields.io/badge/V1_TEST-2000_ROLLS-22C55E?style=for-the-badge">
</p>

<p align="center">
  <a href="https://github.com/SinSloth23/Omega-Imbue-Reroller/releases/tag/v2.0.0-beta">
    <img src="https://img.shields.io/badge/DOWNLOAD-V2.0.0--BETA-00D9FF?style=for-the-badge&logo=github">
  </a>
</p>

---

## Overview

Omega Imbue Reroller is a standalone Windows application designed specifically for the ARK: Survival Ascended Omega community.

The application uses optical character recognition (OCR) to read item imbues directly from the game, automatically rerolling until your configured requirements are met.

Spend less time manually rerolling and more time playing.

---

## What's New in v2.0.0-beta

- Dedicated Gear and Saddle modes, with independent calibration, stat libraries and lifetime records.
- Saddle targeting uses actual imbue values; Gear supports Actual and projected Post-Curse targeting.
- Saved target presets with import and export.
- Custom fonts, colors, six built-in themes and theme import/export.
- Customizable sound notifications for successful targets, exhausted roll limits and new lifetime records.
- Optional session statistics and screenshot/OCR data collection.
- Built-in GitHub update checker.
- Target Achieved notifications display only qualifying selected targets.

---

## Key Features

| Feature | Description |
|---|---|
| Automated Rerolling | Automatically reroll items until your configured targets are met. |
| OCR Recognition | Reads imbue names and values directly from the game screen. |
| Actual Stat Targeting | Search for specific raw imbue values. |
| Post-Curse Targeting | Search for projected Gear values after applying Multiply Curse. |
| Multiple Stat Targets | Configure multiple requirements using ALL or ANY matching. |
| Minimum Imbues | Require a minimum number of imbues on an item. |
| Live Target Tracking | Monitor required, current, and best session values. |
| Automatic Recovery | Recover from temporary OCR errors without additional essence clicks during recovery. |
| Lifetime Records | Track the highest raw imbue values separately for Gear and Saddles. |
| Performance Mode | Fast single-pass OCR during normal rerolling. |
| TEK Interface | Custom high-contrast sci-fi interface. |
| Emergency Controls | Pause, resume, or immediately stop automation. |

---

## Performance & Stability

The previous V1 Beta 6 release successfully completed a live test of **2,000 consecutive rerolls without failures, freezes, or recovery hangs.**

| Metric | Result |
|---|---|
| Consecutive test rolls | 2,000 |
| Failures during test | 0 |
| Recovery hangs during test | 0 |
| Typical roll duration | 700–800 ms |
| Estimated throughput | 75–86 rolls/minute |

These figures are from V1 Beta 6 testing, not a V2 benchmark. V2 has been locally tested by the developer.

Performance may vary depending on hardware, resolution, game performance, and OCR settings.

---

## Post-Curse Targeting

For Gear only, search for the projected value of an imbue after applying Multiply Curse. Saddles use actual values only.

The calculation uses the total number of imbues on the current item.

**Multiplier = 1 + (Total Imbues ÷ 2)**

| Total Imbues | Multiplier | Raw Magic Find | Projected Magic Find |
|---:|---:|---:|---:|
| 6 | 4× | 40% | 160% |
| 8 | 5× | 40% | 200% |
| 9 | 5.5× | 40% | 220% |
| 10 | 6× | 40% | 240% |
| 11 | 6.5× | 40% | 260% |
| 12 | 7× | 40% | 280% |

Each target can independently use Actual or Post-Curse matching.

Projected values are estimates. The application does not automatically apply Multiply Curse.

---

## Lifetime Records

The application automatically maintains persistent, independent Gear and Saddle records across rerolling sessions.

- Total lifetime rolls.
- Highest number of imbues observed on one item.
- Highest observed value for each imbue stat.
- Automatically saved records.

> [!IMPORTANT]
> Lifetime Records exclusively track raw, pre-curse imbue values. Projected Post-Curse values are never included in Lifetime Records.

Records represent the highest observed values, not theoretical maximums.

---

## Installation

1. Visit the [Releases](https://github.com/SinSloth23/Omega-Imbue-Reroller/releases) page.
2. Download `omega-imbue-reroller-2.0.0-beta-windows-x64.zip` from the [V2 beta release](https://github.com/SinSloth23/Omega-Imbue-Reroller/releases/tag/v2.0.0-beta).
3. Extract the ZIP into a folder.
4. Launch `OmegaImbueReroller.exe`.

The compiled release does not require a separate Python installation.

---

## Getting Started

1. Launch ARK: Survival Ascended.
2. Open the Omega imbue workbench.
3. Place the item and rerolling essence in their appropriate locations.
4. Launch Omega Imbue Reroller.
5. Select Gear or Saddles and calibrate the item stat panel.
6. Calibrate the essence click position.
7. Test OCR recognition.
8. Configure your desired stat targets.
9. For Gear, select Actual or Post-Curse targeting; Saddles use Actual only.
10. Start rerolling.

Keep the calibrated game interface visible and unobstructed during operation.

---

## Keyboard Controls

| Key | Function |
|---|---|
| F8 | Pause / Resume |
| F9 | Emergency Stop |

---

## Settings & Customization

Use Settings to customize appearance, sound notifications and update preferences, manage saved presets, and enable optional screenshot/OCR collection. Session statistics can be shown or hidden to keep the main interface uncluttered.

Screenshot collection during live rerolling consumes essence; leave it disabled unless needed.

---

## V1 Beta 6 Highlights (Previous Release)

The [previous V1 Beta 6 release](https://github.com/SinSloth23/Omega-Imbue-Reroller/releases/tag/v1.0-beta.6) remains available as a fallback.

- Post-Curse stat targeting.
- Improved automatic OCR recovery.
- Simplified target-based rerolling.
- Removed unnecessary imbue-count restrictions.
- Removed essence-icon matching restrictions.
- Additional verification of potential winning rolls.
- Improved session personal-best tracking.
- Detailed recovery diagnostics.
- Redesigned high-contrast interface.
- Official Omega RR application icon.
- Successfully completed a 2,000-roll stability test.

---

## Feedback & Bug Reports

Community feedback helps improve the application.

Please use the [GitHub Issues](https://github.com/SinSloth23/Omega-Imbue-Reroller/issues) page to report:

- Bugs and unexpected behavior.
- OCR recognition problems.
- Performance issues.
- Feature requests.
- Interface suggestions.

When reporting an issue, please include your application version, screenshots, relevant logs, and a description of what happened.

---

## Disclaimer

Omega Imbue Reroller is an independently developed, unofficial companion application.

It is not affiliated with Studio Wildcard or the developers of ARK Omega.

Always follow the rules of your server regarding automation and third-party applications.

This software remains in active beta development. Use at your own discretion.

---

<p align="center">
  <img src="assets/OmegaRR_Logo.png" width="90">
</p>

<h3 align="center">DEVELOPED BY SINSLOTH23</h3>

<p align="center">
  Built for the Omega community.
</p>

<p align="center">
  <b>LESS REROLLING. MORE PLAYING.</b>
</p>
