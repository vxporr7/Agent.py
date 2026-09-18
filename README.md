# Agent.py
AI trading bot that I made.
# Solana Trading Bot

a python-based algorithmic trading bot for solana tokens. it finds new coins early, decides when to enter, and manages exits with tiered profit targets.

## features

- early entry detection for coins under 30 minutes old
- market cap filter from $8k to $1M
- exit strategy with three take-profit levels (TP1, TP2, TP3)
- chart-based holding decisions
- data from GMGN (primary), with Axiom and DEX Screener as fallbacks
- 15+ modular python files

## planned work

- ml model to predict short-term chart trends and plug it into the bot

## tech

python, solana, REST/market data APIs

## status

work in progress
