# 📌 Project: Anime Idle RPG Waifu Gacha Game

## 🧠 Vision Statement
A cross-platform idle-RPG anime game featuring collectible waifus, daddies, furries, and custom characters. Uses gacha mechanics, AI interactions, and centralized progression systems. Crypto wallet optional. Token used for progression acceleration and cosmetic content.

---

## 🗂️ Core Pillars

- 🎴 Idle auto-battler + squad-building
- 🎁 Gacha character collection (with rarities)
- 🧠 AI waifus with persistent memory + personality
- 🧬 Character creation via parts from centralized store aka dev store
- 💸 Token used for speeding up progress or unlocking premium content (aka resin?)
- 🧍‍♂️ PvE-focused for 6–12 months post-launch 
- ⚔️ PvP introduced later, async-only
- 🌐 Web-first, mobile-friendly
- 🛒 Centralized store only (no NFT marketplace for now)

---

## 🛠️ MVP Scope

### ✅ Must-Haves
- [ ] Wallet connect (optional)
- [ ] Gacha pull system
- [ ] Idle battle system
- [ ] Basic AI interaction (text-based)
- [ ] Character parts inventory (centralized)
- [ ] Character creation with owned parts
- [ ] Token system (off-chain or hybrid)
- [ ] UI skeleton for store, gacha, squad, chat

### ❌ Not in MVP
- PvP
- NFT minting
- Marketplace
- Full 3D avatars

---

## 💰 Token Utility (TKN)

| Use Case                | Type        |
|-------------------------|-------------|
| Gacha pull cost         | Optional    |
| Speed up timers         | Optional    |
| Unlock premium parts    | Yes         |
| Access special events   | Yes         |
| Battle Pass premium tier| Yes         |

---

## 🛍️ Centralized Store Model

- 🎨 Store sells curated **parts**: hairstyles, bodies, outfits, voices, etc.
- 🧩 Parts are **stackable assets** owned per player
- 👤 Characters are created by fusing owned parts (stored in DB)
- 💾 No on-chain minting (for now)
- 📦 New parts released in themed batches (events, seasons)

---

## 🧬 Character System

```json
{
  "character_id": "char_001",
  "name": "Airi",
  "parts": ["hair_long_black", "body_female_medium", "voice_tsundere_v1"],
  "rarity": "SSR",
  "ai_personality": "tsundere",
  "affection_level": 27,
  "created_by": "user_ABC123",
  "created_at": "2025-07-25"
}

