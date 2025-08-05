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
| Isolde Cornelis | ILVO Marine, MGL | 0009-0006-0636-2477 | 2025-08-04 |
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
|RV | Research Vessel |
|LAF| Laminar Flow |
|DNA	| Deoxyribonucleic acid |
|eDNA	| environmental DNA |
|dPCR | digital PCR |
|EtOH | Ethanol |
|PPE | Personal Protective Equipment |
|m | meter |
|mm | millimeter |
|L | liter |
|ml | milliliter |
|C | Celcius |

### Glossary

| SPECIALISED TERM | DEFINITION |
| ------------- | ------------- |
| Conductivity, Temperature, Depth (CTD) sensor | Sensor used to measure temperature, conductivity and pressure. Additional sensors are often attached to the frame of the deployable CTD frame (oxygen, chlorophyll, pH, etc.) to collect additional data. Often, niskin bottles are attached to the same deployable metal frame as the CTD and ancilliary sensors so that water parameter data are collected alongside niskin water samples. Deployments of this suite of instruments and sensors on the same frame is often referred to as a "CTD cast". |
| Field blank | Sampling negative control. Typically distilled or reverse osmosis water run through a filter like a seawater eDNA sample to control for contamination in the field sampling step.  |
| Niskin bottle  | Plastic cylindrical bottle of varying volumes for collecting discrete water samples. A stopper at each end of the bottle can be "cocked" open with an electronic or weight triggered release mechanism causing the stoppers to snap shut. This is remotely triggered so the bottle closes at a prescribed depth. Often, multiple bottles are arranged on the same frame as a CTD and other sensors in a "rosette". |
| CTD cast | refers to the lowering and raising of a CTD instrument into the sea to make profiles of conductivity, temperature and depth.

## BACKGROUND

This document describes the protocol to collect seawater with Niskin bottles for eDNA analyses. At ILVO, we have been collecting eDNA water samples since 2019, and have modified our collection protocol based on practical experience onboard the research vessels, based on sequencing results from various campaigns and based on review comments from the journal Environmental DNA. This version of the protocol has been developped in the framework of the eDNAqua-Plan project which aims to design a digital landscape that makes eDNA datasets FAIR. 

### Summary

This protocol is intended to collect eDNA onboard research vessels to assess marine biodiversity patterns in the Belgian part of the North sea using eDNA; the geographical area is a shallow marine system, with water depths ranging between 7 and 30 m. There is no halocline and water is well mixed in this area. Previous research has shown that biodiversity patterns assessed with surface (1 m below surface) or bottom (1-3m above seafloor) samples are similar (Dukan et al. 2024). Consequently, seawater sample collection is done at one depth, between 1 and 3 m above the seafloor, to increase detection of epibenthic species. 

### Method Description and Rationale

This protocol uses Niskin bottles mounted on a CTD rosette onboard a research vessel to collect seawater. In each sample location, five Niskin bottles are filled with seawater collected at a depth of 1 to 3 m above the seafloor. From each Niskin bottle, a subsample of 2 L is collected. The number of collected Niskin bottles in a location has been determined based on data gathered from collecting 10 Niskin bottles in five stations located in known fish communities (coastal, transition and offshore). The 12S metabarcoding results showed an increased number of fish species detected with an increasing number of replicates. A trade-off between sampling effort and maximal detection of the common fish species led to the decision to collect 5 Niskin bottles per location to adequately describe fish biodiversity patterns. If also rare species are of interest, then more Niskin bottles should be collected. Increasing the number to 10 Niskin bottles leads, on average, to the detection of four additional species. Depending on the research vessel, further processing is done in a separate lab onboard (RV Belgica) or in the lab at ILVO (RV Simon Stevin). This processing involves filtering of the water using sterivex 0.45µm capsule filters, which are then used for eDNA extraction and metabarcoding or dPCR. 

### Spatial Coverage and Environment(s) of Relevance

This protocol has been applied for hundreds of samples collected in the Southern North Sea. Samples have been collected in the Belgian part of the North Sea during spring and autumn campaigns since 2021 at various distances from shore (coastal, transition and offshore locations). This protocol is also applied for surveys in the Southern Bight of the North Sea (maximum depth 50 m). All samples are taken in the photic zone and are situated in the neritic pelagic zone. 

## PERSONNEL REQUIRED

One technician or scientist with experience in working in a clean and sterile manner and experience in working on a research vessel.

### Safety

(This protocol does not involve any hazardous chemicals) is hazardous although standard precautions including wearing PPE should be taken to avoid skin and eye exposure to bleach and ethanol. 10 % bleach is hazardous

### Training Requirements

Training for working onboard a research vessel and for working sterile is required to conduct this protocol. Experience with going to sea and sample collection under seagoing conditions is encouraged, at a minimum personel should be trained to handle the CTD software before the first deployment at sea.

