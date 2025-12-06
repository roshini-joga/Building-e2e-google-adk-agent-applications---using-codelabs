# README – End-to-End Google ADK Agents Assignment

This repository contains **five AI agents built using the Google Agent Development Kit (ADK)**.  
Each project includes complete code, execution steps, and a video walkthrough link placeholder.

---

## 📁 Repository Structure
```
/
 ├── a-deep-research-leads/
 ├── b-gemini-cli-tool-agent/
 ├── c-mcp-bug-assistant/
 ├── d-code-review-assistant/
 ├── e-ecommerce-agent-alloydb/
 ├── README.md
```

---

## 🔧 Prerequisites
```bash
python -m venv .venv
source .venv/bin/activate      # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

Environment setup:
```bash
export GOOGLE_CLOUD_PROJECT=<your-project-id>
export GOOGLE_LOCATION=us-central1
export GEMINI_MODEL=gemini-2.5-flash
```

Run ADK:
```bash
adk web
# or
adk run agent
```

---

# (a) Deep Research Lead Generation Agent

**Folder:** `a-deep-research-leads/`

This agent performs multi-step deep research: web search → summarization → ranking → CSV output.

### 🎥 Video Link
➡️ Insert your video link here:  
`[Deep Research Agent Video](ADD_LINK_HERE)`

### 📖 References
- Blog: Build a Deep Research Agent with ADK  
- Repo: https://github.com/MagnIeeT/leadGenerationAgentADK

---

# (b) Advanced Tool Agent Using Gemini CLI

**Folder:** `b-gemini-cli-tool-agent/`

This agent wraps the **Gemini CLI as a tool** inside an ADK pipeline.

### 🎥 Video Link
➡️ Insert your video link here:  
`[Gemini CLI Tool Agent Video](ADD_LINK_HERE)`

### 📖 References
- Article: Combine ADK + Gemini CLI + Cloud Run  
- Repo: https://github.com/derrickchwong/gemini-cli-on-adk

---

# (c) MCP Tools-Based Software Bug Assistant

**Folder:** `c-mcp-bug-assistant/`

A debugging assistant that uses MCP Tools to analyze code, logs, and GitHub issues.

### 🎥 Video Link
➡️ Insert your video link here:  
`[MCP Bug Assistant Video](ADD_LINK_HERE)`

### 📖 References
- Codelab: Tools Make an Agent – From Zero to Assistant  
- Repo: https://github.com/google/adk-samples/tree/main/python/agents/software-bug-assistant

---

# (d) Production-Quality Code Review Assistant

**Folder:** `d-code-review-assistant/`

A full code review agent: static analysis → style checks → test generation → fix suggestions.

### 🎥 Video Link
➡️ Insert your video link here:  
`[Code Review Assistant Video](ADD_LINK_HERE)`

### 📖 References
- Codelab: ADK Code Reviewer Assistant  
- Repo: https://github.com/ayoisio/adk-code-review-assistant

---

# (e) E-Commerce Agent with ADK + MCP + AlloyDB

**Folder:** `e-ecommerce-agent-alloydb/`

A production-ready e-commerce assistant supporting product search, ordering, and order tracking.

### 🎥 Video Link
➡️ Insert your video link here:  

[`[E-Commerce Agent Video](ADD_LINK_HERE)`](https://www.youtube.com/watch?v=1Cpc1OoCOMs)

### 📖 References
- Codelab: Sports Shop Agent with ADK + MCP + AlloyDB  
- Repo: https://github.com/mtoscano84/sports-agent-adk-mcp-alloydb

---

# 📚 Codelab & Blog Index

| Agent | Official Resources |
|-------|---------------------|
| Deep Research Agent | Google Cloud Blog; LeadGen sample repo |
| Gemini CLI Tool Agent | Medium article; Gemini CLI ADK repo |
| MCP Bug Assistant | ADK MCP Codelab; ADK Sample Repo |
| Code Review Assistant | Code Reviewer Codelab; Reference GitHub |
| E-Commerce Agent | Sports Agent Codelab; AlloyDB sample repo |

---

# 🎥 Video Upload Checklist

| Agent | Video Link |
|-------|------------|
| Deep Research LeadGen | ADD_LINK_HERE |
| Gemini CLI Tool Agent | ADD_LINK_HERE |
| MCP Bug Assistant | ADD_LINK_HERE |
| Code Review Assistant | ADD_LINK_HERE |
| E-Commerce Agent | ADD_LINK_HERE |

---

# 🏁 Conclusion

This repository demonstrates advanced agent engineering concepts using:

- Google ADK  
- Multi-agent pipelines  
- Gemini CLI as a tool  
- MCP Toolbox  
- AlloyDB integrations  

These five agents collectively form a **production-quality agent suite** covering research, automation, debugging, code review, and e-commerce.

