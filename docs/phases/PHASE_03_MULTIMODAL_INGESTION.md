# PHASE 03: MULTIMODAL INGESTION RESEARCH
## Comparative Analysis of Data Capture Technologies in Resource-Limited Settings

### 1. Ingestion Modality Matrix

| Modality | Target Device | User Skill Level | Research Feasibility (2025) |
| :--- | :--- | :--- | :--- |
| **USSD/SMS** | Feature Phone (Nokia 105) | Low | **High** (Universal availability) |
| **Camera OCR** | Smartphone (Android) | Medium | **High** (Trained on handwritten health ledgers) |
| **Voice (ASR)** | All (via Voice-to-Text) | Very Low | **Medium** (High dialect variability) |
| **Web PWA** | Smartphone (iOS/Android) | Medium | **High** (Zero-install deployment) |

### 2. The OCR Frontier: Scanning the Unstructured
A critical research goal is the digitization of handwritten CHW ledgers. 
- **Challenge:** Variations in handwriting, poor lighting, and low-resolution cameras.
- **Solution:** Deployment of **LayoutLMv3** or similar Transformer-based OCR models fine-tuned on African clinical record templates. 

### 3. USSD Architecture: The "Invisible" UI
Research into USSD (Unstructured Supplementary Service Data) shows it remains the most resilient data channel in rural Africa. 
- **Finding:** 90% of mobile users in SSA are comfortable with `*#` menus for mobile money (M-Pesa).
- **Design:** Mapping clinical symptoms to single-digit codes (e.g., `1: Cough`, `2: Fever`, `3: Diarrhea`) to minimize data entry errors.

### 4. Multilingual ASR (Voice-to-Data)
Voice ingestion is essential for inclusivity. Research targets the 12 major languages of the AU.
- **Goal:** Using models like **Whisper v3-large** (distilled for edge) to transcribe patient consultations into structured ICD-11 codes.

---
*Research by Team InnovatorX.*
