# The expense ledger

*Every tool, service and machine the work runs on. Prices are list prices with the date read, or blank until read; the business share is Christopher's call on each row, and a CPA decides what the return says. Started 2026-11-04 from SOP-ARB-008 (the tech stack, an inventory of the iMac read 2026-11-03), the round-six proposals, `/Applications` as listed on 2026-11-04, and Christopher's own list. Add rows; never erase one, mark it ended. The rules each row is read against are in [IRS-NOTES.md](IRS-NOTES.md).*

## How to read a row

| Column | Means |
|---|---|
| **Kind** | subscription (recurring), one-time (bought once), service (usage-billed), free (no charge at the tier in use), open source (no charge, ever, by licence), hardware (lasts more than a year: usually depreciated or expensed under section 179 or the de minimis safe harbor, a CPA's call) |
| **Business share** | 100% (only the work uses it), mixed (split; the personal part is not deductible), personal, or **?** (not decided) |
| **Owner** | who paid and who owns it: Christopher, or a foundation if it bought the thing (then it is their asset, not his expense; proposal 016) |
| **Receipt** | where the proof lives (email, App Store, a statement); private paths are named by folder only |
| **Christopher to fill** | only he knows the plan or the price; the row stands so the gap is visible, not hidden |

A row at **$0** is still a row: the point of the ledger is that nothing the work runs on is missing from it, and a free tool that becomes paid, or that another person would have to buy, is found here first.

## Software and services

### The fleet and its engines

| Item | What it does for the work | Kind | Price (read on) | Billing | Business share | Since | Receipt | Note |
|---|---|---|---|---|---|---|---|---|
| GitHub (Free today; **Pro proposed**) | every repository, every lane, every public page, GitHub Pages and the Actions minutes that render the PDFs and run the public-lane sync; Pro adds rules on private repos | subscription | $0 → $4/month (GitHub's upgrade prompt, 2026-11-04; verify on the billing page). Pricing page the same day: Free $0, Team $4 per user per month, Enterprise $21 | monthly | 100% | 2024 | GitHub billing emails | [001-github-pro.md](001-github-pro.md) |
| Claude (Anthropic) | the fleet's engine: Alfred, Fortuna, Mystarch, the workflows; Claude Code CLI 2.1.317 on 2026-11-03 | subscription | plan and price: Christopher to fill | monthly | ? (the fleet is the work; some personal use) | 2026 | Anthropic billing | usage limits hit twice on Nov 4 |
| Littlebird 0.87.7 | the observer: screen context, fleet memory, meeting notes; also the `littlebird` MCP server | subscription | Christopher to fill | monthly | ? | 2026 | Littlebird billing | |
| Firecrawl | web capture for the fleet; the `firecrawl` MCP server | subscription | plan: Christopher to fill; credits reset 2026-11-12 | monthly | 100% | 2026 | Firecrawl billing | out of credits this week |
| Harness Cosmos (formerly Augment Cosmos) | cloud agents | planned; no active subscription | $0 now; price when subscribed: Christopher to fill | | 100% | planned | | Harness bought select Augment assets on 2026-10-08 (SOP-ARB-008) |
| Augment Intent 0.5.0 / Auggie CLI | Kavanah's old seat; the app is still installed, the `auggie` MCP server does not connect | ended | $0 now | | | | | keep the row: history |
| 21st-dev (MCP server) | *UI components*, by its name; not authenticated on 2026-11-03 | not in use | $0 as it stands; paid plans exist: Christopher to fill if one is taken | | ? | | | reconnect or drop it (SOP-ARB-008, yours to do) |
| rtk 0.29.0 | a proxy to cut agents' token use (its own description) | installed via Homebrew | $0 as installed; licence not checked | | 100% | 2026 | | use not checked |
| ntfy | phone alerts for the desks (SOP-ARB-005) | free tier | $0 | | 100% | 2026 | | a paid tier exists if volume grows |
| shields.io badges, GitHub Pages | the badges on every page; the public twins' hosting | free | $0 | | 100% | | | |

### Development tools

| Item | What it does for the work | Kind | Price (read on) | Billing | Business share | Since | Receipt | Note |
|---|---|---|---|---|---|---|---|---|
| Visual Studio Code 1.99.3 | the main editor | free | $0 | | 100% | | | runs from `~/Downloads`; move it to `/Applications` (SOP-ARB-008) |
| Sublime Text (build 4215) | a second editor | evaluation or licence | a paid licence exists for continued use: Christopher to fill whether one was bought | one-time | 100% | | | lives in `~/Downloads` |
| Xcode 16.4 | Apple's tools and compilers | free with a Mac | $0 | | 100% | | | |
| Terminal, Safari, Keynote, Numbers, Pages, GarageBand, iMovie | Apple's own apps on the iMac; Numbers and Pages opened this month | free with a Mac | $0 | | mixed | | | Numbers and Pages are where tables and letters get drafted |
| GitHub Desktop 3.6.5 | a picture of git for people | free | $0 | | 100% | | | not checked |
| Docker Desktop 4.66.1 (Docker 29.3.1) | containers; carries its own Linux VM | free at Docker's Personal tier for individuals and small businesses (Docker's own subscription terms; verify on its pricing page on the day) | $0 | | 100% | | | engine off at the Nov 3 sample |
| Homebrew 7.0.11 | installs the command-line tools below | open source | $0 | | 100% | | | |
| Node (v20 through v24 via nvm), npm 10.9.9, pnpm 10.33.0, corepack | the bot, the dashboard, the PDF renderer, mermaid-cli, md-to-pdf | open source | $0 | | 100% | | | |
| Python 3.14.3, uv 0.11.2 | scripts and the public-lane tripwire | open source | $0 | | 100% | | | |
| Rust 1.98.1 | builds | open source | $0 | | 100% | | | not checked |
| Hardhat 2.24.2, solc (five cached compilers) | the DEX bot's contracts | open source | $0 | | 100% | 2025 | | five compilers need Rosetta (SOP-ARB-006) |
| git 2.39.5 (Apple), gh 2.103.3, git-filter-repo 2.47.0 | version control; the public-lane sync | open source | $0 | | 100% | | | |
| ggshield 1.49.0, pre-commit 4.2.0 | catch a secret before it is committed | free tier (GitGuardian) and open source | $0; GitGuardian's paid tiers exist: Christopher to fill if one is taken | | 100% | | | hooks vary by repo |
| poppler 26.04.0, pngquant 3.0.3 | PDF text and image helpers; the tripwire reads PDFs with pdftotext | open source | $0 | | 100% | | | |
| gcloud CLI 587.0.0 | Google Cloud from the command line | free CLI; cloud usage is billed per project | $0 for the CLI; any project's usage: Christopher to fill | monthly if any | ? | | Google Cloud billing, if any | not checked |
| googleworkspace-cli (gws) 0.22.5 | Google Workspace from the command line | free CLI | $0 | | ? | | | the Workspace plan itself is a row below |
| ngrok 3.36.1 | tunnels | free tier; paid plans exist | $0 as far as known: Christopher to fill if a plan is held | monthly if any | 100% | | | not checked |
| Rosetta, FileVault, Time Machine, launchd, Universal Control | Apple's translation layer, disk encryption, backup, scheduled agents, shared keyboard | free with macOS | $0 | | mixed | | | no Time Machine destination is configured today (SOP-ARB-006) |
| OpenCore Legacy Patcher | keeps the 2014 MacBook Pro on a current macOS | open source | $0 | | mixed | | | unsupported by Apple |
| VMware Fusion Pro | Windows and Linux on the Macs (proposal 013) | free for all use since Nov 11, 2024 (VMware, read 2026-11-03) | $0 | | 100% | planned | | needs a Broadcom account; not installed |
| Parallels Desktop | used in the past; proposal 013's first choice if its test passes | ended; may return | Christopher to fill if revived | yearly | 100% | | | not installed |
| Windows 11 (guest licence) | Windows-only trading tools, when one is named | planned | Christopher to fill; Microsoft requires "a unique license... for each instance" (proposal 013) | one-time per VM | 100% | planned | | the licence question is step 4 of 013's test |
| Autodesk Fusion 2603.1.15 | design and machining software in `~/Applications`; no part of the work | personal-use licence as far as known | Christopher to fill if a paid plan | | personal | | | the name trap: nothing to do with VMware Fusion |

### Trading

| Item | What it does for the work | Kind | Price (read on) | Billing | Business share | Since | Receipt | Note |
|---|---|---|---|---|---|---|---|---|
| TradingView 3.5.0 | charts and alerts for the trading desks; the `tradingview` and `tv-alerts` MCP servers read it | subscription | plan: Christopher to fill | monthly or yearly | ? (trading is the work) | | TradingView billing | a trader's data and charting tool is a classic "ordinary" cost in that trade; a CPA confirms |
| Tradovate Trader 3.260904.0 (platform, data, routing); the `tradovate` MCP server | futures | service | fees per statement | monthly | ? | | broker statements (private lane) | Intel only, needs Rosetta; gone at macOS 28 |
| Robinhood; the `robinhood` MCP server | stocks and options; market reads for the fleet | service | $0 to hold; fees and interest per statement | per statement | ? | | broker statements (private lane) | |
| Prop-firm evaluations and resets (TakeProfitTrader, TopOne, MyFundedPerps); the `myfundedperps` MCP server | the funded-account path | one-time per evaluation | per receipt | per event | ? | 2026 | `data/imports` in trading-assistant (redacted receipts, public on purpose) | whether an evaluation fee is a deductible trading expense or a personal cost is exactly the kind of question for a CPA |
| TradeCopia (as Christopher named it; product and fee to verify) | copy-trading | subscription | Christopher to fill | | ? | | | verify the product's exact name and what it is before the row stands |
| TradeZella to STB 1.3 | an Automator helper for trade records; exact job unverified | the lab's own script | $0 | | 100% | | | if a TradeZella subscription sits behind it, that is its own row: Christopher to fill |
| Hummingbot; the `hummingbot-mcp` server | market-making bot; clones and an MCP server exist | open source | $0 | | 100% | | | not checked |
| Exchange and network fees (BTCC, DEXes, gas) | the crypto and DEX work | service | per trade | per trade | ? | | exchange exports (private lane) | fees are usually part of cost basis or trading expense; a CPA decides |
| RPC provider (Alchemy) | the chain reads behind the DEX edge monitor | free tier as far as known | $0; Christopher to confirm the plan | monthly if any | 100% | 2026 | | the VPN resolver drops it now and then (SOP-ARB-002) |
| The DEX edge monitor | this lab's own code: three launchd agents on the iMac | the lab's own | $0 | | 100% | 2026 | | monitor-only; funding gated on the edge study |
| `astra-native-main`, `astra-native-service` (MCP servers) | purpose unverified | not checked | $0 as far as known | | ? | | | named in the trading-assistant project |
| Two MCP servers named for an organisation's domain | an organisation's tools, not this ledger's | not this ledger's | | | | | | counted in SOP-ARB-008, not named |

### Communications

| Item | What it does for the work | Kind | Price (read on) | Billing | Business share | Since | Receipt | Note |
|---|---|---|---|---|---|---|---|---|
| Discord 0.0.420 | the fleet's rooms and the organisations' servers | free | $0 | | mixed | | | |
| Discord Nitro | the main Discord account's upgrade | subscription | Christopher to fill | monthly | mixed (fleet rooms and personal) | | | |
| Telegram 13.0, WhatsApp 26.38.74 | people and alerts | free | $0 | | mixed | | | Telegram Premium, if held, is its own row: Christopher to fill |
| Slack 4.52.178 | work rooms | free tier unless a workspace is paid | $0 as far as known: Christopher to fill if a workspace is paid | | ? | | | |
| Zoom 7.1.9 | calls | free tier unless a plan is held | $0 as far as known: Christopher to fill if a plan is held | | ? | | | |
| Keet 2.5.2 | peer-to-peer calls | free | $0 | | ? | | | not checked |
| Google Workspace / Business (if any) | mail and documents | subscription | Christopher to fill | | ? | | | THEF's own plan is Kenney's, not this ledger's |
| Notion 7.40.0 | notes and pages | free Personal plan unless upgraded | $0 as far as known: Christopher to fill if a paid plan | | ? | | | open at the Nov 3 sample |
| Mobile carrier plan (the iPhone's line) | the phone the desks ring; the hotspot when Starlink drops | subscription | Christopher to fill | monthly | mixed | | carrier billing | a phone plan's business share is a split (Publication 334) |
| Starlink | the connection the monitors and sessions run on | subscription | Christopher to fill | monthly | mixed | | Starlink billing | the business share of a home connection is a split, like a phone |

### Security, backup and storage

| Item | What it does for the work | Kind | Price (read on) | Billing | Business share | Since | Receipt | Note |
|---|---|---|---|---|---|---|---|---|
| 1Password 8.12.42 (and 1Password for Safari) | the vault: credentials, the Apple recovery key | subscription | Christopher to fill | yearly | mixed | | 1Password billing | load-bearing since Nov 4 (SOP-COM-002) |
| NordVPN 10.12.0 | the VPN the desks run behind (SOP-ARB-002 has its resolver trouble) | subscription | Christopher to fill | yearly or multi-year | mixed | | NordVPN billing | Christopher named "Nord" on Nov 4 |
| Intego: VirusBarrier 10.9.101, NetBarrier 10.9.38, ContentBarrier 10.9.28, NetUpdate 10.9.38, Washing Machine 10.9.27 | antivirus, firewall, content filter, updates, cleanup on the iMac | subscription | Christopher to fill | yearly | mixed | | Intego billing | NetBarrier's firewall extension is active |
| Intego Personal Backup 10.9.29 | Intego's own backup, part of the same bundle | included above | $0 beyond the bundle | | mixed | | | whether any job is set up in it is unverified; its use was declined in 015 |
| iCloud+ (2 TB) | the git-safety bundles, phone backup, shared folders | subscription | $9.99/month (Apple's US price; verify on the day) | monthly | mixed | | Apple receipts | the 710 MB of bundles is a sliver of it |
| AppleCare (if any) | cover for the iMac or the iPhone | subscription or one-time | Christopher to fill if held | | mixed | | Apple receipts | |

### Sites, names and everyday apps

| Item | What it does for the work | Kind | Price (read on) | Billing | Business share | Since | Receipt | Note |
|---|---|---|---|---|---|---|---|---|
| Wix | the earlier venture's site, still up | subscription | Christopher to fill | yearly | ? (a prior business; personal unless revived) | | | |
| Domains | names for the sites | subscription | per domain | yearly | ? | | registrar emails | list each domain in its own row when known |
| Brave 155, Firefox 144, Google Chrome 156 | browsers; Chrome is also the engine the local PDF renderer uses | free | $0 | | mixed | | | |
| Spotify 1.3.4 | music | subscription | Christopher to fill | monthly | personal | | | not the work's |
| Capital One Shopping, PayPal Honey, Desktop Verse, Memory Diag | browser helpers, a verse on the desktop, a memory checker | free as far as the inventory shows | $0 | | personal | | | listed so `/Applications` has no gap |
| DappU coursework | the Web3 engineering training behind the dappu/ repos | one-time | Christopher to fill | | ? | 2025–2026 | | education that maintains or improves skills in a present trade is a recognised category; a new trade is not; a CPA draws the line |

## Hardware

| Item | What it does for the work | Kind | Price | Owner | Business share | Since | Note |
|---|---|---|---|---|---|---|---|
| iMac 24" (M4, 32 GB, 2 TB) | the workstation everything runs on today (SOP-ARB-006); macOS 15.4.1 on 2026-11-03 | hardware | Christopher to fill | Christopher | mixed | 2025 | depreciation or section 179 or de minimis, by price: a CPA's call |
| MacBook Pro 2014 (Intel) | the second screen and call machine (proposal 012); a patched macOS | hardware | long since paid | Christopher | mixed | 2014 | battery and OS work planned (012) |
| iPhone 14 Pro Max (1 TB) | alerts, ntfy, the phone the desks ring | hardware | Christopher to fill | Christopher | mixed | | |
| iPad Pro | named in SOP-ARB-008 beside the three Macs; its part in the work: Christopher to say | hardware | Christopher to fill | Christopher | ? | | Universal Control caps at three devices |
| Mac Studio M5 Max (64 GB / 1 TB, the lean) | the foundation's workhorse | hardware | $3,799 (Apple, read 2026-11-03; proposal 018) | **THEF, if it buys** | not Christopher's expense if so | planned | a financed machine is the buyer's asset (016) |
| ASUS ProArt PA27JCV 5K | the Studio's display | hardware | $544.95–$569.95 used (B&H, 2026-11-03) | THEF, if it buys | as above | planned | |
| WD My Passport Ultra 6 TB | Time Machine for three Macs (proposal 019) | hardware | $179.99 (2026-11-03, verify at checkout) | THEF or Christopher | ? | planned | under the de minimis amount either way |
| Secretlab MAGNUS Evo desk, TITAN Evo XL chair | the desk the workstation sits on (proposal 014) | hardware | $749 / verify XL | Christopher unless offered | ? | wished | 014 says: outside THEF's ask unless they offer |
| UPS (proposal 015) | keeps the monitors up through a dip | hardware | per 015's table | ? | ? | planned | |
| Starlink dish and router | the connection's hardware | hardware | Christopher to fill (bought or leased with the plan) | Christopher | mixed | | |
| Nebra outdoor miner (Helium) | a past DePIN experiment | hardware | paid | Christopher | ended | | the frontier had its pilgrims (011 addendum) |

## The home office (a CPA question, recorded for when it is asked)

The simplified method is $5 per square foot of space used "regularly and exclusively" for the trade, up to 300 square feet (Publication 334, 2025). The regular method (Form 8829) would instead take a share of the home's actual costs, electricity among them; the workstation runs all day, so that share is real but unmeasured: Christopher to fill if the regular method is ever weighed. The desk's corner would have to be measured and used only for the work. Nothing is claimed by this page; it only keeps the facts ready.

## What it would take to replace Christopher

*The honest account Christopher asked for on Nov 4: the seats, subscriptions and machines another person would need to run the same desks for the organisations this lab serves through its tech work. The ledger above is the detail; this is the sum, by desk. Where a price says "Christopher to fill", the sum does too.*

| Desk | What another person would need | Seats and subscriptions | Machines | Monthly, where known (read 2026-11-04) |
|---|---|---|---|---|
| **The fleet** (Alfred, Fortuna, Mystarch; every public page and sync) | a Claude seat, a GitHub account with Pro, Littlebird, Firecrawl, a secrets scanner | Claude (Christopher to fill), GitHub Pro $4, Littlebird (fill), Firecrawl (fill), GitGuardian free tier | the workstation below | $4 + three plans to fill |
| **The trading desks** (futures, stocks, prop firms, copy-trading) | a charting seat, a futures platform with data, a brokerage, the evaluations as they come | TradingView (fill), Tradovate data and routing (per statement), Robinhood ($0 to hold), prop-firm evaluations (per event), TradeCopia (fill) | the workstation; a second screen | per statement and per event; two plans to fill |
| **The Web3 desk** (the DEX edge monitor, the dappu repos) | an RPC provider, the open-source toolchain, the coursework behind it | Alchemy (free tier as known), Hardhat and Node $0, DappU (fill, one-time) | the workstation, running all day | $0 known; the coursework one-time |
| **The organisations' tech work** (THEF, PIR, O-R-G, Psanctuary, the Church, Taylor'd, the heal site) | the same GitHub account, their reading rooms (free), Google Workspace where one is held, Discord | GitHub (above), Workspace (fill, if any), Discord Nitro (fill) | the workstation | included above; two to fill |
| **Communications** | phone line, connection, VPN, the rooms | mobile carrier (fill), Starlink (fill), NordVPN (fill), Slack and Zoom free tiers | the iPhone | three plans to fill |
| **Security and backup** | a password vault, endpoint protection, a backup destination, cloud storage | 1Password (fill), Intego (fill), iCloud+ $9.99 | a Time Machine drive ($179.99, proposal 019) | $9.99 + two plans to fill |
| **The workstation itself** | an Apple-silicon Mac with 32 GB or more, a phone, a second machine for calls and the Intel tools | macOS and its tools $0 | iMac M4 (fill), MacBook Pro 2014 (paid), iPhone 14 Pro Max (fill); or the Mac Studio at $3,799 if THEF buys | hardware, once; a CPA decides how it is recovered |
| **The hours** | the part no subscription replaces: the days at the desks, the nights the monitors are watched, the reading behind every page | | | Christopher to fill; the ledger counts tools, and this line is the reason the tools are counted |

**Known monthly subscriptions today, from the rows with a price:** GitHub Pro $4 (proposed) + iCloud+ $9.99 = **$13.99**, with every other plan still "Christopher to fill". That gap is the next thing this page closes; see below.

## What to add next

- The exact plans and prices for Claude, Littlebird, Firecrawl, TradingView, Starlink, the mobile carrier, Intego, 1Password, NordVPN, Wix, Nitro, Spotify.
- Each domain as a row.
- The receipts' folders, named by folder only.
- A yearly "read on" refresh of every price, and the ended rows marked.
- The hours, however Christopher chooses to count them.

*Not tax advice. Kept so the truth is cheap to tell.*
