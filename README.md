# CYPHER

**Programmable audio infrastructure for generative music, adaptive sound, UGC, gaming, GTM, distribution, and creator systems.**

CYPHER is an open, provider-neutral protocol for turning **intent, events, musical structure, timelines, rights constraints, and platform requirements** into reproducible audio control plans and derivatives.

It is not a film-score tool and it is not owned by a single application. A film cue, adaptive game soundtrack, 15-second campaign hook, UGC remix kit, OTT bumper, branded sonic signature, radio sequence, or creator soundtrack can all consume the same primitives.

> Everybody gets a turn on the signal.

## Why CYPHER

Hip-hop's cypher is a shared context where participants listen, respond, transform, build, and pass the signal forward. CYPHER applies that logic to programmable audio systems.

```text
INTENT / EVENT / SIGNAL
          |
        CYPHER
          |
  COMPOSE / ADAPT / REMIX
          |
  +-------+--------+--------+--------+
  |       |        |        |        |
33.3FM  GAMING    UGC      GTM   CREATOR / OTT
  |       |        |        |        |
  +-------+--------+--------+--------+
                  |
             DISTRIBUTION
```

## Architecture

CYPHER is **Layer-1 public infrastructure** within the Agentropolis three-layer model.

- **Infrastructure:** CYPHER protocol, MCP surface, schemas, compilers, interchange utilities.
- **Districts / institutions:** 33.3FM, Gaming District, GTM and other domain institutions define their own domain law and consume CYPHER capabilities.
- **Applications:** creator tools, games, OTT apps, UGC products, campaigns and other surfaces consume those capabilities.

CYPHER does **not** make 33.3FM, Gaming, GTM, Distribution, or CREATOR subordinate to one another. It provides shared programmable-audio primitives beneath them.

## Initial capability families

```text
audio.cypher.compose
audio.cypher.validate
audio.cypher.compile

audio.cypher.motif.transform
audio.cypher.harmony.transform
audio.cypher.rhythm.transform
audio.cypher.tempo.map
audio.cypher.orchestration.map

audio.cypher.event.bind
audio.cypher.state.compile
audio.cypher.transition.compile
audio.cypher.hitpoint.sync

audio.cypher.game.package
audio.cypher.gtm.variant
audio.cypher.gtm.package
audio.cypher.ugc.remix_plan
audio.cypher.ugc.package
audio.cypher.distribution.package
audio.cypher.brand.signature

audio.cypher.export.midi
audio.cypher.export.musicxml
audio.cypher.export.osc
audio.cypher.render.plan
audio.cypher.compare
audio.cypher.provenance.receipt
```

## What CYPHER can drive

- **Music creation:** generative composition, songs, motifs, harmony/rhythm transforms, orchestration, score/soundtrack planning, procedural/live-coded music.
- **Gaming:** adaptive music states, combat/exploration transitions, leitmotifs, stingers, event-driven layers.
- **GTM:** short campaign variants, sonic branding, hooks, stingers, rights-aware derivative plans.
- **UGC:** approved stem packs, remix kits, creator challenges, bounded key/tempo/arrangement transforms.
- **Distribution:** platform versions and OTT/web/mobile/social/retail packaging with provenance handoff.
- **Creator / film / television:** score/soundtrack structure, timecode sync, cue graphs, trailer/bumper music, episodic motif continuity.

## Music-as-code adapters

CYPHER is provider-neutral and may interoperate with Strudel, TidalCycles, SuperCollider, ChucK, Csound, Sonic Pi, MIDI, MusicXML, and OSC. These are adapters, not hard dependencies.

## AI audio renderers

CYPHER describes and validates **render plans**. It does not require a single generation vendor. Consuming runtimes may route those plans to rights-cleared local or hosted AI-audio providers according to their own licensing, rights, privacy, policy, and budget rules.

Provider credentials never belong in CYPHER documents or this repository.

## Public / private boundary

This repository is intentionally public.

### Public

Protocol schemas, MCP tools, deterministic composition contracts, validators and compilers, MIDI/MusicXML/OSC interchange, provider-neutral render plans, reference implementations, tests, synthetic examples, and provenance receipt formats.

### Never commit here

API keys, private Agentropolis routing, unreleased music or stems, client catalogs, private rights agreements, confidential campaign data, private lore motifs, festival production state, or customer/listener data.

## Reproducibility law

The same normalized input, schema version, compiler version, deterministic seed, and bounded stochastic rules should regenerate the same **structural composition plan**.

Rendered audio may vary across model versions or providers. The musical law, event bindings, rights constraints, and provenance trail remain versioned and inspectable.

## Relationship to 33.3FM

33.3FM is a music institution and a major CYPHER consumer. It can use CYPHER for creator composition, SCORE LAB round trips, soundtrack generation, remix kits, sonic branding, release variants, and future 33.3FM Labs workflows.

CYPHER remains broader than 33.3FM so Gaming, GTM, UGC, Distribution, CREATOR, OTT and future systems can share the same protocol.

## License

Apache License 2.0. See [`LICENSE`](LICENSE).

---

**CYPHER — programmable rhythm for systems that listen and respond.**
