# Book Cover Images

This folder stores the cover images used in Research/Books.html. Keep it lightweight and consistent so pages load fast and look tidy.

## What goes here
- One JPG per publication cover that appears in the Authored Books section.
- Optional: temporary `placeholder.jpg` for items without a real cover yet.

## File naming convention
- Lowercase, words separated with hyphens
- Include the publication year at the end
- Extension: `.jpg`

Examples:
- `geographic-information-systems-2022.jpg`
- `geomorphology-2020.jpg`
- `sea-level-changes-2019.jpg`

## Image specifications (recommended)
- Format: JPEG (sRGB)
- Aspect ratio: ~2:3 portrait (or the closest available)
- Suggested size: 800–1200 px height (optimize for clarity, not overkill)
- Target file size: ≤ 300 KB (use compression)

Tips: Use an optimizer (e.g., ImageOptim, Squoosh) and avoid upscaling tiny images.

## Alt text standard
Describe the cover succinctly: `alt="Book cover for <Title>"`.

## How to add or update a cover
1) Save the optimized image with the correct filename into this directory.
2) In `Research/Books.html`, update the corresponding `<img>` `src` to point at the raw GitHub URL:

```
https://raw.githubusercontent.com/AlexandrosLiaskos/OpenScholar.Evelpidou/master/assets/book-covers/[filename].jpg
```

Example:
```html
<img src="https://raw.githubusercontent.com/AlexandrosLiaskos/OpenScholar.Evelpidou/master/assets/book-covers/geomorphology-2020.jpg" alt="Book cover for Geomorphology">
```

3) Commit your change and verify the image renders in the site.

## Placeholder policy
Use `placeholder.jpg` when the real cover is unavailable. Replace it as soon as a proper cover is ready.

## Expected filename reference

Below is the complete list of expected filenames for all books in the Authored Books section, organized by year. Use this as a guide when saving new cover images.

### Authored Books (2025–2002)

**2025:**
- `geovt-project-2025.jpg` — Geomorphology, Geohazards and Geoheritage in Virtual Reality

**2023:**
- `geographic-information-systems-arcgis-pro-2023.jpg` — Geographic Information Systems from theory to practice: using ArcGIS Pro
- `applied-urban-geomorphology-2023.jpg` — Applied and Urban Geomorphology
- `quaternary-geology-archeogeomorphology-2023.jpg` — Quaternary Geology and Archeogeomorphology

**2022:**
- `geographic-information-systems-2022.jpg` — Geographic Information Systems

**2020:**
- `geomorphology-2020.jpg` — Geomorphology

**2019:**
- `sea-level-changes-2019.jpg` — Sea Level Changes
- `geophysical-phenomena-alexandrian-2019.jpg` — Geophysical Phenomena and Alexandrian Littoral

**2018:**
- `geomorphology-laboratory-exercises-2018.jpg` — Geomorphology-Laboratory Exercises

**2015:**
- `geographic-information-systems-2015.jpg` — Geographic Information Systems

**2009:**
- `mapping-geomorphological-environments-2009.jpg` — Mapping Geomorphological Environments

**2006:**
- `gis-mapinfo-professional-2006.jpg` — Geographic Information Systems-Use of MapInfo Professional
- `quaternary-geology-2006.jpg` — Quaternary Geology

**2002:**
- `gis-theory-practice-2002.jpg` — G.I.S. from theory to practice
- `windows-word-excel-internet-2002.jpg` — Windows-Word-Excel-Internet from theory to application

### Edited Volumes (2019–2008)

**2019:**
- `best-practices-mediterranean-2019.jpg` — Best Practices in Evaluation and Restoration of Degraded Mediterranean Environments
- `training-land-restoration-2019.jpg` — Training on land restoration: Impact analysis on "green employment"

**2018:**
- `geophysical-phenomena-alexandrian-2018.jpg` — Geophysical phenomena and the littoral Alexandria

**2012:**
- `runoff-erosion-2012.jpg` — Runoff Erosion

**2010:**
- `urban-flood-management-2010.jpg` — Urban Flood Management
- `natural-heritage-east-west-2010.jpg` — Natural Heritage from East to West

**2009:**
- `soil-protection-mediterranean-2009.jpg` — Soil Protection in Sloping Mediterranean Agri-Environments, Lectures and exercises

**2008:**
- `risk-assessment-pollution-hazards-2008.jpg` — Risk Assessment and pollution hazards in environmentally sensitive European regions
- `methodological-approaches-geoarchaeology-2008.jpg` — Methodological Approaches in Geoarchaeology
- `geoinformation-geocultural-landscape-2008.jpg` — GeoInformation Technology for Geo-Cultural Landscape Analysis
- `caves-underground-heritage-2008.jpg` — Caves-Natural & Manmade Underground European Heritage

### Handbooks (2023–2005)

