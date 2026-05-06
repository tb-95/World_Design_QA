# World Design QA – Complete Bug Report

**Systematic validation of an open‑world map environment.**  
This document contains all 48 identified issues across 12 pages of the original PDF, organized by location with severity, priority, and detailed descriptions.

---

## Page 01 – General Store / Entrance

**Source:** PDF page 1

| ID | Severity | Priority | Description |
|----|----------|----------|-------------|
| GS‑01 | Medium | P2 | Missing store logo |
| GS‑02 | Major | P1 | Missing crosswalk |
| GS‑03 | Medium | P2 | Missing parking signs |
| GS‑04 | Major | P1 | Car bugged through asphalt |

### Detailed Descriptions

**GS‑01: Missing store logo**  
- *Expected:* Store logo displayed on building or sign.  
- *Actual:* No logo present.  
- *Impact:* Branding inconsistency.

**GS‑02: Missing crosswalk**  
- *Expected:* Crosswalk marked for pedestrians near entrance.  
- *Actual:* None.  
- *Impact:* Pedestrian safety logic broken.

**GS‑03: Missing parking signs**  
- *Expected:* Parking regulation signs visible.  
- *Actual:* Absent.  
- *Impact:* Player has no guidance on parking rules.

**GS‑04: Car bugged through asphalt**  
- *Expected:* Car fully above ground.  
- *Actual:* Car partially clipped into asphalt.  
- *Impact:* Visual glitch, immersion break.

---

## Page 02 – Greece

**Source:** PDF page 2

| ID | Severity | Priority | Description |
|----|----------|----------|-------------|
| GR‑01 | Major | P1 | Missing full lane |
| GR‑02 | Major | P1 | No crosswalk while turning left |
| GR‑03 | Critical | P0 | "Wrong way" sign facing opposite direction |
| GR‑04 | Major | P1 | Traffic lights serve no purpose here |
| GR‑05 | Critical | P0 | Road is going nowhere |
| GR‑06 | Medium | P2 | Missing directional arrows on the road |
| GR‑07 | Medium | P2 | Missing dashed lane and there should be no arrow |
| GR‑08 | Minor | P3 | Different offset of the poles from the road guard |
| GR‑09 | Minor | P3 | One sign partially on sidewalk |

### Detailed Descriptions

**GR‑01: Missing full lane**  
- *Expected:* Complete driveable lane.  
- *Actual:* Lane missing.  
- *Impact:* Navigation broken.

**GR‑02: No crosswalk while turning left**  
- *Expected:* Crosswalk at left-turn intersection.  
- *Actual:* None.  
- *Impact:* Pedestrian safety issue.

**GR‑03: "Wrong way" sign facing opposite direction**  
- *Expected:* Sign faces oncoming traffic.  
- *Actual:* Facing away.  
- *Impact:* Confuses player, logical error.

**GR‑04: Traffic lights serve no purpose**  
- *Expected:* Lights regulate intersection.  
- *Actual:* No logical intersection present.  
- *Impact:* Redundant asset.

**GR‑05: Road is going nowhere**  
- *Expected:* Road connects somewhere.  
- *Actual:* Dead end.  
- *Impact:* Map incomplete.

**GR‑06: Missing directional arrows on the road**  
- *Expected:* Arrows painted on lanes.  
- *Actual:* None.  
- *Impact:* Player doesn't know direction.

**GR‑07: Missing dashed lane and there should be no arrow**  
- *Expected:* Dashed line or no arrow.  
- *Actual:* Arrow present without proper lane marking.  
- *Impact:* Visual inconsistency.

**GR‑08: Different offset of the poles from the road guard**  
- *Expected:* Uniform pole placement.  
- *Actual:* Varying offset.  
- *Impact:* Cosmetic inconsistency.

**GR‑09: One sign partially on sidewalk**  
- *Expected:* Sign fully on grass or pavement edge.  
- *Actual:* Intersects sidewalk.  
- *Impact:* Pedestrian obstruction, clipping.

---

## Page 03 – Road Guard / Signage

