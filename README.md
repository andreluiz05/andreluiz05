<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Geist+Mono&size=22&duration=3000&pause=1000&color=10B981&center=true&vCenter=true&width=600&lines=andreluiz05%40github%3A~%24+whoami;Andr%C3%A9+Luiz%2C+Fullstack+Engineer;Building+with+TypeScript%2C+Java%2C+Python%2C+Flutter;AI%2FML+%7C+Cloud+%7C+DevTools" alt="Typing SVG" />
</p>

<p align="center">
  <img src="./perfil.jpg" width="120" height="120" alt="André Luiz" />
</p>

<h1 align="center">André Luiz</h1>

<p align="center"><code>Fullstack Engineer · AI/ML Enthusiast · DevTools Builder</code></p>

<p align="center">
  <a href="mailto:andreluizdesantanasilva123@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://wa.me/5531998235716"><img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp" /></a>
</p>

---

## ⚡ `system.info()`

```yaml
username: andreluiz05
name: "André Luiz"
role: "Fullstack Engineer"
focus:
  - "TypeScript/React/Next.js Ecosystem"
  - "Java/Spring Boot Microservices"
  - "Python/FastAPI + AI/ML"
  - "Flutter Cross-Platform"
  - "Cloud Native (Oracle Cloud, Firebase, MongoDB, MySQL)"
  - "DevTools: Antigravity, opencode, Claude Code"
location: "São Paulo, BR"
timezone: "America/Sao_Paulo (UTC-3)"
status: "Accepting freelance/consulting"
uptime: "6+ years in production"
```

---

## 🛠 `stack.list --verbose`

### **Frontend & Mobile**

```
████████████████████  React / Next.js 14+ (App Router, RSC, Server Actions)
███████████████████░  TypeScript (Strict Mode, Type-Level Programming)
██████████████████░░  Flutter (Riverpod, GoRouter, Custom Painters)
████████████████░░░░  Tailwind CSS v4 / CSS Modules / Styled Components
█████████████░░░░░░░  Framer Motion / GSAP (Scroll-triggered, Micro-interactions)
██████████░░░░░░░░░░  Radix UI / shadcn/ui / Headless UI (Accessible Primitives)
```

### **Backend & APIs**

```
████████████████████  Node.js / Fastify / Hono (Edge-Ready, Type-Safe)
███████████████████░  Java 21 / Spring Boot 3 (Virtual Threads, GraalVM Native)
██████████████████░░  Python 3.12+ / FastAPI (Pydantic v2, Async, OpenAPI)
██████████████░░░░░░  tRPC / GraphQL (Codegen, Subscriptions, Federation)
██████████░░░░░░░░░░  REST / gRPC / WebSockets (Real-time, Bidirectional)
```

### **Data & AI/ML**

```
███████████████████░  PostgreSQL / MySQL (Prisma, Drizzle, TypeORM, JPA/Hibernate)
████████████████░░░░  MongoDB (Aggregation, Change Streams, Atlas)
██████████████░░░░░░  Firebase (Auth, Firestore, Functions, Hosting, Extensions)
█████████████░░░░░░░  Oracle Cloud (ATP, OKE, Functions, Analytics)
███████████░░░░░░░░░  Vector DBs (pgvector, Pinecone, Weaviate) + RAG Pipelines
██████████░░░░░░░░░░  LLM Integration (OpenAI, Anthropic, Local via Ollama/vLLM)
████████░░░░░░░░░░░░  LangChain / LangGraph / PydanticAI (Agent Orchestration)
```

### **DevOps & Tooling**

```
███████████████████░  Docker / Docker Compose / BuildKit (Multi-arch, Cache Mounts)
██████████████████░░  Kubernetes (Helm, Kustomize, ArgoCD, Operators)
████████████████░░░░  CI/CD: GitHub Actions / GitLab CI (Matrix, Reusable Workflows)
█████████████░░░░░░░  Terraform / OpenTofu (Modules, State, Policy as Code)
████████████░░░░░░░░  Observability: OpenTelemetry, Grafana, Loki, Tempo, Prometheus
██████████░░░░░░░░░░  Antigravity / opencode / Claude Code (AI-Native Dev Loop)
████████░░░░░░░░░░░░  Turborepo / Nx (Monorepo, Remote Caching, Affected Graph)
```

---

## 📊 `git.stats --since="2018"`

| Metric | Value | Trend |
|--------|-------|-------|
| **Commits** | 3,847+ | ↗️ +12% YoY |
| **Repositories** | 84 (42 public) | ↗️ +8 |
| **Lines Changed** | 420k+ | — |
| **Languages** | 12 active | TypeScript ████████████ 38% |
| | | Java ██████████░░ 28% |
| | | Python ████████░░░░ 19% |
| | | Dart ██████░░░░░░ 11% |
| | | Other ░░░░░░░░░░ 4% |
| **PRs Merged** | 312 | ↗️ |
| **Issues Closed** | 187 | ↗️ |
| **Code Reviews** | 420+ | ↗️ |

