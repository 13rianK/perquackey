---
layout: default
title: Privacy Policy — Perquackey
---

# Privacy Policy

**Perquackey**
*Last updated: April 21, 2026*

## Overview

Perquackey ("the App") is a word dice game. Your privacy is important to us. This policy explains what data the App collects (or doesn't).

## Data Collection

**The App does not collect, store, or transmit any personal data.** Specifically:

- No account or sign-up is required
- No personal information is requested or stored
- No analytics or tracking SDKs are included
- No advertising networks or ad SDKs are included
- No cookies or device identifiers are collected

## Data Stored on Your Device

The App stores the following data **locally on your device only**, using standard iOS storage (UserDefaults and the app Documents directory):

- Game settings (timer duration, vulnerability threshold, sound and haptic preferences)
- Game statistics (games played, win/loss counts, best scores, longest word, streaks)
- Saved game state (to resume an interrupted game)
- Daily Challenge history (date, score, words found for each attempt)

This data never leaves your device and is deleted if you uninstall the App.

## Third-Party Services

The App uses the following services, each with a narrow, specific purpose:

### Apple Game Center

Used for achievements, the daily challenge leaderboard, and the all-time best-turn leaderboard. Game Center is managed entirely by Apple and governed by [Apple's Privacy Policy](https://www.apple.com/privacy/). Game Center is optional — the App functions fully without a Game Center account.

### Apple StoreKit

Used to process the one-time in-app purchase that unlocks Classic Mode, Word Analysis, and Lifetime Statistics. StoreKit is managed entirely by Apple and governed by [Apple's Privacy Policy](https://www.apple.com/privacy/). Purchase receipts are handled by Apple; the App does not receive or store payment information.

### Free Dictionary API (dictionaryapi.dev)

When you tap a word on the post-game Word Analysis screen, the App sends the single word being looked up to [dictionaryapi.dev](https://dictionaryapi.dev) over HTTPS to retrieve its English definition. No user identifiers, device information, or account data is transmitted. The only data sent per request is the word being looked up. The provider is stateless and does not retain query logs. Definitions are licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) and attributed within the App.

No other third-party services, APIs, or SDKs are used.

## Third-Party Content

The App displays word definitions fetched from the Free Dictionary API (licensed CC BY-SA 3.0). Attribution is provided in the in-app definition view. The bundled English word list ("ENABLE") is in the public domain.

## Children's Privacy

The App does not collect any data from any user, including children. It is suitable for all ages (rated 4+).

## Changes to This Policy

If this policy changes, the updated version will be posted at this URL with a new "Last updated" date.

## Contact

If you have questions about this privacy policy, please [submit a request](https://docs.google.com/forms/d/e/1FAIpQLScv-0Vabgt-Kesj-9t67T4_6Hgx-wzKToeB4upK5EdLWTyDcQ/viewform) or [open an issue](https://github.com/13rianK/perquackey/issues) on GitHub.