### Time Needed to Execute the Procedure

The time needed varies based on the number and type of samples collected. For a majority of our sampling, five Niskin bottles on a CTD rosette are triggered to collect sea water at one depth (e.g., 1-3 m above the bottom depending on the weather conditions). Then a singular sample is collected from each Niskin bottle. A cast in the Southern Bight of the North Sea is at most 50 m deep and takes roughly 10 minutes (including 3 minutes of calibration time subsurface for the CTD sensors). Collecting a 2 L subsample from one Niskin bottle takes between 2-5 minutes, depending on access and size of the Niskin bottle (larger botlles are faster to subsample because there is more pressure on the water to flow out of the Niskin bottle sampling valve). The total collection time for a singular cast with five Niskin bottles triggered and one sample taken from each Niskin bottle is 35 minutes on average.

## EQUIPMENT

- Description: E.g., "filter".
- Product Name and Model: Provide the official name of the product.
- Manufacturer: Provide the name of the manufacturer of the product.
- Quantity: Provide quantities necessary for one application of the standard operating procedure (e.g., number of filters).
- Remark: For example, some of the consumable may need to be sterilized, some commercial solution may need to be diluted or shielded from light during the operating procedure.

| DESCRIPTION | PRODUCT NAME AND MODEL | MANUFACTURER | QUANTITY | REMARK |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| **Durable equipment** |
| Commercial drinking water bottles | 2 L Everyday | Colruyt | 5 per cast + 4 for field controls | Can be substituted with similar clean drinking water bottles  |
| Safety wash bottles | Safety wash bottle 250 ml for 10% bleach or 70% ethanol | VWR | 2 | Can be substituted with generic |
| Prefilter mesh | 200 µm mesh size | Sefar | 5 per cast | Must be sterilized with 10% bleach and sterile MilliQ water |
| Stacking tray | 1 L tray | Generic | 3 | |
| Stomacher bags| blenderbag | Interscience | 1 per batch of 26 prefilters| optional, only if Stomacher device is used to clean the prefilters |
| Glass bottle | Duran 1L bottle | Duran | 4 | Can be substituted with generic, recipient needs to withstand autoclave procedure | 
| 10 L bucket | Plastic, white bucket | Generic | 2 | Can be substituted with generic |
| PMD bags | Plastic bags to collect the empty water bottles | Sara? | 2 | Can be substituted with generic |
| Ziplock bags | Plastic bags to store sterile prefilters and to collect used prefilters | Sara? | 2 | Can be substituted with generic |
| Field lab sheet | Paper sheet with sample locations | Generic | 1 | Can be substituted with generic; is used to write down sampling date and volume filtered |
| **Consumable equipment** |
| SHIELDskin orange nitrile 260 gloves | Powder free nitril gloves | Novolab | 1 box per size | Can be subsituted with generic nitrile gloves. Does not come sterile, must be sterilized before use (10% bleach followed by 70% EtOH) |
| Paper towl | paper sheets to wipe material dry | Tork universal | 1 package | Can be substituted with generic |
| Labels | 105 x 48 mm | HERMA premium | 1 package | Can be substituted with generic; stickers are preprinted in the lab, blanc stickers are also provided as back-up |
| Writing utensils | Pencil and permanent marker | Generic | 2 | Not made of wood - must be able to be wiped down with bleach/EtOH |
| **Chemicals** |
| Ethanol absolute | Ethanol absolute | AnalytiChem | 5 L | Can be substituted with generic, must be molecular biology grade |
| Disolol | Disolol Technisolv | AnalytiChem | 5 L | Can be sustituted with generic |
| 10% bleach | Sodium hypochloride | Colruyt | 2 L | Remake every ~5 days as bleach decomposes quickly at 10% concentration |
| Milli-Q water | Sartorius | Sartorius arium device | | |

## STANDARD OPERATING PROCEDURE

### Preparation
**Before embarking**

*Prefilter sterilization:* 10cm*10cm prefilters are cut from a 200 µm mesh sheet and are used to filter out big pieces of organic material from the seawater to prevent overrepresentation in the eDNA samples. The prefilters are re-used between campaigns. They are washed under tap water to remove the obvious dirt in the filter. After that, filters are submerged in 10% bleach and in sterilised Milli-Q water.