```bash
$ gh api user --jq '.contributionsCollection.contributionCalendar.totalContributions'
4123
```

---

## 🚀 `projects.featured --limit=6`

### **1. `neural-cli`** — *AI-Native Terminal Assistant*

```bash
$ neural --help
Usage: neural <command> [options]

Commands:
  ask       Query LLMs with context (files, git, stdout)
  agent     Spawn autonomous coding agents
  index     Embed codebase for semantic search
  diff      AI-powered code review

Options:
  --model     claude-opus-4 | gpt-4o | local (default: claude-opus-4)
  --tools     bash, edit, grep, glob, task, webfetch, mcp
  --stream    Stream tokens in real-time
```

**Stack:** TypeScript, Node.js, Ink (React for CLI), MCP, SQLite (vec0)  
**Status:** 🟢 Active • ⭐ 234 • 🍴 18

---

### **2. `spring-ai-starter`** — *Production-Ready Spring AI Template*

```java
@SpringBootApplication
@EnableAiAgents
public class Application {
    public static void main(String[] args) {
        SpringApplication.run(Application.class, args);
    }
}

// Auto-configured: VectorStore, ChatModel, EmbeddingModel, ToolCallbackProvider
// Features: RAG, Function Calling, Structured Output, Observability (Micrometer)
```

**Stack:** Java 21, Spring Boot 3.3, Spring AI 1.0, PostgreSQL + pgvector, GraalVM  
**Status:** 🟢 Active • ⭐ 567 • 🍴 43

---

### **3. `flutter-ai-toolkit`** — *On-Device AI for Flutter*

```dart
// Run LLMs locally on mobile (no cloud)
final model = await LlmModel.fromAsset('assets/models/gemma-2b-it-q4.gguf');
final session = model.createSession();
final stream = session.stream('Explain quantum entanglement');
await for (final chunk in stream) { print(chunk); }
// Works offline • 2.3GB model • 15 tok/s on Snapdragon 8 Gen 3
```

**Stack:** Flutter, llama.cpp (FFI), GGUF, Riverpod, Isolate Compute  
**Status:** 🟡 Beta • ⭐ 189 • 🍴 12

---

### **4. `fastapi-rag-template`** — *RAG Pipeline with Observability*

```python
# app/rag/pipeline.py
class RagPipeline:
    def __init__(self, vector_store: VectorStore, llm: LLM):
        self.retriever = HybridRetriever(vector_store, bm25_weight=0.3)
        self.generator = AnswerGenerator(llm, citations=True)
        self.tracer = get_tracer(__name__)

    async def ask(self, query: str, ctx: Context) -> Answer:
        with self.tracer.start_as_current_span("rag.ask") as span:
            docs = await self.retriever.search(query, k=8)
            return await self.generator.generate(query, docs, ctx)
```

**Stack:** FastAPI, Pydantic v2, LangGraph, pgvector, OpenTelemetry, Grafana  
**Status:** 🟢 Production • ⭐ 412 • 🍴 31

---

### **5. `oracle-cloud-operator`** — *Kubernetes Operator for OCI*

```yaml
# CRD: OracleCloudDatabase
apiVersion: oci.oracle.com/v1alpha1
kind: AutonomousDatabase
metadata:
  name: prod-db
spec:
  compartmentId: "ocid1.compartment.oc1.."
  cpuCoreCount: 4
  dataStorageSizeInTBs: 1
  isFreeTier: false
  adminPasswordSecretRef:
    name: db-credentials
    key: password
```

**Stack:** Go, Operator SDK (Kubebuilder), OCI Go SDK, Helm, Prometheus Operator  
**Status:** 🟢 Active • ⭐ 87 • 🍴 9

---

### **6. `antigravity-workflows`** — *AI-Native Dev Automation*

```yaml
# .antigravity/workflows/pr-review.yml
name: "AI Code Review"
on: [pull_request]
jobs:
  review:
    runs-on: antigravity-runner
    steps:
      - uses: antigravity/actions/checkout@v4
      - uses: antigravity/actions/claude-code@v2
        with:
          prompt: |
            Review this PR for: security, performance, architecture.
            Output: JSON with severity, file, line, suggestion.
          model: claude-opus-4
          tools: [read, grep, glob, bash]
      - uses: antigravity/actions/annotate@v1
```

**Stack:** TypeScript, GitHub Actions, Antigravity SDK, Claude Code SDK  
**Status:** 🟢 Active • 🔧 Internal Tool (adopted by 3 teams)

---

## 🧪 `experiments.current`

