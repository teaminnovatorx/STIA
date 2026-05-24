# SENTRI: Sentinel Emergency Network for Treatment & Resistance Intelligence

> **"Turning Invisible Data into Global Health Security"**

SENTRI is an elite, decentralized, and research-driven AI framework designed to bridge the catastrophic "data vacuum" in African Antimicrobial Resistance (AMR) surveillance. By integrating informal health networks—pharmacy kiosks, community workers, and rural healers—into a unified intelligence pipeline, SENTRI provides real-time, localized clinical guidance where connectivity ends.

## The Mission
To empower the "last mile" of healthcare with resource-efficient intelligence, ensuring that no resistance pattern remains hidden and no life is lost to a preventable infection. SENTRI transforms the "Data Vacuum" of Sub-Saharan Africa into a high-fidelity "Sentinel Mesh."

## Technical Foundation (STIA Architecture)
- **Rust Systems Core:** A high-performance, memory-safe data bus utilizing the **Zenoh** protocol for sub-millisecond, decentralized P2P edge synchronization.
- **Tiered Intelligence:**
  - **The Oracle (Tier 1):** NVIDIA Jetson AGX Thor running **OpenMedLLM-70B** for deep clinical reasoning and district-level trend analysis.
  - **The Sentinel (Tier 2):** NVIDIA Jetson Orin Nano Super running **MedGemma-27B** for real-time OCR/ASR and clinic-level guidance.
  - **The Field (Tier 3):** Llama-3.2-3B and Phi-3.5-mini running locally on **Hailo-10H** accelerated handhelds for instant syndromic capture.
- **Hybrid Ingestion:** Industrial-grade OCR/ASR pipelines optimized with **TensorRT** for processing handwritten ledgers and voice consultations.
- **Sovereign RAG:** Localized, vector-embedded clinical knowledge graphs using **Qdrant** with HNSW indexing, grounded in 54 National Essential Medicine Lists (EMLs).

## Project Structure
- `docs/SENTRI_MANIFESTO.md`: The core strategic blueprint and 17-phase roadmap.
- `docs/phases/`: Deep-dive academic research whitepapers (2,500+ words each) for every phase of development.
- `research/SENTRI_RESEARCH_REPORT.md`: Exhaustive evaluation of 2025-2026 medical LLMs and industrial edge hardware.

---
*Developed by **Team InnovatorX** for the UDARA 2026 Initiative. The best is in our hands.*
