<div align="center">

<img src="../assets/icons/sprout.svg" width="56" height="56" alt="">

# The business, kept honestly

*A live catalogue of what the work runs on and what it costs, kept in the open so the record is ready the day the breakers flip.*

![Kind](https://img.shields.io/badge/Kind-ledger-2962ff?style=flat-square)
![Since](https://img.shields.io/badge/Since-2026--11--04-8a6a2a?style=flat-square)
![For](https://img.shields.io/badge/For-Christopher%2C_a_CPA%2C_and_anyone_doing_the_same-64748b?style=flat-square)

</div>

## <img src="../assets/icons/compass.svg" width="24" height="24" alt=""> TL;DR

1. **What this folder is.** A running list of the software, services and hardware the trading, Web3 and fleet work runs on, with what each costs and whether it is a business cost, a personal one, or a mix. It is kept in the public twin on purpose: an honest trail that shows anyone doing the same work what a sincere record looks like.
2. **Why before there is an LLC.** A person who carries on "a trade or business as a sole proprietor" files Schedule C whether or not a company exists; the IRS's test for a deductible expense is that it is "ordinary and necessary" for that trade, and a cost that is partly personal must be split. Keeping the ledger now means the day the business gets its own name and employer identification number, nothing has to be reconstructed.
3. **What this folder is not.** Tax advice. Every row says "a CPA decides". The private working files, filings and correspondence stay in the private lanes of this repository and never travel.

## <img src="../assets/icons/footprints.svg" width="24" height="24" alt=""> The pages

| Page | What it holds |
|---|---|
| [EXPENSE-LEDGER.md](EXPENSE-LEDGER.md) | every tool, service and machine, its price, its billing, the business share (Christopher's call), where the receipt lives |
| [001-github-pro.md](001-github-pro.md) | the first proposal written against the ledger: GitHub Pro, $4 a month, what it buys and why now |
| [IRS-NOTES.md](IRS-NOTES.md) | every IRS fact the ledger leans on, quoted with its page and the day it was read, and what we intend: an honest ledger, the existing balance resolved in good standing |
| [pdf/](pdf/) | each page above rendered to PDF on every push to `main` (`EXPENSE-LEDGER.pdf`, `IRS-NOTES.pdf`, `001-github-pro.pdf`, `README.pdf`), in the Labs tone, for a CPA's desk or a printed folder |

## <img src="../assets/icons/globe.svg" width="24" height="24" alt=""> The reading room

The public twin at <https://drasticstatic.github.io/tax-assistant-public-preview/> carries these pages and their PDFs (rendered as pages at [github.com/drasticstatic/tax-assistant-public-preview/tree/main/business](https://github.com/drasticstatic/tax-assistant-public-preview/tree/main/business)), so a CPA, a partner organisation or a stranger in the same place can read them without an account: the folder `business/` travels on the public lane as it stands, every file read by the lane's tripwire before it publishes. The PDFs are rendered by the repository's own workflow (`.github/workflows/pdf.yml`; the local twin is `scripts/render-pdfs.sh`) in the drasticstatic lab's tone from the fleet's register, electric blue on navy (`2962ff` / `1a1a2e` / `0f3460` / `e8f1ff`, TONES.md in my-template). What never travels: the filings, correspondence and holdings lanes, and any amount tied to a live matter.

**Legal:** the entity, filings and counsel folders live in the private repository [`drasticstatic/legal`](https://github.com/drasticstatic/legal) ("drasticstatic (trading as a business): legal"). Questions for a CPA are drafted against this ledger and land in its `counsel/` folder; its README points back here.

## <img src="../assets/icons/users-round.svg" width="24" height="24" alt=""> The IRS pages this leans on (read 2026-11-04)

The short form; [IRS-NOTES.md](IRS-NOTES.md) holds every fact, quoted, with its page and date.

- *Publication 334, Tax Guide for Small Business (2025)*: "ordinary" is "common and accepted in your field"; "necessary" is "helpful and appropriate", not indispensable; a partly personal expense must be separated; equipment "expected to last more than a year" is generally not deducted whole in the year bought, except through section 179 or the de minimis safe harbor ("up to $2,500 per item or invoice" without an applicable financial statement); the simplified home-office method is "$5 by the area" used "regularly and exclusively", "limited to 300 square feet"; self-employment tax applies from $400 of net earnings. <https://www.irs.gov/publications/p334>
- *Get an employer identification number*: free, online, one per responsible party per day; "Beware of websites that charge for an EIN". A sole proprietor may have one. <https://www.irs.gov/businesses/small-businesses-self-employed/get-an-employer-identification-number>
- *Start-up costs* (IRS Tax Tip 2021-166, marked historical): costs to create or investigate a business, deductible if the business could deduct them once running; the rest recovered over 180 months from the month it opens. <https://www.irs.gov/newsroom/heres-how-businesses-can-deduct-startup-costs-from-their-federal-taxes>
- *Guide to business expense resources*: Publication 535 was discontinued after 2022; Publications 334, 587 (home) and 463 (travel, car) replace it. <https://www.irs.gov/businesses/small-businesses-self-employed/deducting-business-expenses>

*A prior venture, a sole proprietorship in live-sound production, was wound down because it felt as if it cost more to be a business than to serve people. This ledger is the opposite bet: keep the record light and honest from the first day, so being a business costs nothing but the truth.*
