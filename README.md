# My Vibe Coding Portfolio

This repository collects README-style summaries and visual assets for projects I built or rapidly iterated through vibe coding. It is intended as a GitHub portfolio showcase.

This repository only stores public-safe project descriptions, screenshots, architecture notes, feature highlights, and development context. It does not include original source code. For private projects, personal tools, and experimental research tools, each README preserves the original spirit and key value while removing or rewriting paths, deployment details, personal data, credentials, internal information, and source-code references that should not be public.

## Project Summary

| Project | Domain | What it showcases | Key points |
|---|---|---|---|
| [AtomisticStudio](projects/AtomisticStudio/README.md) | Atomistic simulation / computational chemistry | Browser-based ASE research workbench | Structure builder, calculator setup, optimization, MD, electronic/vibration/thermo workflows, SQLite provenance |
| [calOLED](projects/calOLED/README.md) | OLED device characterization | EL + IV data analysis for OLED experiments | EQE, brightness, CCT, PE/CE/LE, calibration snapshots, audit trail, desktop/mobile UI |
| [claude-review-pipeline](projects/claude-review-pipeline/README.md) | AI coding workflow / review automation | Domain-aware iterative review pipeline | Conversational setup, generated domain expert, parallel reviewers, review-fix loop, E2E testing flow |
| [ExpSheet](projects/ExpSheet/README.md) | Semiconductor experiment management | Local-first process and wafer experiment notebook | Chambers, process flows, experiments, image comparison, process-value matrix, JSON storage |
| [MyStocks](projects/MyStocks/README.md) | Personal finance analytics | Local Taiwan stock portfolio manager | SQLite ledger, dashboards, positions, performance metrics, stock drill-down, fake demo-data screenshots |
| [SpectraFit-gamma](projects/SpectraFit-gamma/README.md) | OLED spectrum analysis | Exciton ratio extraction from white OLED EL spectra | Cavity-modified fitting, gamma partition ratio, color science metrics, batch fitting |
| [TADF](projects/TADF/README.md) | Photophysics / OLED materials | TADF intrinsic rate constant calculator | TRPL + PLQY input, three-level model, Phi_Tnr sweep, rate/efficiency envelope |
| [TMM-FBP](projects/TMM-FBP/README.md) | Optical thin-film optimization | Transfer-matrix design and optimization workbench | Multi-target loss functions, analytical gradients, live optimization, result tabs, exportable figures |
| [GoodLabSimulator_aniso](projects/GoodLabSimulator_aniso/README.md) | Planar optics simulation | React + FastAPI modernization of a legacy simulator | Material manager, user sandboxing, nk/PL/DOF libraries, 14 simulation forms, interactive plotting |

## Repository Layout

```text
projects/
  ProjectName/
    README.md
    assets/
```

Each project README is a portfolio-safe rewrite of the original project README and related docs. Images referenced by those README files are copied into the corresponding `assets/` folder and linked with relative paths, so the pages render correctly on GitHub without needing access to the original private project folders.

## Public-Safe Editing Rules

- No original source code is included.
- No private repo URLs, local absolute paths, credentials, API keys, database files, spreadsheets, backups, or runtime data are included.
- Screenshots are kept only when they are already documentation/demo assets or otherwise suitable for public display.
- Operational details are summarized when useful, but deployment commands and machine-specific setup notes are intentionally reduced.
- Project limitations are preserved when they matter for honest positioning, but internal debugging noise is not copied verbatim.

## License

Copyright (c) 2026 Wei-Kai Lee. All rights reserved.

This repository is not open source. The materials are provided for portfolio viewing only, and no permission is granted to copy, modify, distribute, sublicense, sell, publish, or create derivative works without prior written permission.
