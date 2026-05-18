# Scholarly Knowledge Graph (SKG) Ontology

Ontology for the [SKG Data Pipeline](https://github.com/duyhxm/skg-data-pipeline) — a thesis on constructing Scholarly Knowledge Graphs from NeurIPS publications.

## Contents

| Module | Type | Description |
|--------|------|-------------|
| [`core/`](https://duyhxm.github.io/skg-ontology/core/) | TBox | Source-agnostic core: papers, authors, venues, ML tasks/datasets/methods |
| [`neurips/`](https://duyhxm.github.io/skg-ontology/neurips/) | TBox | NeurIPS-specific extension terms |
| [`seed/`](https://github.com/duyhxm/skg-ontology/blob/main/seed/skg-neurips-seed.ttl) | ABox | Seed instances for NeurIPS identifier scheme |
| [`external/`](https://github.com/duyhxm/skg-ontology) | SHACL | Shape constraints for validation |

## Namespaces

| Prefix | URI |
|--------|-----|
| `skg:` | `https://duyhxm.github.io/skg-ontology/core#` |
| `skg-neurips:` | `https://duyhxm.github.io/skg-ontology/neurips#` |
| `skgr:` | `https://duyhxm.github.io/skg-ontology/resource/core/` |
| `skgr-neurips:` | `https://duyhxm.github.io/skg-ontology/resource/neurips/` |

## Loading Order

1. `skg-core.ttl`
2. `skg-neurips-extension.ttl` (imports core)
3. `skg-neurips-seed.ttl` (imports extension)

## View Online

- **Web:** https://duyhxm.github.io/skg-ontology/
- **Core docs:** https://duyhxm.github.io/skg-ontology/core/
- **NeurIPS docs:** https://duyhxm.github.io/skg-ontology/neurips/
- **Raw TTL:** `core.ttl`, `neurips.ttl`, `seed/skg-neurips-seed.ttl`

## License

[Creative Commons Attribution 4.0](https://creativecommons.org/licenses/by/4.0/)
