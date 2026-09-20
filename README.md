# token-launch-tracker

I needed a simple terminal tool to track newly launched Web3 game tokens and liquidity pools without keeping fifty browser tabs open. This tool polls DexScreener's public API to monitor price action, volume spikes, and liquidity changes for specific tokens or gaming-related tickers.

It runs entirely in the terminal, saves your watchlist locally, and alerts you when liquidity is pulled or volume surges.

## Installation

Clone the repository and install the dependencies. Works on Windows.

```cmd
pip install -r requirements.txt
```

## How to run

To search and add a token to your watchlist:

```cmd
python tracker.py add --chain solana --query "SUPER"
```

To view the live dashboard of watched tokens:

```cmd
python tracker.py view
```

To clear your watchlist:

```cmd
python tracker.py clear
```

<!-- updated: 2026-09-20 -->
