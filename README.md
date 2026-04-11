# Claude Harness Engineer 

This repository contains the definitive "Meta-Prompt" architecture designed for advanced Large Language Models. Its objective is to transform baseline generative models into elite System Harness Engineers, optimizing them for high-stakes Application Security Research and Bug Bounty methodologies.

## Harness Engineering Overview

Harness Engineering supersedes standard prompt engineering by establishing a rigid, dual-layer cognitive architecture designed to eliminate extrapolation errors and context degradation.

1. **The System Harness**: The immutable foundation. It enforces the operational persona, dictates strict analytical constraints, and requires an obligatory logical progression framework via XML-based Chain of Thought.
2. **Pluggable Skill Modules**: Modular, highly specific heuristic instructions deployed at runtime alongside raw target data. These modules dictate the exact atomic operations the model must execute for a given vulnerability class.

## Deployment Protocol

The core architecture resides within `harness_engineer_meta_prompt.md`. This file is not deployed against targets; it is utilized to architect new prompt systems.

1. Inject the contents of `harness_engineer_meta_prompt.md` into the initial system state of an advanced LLM (e.g., Claude 3.5 Sonnet / Opus).
2. The model will initialize and adopt the Harness Engineer persona.
3. Command the initialized system to construct precise, XML-structured Prompt Frameworks for specific operational requirements.

**Execution Example:**
> "Design a System Harness and Pluggable Skill Module for detecting Server-Side Request Forgery (SSRF) bypasses in AWS environments utilizing octal IP encodings."

The output will be a highly structured, strict operational prompt framework ready for deployment against live targets.

## Architectural Advantages of XML

This methodology relies heavily on XML syntactical structures (e.g., `<system_prompt>`, `<input_data>`, `<thinking_process>`). By encapsulating instructions, operational rules, and untrusted data within distinct XML tags, this architecture mitigates prompt injection vectors and ensures the strict separation of logic and data during analysis.
