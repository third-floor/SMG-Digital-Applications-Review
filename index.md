# Digital Research Applications: Fellowship Data Lab

Welcome to the documentation of digital experiments conducted during the Science Museum Group's Fellowship. This site is a modular exploration of how computational tools—ranging from geospatial mapping to Large Language Models—can enrich and refine museum metadata.

---

## 🌍 Module 1: Geospatial Analysis & Mapping

**Goal:** To transform static geographic metadata into dynamic, coordinate-based information for spatial research and visualization.

### A) Enriching the Places Table
[cite_start]We successfully linked internal museum "Place" data to **Getty Thesaurus of Geographic Names (TGN)** identifiers[cite: 1]. [cite_start]This enabled the addition of precise longitude and latitude coordinates to our records, facilitating deep geospatial analysis of both the collection's composition and all objects linked to those geographic entities[cite: 2].

**Future Work:**
* [cite_start]**Service Expansion**: Extend linkages to additional services and gazetteers[cite: 2].
* [cite_start]**Real-time Enrichment**: Add new place name entries and enable searching of external services[cite: 3].
* [cite_start]**Validation Tools**: Create a search app that compares results across multiple different geocoding services[cite: 4].
* [cite_start]**Historical Data Integration**: Identify and integrate mapping datasets such as NLS historic maps, UK Data Service geospatial info, and CamPOP[cite: 5].
* [cite_start]**Institutional Links**: Set up direct connections with the **HeritageGateway**[cite: 6].

### B) Visualizing Object Distribution
[cite_start]A map was created to show the locations of objects based on the "place made" field content[cite: 6]. [cite_start]This allows researchers to analyze the global distribution of historical manufacturing and craftsmanship origins represented in the collection[cite: 7].

**Future Work:**
* [cite_start]**Field Extraction**: Extract and visualize location data mentioned in other descriptive fields beyond "place made"[cite: 8].
* [cite_start]**Gamification**: Explore interactive "map-discovery" games to encourage public engagement[cite: 8].
* [cite_start]**Advanced Spatial Analysis**: Conduct further analysis of object distribution patterns[cite: 9].

### C) Museum Counts & Collection Benchmarking
[cite_start]We developed visualizations showing the distribution of objects across various countries based on their appearance in the "place made" field[cite: 9].

**Future Work:**
* [cite_start]**Local Precision**: Further geospatial analysis of objects within the UK at county and city levels[cite: 10].
* [cite_start]**Benchmarking**: Compare our collection's distribution with other major museum datasets[cite: 10].

### D) Audience Insights (Google Analytics)
[cite_start]By combining **Google Analytics** visitor numbers with geocoded location data, we visualized whether international visitors tend to view objects made in their own countries or explore items from elsewhere[cite: 10, 11].

**Future Work:**
* [cite_start]**Live Integration**: Enhance the visualization by integrating real-time visitor information[cite: 11].
* [cite_start]**Analytical Depth**: Explore the integration of additional Google Analytics metrics and other monitoring tools[cite: 12, 13].

### E) Mapping Railway Poster Destinations
[cite_start]Travel destinations mentioned in the metadata of a subset of railway posters were extracted and visualized on a map[cite: 13, 14].

**Future Work:**
* [cite_start]**Scale-up**: Extract information from the full set of railway posters and incorporate visual material extraction[cite: 14, 15].
* [cite_start]**Complex Data Mapping**: Experiment with better approaches for visualising objects containing multiple location references within their metadata[cite: 16].

---

## 👥 Module 2: People, Identity & Authority Matching

**Goal:** To reconcile museum biographical records with external authority files and leverage AI to identify internal data redundancies.

### A) Global Authority Search Script
[cite_start]As part of a review of authority file management at other GLAM (Galleries, Libraries, Archives, and Museums) institutions, a script was developed to query search terms across multiple publicly available authority files[cite: 17].

