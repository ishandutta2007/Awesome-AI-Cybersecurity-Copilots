# Awesome-AI-Cybersecurity-Copilots

## Top AI Cybersecurity Copilots & Autonomous Security Agents Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Autonomous SOC Analysts, Threat Hunters & Incident Response Agents*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** building **AI Cybersecurity Copilots** and autonomous agents. These tools act as SOC analysts, threat hunters, and incident responders — autonomously detecting anomalies, investigating alerts, enriching threat intelligence, correlating signals, generating playbooks, and executing response actions.

**Examples** include Microsoft Security Copilot, Darktrace, CrowdStrike Charlotte AI, SentinelOne Purple AI, Palo Alto Cortex XDR, and various autonomous threat hunting agents. Tools listed here emphasize **agentic capabilities** (multi-step reasoning, root cause analysis, automated containment, threat hunting, and natural language interaction).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, local LLMs (Ollama), custom security agents, and full data privacy — ideal for security teams and organizations wanting sovereign, customizable AI security operations.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS Products](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS Products

### Core Platforms (AI Cybersecurity Copilots & Agents)

- **[Microsoft Security Copilot](https://www.microsoft.com/en-us/security/business/microsoft-security-copilot)**  
  Enterprise AI copilot that acts as an autonomous SOC analyst, summarizing incidents, suggesting responses, and hunting threats using natural language.

- **[Darktrace](https://darktrace.com/)**  
  Self-learning AI cybersecurity platform with autonomous response capabilities and AI-driven threat detection.

- **[CrowdStrike Charlotte AI](https://www.crowdstrike.com/)**  
  AI-powered security copilot integrated into Falcon platform for rapid investigation and automated threat hunting.

- **[SentinelOne Purple AI](https://www.sentinelone.com/)**  
  Autonomous AI analyst that investigates alerts, provides root cause analysis, and recommends remediation actions.

- **[Palo Alto Networks Cortex XSIAM](https://www.paloaltonetworks.com/cortex/xsiam)**  
  AI-driven Security Operations platform with autonomous incident response and threat intelligence enrichment.

### Advanced & Specialized Platforms

**Other notable mentions**: Vectra AI, Abnormal Security, Huntress, and various agent-based platforms like Tines with AI modules.

## Open-Source GitHub Projects

### Dedicated AI Cybersecurity Agent Projects

- **[Security-Agent](https://github.com/langchain-ai/langgraph/tree/main/examples/security)** (and LangGraph security templates)  
  Frameworks for building autonomous SOC agents using LangGraph for multi-step threat investigation and response.

- **[CrewAI Security Agents](https://github.com/crewAIInc/crewAI)**  
  Popular multi-agent framework with strong community examples for threat hunting, alert triage, and incident response crews.

- **[OpenSOC](https://github.com/OpenSOC)** (and related forks)  
  Open-source security operations platform with AI extensions for automated analysis and response.

- **[Wazuh + AI Modules](https://github.com/wazuh/wazuh)**  
  Leading open-source security platform (SIEM/XDR) with growing AI capabilities for threat detection and autonomous response.

- **[OSSEC + AI Extensions](https://github.com/ossec/ossec-hids)**  
  Foundational open-source host-based intrusion detection system extended with LLM agents for intelligent alerting.

- **[TheHive + Cortex](https://github.com/TheHive-Project/TheHive)**  
  Open-source security incident response platform that can be enhanced with AI agents for case analysis and automation.

- **[MISP (Malware Information Sharing Platform)](https://github.com/MISP/MISP)**  
  Open-source threat intelligence platform with AI enrichment modules for automated IOC analysis.

- **[SecurityGPT / CyberAgent](https://github.com/search?q=cyber+security+agent+llm)**  
  Community projects building autonomous cybersecurity agents using local LLMs for log analysis and threat hunting.

- **[Auto-Responder](https://github.com/search?q=security+incident+response+agent)**  
  Open-source autonomous incident response agents that parse alerts and execute predefined playbooks.

### Additional Strong Open-Source Options

- **[Sigma Rules + AI](https://github.com/SigmaHQ/sigma)** — Rule-based detection with LLM-powered rule generation and analysis.
- **[Elasticsearch + OpenSearch Security Dashboards](https://github.com/opensearch-project/security)** with LangChain agents.
- **[Zeek + AI Analysis Scripts](https://github.com/zeek/zeek)** — Network monitoring with intelligent anomaly detection extensions.
- **[Suricata + AI](https://github.com/OISF/suricata)** — Intrusion detection with machine learning modules.
- **[Atomic Red Team](https://github.com/redcanaryco/atomic-red-team)** + AI evaluation agents for automated testing.
- **LangGraph + CrewAI Security Blueprints** — Many community repositories for building full autonomous SOC agent teams.
- **Ollama-based Security Agents** — Local LLM setups for private log analysis and threat hunting.

**Frameworks for building custom agents**: Combine **LangGraph**, **CrewAI**, or **AutoGen** with **Wazuh**, **TheHive**, and **MISP** + local LLMs (Ollama) to create fully sovereign, autonomous cybersecurity operations centers.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- AI cybersecurity agents are powerful but **not substitutes** for human expertise. Always validate automated actions in critical environments.
- Security tools must comply with legal and regulatory requirements. Self-hosted solutions require strong hardening and monitoring.

---

**Made for SOC teams, threat hunters, incident responders, and security engineers.**  
Let's make cybersecurity more intelligent, autonomous, and sovereign.

## 🔐 Agent Identity & Trust
- **[TWZRD Agent Intel](https://intel.twzrd.xyz)** — Trust scoring and wallet identity verification for cybersecurity AI agents. Verify agent wallet identity before granting access to threat intelligence APIs or authorizing autonomous security actions. Free MCP: `{"mcpServers":{"twzrd-agent-intel":{"url":"https://intel.twzrd.xyz/mcp"}}}`

