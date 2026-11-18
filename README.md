### Youcef ADDA · GEODECI - GeoData & Decision Intelligence

**La carte au service de la décision · From geodata to decisions you can defend**

I build GIS tools and data workflows for teams that decide with maps: planning, environment, energy, utilities and networks, local authorities, construction.
The decision comes first. QGIS, PostGIS and Python are how I get there.

**How I work**
- Start from the decision to be made, then trace it back to the data that justifies it.
- Put reusable business rules in the database or in configuration, not in manual steps.
- Make every result reproducible: source, version, date, parameters.
- Use open formats and open tools, so clients can keep going without me.

**Open-source QGIS plugins** (official QGIS repository, QGIS 4 ready)
| Plugin | What it helps you decide or do | Distribution |
|---|---|---|
| [Transformer](https://github.com/yadda07/Transformer) | Prepare controlled, repeatable vector data products: field rules, filters, JSON configs, PostgreSQL publishing | [QGIS Hub](https://plugins.qgis.org/plugins/Transfomer/) · [Source](https://github.com/yadda07/Transformer) |
| [RecoverLand](https://github.com/yadda07/recoverland) | Know who changed what, compare states and restore edits from a local SQLite audit journal | [QGIS Hub](https://plugins.qgis.org/plugins/RecoverLand/) · [Source](https://github.com/yadda07/recoverland) |
| [Log Cleaner](https://github.com/yadda07/log_cleaner) | One-click message log and Python bytecode cache cleanup for plugin developers | [QGIS Hub](https://plugins.qgis.org/plugins/log_cleaner/) · [Source](https://github.com/yadda07/log_cleaner) |

6,244 cumulative downloads on the official QGIS repository as of 23 Oct 2026.

**Field GIS & PostgreSQL engineering**
- [StAir](https://github.com/yadda07/stair) - Local QGIS quality control of aerial FTTH deliverables, no server required.
- [PoleAerien](https://github.com/yadda07/poleaerien) - QGIS quality control and PostGIS sync for aerial network poles (CAP_FT, COMAC, GraceTHD).
- [DQE Chargeur](https://github.com/yadda07/dqe) - Bills of quantities generator (PRO, EXE, PGC) from PostGIS network data with replayable JSON archives.
- [Blackhole](https://github.com/yadda07/blackhole) - Centralized JSONB PostgreSQL audit log (`INSERT`, `UPDATE`, `DELETE`) and point-in-time table recovery.
- [meta_ai_4_postgresql](https://github.com/yadda07/meta_ai_4_postgresql) - Schema-aware natural-language to SQL queries on PostgreSQL.

Much of my tooling was built inside client and employer projects and is not public. Upstream contributor to [opengisch/libqfieldsync](https://github.com/opengisch/libqfieldsync/pull/174).

**Stack:** QGIS · PyQGIS · PostgreSQL/PostGIS · PL/pgSQL · Python · FME

**AI transparency:** I use AI assistants to speed up development. I design, review, test and sign every release; responsibility stays human.

[geodeci.xyz](https://geodeci.xyz) · [contact@geodeci.xyz](mailto:contact@geodeci.xyz)
