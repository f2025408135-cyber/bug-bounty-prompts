# Harness Execution and Operational Directives

This documentation serves as the strict deployment guide for utilizing the Bug Bounty Prompt Library. It details the operational execution of the **System Harness** and **Pluggable Skill Modules** designed for elite Application Security Research and Bug Bounty Hunting.

## 1. The Core Architecture

The operational framework strictly separates overarching behavioral directives from specific operational logic.

* **The System Harness**: The foundational state. This dictates the operational persona, forces a mandatory Chain of Thought evaluation sequence, and enforces rigid analytical constraints (e.g., prohibition of hallucination and strict adherence to XML syntax).
* **The Pluggable Skill Module**: Specific, atomic instructions dictating the sequence of operations required to analyze and exploit a defined vulnerability class (e.g., Boolean-Based Blind SQL Injection, SSRF).

## 2. Execution Workflow

To ensure analytical rigor and eliminate context degradation in advanced LLMs (e.g., Claude 3.5 Sonnet / Opus), strict adherence to the deployment sequence is required.

### Step 1: System Initialization
Initialize a new session. Do not inject raw target data during this phase.
Inject the `system_harness.md` configuration as the foundational System Prompt. Await initialization and acknowledgment of the operational constraints.

### Step 2: Module Selection
Select the specific vulnerability operational directive (Skill Module) corresponding to the target architecture and the hypothesized vulnerability. Copy the raw Skill Module template from the designated library file.

### Step 3: Data Injection
Replace the defined `<input_data>` tags or `[Insert relevant HTTP request...]` placeholders within the Skill Module with raw, unmodified data captured from an intercepting proxy (e.g., Burp Suite). 

### Step 4: Execution
Deploy the combined Skill Module and raw input data to the initialized LLM.

### Step 5: Output Analysis
The System Harness enforces an obligatory analytical phase prior to payload generation. Review the output within the `<thinking>` or `<scratchpad>` tags. This section details the model's logical derivation and interpretation of the provided data structure. Following the analytical phase, the output will yield weaponized, formatted proof-of-concept directives ready for deployment against the target application.

## 3. Operational Best Practices

- **Prevent Context Degradation**: Do not reuse sessions across disparate targets or vulnerability classes. Context pollution introduces analytical flaws. Always initialize a new session and deploy a fresh Harness for every new analysis.
- **Strict Data Integrity**: Provide raw, unsummarized target data. Summarization introduces human bias and conceals subtle architectural discrepancies (e.g., misconfigured `Content-Type` headers or improper edge caching configurations) critical for vulnerability detection.
- **Mandatory Verification**: The payloads derived from this architecture are theoretical and hypothesis-driven. Researchers must execute the derived payloads, analyze the behavioral delta returned by the target application, and confirm the exploit path. The model output is a high-level operational starting point, not a definitive conclusion.
