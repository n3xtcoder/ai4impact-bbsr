# ÖKOBAUDAT Database Field Descriptions

## Identification and Metadata

| Field | Description |
|-------|-------------|
| UUID | Unique identifier for each dataset |
| Version | Version number of the dataset (format: xx.xx.xxx) |
| Name (de) | Material/product name in German |
| Name (en) | Material/product name in English |
| Kategorie (original) | Original category classification in German |
| Kategorie (en) | Category classification in English |
| Konformität | Compliance with standards (e.g., EN 15804+A2) |
| Laenderkennung | Country code (e.g., DE for Germany) |
| Typ | Dataset type (e.g., generic dataset) |
| Referenzjahr | Reference year for data validity |
| Gueltig bis | Year until which the data is valid |
| URL | Web address to access the dataset details |
| Declaration owner | Organization that owns the dataset |
| Veroeffentlicht am | Publication date |
| Registrierungsnummer | Registration number |
| Registrierungsstelle | Registration authority |
| UUID des Vorgängers | UUID of predecessor dataset version |
| Version des Vorgängers | Version number of predecessor dataset |
| URL des Vorgängers | URL to predecessor dataset (if available) |

## Material Properties and Reference Units

| Field | Description |
|-------|-------------|
| Bezugsgroesse | Reference value for measurements |
| Bezugseinheit | Reference unit (e.g., kg, m², m³) |
| Referenzfluss-UUID | UUID of the reference flow |
| Referenzfluss-Name | Name of reference flow |
| Schuettdichte (kg/m3) | Bulk density in kg/m³ |
| Flaechengewicht (kg/m2) | Area weight in kg/m² |
| Rohdichte (kg/m3) | Raw density in kg/m³ |
| Schichtdicke (m) | Layer thickness in meters |
| Ergiebigkeit (m2) | Coverage/yield in m² |
| Laengengewicht (kg/m) | Linear weight in kg/m |
| Stueckgewicht (kg) | Unit weight in kg |
| Umrechungsfaktor auf 1kg | Conversion factor to 1kg |
| biogener Kohlenstoffgehalt in kg | Biogenic carbon content in kg |
| biogener Kohlenstoffgehalt (Verpackung) in kg | Biogenic carbon content of packaging in kg |

## Life Cycle Information

| Field | Description |
|-------|-------------|
| Modul | Life cycle module (e.g., A1-A3: Production, C2: Transport to waste processing, C3: Waste processing, D: Recycling potential) |
| Szenario | Scenario description |
| Szenariobeschreibung | Detailed scenario description |

## Environmental Impact Indicators (EN 15804+A1)

| Field | Description |
|-------|-------------|
| GWP | Global Warming Potential (kg CO₂ eq.) |
| ODP | Ozone Depletion Potential (kg CFC-11 eq.) |
| POCP | Photochemical Ozone Creation Potential (kg NMVOC eq.) |
| AP | Acidification Potential (Mole of H⁺ eq.) |
| EP | Eutrophication Potential |
| ADPE | Abiotic Depletion Potential - Elements (kg Sb eq.) |
| ADPF | Abiotic Depletion Potential - Fossil fuels (MJ) |

## Resource Use Indicators

| Field | Description |
|-------|-------------|
| PERE | Use of renewable primary energy as energy carrier (MJ) |
| PERM | Use of renewable primary energy resources used as raw materials (MJ) |
| PERT | Total use of renewable primary energy (MJ) |
| PENRE | Use of non-renewable primary energy as energy carrier (MJ) |
| PENRM | Use of non-renewable primary energy resources used as raw materials (MJ) |
| PENRT | Total use of non-renewable primary energy resources (MJ) |
| SM | Use of secondary material (kg) |
| RSF | Use of renewable secondary fuels (MJ) |
| NRSF | Use of non-renewable secondary fuels (MJ) |
| FW | Net use of fresh water (m³) |

## Waste and Output Flows

| Field | Description |
|-------|-------------|
| HWD | Hazardous waste disposed (kg) |
| NHWD | Non-hazardous waste disposed (kg) |
| RWD | Radioactive waste disposed (kg) |
| CRU | Components for re-use (kg) |
| MFR | Materials for recycling (kg) |
| MER | Materials for energy recovery (kg) |
| EEE | Exported electrical energy (MJ) |
| EET | Exported thermal energy (MJ) |

## Environmental Impact Indicators (EN 15804+A2)

| Field | Description |
|-------|-------------|
| AP (A2) | Acidification Potential (Mole of H⁺ eq.) |
| GWPtotal (A2) | Total Global Warming Potential (kg CO₂ eq.) |
| GWPbiogenic (A2) | Biogenic Global Warming Potential (kg CO₂ eq.) |
| GWPfossil (A2) | Fossil Global Warming Potential (kg CO₂ eq.) |
| GWPluluc (A2) | Global Warming Potential - land use and land use change (kg CO₂ eq.) |
| ETPfw (A2) | Ecotoxicity, freshwater |
| PM (A2) | Particulate Matter emissions |
| EPmarine (A2) | Eutrophication Potential, marine (kg N eq.) |
| EPfreshwater (A2) | Eutrophication Potential, freshwater (kg P eq.) |
| EPterrestrial (A2) | Eutrophication Potential, terrestrial (Mole of N eq.) |
| HTPc (A2) | Human Toxicity Potential, cancer effects |
| HTPnc (A2) | Human Toxicity Potential, non-cancer effects |
| IRP (A2) | Ionizing Radiation Potential |
| SOP (A2) | Soil Quality Potential |
| ODP (A2) | Ozone Depletion Potential (kg CFC-11 eq.) |
| POCP (A2) | Photochemical Ozone Creation Potential (kg NMVOC eq.) |
| ADPF (A2) | Abiotic Depletion Potential - Fossil fuels (MJ) |
| ADPE (A2) | Abiotic Depletion Potential - Elements (kg Sb eq.) |
| WDP (A2) | Water Depletion Potential (m³ world equiv.) |

