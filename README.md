# GenAI-Powered SAST & DAST Vulnerability Identification Utility

## Overview

This repository contains a unique utility designed to automate the identification of SAST (Static Application Security Testing) and DAST (Dynamic Application Security Testing) vulnerabilities using advanced GenAI models. The primary goal is to significantly reduce manual effort in false positive analysis, streamlining the vulnerability management process for security teams.

---

## Highlights

- **GenAI Automation:**  
  Utilizes local LLMs (e.g., Qwen, Mistral via Ollama) to analyze security scan reports and intelligently identify true vulnerabilities, minimizing manual review.

- **False Positive Reduction:**  
  Achieved up to **80% reduction in manual effort** for false positive triage by leveraging GenAI-driven automation across multiple SAST/DAST report formats.

- **Multi-Tool Compatibility:**  
  Supports ingestion and analysis of reports from various SAST and DAST tools, making it adaptable to diverse security environments.

- **User-Friendly & Extensible:**  
  Designed for easy setup on Windows systems, with clear documentation and modular code for future enhancements.

---

## Hardware Requirements

- **Operating System:** Windows 10/11
- **CPU:** 16 vCPUs (recommended for optimal LLM performance)
- **Memory:** 32 GB RAM (minimum), 64 GB RAM (recommended)
- **Storage:** 100–150 GB free disk space

---

## Software Requirements

- **Python:** v3.6.x or above
- **Python Libraries:**  
  - `requests`  
  - (Other dependencies listed in `requirements.txt`)
- **Ollama:** Local LLM server for running models
- **LLM Models:**  
  - Qwen  
  - Mistral  
  (Download and configure as per Ollama documentation)

---

## Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