**Future Work:**
* [cite_start]**Optimization**: Make the script more robust by implementing parallel searches across different sites rather than sequential execution[cite: 18].
* [cite_start]**Scope Expansion**: Expand searches to include catalogue items as well as authority files[cite: 19].
* [cite_start]**Discovery**: Identify additional institutions providing public access to their authority files[cite: 20].

### B) The Royal Society Connection
[cite_start]Using the **Royal Society Past Fellows** dataset, we tested digital applications designed to identify matching entries across disparate datasets[cite: 20].
* [cite_start]**Result**: Identified **967 entries** for people matched across Collections Online and the Royal Society[cite: 21].
* [cite_start]**Data Correction**: Identified **107 entries** with missing or mismatched life dates (46 birth date mismatches, 17 death date mismatches, and 44 entries where both were incorrect)[cite: 22].
* [cite_start]**Linked Data Enrichment**: Updated approximately **700 identifiers** and links on corresponding Wikidata people pages[cite: 23].

**Future Work:**
* [cite_start]**Global Links**: Establish links with additional external datasets from history of science museum collections worldwide[cite: 24].
* [cite_start]**Wikidata Growth**: Continue adding Science Museum Group (SMG) identifiers to Wikidata[cite: 25].

### C) Whipple Museum Dataset Insights
[cite_start]We collaborated with the **Whipple Museum of the History of Science** to replicate matching workflows[cite: 25]. [cite_start]While the dataset currently lacks authority files—precluding digital matching until a deduplication task is completed—it remains a valuable asset for future testing[cite: 26, 27].

### D) The Darwin Correspondence Project
[cite_start]A dataset of authority entries from the **Darwin Correspondence Project** was used to further test automated matching[cite: 28, 29].
* [cite_start]**Result**: Successfully identified approximately **600 matching pairs** across the two datasets[cite: 30].

### E) Wikidata Accuracy & LLM Verification
[cite_start]We evaluated the accuracy of Wikidata identifiers added via the Heritage Connector project[cite: 31, 32]. [cite_start]Using a pipeline incorporating **Google Gemini**, we retrieved data from both Collections Online and Wikidata to verify if they referred to the same individual[cite: 33].
* [cite_start]**Findings**: Identified **222 incorrect Wikidata links**[cite: 34].
* [cite_start]**Missing Links**: Approximately 100 of these errors occurred because no relevant Wikidata page currently exists for the entity[cite: 35].

**Future Work:**
* [cite_start]**Content Creation**: Proactively create Wikidata/Wikipedia pages for missing entities[cite: 35].
* [cite_start]**Local LLMs**: Utilize local Large Language Models to match Mimsy authorities to Wikidata[cite: 36].

### F) Internal Duplicate Identification
[cite_start]Using an enhanced LLM-based approach, we identified potential duplicate entries within our own people and company records[cite: 36, 37]. [cite_start]By fuzzy matching names and filtering for life-date discrepancies, **665 pairs** of high-likelihood duplicates were identified[cite: 37, 38, 39].

### G) Research & PhD Placement
[cite_start]A PhD placement student aided exploration of these records from August to October[cite: 39].
* [cite_start]**Outputs**: Analysis of date presence in descriptive fields, spatial analysis of people records, and a comparative study of "items on display" versus "items in store"[cite: 40].

---

### ✅ Data Sample: Reconciled Identities
*Examples of successful matches across the Royal Society (RS), Darwin (DCP), and internal (CO) datasets.*

| Name | Match Source | Match Strength | Lifespan (Verified) |
| :--- | :--- | :--- | :--- |
| **Stephen William Hawking** | Royal Society | High | 1942 - 2018 |
| **Margaret Hilda Thatcher** | Royal Society | High | 1925 - 2013 |
| **Charles Robert Darwin** | Darwin Project | High | 1809 - 1882 |
| **Sir Godfrey Newbold Hounsfield** | Royal Society | High | 1919 - 2004 |
| **Adam Sedgwick** | Internal | Fuzzy | 1785 - 1873 |

---

**Next Module:** Ready for the next set! Upload the text and data for **Historical Catalogues** or **Visual Analysis**, and I will add them to the script.
