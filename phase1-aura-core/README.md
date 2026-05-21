# Phase 1: Aura-Core ⚙️
### Core Image Processing & Zero-Shot Multimodal Extraction

Phase 1 focuses on eliminating the technical debt associated with writing and maintaining thousands of static document layout templates.

### 🛠️ Architecture Drivers
*   **Deterministic Ingestion:** An automated directory polling module mimicking the *Captiva Input Manager*.
*   **Image Alignment Pipeline:** Custom OpenCV scripts ensuring precise image normalization, de-noising, and auto-deskewing prior to extraction blocks.
*   **Vision-Language Parsing:** Structuring multi-modal payloads via `Pydantic` and `Instructor` libraries to map unstructured or handwritten forms into type-safe JSON.
