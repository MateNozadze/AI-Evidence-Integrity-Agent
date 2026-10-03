<!-- Language Switcher Bar -->
<p align="right">
  <a href="#-english"><b>English</b></a> 
</p>

---

<a name="-english"></a>
# 🇬🇧 English

## AI Evidence Integrity Agent (IT Forensics Demo)

An autonomous AI Agent demonstration built with **LangGraph** and **Mistral AI** tailored for **IT Forensics & Threat Analysis**. The agent performs automated evidence collection by interfacing with real security threat intelligence APIs, demonstrates text-based prompt injection attacks analogous to computer vision FGSM attacks, and integrates Human-in-the-Loop (HITL) error correction mechanisms.

---

### 🔑 Key Features

* **Real-time Threat Intelligence Integration:** Communicates with live endpoints including **AbuseIPDB** and **VirusTotal** APIs to evaluate IP reputation, query file hashes, and inspect system log entries.
* **Adversarial Prompt Injection (Text-based FGSM Analogy):** Demonstrates how malicious, adversarial text inputs can mislead LLM reasoning logic, mimicking the Fast Gradient Sign Method (FGSM) perturbation concept used against deep vision models.
* **Human-in-the-Loop (HITL) Control:** Leverages LangGraph interrupt mechanics to enable security analysts to review, override, and assist the AI agent during critical or manipulated analysis flows.
* **Stateful Conversational Memory:** Maintains investigation context across multiple steps using `MemorySaver` checkpointers.

---

### 🛠️ Tech Stack

* **Frameworks:** `LangGraph`, `LangChain`
* **LLM Provider:** `Mistral AI` (`mistral-small-latest`)
* **Language & Runtime:** Python 3.12+ / Google Colab
* **APIs & Tools:** AbuseIPDB API, VirusTotal API, Custom Forensic Log Analyzers

---

### 📦 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/MateNozadze/AI-Evidence-Integrity-Agent.git](https://github.com/MateNozadze/AI-Evidence-Integrity-Agent.git)
   cd AI-Evidence-Integrity-Agent