**2023:**
- `intro-gis-handbook-arcgis-pro-2023.jpg` — INTRODUCTION TO GEOGRAPHIC INFORMATION SYSTEMS-Handbook ArcGIS Pro
- `gis-environmental-applications-2023.jpg` — GEOGRAPHIC INFORMATION SYSTEMS IN ENVIRONMENTAL APPLICATIONS Laboratory notes
- `geographic-information-systems-arcgis-pro-notes-2023.jpg` — Geographic Information Systems – Laboratory notes for ArcGIS Pro

**2022:**
- `resilience-strategies-heritage-landscapes-2022.jpg` — Course Module Resilience Strategies for Natural and Historic Heritage Landscapes – Study Guide
- `telematics-metrics-2022.jpg` — Course Module Telematics and metrics – Study Guide

**2021:**
- `integrated-coastal-zone-management-2021.jpg` — Integrated coastal zone management. Student guide
- `flash-floods-2021.jpg` — Flash floods. Student guide
- `arcpro-lab-instruction-2021.jpg` — ArcPro, Laboratory instruction guide

**2018:**
- `coastal-systems-mediterranean-fieldtrip-2018.jpg` — Field trip 2. Coastal systems

**2017:**
- `quaternary-geoenvironment-archaeogeomorphology-2017.jpg` — Quaternary GeoEnvironment-ArchaeoGeomorphology. Field trip guide
- `land-rehabilitation-mediterranean-2017.jpg` — Land rehabilitation in Mediterranean environments. Field trip guide

**2016:**
- `coastal-erosion-erasmus-2016.jpg` — Coastal erosion. Notes within framework of Erasmus+ International Course 2016

**2015:**
- `gis-lab-instruction-2015.jpg` — G.I.S. Laboratory instruction guide

**2012:**
- `marathon-park-schinias-fieldtrip-2012.jpg` — Studying the Environment-Protection and Management-Marathon National Park Schinias. Field trip guide

**2011:**
- `building-materials-crete-fieldtrip-2011.jpg` — Building materials of antiquity and geomorphological evolution of W. Crete

**2009:**
- `erosion-geomorphology-fieldtrip-2009.jpg` — Erosion and Geomorphology, Field trip guide

**2008:**
- `georeference-3d-variables-2008.jpg` — Georeference systems and Analysis of 3-D variables. Notes
- `landscape-evolution-geoarchaeology-2008.jpg` — Field trip guide for 13th Belgium-France-Italy-Romania Geomorphological Meeting

**2007:**
- `applied-geomorphology-fieldtrip-2007.jpg` — Applied Geomorphology, Theory and Practice, Field trip guide
- `vouraikos-river-fieldtrip-2007.jpg` — Applied Geomorphology in Valley of Vouraikos River, Field trip guide

**2006:**
- `samos-geocultural-resources-2006.jpg` — GeoCultural Resources of Samos Island - a brief guide, Field trip guide
- `samos-island-guide-2006.jpg` — Guide to Samos Island, Field trip guide
- `gis-notes-2006.jpg` — Geographic Information Systems (notes)

**2005:**
- `geomorphology-notes-2005.jpg` — Geomorphology (notes)

### Editor of Bulletins & Special Issues (2023–2008)

**2023:**
- `tectonic-geomorphology-orogenic-2023.jpg` — Tectonic Geomorphology in Modern Orogenic Zones
- `coastal-systems-adaptation-2023.jpg` — Coastal Systems: Monitoring, Protection and Adaptation Approaches
- `natural-disaster-coastal-zones-2023.jpg` — Management of Natural Disaster in Coastal Zones

**2022:**
- `tectonics-sea-level-fluctuations-2022.jpg` — Tectonics and Sea-Level Fluctuations
- `eastern-mediterranean-part2-2022.jpg` — Geomorphology, Quaternary Geology and Geoarchaeology of the Eastern Mediterranean-Part 2

**2021:**
- `eastern-mediterranean-parta-2021.jpg` — Geomorphology, Quaternary Geology and Geoarchaeology of the Eastern Mediterranean-Part A

**2015:**
- `coastal-mining-heritage-2015.jpg` — Coastal Landscapes, Mining Activities and Preservation of Cultural Heritage

**2013:**
- `quaternary-geomorphology-tectonically-active-2013.jpg` — Quaternary Geomorphology in Tectonically Active Areas with Emphasis in Fluvio - Coastal Processes

**2008:**
- `geological-society-greece-vol-xlii-ii-2008.jpg` — Bulletin of the Geological society of Greece Vol. XL II/II-2008
- `geological-society-greece-vol-xlii-i-2008.jpg` — Bulletin of the Geological society of Greece, Vol. XLII/I-2008

### Children's Books (2025–2022)

**2025:**
- `where-spring-go-2025.jpg` — Where did the spring go?

**2023:**
- `sand-dune-2023.jpg` — Once upon a time there was a sand dune

**2022:**
- `raindrop-journey-2022.jpg` — The journey of the raindrop

---

## Quick checklist (before committing)
- [ ] Filename follows convention and year suffix
- [ ] Image is portrait, optimized (≤ 300 KB)
- [ ] Alt text added/kept accurate in Books.html
- [ ] Link uses the raw GitHub URL format
