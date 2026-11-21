
<div align="center">

# OMEGA // IMBUE REROLLER
### T E K &nbsp; E D I T I O N

**Automated Imbue Rerolling for ARK: Survival Ascended**

![Version](https://img.shields.io/github/v/release/SinSloth23/Omega-Imbue-Reroller?include_prereleases&label=VERSION&color=00BCD4&style=for-the-badge)
![Platform](https://img.shields.io/badge/PLATFORM-WINDOWS-0078D4?style=for-the-badge)
![Status](https://img.shields.io/badge/STATUS-BETA-FFA500?style=for-the-badge)
![Price](https://img.shields.io/badge/PRICE-FREE-2EA44F?style=for-the-badge)

[DOWNLOAD](../../releases) • [REPORT A BUG](../../issues)

---

</div>

## ⚡ Overview

Omega Imbue Reroller is a standalone utility designed
for the ARK Omega community.

Automatically reroll your equipment imbues, configure
your desired stats, and let the application stop when
your requirements are met.

Track your lifetime imbue records, set advanced item
requirements, automatically recover from temporary
errors and calculate potential Multiply Curse values.

**Less clicking. More playing.**

## ◆ Features

| Feature | Description |
| :--- | :--- |
| Smart Recognition | Automatic OCR-based stat detection |
| OCR Correction | Automatic correction of minor stat-name recognition errors |
| Custom Targets | Configure multiple stat requirements |
| Minimum Imbues | Require a minimum number of imbues on an item |
| Target Tracking | Dedicated required, current and best-value display |
| Target Highlighting | Highlighted and pinned target statistics |
| ALL / ANY Matching | Flexible target matching |
| Essence Selection | All 12 essence tiers supported |
| Performance Mode | High-speed single-pass OCR |
| Multi-Monitor Support | Select the display running ARK |
| Adaptive Recovery | Handles delayed game responses |
| Automatic Resume | Automatically resumes after verified recovery |
| Recovery Configuration | Custom recovery delays, intervals and attempt limits |
| Batch Management | Configurable maximum roll limits |
| Session Statistics | Track rolls, clicks and performance |
| Best Values | Organized, scrollable batch statistics |
| Lifetime Records | Permanent highest observed imbue values |
| Lifetime Rolls | Persistent completed reroll counter |
| Imbue Count Records | Most imbues ever observed on a single item |
| Curse Projections | Automatically calculates potential Multiply Curse values |
| Safety Protection | Suspends clicks when unsafe conditions are detected |
| Tek Interface | Dark, gaming-inspired application design |
| Portable | No separate Python or OCR installation |

## ◆ Supported Essences

| | | | | | |
| :---: | :---: | :---: | :---: | :---: | :---: |
| ⚪ Basic | 🟢 Delta | 🔵 Gamma | 🟣 Beta | 🟡 Alpha | 🩵 Elite |
| ⚪ Prime | 🟠 Apex | 🩷 Ultimate | 🔴 Ancient | ⚫ Endless | 🌈 Omega |

## ◆ Download

### [⬇ Download the Latest Release](../../releases)

Designed for Windows 10 and Windows 11 (64-bit).

No separate Python or Tesseract installation required.

Download the Windows release ZIP from the release assets.

Previous versions remain available on the Releases page.

## ◆ Getting Started

1. Download the Windows release ZIP.
2. Extract the entire ZIP into a folder.
3. Launch `OmegaImbueReroller.exe`.
4. Open the Imbue Workbench in ARK.
5. Select the monitor running ARK.
6. Select your desired essence.
7. Calibrate the stat panel and essence click location.
8. Use **Read Current Stats** to verify recognition.
9. Configure your desired imbue requirements.
10. Optionally configure a minimum total imbue count.
11. Configure your automatic recovery settings.
12. Test using Dry Run before starting.
13. Select **Start New Batch**.

## ◆ Advanced Target Configuration

Configure individual stat requirements alongside an
optional minimum total imbue count.

For example:

- Magic Find: 40% or higher
- Minimum Total Imbues: 9

| Magic Find | Total Imbues | Result |
| :---: | :---: | :--- |
| 45% | 7 | Continue Rolling |
| 38% | 9 | Continue Rolling |
| 40% | 9 | Target Achieved |
| 48% | 10 | Target Achieved |

The minimum imbue requirement is independent of
ALL / ANY stat matching.

Both the configured stat matching criteria and the
minimum imbue count must be satisfied.

## ◆ Automatic Recovery

Omega Imbue Reroller can attempt to recover automatically
from temporary recognition errors and delayed game responses.

During recovery, automatic clicking is suspended.

The application attempts to verify the current workbench
state and checks the active targets before resuming.

| Recovery Setting | Default |
| :--- | :--- |
| Auto-Recovery | Enabled |
| Initial Recovery Delay | 3 seconds |
| Recovery Retry Interval | 5 seconds |
| Maximum Recovery Attempts | 10 |

Manual pauses and emergency stops will not trigger
automatic resumption.

If the application cannot safely recover, manual
intervention is required.

**Do not change equipment or workbenches during
automatic recovery.**

Screen-based verification cannot guarantee equipment
identity.

## ◆ Lifetime Records

The dedicated Lifetime Records tab permanently tracks
the highest observed value for each numerical imbue stat.

### Lifetime Statistics

- Total completed lifetime rolls
- Most imbues observed on a single item
- Highest observed value for all 24 numerical imbue stats

Lifetime records are automatically saved and are
independent of individual batch statistics.

Starting a new batch or restarting the application
does not reset lifetime records.

Individual stat records only increase when a higher
value is verified.

These values represent observed records, not confirmed
theoretical maximums.

## ◆ Multiply Curse Projections

When a successful roll is achieved, the application
displays potential Multiply Curse values alongside the
actual imbue values.

**Curse Multiplier = 1 + (Total Imbue Text Lines / 2)**

**Potential Cursed Value = Actual Value × Curse Multiplier**

### Multiplier Reference

| Imbue Lines | Multiplier | 40% Magic Find |
| :---: | :---: | :---: |
| 1 | 1.5x | 60% |
| 2 | 2x | 80% |
| 3 | 2.5x | 100% |
| 4 | 3x | 120% |
| 5 | 3.5x | 140% |
| 6 | 4x | 160% |
| 7 | 4.5x | 180% |
| 8 | 5x | 200% |
| 9 | 5.5x | 220% |
| 10 | 6x | 240% |

Each projection assumes that the individual stat
receives Multiply Curse.

Projected values are informational only and do not
affect target matching or lifetime stat records.

## ◆ Keyboard Controls

| Key | Function |
| :---: | :--- |
| **F8** | Pause / Resume Active Batch |
| **F9** | Emergency Stop |

## ◆ Recommended Settings

| Setting | Recommended Value |
| :--- | :--- |
| Game Display Mode | Windowed Fullscreen |
| Minimum Wait | 0.100 seconds |
| Adaptive Detection | Enabled |
| Verification | Performance |
| Auto-Recovery | Enabled |
| Initial Recovery Delay | 3 seconds |
| Recovery Retry Interval | 5 seconds |
| Maximum Recovery Attempts | 10 |
| Initial Test Batch | 10 rolls |

Increase the minimum wait if your game or server
cannot reliably keep up.

## ◆ Development Status

This application is currently in public beta testing.

Feedback, bug reports and feature requests are welcome.

## ◆ Changelog

### V1.0 Beta 5 — Recovery, Lifetime Records & Curse Projections

**Automatic Recovery**

- Automatic recovery from temporary errors
- Automatic batch resumption after verification
- Configurable recovery settings
- Preserved active batch targets and statistics
- Recovery checks before resuming clicks
- Manual pause and emergency stop protections

**Advanced Targets**

- Optional minimum total imbue requirement
- Current imbue count tracking
- Highest batch imbue count tracking
- Integration with existing ALL / ANY matching

**Lifetime Records**

- Dedicated Lifetime Records tab
- Persistent highest observed imbue values
- Lifetime completed roll counter
- Most imbues observed on a single item
- Automatic record saving
- Additional verification of potential new records

**Curse Projections**

- Automatic Multiply Curse calculations
- Actual and projected cursed values
- Imbue line-based multiplier calculations
- Successful roll results display

### V1.0 Beta 4 — Target Tracking & OCR Improvements

**Interface Improvements**

- Dedicated target tracking panel
- Required, current and best-value tracking
- Bold cyan highlighting for targeted stats
- Green highlighting for satisfied requirements
- Targeted stats pinned to the top
- Organized, scrollable best-values table

**Recognition Improvements**

- Case-insensitive stat recognition
- Automatic minor OCR spelling correction
- Duplicate stat-name prevention
- Improved punctuation and whitespace handling
- Standardized recognition of 24 known imbue stats
- Diagnostic logging for unrecognized stats
- Protection against conflicting duplicate values
- Preserved distinction between flat and percentage stats

**Performance**

- No additional OCR passes during normal rolling
- Existing high-speed rolling engine retained
- Adaptive lag recovery retained

### V1.0 Beta 3 — Multi-Monitor Update

- Dedicated ARK monitor selection
- Improved multi-monitor calibration
- Display resolution and position identification
- Improved Windows display scaling support
- Support for negative monitor coordinates
- Calibration validation when display layouts change
- Existing OCR performance retained

### V1.0 Beta 2 — Recognition & Batch Improvements

- Searchable stat selection dropdown
- Improved stat matching
- Automatic punctuation normalization
- Independent batch and resume controls
- Improved target configuration management
- Standalone Windows packaging

### V1.0 Beta 1 — Initial Release

- Initial standalone Windows release
- Automated imbue rerolling
- Configurable target requirements
- All 12 essence tiers supported
- Tek-inspired interface
- Adaptive lag recovery
- Emergency stop and pause controls

## ◆ Bug Reports

Found a problem?

[Submit a bug report here.](../../issues)

Please include:

- Application version
- Screen resolution
- Number of connected monitors
- Windows version
- Description of the problem
- Diagnostic log, with personal information removed

## ◆ Community Feedback

Omega Imbue Reroller is actively being improved based
on feedback from the ARK Omega community.

Many features have been introduced directly because
of community suggestions.

Thank you to everyone participating in beta testing,
reporting bugs and suggesting new features.

Have an idea for improving the application?

[Submit a feature request here.](../../issues)

## ⚠ Disclaimer

This is an unofficial community-developed application.
It is not affiliated with Studio Wildcard or the
ARK Omega development team.

Ensure automation is permitted by your server rules
before using this utility.

OCR recognition is not guaranteed to be completely
accurate. Test on disposable equipment first.

Observed lifetime records and projected cursed values
are informational and depend on accurate recognition.

Do not change equipment during automatic recovery.

The beta executable is unsigned. Verify downloads
and never disable antivirus protection to run it.

---

<div align="center">

### OMEGA // IMBUE REROLLER

**Built for the Omega community.**

TEK EDITION • LESS CLICKING. MORE PLAYING.

[DOWNLOAD](../../releases) • [REPORT A BUG](../../issues)

</div>
