# AuraCaptureAI 🌌
### Next-Generation Agentic Document Intelligence Platform

**AuraCaptureAI** is an enterprise-grade, multi-agent Intelligent Document Processing (IDP) platform. It transitions high-volume banking workflows away from rigid legacy template layouts (like OpenText Captiva) and traditional ICR matrix tools (like Parascript) toward self-correcting **Compound AI Systems**.

Developed by a Senior Architect with 14 years of capturing domain expertise and 6 years of Java enterprise engineering, this mono-repository showcases the integration of stateful multi-agent systems, deep enterprise application bridges (Java/Spring Boot/Kafka), and production MLOps loops.

---

## 🏗️ Architectural Framework (The 3-Phase Maturity Model)

### [Phase 1: Aura-Core](./phase1-aura-core/README.md)
*   **Focus:** Image normalization and baseline zero-shot multi-modal extraction.
*   **Legacy Overhaul:** Replaces Captiva Image Clean-up with custom `OpenCV` pipelines and replaces Parascript ICR with Multimodal Vision LLMs.

### [Phase 2: Aura-Agentic](./phase2-aura-agentic/README.md)
*   **Focus:** Multi-Agent consensus and stateful error recovery.
*   **Agent Architecture:** Leverages **LangGraph** to build a cooperative network of specialized Worker Agents (Classifier, Extractor, Auditor) governed by an orchestration state.

### [Phase 3: Aura-Enterprise](./phase3-aura-enterprise/README.md)
*   **Focus:** Core banking integration, high-concurrency event streams, and operational MLOps.
*   **Infrastructure Bridge:** Combines a reactive **Spring Boot WebFlux** ingress engine with **Kafka Event Streaming**, **SAP OData** endpoints, and **Amazon Bedrock** governance wrappers.
