# 🧾 Tax Assistant

> AI-assisted tax position management — back-tax relief navigation, transaction-history reconstruction, filing support

<p align="left"><a href="https://drasticstatic.github.io/tax-assistant-public-preview/"><img src="https://img.shields.io/badge/%F0%9F%8C%90%20Public%20Preview-Configured-brightgreen" alt="Public Preview"></a> <a href="https://github.com/open-condo-software/gitexporter"><img src="https://img.shields.io/badge/Synced%20via-GitExporter-blue" alt="Synced via GitExporter"></a> <a href="https://code.claude.com/docs/en/overview"><img src="https://img.shields.io/badge/Built%20with-Claude%20Code%20CLI-blueviolet" alt="Built with Claude Code CLI"></a> <a href="https://github.com/drasticstatic/tax-assistant/actions/workflows/sync-public.yml"><img src="https://github.com/drasticstatic/tax-assistant/actions/workflows/sync-public.yml/badge.svg" alt="Sync"></a></p>

---

**🌐 [Explore the Public Preview →](https://drasticstatic.github.io/tax-assistant-public-preview/)**

---

> 🔒 Public mirror notice: This repository is partially mirrored as a public preview of the private source via an automated sync pipeline, matching the pattern used by [`divorce-custody-assistant`](https://drasticstatic.github.io/divorce-custody-assistant-public-preview/). The public mirror stays minimal until content is explicitly reviewed and allowlisted for export — see the Public preview boundary section below.

## What this project is for

This repo tracks Christopher's federal (and applicable state) tax position: back-tax debt originating from early retirement-account liquidations used as survival capital during a period of separation, ongoing navigation of IRS relief programs (currently **Currently Not Collectible / CNC** status), and the historical reconstruction of stock and cryptocurrency transaction history needed to file accurate returns and pursue further relief.

It grew out of work that started inside `trading-assistant` — understanding the tax implications of stock and crypto positions — and was split into its own repo so tax-specific work (relief-program research, filing prep, transaction-history reconstruction) has its own space, separate from trading-strategy work, while still staying closely linked to it.

Planned/ongoing capabilities:

- transaction-history reconstruction across exchanges, DeFi protocols, and prop-firm accounts (via CoinLedger and manual review)
- IRS relief-program tracking and strategy (CNC → Offer in Compromise, penalty abatement, installment agreements)
- filing support — Form 433-A preparation, back-tax return reconciliation
- a public-safe methodology writeup, eventually, for anyone navigating a similar situation (early-withdrawal tax debt from financial hardship, crypto/DeFi transaction reconstruction) — no account-level detail, ever

## Current status

**Early / in-progress** — repo scaffolding just established (2026-08-21); real content follows as reconstruction and relief-program work continues.

## Public preview boundary

Same allowlist model as `divorce-custody-assistant`: private-by-default, new root paths must be explicitly classified before they can export.

- `holdings/`, `correspondence/`, and `filings/` are never public — they hold account-linked position data, IRS/state correspondence, and draft/filed return material.
- The public mirror (`tax-assistant-public-preview`), once anything is published there, will hold structure and methodology only — never account numbers, SSN/EIN, specific dollar figures tied to a live matter, or anything that could assist someone else in impersonating Christopher to a tax authority.

## Agent roles

Built and maintained with **Anthropic's Claude** (Claude Code CLI).

**Fortuna** leads this work — she started it inside `trading-assistant` to understand the tax implications of stock and crypto positions, and continues leading relief-program strategy and transaction-history reconstruction here.

**Alfred** handles repo scaffolding, sync-pipeline setup, and cross-repo coordination.

## A note on approach

This repo's operating posture is full legal compliance pursued through legitimate IRS relief channels — CNC, Offer in Compromise, penalty abatement, installment agreements — not tax-protester or "sovereign citizen" theory. That material gets flagged and set aside wherever it surfaces, not incorporated into strategy. The goal is genuine resolution, approached honestly.

---

*Companion repos in this ecosystem: [Divorce & Custody Assistant](https://drasticstatic.github.io/divorce-custody-assistant-public-preview/) · [Trading Assistant](https://drasticstatic.github.io/trading-assistant-public-preview/) (see its live [Tax Tracker](https://drasticstatic.github.io/trading-assistant-public-preview/data/tax/tax.html))*
