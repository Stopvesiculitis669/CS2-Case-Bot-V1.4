# 🎮 CS2 Case Bot for Streamer.bot V1.4

<p align="center">
  <img src="CS2 Case Bot Logo.png" width="128" height="128">
</p>

![Version](https://img.shields.io/badge/version-1.4-blue.svg)
![Streamer.bot](https://img.shields.io/badge/Streamer.bot-1.0.4+-orange.svg)
[![Ko-fi](https://img.shields.io/badge/Ko--fi-Support%20Me-FF5E5B?style=flat-square&logo=kofi&logoColor=white)](https://ko-fi.com/mk4gtiguy)
[![License](https://img.shields.io/badge/License-MIT%20%2B%20Disclaimer-yellow.svg?style=flat-square)](LICENSE)

A complete CS2 case opening bot for Streamer.bot with inventory, economy, jackpot, leaderboards, and 11 cases. Perfect for CS2 streamers who want to add interactive engagement without real money.

**✅ Fully tested and stable!**

---

## ⚠️ Disclaimer

> This bot is a **fan project for entertainment purposes only**. All CS2 skin names, case names, and trademarks are property of **Valve Corporation**. This bot is not affiliated with, endorsed by, or sponsored by Valve. No real money or actual CS2 items are involved — everything is simulated with fake currency and emoji-based items.

---

## 🚀 Quick Install (5 Minutes)

### One-Click Import (Actions)

1. Download [`CS2-Case-Bot-V1.4-Actions.sb`](CS2-Case-Bot-V1.4-Actions.sb)
2. In Streamer.bot → **Actions** → Right-click → **Import** → Select the file
3. Open [`persisted-globals.txt`](persisted-globals.txt) and copy each line
4. In Streamer.bot → **Services** → **Global Variables** → **Persisted Globals** → Add each line as a new variable
5. Set `!jackpotdraw` and admin commands to **Moderator** permission
6. Type `!help` in your chat to test!

**Actions import automatically. Globals take ~5 minutes to add manually.**

### Manual Setup (For Learning or Modifying)

Follow [`setup-guide.md`](setup-guide.md) and use the code in [`V1.4-Complete-Code-Reference.md`](V1.4-Complete-Code-Reference.md)

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| **11 Cases** | Dreams, Recoil, Kilowatt, Revolution, Fracture, Clutch, Prisma, DangerZone, Horizon, Chroma3, Spectrum2 |
| **Realistic Skins** | 200+ skin names from actual CS2 cases |
| **StatTrak™ Items** | 10% chance, 2x sell value |
| **Item Conditions** | FN, MW, FT, WW, BS with value multipliers |
| **Case Costs** | $0.50 – $3.00 (simulated currency) |
| **Inventory System** | Collect, sell by number, or sell all |
| **Daily Rewards** | Claim $5-$25 every 24 hours |
| **Trade-Up System** | Trade 10 Blues for 1 Purple |
| **Jackpot System** | Enter with random item, winner takes all |
| **Trade System** | Trade items between users |
| **Gift System** | Gift cases to other viewers |
| **Streak System** | Bonuses at 10, 25, 50, 100 opens |
| **Achievements** | Earn badges for milestones |
| **Case Unlocking** | New cases unlock every 25 opens |
| **Leaderboards** | Top money, inventory, gold pulls, opens |
| **30+ Commands** | Full chat interaction |

---

## 📋 Commands

| Command | Description |
|---------|-------------|
| `!setcase [name]` | Switch your active case |
| `!case` | Open your selected case |
| `!inv` | View your inventory counts |
| `!sell` | Show numbered inventory |
| `!sell [number]` | Sell specific item |
| `!sellall` | Sell entire inventory |
| `!sellhelp` | Selling instructions |
| `!balance` | Check your balance |
| `!daily` | Claim daily reward ($5-$25) |
| `!tradeup` | Trade 10 Blues for a Purple |
| `!streak` | Check your open streak |
| `!badges` | View earned achievements |
| `!trade @user #` | Trade an item |
| `!accepttrade` | Accept a trade offer |
| `!denytrade` | Deny a trade offer |
| `!gift @user [case]` | Gift a case to someone |
| `!jackpot` | Enter jackpot with random item |
| `!jackpotinfo` | See current jackpot status |
| `!jackpotdraw` | Draw jackpot winner (Mods only) |
| `!mystats` | Your personal case stats |
| `!casestats` | Total opens per case |
| `!caseinfo` | List available cases with prices |
| `!odds` | Show drop rates |
| `!inventoryvalue` | Show your inventory value |
| `!topmoney` | Top 5 balances |
| `!topinventory` | Top 5 inventory values |
| `!topgolds` | Top 5 gold pullers |
| `!topopens` | Top 5 most cases opened |
| `!help` | Show all commands |

### Admin Commands (Moderator+)

| Command | Description |
|---------|-------------|
| `!givebalance @user amount` | Add money to user |
| `!takebalance @user amount` | Remove money from user |
| `!giveitem @user "item"` | Give item to user |
| `!resetuser @user` | Reset user's data |
| `!setcaseprice Case price` | Change case cost |

---

## 💰 Case Costs

| Case | Cost |
|------|------|
| Recoil | $0.50 |
| Dreams | $1.50 |
| Revolution | $1.50 |
| Kilowatt | $2.00 |
| Fracture | $2.00 |
| Horizon | $2.00 |
| Chroma3 | $2.00 |
| Clutch | $3.00 |
| Prisma | $2.50 |
| DangerZone | $2.50 |
| Spectrum2 | $2.50 |

---

## 🎲 Drop Rates & Values

| Rarity | Emoji | Chance | Base Value |
|--------|-------|--------|-------------|
| Gold (Knife/Gloves) | 🟡 | 2.6% | $50.00 |
| Red (Covert) | 🔴 | 2.5% | $5.00 |
| Pink (Classified) | 💗 | 2.5% | $1.50 |
| Purple (Restricted) | 🟣 | 5.0% | $0.50 |
| Blue (Mil-Spec) | 🔷 | 87.4% | $0.10 |

### Condition Multipliers

| Condition | Chance | Multiplier |
|-----------|--------|------------|
| Factory New (FN) | 5% | 2.0x |
| Minimal Wear (MW) | 15% | 1.5x |
| Field-Tested (FT) | 50% | 1.0x |
| Well-Worn (WW) | 20% | 0.75x |
| Battle-Scarred (BS) | 10% | 0.5x |

### Special Features
- **StatTrak™**: 10% chance, 2x sell value
- **Streak Bonuses**: 10 ($5), 25 ($15), 50 ($50), 100 ($200)
- **Case Unlocks**: New case every 25 opens

---

## 📁 Files Included

| File | Description |
|------|-------------|
| `CS2 Case Bot Logo.png` | Repository logo |
| `README.md` | Main documentation |
| `LICENSE` | MIT License + IP Disclaimer |
| `setup-guide.md` | Step-by-step installation |
| `persisted-globals.txt` | Skin lists for copy/paste |
| `V1.4-Complete-Code-Reference.md` | All action C# code |
| `CS2-Case-Bot-V1.4-Actions.sb` | One-click action import |

---

## 🔧 Commands Cheat Sheet for Viewers

**Case Commands**
- `!setcase [Dreams/Recoil/Kilowatt/Revolution/Fracture/Clutch/Prisma/DangerZone/Horizon/Chroma3/Spectrum2]` - Switch cases
- `!case` - Open your selected case
- `!caseinfo` - See all cases and prices
- `!odds` - See drop rates

**Economy Commands**
- `!balance` - Check your balance
- `!daily` - Claim free $5-$25
- `!inv` - View inventory
- `!sell` - Show numbered inventory
- `!sell [number]` - Sell specific item
- `!sellall` - Sell everything
- `!tradeup` - Trade 10 Blues for 1 Purple
- `!inventoryvalue` - Total inventory worth

**Trading & Gifting**
- `!trade @user #` - Trade an item (use number from !inv)
- `!accepttrade` - Accept a trade
- `!denytrade` - Deny a trade
- `!gift @user [case]` - Gift a case

**Streaks & Badges**
- `!streak` - Check your open streak
- `!badges` - View your achievements

**Jackpot Commands**
- `!jackpot` - Enter with a random item
- `!jackpotinfo` - See current pot

**Stats & Leaderboards**
- `!mystats` - Your personal stats
- `!casestats` - Total case opens
- `!topmoney` - Richest users
- `!topinventory` - Highest inventory value
- `!topgolds` - Most gold pulls
- `!topopens` - Most cases opened

**Help**
- `!help` - Show all commands

---

## 🤝 Support the Project

If this bot brings entertainment to your stream, consider supporting continued development:

[![Ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/mk4gtiguy)

Your support helps keep the project maintained and updated!

---

## 📝 License

This project is licensed under the **MIT License** with an **IP Disclaimer** — see [LICENSE](LICENSE) file for details.

- ✅ Free to use, modify, and share
- ✅ Donations accepted
- ❌ Not for commercial resale
- ❌ Not affiliated with Valve Corporation

---

## 🙏 Credits

- Created by **Mk4gtiguy**
- Skin names from Counter-Strike 2 © Valve Corporation
- Built for [Streamer.bot](https://streamer.bot)

---

## ⚠️ Legal Note

This software is a **fan project** and does not contain any actual gambling or real money transactions. All currency and items are simulated for entertainment purposes only.

---

## 📌 Version History

| Version | Changes |
|---------|---------|
| V1.4 | Added StatTrak, conditions, 5 new cases, trading, gifting, streaks, achievements, case unlocking, sell by number, admin commands |
| V1.3 | Added case switching, costs, fixed jackpot commands |
| V1.2 | Initial release |
