# ChainMon
![ChainMon logo](assets/logo.png)

小学生でも遊べる、Solana上の血統が刻まれるモンスター収集RPG

## Overview
ChainMon is a friendly, turn-based monster-catching RPG built for kids. Every monster is a compressed NFT on Solana, and game state like HP, level, and moves lives on-chain, so progress is provably owned and tradeable. The game client itself stays simple and colorful, in the spirit of classic Pokemon games, so young players never need to think about wallets or gas fees to have fun.

## Problem
Kids love Pokemon-style games, but existing web3 games are usually too complex, text-heavy, or finance-focused for young players. Wallet setup, gas fees, and trading jargon get in the way of simple, joyful play.

## Solution
ChainMon builds a simple catch-battle-level RPG loop where blockchain ownership is invisible by default. Kids tap to catch monsters, pick moves to battle, and watch their monsters level up. Ownership and trading features are there for families who want them, but hidden until needed.

## Features (MVP)
- Wild monster encounters with a simple catch mini-game (tap/swipe)
- Turn-based battle system with 4 basic moves per monster
- On-chain monster stats stored via an Anchor program, minted as compressed NFTs
- Simple town/map exploration across 2-3 zones for the MVP
- Leveling system that updates on-chain metadata after battles

## Tech Stack
- Anchor, Rust (on-chain program)
- Metaplex Bubblegum (compressed NFTs)
- Phaser.js or Unity WebGL (game client)
- Solana Web3.js
- Solana Devnet

## How It Works
Players explore a small map, encounter wild monsters, and catch them with a quick tap/swipe mini-game. Caught monsters are minted as compressed NFTs on Solana via Metaplex Bubblegum. Battles are turn-based with 4 moves per monster, resolved client-side. After each battle, level and stat changes are written on-chain through the Anchor program.

```
[Game Client (Phaser.js / Unity WebGL)]
        |
        v
[Solana Web3.js] <----> [Anchor Program on Solana Devnet]
        |                         |
        v                         v
[Wallet/Session]          [Compressed NFTs via Bubblegum]
                           (monster stats: HP, level, moves)
```

## Roadmap
- Add PvP battles between players' monster teams
- Introduce breeding/evolution mechanics with on-chain randomness
- Launch mobile-friendly client and onboarding flow with custodial wallets for kids

## Pitch
See our full pitch deck at [docs/pitch.pdf](docs/pitch.pdf) and the spoken pitch script at [docs/pitch-script.md](docs/pitch-script.md).

## Team
- Name / Role (placeholder)
- Name / Role (placeholder)
- Name / Role (placeholder)

Built for the Colosseum hackathon (Solana and other chains).

---

🎬 Pitch video: [docs/pitch-video.mp4](docs/pitch-video.mp4)


## Prototype

Live prototype: https://hirototakenaka10-boop.github.io/chainmon/

The source is [docs/index.html](docs/index.html) (served with GitHub Pages from the /docs folder). All data is simulated.

🎥 Demo video: [docs/demo-video.mp4](docs/demo-video.mp4)
