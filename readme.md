# 🕵️ Hide & Seek Online

A real-time multiplayer Hide & Seek game playable in any browser. Play against bots or challenge friends from anywhere in the world!

---

## 🎮 How to Play

### vs Bots
1. Enter your name
2. Click **🤖 vs Bots**
3. Pick your role, number of bots, and difficulty
4. Click **Start**

### Online Multiplayer
1. Get a free Ably API key at [ably.com](https://ably.com)
2. Enter your name and click **🌍 Online**
3. Paste your Ably key and save it (only needed once)
4. **Host** a room and share the 4-letter code with friends, or **Join** with a code

---

## 🕹️ Controls

| Action | Keyboard | Mobile |
|--------|----------|--------|
| Move | WASD or Arrow Keys | On-screen D-Pad |

---

## 🌟 Features

- 🌍 Real-time online multiplayer via Ably
- 🤖 Bots mode — no account needed
- 👁️ Seeker vision cone with line-of-sight
- 🌿 Bushes to hide in (block vision too)
- 🏆 Win tracking & persistent leaderboard
- 👟 Shoe shop — spend wins to go faster
- 💬 In-game chat with automatic filter
- 🛡️ Admin panel (owner only)
- ⏱️ 100 second rounds with 5 second countdown

---

## 🛡️ Admin Panel (Owner Only)

The admin panel is accessible only to the owner. Features include:
- Ban / temp ban / unban players
- Grant or revoke admin to other players
- Toggle invisibility mid-game
- Swap role mid-game
- Chat commands via `/command`

### Chat Commands
| Command | Description |
|---------|-------------|
| `/ban [name]` | Permanently ban a player |
| `/tempban [name] [mins]` | Temp ban for X minutes |
| `/unban [name]` | Unban a player |
| `/grant [name]` | Give admin to a player |
| `/revoke [name]` | Remove admin from a player |
| `/invisible` | Toggle invisibility |
| `/role` | Swap your role |
| `/wins [amount]` | Add wins to yourself |
| `/help` | List all commands |

---

## 🚀 Getting Started (Self-hosting)

1. Download `index.html`
2. Upload to any static hosting (e.g. GitHub Pages)
3. Visit your URL and play!

### GitHub Pages Setup
1. Create a new public repository
2. Upload `index.html`
3. Go to **Settings → Pages → Source → main**
4. Your game will be live at `https://yourusername.github.io/repositoryname/`

---

## 🔑 Ably API Key

This game uses [Ably](https://ably.com) for real-time online multiplayer.
- Sign up for free at ably.com
- Free tier includes 6 million messages/month
- No credit card required

---

## 📜 Chat Rules

The chat has an automatic filter. Violations result in:
- **1st offence** — message removed, warning
- **2nd offence** — 15 minute temp ban
- **3rd offence** — permanent ban

---

Made by **oji the champ** 👑
