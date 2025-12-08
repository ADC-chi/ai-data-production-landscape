# AI Data Production Landscape

**Companion repository for the CHI 2026 paper submission:**  
*“Understanding AI Data Production & Community Impacts Worldwide: A Multivocal Literature Review”*

This repository contains the coded dataset, interactive source collections, and supplementary visualizations regarding the search and selection protocol used in our Multivocal Literature Review (MLR).

| 📄 **Paper** | 📊 **Dataset** | 🌐 **Website** |
| :--- | :--- | :--- |
| [**Read Draft (PDF)**](docs/REVISION_ADC_MultivocalV3.pdf) | [**Excel**](https://github.com/ADC-chi/ai-data-production-landscape/blob/main/data/processed/REVISED%20Datasheet.xlsx) · [**CSV**](https://github.com/ADC-chi/ai-data-production-landscape/blob/main/data/processed/REVISED%20Datasheet.csv) · [**Google Sheet**](https://docs.google.com/spreadsheets/d/1NJBIsDhtqp5CrCTJtfccObCneRLaRtoun6VfPuNTims/edit?usp=sharing) | [**Project Landing Page**](https://adc-chi.github.io/ai-data-production-landscape/) |

---

## 🔍 Methodology: Search & Selection Process
The following flow diagram details our attrition and selection protocol, integrating representative academic searches (ACM) with grey literature strategies. 

> **Note:** This figure supplements the methodology section of the submitted PDF.

```mermaid
flowchart TD
    %% --- STYLES ---
    classDef prep fill:#f3e5f5,stroke:#7b1fa2,stroke-width:2px,color:#000;
    classDef acm fill:#e3f2fd,stroke:#1565c0,stroke-width:2px,color:#000;
    classDef grey fill:#fff3e0,stroke:#e65100,stroke-width:2px,color:#000;
    classDef final fill:#e8f5e9,stroke:#2e7d32,stroke-width:3px,color:#000;
    classDef titleNode fill:none,stroke:none,font-weight:bold,font-size:16px,color:#000;

    %% --- PHASE 0 ---
    subgraph Prep ["PHASE 0: PROTOCOL REFINEMENT (Aug-Sept 2024)"]
        direction TB
        P1["A/D/C Framework Dev<br/>& Keyword Strategy"]:::prep
        P2["Pilot Searches<br/>Tested against known<br/>seminal papers"]:::prep
        P1 --> P2
    end

    %% --- PHASE 1 ---
    subgraph ACMFlow [" "]
        direction TB
        Title1["PHASE 1: REPRESENTATIVE SEARCH (ACM)"]:::titleNode
        
        A1[("ACM Digital Library<br/>(Primary Query Sets)")]:::acm
        A2["Identification<br/>Hits: 1,914"]:::acm
        A3["Screening<br/>(Title/Abstract)<br/>Screened: 1,201"]:::acm
        A4["Eligibility<br/>(Full Text A/D/C)<br/>Met Criteria: 153"]:::acm
        A5["Included<br/>Unique Sources: 48"]:::acm
        
        Title1 --> A1
        A1 --> A2 --> A3 --> A4 --> A5
    end

    %% --- PHASE 2 ---
    subgraph OtherStreams ["PHASE 2: EXPANDED SEARCH (Aug 2024 - Jan 2025)"]
        direction TB
        B1[("Other Academic DBs<br/>IEEE, ScienceDirect, Springer,<br/>Wiley, Taylor & Francis")]:::acm
        
        C1[("Grey Literature<br/>Org Reports, Policy Docs,<br/>Google Search")]:::grey
        
        C2[("Targeted Hand-Search<br/>CHI, FAccT, CSCW, JRC,<br/>Big Data & Society, AI & Soc")]:::grey
        
        Process["Rigorous Consensus Review<br/>-----------------------------<br/>• Two authors lead screening<br/>• Batched presentation to full team<br/>• 2 Rounds (Aug-Sept 2024)<br/>• Team iteration through Jan 2025"]:::prep
    end

    %% --- FINAL CORPUS ---
    FinalBox["FINAL CORPUS (N = 350)<br/>---------------------------------------<br/>Database Searches: 174 (50%)<br/>Existing Networks/Orgs: 73 (21%)<br/>Citation Snowballing: 51 (15%)<br/>Iterative Keyword Search: 31 (9%)<br/>Hand-Searching Journals: 21 (6%)"]:::final

    %% --- CONNECTIONS ---
    P2 --> Title1
    P2 --> B1
    
    A5 --> FinalBox
    B1 --> Process
    C1 --> Process
    C2 --> Process
    Process --> FinalBox
```

# 🌊 Context: The AI Development Pipeline
We position data production not as a mere prerequisite, but as a site of sociotechnical power. The image below illustrates the interwoven domains of AI (A), Data Production (D), and Community Impacts (C).

![AI development pipeline](https://github.com/adc-chi/ai-data-production-landscape/blob/main/docs/assets/pipe-1.png?raw=true)

---

# 📚 Interactive Resources
We have curated subsets of our corpus (open-access sources only, max 50 per collection) into interactive NotebookLM environments for easier exploration:

*   **[Extractive Patterns](https://notebooklm.google.com/notebook/a048fa59-64b2-4b13-a98e-0e739bca49d7)**  
    *Focus: Mechanisms that centralize control, obscure labor, or erase context.*
*   **[High-Agency Principles](https://notebooklm.google.com/notebook/f11a7a3b-dfbf-47a1-93e9-ee53683611ba)**  
    *Focus: Theoretical frameworks for refusal, sovereignty, and justice.*
*   **[High-Agency Practices](https://notebooklm.google.com/notebook/bd97ea3f-b516-48d5-b8c6-720ca8e47bca)**  
    *Focus: Applied methods, from co-design to federated data governance.*

---

**Contact:** chifod2025@gmail.com
