
System Flow

Raw User Input
→ Reality Filter
→ Intent Router
→ Observer Protocol
→ Decode Policy
→ Guardrail Layer
→ Bridge State Builder
→ F-Array / State Packet
→ LLM / Local Fallback / Replay / UI

Mermaid Diagram

flowchart TD
A[Raw User Input] --> B[Reality Filter]
B --> C[Intent Router]
C --> D[Observer Protocol]
D --> E[Decode Policy]
E --> F[Guardrail Layer]
F --> G[Bridge State Builder]
G --> H[F-Array / State Packet]
H --> I[LLM]
H --> J[Local Fallback]
H --> K[Replay / Validation]
H --> L[UI / API Output]
