# 🐾 Bark To Earn

**Bark To Earn** is a Farcaster-integrated mini dApp built on **Base Mainnet** that allows users to "bark" (interact) and earn ERC20 rewards ($BARK tokens).  
It’s a fun, community-driven web3 mini app inspired by the *Boop to Earn* concept, rebuilt with Base chain compatibility and improved UI/UX.

---

## 🌐 Live App

🔗 **Website:** [https://bark-to-earn.vercel.app](https://bark-to-earn.vercel.app)  
🧭 **Network:** Base Mainnet  
💰 **Token:** BARK (ERC20)  
📄 **Contracts:**
- **BarkToken:** `0xYOUR_BARK_TOKEN_ADDRESS`
- **BarkToEarn:** `0xYOUR_BARK_TO_EARN_CONTRACT`

---

## ⚙️ Tech Stack

- **Frontend:** HTML + CSS + Vanilla JS  
- **Blockchain SDK:** [wagmi/core](https://wagmi.sh/core), [farcaster/miniapp-sdk](https://github.com/farcasterxyz/miniapp-sdk)  
- **Chain:** Base Mainnet  
- **Hosting:** [Vercel](https://vercel.com)

---

## 🧱 Project Structure

bark-to-earn/
├── index.html # Main app frontend
├── contract.json # Deployed BarkToEarn ABI + address
├── token.json # BarkToken info (symbol, decimals, address)
├── barklogo.png # Main dog logo
├── image.png # Frame preview image
├── splash.png # Miniapp splash image
└── .well-known/
└── farcaster.json # Miniapp metadata for Farcaster verification

🧠 Troubleshooting
Issue	Cause	Fix
🐶 Image not showing	Farcaster sandbox blocks local path	Use full URL (https://bark-to-earn.vercel.app/barklogo.png)
❌ Execution Reverted	No tokens in contract	Send BARK tokens to contract
⏸️ Paused	Contract paused	Call unpause()
⚠️ Limit reached	Daily barks exceeded	Wait 24h or call setBarksPerDay()
0 reward	Range misconfigured	Call setBarkAmountRange(min, max)

💡 Future Upgrades
🏆 Leaderboard for top barkers

🔔 Daily streak bonuses

🎨 On-chain profile badges

🐕 NFT collectibles for frequent barkers

🧾 License
MIT License © 2025
Built by monu with ❤️ on Base Network.

