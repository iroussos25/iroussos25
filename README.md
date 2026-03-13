# Hi, I'm Giannis Roussos 👋
### AI Implementation Engineer | HealthTech & Mission-Critical Systems

**"From Healthcare to HealthTech: Building production-grade AI systems with ICU-level discipline."**

---

### 🚀 The 90-Day Sprint: 30 Repositories
I don't just use AI; I orchestrate it. In the last 90 days, I transitioned from a clinical professional to a technical builder by shipping over 30 projects, culminating in a full-scale **Clinical Decision Support Platform.** I specialize in high-velocity implementation, turning complex clinical requirements into "zero-fail" code.

---

### 🔬 Featured Project: AI Clinical Context Agent
A full-stack clinical intelligence platform built to simulate hospital-grade decision support.

**[Live Demo](https://ai-clinical-context-agent.vercel.app/) | [Architecture Deep Dive](./docs/RECRUITER_ARCHITECTURE_AND_TRADEOFFS.md)**

#### 🛡️ Engineering Highlights:
* **Resilient AI Orchestration:** Implemented a **Model Fallback Chain** (Gemini 2.5 → Flash Lite → Gemma 3) to ensure 99.9% uptime despite API quotas or latency issues.
* **Clinical RAG Pipeline:** Developed a semantic search engine using **Supabase pgvector** and **768-dim embeddings** with custom chunking logic for unstructured medical notes.
* **Interoperability:** Built a **FHIR R4 Explorer** that pulls live data from HAPI FHIR servers directly into the AI workbench.
* **Security & Ops:** Integrated **Zod-validated request guarding**, **Upstash Redis rate-limiting**, and a structured **Audit Logging** system for HIPAA-aware traceability.
* **Medical Grounding:** Live **PubMed API** integration to cross-reference AI analysis with peer-reviewed literature.

---

### 🛠️ The Stack
* **Core:** Next.js 15/16 (App Router), TypeScript, React 19.
* **AI/Data:** Vercel AI SDK, Google Gemini/Gemma, Supabase (pgvector).
* **Infrastructure:** Redis (Upstash), GitHub Actions (CI/CD), Vitest (Integration Testing).
* **Domain:** HL7 FHIR R4, PubMed eUtils, Clinical Workflow Automation.

---

### 🏥 Why This Matters
As a former **Special Forces Leader** and **ICU Nurse**, I know that in clinical environments, "it mostly works" isn't good enough. I build software that prioritizes:
1.  **Observability:** Real-time metrics and latency benchmarking.
2.  **Explainability:** "Show-your-work" panels with retrieved evidence chunks.
3.  **Reliability:** Fail-fast environment validation and robust error handling.

[**LinkedIn**](https://linkedin.com/in/giannisr) | [**Portfolio**](https://giannisroussos.com) | **Status: US Citizen | NC-Based | Available for HealthTech Engineering Roles**
