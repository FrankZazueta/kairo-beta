# Kairo (beta)

**Free DJ software for Windows.** Public beta.

### [⬇ Download the latest version](https://github.com/FrankZazueta/kairo-beta/releases/latest)

Kairo is DJ software I'm building, and I'd love DJs to try it and tell me what works, what breaks and what's missing.

## What it does

- **Two decks and a club-style mixer:** 3-band isolator EQ, filter, crossfader, sync, key lock, key shift, hot cues, loops, beat jumps, effects
- **Stems:** drums, bass, melody and vocals separated on your graphics card while the track plays (about 15–20 s for a whole song), with effects on a single stem
- **One-button transitions:** blend, drums first, vocal takeover, echo out, filter fade, brake and more. Reshape them bar by bar, and preview them in your headphones before the crowd hears them
- **Mashups:** loop one track's beat under another track's vocals, built ahead and saved
- **Your library worked out for you:** tempo, key, energy (1–10) and song sections (intro, build, drop, breakdown…) for every song
- **"Play next" suggestions** that learn from your Serato history, if you have one
- **Sampler**, and **beat-synced visuals** for a second screen or projector
- **Headphone cue** on a second sound card
- **Record your mix** to a WAV file

## Requirements

- Windows 10 or 11, 64-bit
- A graphics card with DirectX 12 (NVIDIA, AMD or Intel from the last ~8 years) for fast stems; without one, stems are much slower
- Headphone cue needs a second output, such as a USB sound card or your PC's headphone jack
- No DJ controller support yet: mouse and keyboard only

## Installing

1. Download `Kairo_<version>_x64-setup.exe` from the [latest release](https://github.com/FrankZazueta/kairo-beta/releases/latest) and run it. It installs for your Windows user only; no admin rights needed.
2. Windows will probably say **"Windows protected your PC"**, because Kairo isn't code-signed yet. Click **More info → Run anyway**.
3. In Kairo, click **Add a music folder**. Kairo reads your songs and works out their tempo, key, energy and sections in the background.

To uninstall: Windows Settings → Apps → Kairo.

## Good to know

- Kairo plays in WASAPI **exclusive mode** by default for low latency (about 11 ms). While it runs, other apps can't play sound through that same output. You can switch to shared mode in **Audio settings**.
- **Everything stays on your PC.** Your music, library and stems are never uploaded anywhere.
- It's a beta: please don't rely on it for a paying gig yet.

## Known issues

- The visuals window stutters while stems are being separated.
- Windows only for now.

## Problems and ideas

[Open an issue](https://github.com/FrankZazueta/kairo-beta/issues/new/choose): a bug report or an idea. Screenshots help a lot.

---

Kairo is free to use during the beta. It isn't open source: this page has the downloads and the issue tracker, not the code. Kairo is built on open-source software and models; their licences are in Kairo's **About** panel and in `THIRD-PARTY-NOTICES.txt` in the install folder.

© 2026 Frank Zazueta
