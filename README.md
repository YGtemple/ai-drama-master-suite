<div align="right">

**[English](README.md)** · [简体中文](README.zh-CN.md)

</div>

# ai-drama-master-suite

A production pipeline for AI short drama — `SKILL.md` defines the method, `cases/` shows it applied to four films.

<sub>125 KB `SKILL.md` · four production records</sub>

---

## What this is

Not a "one-click short drama generator". A **constraint system** — contracts, assertions and checklists that hold the non-determinism of generation inside an acceptable range.

```
SKILL.md          the method, 125 KB
references/       topic-specific reference material
cases/            four films, start to finish
```

Method and evidence sit together on purpose. Read the rule, then read what happened when it was applied.

## What the method covers

| Stage | Content |
|---|---|
| Script | three-layer structure (story / metaphor / intent), setup→payoff object list |
| Assets | cross-age face anchoring, prop state splitting, material exclusion |
| Storyboard | four camera parameters, four-part vocal direction, axis rules |
| Video | first-frame vs character reference separation, per-segment sign-off, scrapped-take archiving |

## The four cases

Each is worth reading for a specific reason.

### 反话 — a soul-companion story

The **prop continuity table** is the part to look at. A single eraser runs across ten scenes through eight states — lent, gifted, filed alongside its old twin, pressed under a thermos, dropped, accumulated, worn to a stub, reset. Marked *must not skip*.

Prop drift is one of the first things generation gets wrong, and one of the hardest to notice before the cut.

### 国家的孩子 — documentary reconstruction

35 frames classified into six shot scales, percentages computed, and the narrative centre derived from the distribution: close-ups and near shots total 43%, therefore the asset cards must specify facial detail — high-altitude flush, skin texture, wrinkle depth — in full.

Every claim carries a frame number, so a later check can return to the evidence.

### 一会儿 — first-person dog

A report that turns a subjective disagreement into a **pronoun table**. Two rounds of feedback looked contradictory until the real issue was named: the sentence did not say who performs the action, so the reader attached "I" to the boy visible on screen.

A writing fault, not a wrong choice of viewpoint. The table then fixes each pronoun to one referent for the whole film.

### 凝视的接力 — generational gaze

25 classic films × 5 narrative techniques, as an index. One evaluation dimension is **AI feasibility** — a direction can score high for reach and low for feasibility because scaffolding at height is a high-risk frame for generation.

A good idea that cannot be rendered is still zero.

## Practices that recur across the cases

| Practice | Problem it solves |
|---|---|
| Main anchor + repeated bone structure across ages | face drift |
| Fixed seed, low stylise/weird/chaos | cross-shot inconsistency |
| ASCII plan view + axis rules | crossing the line, spatial confusion |
| Prop continuity table tracing every state change | props mutating between cuts |
| "Do not rebuild the room" repeated per group | the same place looking different each time |
| Material exclusion ("not stone") | white objects rendered as marble |
| Four-part vocal direction | voice drifting across shots |
| One pronoun table for the whole film | ambiguity causing rework |
| Film × technique matrix | no starting point when hunting for references |
| Version correction log | the same mistake made twice |

## Standing position

Two sentences appear across the documents and mean the same thing:

> Not fully automatic. Storyboard and character consistency still need human sign-off — an end-to-end run fails at exactly those two steps, and the rework costs more than checking by hand.

> The next one only after the user approves.

## Related

- [Profile](https://github.com/YGtemple) — all projects
- [ai-film-production (archived)](https://github.com/YGtemple/ai-film-production)
- [ai-drama-asset-prompts (archived)](https://github.com/YGtemple/ai-drama-asset-prompts)

## License

MIT
