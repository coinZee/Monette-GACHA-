## 🧠 Vision Statement
A cross-platform idle-RPG anime game featuring collectible waifus, daddies, furries, and custom characters. Uses gacha mechanics, AI interactions, and centralized progression systems. Crypto wallet optional. Token used for progression acceleration and cosmetic content.

---

## 🗂️ Core Pillars

- 🎴 Idle auto-battler + squad-building
- 🎁 Gacha character collection (with rarities)
- 🧠 AI waifus with persistent memory + personality
- 🧬 Character creation via parts from centralized store
- 💸 Token used for speeding up progress or unlocking premium content
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
```

---

## 🧠 AI Interaction System

### Per Character:
- Prompt seed (personality)
- Memory: long-term affection, user facts, chat history
- Mood & relationship stage

### Basic Prompt Format:
```
You are {{name}}, a {{personality}} anime companion in a fantasy sci-fi world. Your user is {{username}}. Speak like an anime character and show emotional variation.

Traits: {{trait_list}}
History with user: {{relationship_log}}
```

---

## 📅 Roadmap (High-Level)

### Phase 1 — Pre-MVP
- [ ] Define character types + part categories
- [ ] Design gacha + rarity rules
- [ ] Prototype AI convo system (mock character)
- [ ] Wire up basic wallet/token support

### Phase 2 — MVP Build
- [ ] Gacha system live (10 characters)
- [ ] Storefront for parts
- [ ] Basic idle battle engine
- [ ] Character creation with parts
- [ ] Token usage in store
- [ ] AI waifu chat working for at least 3 waifus

### Phase 3 — Launch Prep
- [ ] Polish UI/UX
- [ ] Add early monetization layer
- [ ] Write lore, events, and AI backstories
- [ ] Invite-only alpha with feedback loop

---

## 🧩 System Architecture (Rough)

| Layer        | Tech Stack Idea               |
| ------------ | ----------------------------- |
| Frontend     | React + Tailwind + PWA        |
| Backend API  | Node.js (Express) or Supabase |
| AI Engine    | OpenAI / Gemini / LM Studio   |
| DB           | PostgreSQL                    |
| Token System | Custom off-chain ledger       |
| Hosting      | Vercel / Railway / VPS        |

---

## 🧠 Notes

- Prioritize gameplay feel and visual polish even in MVP.
- Don’t overload gacha pool at launch — 10–15 solid units are enough.
- Create character archetypes (tsundere, brooding, hyper, etc.) for easy scaling.
- AI convo needs safeguards to avoid spam or creepy stuff (rate limit, filters).

---

## 🏁 Next Steps

- [ ] Confirm part categories (hair, body, voice, etc.)
- [ ] Define token pricing per part + per gacha
- [ ] Draft 3–5 sample characters with AI templates
- [ ] Set up Notion board or GitHub issues for task tracking

---

