# 🔧 Tech Stack Overview – Waifu Idle RPG (Web3)

## 🧠 Goal
Build an idle-RPG anime gacha game with AI-driven character interactions, NFT support, and crypto token economy. MVP first, scalable and flexible later. Mobile first web based.

---

## 🖥️ Frontend (Web Client)
- **Framework:** [React.js](https://reactjs.org/)
  - Reason: Widely used, fast for building dynamic UIs
- **Styling:** [Tailwind CSS](https://tailwindcss.com/)
  - Utility-first, fast to build stylish interfaces
- **Bundler:** [Vite](https://vitejs.dev/)
  - Super fast hot reload, built-in TypeScript support
- **State Management:** `useState`, `useReducer`, maybe [Zustand](https://zustand-demo.pmnd.rs/)
- **UI Components:** Headless UI / Radix / ShadCN (optional)
- **Animations:** Framer Motion (optional, for polished character interactions)
- **Other:**
  - Crypto wallet integration via [RainbowKit](https://www.rainbowkit.com/) + Wagmi
  - Image CDN (e.g., Cloudflare Images or Uploadcare)
  - PWA (Progressive Web App) support for mobile feel

---

## 📱 Platform Targets
- **Primary:** Web
- **Secondary:** Mobile Web (responsive)
- **Optional Later:** Native (via Capacitor, React Native, or Flutter)

---

## 🔌 Backend (Game Logic, APIs, Database)
- **Framework:** [FastAPI (Python)](https://fastapi.tiangolo.com/)
  - Type-hinted Python backend, great for REST APIs
- **Alt:**  %% Node.js + Express or tRPC (if staying JS-only) %%
- **Database:** PostgreSQL
  - Managed (Supabase, %% Neon, or Planetscale for MySQL %%)
- **ORM:** [SQLModel](https://sqlmodel.tiangolo.com/) (FastAPI) or Prisma (Node)
- **Auth:** JWT (via Supabase or custom)
- **AI interaction engine:** Python-based (see AI tools below)

---

## ⛓️ Blockchain Integration
- **Chain:** Polygon / Arbitrum / Immutable X (cheap gas)
- **Wallet:** MetaMask, RainbowKit (optional)
- **NFTs:** ERC-721 or ERC-1155 smart contracts
- **Tokens:** ERC-20 (custom game currency)
- **Smart Contract Language:** Solidity
- **Deployment Tools:** Hardhat or Foundry
- **Backend integration:** Ethers.js + Alchemy/Infura RPC

---

## 🤖 AI / Character Interaction
- **Voice + Text AI:**
  - LLM backend (Gemini 1.5 Flash / dolphin small ones)
  - Fine-tuned character behavior (personas per character)
- **Speech Synthesis (optional):** ElevenLabs / Coqui.ai
- **Chatbot infra:** LangChain or custom logic + prompt engineering
- **Storage for LLM context:** Redis / Pinecone (vector DB) if using memory

---

## 🗃️ File Storage
- **User Assets:** Cloudflare R2 / AWS S3
- **NFT Media:** IPFS via Pinata or NFT.Storage
- **CDN:** Cloudflare or BunnyCDN

---

## 🛠️ Dev Tools
- **Version Control:** Git + GitHub
- **Issue Tracking:** Linear / GitHub Projects
- **Project Management:** Obsidian + Kanban Plugin
- **CI/CD:** GitHub Actions
- **Deployment:** Vercel (Frontend) + Render/Supabase (Backend)
- **Monitoring:** Sentry (frontend/backend error tracking)
- **Logging:** Logtail / BetterStack (or console + basic logs for MVP)

---

## 📦 Dev Environment
- **Languages Used:**
  - JavaScript / TypeScript (Frontend)
  - Python (Backend + AI)
  - Solidity (Smart Contracts)

- **Optional Extensions:**
  - VSCode extensions: Tailwind IntelliSense, Prettier, ESLint, TabNine, GitLens

---

## 🧪 Testing (Minimal at MVP)
- **Frontend Testing:** Playwright (for E2E later)
- **Backend Testing:** Pytest / Supertest
- **Smart Contracts:** Hardhat + Chai/Mocha

---

## 🧠 Note
Focus first on MVP: Web-only, turn-based logic, basic gacha, simple token wallet, basic AI chat.

Later: Full PvP, advanced AI memory, breeding, and collectibles ecosystem.

---

# ✅ First Setup Plan (Sprint 0)
- [ ] Scaffold Vite + React + Tailwind
- [ ] Setup GitHub repo and deploy to Vercel
- [ ] Scaffold FastAPI backend with test `/api/ping`
- [ ] Setup MetaMask + test token on testnet
- [ ] Design DB schema (players, characters, inventory)
- [ ] First gacha logic in backend
- [ ] First AI dialogue prototype
