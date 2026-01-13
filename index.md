# Digital Research Applications: Fellowship Data Lab

Welcome to the documentation of digital experiments conducted during the Science Museum Group's Fellowship. This site is a modular exploration of how computational tools—ranging from geospatial mapping to Large Language Models—can enrich and refine museum metadata.

---

## 🌍 Module 1: Geospatial Analysis & Mapping

[cite_start]**Goal:** To transform static geographic metadata into dynamic, coordinate-based information for spatial research and visualization[cite: 1, 2].

### A) Enriching the Places Table
[cite_start]We successfully linked internal museum "Place" data to **Getty Thesaurus of Geographic Names (TGN)** identifiers[cite: 1]. [cite_start]This enabled the addition of precise longitude and latitude coordinates to our records, facilitating deep geospatial analysis of both the collection's composition and all objects linked to those geographic entities[cite: 1, 2].

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
* [cite_start]**Local Precision**: Further geospatial analysis of objects within the UK at county and city levels[cite: 9].
* [cite_start]**Benchmarking**: Compare our collection's distribution with other major museum datasets[cite: 10].

### D) Audience Insights (Google Analytics)
[cite_start]By combining **Google Analytics** visitor numbers with geocoded location data, we visualized whether international visitors tend to view objects made in their own countries or explore items from elsewhere[cite: 11].

**Future Work:**
* [cite_start]**Live Integration**: Enhance the visualization by integrating real-time visitor information[cite: 11].
* [cite_start]**Analytical Depth**: Explore the integration of additional Google Analytics metrics and other monitoring tools[cite: 12, 13].

### E) Mapping Railway Poster Destinations
[cite_start]Travel destinations mentioned in the metadata of a subset of railway posters were extracted and visualized on a map[cite: 13, 14].

**Future Work:**
* [cite_start]**Scale-up**: Extract information from the full set of railway posters and incorporate visual material extraction[cite: 14, 15].
* [cite_start]**Complex Data Mapping**: Experiment with better approaches for visualising objects containing multiple location references within their metadata[cite: 16].

---

### 📍 Data Sample: Reconciled Places
*Below is a sample of the enriched data from the Places table, showing the successful link between internal names, TGN IDs, and coordinates.*

| Place Name | Broader Context | TGN ID | Latitude | Longitude |
| :--- | :--- | :--- | :--- | :--- |
| **Dunecht** | Aberdeenshire; Scotland | 7030514 | 57.15 | -2.4 |
| **Belgium** | World; Europe | 1000063 | 50.8333 | 4.0 |
| **Greenwich** | London; England | 7018915 | 51.4667 | 0.0333 |
| **Jonkoping** | Sweden | 1000396 | 57.5 | 14.5 |
| **Pembrey** | Carmarthenshire; Wales | 7010408 | 51.6833 | -4.2667 |

---

**[Note: To add the next module, simply append the next block of text and data below this line.]**
