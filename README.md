# Awesome-Prompt-Security-Platform

## Top Prompt Security Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Prompt Injection Defense, Jailbreak Prevention, LLM Guardrails, Input/Output Scanning & AI Runtime Security*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Prompt Security**. These tools detect and block prompt injection, jailbreaks, data leakage, toxic content, and other risks in LLM inputs and outputs, often acting as runtime guardrails or AI firewalls.



**Examples** include Prompt Security, Lakera, Aporia, Protect AI, HiddenLayer, CalypsoAI, Noma Security, Pangea, Zenity, and LayerX AI Security (the category leaders).



**Open-source emphasis**: Prompt and LLM security has strong open-source options. **NVIDIA NeMo Guardrails**, **LLM Guard**, **Guardrails AI**, and related projects provide programmable and scanner-based protection. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Prompt Security](https://www.prompt.security/)**  

  Platform focused on securing generative AI applications against prompt-based attacks and related risks.



- **[Lakera](https://www.lakera.ai/)**  

  Leading prompt injection and jailbreak defense platform (Lakera Guard) with strong runtime protection and threat intelligence.



- **[Aporia](https://www.aporia.com/)**  

  ML observability and guardrails platform that includes runtime protection and monitoring for AI models.



- **[Protect AI](https://www.protectai.com/)**  

  MLSecOps platform (now part of broader security ecosystems) offering model scanning, runtime guardrails, and AI supply-chain security.



- **[HiddenLayer](https://hiddenlayer.com/)**  

  AI security platform focused on model protection, adversarial threats, and runtime defenses for machine learning systems.



- **[CalypsoAI](https://www.calypsoai.com/)**  

  AI security and control platform providing guardrails and governance for enterprise generative AI deployments.



- **[Noma Security](https://www.noma.security/)**  

  AI security solutions addressing risks in generative AI applications and models.



- **[Pangea](https://pangea.cloud/)**  

  Security platform that includes AI and prompt-related security services among its broader offerings.



- **[Zenity](https://zenity.io/)**  

  Security platform focused on low-code/no-code and AI application risks, including governance and protection.



- **[LayerX AI Security](https://layerxsecurity.com/)**  

  Browser and AI security solutions that extend into generative AI usage and prompt-related controls.



## Open-Source GitHub Projects

- **[NVIDIA NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails)**  

  Open-source toolkit for adding programmable guardrails (input, dialog, retrieval, execution, output) to LLM applications. Supports jailbreak detection, topic control, and policy enforcement.



- **[LLM Guard](https://github.com/protectai/llm-guard)**  

  Open-source LLM security toolkit with multiple input and output scanners for prompt injection, PII, toxicity, and other risks. Can run as a self-hosted API.



- **[Guardrails AI](https://github.com/guardrails-ai/guardrails)**  

  Open-source framework for adding structured validation, guardrails, and corrective actions around LLM outputs.



- **[Rebuff and related prompt injection detectors](https://github.com/)**  

  Open projects focused specifically on detecting and mitigating prompt injection attacks.



- **[Llama Guard and safety model open releases](https://github.com/)**  

  Open safety classifiers and models that can be used as components in prompt/output filtering pipelines.



- **[Garak and red-teaming open tools](https://github.com/)**  

  Open LLM vulnerability scanners and red-teaming frameworks useful for testing prompt security before production.



- **[Presidio and PII detection open libraries](https://github.com/microsoft/presidio)**  

  Open tools for detecting and anonymizing personally identifiable information in prompts and responses.



- **[Custom scanner and policy open frameworks](https://github.com/)**  

  Community libraries for building regex-, ML-, or rule-based scanners for LLM traffic.



- **[AI firewall and proxy open prototypes](https://github.com/)**  

  Experimental open proxies that sit in front of LLM APIs to enforce security policies.



- **[Evaluation and benchmark open datasets](https://github.com/)**  

  Public datasets and harnesses for measuring prompt injection and jailbreak detection performance.



### Additional Strong Open-Source Options

- Starting with **NeMo Guardrails** when you need programmable, dialog-aware control over LLM behavior.

- Using **LLM Guard** for practical, scanner-based input/output filtering that can be self-hosted.

- Combining open safety models (Llama Guard, etc.) with custom logic for layered defense.

- Running open red-teaming tools (Garak and similar) to continuously test applications.

- Accepting that enterprise-scale threat intelligence, ultra-low-latency managed APIs, and comprehensive MLSecOps platforms still favor commercial solutions (Lakera, Protect AI, HiddenLayer, Aporia, etc.).

- Deploying open guardrails in development and lower-risk environments while evaluating commercial options for production critical systems.



**Frameworks for building custom systems**: Intercept LLM calls with an open guardrails layer (NeMo Guardrails or LLM Guard) → scan inputs for injection/jailbreak/PII → apply dialog or topic rails → scan outputs before returning to users → log and monitor decisions. This provides a fully open runtime protection stack. Commercial platforms remain the practical choice when teams need managed services, continuous threat updates, and enterprise support.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Prompt security tools reduce but do not eliminate risks from prompt injection, jailbreaks, and data leakage. No guardrail is perfect. Open-source and commercial solutions require proper configuration, testing, monitoring, and defense-in-depth. This list is not security or compliance advice.



---

**Made for AI engineers, security teams, and platform owners who need safer LLM applications.**

Let's keep generative AI protected, observable, and as open as practical.