**Source:** PDF page 3

| ID | Severity | Priority | Description |
|----|----------|----------|-------------|
| RG‑01 | Minor | P3 | Different thickness of the line |
| RG‑02 | Major | P2 | Signs and light pole should be on the other side of the road guard |
| RG‑03 | Major | P1 | Should be on the other side of the road guard and lower speed limit – 30/50 km/h |

### Detailed Descriptions

**RG‑01: Different thickness of the line**  
- *Expected:* Uniform road line thickness.  
- *Actual:* Lines have varying thickness.  
- *Impact:* Visual inconsistency.

**RG‑02: Signs and light pole on wrong side of guard**  
- *Expected:* Placed behind guardrail (away from traffic).  
- *Actual:* On traffic side.  
- *Impact:* Safety hazard, visual error.

**RG‑03: Wrong side + incorrect speed limit**  
- *Expected:* Correct side, limit 30 or 50 km/h.  
- *Actual:* Wrong side + wrong limit.  
- *Impact:* Combined logical and gameplay error.

---

## Page 04 – Finland

**Source:** PDF page 4

| ID | Severity | Priority | Description |
|----|----------|----------|-------------|
| FI‑01 | Minor | P3 | Visible mesh |
| FI‑02 | Major | P1 | Yield sign on the road is upside down |

### Detailed Descriptions

**FI‑01: Visible mesh**  
- *Expected:* No visible mesh clipping.  
- *Actual:* Mesh protrudes or renders incorrectly.  
- *Impact:* Visual glitch.

**FI‑02: Yield sign upside down**  
- *Expected:* Triangle pointing down.  
- *Actual:* Pointing up (180° rotated).  
- *Impact:* Confuses player, violates traffic logic.

---

## Page 05 – Sweden

**Source:** PDF page 5

| ID | Severity | Priority | Description |
|----|----------|----------|-------------|
| SE‑01 | Medium | P2 | Different logos, doesn't match |
| SE‑02 | Major | P1 | Language on this sign isn't in Swedish |
| SE‑03 | Minor | P3 | Bugged sidewalk |

### Detailed Descriptions

**SE‑01: Different logos don't match**  
- *Expected:* Consistent logo usage.  
- *Actual:* Two or more different logos.  
- *Impact:* Branding inconsistency.

**SE‑02: Language not Swedish**  
- *Expected:* Swedish text.  
- *Actual:* Other language.  
- *Impact:* Localization bug.

**SE‑03: Bugged sidewalk**  
- *Expected:* Intact sidewalk geometry.  
- *Actual:* Clipping, floating, or missing parts.  
- *Impact:* Visual and navigation issue.

---

## Page 06 – Construction Site

**Source:** PDF page 6

| ID | Severity | Priority | Description |
|----|----------|----------|-------------|
| CS‑01 | Major | P1 | On the construction site shouldn't be trees |

### Detailed Descriptions

**CS‑01: Trees on construction site**  
- *Expected:* Construction site cleared of vegetation.  
- *Actual:* Fully grown trees present.  
- *Impact:* Logical inconsistency (trees would be removed before building).

---

## Page 07 – Urban Area / City

**Source:** PDF page 7

| ID | Severity | Priority | Description |
|----|----------|----------|-------------|
| UA‑01 | Minor | P3 | Bugged texture |
| UA‑02 | Major | P2 | Bugged buildings – glitched together |
| UA‑03 | Minor | P3 | Small first letter in the name of the city |
| UA‑04 | Minor | P3 | Bugged texture of the pallet through building |
| UA‑05 | Major | P1 | Bugged building – only half is above ground |

### Detailed Descriptions

**UA‑01: Bugged texture**  
- *Expected:* Textures render correctly.  
- *Actual:* Stretching, missing, or repeating.  
- *Impact:* Visual glitch.

**UA‑02: Buildings glitched together**  
- *Expected:* Separate buildings.  
- *Actual:* Intersecting/clipping.  
- *Impact:* Geometry collision error.

