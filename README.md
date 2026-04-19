# xAIDR — Extended AI Detection & Response
## The First Published Runtime A2A Attack Benchmark

**By Delphi Security Inc. | April 2026**

### What is xAIDR?

xAIDR (Extended AI Detection & Response) is a new security 
category for detecting and responding to attacks that occur 
inside agent-to-agent communications at runtime.

Traditional security tools watch what AI agents do at the 
endpoint layer. xAIDR reads what AI agents say to each other — 
intercepting threats inside the message before they execute.

### The Benchmark

- **500 adversarial A2A scenarios** across 12 attack categories
- **94.5% detection accuracy** · **98.4% precision**
- **92.9% recall** across agent hijacking, goal injection, 
  trust escalation, identity spoofing, and MCP poisoning
- Tested against agents running on OpenAI, Anthropic, 
  Gemini, Groq, and Azure simultaneously

### Attack Categories Covered

| Category | Scenarios | Detection Rate |
|---|---|---|
| Prompt Injection via A2A | 87 | 96.2% |
| Agent Identity Spoofing | 63 | 95.1% |
| Goal Hijacking | 71 | 94.8% |
| Trust Escalation | 58 | 93.4% |
| MCP Tool Poisoning | 52 | 94.0% |
| Data Exfiltration via Agent | 67 | 93.7% |
| Unauthorized Delegation | 49 | 92.1% |
| Memory Poisoning | 53 | 91.8% |

### Why This Matters

OWASP ranks Prompt Injection #1 in the LLM Top 10 for 
2025 and 2026. When attacks move from user→LLM to 
agent→agent, existing tools are blind. Neither the source 
agent's LLM vendor nor the destination agent's LLM vendor 
can see the cross-vendor A2A message. Only a vendor-agnostic 
runtime layer can.

This benchmark is the first published evidence that 
runtime A2A detection is both necessary and achievable.

### Live Demo

Try to break our detection at **hack.delphisecurity.ai**  
Nobody has beaten it yet.

### Full Whitepaper

Download at **delphisecurity.ai/research**

### About Delphi Security

AI runtime security for the agentic era.  
proxy.delphisecurity.ai | delphisecurity.ai  
Founded 2026 · Toronto · 3 provisional US patents filed

---

*If you work in AI security research and want to collaborate 
on extending this benchmark, reach out: 
anirudh@delphisecurity.ai*
