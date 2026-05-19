# 🎬 data-motion-video — Claude Skill

> Turn data, stats, and numbers into a rendered **30-second MP4 video** — no screen recording, no manual editing. Just describe what you want and get a real video file back.

---

## What This Skill Does

This is a Claude AI skill that builds **data motion-graphic videos** and renders them as actual MP4 files using headless Chromium + ffmpeg. Claude writes the animation, renders it server-side, and hands you the file.

Use it for:
- 🚀 **Launch trailers** for your product or project
- 📊 **Animated stat reveals** from your data or dashboard
- 📱 **X/Twitter videos** (16:9), **Instagram Reels** (9:16), or square feed posts
- 🎯 **Promo films** built around typography and numbers

---

## How It Works

```
Your data + hook  →  Self-playing HTML animation  →  Headless Chromium  →  MP4 file
```

Claude handles the entire pipeline:
1. Finds the **hook** — the one stat that earns the first 3 seconds
2. Plans the **arc** — hook → reveal → punchline → CTA in 30 seconds
3. Builds a **single-file HTML animation** (auto-plays on load)
4. Verifies it with **Playwright screenshots**
5. Renders it to a **real MP4** via headless Chromium + ffmpeg
6. Delivers the file ready to post

---

## Video Structure

Every video follows this 4-move arc:

| Timestamp | Scene |
|---|---|
| 0:00 – 0:03 | Cold open — the hook (one big number) |
| 0:03 – 0:08 | Setup — build context, animate the data |
| 0:08 – 0:21 | Reveal — the surprising or contrarian bit |
| 0:21 – 0:25 | Punchline — the thesis stated plainly |
| 0:25 – 0:30 | CTA — brand + URL |

---

## Output Specs

| Property | Value |
|---|---|
| Default duration | 30 seconds |
| Codec | H.264 (MP4) |
| Frame rate | 30fps |
| File size | ~1–3 MB |
| Audio | Silent (add music in post) |

---

## Supported Platforms

| Platform | Aspect Ratio | Resolution |
|---|---|---|
| X / Twitter | 16:9 | 1920×1080 (default) |
| Instagram Reels / TikTok | 9:16 | 1080×1920 |
| Instagram Feed | 1:1 | 1080×1080 |
| YouTube | 16:9 | 1920×1080 |
| LinkedIn | 16:9 or 1:1 | 1920×1080 |

---

## Design Style

- **Typography:** Fraunces (display serif) + IBM Plex Sans + JetBrains Mono
- **Color palette:** Warm cream `#FAFAF7` background, stone-900 `#1C1917` text
- **Animations:** Subtle — opacity + 20px slide. No swooshes, no glitter
- **Feel:** Editorial, like a New Yorker piece set to motion

---

## Trigger Phrases

Say any of these to Claude to activate this skill:

- "Make a 30-sec video about..."
- "Render an MP4 of these stats"
- "Launch trailer for my project"
- "Animate these numbers"
- "Make a Reel about..."
- "X video showing..."
- "Social cut from this data"

---

## Source

Originally created by [hmalviya9/hitesh.eth](https://github.com/hmalviya9/hitesh.eth/blob/main/data-motion-video-SKILL.md)  
Archived by [@IndiSingh](https://twitter.com/IndiSingh) under [hunterzai16z/data-motion-video](https://github.com/hunterzai16z/data-motion-video)
