# Enhancing Query Recommendations Through User Behavior Analysis
*K-LaMP extension with ORCID-based user profiles and Gemini API for personalized next-query suggestions.*

This repository contains the implementation of a **K-LaMP-inspired framework** for **personalized contextual query suggestion**,  
developed as part of my MSc thesis in Data Science (University of Verona).  

The project re-implements the ideas from the paper *"Knowledge-Augmented Large Language Models for Personalized Contextual Query Suggestion"*  
and extends them by integrating **ORCID profiles** and **user attributes** (profession, nationality, personal interests)  
into the entity-centric knowledge store.

---
## 📑 Workflow

1. **Data Loading**: POI dataset, descriptions, and user profiles.  
2. **Memory Stream Construction**: logs queries, POI views, and ORCID keywords.  
3. **Entity Store Construction**: aggregates entities with counts and timestamps.  
4. **User & Session Modeling**: captures session context from recent interactions.  
5. **Prompt Building (K-LaMP style)**: original vs. enhanced with ORCID integration.  
6. **Gemini API Integration**: generates next-query suggestions under different strategies.  

---
## 📂 Project structure

Quick overview of the repository and the role of each file/folder.

### Top-level

| Path | Description |
|------|-------------|
| `README.md` | Project overview and documentation |
| `Thesis_Enhancing_Query_Recommendations_Through_User_Behavior_Analysis.pdf` | My Thesis |
| `Official_no_Orcid_API.ipynb` | Model 1 & 3 described in my thesis with some use cases |
| `prova_versione_funzionante.ipynb` | Model 2 & 3 described in my thesis with some use cases |
| `Official_Orcid_API.ipynb` | an old version where I tried a primitive version of k-LaMp with ORCID API |
| `Datasets/User Profiles_updated.csv` | simulated User Profiles used |
| `Datasets/poi_info_updated.csv` | POIs (points of interest) in Verona |
| `Datasets/data_descr_en_updated.csv` | Description of the POIs of Verona |



