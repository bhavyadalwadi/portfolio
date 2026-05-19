# Graph Report - portfolio  (2026-05-19)

## Corpus Check
- 4 files · ~173,245 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 90 nodes · 171 edges · 11 communities
- Extraction: 95% EXTRACTED · 5% INFERRED · 0% AMBIGUOUS · INFERRED: 9 edges (avg confidence: 0.8)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- [[_COMMUNITY_Community 0|Community 0]]
- [[_COMMUNITY_Community 2|Community 2]]
- [[_COMMUNITY_Community 3|Community 3]]
- [[_COMMUNITY_Community 4|Community 4]]
- [[_COMMUNITY_Community 5|Community 5]]
- [[_COMMUNITY_Community 6|Community 6]]
- [[_COMMUNITY_Community 7|Community 7]]
- [[_COMMUNITY_Community 8|Community 8]]
- [[_COMMUNITY_Community 9|Community 9]]

## God Nodes (most connected - your core abstractions)
1. `TetherClass` - 13 edges
2. `ya()` - 9 edges
3. `ga()` - 8 edges
4. `na()` - 7 edges
5. `xa()` - 7 edges
6. `t()` - 7 edges
7. `ia()` - 6 edges
8. `oa()` - 6 edges
9. `$a()` - 6 edges
10. `i()` - 6 edges

## Surprising Connections (you probably didn't know these)
- `xa()` --calls--> `i()`  [INFERRED]
  jquery-3.2.1.min.js → bootstrap.min.js
- `fa()` --calls--> `h()`  [INFERRED]
  jquery-3.2.1.min.js → bootstrap.min.js
- `Ea()` --calls--> `r()`  [INFERRED]
  jquery-3.2.1.min.js → bootstrap.min.js
- `ib()` --calls--> `h()`  [INFERRED]
  jquery-3.2.1.min.js → bootstrap.min.js
- `ga()` --calls--> `t()`  [INFERRED]
  jquery-3.2.1.min.js → bootstrap.min.js

## Communities (11 total, 0 thin omitted)

### Community 0 - "Community 0"
Cohesion: 0.23
Nodes (16): e(), h(), i(), l(), n(), o(), r(), s() (+8 more)

### Community 2 - "Community 2"
Cohesion: 0.27
Nodes (3): parseOffset(), TetherClass, within()

### Community 3 - "Community 3"
Cohesion: 0.31
Nodes (10): $a(), B(), Ea(), ja(), ka(), na(), oa(), p() (+2 more)

### Community 4 - "Community 4"
Cohesion: 0.22
Nodes (8): MIRROR_LR, MIRROR_TB, now(), OFFSET_MAP, Tether, tethers, tick(), transformKey

### Community 5 - "Community 5"
Cohesion: 0.33
Nodes (6): E(), M(), va(), wa(), xa(), za()

### Community 6 - "Community 6"
Cohesion: 0.33
Nodes (4): addOffset(), attachmentToOffset(), autoToFixedAttachment(), offsetToPx()

### Community 7 - "Community 7"
Cohesion: 0.4
Nodes (5): ha(), hb(), ia(), ib(), pa()

### Community 8 - "Community 8"
Cohesion: 0.5
Nodes (4): g(), K(), Nb(), qb()

### Community 9 - "Community 9"
Cohesion: 0.67
Nodes (3): fb(), jb(), kb()

## Knowledge Gaps
- **6 isolated node(s):** `transformKey`, `tethers`, `MIRROR_LR`, `MIRROR_TB`, `OFFSET_MAP` (+1 more)
  These have ≤1 connection - possible missing edges or undocumented components.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `TetherClass` connect `Community 2` to `Community 4`, `Community 6`?**
  _High betweenness centrality (0.041) - this node is a cross-community bridge._
- **Why does `ya()` connect `Community 0` to `Community 8`, `Community 1`, `Community 5`?**
  _High betweenness centrality (0.041) - this node is a cross-community bridge._
- **Why does `ga()` connect `Community 0` to `Community 8`, `Community 1`, `Community 3`, `Community 5`?**
  _High betweenness centrality (0.038) - this node is a cross-community bridge._
- **Are the 3 inferred relationships involving `ya()` (e.g. with `i()` and `l()`) actually correct?**
  _`ya()` has 3 INFERRED edges - model-reasoned connections that need verification._
- **Are the 2 inferred relationships involving `ga()` (e.g. with `t()` and `i()`) actually correct?**
  _`ga()` has 2 INFERRED edges - model-reasoned connections that need verification._
- **What connects `transformKey`, `tethers`, `MIRROR_LR` to the rest of the system?**
  _6 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Community 1` be split into smaller, more focused modules?**
  _Cohesion score 0.13 - nodes in this community are weakly interconnected._