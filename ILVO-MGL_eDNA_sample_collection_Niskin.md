---
# MIOP terms
methodology_category: sampling collection procedure
project: ILVO Marine Genomics Laboratory Group protocols
purpose: biodiversity assessment objective [OBI:0001969]
analyses: environmental material collection process [OBI:0600012]
geographic_location: North Sea [GAZ:00002284], Southern Bight [GAZ_00050972] 
broad_scale_environmental_context: marine biome [ENVO:00000447], marine photic zone [ENVO:00000209], neritic pelagic zone biome [ENVO:01000032]
local_environmental_context: coastal sea water [ENVO:03605019]
environmental_medium: sea water [ENVO:00002149]
target: deoxyribonucleic acid (DNA) [NCIT:C449], environmental DNA [NCIT:C169106]
creator: Sofie Derycke, Isolde Cornelis, Sara Maes
materials_required: CTD rosette, 2L plastic bottles
skills_required: sterile technique, standard molecular technique, research vessel experience
time_required: 15
personnel_required: 1
language: en
issued: 2025-06-11
audience: scientists
publisher: ILVO Marine Genomics Laboratory
hasVersion: 1
license: CC0 1.0 Universal
maturity level: mature

# FAIRe terms
samp_category: sample
env_broad_scale: marine biome [ENVO:00000447]
env_local_scale: coastal sea water [ENVO:03605019]
env_medium: sea water [ENVO:00002149]
habitat_natural_artificial_0_1: 0
samp_collect_method: CTD rosette
samp_collect_device: Niskin bottle
samp_size: 2000
samp_size_unit: mL
---

# ILVO MGL eDNA Sample Collection Protocol with Niskin

## PROTOCOL INFORMATION

### Minimum Information about an Omics Protocol (MIOP)

