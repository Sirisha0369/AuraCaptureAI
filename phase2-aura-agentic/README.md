# Phase 2: Aura-Agentic 🤖
### Stateful Multi-Agent Orchestration & Human-in-the-Loop Validation

Phase 2 replaces traditional linear routing scripts with a cyclical, autonomous multi-agent graph capable of verifying its own work.

### 🛠️ Architecture Drivers
*   **Supervisor Topology:** Built via **LangGraph**, routing tasks between independent agent nodes dynamically depending on processing requirements.
*   **Mathematical Auditing:** Specialized Auditor Agents validating logical business constraints (e.g., balance sheet cross-checks or compliance validations).
*   **Stateful Interruption:** Real-time state preservation via checkpointers to halt graph execution and trigger a `PENDING_OPERATOR_REVIEW` event when confidence scores fail risk profiles.
