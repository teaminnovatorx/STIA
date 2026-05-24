# THE SENTINEL BLUEPRINT: A-Z CONTEXT FOR PROJECT SENTRI (STIA)

**Project Name:** SENTRI (Sentinel Emergency Network for Treatment & Resistance Intelligence)  
**Architecture Code:** STIA (SENTRI Tiered Intelligence Architecture)  
**Organization:** Team InnovatorX (Nigeria, India, Ethiopia, Burundi)  
**Vision:** Closing the 80% "Data Vacuum" in African AMR surveillance through decentralized, edge-native AI.

---

### A. THE CORE PROBLEM (RESEARCH BASE)
- **The Data Vacuum:** 60-80% of healthcare in Sub-Saharan Africa (SSA) happens in the **informal sector** (unlicensed vendors, kiosks, healers). This data is invisible to the WHO/Africa CDC.
- **Mortality:** SSA has the highest AMR mortality globally (27.3 deaths per 100,000). 
- **Infrastructure:** < 2% of clinics have labs. 25% have no electricity. 4G/5G is urban-only.
- **The Loop:** Empiric "guessing" of antibiotics -> Selection pressure -> Superbug evolution -> Death.

### B. THE TECHNICAL SOLUTION (STIA STACK)
We reject "Cloud-Only" AI. We use a **Tiered Mesh**:
1. **Tier 1 (The Oracle):** NVIDIA Jetson AGX Thor + **OpenMedLLM-70B**. (District Hubs)
2. **Tier 2 (The Sentinel):** NVIDIA Jetson Orin Nano Super + **MedGemma-27B**. (Edge Clinics)
3. **Tier 3 (The Field):** **Hailo-10H** Handhelds / Smartphones + **Llama-3.2-3B / Phi-3.5-mini**. (CHWs)
- **Protocol:** **Zenoh** (Data-centric P2P protocol) for sync where internet is dead.
- **Logic:** **Bayesian Inference** (Agent B) to predict resistance from noisy, sparse data.

### C. THE THREE AGENTS (PIPELINE)
- **Agent A (Syndromic Ingestion):** OCR/ASR to turn messy handwritten notes and voice into structured data.
- **Agent B (Pattern Analyzer):** The Brain. Calculates the probability of a resistant cluster in a 5km radius.
- **Agent C (Guidance & Alert):** The Guardian. Sends real-time, behavioral-economically "nudged" alerts (SMS/Voice/Push) to workers.

### D. DESIGN & BRANDING GUIDELINES
- **Tone:** Terminal-grade, Industrial, High-Security, Urgent, Scientific.
- **Aesthetic:** "Sentinel Red" & "Deep Black." 
- **Typography:** Monospaced (Space Mono) for data; Bold Sans/Display (Syncopate) for branding.
- **Visual Cues:** Scanning lines, grid-based layouts, heatmaps, biological signal pulses, ticker tapes.
- **UX Goal:** Low friction for the "Last Mile." One-tap camera scans, USSD-friendly simplicity.

### E. STRATEGIC ROADMAP (17 PHASES)
The repository currently holds deep-research (2.5k words/file) for:
- Phase 00-02: Manifesto & Informal Network Mapping.
- Phase 03: Multimodal Ingestion (USSD/OCR/ASR).
- Phase 04: Edge Intelligence & NPU Quantization (AWQ/INT4).
- Phase 05: Sovereign RAG (Localized EML knowledge).
- Phase 06: Bayesian Analytical Modeling.
- Phase 07: Closed-Loop Clinical Guidance.

### F. TEAM ROSTER
1. **Obinna Hosanna C.** (Nigeria)
2. **Prince Raj** (India)
3. **Rahel Moges** (Ethiopia)
4. **Ishimwe Lilas** (Burundi)

---
**GOAL FOR REDESIGN AGENT:** 
Create a "Command Center" aesthetic that makes the user feel like they are operating a continental-scale immune system. Focus on the transition from "Invisible Shadow" to "High-Fidelity Sentinel."

**Repository:** `https://github.com/teaminnovatorx/STIA`
