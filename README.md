<a href="https://rexxar.xyz"><img src="assets/hero-cdb5eac8.svg" width="100%" alt="Richard Rexxar, Senior AI Engineer in Prague. An ASCII portrait in a red oni mask looks around next to a terminal that types whoami, then ship --to production, and ends with live at rexxar.xyz."></a>

<p align="center">
  <a href="https://rexxar.xyz"><b>rexxar.xyz</b></a> &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/egor-suslin-data-science">LinkedIn</a> &nbsp;·&nbsp;
  <a href="mailto:riharex420@gmail.com">riharex420@gmail.com</a>
</p>

I build LLM applications and AI agents and take them all the way to production: architecture, backend, frontend, CI/CD, security, and the risk assessments a regulated company asks for before go-live. 8 years of Python, AI since 2021, across insurance, pharma, banking and energy.

Most of that work is private or under NDA, so what you see here is forks and experiments. The case studies are on [rexxar.xyz](https://rexxar.xyz/#cases).

### What I build

<p align="center">
  <a href="https://rexxar.xyz/#build"><img src="assets/tile-speech-df746de5.svg" width="32%" alt="Voice AI: ASCII sound bars pulsing like a voice waveform."></a>
  <a href="https://rexxar.xyz/#build"><img src="assets/tile-documents-fd192d24.svg" width="32%" alt="Document AI: a scan line moves down an ASCII page and boxes the fields it extracts."></a>
  <a href="https://rexxar.xyz/#build"><img src="assets/tile-agents-e32caf31.svg" width="32%" alt="Agents: messages travel between a central agent and six others."></a>
</p>
<p align="center">
  <a href="https://rexxar.xyz/#build"><img src="assets/tile-security-719b3a84.svg" width="32%" alt="AI security: a radar sweep inside an ASCII shield with a lock."></a>
  <a href="https://rexxar.xyz/#build"><img src="assets/tile-production-5ac2b28d.svg" width="32%" alt="Production: packets ride a pipeline into three server racks with blinking lights and a heartbeat line."></a>
</p>

- **Agentic AI**: multi-agent workflows, tool calling, MCP, and identity, policy and audit layers for AI agents that make payments
- **RAG and document AI**, including medical document analysis
- **Voice AI**: speech-to-text, text-to-speech and live translation for customer support
- **AI security and compliance**: guardrails, access control, the EU AI Act, security and risk assessments
- **Production**: Kubernetes, Terraform, Docker and CI/CD on Azure, Google Cloud and DigitalOcean

### Case study: a control plane for AI agents that spend money

<a href="https://rexxar.xyz/#cases"><img src="assets/diagram-payments-0f5131f3.svg" width="100%" alt="Architecture diagram in ASCII. An AI agent's payment passes an SDK guard, an identity check and a policy engine. Allowed payments go to the payment rails and the audit log; payments over the limit wait for human approval first. A packet travels each path and boxes light up as it arrives."></a>

Agents carry a verifiable identity, and a policy engine checks budgets and allow lists before anything executes. Payments over a threshold wait for a person, and one audit ledger covers card and crypto, with an EU AI Act export. [More case studies](https://rexxar.xyz/#cases).

### Stack

```text
lang    python · typescript · go · rust · sql
ai      langgraph · langchain · mcp · rag · evals
models  azure openai · vertex ai · claude · gemini · ollama · whisper
web     fastapi · react · next.js · node.js · astro
infra   kubernetes · terraform · docker · nginx · ci/cd · azure · gcp · digitalocean
data    postgresql · mongodb · redis
```

<sub>Everything above is plain ASCII. The portrait's characters are picked by shape from a photo and a depth map, with the oni mask painted on before the conversion; the tiles and the diagram are recorded from the engines behind <a href="https://rexxar.xyz">rexxar.xyz</a>, where they run live.</sub>