1. Add 800 ml Milli-Q water to four 1L Duran glass bottles and sterilise by placing the bottles in the autoclave for 15 minutes at 121°C
2. Clean the work surface of the LAF cabinet with 10% bleach and 70% ethanol.
3. Clean 5 washing trays with 10% bleach and sterile Milli-Q water and wipe dry with paper in the LAF cabinet; put the five trays next to each other in the LAF cabinet.
4. Switch on the UV light for 30 minutes
5. Switch on the laminar flow, and fill two washing trays with 10% bleach and three with sterile Milli-Q water; keep the 5 trays in the LAF cabinet to avoid any contamination.
6. Take the prefilters and rinse both sides under running tap water to remove the obvious dirt that is on the filter. Batches of 26 filters are optimal for the trays.
------------------------------------------------------------------------------------------------
*Optional, and recommended if filters are re-used between campaigns,* is the use of a stomacher device to remove dirt from the filters. Follow steps 7-9 to ensure dirt in the filters is removed (this part is outside the LAF cabinet); if you use the filters for the first time or visible dirt is absent, you can immediately go to step 10;

7.  Place 26 pre-filters in a stomacher plastic bag, and remove excess water from the stomacher bag.
8.  Add 10% bleach to the stomacher bag (not to full). Press out as much air as possible and close the top of the bag by folding. Leave enough empty space for the bleach to move around when the paddles work or else the bag wil overflow or rip.
9.  Stomacher for 90 seconds or longer to make sure the bleach passes through all the pores.
------------------------------------------------------------------------------------------------  
10.  In the LAF cabinet, take the filters one by one and place them in the first bleach bath and flip the filter a couple of times to expose both sides to the bleach, then transfer to the second bleach bath. Release the filter to ensure the full surface is in contact with the bleach for a few minutes.
11.  Transfer the filter to the first water bath and leave it there until all 26 filters are processed.
12.  Transfer the filters to the second water bath and then to the third water bath. This way, the bleach is removed from the filters.
13.  When all 26 filters are in the last water bath, pour away the water and replace with sterile Milli-Q water to ensure that all bleach is completely removed.
14.  Place all the filters in a ziplock bag, remove excess water and close the bag.
15.  Write the date of cleaning and the number of filters inside the bag with a permanent marker on the bag.
16.  Place the bag under UV for 20 minutes. The filters are now ready for transport or storage until use.

*Preprinted labels:* Each 2-liter commercial drinking water bottle is labelled with a sticker that contains the name of the station and the replicate number (eg ft120_1). The stations and number of replicate samples (Niskin bottles) are usually known before embarking, the stickers are therefore preprinted. Blanc stickers are also provided in case the sampling scheme deviates from the original plan. 

*Digital cruise report file:* during the cruise, a word document is kept that records the activities per day. In addtion, the metadata of the samples needs to be added in the ILVO-MGL_eDNA_sample_collection_MIMARKS.survey.water.6.0_template.xlsx to ensure all relevant metadata fields are filled in. This file can then directly be used for upload to Biosamples in NCBI.

**Immediately before sampling**

Wear new gloves on every location. Keep in mind not to touch your face ed with them. In case you do, change gloves immediately.

### Sampling

This protocol is designed for samples collected with a Niskin bottle - the samples are expected to be discrete and to be sealed masses of water that can be transferred to a 2-liter commercial plastic drinking water bottle without contamination (typically from the sampling valve of the Niskin bottle). For our samples, Niskin bottles are remotely triggered to close at a specified depth and collected alongside complementary hydrographic data (using a CTD attached to the niskin sampling rosette). 

1. Use new gloves for each location and clean them with 10% bleach and 70% ethanol.
2. Stick the pre-printed labels onto the side of the bottles and write down the location and date on the bottle itself with the marker (sometimes, when the bottles are kept in the freezer and then thawn, the sticker gets loose, so additional writing on the bottle ensures the sample info will not be lost).    
3. The negative field controls Niskin were taken just before sampling. Rinse one bottle like you would do before sampling, close the Niskin bottle at the bottom and fill it with one 2-liter bottle of commercial drinking water. Then collect the water from the Niskin bottle in the empty bottle. The Niskin rosette is now ready for sampling as there is no need to rinse the Niskin bottle again. The sample can then be collected from the bottle that was used to rinse the Niskin bottle.
4. Niskin bottles: open six bottles at the top and ensure the rosette is balanced (choose three bottles in front of each other), close the bottom stopper and close the sampling valve.
5. Pour 2 L of drinking water in each Niskin bottle and immediately close the empty commercial plastic drinking water bottle; open the sampling valve of the Niskin bottle to flush it with the drinking water; afterwards, open the bottom stopper to remove the remaining drinking water from the Niskin. This flushing with drinking water does not sterilize the Niskin bottles, but we have the water anyway, so we may as well use it to clean the Niskin bottles a bit.
6. The top and bottom stoppers of the Niskin bottles should be open before deployment of the rosette. The air and sampling valves must be closed before deployment of the rosette.
7. Lower the Niskin rosette subsurface and submerge for three minutes to calibrate the CTD. During these three minutes, the open Niskin bottles are flushed with local seawater, ensuring that any carry-over DNA from the previous location is washed away.
8. After the three minutes, lower the rosette to the desired depth (1 to 3 m above the seafloor) and close the six Niskin bottles. It is important not to hit the floor to avoid upwelling of sediment and damage the CTD. Note down in the campaign report if the CTD touched the seafloor!  
9. Bring the rosette back onboard of the vessel.
10. Immediately subsample the Niskin bottles: open the air and sampling valve and let water flow for a few seconds to wash away any residual DNA in the sampling valve; then fill one empty 2-liter commercial plastic bottle with 2 L of seawater from one Niskin bottle using a sterile pre-filter.
11. Close the 2-liter commercial plastic bottle and put the prefilter in a ziplock bag (all prefilters can be reused after sterilisation with bleach and sterile milliQ water)
12. Repeat this for four other Niskin bottles to reach a total of five 2-liter commercial plastic drinking water bottles filled with 2 L of seawater.

