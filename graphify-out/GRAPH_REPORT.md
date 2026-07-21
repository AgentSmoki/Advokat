# Graph Report - clones/agentsmoki_advokat  (2026-07-21)

## Corpus Check
- cluster-only mode — file stats not available

## Summary
- 21 nodes · 43 edges · 4 communities
- Extraction: 84% EXTRACTED · 12% INFERRED · 5% AMBIGUOUS · INFERRED: 5 edges (avg confidence: 0.84)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `57ef5377`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- [[_COMMUNITY_Community 0|Community 0]]
- [[_COMMUNITY_Community 1|Community 1]]
- [[_COMMUNITY_Community 2|Community 2]]
- [[_COMMUNITY_Community 3|Community 3]]

## God Nodes (most connected - your core abstractions)
1. `Исследование: судебная практика РФ 2026` - 14 edges
2. `Адвокат — судебный стратег` - 11 edges
3. `Адвокат — судебный стратег (CLAUDE.md)` - 9 edges
4. `Advokat — проект (README)` - 7 edges
5. `Workflow: 7 фаз` - 6 edges
6. `Evidence-Anchored Citation Protocol` - 5 edges
7. `Юрисдикционный профиль: Волгоград` - 4 edges
8. `Раскрытие ИИ (Пленум ВС РФ 2026)` - 4 edges
9. `Проектные выводы для инструкции агента` - 4 edges
10. `memory.md — опыт по делам` - 3 edges

## Surprising Connections (you probably didn't know these)
- `Адвокат — судебный стратег` --references--> `kad.arbitr.ru — картотека арбитражных дел`  [AMBIGUOUS]
  AGENTS.md → research/legal_research_2026.md
- `Адвокат — судебный стратег` --references--> `sudact.ru — база судебных актов`  [AMBIGUOUS]
  AGENTS.md → research/legal_research_2026.md
- `Evidence-Anchored Citation Protocol` --conceptually_related_to--> `Иерархия убедительности источников практики`  [INFERRED]
  AGENTS.md → research/legal_research_2026.md
- `Методология оценки перспектив и позиции по делу` --conceptually_related_to--> `Workflow: 7 фаз`  [INFERRED]
  research/legal_research_2026.md → AGENTS.md
- `Судебная статистика — ориентиры для прогнозов` --conceptually_related_to--> `Workflow: 7 фаз`  [INFERRED]
  research/legal_research_2026.md → AGENTS.md

## Import Cycles
- None detected.

## Communities (4 total, 0 thin omitted)

### Community 0 - "Community 0"
Cohesion: 0.25
Nodes (8): Исследование: судебная практика РФ 2026, Иерархия убедительности источников практики, kad.arbitr.ru — картотека арбитражных дел, ras.arbitr.ru — банк решений арбитражных судов, sudact.ru — база судебных актов, sudrf.ru — ГАС Правосудие, Судебная вертикаль Волгограда, vsrf.ru — Верховный Суд РФ

### Community 1 - "Community 1"
Cohesion: 0.67
Nodes (7): Адвокат — судебный стратег, Evidence-Anchored Citation Protocol, memory.md — опыт по делам, Prompt Caching Discipline, Юрисдикционный профиль: Волгоград, Адвокат — судебный стратег (CLAUDE.md), Advokat — проект (README)

### Community 2 - "Community 2"
Cohesion: 0.67
Nodes (3): Раскрытие ИИ (Пленум ВС РФ 2026), ИИ в российском процессе — контекст 2026, Проектные выводы для инструкции агента

### Community 3 - "Community 3"
Cohesion: 0.67
Nodes (3): Workflow: 7 фаз, Методология оценки перспектив и позиции по делу, Судебная статистика — ориентиры для прогнозов

## Ambiguous Edges - Review These
- `Адвокат — судебный стратег` → `kad.arbitr.ru — картотека арбитражных дел`  [AMBIGUOUS]
  AGENTS.md · relation: references
- `Адвокат — судебный стратег` → `sudact.ru — база судебных актов`  [AMBIGUOUS]
  AGENTS.md · relation: references

## Knowledge Gaps
- **3 isolated node(s):** `vsrf.ru — Верховный Суд РФ`, `ras.arbitr.ru — банк решений арбитражных судов`, `sudrf.ru — ГАС Правосудие`
  These have ≤1 connection - possible missing edges or undocumented components.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **What is the exact relationship between `Адвокат — судебный стратег` and `kad.arbitr.ru — картотека арбитражных дел`?**
  _Edge tagged AMBIGUOUS (relation: references) - confidence is low._
- **What is the exact relationship between `Адвокат — судебный стратег` and `sudact.ru — база судебных актов`?**
  _Edge tagged AMBIGUOUS (relation: references) - confidence is low._
- **Why does `Исследование: судебная практика РФ 2026` connect `Community 0` to `Community 1`, `Community 2`, `Community 3`?**
  _High betweenness centrality (0.552) - this node is a cross-community bridge._
- **Why does `Адвокат — судебный стратег` connect `Community 1` to `Community 0`, `Community 2`, `Community 3`?**
  _High betweenness centrality (0.199) - this node is a cross-community bridge._
- **Why does `Адвокат — судебный стратег (CLAUDE.md)` connect `Community 1` to `Community 0`, `Community 2`, `Community 3`?**
  _High betweenness centrality (0.123) - this node is a cross-community bridge._
- **Are the 2 inferred relationships involving `Workflow: 7 фаз` (e.g. with `Методология оценки перспектив и позиции по делу` and `Судебная статистика — ориентиры для прогнозов`) actually correct?**
  _`Workflow: 7 фаз` has 2 INFERRED edges - model-reasoned connections that need verification._
- **What connects `vsrf.ru — Верховный Суд РФ`, `ras.arbitr.ru — банк решений арбитражных судов`, `sudrf.ru — ГАС Правосудие` to the rest of the system?**
  _3 weakly-connected nodes found - possible documentation gaps or missing edges._