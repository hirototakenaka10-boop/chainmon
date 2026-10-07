# ChainMon

_小学生でも遊べる、Solana上の血統が刻まれるモンスター収集RPG_

## Summary

A friendly turn-based monster-catching RPG where each monster is a compressed NFT on Solana, with simple catch/battle/level-up loops designed for kids. Game state (HP, level, moves) lives on-chain so progress is provably owned and tradeable, while the game client stays simple and colorful like classic Pokemon.

## Target users

Elementary school kids and families new to crypto, casual RPG fans

## Problem

Kids love Pokemon-style games but existing web3 games are too complex, text-heavy or finance-focused for young players.

## Solution

Build a simple, colorful catch-battle-level RPG where blockchain ownership is invisible until the child wants to see/trade their monsters.

## MVP features

- Wild monster encounters with simple catch mini-game (tap/swipe)
- Turn-based battle system with 4 basic moves per monster
- On-chain monster stats stored via Anchor program, minted as compressed NFTs
- Simple town/map exploration with 2-3 zones for MVP
- Leveling system that updates on-chain metadata after battles

## Chains

Solana

## Tech

Anchor, Rust, Metaplex Bubblegum (cNFTs), Phaser.js or Unity WebGL, Solana Web3.js, Devnet

## Category

Gaming

## Why now

Compressed NFTs make minting thousands of cheap monster assets on Solana finally affordable for a kid-friendly game economy.

## Roadmap

- Add PvP battles between players' monster teams
- Introduce breeding/evolution mechanics with on-chain randomness
- Launch mobile-friendly client and onboarding flow with custodial wallets for kids
