# ChainSight 🔍 - DeFi Threat Intelligence Platform

## Overview
Real-time monitoring system detecting DeFi attacks using:
- Somnia's reactive blockchain triggers
- 0G Labs' AI inference modules
- On-chain anomaly pattern recognition

## Features
- Customizable alert tiers (SMS/Discord/on-chain)
- Attack simulation playground

## Installation
```bash
# Frontend
git clone https://github.com/GauravKarakoti/chainsight
yarn install && yarn start

# Smart Contracts (Somnia)
forge install --no-commit somnia-network/core
forge build
```

## Usage
1. Connect wallet to dashboard
2. Select protocols to monitor
3. Set risk thresholds (60+ = high risk)
4. Receive real-time threat alerts
