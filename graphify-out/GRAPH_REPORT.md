# Graph Report - portfolio  (2026-05-26)

## Corpus Check
- 22 files · ~175,305 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 204 nodes · 337 edges · 23 communities (14 shown, 9 thin omitted)
- Extraction: 97% EXTRACTED · 3% INFERRED · 0% AMBIGUOUS · INFERRED: 9 edges (avg confidence: 0.8)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `45c801c0`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- [[_COMMUNITY_Community 0|Community 0]]
- [[_COMMUNITY_Community 1|Community 1]]
- [[_COMMUNITY_Community 2|Community 2]]
- [[_COMMUNITY_Community 3|Community 3]]
- [[_COMMUNITY_Community 4|Community 4]]
- [[_COMMUNITY_Community 5|Community 5]]
- [[_COMMUNITY_Community 6|Community 6]]
- [[_COMMUNITY_Community 7|Community 7]]
- [[_COMMUNITY_Community 8|Community 8]]
- [[_COMMUNITY_Community 9|Community 9]]
- [[_COMMUNITY_Community 11|Community 11]]
- [[_COMMUNITY_Community 12|Community 12]]
- [[_COMMUNITY_Community 13|Community 13]]
- [[_COMMUNITY_Community 14|Community 14]]
- [[_COMMUNITY_Community 15|Community 15]]
- [[_COMMUNITY_Community 16|Community 16]]
- [[_COMMUNITY_Community 17|Community 17]]
- [[_COMMUNITY_Community 18|Community 18]]
- [[_COMMUNITY_Community 19|Community 19]]
- [[_COMMUNITY_Community 20|Community 20]]
- [[_COMMUNITY_Community 21|Community 21]]

## God Nodes (most connected - your core abstractions)
1. `portfolio Project Context` - 16 edges
2. `Primary App` - 15 edges
3. `TetherClass` - 14 edges
4. `portfolio Architecture` - 14 edges
5. `ya()` - 10 edges
6. `portfolio Workflows` - 10 edges
7. `ga()` - 9 edges
8. `portfolio Coding Rules` - 9 edges
9. `na()` - 8 edges
10. `xa()` - 8 edges

## Surprising Connections (you probably didn't know these)
- `ga()` --calls--> `t()`  [INFERRED]
  _scripts/jquery-3.2.1.min.js → _scripts/bootstrap.min.js
- `ga()` --calls--> `i()`  [INFERRED]
  _scripts/jquery-3.2.1.min.js → _scripts/bootstrap.min.js
- `xa()` --calls--> `i()`  [INFERRED]
  _scripts/jquery-3.2.1.min.js → _scripts/bootstrap.min.js
- `ya()` --calls--> `i()`  [INFERRED]
  _scripts/jquery-3.2.1.min.js → _scripts/bootstrap.min.js
- `ya()` --calls--> `l()`  [INFERRED]
  _scripts/jquery-3.2.1.min.js → _scripts/bootstrap.min.js

## Communities (23 total, 9 thin omitted)

### Community 0 - "Community 0"
Cohesion: 0.47
Nodes (10): e(), h(), i(), l(), n(), o(), r(), s() (+2 more)

### Community 1 - "Community 1"
Cohesion: 0.11
Nodes (48): $(), $a(), Ab(), B(), E(), Ea(), eb(), fa() (+40 more)

### Community 2 - "Community 2"
Cohesion: 0.15
Nodes (16): addOffset(), attachmentToOffset(), autoToFixedAttachment(), MIRROR_LR, MIRROR_TB, now(), OFFSET_MAP, offsetToPx() (+8 more)

### Community 3 - "Community 3"
Cohesion: 0.12
Nodes (16): Business Purpose, Critical Dependencies, Current Architecture Themes, Deployment Model, Environments, Important APIs, Important Databases, Important Queues / Events (+8 more)

### Community 4 - "Community 4"
Cohesion: 0.12
Nodes (15): Critical Workflows, Dangerous Code Paths, Databases Used, Dependencies, Failure Modes, Important Source Files, Inbound APIs, Known Technical Debt (+7 more)

### Community 5 - "Community 5"
Cohesion: 0.13
Nodes (14): Auth Flow, Caching Layers, Deployment Topology, End-to-End Request Flows, Event-Driven Architecture, Failover Behavior, Frontend / Backend Interaction, Observability Architecture (+6 more)

### Community 6 - "Community 6"
Cohesion: 0.18
Nodes (10): Debugging, Deployment, Feature Rollout, Incident Response, Local Development, Migrations, Observability Investigation, portfolio Workflows (+2 more)

### Community 7 - "Community 7"
Cohesion: 0.2
Nodes (9): API Conventions, Architecture Patterns, Database / Migration Patterns, Error Handling / Logging, Naming / Structure, portfolio Coding Rules, State Management, Testing Conventions (+1 more)

### Community 8 - "Community 8"
Cohesion: 0.25
Nodes (7): Main files, portfolio, Resume value, Start here, Status, What this repo does, Why this repo still matters

### Community 9 - "Community 9"
Cohesion: 0.29
Nodes (6): Critical Entrypoints, First Read, How To Start Reasoning, Local Run Baseline, Module Map, portfolio Onboarding

### Community 11 - "Community 11"
Cohesion: 0.5
Nodes (3): Graphify-first repo discovery, portfolio Decision Log, Preserve repo separation

### Community 12 - "Community 12"
Cohesion: 0.5
Nodes (3): Critical Entrypoints, Read First, Top-Level Modules

## Knowledge Gaps
- **84 isolated node(s):** `Why this repo still matters`, `What this repo does`, `Main files`, `Status`, `Resume value` (+79 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **9 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `ya()` connect `Community 1` to `Community 0`?**
  _High betweenness centrality (0.009) - this node is a cross-community bridge._
- **Why does `ga()` connect `Community 1` to `Community 0`?**
  _High betweenness centrality (0.008) - this node is a cross-community bridge._
- **Are the 3 inferred relationships involving `ya()` (e.g. with `i()` and `l()`) actually correct?**
  _`ya()` has 3 INFERRED edges - model-reasoned connections that need verification._
- **What connects `Why this repo still matters`, `What this repo does`, `Main files` to the rest of the system?**
  _84 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Community 1` be split into smaller, more focused modules?**
  _Cohesion score 0.11 - nodes in this community are weakly interconnected._
- **Should `Community 3` be split into smaller, more focused modules?**
  _Cohesion score 0.12 - nodes in this community are weakly interconnected._
- **Should `Community 4` be split into smaller, more focused modules?**
  _Cohesion score 0.12 - nodes in this community are weakly interconnected._