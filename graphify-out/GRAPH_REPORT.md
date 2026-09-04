# Graph Report - .  (2026-09-04)

## Corpus Check
- cluster-only mode — file stats not available

## Summary
- 22 nodes · 25 edges · 3 communities
- Extraction: 96% EXTRACTED · 4% INFERRED · 0% AMBIGUOUS · INFERRED: 1 edges (avg confidence: 0.9)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `e3a8e1bc`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- [[_COMMUNITY_Community 0|Community 0]]
- [[_COMMUNITY_Community 1|Community 1]]
- [[_COMMUNITY_Community 2|Community 2]]

## God Nodes (most connected - your core abstractions)
1. `Tax Assistant Repository` - 8 edges
2. `render_page()` - 5 edges
3. `render_section()` - 4 edges
4. `split_repeatable()` - 3 edges
5. `read_csv()` - 2 edges
6. `group_by_section()` - 2 edges
7. `render_field()` - 2 edges
8. `main()` - 2 edges
9. `Tax Assistant Public Preview` - 2 edges
10. `IRS Form 433-F` - 2 edges

## Surprising Connections (you probably didn't know these)
- `Form 433-F Fill-In Framework (Example)` --references--> `IRS Form 433-F`  [EXTRACTED]
  433f-framework-example.html → filings/source-docs-local/IRS-Form433-F.pdf
- `Fortuna (AI Agent)` --implements--> `Tax Assistant Repository`  [EXTRACTED]
  CLAUDE.md → README.md
- `Alfred (AI Agent)` --implements--> `Tax Assistant Repository`  [EXTRACTED]
  CLAUDE.md → README.md
- `Tax Assistant Repository` --references--> `Currently Not Collectible (CNC) Status`  [EXTRACTED]
  README.md → PENDING-TASKS.md
- `Tax Assistant Repository` --references--> `Offer in Compromise (OIC)`  [EXTRACTED]
  README.md → PENDING-TASKS.md

## Communities (3 total, 0 thin omitted)

### Community 0 - "Community 0"
Cohesion: 0.2
Nodes (10): Alfred (AI Agent), Currently Not Collectible (CNC) Status, Divorce & Custody Assistant Repository, Fortuna (AI Agent), Offer in Compromise (OIC), Penalty Abatement, Sync Public Preview Workflow, Tax Assistant Public Preview (+2 more)

### Community 1 - "Community 1"
Cohesion: 0.39
Nodes (8): group_by_section(), main(), For repeatable sections, group field_keys sharing a numeric index     (e.g. bank, read_csv(), render_field(), render_page(), render_section(), split_repeatable()

### Community 2 - "Community 2"
Cohesion: 0.67
Nodes (3): Form 433-F Call Prep Walkthrough, Form 433-F Fill-In Framework (Example), IRS Form 433-F

## Knowledge Gaps
- **11 isolated node(s):** `For repeatable sections, group field_keys sharing a numeric index     (e.g. bank`, `Trading Assistant Repository`, `Divorce & Custody Assistant Repository`, `Fortuna (AI Agent)`, `Alfred (AI Agent)` (+6 more)
  These have ≤1 connection - possible missing edges or undocumented components.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **What connects `For repeatable sections, group field_keys sharing a numeric index     (e.g. bank`, `Trading Assistant Repository`, `Divorce & Custody Assistant Repository` to the rest of the system?**
  _11 weakly-connected nodes found - possible documentation gaps or missing edges._