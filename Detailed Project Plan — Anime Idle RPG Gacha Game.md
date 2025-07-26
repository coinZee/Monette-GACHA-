# 🧾 Detailed Project Plan — Anime Idle RPG Gacha Game

## Phase 0 — Planning & Setup 🧠

### ✅ Define Game Concept
- [x] Describe core loop: Gacha → Squad → Idle Battle → Upgrade
- [x] Define player fantasy (Waifu(Big daddies, furries, etc) Collector, Affection Builder, Strategist, etc.)
- [ ] Clarify tone: Semi-wholesome anime with edgy/horny undertones?

### ✅ Define MVP Scope
- [ ] Minimum viable systems (see MVP note)
- [ ] List MVP characters & part categories
- [ ] Set "No NFT / No PvP" in MVP boundaries

### 🛠️ Environment Setup
- [x] Create GitHub repo
- [x] Set up Obsidian project vault
- [ ] Initialize frontend (React + Tailwind)
- [ ] Spin up backend API (Express / Supabase)
- [ ] Set up database schema (Postgres)
- [ ] Setup testing + deployment pipeline (Railway/Vercel + GitHub Actions)

---

## Phase 1 — Core System Prototypes 🧪

### 🏗️ Character Parts System
- [ ] Design part categories (hair, body, eyes, outfits, voices)
- [ ] Create dummy assets for 3–5 parts per category
- [ ] Define part data format (JSON, DB schema)
- [ ] Store + fetch parts from DB via API

### 🎴 Gacha System
- [ ] Define rarity tiers (C, R, SR, SSR, UR)
- [ ] Create pool of 10 MVP characters
- [ ] Write gacha pull logic (pseudo-random w/ pity)
- [ ] UI: Gacha screen w/ pull animation
- [ ] Add "preview character" functionality

### 🤖 AI Interaction System
- [ ] Draft 3–5 character personalities
- [ ] Write prompt templates for LLM
- [ ] Integrate basic chat window (text only)
- [ ] Implement memory (affection level, facts)
- [ ] Store chat logs per user/character

---

## Phase 2 — Gameplay Loop 🔄

### ⚔️ Idle Battle System
- [ ] Define battle formula (DPS, buffs, rarity scaling)
- [ ] Build turn simulator (auto resolve)
- [ ] Squad builder screen (drag & drop or select)
- [ ] Visualize battle logs (text summary or simple UI)
- [ ] Add experience system (waifu level-up)

### 🧍‍♂️ Character Creation UI
- [ ] Drag/drop or select parts to build waifu
- [ ] Preview final character + save
- [ ] Store character config in DB
- [ ] Restrict part selection to owned parts

### 💸 Token Economy
- [ ] Implement wallet connect (optional)
- [ ] Add off-chain token balance per user
- [ ] Deduct token on gacha pull / store purchase
- [ ] Recharge token manually for testing

---

## Phase 3 — Store & Monetization 🛒

### 🛍️ Central Store
- [ ] Build store UI (filter by category / rarity)
- [ ] Display available parts for purchase
- [ ] Purchase flow: token → part → inventory
- [ ] Add part rarity modifiers (eg. seasonal, limited)

### 🎟️ Premium Token Utility
- [ ] Speed-up idle rewards
- [ ] Purchase premium gacha
- [ ] Unlock exclusive AI waifus

---

## Phase 4 — Polish & Pre-Launch 🧽

### 🧪 QA & UX Polish
- [ ] Add error handling + UI feedback
- [ ] Test gacha + battle balance
- [ ] Mobile optimization pass
- [ ] Add sound fx + ambient bgm
- [ ] Accessibility checks (text scale, screen reader alt)

### 📣 Lore & Engagement
- [ ] Write waifu backstories
- [ ] Design first 3 in-game events (Valentine's, Beach, Mecha Month?)
- [ ] Add relationship titles (BFF, Soulbound, etc.)

### 🔒 Safeguards
- [ ] Add content filters to AI prompt
- [ ] Rate limit chat inputs
- [ ] Privacy & data policy draft (GDPR prep)

---

## Phase 5 — Private Alpha 🚧

### 🧪 Invite-Only Testing
- [ ] Set up invite system
- [ ] Track user feedback
- [ ] Monitor logs & bug reports
- [ ] Patch fixes weekly

---

## 🏁 Final TODOs
- [ ] MVP Launch target date?
- [ ] Final polish tasks
- [ ] Monetization plan (opt-in crypto or just cosmetic purchases?)
- [ ] Pre-launch waitlist site?

---

## 📎 Linked Notes (create separate files)

- [[MVP Scope]]
- [[Character Personality Templates]]
- [[Gacha Pool Design]]
- [[Storefront Catalog]]
- [[LLM Prompt Engineering]]
- [[Token Pricing & Balancing]]

