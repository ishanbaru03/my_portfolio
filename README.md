# Ishaan Baru — Portfolio

Modern, high-performance developer portfolio showcasing systems profiling research, deterministic backend architectures, and production-grade engineering projects.

🔗 **Live Portfolio:** [https://my-portfolio-ishanbaru03.vercel.app](https://my-portfolio-ishanbaru03.vercel.app) *(or your deployed Vercel link)*  
📄 **Resume:** [Direct Download](./resume.pdf)

---

## 🔬 Systems Research Highlight

### "The Energy Fallacy of Thread Preemption: Empirical Quantification of Context Switching Overhead"
* **Author:** Ishaan Baru · Department of Computer Science & IT, University of Jammu
* **Focus:** Empirical hardware-level profiling of thread scheduling costs using AMD SMU power telemetry and Win32 APIs on an AMD Ryzen 5 5625U.
* **Findings:**
  - **7.49x** execution slowdown (14.75 s vs. 110.50 s) under 20,000 synchronized context switches.
  - **+635.9%** surge in cumulative energy dissipation (55.96 J to 411.86 J).
  - Proved that preemption penalties manifest as temporal energy dissipation (cache/TLB thrashing) rather than elevated instantaneous thermal peaks.

---

## 🛠️ Featured Engineering Projects

### 1. Production-Grade Hybrid RAG Knowledge Engine
* **Stack:** Python, FastAPI, ChromaDB, Redis, Pytest, Docker
* Hybrid retrieval fusing BM25 lexical keyword matching with dense vector embeddings (+28% top-5 recall).
* Redis-cached embeddings and semantic chunking reducing redundant LLM inference calls by 42%.
* Sub-180ms p95 latency with automated Pytest evaluation for retrieval faithfulness.

### 2. Concurrent Transactional Ledger & Idempotent API
* **Stack:** Python, FastAPI, PostgreSQL, Docker, Pytest
* ACID-compliant double-entry ledger backend processing inter-account transfers with zero balance drift.
* Row-level locking (`SELECT ... FOR UPDATE`) and idempotency key verification to eliminate race conditions and double debiting.
* Unit and integration test suites covering concurrent edge cases with >90% branch coverage.

---

## 💻 Technical Stack

* **Languages:** C, C++, Python, SQL, Java, Bash, JavaScript
* **Systems & Architecture:** Linux/POSIX, Win32 API, Multithreading, Thread Affinity & Synchronization, Hardware Telemetry (SMU/typeperf), CPU Cache/TLB Behavior
* **Backend & Data Stores:** FastAPI, PostgreSQL, MySQL, Redis, ChromaDB, FAISS, Docker, RESTful APIs
* **Testing & Tools:** Git, GCC/MinGW, Pytest, Pandas, NumPy, Linux CLI

---

## 🎓 Education & Background

* **M.Tech in Computer Science** — University of Jammu *(Expected 2028)*
* **Master of Computer Applications (MCA)** — MIET Jammu *(2026)*
* **Bachelor of Science (B.Sc)** — IGNOU *(2023)*

---

## 📬 Contact & Links

* **Email:** [ishaanbaru33@gmail.com](mailto:ishaanbaru33@gmail.com)
* **GitHub:** [@ishanbaru03](https://github.com/ishanbaru03)
* **LinkedIn:** [Ishaan Baru](https://linkedin.com)
