# ﷽

# آلة الزمن — Time Machine v1.0

An interactive educational game about Muslim scientists who changed the world.  
Travel through time, discover 10 legendary scientists, collect stars and cards.

**Single HTML file · 186 KB · 12 screens · 25+ animations · No dependencies**

---

## 🧑‍🔬 Scientists Featured

| # | Scientist | Emoji | City | Era | Field |
|---|-----------|-------|------|-----|-------|
| 1 | جابر بن حيان — Jābir ibn Hayyān | ⚗️ | Baghdad | 780 | Chemistry |
| 2 | الخوارزمي — Al-Khwārizmī | 📐 | Baghdad | 820 | Mathematics |
| 3 | عباس بن فرناس — Abbās ibn Firnās | 🦅 | Córdoba | 852 | Aviation |
| 4 | فاطمة الفهري — Fatima al-Fihri | 🎓 | Fez | 859 | Education |
| 5 | ابن سينا — Ibn Sīnā | 💊 | Bukhara | 1000 | Medicine |
| 6 | ابن الهيثم — Ibn al-Haytham | 💡 | Cairo | 1000 | Optics |
| 7 | البيروني — Al-Bīrūnī | 🌍 | Ghazni | 1040 | Geography |
| 8 | الإدريسي — Al-Idrīsī | 🗺️ | Sicily | 1154 | Cartography |
| 9 | الجزري — Al-Jazarī | ⚙️ | Diyarbakir | 1206 | Engineering |
| 10 | الزهراوي — Al-Zahrāwī | 🏥 | Córdoba | 1000 | Surgery |

---

## ✨ Features

**Core Gameplay**
- 10 playable levels with 4-page stories, interactive challenges, and 3-star ratings
- Progressive level unlocking with replay support
- Free Play mode to unlock all levels instantly

**Engagement**
- 🎯 Daily Challenge — new question every day with streak tracking 🔥
- 🏆 8 Achievement Badges — from First Discovery to Golden Age Scholar
- 🧩 Mystery Scientist — guess the scientist from 3 progressive clues (era → field → city)
- 📜 Scholar's Passport — visual passport with stamps for each completed level

**Languages & Accessibility**
- 🌐 Trilingual — Arabic (RTL) · Français · English — instant switch
- 🔢 Independent numeral toggle — ١٢٣ Hindu-Arabic / 123 Western
- 🎤 Pronunciation mode — hear Arabic scientist names via Web Speech API

**Themes**
- 🔭 Astrolabe — dark navy, brass gold, circular rings
- 📐 Al-Khwarizmi — emerald green, gold, 8-pointed star
- 💡 Ibn Al-Haytham — deep purple, prismatic, light prism
- ☀️ Al-Andalus — warm ivory, terracotta, zellige tiles

**Audio & Visual**
- 🔊 12 sound effects synthesized via Web Audio API (no external files)
- ✨ 25+ animations — portal, confetti, starfield, bursts, staggered reveals
- 📱 PWA ready — haptic feedback, swipe navigation, Add to Home Screen

---

## 📌 Header Bar

Persistent across all 12 screens:

```
🔊 Mute │ 🗺️ Map │ 🔭📐💡☀️ Themes │ ١٢٣ · 123 │ ﷽ v1.0 │ عربي FR EN
```

---

## 🗺️ Game Flow

```
Home → Daily Challenge
  ↓
Journey Map → Select Level
  ↓
City Arrival → Meet Scientist + 🔊 Pronunciation
  ↓
Story (4 swipeable pages)
  ↓
Challenge (multiple choice)
  ↓
Victory + Stars + Fun Fact
  ↓
Museum + Badges + 🧩 Mystery Scientist + 📜 Passport
```

**12 Screens:** Home · Map · City · Scientist · Story · Challenge · Victory · Museum · Mystery · Passport · Splash · Onboarding

---

## 🏆 Achievement Badges

| Badge | Emoji | Requirement |
|-------|-------|-------------|
| First Discovery | 🌟 | Complete 1 level |
| Explorer | 🧭 | Complete 3 levels |
| Scholar | 📚 | Complete 5 levels |
| Master | 🎓 | Complete 7 levels |
| Polymath | 🧠 | Complete 10 levels |
| Golden Age | 👑 | Earn 30 stars |
| Dedicated | 🔥 | 3-day streak |
| Streak Master | ⚡ | 7-day streak |

---

## 💾 localStorage Keys

| Key | Purpose |
|-----|---------|
| `tm_lang` | Language preference (ar / fr / en) |
| `tm_stars` | Star ratings per level (JSON) |
| `tm_mute` | Mute toggle |
| `tm_onboard` | Onboarding completed |
| `tm_theme` | Theme choice |
| `tm_num` | Numeral format (hindu / western) |
| `tm_freeplay` | Free play mode |
| `tm_dc_date` | Last daily challenge date |
| `tm_dc_streak` | Daily challenge streak count |

---

## ⚙️ Technical Specs

| Spec | Value |
|------|-------|
| Version | 1.0 |
| File size | ~186 KB |
| Lines of code | ~1,535 |
| External dependencies | Google Fonts (Amiri, Tajawal) |
| Screens | 12 |
| Levels | 10 |
| Languages | 3 |
| Themes | 4 |
| Animations | 25+ |
| Sound effects | 12 (synthesized) |
| Badges | 8 |
| Daily questions | 10 |

---

## 📖 How to Use

1. Open `timemachine.html` in any modern browser
2. Select your language, pick a theme, choose your numeral format
3. Tap **Start Journey**
4. Complete levels in order — or toggle **Free Play** to explore freely
5. Don't forget the **Daily Challenge** on the Home screen!

**Mobile install:** Tap your browser's share button → **"Add to Home Screen"** for a native app experience with haptic feedback and swipe navigation.

**Browser support:** Chrome/Edge 80+ · Safari 14+ · Firefox 80+ · Mobile Chrome & Safari (primary target)

---

## 📁 Project Files

| File | Description |
|------|-------------|
| `timemachine.html` | The game (single self-contained file) |
| `readme.html` | Visual documentation page |
| `README.md` | This file |
| `logo.svg` | Workshop DIY logo (gold) |

---

## 🏗️ Built With

- Vanilla HTML / CSS / JavaScript
- Web Audio API (sound synthesis)
- Web Speech API (pronunciation)
- CSS animations & transitions
- SVG patterns per theme
- localStorage persistence

---

*© 2026 Workshop-DIY · Educational Use*
