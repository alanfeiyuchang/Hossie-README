# Hossie — A Trick‑Taking Card Game for iPhone & iPad

> Six cards. Six tricks. One bold call: **Hossie**.

Hossie is a fast, four‑player, two‑versus‑two trick‑taking card game built natively for iOS in SwiftUI. Bid for tricks, pick a mode (High, Low, or Jack‑of‑a‑suit trump), and race your partner to **50 points**. Play offline against bots, locally with friends over the same Wi‑Fi/Bluetooth, or online in private rooms.

---

## Table of Contents

- [Highlights](#highlights)
- [How to Play](#how-to-play)
- [Game Modes](#game-modes)
- [Multiplayer](#multiplayer)
- [Accessibility & Languages](#accessibility--languages)
- [Requirements](#requirements)
- [Privacy](#privacy)
- [Support](#support)
- [App Store Submission Info](#app-store-submission-info)
- [Credits](#credits)

---

## Highlights

- **Four‑player 2v2 trick‑taking** with a compact 24‑card deck (9, 10, J, Q, K, A in four suits).
- **Bidding ladder** from 1 trick all the way up to **4× Hossie** for huge swings.
- **Three game modes** — High, Low, and Jack‑of‑a‑suit (with right‑bower / left‑bower mechanics).
- **Hossie contracts** — declare big, sit your partner, and optionally swap a card before tricks begin.
- **Smart bot AI** to play solo any time, plus a built‑in **Must‑Win Lab** for studying solid‑suit hands.
- **Local multiplayer** over MultipeerConnectivity (Wi‑Fi / Bluetooth, no account needed).
- **Online multiplayer** via Photon rooms with quick chat, custom avatars, and reconnection support.
- **Tutorial & rule book** with diagrams, plus an interactive Must‑Win lab tool.
- **Custom profile avatars** (pick from your photo library) and **player names** that travel with you across rooms.
- **Quick Chat** for friendly table banter without a keyboard.
- **English + 简体中文 (Simplified Chinese)** UI, switchable on the fly without restarting.
- **Seasonal themes** (e.g., a festive birthday palette unlocked with redeem code `0502` during May 1–9).
- **Universal app** — looks at home on iPhone and iPad.
- Built with **SwiftUI**, optimized for modern iOS, with full sound effects.

---

## How to Play

Hossie is a **partnership trick‑taking** game. Partners sit across from each other; you are always at the bottom seat.

1. **Deal** — six cards to each player from a 24‑card deck (9, 10, J, Q, K, A × four suits).
2. **Bid** — going around the table, each player either raises the bid or passes.
   - Numeric bids `1`–`5` claim that many tricks for the bidding side.
   - After `5`, the bid escalates to **Hossie**, **2× Hossie**, **3× Hossie**, **4× Hossie** — bigger reward, bigger penalty.
3. **Choose mode** — the highest bidder ("the maker") picks how tricks are decided this round (see below).
4. **Hossie card swap** — if the winning bid is a Hossie, the maker's partner sits out the round. Before tricks, the maker may offer one card to swap with the partner; the partner returns one card. Either side can decline.
5. **Play tricks** — six tricks per round. You must follow the led suit if you can. The strongest card under the chosen mode wins; the trick winner leads next.
6. **Score** — makers gain or lose points based on whether they hit their contract; defenders score from tricks they win. **First team to 50 points wins the match.**

Open the in‑app **How to Play** section for diagrams, examples, and the Must‑Win lab.

---

## Game Modes

The maker picks one of three modes for the round:

- **High** — In the suit that was led, **A is strongest**, then K → Q → J → 10 → 9.
- **Low** — In the led suit, **9 is strongest**, then 10 → J → Q → K → A weakest.
- **Jack of a suit** — That suit becomes **trump**. The **Jack of trump (right bower)** beats everything, then the **same‑colored Jack (left bower)**, then remaining trump cards, then cards in the lead suit. Off‑suit cards can't win.

---

## Multiplayer

Hossie supports several ways to play:

| Mode            | How it works                                                                                       |
|-----------------|----------------------------------------------------------------------------------------------------|
| **Solo vs bots**| Practice or play any time; AI partners and opponents.                                             |
| **Local LAN**   | Built on Apple's **MultipeerConnectivity** — devices nearby auto‑discover via Wi‑Fi/Bluetooth.    |
| **Online**      | Private rooms powered by **Photon** — share a short code with friends to join from anywhere.       |
| **Mixed**       | Fill empty seats with bots in any room when you don't have four humans.                            |

Players can pick a **display name** and **profile avatar** (from their photo library), use **Quick Chat** taunts, and rejoin a session automatically after brief disconnects.

---

## Accessibility & Languages

- Full **English** and **Simplified Chinese (简体中文)** UI; toggle from Settings without restarting.
- High‑contrast felt theme designed for clarity at a glance.
- Native **Dynamic Type**‑friendly SwiftUI layouts.
- Supports both **portrait and landscape** orientations on iPad.

---

## Requirements

- **iPhone** or **iPad** running **iOS 18.0** or later.
- For local multiplayer: Wi‑Fi or Bluetooth enabled, and Local Network permission granted.
- For online multiplayer: an active internet connection.
- For setting a custom avatar: Photo Library access.

---

## Privacy

Hossie is designed to collect as little as possible.

- The app does **not** require an account, sign‑up, or email.
- Your **display name**, **avatar image**, and **language preference** are stored locally on your device.
- During multiplayer, only the data needed to play the game (player name, avatar thumbnail, bids, plays, chat taunts) is exchanged with other players in your room.
- The app does **not** include third‑party advertising or in‑app purchases.
- Photo Library access, when granted, is used **only** to pick a profile avatar — images are stored locally.
- Local Network access is used **only** to discover nearby players for LAN multiplayer.
- Online multiplayer routes traffic through **Photon** game servers; no personally identifying account data is sent.

A full Privacy Policy URL is included in the App Store listing.

---

## Support

- **Email:** alanfeiyuchang@gmail.com
- **Issues / feature requests:** please open an issue on this repository.

---

## App Store Submission Info

The following fields are ready to drop into App Store Connect.

### App Information

| Field                       | Value                                                                                          |
|-----------------------------|------------------------------------------------------------------------------------------------|
| **App Name**                | Hossie                                                                                         |
| **Subtitle** (≤ 30 chars)   | Bid, swap, and take the trick                                                                  |
| **Bundle ID**               | `ACM-Hossie`                                                                                   |
| **SKU**                     | hossie-ios-001                                                                                 |
| **Primary Category**        | Games                                                                                          |
| **Secondary Category**      | Games › Card                                                                                   |
| **Primary Language**        | English (U.S.)                                                                                 |
| **Localizations**           | English, Simplified Chinese (zh‑Hans)                                                          |
| **Pricing**                 | Free                                                                                           |
| **In‑App Purchases**        | None                                                                                           |
| **Contains Ads**            | No                                                                                             |
| **Sign‑In Required**        | No                                                                                             |
| **Made for Kids**           | No                                                                                             |
| **Game Center Enabled**     | No                                                                                             |
| **Copyright**               | © 2026 Feiyu Chang                                                                             |

### Promotional Text (≤ 170 chars)

> New: festive birthday theme + Quick Chat. Play Hossie online, on your local network, or solo against bots — fast trick‑taking matches in under 10 minutes.

### Description (≤ 4000 chars)

> **Hossie — A Trick‑Taking Card Game**
>
> Hossie is a snappy, four‑player, two‑versus‑two trick‑taking card game. Six cards, six tricks, one bold call. Race your partner to 50 points and outsmart your opponents through clever bidding and tight card play.
>
> **What makes Hossie special**
>
> • A compact 24‑card deck — quick to deal, fast to finish, deep to master.
> • A full bidding ladder, from a cautious 1 trick all the way up to a heroic 4× Hossie.
> • Three modes per round: High, Low, or Jack‑of‑a‑suit (with right‑bower and left‑bower mechanics).
> • Sit‑your‑partner Hossie contracts with optional pre‑trick card swaps for huge swings.
> • Strong on‑device AI so you can play any time, anywhere — no internet required.
>
> **Play how you like**
>
> • Solo against bots for a quick round on the go.
> • Local multiplayer with friends in the same room over Wi‑Fi or Bluetooth — no accounts, no setup.
> • Online private rooms with friends anywhere, powered by Photon. Share a code, sit down, deal.
> • Mix and match — fill empty seats with bots whenever you don't have four humans.
>
> **Built for iOS**
>
> • Native SwiftUI design that looks at home on iPhone and iPad.
> • Full English and Simplified Chinese (简体中文) localization, switchable on the fly.
> • Profile avatars, custom names, and Quick Chat taunts to bring the table to life.
> • A built‑in tutorial with diagrams plus a Must‑Win Lab to study solid‑suit hands.
> • Seasonal themes you can unlock with redeem codes throughout the year.
>
> Whether you grew up playing Hossie at the kitchen table or you're brand new to trick‑taking games, Hossie's clean rules and short matches make it easy to pick up and hard to put down.
>
> Deal in. Bid bold. Take the trick.

### Keywords (≤ 100 chars, comma‑separated)

```
card,trick,bid,partner,euchre,whist,hossie,trump,multiplayer,solo,offline,strategy
```

### Support URL

`https://github.com/alanfeiyuchang/Hossie-README`

### Marketing URL (optional)

`https://github.com/alanfeiyuchang/Hossie-README`

### Privacy Policy URL

`https://github.com/alanfeiyuchang/Hossie-README/blob/main/PRIVACY.md`

### Age Rating

| Question                             | Answer            |
|--------------------------------------|-------------------|
| Cartoon or Fantasy Violence          | None              |
| Realistic Violence                   | None              |
| Sexual Content or Nudity             | None              |
| Profanity or Crude Humor             | None              |
| Alcohol, Tobacco, or Drug Use        | None              |
| Mature/Suggestive Themes             | None              |
| Horror/Fear Themes                   | None              |
| Gambling and Contests                | **None**          |
| Unrestricted Web Access              | No                |
| Simulated Gambling                   | **No**            |
| User‑Generated Content               | Limited (Quick Chat presets + display name only) |

> ⚠️ **Important — Gambling note for App Review:** Hossie is a card game with **no real‑money wagering, no virtual currency, and no simulated gambling**. Bidding refers to in‑game trick contracts only. Expected age rating: **4+**.

### App Privacy ("Data the app collects")

| Data Type                | Collected? | Linked to user? | Used for tracking? | Purpose                  |
|--------------------------|------------|-----------------|--------------------|--------------------------|
| Name (display name)      | Yes        | No              | No                 | App functionality        |
| Photos (profile avatar)  | Yes (locally only) | No        | No                 | App functionality        |
| Coarse Location          | No         | —               | —                  | —                        |
| Contacts                 | No         | —               | —                  | —                        |
| Identifiers              | No         | —               | —                  | —                        |
| Usage Data / Diagnostics | No         | —               | —                  | —                        |

The app does not collect any data that leaves the device except for the game‑play data exchanged with other players in your multiplayer room.

### Required Permission Strings (already in `Info.plist`)

| Key                                              | Suggested copy                                                                                              |
|--------------------------------------------------|-------------------------------------------------------------------------------------------------------------|
| `NSPhotoLibraryUsageDescription`                 | "Choose a photo to use as your in‑game profile avatar. Photos stay on your device."                          |
| `NSLocalNetworkUsageDescription`                 | "Hossie uses your local network to find nearby players for LAN multiplayer."                                |
| `NSBonjourServices`                              | `_hossie._tcp`, `_hossie._udp`                                                                              |
| `NSBluetoothAlwaysUsageDescription`              | "Hossie can use Bluetooth to discover nearby players for offline multiplayer."                              |
| `NSCameraUsageDescription` *(only if used)*      | "Hossie may use the camera to capture a profile avatar."                                                    |

### Build Settings

| Setting                          | Value                |
|----------------------------------|----------------------|
| **Marketing Version**            | 1.0                  |
| **Build Number**                 | 5                    |
| **Minimum iOS**                  | 18.0                 |
| **Targeted Device Family**       | iPhone, iPad         |
| **Supported Orientations**       | Portrait, Landscape  |
| **Encryption (Export Compliance)** | Uses only standard iOS HTTPS / TLS — set `ITSAppUsesNonExemptEncryption = NO` in Info.plist |

### Required Screenshots (provide for each device class)

Take one screenshot per item below in **both languages (en, zh‑Hans)** at the device sizes Apple currently requires:

1. Title / home screen.
2. Bidding overlay during a round.
3. Game mode selection (High / Low / Jack of a suit).
4. Mid‑trick play with cards on the felt.
5. Round‑complete scoring screen showing both teams.
6. How‑to‑Play tutorial with the bid strip diagram.
7. Online room / multiplayer lobby.
8. Settings sheet showing language toggle and avatar.

### App Review Notes (for the reviewer)

> Hossie is a single‑purpose card game. There is no account, no in‑app purchase, no advertising, and no real‑money or simulated gambling.
>
> To test multiplayer:
> 1. Tap **Online** on the home screen.
> 2. Choose **Create Room** — the app will display a 4‑character room code.
> 3. On a second device, choose **Join Room** and enter that code.
> 4. Empty seats can be filled with bots so a single reviewer can complete a full round.
>
> The "Must‑Win Lab" inside How‑to‑Play is an offline tutorial tool — pick six cards and a mode, and the app reports whether the hand passes the solid‑suit must‑win test. No network calls.

### Demo Account

> Not applicable — Hossie does not require sign‑in.

---

## Credits

- **Design & Engineering:** Feiyu Chang
- **Networking:** Photon Realtime SDK, Apple MultipeerConnectivity
- **Built with:** SwiftUI, Swift, RealityKit‑ready architecture

---

© 2026 Feiyu Chang. All rights reserved. Hossie and the Hossie mark are trademarks of their respective owner.