### Storage

After collecting, if you don’t have time/space to filter onboard, store bottles in the dark in the fridge (4˚C) for up to 12 hours (>4 hours is not ideal), or in the freezer (-20°C) if filtering will be done later. Note the length of time a seawater sample sits in the fridge/freezer in the digital campaign report.

### Quality Control

A field blank is taken at the start and end of each campaign to assess possible contamination during the water collection handling procedure onboard the vessel. A plastic commercial drinking water bottle is emptied in the Niskin bottle, and then filled with drinking water from a second commercial drinking water bottle and then sealed.

### Basic Troubleshooting Guide

- Identify known issues associated with the procedure, if any.
- Provide troubleshooting guidelines when available.

## REFERENCES

Dukan, N., Cornelis, I., Maes, S., Hostens, K., De Backer, A., Derycke, S. Vertical and horizontal environmental DNA (eDNA) patterns of fish in a shallow and well-mixed North Sea area. Sci Rep 14, 16748 (2024). https://doi.org/10.1038/s41598-024-66912-2

## APPENDIX A: DATASHEETS

Link templates (e.g. preformatted spreadsheets) used to record measurements and report on the quality of the data as well as any documents such as manufacturer specifications, images, etc that support this protocol. Please include a short note describing the document's relevance. 

Cruise report template: [ILVO-MGL_eDNA_sample_collection_Niskin_Template_Campaign-Report.docx](https://github.com/icornelis90-ilvo/ILVO-MGL_eDNA_sample_collection_Niskin/blob/main/ILVO-MGL_eDNA_sample_collection_Niskin_Template_Campaign-Report.docx)

Sample metadata template: [ILVO-MGL_eDNA_sample_collection_MIMARKS.survey.water.6.0_template.xlsx](https://github.com/sofiederycke/ILVO-MGL_eDNA_sample_collection_Niskin/blob/main/ILVO-MGL_eDNA_sample_collection_MIMARKS.survey.water.6.0_template.xlsx)

Sticker template:
- Big labels: [ILVO-MGL_eDNA_sample_collection_Niskin_Template_Big-Labels.docx](https://github.com/icornelis90-ilvo/ILVO-MGL_eDNA_sample_collection_Niskin/blob/main/ILVO-MGL_eDNA_sample_collection_Niskin_Template_Big-Labels.docx)
- Small labels: [ILVO-MGL_eDNA_sample_collection_Niskin_Template_Small-Labels.docx](https://github.com/icornelis90-ilvo/ILVO-MGL_eDNA_sample_collection_Niskin/blob/main/ILVO-MGL_eDNA_sample_collection_Niskin_Template_Small-Labels.docx)

Manual for CTD software:
- RV Belgica: [ILVO-MGL_eDNA_sample_collection_Niskin_Manual_Niskin-CDT-software_RVBelgica.pdf](https://github.com/icornelis90-ilvo/ILVO-MGL_eDNA_sample_collection_Niskin/blob/main/ILVO-MGL_eDNA_sample_collection_Niskin_Manual_Niskin-CDT-software_RVBelgica.pdf)
- RV Simon Stevin: [ILVO-MGL_eDNA_sample_collection_Niskin_Manual_Niskin-CDT-software_RVSimonStevin.pdf](https://github.com/icornelis90-ilvo/ILVO-MGL_eDNA_sample_collection_Niskin/blob/main/ILVO-MGL_eDNA_sample_collection_Niskin_Manual_Niskin-CDT-software_RVSimonStevin.pdf)
- Manual Seasave V7 (Sea-Bird Scientific): [ILVO-MGL_eDNA_sample_collection_Niskin_Manual-CDT-Software_Seasave.pdf](https://github.com/icornelis90-ilvo/ILVO-MGL_eDNA_sample_collection_Niskin/blob/main/ILVO-MGL_eDNA_sample_collection_Niskin_Manual-CDT-Software_Seasave.pdf)