**UA‑03: Small first letter in city name**  
- *Expected:* Proper capitalization (first letter uppercase).  
- *Actual:* Lowercase or smaller font.  
- *Impact:* Cosmetic typography issue.

**UA‑04: Pallet texture through building**  
- *Expected:* Pallet renders correctly outside building.  
- *Actual:* Clips through wall.  
- *Impact:* Visual clipping.

**UA‑05: Half‑submerged building**  
- *Expected:* Building fully above ground.  
- *Actual:* Only half visible, rest below terrain.  
- *Impact:* Major geometry bug.

---

## Page 08 – Missing Area

**Source:** PDF page 8

| ID | Severity | Priority | Description |
|----|----------|----------|-------------|
| MA‑01 | Major | P1 | No crosswalk, missing directional arrows on road |
| MA‑02 | Critical | P0 | Whole segment should be where I draw a line + missing directional arrows + wrong sign (no traffic lights) |
| MA‑03 | Major | P1 | Speed limit should be lower – 30/50 km/h |
| MA‑04 | Critical | P0 | Whole area isn't on the map |

### Detailed Descriptions

**MA‑01: No crosswalk, missing arrows**  
- *Expected:* Crosswalk and arrows present.  
- *Actual:* None.  
- *Impact:* Navigation and pedestrian logic broken.

**MA‑02: Entire segment missing**  
- *Expected:* Segment connects as drawn.  
- *Actual:* Missing; plus no arrows, wrong sign.  
- *Impact:* Map incomplete, player cannot proceed.

**MA‑03: Speed limit too high**  
- *Expected:* Lower limit (30 or 50 km/h).  
- *Actual:* Higher limit posted.  
- *Impact:* Gameplay inconsistency.

**MA‑04: Whole area not on map**  
- *Expected:* Area within map boundaries.  
- *Actual:* Absent from minimap/world map.  
- *Impact:* Critical map boundary error.

---

## Page 09 – Main Street / Dealer

**Source:** PDF page 9

| ID | Severity | Priority | Description |
|----|----------|----------|-------------|
| MS‑01 | Major | P2 | Wrong sign, should be still main street |
| MS‑02 | Major | P1 | Missing yield sign, fence is obstacle on the road |
| MS‑03 | Medium | P2 | Wrong logo of the Manufacturer |
| MS‑04 | Minor | P3 | Different lengths of dashed line |
| MS‑05 | Major | P1 | Dealer isn't on the map |

### Detailed Descriptions

**MS‑01: Wrong sign**  
- *Expected:* Sign indicates main street continues.  
- *Actual:* Different sign.  
- *Impact:* Misleading navigation.

**MS‑02: Missing yield sign + fence obstacle**  
- *Expected:* Yield sign present, fence not on road.  
- *Actual:* No yield sign, fence blocks road.  
- *Impact:* Gameplay obstruction, collision hazard.

**MS‑03: Wrong manufacturer logo**  
- *Expected:* Correct logo for dealer.  
- *Actual:* Different logo.  
- *Impact:* Branding error.

**MS‑04: Different dashed line lengths**  
- *Expected:* Uniform dash lengths.  
- *Actual:* Varying lengths.  
- *Impact:* Visual inconsistency.

**MS‑05: Dealer not on map**  
- *Expected:* Dealer marked on map.  
- *Actual:* Missing.  
- *Impact:* Player cannot locate dealer.

---

## Page 10 – Roundabout

**Source:** PDF page 10

| ID | Severity | Priority | Description |
|----|----------|----------|-------------|
| RB‑01 | Major | P1 | Missing "Wrong Way" and "Yield" sign |
| RB‑02 | Major | P1 | Missing "Wrong Way" and "Yield" sign (second location) |
| RB‑03 | Medium | P2 | Missing directional arrow on the road and dashed line |
| RB‑04 | Medium | P2 | Missing dashed line on the roundabout |
| RB‑05 | Critical | P0 | Map bug – roundabout isn't whole |
| RB‑06 | Medium | P2 | Missing dashed line (third instance) |

### Detailed Descriptions