```bash
$ ls -la ~/labs/
drwxr-xr-x  12 andre  staff   384 Jul 15 09:32 .
drwxr-xr-x   8 andre  staff   256 Jul 10 14:22 ..
drwxr-xr-x   5 andre  staff   160 Jul 14 22:11 local-llm-benchmark/    # GGUF quantization comparison
drwxr-xr-x   6 andre  staff   192 Jul 12 18:45 agent-memory-mesh/     # Persistent agent memory (pgvector + Redis)
drwxr-xr-x   4 andre  staff   128 Jul 08 11:30 wasm-sandbox/          # Secure code execution (Wasmtime + Wasi)
drwxr-xr-x   7 andre  staff   224 Jul 05 09:15 mcp-registry/          # Private MCP server registry
drwxr-xr-x   3 andre  staff    96 Jun 28 16:40 cli-plugin-system/     # Dynamic plugin loader for CLIs
```

---

## 📈 `activity.heatmap --year=2024`

```
     Jan Feb Mar Apr May Jun Jul Aug Sep Oct Nov Dec
Su  ░░░ ░░░ ░░░ ░░░ ░░░ ░░░ ░░░ ░░░ ░░░ ░░░ ░░░ ░░░
Mo  ███ ███ ███ ███ ███ ███ ███ ███ ███ ███ ███ ███
Tu  ███ ███ ███ ███ ███ ███ ███ ███ ███ ███ ███ ███
We  ███ ███ ███ ███ ███ ███ ███ ███ ███ ███ ███ ███
Th  ███ ███ ███ ███ ███ ███ ███ ███ ███ ███ ███ ███
Fr  ███ ███ ███ ███ ███ ███ ███ ███ ███ ███ ███ ███
Sa  █░░ █░░ █░░ █░░ █░░ █░░ █░░ █░░ █░░ █░░ █░░ █░░
```
**Legend:** ███ Heavy (10+) · ██░ Medium (5-9) · █░░ Light (1-4) · ░░░ None

---

## 🎯 `focus.current --priority=high`

```bash
$ focus list --active
┌─────────────────────────────────────────────────────────────────┐
│ ▸ [P0] neural-cli v2.0 — Plugin architecture + MCP marketplace  │
│ ▸ [P1] spring-ai-starter — OAuth2/OIDC + Multi-tenancy          │
│ ▸ [P1] flutter-ai-toolkit — Gemma 2 2B/9B + Function Calling    │
│ ▸ [P2] antigravity-workflows — Team adoption + Metrics dashboard│
│ ▸ [P3] Technical Writing: "Building AI-Native DevTools" series  │
└─────────────────────────────────────────────────────────────────┘
```

---

## 🤝 `collab.open --mode=async`

```yaml
available_for:
  - "Freelance/Contract (Fullstack, AI/ML, Cloud)"
  - "Technical Advisory (Architecture, Stack Selection, Team Scaling)"
  - "Code Review / Audit (Security, Performance, Maintainability)"
  - "Mentoring (Junior → Senior, Career Transition)"
  - "Open Source Collaboration (Issues, PRs, RFCs)"

preferred_communication:
  - "Async first (GitHub Issues, Discussions, Email)"
  - "Sync when needed (Google Meet, Discord, WhatsApp)"
  - "Email: andreluizdesantanasilva123@gmail.com"
  - "WhatsApp: +55 31 99823-5716"
  - "Timezone: UTC-3 (São Paulo)"

rate_card: "Available on request (project-based or retainer)"
```

---

## 📜 `certifications.verified`

| Cert | Issuer | Year | Status |
|------|--------|------|--------|
| **Oracle Cloud Infrastructure Architect Professional** | Oracle | 2024 | ✅ Active |
| **AWS Solutions Architect Associate** | Amazon | 2023 | ✅ Active |
| **CKAD: Certified Kubernetes Application Developer** | CNCF | 2023 | ✅ Active |
| **Google Cloud Professional Data Engineer** | Google | 2022 | 🔄 Renewing |
| **Spring Professional Certification** | VMware | 2022 | ✅ Active |

---

## 🎓 `education.history`

```bash
$ cat education.json | jq '.[] | "\(.degree) @ \(.institution) (\(.year))"'
"M.Sc. Computer Science (Distributed Systems) @ USP (2020)"
"B.Sc. Computer Engineering @ POLI-USP (2017)"
```

---

## 💬 `shell --interactive`

```bash
andreluiz05@github:~$ echo "Thanks for visiting!" | lolcat --seed=42
Thanks for visiting!

andreluiz05@github:~$ fortune -s
"Code is read more than it is written. Optimize for the reader."
                                    — Guido van Rossum

andreluiz05@github:~$ uptime
 09:42:15 up 6 years, 247 days, 14:32,  3 users,  load average: 0.23, 0.31, 0.28

andreluiz05@github:~$ exit
Connection to github.com closed.
```

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,10B981,06B6D4,8B5CF6&height=120&section=footer&animation=twinkling&fontAlignY=35&desc=Built%20with%20%E2%9D%A4%20using%20Neovim%2C%20Claude%20Code%2C%20opencode%2C%20Antigravity&descAlignY=55&descSize=14" alt="Footer" />
</p>

<p align="center"><code>Last updated: 2025-01-15 09:42 UTC</code> • <code>Profile README v3.2.1</code> • <code>Generated via <a href="https://github.com/andreluiz05/profile-generator">profile-generator</a></code></p>