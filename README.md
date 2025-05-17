# Baylag

> *Baylag* — Mongolian for **wealth**.  
> A minimal, offline-first personal finance app built for anyone who wants full control over their money.

Baylag is your local-first, privacy-respecting finance companion.  
No databases. No noise. Just your money, your way—with the power to sync it wherever you go.

---

## ✨ Features (planned)

- **Custom Budgeting** — Flexible categories, smart goals, and monthly limits.
- **Quick Add** — Keyboard-friendly transaction input for rapid logging.
- **Insightful Overview** — See balances, income, expenses, and net worth.
- **Local-First Storage** — Uses IndexedDB to keep your data on your device.
- **Optional Sync** — Encrypted JSON blob syncing without traditional databases.
- **Privacy-First** — Your data is yours. End-to-end encrypted before sync.
- **Import / Export** — Easily migrate or backup your finances.

---

## 📦 Stack (Planned)

- **Frontend**: [Vite](https://vite.dev/), [React](https://react.dev), [ShadCN](https://ui.shadcn.com/) [TailwindCSS](https://tailwindcss.com/)
- **State / Storage**: Legend State + IndexedDB (via `dexie.js` or `idb`)
- **Sync Server**: Supabase (handled by Legend State)
- **Auth (Optional)**: JWT or anonymous device-based sync tokens
- **Deployment**: Vercel (frontend) + Supabase (sync server)

---

## 🛣️ Roadmap

### 📍 Phase 1 — Core MVP
- [ ] Set up Vite + React + ShadCN + Tailwind base
- [ ] IndexedDB setup with Legend State
- [ ] Create transaction schema (amount, category, note, date)
- [ ] Add / Edit / Delete local transactions
- [ ] Overview dashboard (income, expenses, balance)
- [ ] Category management

### 🌐 Phase 2 — Sync & Security
- [ ] Basic sync server (REST or tRPC)
- [ ] Encrypt data before sync
- [ ] Sync blob storage (no DB, just file/blob per user)
- [ ] Manual & auto sync triggers

### 💅 Phase 3 — UX Polish & Power Features
- [ ] Keyboard shortcuts (CMD/CTRL + K, quick add)
- [ ] Export / import JSON
- [ ] Light/dark theme toggle
- [ ] Responsive mobile UI
- [ ] Monthly recap visuals / insights

### 🌍 Phase 4 — Optional Features
- [ ] Multiple devices support
- [ ] Income/expense predictions
- [ ] Recurring transactions
- [ ] Cloud backup toggle

---

## 🧠 Inspiration

This app is for people who:
- Hate bloat and love simplicity
- Want full ownership of their money data
- Switch between devices but don't want vendor lock-in
- Are building wealth from the ground up

---

## 🤝 Contributing

Not open to contributions yet—but feel free to fork or follow development!  
This is a personal project, but if it resonates with enough people, who knows? 🌱

---

## 📄 License

Apache 2.0 — free to use, modify, and distribute with proper attribution.  
See [LICENSE](./LICENSE) for full details.

---

