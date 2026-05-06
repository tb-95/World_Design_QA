# World Design QA – Open World Environment Audit

## Project Overview
This repository contains a **systematic QA analysis** of an open‑world map environment. The audit focuses on visual consistency, level design logic, and environmental asset placement. It serves as a portfolio piece for **Game QA** or **Level Design Validation** roles.

## Repository Structure
World_Design_QA/
├── Map_Analysis/ # Original map PDF
│ └── World_Design_QA.pdf
├── Report/
│ ├── Bug_report_World_Design_Bednar.pdf
│ └── screenshots/ # Visual evidence (optional)
├── bugs/ # Per‑location detailed reports
│ ├── greece.md
│ ├── finland.md
│ ├── sweden.md
│ ├── construction_site.md
│ ├── road_guard.md
│ ├── urban_area.md
│ ├── missing_area.md
│ ├── main_street.md
│ ├── roundabout.md
│ ├── bridge.md
│ ├── bus_stop.md
│ └── general_store.md
└── README.md

text

## Bug Report Summary
A full audit of **48 individual issues** across 12 map segments, classified by type (missing elements, glitched textures, logical errors).

| Page | Location | Key Issue | Type |
|------|----------|-----------|------|
| 1 | Store entrance | Missing crosswalk, car through asphalt | Missing + visual |
| 2 | Greece | Wrong way sign backwards, road to nowhere | Logical + map |
| 3 | Road guard | Signs on wrong side of guardrail | Placement |
| 4 | Finland | Yield sign upside down | Logical |
| 5 | Sweden | Wrong language on sign | Localization |
| 6 | Construction | Trees on active site | Asset logic |
| 7 | Urban area | Buildings glitched, half‑submerged | Mesh/geometry |
| 8 | Missing area | Entire segment off map | Map boundary |
| 9 | Main street | Missing yield sign, dealer off map | Gameplay + map |
| 10 | Roundabout | Missing signs, incomplete on map | Map + signage |
| 11 | Bridge | Pole on road, rock/water mixed | Placement + texture |
| 12 | Bus stop | Pedestrian in traffic-only zone | Logic |

## Methodology
- Manual visual inspection of every map segment
- Priority classification: Critical (game-breaking), Major (gameplay obstruction), Minor (cosmetic)
- Structured bug reporting ready for Jira or other trackers

## Why This Project?
This audit demonstrates:
- Ability to read maps/levels like a tester
- Detecting inconsistency in assets, signage, and world logic
- Structured reporting across multiple environments (urban, rural, construction)

## Author
**Tomáš Bednář**   
[GitHub Profile](https://github.com/tb-95)
