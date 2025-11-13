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

### Authored Books (2023–2002)

**2023:**
- `geographic-information-systems-arcgis-pro-2023.jpg` — Geographic Information Systems from theory to practice: using ArcGIS Pro
- `applied-urban-geomorphology-2023.jpg` — Applied and Urban Geomorphology
- `quaternary-geology-archeogeomorphology-2023.jpg` — Quaternary Geology and Archeogeomorphology

**2022:**
- `geographic-information-systems-2022.jpg` — Geographic Information Systems

**2020:**
- `geomorphology-2020.jpg` — Geomorphology

**2019:**
- `best-practices-mediterranean-2019.jpg` — Best Practices in Evaluation and Restoration of Degraded Mediterranean Environments
- `sea-level-changes-2019.jpg` — Sea Level Changes
- `geophysical-phenomena-alexandrian-2019.jpg` — Geophysical Phenomena and Alexandrian Littoral

**2018:**
- `geomorphology-laboratory-exercises-2018.jpg` — Geomorphology-Laboratory Exercises

**2015:**
- `geographic-information-systems-2015.jpg` — Geographic Information Systems

**2012:**
- `runoff-erosion-2012.jpg` — Runoff Erosion

**2010:**
- `urban-flood-management-2010.jpg` — Urban Flood Management
- `natural-heritage-east-west-2010.jpg` — Natural Heritage from East to West

**2009:**
- `soil-protection-mediterranean-2009.jpg` — Soil Protection in Sloping Mediterranean Agri-Environments, Lectures and exercises
- `mapping-geomorphological-environments-2009.jpg` — Mapping Geomorphological Environments

**2008:**
- `risk-assessment-pollution-hazards-2008.jpg` — Risk Assessment and pollution hazards in environmentally sensitive European regions
- `methodological-approaches-geoarchaeology-2008.jpg` — Methodological Approaches in Geoarchaeology
- `geoinformation-geocultural-landscape-2008.jpg` — GeoInformation Technology for Geo-Cultural Landscape Analysis
- `caves-underground-heritage-2008.jpg` — Caves-Natural & Manmade Underground European Heritage

**2006:**
- `gis-mapinfo-professional-2006.jpg` — Geographic Information Systems-Use of MapInfo Professional
- `quaternary-geology-2006.jpg` — Quaternary Geology

**2002:**
- `gis-theory-practice-2002.jpg` — G.I.S. from theory to practice
- `windows-word-excel-internet-2002.jpg` — Windows-Word-Excel-Internet from theory to application

### Guides & Notes (2023–2005)

**2023:**
- `intro-gis-handbook-arcgis-pro-2023.jpg` — INTRODUCTION TO GEOGRAPHIC INFORMATION SYSTEMS-Handbook ArcGIS Pro
- `gis-environmental-applications-2023.jpg` — GEOGRAPHIC INFORMATION SYSTEMS IN ENVIRONMENTAL APPLICATIONS Laboratory notes
- `gis-lab-notes-arcgis-pro-2023.jpg` — Geographic Information Systems – Laboratory notes for ArcGIS Pro

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
- `georeference-3d-variables-2008.jpg` — 'Georeference systems and Analysis of 3-D variables'. Notes
- `landscape-evolution-geoarchaeology-2008.jpg` — Field trip guide for 13th Belgium-France-Italy-Romania Geomorphological Meeting

**2007:**
- `applied-geomorphology-fieldtrip-2007.jpg` — Field trip guide, 'Applied Geomorphology, Theory and Practice'
- `vouraikos-river-fieldtrip-2007.jpg` — Field trip guide 'Applied Geomorphology in Valley of Vouraikos River'

**2006:**
- `samos-geocultural-resources-2006.jpg` — Field trip guide, 'GeoCultural Resources of Samos Island - a brief guide'
- `samos-island-guide-2006.jpg` — Field trip guide, 'Guide to Samos Island'
- `gis-notes-2006.jpg` — "Geographic Information Systems" (notes)

**2005:**
- `geomorphology-notes-2005.jpg` — "Geomorphology" (notes)

---

## Quick checklist (before committing)
- [ ] Filename follows convention and year suffix
- [ ] Image is portrait, optimized (≤ 300 KB)
- [ ] Alt text added/kept accurate in Books.html
- [ ] Link uses the raw GitHub URL format