- MIOP terms are listed in the YAML frontmatter of this page.
- See [MIOP_definition.md](https://github.com/BeBOP-OBON/0_protocol_collection_template/blob/main/MIOP_definition.md) for list and definitions.

### Making eDNA FAIR (FAIRe)

- FAIRe terms are listed in the YAML frontmatter of this page.
- See <https://fair-edna.github.io/download.html> for the FAIRe checklist and more information.
- See <https://fair-edna.github.io/guidelines.html#missing-values> for guidelines on missing values that can be used for missing FAIRe or MIOP terms.

### Authors

- All authors known to have contributed to the preparation of this protocol, including those who filled in the template.
- Visit https://orcid.org/ to register for an ORCID.
- Date is the date the author first worked on the protocol.

| PREPARED BY  | AFFILIATION  | ORCID        | DATE       |
| ------------ | ------------ | ------------ | ---------- |
| Sofie Derycke | ILVO Marine, MGL | 0000-0003-3763-6187 | 2025-06-11 |
| Isolde Cornelis | ILVO Marine, MGL | 0009-0006-0636-2477 | yyyy-mm-dd |
| Sara Maes | ILVO Marine, MGL | 0000-0003-2868-4769 | yyyy-mm-dd |
### Related Protocols

- This section contains protocols that should be known to users of this protocol.
- Include the link to each protocol.
- Include the version number and release date (if available).
- Internal/External: "Internal" are derivative or altered protocols, or other protocols in this workflow. "External" are protcols from manufacturers or other groups.

| PROTOCOL NAME | LINK         | VERSION      | RELEASE DATE | INTERNAL/EXTERNAL |
| ------------- | ------------ | ------------ | ------------ | ----------------- |
| Content Cell  | Content Cell | Content Cell | yyyy-mm-dd   | Content Cell      |
| Content Cell  | Content Cell | Content Cell | yyyy-mm-dd   | Content Cell      |

### Protocol Revision Record

- Version numbers start at 1.0.0 when the protocol is first completed and will increase when changes that impact the outcome of the procedure are made (patches: 1.0.1; minor changes: 1.1.0; major changes: 2.0.0).
- Release date is the date when a given protocol version was finalised.
- Description of revisions includes a brief description of what was changed relative to the previous version.

| VERSION | RELEASE DATE | DESCRIPTION OF REVISIONS |
| ------------- | ------------- | ------------- |
| 1.0.0 | 2025-06-11 | Initial release |

### Acronyms and Abbreviations

| ACRONYM / ABBREVIATION | DEFINITION |
| ------------- | ------------- |
|ILVO | Flanders Research Institute for Agriculture, Fisheries and Food |
|CTD | Conductivity Temperature Depth |
|DNA	|Deoxyribonucleic acid |
|eDNA	|environmental DNA |
|EtOH | Ethanol |

### Glossary

| SPECIALISED TERM | DEFINITION |
| ------------- | ------------- |
| Conductivity, Temperature, Depth (CTD) sensor | Sensor used to measure temperature, conductivity and pressure. Additional sensors are often attached to the frame of the deployable CTD frame (oxygen, chlorophyll, pH, etc.) to collect additional data. Often, niskin bottles are attached to the same deployable metal frame as the CTD and ancilliary sensors so that water parameter data are collected alongside niskin water samples. Deployments of this suite of instruments and sensors on the same frame is often referred to as a "CTD cast". |
| Field blank | Sampling negative control. Typically distilled or reverse osmosis water run through a filter like a seawater eDNA sample to control for contamination in the field sampling step.  |
| Niskin bottle  | Plastic cylindrical bottle of varying volumes for collecting discrete water samples. A stopper at each end of the bottle can be "cocked" open with an electronic or weight triggered release mechanism causing the stoppers to snap shut. This is remotely triggered so the bottle closes at a prescribed depth. Often, multiple bottles are arranged on the same frame as a CTD and other sensors in a "rosette". |
|CTD cast| refers to the lowering and raising of a CTD instrument into the sea to make profiles of conductivity, temperature and depth.

## BACKGROUND

This document describes the protocol to collect seawater with Niskin bottles for eDNA analyses. At ILVO, we have been collecting eDNA water samples since 2019, and have modified our collection protocol based on practical experience onboard the research vessels and on sequencing results from various campaigns. This version of the protocol has been developped in the framework of the eDNAqua-Plan project which aims to make eDNA datasets FAIR. 

### Summary

This protocol is intended to perform eDNA analyses to assess marine biodiversity patterns in the Belgian part of the North sea; the geographical area is a shallow marine system, with water depths ranging between 7 and 30 m. There is no halocline and water is well mixed in this area. Previous research has shown that biodiversity patterns assessed with surface (1 m below surface) or bottom (1-3m above seafloor) samples are similar (Dukan et al. 2024). Consequently, seawater sample collection is done at one depth, between 1 and 3 m above the seafloor, to increase detection of epibenthic species. 

### Method Description and Rationale

This protocol uses Niskin bottles mounted on a CTD rosette onboard a research vessel to collect seawater. In each sample location, five Niskin bottles are filled with seawater collected at a depth of 1 to 3 m above the seafloor. From each Niskin bottle, a subsample of 2L is collected. The number of Niskin bottles in a location has been determined based on collecting 10 Niskin bottles in five stations located in known fish communities (coastal, transition and offshore). 12S metabarcoding results showed an increased number of fishes detected with increasing number of replicates. A trade-off between sampling effort and maximal detection of the common fishes led to the collection of 5 bottles to adequately describe fish biodiversity patterns. If rare species are also of interest, then more Niskin bottles should be collected. Increasing the number to 10 bottles leads on average to the detection of four extra species. Depending on the research vessel, further processing is done in a separate lab onboard (RV Belgica) or in the lab at ILVO (Simon Stevin). This processing involves filtering of the water using sterivex 0.45µm capsule filters, which are then used for eDNA extraction and metabarcoding. 

### Spatial Coverage and Environment(s) of Relevance

This protocol has been applied for hundreds of samples collected in the southern North Sea. Samples have been collected in the belgian part of the North Sea during spring and autumn campaigns since 2021 at various distances from shore (coastal, transition and offshore locations). This protocol is also applied for surveys in the southern bight of the North Sea (maximum depth 50 m). All samples are taken in the photic zone and are situated in the neritic pelagic zone. 

## PERSONNEL REQUIRED

One technician or scientist with experience in sterile and clean working and with research vessel experience. 

### Safety

This protocol does not involve any hazardous chemicals, although standard precautions including wearing PPE should be taken to avoid skin and eye exposure to bleach and ethanol.

### Training Requirements

Training for working onboard a research vessel and for working sterile is required to conduct this protocol. Experience with going to sea and sample collection under seagoing conditions is encouraged, at a minimum personel should be trained to handle the CTD software before the first deployment at sea.

### Time Needed to Execute the Procedure

The time needed varies based on the number and type of samples collected. For a majority of our sampling, five niskin bottles on a CTD rosette are triggered to collect sea water at one depth (e.g., 1-3 m off bottom depending on the weather conditions). Then a singular sample is collected from each niskin. A cast in the southern Bight of the North Sea is at most 50 m deep and takes roughly 10 minutes (including 3 minutes of calibration time subsurface for the CTD sensors). Collecting a 2L subsample from one niskins take between 2-5 minutes, depending on access and size of the Niskin bottle (larger botlles are faster to subsample because there is more pressure on the water to flow out of the Niskin spout/spigot). The total collection time for a singular cast with five niskins triggered and one sample taken from each niskin is 35 minutes on average.

## EQUIPMENT

- Description: E.g., "filter".
- Product Name and Model: Provide the official name of the product.
- Manufacturer: Provide the name of the manufacturer of the product.
- Quantity: Provide quantities necessary for one application of the standard operating procedure (e.g., number of filters).
- Remark: For example, some of the consumable may need to be sterilized, some commercial solution may need to be diluted or shielded from light during the operating procedure.

| DESCRIPTION | PRODUCT NAME AND MODEL | MANUFACTURER | QUANTITY | REMARK |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| **Durable equipment** |
| Commercial drinking water bottles | 2L Everyday | Colruyt | 5 per cast | Can be substituted with similar clean drinking water bottles  |
| Content Cell | Content Cell | Content Cell | Content Cell | Content Cell |
| Prefilter mesh | 200µm mesh size | Generic | 5 percast |Must be sterilized with 10% bleach and sterile MilliQ water |
| **Consumable equipment** |
| Nitril gloves | Content Cell | Content Cell | Content Cell | Content Cell |
| Paper cloth | Content Cell | Content Cell | Content Cell | Content Cell |
| Label stickers | Content Cell | Content Cell | Content Cell | Content Cell |
| Writing utensils | Pens and permanent marker | Generic | 2 |  |

| **Chemicals** |
| 70% EtOH | Molecular biology grade ethanol | 500 mL |  |
| 10% bleach | Hypochlorite bleach | Clorox | 400 mL| Remake every ~5 days as bleach decomposes quickly at 10% concentration. The majority is used in bottle/tube sterilization.|

| Content Cell | Content Cell | Content Cell | Content Cell | Content Cell |
| Content Cell | Content Cell | Content Cell | Content Cell | Content Cell |

## STANDARD OPERATING PROCEDURE

In the following SOP, please use the exact names of equipment as noted in the table above.

Provide a step-by-step description of the protocol. The identification of difficult steps in the protocol and the provision of recommendations for the execution of those steps are encouraged.

### Preparation
**before embarking**
Prefilter sterilization: 
Preprinted labels: 
Digital cruise report file:

**Immediately before sampling**

Glove Sterilization: Sterile nitrile gloves must be worn at all times during the sterilization, sampling, filtering, preservation and storage steps. Gloves directly from the box are not considered sterile. To sterilize, put on a new pair of gloves, squirt 10% bleach solution from a squirt bottle onto the gloves and rub hands together, then squirt with EtOH to get rid of bleach residue.  

2L commercial drinking water bottles: label five 2L bottles with the pre-printed labels (NameStation_ReplicateNumber) onto the side of the bottles and write down the location and date on the bottle itself with the marker  

Niskin bottles: open six bottles at the top and ensure the rosette is balanced (choose three bottles in front of each other), close the bottom stopper and close the faucet; pour 2L drinking water in each Niskin bottle and immediately close the empty plastic bottle; open the faucet to flush it with the drinking water; afterwards, open the bottom stopper to remove the remaining water.  

### Sampling

This protocol is designed for samples collected with a niskin bottle - the samples are expected to be discrete and sealed masses of water that can be transferred to a 1 L Nalgene bottle without contamination (typically from the spout/spigot of the niskin bottle). For our samples, niskin bottles are remotely triggered to close at a specified depth and collected alongside complementary hydrographic data (using a CTD attached to the niskin sampling rosette). 

Fill 2 L plastic bottle with 2 L of seawater. It is important to do this before the sample seawater has sat on the deck in the sun. After collecting, if you don’t have time to filter, label and store bottles in the fridge (4˚C) for up to 12 hours (>4 hours is not ideal), or in the freezer (-20°C)if filtering will be done later. Note the length of time a seawater sample sits in the fridge/freezer in the cruise report.

Please specify how you collected samples and note what equipment you used to do so (e.g. targeted water mass, volume, sampling equipment, replication).

1. [Step 1]
2. [Step 2]

### Filtration

Please specify how you filtered the samples and note what equipment you used to do so (e.g. mixing, volume filtered, size of filter and pores, filtration apparatus, duration of filtration, replication).

1. [Step 1]
2. [Step 2]

### Sample Preservation

Please specify what steps you took to preserve the samples taken and note what equipment you used to do so (e.g. freezing in liquid nitrogen).

1. [Step 1]
2. [Step 2]

### Storage

Please specify how you stored your samples and note what equipment you used to do so (e.g. stored in -80°C freezer).

1. [Step 1]
2. [Step 2]

### Quality Control

Describe and explain criteria used to validate results of the standard operating procedure.

### Basic Troubleshooting Guide

- Identify known issues associated with the procedure, if any.
- Provide troubleshooting guidelines when available.

## REFERENCES

- Insert all references cited in the document.
- Please insert full DOI address when available, e.g. http://doi.dx.org/10.1007/s11258-014-0404-1.

Dukan et al. 2024

## APPENDIX A: DATASHEETS

Link templates (e.g. preformatted spreadsheets) used to record measurements and report on the quality of the data as well as any documents such as manufacturer specifications, images, etc that support this protocol. Please include a short note describing the document's relevance. 

