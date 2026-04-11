# Bug Bounty LLM Prompts Collection

Welcome to my personal collection of bug bounty prompts. I've spent time curating and fine-tuning these prompts to help automate and improve the bug bounty hunting workflow, specifically tailored for Claude and other advanced LLMs.

Currently, this repository focuses on two of the most critical vulnerability classes:
1. **API Authentication**: Deep dives into JWT abuse, exposed credentials, database type confusion, and Row-Level Security (RLS) bypasses.
2. **Business Logic Flaws**: Advanced strategies for identifying price manipulation, workflow bypasses, and improper state transitions.

## How to Use
Copy the relevant prompt from the markdown files, insert your target's HTTP request/response data into the `[Input Data]` section, and let the LLM do the heavy lifting of parsing, formatting, and generating test cases.

## Why these prompts?
Generic LLM prompts often hallucinate or provide surface-level analysis. I've designed these to follow strict methodological steps ("Atomic Reasoning") and operational constraints to ensure the output is actionable, accurate, and ready for manual testing.
