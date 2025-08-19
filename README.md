
# Σxpend – Immutable Expense Tracker

Σxpend is a **crypto-native expense tracker** that combines **wallet-based transaction fetching**, **AI-powered classification**, and **immutable storage on Irys**. The goal is to give users **financial clarity** while ensuring their logs are **permanent, transparent, and tamper-proof**.

---

## 🚀 Vision

A lightweight, fun, and polished tool that helps people:

- Track their crypto & DeFi expenses
    
- Store immutable logs for accountability
    
- Gain insights into their financial habits
    
- Stay engaged with gamification & rewards
    

---

## 🛠️ Core Tech Stack

- **Frontend**: React (Next.js) + TailwindCSS + shadcn/ui
    
- **Wallets**: MetaMask / WalletConnect
    
- **Blockchain Access**: Infura (Metamask Developer) + Etherscan API
    
- **Immutable Storage**: Irys (permanent receipts & logs)
    
- **Backend**: Serverless functions (Vercel)
    
- **Database (optional)**: Local memory / IndexedDB (user-only), no central DB for privacy
    

---

## 📦 Development Roadmap (Phases 0–5)

### **Phase 0 – Setup & Foundation**

**Goal:** Prepare the project structure.

- Initialize Next.js + TailwindCSS + shadcn/ui
    
- Set up Infura provider & wallet connection
    
- Add basic routing + sidebar layout
    
- Dark/light mode theming
    

✅ Outcome: Boilerplate ready, clean UI shell.

---

### **Phase 1 – MVP Core**

**Goal:** Build the simplest usable expense tracker.

- Connect wallet (MetaMask / WalletConnect)
    
- Fetch wallet balance (via Infura)
    
- Fetch past transactions (via Etherscan API)
    
- Classify transactions (send/receive/swap)
    
- Store immutable expense log on Irys
    

✅ Outcome: Wallet → Transactions → Immutable Record.

---

### **Phase 2 – Insights & Analytics**

**Goal:** Add clarity & visualization.

- Categorize expenses (tokens, gas fees, DeFi activity)
    
- Dashboard with charts & spending summaries
    
- Monthly/weekly breakdowns
    
- Export logs as CSV/JSON
    

✅ Outcome: Σxpend moves from raw data → insights.

---

### **Phase 3 – Scale & Pro Tools**

**Goal:** Make the app useful for power users.

- Multi-wallet support
    
- Support for multiple chains (ETH, Polygon, Arbitrum, etc.)
    
- Custom tagging of transactions
    
- Search + filter history
    
- Downloadable immutable proof receipts
    

✅ Outcome: Professional-grade expense tracking.

---

### **Phase 4 – Irys Deep Integration**

**Goal:** Treat Irys as a core feature.

- Immutable transaction logs (per session/month)
    
- Shareable expense proofs (verifiable links)
    
- Timestamped receipts for compliance/accountability
    
- Optional auto-upload of categorized reports
    

✅ Outcome: Proof-first expense tracker.

---

### **Phase 5 – Polish & Gamification**

**Goal:** Improve usability + engagement.

- Gamified rewards (badges, NFT milestones)
    
- Privacy Mode (local-only analysis, optional Irys proofing)
    
- Mobile PWA support (installable, offline-first)
    
- UI polish (themes, animations, refinements)
    

✅ Outcome: Σxpend feels **premium, fun, and polished**.

---

## 🎨 UI & Design System

- **Color Scheme:** Dark base with cyan highlights (`#51FFD6`), neutral grays, optional playful accents
    
- **Font Stack:** Inter (UI clarity), Space Grotesk (headings/numbers), fallback to system sans
    
- **Components:** Cards, progress bars, charts, tag filters
    
- **Layout:** Responsive sidebar + dashboard grid
    
- **Style:** Minimal, spacious, modern
    

---

## 🔌 Data Flow Overview

1. **Wallet Connect** → User authenticates with MetaMask/WalletConnect
    
2. **Fetch Data** → Infura (live state) + Etherscan API (historical txns)
    
3. **Classify Transactions** → Categorization rules + optional AI
    
4. **Immutable Storage** → Push logs/receipts to Irys
    
5. **UI Visualization** → Dashboard, charts, breakdowns
    
6. **Export/Share** → CSV, JSON, or Irys proof link
    

---

## ✅ Quick Recap

- **MVP = Wallet → Fetch Txns → Classify → Immutable Logs**
    
- **Phase 2–5 = add insights, scale, pro tools, and polish**
    
- **Irys = permanent proof layer**, core differentiator
    

Σxpend = **crypto expense tracking with permanence + clarity**.
