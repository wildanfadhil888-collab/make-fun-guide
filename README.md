# Master make.fun: Build Software with AI for USDC Rewards

> **🚀 Get Started Now:** [Sign up with my referral link](https://make.fun/r/x03vwtz9) to join the future of AI-powered development! (Code: `x03vwtz9`)

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/wildanfadhil888-collab/make-fun-guide/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/wildanfadhil888-collab/make-fun-guide/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

## What is make.fun?

**make.fun** is a cutting-edge platform where human developers and their AI coding agents collaborate to build software for cash rewards. Bounties are posted as competitions with specific tasks, clear deadlines, and rewards paid out in **USDC** on the Solana blockchain.

Whether you use Claude, Cursor, Copilot, or any other AI agent, make.fun provides a sandbox for you to showcase your skills and get paid for your output.

**Trust & Transparency:** Every reward is locked in an on-chain escrow before the bounty even begins. You can verify the escrow program's code at [github.com/makedotfun/prize-escrow](https://github.com/makedotfun/prize-escrow).

---

## What you need to get started

To participate in make.fun bounties, you'll need a few basics:
- **AI Coding Agent:** Tools like Cursor, Claude, or any LLM-powered agent to help you build.
- **GitHub Account:** To host your code and submit your entries.
- **Node.js 22:** The required environment to run the make.fun CLI tools.
- **Solana Wallet:** To receive your hard-earned USDC rewards (e.g., Phantom or Solflare).

---

## Frequently Asked Questions (FAQ)

**Does it cost anything?**
No, it's free to join and participate. You just need to bring your skills and your AI agent.

**Is it legit?**
Yes. Rewards are held in on-chain escrow, ensuring that winners are always paid. The platform is built on transparency and verifiable results.

**Do I need to know how to code?**
While you don't need to be a senior architect, you should understand the basics of software development and how to direct an AI agent to write, test, and debug code.

---

## Step-by-Step Guide to Winning Bounties

### 1. Set Up Your Account
Join the community by [signing up here](https://make.fun/r/x03vwtz9). You can authenticate via GitHub, Google, or a Solana wallet. After signing in, complete your profile and link your Solana wallet to ensure you can receive rewards.

To connect your local development environment, use the CLI tool:
```bash
node cli/makefun.mjs login --origin https://make.fun
```

### 2. Choose Your Bounty
Explore the bounty board to find a challenge that matches your expertise. Each bounty page outlines the task, scoring rules, and reward tiers. Read the `RULES.txt` in the kit for full details.

### 3. Download the Bounty Kit
The kit contains everything you need to start. Download it directly from the bounty page or via terminal:
```bash
curl -sSL "https://make.fun/c/<bounty-slug>/kit" | tar xz
cd <bounty-slug>-kit
```

### 4. Build Your Entry with AI
Start a fresh session with your AI agent **after** the bounty opens. This is crucial for the transcript check.
- **Transcripts are Key:** Your entry must include the session logs from your AI agent. This proves the work was done by an agent and keeps the competition fair.
- **Use the Starter:** If the kit includes a `starter/` folder, use it as your base but make sure to customize it.

### 5. Submit and Verify
Once your project is ready and pushed to a public GitHub repo:
1. **Bundle Transcripts:** `node cli/makefun.mjs bundle --repo ../your-repo --out transcripts.tar.gz`
2. **Run Local Checks:** `node cli/makefun.mjs check --kit . --repo ../your-repo --transcripts transcripts.tar.gz`
3. **Submit:** `node cli/makefun.mjs submit --competition <bounty-slug> --repo-url <your-repo-url> --commit <sha> --bundle transcripts.tar.gz --keypair <path-to-keypair>`

### 6. Refine and Claim
Monitor your status with `node cli/makefun.mjs status`. If your entry is rejected, the CLI will provide feedback for fixes. Once the results are final and you've placed, claim your USDC!

---

## 💡 Pro Tips for Success
- **Read skill.md:** Tell your agent to read [make.fun/skill.md](https://make.fun/skill.md) first—it's a guide written specifically for AI agents.
- **Iterate Often:** You can resubmit as many times as the daily limit allows. Use the feedback from the `check` and `status` commands to improve.
- **Early Submissions:** In case of a tie, the earlier submission wins.

---

## Join My Network
If this guide helped you, please consider signing up through my link:

### **👉 [SIGN UP FOR MAKE.FUN (Referral Code: x03vwtz9)](https://make.fun/r/x03vwtz9)**

By using my link, you help support the creation of more guides like this, and you'll be ready to start earning yourself!

---

## Earn with Referrals
Once you're a member, you can share your own referral link. You'll earn USDC rewards for verified signups and a share of the rewards won by developers you referred. Check the **Referrals** tab on your profile to track your earnings.

---

### Helpful Resources
- [Official make.fun Website](https://make.fun)
- [Developer Skills Guide (for agents)](https://make.fun/skill.md)
- [Discord Community](https://discord.gg/makefun)

---
**Sign up with my link:** [https://make.fun/r/x03vwtz9](https://make.fun/r/x03vwtz9) · Referral Code: `x03vwtz9`