**RB‑01 & RB‑02: Missing signs (two locations)**  
- *Expected:* "Wrong Way" and "Yield" at roundabout entries.  
- *Actual:* Absent.  
- *Impact:* Player drives wrong way, confusion.

**RB‑03: Missing arrow + dashed line**  
- *Expected:* Directional arrow and dashed lane marking.  
- *Actual:* None.  
- *Impact:* Poor lane guidance.

**RB‑04: No dashed line on roundabout**  
- *Expected:* Dashed lines defining lanes.  
- *Actual:* Missing.  
- *Impact:* Lane confusion.

**RB‑05: Incomplete roundabout on map**  
- *Expected:* Full roundabout shown on minimap.  
- *Actual:* Partially missing (e.g., 3/4 visible).  
- *Impact:* Map rendering bug.

**RB‑06: Another missing dashed line**  
- *Expected:* Dashed line present.  
- *Actual:* Absent.  
- *Impact:* Cumulative lane marking issue.

---

## Page 11 – Bridge

**Source:** PDF page 11

| ID | Severity | Priority | Description |
|----|----------|----------|-------------|
| BR‑01 | Major | P2 | Misplaced pole – on the side of the bridge, should be on the rail |
| BR‑02 | Major | P1 | Misplaced light pole – should be on road guard, not on the road |
| BR‑03 | Medium | P2 | Glitched texture – rocks and water mixed up + fence of the building bugged, should be on the green as well, not mixed |

### Detailed Descriptions

**BR‑01: Pole on bridge side instead of rail**  
- *Expected:* Pole attached to bridge rail.  
- *Actual:* Placed on side surface.  
- *Impact:* Visual inconsistency.

**BR‑02: Light pole on road**  
- *Expected:* Mounted on guardrail.  
- *Actual:* Standing on drivable road.  
- *Impact:* Collision hazard, illogical placement.

**BR‑03: Mixed rock/water texture + bugged fence**  
- *Expected:* Clear separation, fence on grass.  
- *Actual:* Textures overlapping, fence intersects incorrectly.  
- *Impact:* Visual glitch, asset placement error.

---

## Page 12 – Bus Stop

**Source:** PDF page 12

| ID | Severity | Priority | Description |
|----|----------|----------|-------------|
| BS‑01 | Major | P1 | City name on the bus stop isn't in Finland |
| BS‑02 | Minor | P3 | Pole is bugged in the wall |
| BS‑03 | Major | P2 | Pedestrian shouldn't be there, it's only for traffic |

### Detailed Descriptions

**BS‑01: Wrong city name language**  
- *Expected:* Finnish city name (in Finland location).  
- *Actual:* Name in other language or non-Finnish spelling.  
- *Impact:* Localization error.

**BS‑02: Pole clipping into wall**  
- *Expected:* Pole placed outside wall.  
- *Actual:* Mesh intersects wall.  
- *Impact:* Clipping glitch.

**BS‑03: Pedestrian in traffic-only area**  
- *Expected:* No pedestrians where only vehicles allowed.  
- *Actual:* Pedestrian present.  
- *Impact:* Logical inconsistency, safety violation.

---

## Summary

| Page | Location | Bug Count | Critical (P0) | Major (P1) |
|------|----------|-----------|---------------|------------|
| 1 | General Store | 4 | 0 | 2 |
| 2 | Greece | 9 | 2 | 4 |
| 3 | Road Guard | 3 | 0 | 2 |
| 4 | Finland | 2 | 0 | 1 |
| 5 | Sweden | 3 | 0 | 1 |
| 6 | Construction | 1 | 0 | 1 |
| 7 | Urban Area | 5 | 0 | 2 |
| 8 | Missing Area | 4 | 2 | 2 |
| 9 | Main Street | 5 | 0 | 3 |
| 10 | Roundabout | 6 | 1 | 2 |
| 11 | Bridge | 3 | 0 | 2 |
| 12 | Bus Stop | 3 | 0 | 2 |
| **Total** | | **48** | **5** | **24** |

---

**Report prepared by:** Tomáš Bednář  