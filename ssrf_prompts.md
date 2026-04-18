# SSRF Bug Bounty Skills

A curated, extensive collection of 158 advanced skills for SSRF bug bounty hunting. Built for the Bug Bounty System Harness.

### 1. Server-Side Request Forgery - SSRF via SVG Uploads targeting GraphQL (Apollo)

**Target Area**: Internal Logic / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via SVG Uploads. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to GraphQL (Apollo).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 2. Server-Side Request Forgery - SSRF via PDF Generation targeting Ruby on Rails

**Target Area**: Internal Logic / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via PDF Generation within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via PDF Generation within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via PDF Generation. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Ruby on Rails.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 3. Server-Side Request Forgery - SSRF Filter Bypass via Octal IP Encodings targeting Azure API Management

**Target Area**: Internal Logic / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Azure API Management parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF Filter Bypass via Octal IP Encodings. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service via internal loopback requests.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Azure API Management.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 4. Server-Side Request Forgery - SSRF via SVG Uploads targeting Apigee

**Target Area**: Internal Logic / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via SVG Uploads. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Apigee.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 5. Server-Side Request Forgery - SSRF to Localhost Services targeting Laravel (PHP)

**Target Area**: Internal Logic / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF to Localhost Services within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF to Localhost Services within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF to Localhost Services. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service via internal loopback requests.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Laravel (PHP).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 6. Server-Side Request Forgery - SSRF via XML External Entity (XXE) targeting FastAPI

**Target Area**: Internal Logic / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via XML External Entity (XXE) within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via XML External Entity (XXE) within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how FastAPI parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via XML External Entity (XXE). Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to FastAPI.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 7. Server-Side Request Forgery - SSRF against Internal Redis Instances targeting GraphQL (Apollo)

**Target Area**: Internal Logic / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Internal Redis Instances within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Internal Redis Instances within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF against Internal Redis Instances. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to GraphQL (Apollo).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 8. Server-Side Request Forgery - Blind SSRF via Webhooks targeting GraphQL (Relay)

**Target Area**: Internal Logic / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting Blind SSRF via Webhooks within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Blind SSRF via Webhooks within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on Blind SSRF via Webhooks. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to GraphQL (Relay).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 9. Server-Side Request Forgery - SSRF against Cloud Metadata (AWS IMDSv2) targeting Supabase

**Target Area**: Internal Logic / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Supabase parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF against Cloud Metadata (AWS IMDSv2). Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Supabase.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 10. Server-Side Request Forgery - SSRF Filter Bypass via DNS Rebinding targeting Spring Boot (Java)

**Target Area**: Internal Logic / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF Filter Bypass via DNS Rebinding within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF Filter Bypass via DNS Rebinding within a Third-party integration webhook. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Spring Boot (Java) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF Filter Bypass via DNS Rebinding. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Spring Boot (Java).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 11. Server-Side Request Forgery - SSRF against Cloud Metadata (GCP/Azure) targeting Supabase

**Target Area**: Internal Logic / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (GCP/Azure) within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (GCP/Azure) within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Supabase parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF against Cloud Metadata (GCP/Azure). Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Supabase.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 12. Server-Side Request Forgery - SSRF against Cloud Metadata (AWS IMDSv2) targeting Node.js/Express

**Target Area**: Internal Logic / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Node.js/Express parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF against Cloud Metadata (AWS IMDSv2). Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service via internal loopback requests.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Node.js/Express.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 13. Server-Side Request Forgery - SSRF against Cloud Metadata (AWS IMDSv2) targeting GraphQL (Relay)

**Target Area**: Internal Logic / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF against Cloud Metadata (AWS IMDSv2). Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to GraphQL (Relay).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 14. Server-Side Request Forgery - SSRF via XML External Entity (XXE) targeting Node.js/Express

**Target Area**: Internal Logic / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via XML External Entity (XXE) within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via XML External Entity (XXE) within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Node.js/Express parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via XML External Entity (XXE). Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Node.js/Express.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 15. Server-Side Request Forgery - SSRF Filter Bypass via Octal IP Encodings targeting GraphQL (Apollo)

**Target Area**: Internal Logic / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF Filter Bypass via Octal IP Encodings. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to GraphQL (Apollo).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 16. Server-Side Request Forgery - SSRF Filter Bypass via DNS Rebinding targeting Go (Fiber)

**Target Area**: Internal Logic / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF Filter Bypass via DNS Rebinding within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF Filter Bypass via DNS Rebinding within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Fiber) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF Filter Bypass via DNS Rebinding. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service via internal loopback requests.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Go (Fiber).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 17. Server-Side Request Forgery - SSRF against Internal Redis Instances targeting Firebase

**Target Area**: Internal Logic / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Internal Redis Instances within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Internal Redis Instances within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF against Internal Redis Instances. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Firebase.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 18. Server-Side Request Forgery - SSRF against Cloud Metadata (GCP/Azure) targeting Apigee

**Target Area**: Internal Logic / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (GCP/Azure) within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (GCP/Azure) within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF against Cloud Metadata (GCP/Azure). Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Apigee.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 19. Server-Side Request Forgery - SSRF against Cloud Metadata (AWS IMDSv2) targeting Ruby on Rails

**Target Area**: Internal Logic / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Mobile application backend API. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF against Cloud Metadata (AWS IMDSv2). Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Ruby on Rails.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 20. Server-Side Request Forgery - SSRF via SVG Uploads targeting Ruby on Rails

**Target Area**: Internal Logic / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via SVG Uploads. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Ruby on Rails.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 21. Server-Side Request Forgery - SSRF via PDF Generation targeting Go (Fiber)

**Target Area**: Internal Logic / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via PDF Generation within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via PDF Generation within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Fiber) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via PDF Generation. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Go (Fiber).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 22. Server-Side Request Forgery - SSRF to Localhost Services targeting Django (Python)

**Target Area**: Internal Logic / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF to Localhost Services within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF to Localhost Services within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Django (Python) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF to Localhost Services. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Django (Python).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 23. Server-Side Request Forgery - SSRF via XML External Entity (XXE) targeting Spring Boot (Java)

**Target Area**: Internal Logic / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via XML External Entity (XXE) within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via XML External Entity (XXE) within a Third-party integration webhook. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Spring Boot (Java) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via XML External Entity (XXE). Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Spring Boot (Java).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 24. Server-Side Request Forgery - SSRF via SVG Uploads targeting FastAPI

**Target Area**: Internal Logic / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how FastAPI parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via SVG Uploads. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service via internal loopback requests.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to FastAPI.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 25. Server-Side Request Forgery - SSRF against Internal Redis Instances targeting Azure API Management

**Target Area**: Internal Logic / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Internal Redis Instances within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Internal Redis Instances within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Azure API Management parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF against Internal Redis Instances. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Azure API Management.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 26. Server-Side Request Forgery - SSRF against Internal Redis Instances targeting GraphQL (Apollo)

**Target Area**: Internal Logic / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Internal Redis Instances within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Internal Redis Instances within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF against Internal Redis Instances. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to GraphQL (Apollo).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 27. Server-Side Request Forgery - SSRF to Localhost Services targeting Symfony (PHP)

**Target Area**: Internal Logic / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF to Localhost Services within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF to Localhost Services within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Symfony (PHP) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Mobile application backend API. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF to Localhost Services. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Symfony (PHP).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 28. Server-Side Request Forgery - SSRF via PDF Generation targeting Symfony (PHP)

**Target Area**: Internal Logic / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via PDF Generation within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via PDF Generation within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Symfony (PHP) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via PDF Generation. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Symfony (PHP).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 29. Server-Side Request Forgery - SSRF against Cloud Metadata (AWS IMDSv2) targeting Supabase

**Target Area**: Internal Logic / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Supabase parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF against Cloud Metadata (AWS IMDSv2). Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Supabase.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 30. Server-Side Request Forgery - SSRF Filter Bypass via Octal IP Encodings targeting Go (Gin)

**Target Area**: Internal Logic / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Third-party integration webhook. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Gin) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF Filter Bypass via Octal IP Encodings. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service via internal loopback requests.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Go (Gin).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 31. Server-Side Request Forgery - SSRF against Cloud Metadata (GCP/Azure) targeting Go (Fiber)

**Target Area**: Internal Logic / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (GCP/Azure) within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (GCP/Azure) within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Fiber) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF against Cloud Metadata (GCP/Azure). Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Go (Fiber).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 32. Server-Side Request Forgery - SSRF to Localhost Services targeting Apigee

**Target Area**: Internal Logic / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF to Localhost Services within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF to Localhost Services within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF to Localhost Services. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Apigee.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 33. Server-Side Request Forgery - SSRF to Localhost Services targeting Apigee

**Target Area**: Internal Logic / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF to Localhost Services within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF to Localhost Services within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF to Localhost Services. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Apigee.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 34. Server-Side Request Forgery - SSRF against Internal Redis Instances targeting Laravel (PHP)

**Target Area**: Internal Logic / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Internal Redis Instances within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Internal Redis Instances within a Third-party integration webhook. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF against Internal Redis Instances. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Laravel (PHP).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 35. Server-Side Request Forgery - SSRF via Image Processing Library targeting Laravel (PHP)

**Target Area**: Internal Logic / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via Image Processing Library within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via Image Processing Library within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via Image Processing Library. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Laravel (PHP).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 36. Server-Side Request Forgery - SSRF via PDF Generation targeting GraphQL (Relay)

**Target Area**: Internal Logic / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via PDF Generation within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via PDF Generation within a Third-party integration webhook. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via PDF Generation. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service via internal loopback requests.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to GraphQL (Relay).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 37. Server-Side Request Forgery - SSRF against Cloud Metadata (AWS IMDSv2) targeting AWS API Gateway

**Target Area**: Internal Logic / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how AWS API Gateway parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF against Cloud Metadata (AWS IMDSv2). Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to AWS API Gateway.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 38. Server-Side Request Forgery - SSRF Filter Bypass via Octal IP Encodings targeting Go (Gin)

**Target Area**: Internal Logic / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Gin) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF Filter Bypass via Octal IP Encodings. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service via internal loopback requests.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Go (Gin).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 39. Server-Side Request Forgery - SSRF via Image Processing Library targeting GraphQL (Relay)

**Target Area**: Internal Logic / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via Image Processing Library within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via Image Processing Library within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via Image Processing Library. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to GraphQL (Relay).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 40. Server-Side Request Forgery - Blind SSRF via Webhooks targeting Flask (Python)

**Target Area**: Internal Logic / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting Blind SSRF via Webhooks within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Blind SSRF via Webhooks within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Flask (Python) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Mobile application backend API. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on Blind SSRF via Webhooks. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Flask (Python).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 41. Server-Side Request Forgery - Blind SSRF via Webhooks targeting Spring Boot (Java)

**Target Area**: Internal Logic / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting Blind SSRF via Webhooks within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Blind SSRF via Webhooks within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Spring Boot (Java) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on Blind SSRF via Webhooks. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Spring Boot (Java).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 42. Server-Side Request Forgery - SSRF Filter Bypass via Octal IP Encodings targeting Kong API Gateway

**Target Area**: Internal Logic / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Kong API Gateway parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Mobile application backend API. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF Filter Bypass via Octal IP Encodings. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Kong API Gateway.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 43. Server-Side Request Forgery - SSRF via SVG Uploads targeting GraphQL (Apollo)

**Target Area**: Internal Logic / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via SVG Uploads. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to GraphQL (Apollo).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 44. Server-Side Request Forgery - SSRF against Internal Redis Instances targeting Ruby on Rails

**Target Area**: Internal Logic / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Internal Redis Instances within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Internal Redis Instances within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF against Internal Redis Instances. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service via internal loopback requests.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Ruby on Rails.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 45. Server-Side Request Forgery - SSRF via SVG Uploads targeting Azure API Management

**Target Area**: Internal Logic / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Azure API Management parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via SVG Uploads. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Azure API Management.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 46. Server-Side Request Forgery - SSRF via PDF Generation targeting Go (Fiber)

**Target Area**: Internal Logic / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via PDF Generation within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via PDF Generation within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Fiber) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via PDF Generation. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service via internal loopback requests.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Go (Fiber).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 47. Server-Side Request Forgery - SSRF Filter Bypass via DNS Rebinding targeting Kong API Gateway

**Target Area**: Internal Logic / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF Filter Bypass via DNS Rebinding within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF Filter Bypass via DNS Rebinding within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Kong API Gateway parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF Filter Bypass via DNS Rebinding. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Kong API Gateway.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 48. Server-Side Request Forgery - SSRF Filter Bypass via Octal IP Encodings targeting Symfony (PHP)

**Target Area**: Internal Logic / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Symfony (PHP) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF Filter Bypass via Octal IP Encodings. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Symfony (PHP).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 49. Server-Side Request Forgery - SSRF against Internal Redis Instances targeting Firebase

**Target Area**: Internal Logic / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Internal Redis Instances within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Internal Redis Instances within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF against Internal Redis Instances. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Firebase.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 50. Server-Side Request Forgery - SSRF via XML External Entity (XXE) targeting Azure API Management

**Target Area**: Internal Logic / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via XML External Entity (XXE) within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via XML External Entity (XXE) within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Azure API Management parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Mobile application backend API. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via XML External Entity (XXE). Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Azure API Management.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 51. Server-Side Request Forgery - SSRF against Internal Redis Instances targeting GraphQL (Relay)

**Target Area**: Internal Logic / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Internal Redis Instances within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Internal Redis Instances within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Mobile application backend API. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF against Internal Redis Instances. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to GraphQL (Relay).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 52. Server-Side Request Forgery - SSRF via XML External Entity (XXE) targeting Spring Boot (Java)

**Target Area**: Internal Logic / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via XML External Entity (XXE) within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via XML External Entity (XXE) within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Spring Boot (Java) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via XML External Entity (XXE). Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Spring Boot (Java).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 53. Server-Side Request Forgery - SSRF against Internal Redis Instances targeting AWS API Gateway

**Target Area**: Internal Logic / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Internal Redis Instances within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Internal Redis Instances within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how AWS API Gateway parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF against Internal Redis Instances. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to AWS API Gateway.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 54. Server-Side Request Forgery - SSRF Filter Bypass via DNS Rebinding targeting Spring Boot (Java)

**Target Area**: Internal Logic / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF Filter Bypass via DNS Rebinding within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF Filter Bypass via DNS Rebinding within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Spring Boot (Java) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF Filter Bypass via DNS Rebinding. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Spring Boot (Java).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 55. Server-Side Request Forgery - SSRF against Cloud Metadata (AWS IMDSv2) targeting Firebase

**Target Area**: Internal Logic / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF against Cloud Metadata (AWS IMDSv2). Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Firebase.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 56. Server-Side Request Forgery - SSRF to Localhost Services targeting Rust (Actix)

**Target Area**: Internal Logic / Rust (Actix) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF to Localhost Services within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF to Localhost Services within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Rust (Actix) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF to Localhost Services. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Rust (Actix).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 57. Server-Side Request Forgery - SSRF against Cloud Metadata (GCP/Azure) targeting Rust (Actix)

**Target Area**: Internal Logic / Rust (Actix) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (GCP/Azure) within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (GCP/Azure) within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Rust (Actix) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF against Cloud Metadata (GCP/Azure). Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Rust (Actix).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 58. Server-Side Request Forgery - SSRF against Cloud Metadata (GCP/Azure) targeting Ruby on Rails

**Target Area**: Internal Logic / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (GCP/Azure) within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (GCP/Azure) within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF against Cloud Metadata (GCP/Azure). Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Ruby on Rails.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 59. Server-Side Request Forgery - SSRF Filter Bypass via Octal IP Encodings targeting GraphQL (Apollo)

**Target Area**: Internal Logic / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF Filter Bypass via Octal IP Encodings. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to GraphQL (Apollo).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 60. Server-Side Request Forgery - SSRF via XML External Entity (XXE) targeting Apigee

**Target Area**: Internal Logic / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via XML External Entity (XXE) within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via XML External Entity (XXE) within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via XML External Entity (XXE). Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Apigee.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 61. Server-Side Request Forgery - SSRF against Internal Redis Instances targeting GraphQL (Relay)

**Target Area**: Internal Logic / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Internal Redis Instances within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Internal Redis Instances within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF against Internal Redis Instances. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to GraphQL (Relay).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 62. Server-Side Request Forgery - SSRF against Cloud Metadata (AWS IMDSv2) targeting Ruby on Rails

**Target Area**: Internal Logic / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF against Cloud Metadata (AWS IMDSv2). Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Ruby on Rails.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 63. Server-Side Request Forgery - SSRF via SVG Uploads targeting Flask (Python)

**Target Area**: Internal Logic / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Flask (Python) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via SVG Uploads. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service via internal loopback requests.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Flask (Python).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 64. Server-Side Request Forgery - SSRF against Cloud Metadata (AWS IMDSv2) targeting ASP.NET Core

**Target Area**: Internal Logic / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF against Cloud Metadata (AWS IMDSv2). Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service via internal loopback requests.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to ASP.NET Core.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 65. Server-Side Request Forgery - SSRF via Image Processing Library targeting FastAPI

**Target Area**: Internal Logic / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via Image Processing Library within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via Image Processing Library within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how FastAPI parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via Image Processing Library. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service via internal loopback requests.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to FastAPI.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 66. Server-Side Request Forgery - SSRF via Image Processing Library targeting ASP.NET Core

**Target Area**: Internal Logic / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via Image Processing Library within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via Image Processing Library within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via Image Processing Library. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to ASP.NET Core.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 67. Server-Side Request Forgery - SSRF Filter Bypass via Octal IP Encodings targeting Go (Gin)

**Target Area**: Internal Logic / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Gin) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Mobile application backend API. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF Filter Bypass via Octal IP Encodings. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Go (Gin).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 68. Server-Side Request Forgery - SSRF via SVG Uploads targeting Django (Python)

**Target Area**: Internal Logic / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Django (Python) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via SVG Uploads. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Django (Python).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 69. Server-Side Request Forgery - SSRF via XML External Entity (XXE) targeting FastAPI

**Target Area**: Internal Logic / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via XML External Entity (XXE) within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via XML External Entity (XXE) within a Third-party integration webhook. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how FastAPI parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via XML External Entity (XXE). Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to FastAPI.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 70. Server-Side Request Forgery - SSRF via SVG Uploads targeting Go (Fiber)

**Target Area**: Internal Logic / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Fiber) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via SVG Uploads. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Go (Fiber).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 71. Server-Side Request Forgery - SSRF via Image Processing Library targeting GraphQL (Apollo)

**Target Area**: Internal Logic / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via Image Processing Library within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via Image Processing Library within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via Image Processing Library. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to GraphQL (Apollo).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 72. Server-Side Request Forgery - SSRF Filter Bypass via Octal IP Encodings targeting GraphQL (Relay)

**Target Area**: Internal Logic / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF Filter Bypass via Octal IP Encodings. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to GraphQL (Relay).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 73. Server-Side Request Forgery - SSRF to Localhost Services targeting Go (Fiber)

**Target Area**: Internal Logic / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF to Localhost Services within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF to Localhost Services within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Fiber) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF to Localhost Services. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Go (Fiber).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 74. Server-Side Request Forgery - Blind SSRF via Webhooks targeting Kong API Gateway

**Target Area**: Internal Logic / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting Blind SSRF via Webhooks within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Blind SSRF via Webhooks within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Kong API Gateway parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on Blind SSRF via Webhooks. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Kong API Gateway.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 75. Server-Side Request Forgery - SSRF against Cloud Metadata (GCP/Azure) targeting Go (Gin)

**Target Area**: Internal Logic / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (GCP/Azure) within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (GCP/Azure) within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Gin) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF against Cloud Metadata (GCP/Azure). Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Go (Gin).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 76. Server-Side Request Forgery - SSRF via XML External Entity (XXE) targeting GraphQL (Relay)

**Target Area**: Internal Logic / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via XML External Entity (XXE) within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via XML External Entity (XXE) within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via XML External Entity (XXE). Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to GraphQL (Relay).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 77. Server-Side Request Forgery - SSRF Filter Bypass via Octal IP Encodings targeting GraphQL (Apollo)

**Target Area**: Internal Logic / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF Filter Bypass via Octal IP Encodings. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to GraphQL (Apollo).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 78. Server-Side Request Forgery - SSRF via XML External Entity (XXE) targeting Symfony (PHP)

**Target Area**: Internal Logic / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via XML External Entity (XXE) within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via XML External Entity (XXE) within a Third-party integration webhook. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Symfony (PHP) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via XML External Entity (XXE). Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service via internal loopback requests.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Symfony (PHP).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 79. Server-Side Request Forgery - SSRF Filter Bypass via DNS Rebinding targeting Apigee

**Target Area**: Internal Logic / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF Filter Bypass via DNS Rebinding within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF Filter Bypass via DNS Rebinding within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF Filter Bypass via DNS Rebinding. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Apigee.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 80. Server-Side Request Forgery - SSRF against Cloud Metadata (GCP/Azure) targeting Symfony (PHP)

**Target Area**: Internal Logic / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (GCP/Azure) within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (GCP/Azure) within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Symfony (PHP) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF against Cloud Metadata (GCP/Azure). Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Symfony (PHP).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 81. Server-Side Request Forgery - SSRF via SVG Uploads targeting Apigee

**Target Area**: Internal Logic / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via SVG Uploads. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Apigee.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 82. Server-Side Request Forgery - SSRF Filter Bypass via DNS Rebinding targeting Symfony (PHP)

**Target Area**: Internal Logic / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF Filter Bypass via DNS Rebinding within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF Filter Bypass via DNS Rebinding within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Symfony (PHP) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF Filter Bypass via DNS Rebinding. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Symfony (PHP).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 83. Server-Side Request Forgery - SSRF to Localhost Services targeting AWS API Gateway

**Target Area**: Internal Logic / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF to Localhost Services within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF to Localhost Services within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how AWS API Gateway parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF to Localhost Services. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to AWS API Gateway.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 84. Server-Side Request Forgery - SSRF via PDF Generation targeting AWS API Gateway

**Target Area**: Internal Logic / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via PDF Generation within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via PDF Generation within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how AWS API Gateway parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via PDF Generation. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service via internal loopback requests.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to AWS API Gateway.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 85. Server-Side Request Forgery - SSRF Filter Bypass via Octal IP Encodings targeting Azure API Management

**Target Area**: Internal Logic / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Azure API Management parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF Filter Bypass via Octal IP Encodings. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Azure API Management.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 86. Server-Side Request Forgery - SSRF against Internal Redis Instances targeting Kong API Gateway

**Target Area**: Internal Logic / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Internal Redis Instances within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Internal Redis Instances within a Third-party integration webhook. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Kong API Gateway parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF against Internal Redis Instances. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service via internal loopback requests.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Kong API Gateway.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 87. Server-Side Request Forgery - SSRF against Cloud Metadata (AWS IMDSv2) targeting Node.js/Express

**Target Area**: Internal Logic / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Node.js/Express parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF against Cloud Metadata (AWS IMDSv2). Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service via internal loopback requests.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Node.js/Express.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 88. Server-Side Request Forgery - SSRF against Internal Redis Instances targeting Laravel (PHP)

**Target Area**: Internal Logic / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Internal Redis Instances within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Internal Redis Instances within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF against Internal Redis Instances. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Laravel (PHP).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 89. Server-Side Request Forgery - SSRF via Image Processing Library targeting Go (Fiber)

**Target Area**: Internal Logic / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via Image Processing Library within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via Image Processing Library within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Fiber) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via Image Processing Library. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Go (Fiber).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 90. Server-Side Request Forgery - SSRF against Internal Redis Instances targeting Flask (Python)

**Target Area**: Internal Logic / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Internal Redis Instances within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Internal Redis Instances within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Flask (Python) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF against Internal Redis Instances. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Flask (Python).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 91. Server-Side Request Forgery - SSRF against Cloud Metadata (GCP/Azure) targeting Go (Gin)

**Target Area**: Internal Logic / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (GCP/Azure) within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (GCP/Azure) within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Gin) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF against Cloud Metadata (GCP/Azure). Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Go (Gin).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 92. Server-Side Request Forgery - SSRF Filter Bypass via DNS Rebinding targeting Spring Boot (Java)

**Target Area**: Internal Logic / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF Filter Bypass via DNS Rebinding within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF Filter Bypass via DNS Rebinding within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Spring Boot (Java) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF Filter Bypass via DNS Rebinding. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Spring Boot (Java).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 93. Server-Side Request Forgery - SSRF against Cloud Metadata (GCP/Azure) targeting Apigee

**Target Area**: Internal Logic / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (GCP/Azure) within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (GCP/Azure) within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF against Cloud Metadata (GCP/Azure). Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service via internal loopback requests.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Apigee.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 94. Server-Side Request Forgery - SSRF against Internal Redis Instances targeting FastAPI

**Target Area**: Internal Logic / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Internal Redis Instances within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Internal Redis Instances within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how FastAPI parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF against Internal Redis Instances. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to FastAPI.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 95. Server-Side Request Forgery - SSRF against Cloud Metadata (GCP/Azure) targeting Django (Python)

**Target Area**: Internal Logic / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (GCP/Azure) within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (GCP/Azure) within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Django (Python) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF against Cloud Metadata (GCP/Azure). Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Django (Python).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 96. Server-Side Request Forgery - SSRF via PDF Generation targeting Symfony (PHP)

**Target Area**: Internal Logic / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via PDF Generation within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via PDF Generation within a Third-party integration webhook. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Symfony (PHP) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via PDF Generation. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Symfony (PHP).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 97. Server-Side Request Forgery - SSRF to Localhost Services targeting Node.js/Express

**Target Area**: Internal Logic / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF to Localhost Services within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF to Localhost Services within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Node.js/Express parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF to Localhost Services. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Node.js/Express.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 98. Server-Side Request Forgery - SSRF against Cloud Metadata (AWS IMDSv2) targeting Rust (Actix)

**Target Area**: Internal Logic / Rust (Actix) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Rust (Actix) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF against Cloud Metadata (AWS IMDSv2). Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service via internal loopback requests.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Rust (Actix).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 99. Server-Side Request Forgery - SSRF via SVG Uploads targeting Azure API Management

**Target Area**: Internal Logic / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Azure API Management parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Mobile application backend API. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via SVG Uploads. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Azure API Management.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 100. Server-Side Request Forgery - SSRF against Cloud Metadata (AWS IMDSv2) targeting Go (Fiber)

**Target Area**: Internal Logic / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Fiber) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF against Cloud Metadata (AWS IMDSv2). Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Go (Fiber).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 101. Server-Side Request Forgery - Blind SSRF via Webhooks targeting Symfony (PHP)

**Target Area**: Internal Logic / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting Blind SSRF via Webhooks within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Blind SSRF via Webhooks within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Symfony (PHP) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Mobile application backend API. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on Blind SSRF via Webhooks. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Symfony (PHP).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 102. Server-Side Request Forgery - SSRF against Cloud Metadata (AWS IMDSv2) targeting Go (Fiber)

**Target Area**: Internal Logic / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Fiber) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Mobile application backend API. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF against Cloud Metadata (AWS IMDSv2). Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Go (Fiber).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 103. Server-Side Request Forgery - SSRF Filter Bypass via DNS Rebinding targeting Supabase

**Target Area**: Internal Logic / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF Filter Bypass via DNS Rebinding within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF Filter Bypass via DNS Rebinding within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Supabase parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF Filter Bypass via DNS Rebinding. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Supabase.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 104. Server-Side Request Forgery - SSRF via Image Processing Library targeting Django (Python)

**Target Area**: Internal Logic / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via Image Processing Library within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via Image Processing Library within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Django (Python) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via Image Processing Library. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Django (Python).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 105. Server-Side Request Forgery - SSRF via Image Processing Library targeting Firebase

**Target Area**: Internal Logic / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via Image Processing Library within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via Image Processing Library within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via Image Processing Library. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service via internal loopback requests.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Firebase.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 106. Server-Side Request Forgery - SSRF Filter Bypass via Octal IP Encodings targeting Symfony (PHP)

**Target Area**: Internal Logic / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Symfony (PHP) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF Filter Bypass via Octal IP Encodings. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Symfony (PHP).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 107. Server-Side Request Forgery - SSRF via SVG Uploads targeting Laravel (PHP)

**Target Area**: Internal Logic / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via SVG Uploads. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Laravel (PHP).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 108. Server-Side Request Forgery - SSRF Filter Bypass via DNS Rebinding targeting FastAPI

**Target Area**: Internal Logic / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF Filter Bypass via DNS Rebinding within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF Filter Bypass via DNS Rebinding within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how FastAPI parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF Filter Bypass via DNS Rebinding. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to FastAPI.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 109. Server-Side Request Forgery - SSRF via XML External Entity (XXE) targeting Django (Python)

**Target Area**: Internal Logic / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via XML External Entity (XXE) within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via XML External Entity (XXE) within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Django (Python) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via XML External Entity (XXE). Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service via internal loopback requests.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Django (Python).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 110. Server-Side Request Forgery - SSRF via SVG Uploads targeting Kong API Gateway

**Target Area**: Internal Logic / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Kong API Gateway parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via SVG Uploads. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Kong API Gateway.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 111. Server-Side Request Forgery - SSRF against Internal Redis Instances targeting Laravel (PHP)

**Target Area**: Internal Logic / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Internal Redis Instances within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Internal Redis Instances within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF against Internal Redis Instances. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Laravel (PHP).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 112. Server-Side Request Forgery - SSRF via SVG Uploads targeting Go (Gin)

**Target Area**: Internal Logic / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Gin) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via SVG Uploads. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Go (Gin).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 113. Server-Side Request Forgery - SSRF against Cloud Metadata (GCP/Azure) targeting GraphQL (Relay)

**Target Area**: Internal Logic / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (GCP/Azure) within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (GCP/Azure) within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF against Cloud Metadata (GCP/Azure). Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to GraphQL (Relay).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 114. Server-Side Request Forgery - SSRF via SVG Uploads targeting GraphQL (Apollo)

**Target Area**: Internal Logic / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via SVG Uploads. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to GraphQL (Apollo).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 115. Server-Side Request Forgery - SSRF Filter Bypass via Octal IP Encodings targeting Go (Gin)

**Target Area**: Internal Logic / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Gin) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Mobile application backend API. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF Filter Bypass via Octal IP Encodings. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Go (Gin).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 116. Server-Side Request Forgery - SSRF against Cloud Metadata (AWS IMDSv2) targeting Spring Boot (Java)

**Target Area**: Internal Logic / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Spring Boot (Java) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF against Cloud Metadata (AWS IMDSv2). Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Spring Boot (Java).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 117. Server-Side Request Forgery - SSRF via SVG Uploads targeting Ruby on Rails

**Target Area**: Internal Logic / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Mobile application backend API. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via SVG Uploads. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service via internal loopback requests.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Ruby on Rails.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 118. Server-Side Request Forgery - SSRF Filter Bypass via Octal IP Encodings targeting Go (Gin)

**Target Area**: Internal Logic / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Gin) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF Filter Bypass via Octal IP Encodings. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Go (Gin).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 119. Server-Side Request Forgery - SSRF via Image Processing Library targeting ASP.NET Core

**Target Area**: Internal Logic / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via Image Processing Library within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via Image Processing Library within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via Image Processing Library. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to ASP.NET Core.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 120. Server-Side Request Forgery - SSRF via PDF Generation targeting FastAPI

**Target Area**: Internal Logic / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via PDF Generation within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via PDF Generation within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how FastAPI parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via PDF Generation. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to FastAPI.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 121. Server-Side Request Forgery - SSRF via PDF Generation targeting Apigee

**Target Area**: Internal Logic / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via PDF Generation within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via PDF Generation within a Third-party integration webhook. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via PDF Generation. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Apigee.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 122. Server-Side Request Forgery - SSRF Filter Bypass via Octal IP Encodings targeting GraphQL (Relay)

**Target Area**: Internal Logic / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF Filter Bypass via Octal IP Encodings. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to GraphQL (Relay).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 123. Server-Side Request Forgery - SSRF via SVG Uploads targeting Kong API Gateway

**Target Area**: Internal Logic / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Kong API Gateway parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via SVG Uploads. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Kong API Gateway.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 124. Server-Side Request Forgery - SSRF against Cloud Metadata (AWS IMDSv2) targeting GraphQL (Relay)

**Target Area**: Internal Logic / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF against Cloud Metadata (AWS IMDSv2). Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to GraphQL (Relay).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 125. Server-Side Request Forgery - Blind SSRF via Webhooks targeting Laravel (PHP)

**Target Area**: Internal Logic / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting Blind SSRF via Webhooks within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Blind SSRF via Webhooks within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on Blind SSRF via Webhooks. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Laravel (PHP).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 126. Server-Side Request Forgery - SSRF via PDF Generation targeting Flask (Python)

**Target Area**: Internal Logic / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via PDF Generation within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via PDF Generation within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Flask (Python) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via PDF Generation. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Flask (Python).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 127. Server-Side Request Forgery - SSRF against Cloud Metadata (GCP/Azure) targeting Azure API Management

**Target Area**: Internal Logic / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (GCP/Azure) within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (GCP/Azure) within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Azure API Management parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF against Cloud Metadata (GCP/Azure). Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Azure API Management.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 128. Server-Side Request Forgery - SSRF against Cloud Metadata (AWS IMDSv2) targeting FastAPI

**Target Area**: Internal Logic / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how FastAPI parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF against Cloud Metadata (AWS IMDSv2). Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to FastAPI.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 129. Server-Side Request Forgery - SSRF via SVG Uploads targeting FastAPI

**Target Area**: Internal Logic / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how FastAPI parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via SVG Uploads. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to FastAPI.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 130. Server-Side Request Forgery - SSRF to Localhost Services targeting Go (Fiber)

**Target Area**: Internal Logic / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF to Localhost Services within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF to Localhost Services within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Fiber) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF to Localhost Services. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Go (Fiber).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 131. Server-Side Request Forgery - SSRF against Internal Redis Instances targeting Ruby on Rails

**Target Area**: Internal Logic / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Internal Redis Instances within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Internal Redis Instances within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF against Internal Redis Instances. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Ruby on Rails.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 132. Server-Side Request Forgery - SSRF to Localhost Services targeting Symfony (PHP)

**Target Area**: Internal Logic / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF to Localhost Services within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF to Localhost Services within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Symfony (PHP) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF to Localhost Services. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service via internal loopback requests.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Symfony (PHP).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 133. Server-Side Request Forgery - SSRF against Cloud Metadata (GCP/Azure) targeting Apigee

**Target Area**: Internal Logic / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (GCP/Azure) within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (GCP/Azure) within a Third-party integration webhook. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF against Cloud Metadata (GCP/Azure). Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Apigee.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 134. Server-Side Request Forgery - SSRF Filter Bypass via Octal IP Encodings targeting Go (Gin)

**Target Area**: Internal Logic / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Gin) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF Filter Bypass via Octal IP Encodings. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Go (Gin).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 135. Server-Side Request Forgery - SSRF via XML External Entity (XXE) targeting Rust (Actix)

**Target Area**: Internal Logic / Rust (Actix) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via XML External Entity (XXE) within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via XML External Entity (XXE) within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Rust (Actix) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via XML External Entity (XXE). Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Rust (Actix).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 136. Server-Side Request Forgery - Blind SSRF via Webhooks targeting Django (Python)

**Target Area**: Internal Logic / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting Blind SSRF via Webhooks within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Blind SSRF via Webhooks within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Django (Python) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on Blind SSRF via Webhooks. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Django (Python).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 137. Server-Side Request Forgery - SSRF via Image Processing Library targeting Rust (Actix)

**Target Area**: Internal Logic / Rust (Actix) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via Image Processing Library within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via Image Processing Library within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Rust (Actix) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via Image Processing Library. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Rust (Actix).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 138. Server-Side Request Forgery - SSRF Filter Bypass via Octal IP Encodings targeting Go (Gin)

**Target Area**: Internal Logic / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Gin) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF Filter Bypass via Octal IP Encodings. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Go (Gin).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 139. Server-Side Request Forgery - SSRF via PDF Generation targeting ASP.NET Core

**Target Area**: Internal Logic / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via PDF Generation within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via PDF Generation within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via PDF Generation. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to ASP.NET Core.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 140. Server-Side Request Forgery - SSRF Filter Bypass via DNS Rebinding targeting GraphQL (Apollo)

**Target Area**: Internal Logic / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF Filter Bypass via DNS Rebinding within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF Filter Bypass via DNS Rebinding within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF Filter Bypass via DNS Rebinding. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service via internal loopback requests.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to GraphQL (Apollo).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 141. Server-Side Request Forgery - SSRF via XML External Entity (XXE) targeting GraphQL (Apollo)

**Target Area**: Internal Logic / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via XML External Entity (XXE) within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via XML External Entity (XXE) within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Mobile application backend API. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via XML External Entity (XXE). Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to GraphQL (Apollo).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 142. Server-Side Request Forgery - SSRF against Internal Redis Instances targeting Ruby on Rails

**Target Area**: Internal Logic / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Internal Redis Instances within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Internal Redis Instances within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF against Internal Redis Instances. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Ruby on Rails.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 143. Server-Side Request Forgery - Blind SSRF via Webhooks targeting Rust (Actix)

**Target Area**: Internal Logic / Rust (Actix) architecture
**Description**: An extensive operational guide for identifying and exploiting Blind SSRF via Webhooks within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Blind SSRF via Webhooks within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Rust (Actix) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on Blind SSRF via Webhooks. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Rust (Actix).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 144. Server-Side Request Forgery - SSRF via PDF Generation targeting Kong API Gateway

**Target Area**: Internal Logic / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via PDF Generation within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via PDF Generation within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Kong API Gateway parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via PDF Generation. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Kong API Gateway.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 145. Server-Side Request Forgery - SSRF via SVG Uploads targeting Ruby on Rails

**Target Area**: Internal Logic / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via SVG Uploads. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Ruby on Rails.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 146. Server-Side Request Forgery - SSRF to Localhost Services targeting Node.js/Express

**Target Area**: Internal Logic / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF to Localhost Services within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF to Localhost Services within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Node.js/Express parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF to Localhost Services. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Node.js/Express.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 147. Server-Side Request Forgery - SSRF via PDF Generation targeting GraphQL (Relay)

**Target Area**: Internal Logic / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via PDF Generation within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via PDF Generation within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via PDF Generation. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to GraphQL (Relay).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 148. Server-Side Request Forgery - SSRF via Image Processing Library targeting GraphQL (Relay)

**Target Area**: Internal Logic / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via Image Processing Library within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via Image Processing Library within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via Image Processing Library. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to GraphQL (Relay).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 149. Server-Side Request Forgery - Blind SSRF via Webhooks targeting Firebase

**Target Area**: Internal Logic / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting Blind SSRF via Webhooks within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Blind SSRF via Webhooks within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on Blind SSRF via Webhooks. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service via internal loopback requests.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Firebase.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 150. Server-Side Request Forgery - SSRF Filter Bypass via DNS Rebinding targeting Go (Gin)

**Target Area**: Internal Logic / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF Filter Bypass via DNS Rebinding within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF Filter Bypass via DNS Rebinding within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Gin) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF Filter Bypass via DNS Rebinding. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Go (Gin).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 151. Server-Side Request Forgery - SSRF Filter Bypass via DNS Rebinding targeting Django (Python)

**Target Area**: Internal Logic / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF Filter Bypass via DNS Rebinding within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF Filter Bypass via DNS Rebinding within a Third-party integration webhook. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Django (Python) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF Filter Bypass via DNS Rebinding. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Django (Python).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 152. Server-Side Request Forgery - SSRF Filter Bypass via Octal IP Encodings targeting Spring Boot (Java)

**Target Area**: Internal Logic / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Spring Boot (Java) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF Filter Bypass via Octal IP Encodings. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Spring Boot (Java).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 153. Server-Side Request Forgery - Blind SSRF via Webhooks targeting Supabase

**Target Area**: Internal Logic / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting Blind SSRF via Webhooks within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Blind SSRF via Webhooks within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Supabase parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on Blind SSRF via Webhooks. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service via internal loopback requests.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Supabase.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 154. Server-Side Request Forgery - SSRF to Localhost Services targeting Node.js/Express

**Target Area**: Internal Logic / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF to Localhost Services within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF to Localhost Services within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Node.js/Express parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF to Localhost Services. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Node.js/Express.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 155. Server-Side Request Forgery - SSRF via PDF Generation targeting Ruby on Rails

**Target Area**: Internal Logic / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via PDF Generation within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via PDF Generation within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via PDF Generation. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Ruby on Rails.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 156. Server-Side Request Forgery - SSRF Filter Bypass via Octal IP Encodings targeting Supabase

**Target Area**: Internal Logic / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Supabase parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Mobile application backend API. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF Filter Bypass via Octal IP Encodings. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Supabase.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 157. Server-Side Request Forgery - SSRF via Image Processing Library targeting Spring Boot (Java)

**Target Area**: Internal Logic / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via Image Processing Library within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via Image Processing Library within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Spring Boot (Java) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via Image Processing Library. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Spring Boot (Java).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 158. Server-Side Request Forgery - SSRF via SVG Uploads targeting Rust (Actix)

**Target Area**: Internal Logic / Rust (Actix) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Rust (Actix) parses underlying operating system calls or external HTTP requests.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if input is sanitized at the edge or passed blindly to backend functions.</step>
    <step>Formulate hypotheses focused on SSRF via SVG Uploads. Map out exactly how parameter injection could subvert the intended functionality.</step>
    <step>Generate specific, weaponized payloads designed to bypass common regular expression filters.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Rust (Actix).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 159. Server-Side Request Forgery - SSRF via Image Processing Library targeting Rust (Actix)

**Target Area**: Internal Logic / Rust (Actix) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via Image Processing Library within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via Image Processing Library within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Rust (Actix) handles user-supplied data in the context of SSRF via Image Processing Library.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF via Image Processing Library. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service via internal loopback requests.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Rust (Actix).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 160. Server-Side Request Forgery - SSRF against Cloud Metadata (AWS IMDSv2) targeting Symfony (PHP)

**Target Area**: Internal Logic / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Symfony (PHP) handles user-supplied data in the context of SSRF against Cloud Metadata (AWS IMDSv2).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF against Cloud Metadata (AWS IMDSv2). Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Symfony (PHP).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 161. Server-Side Request Forgery - SSRF via SVG Uploads targeting Firebase

**Target Area**: Internal Logic / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase handles user-supplied data in the context of SSRF via SVG Uploads.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF via SVG Uploads. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Firebase.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 162. Server-Side Request Forgery - Blind SSRF via Webhooks targeting Go (Fiber)

**Target Area**: Internal Logic / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting Blind SSRF via Webhooks within a Mobile application backend API. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Blind SSRF via Webhooks within a Mobile application backend API. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Fiber) handles user-supplied data in the context of Blind SSRF via Webhooks.</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Blind SSRF via Webhooks. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service via internal loopback requests.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Go (Fiber).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 163. Server-Side Request Forgery - SSRF to Localhost Services targeting Kong API Gateway

**Target Area**: Internal Logic / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF to Localhost Services within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF to Localhost Services within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Kong API Gateway handles user-supplied data in the context of SSRF to Localhost Services.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF to Localhost Services. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Kong API Gateway.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 164. Server-Side Request Forgery - SSRF via PDF Generation targeting Symfony (PHP)

**Target Area**: Internal Logic / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via PDF Generation within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via PDF Generation within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Symfony (PHP) handles user-supplied data in the context of SSRF via PDF Generation.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF via PDF Generation. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Symfony (PHP).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 165. Server-Side Request Forgery - SSRF against Cloud Metadata (GCP/Azure) targeting Flask (Python)

**Target Area**: Internal Logic / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (GCP/Azure) within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (GCP/Azure) within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Flask (Python) handles user-supplied data in the context of SSRF against Cloud Metadata (GCP/Azure).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF against Cloud Metadata (GCP/Azure). Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Flask (Python).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 166. Server-Side Request Forgery - SSRF Filter Bypass via Octal IP Encodings targeting Supabase

**Target Area**: Internal Logic / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Third-party integration webhook. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Third-party integration webhook. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Supabase handles user-supplied data in the context of SSRF Filter Bypass via Octal IP Encodings.</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF Filter Bypass via Octal IP Encodings. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Supabase.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 167. Server-Side Request Forgery - SSRF to Localhost Services targeting GraphQL (Relay)

**Target Area**: Internal Logic / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF to Localhost Services within a Multi-tenant application environment. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF to Localhost Services within a Multi-tenant application environment. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) handles user-supplied data in the context of SSRF to Localhost Services.</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF to Localhost Services. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to GraphQL (Relay).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 168. Server-Side Request Forgery - SSRF to Localhost Services targeting Spring Boot (Java)

**Target Area**: Internal Logic / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF to Localhost Services within a Third-party integration webhook. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF to Localhost Services within a Third-party integration webhook. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Spring Boot (Java) handles user-supplied data in the context of SSRF to Localhost Services.</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF to Localhost Services. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Spring Boot (Java).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 169. Server-Side Request Forgery - SSRF against Cloud Metadata (GCP/Azure) targeting GraphQL (Apollo)

**Target Area**: Internal Logic / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (GCP/Azure) within a Mobile application backend API. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (GCP/Azure) within a Mobile application backend API. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) handles user-supplied data in the context of SSRF against Cloud Metadata (GCP/Azure).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF against Cloud Metadata (GCP/Azure). Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to GraphQL (Apollo).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 170. Server-Side Request Forgery - SSRF against Cloud Metadata (GCP/Azure) targeting GraphQL (Apollo)

**Target Area**: Internal Logic / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (GCP/Azure) within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (GCP/Azure) within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) handles user-supplied data in the context of SSRF against Cloud Metadata (GCP/Azure).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF against Cloud Metadata (GCP/Azure). Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service via internal loopback requests.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to GraphQL (Apollo).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 171. Server-Side Request Forgery - Blind SSRF via Webhooks targeting Spring Boot (Java)

**Target Area**: Internal Logic / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting Blind SSRF via Webhooks within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Blind SSRF via Webhooks within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Spring Boot (Java) handles user-supplied data in the context of Blind SSRF via Webhooks.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Blind SSRF via Webhooks. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Spring Boot (Java).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 172. Server-Side Request Forgery - SSRF via Image Processing Library targeting AWS API Gateway

**Target Area**: Internal Logic / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via Image Processing Library within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via Image Processing Library within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how AWS API Gateway handles user-supplied data in the context of SSRF via Image Processing Library.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF via Image Processing Library. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service via internal loopback requests.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to AWS API Gateway.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 173. Server-Side Request Forgery - SSRF via XML External Entity (XXE) targeting Node.js/Express

**Target Area**: Internal Logic / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via XML External Entity (XXE) within a Third-party integration webhook. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via XML External Entity (XXE) within a Third-party integration webhook. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Node.js/Express handles user-supplied data in the context of SSRF via XML External Entity (XXE).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF via XML External Entity (XXE). Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Node.js/Express.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 174. Server-Side Request Forgery - SSRF Filter Bypass via DNS Rebinding targeting Laravel (PHP)

**Target Area**: Internal Logic / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF Filter Bypass via DNS Rebinding within a Mobile application backend API. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF Filter Bypass via DNS Rebinding within a Mobile application backend API. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) handles user-supplied data in the context of SSRF Filter Bypass via DNS Rebinding.</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF Filter Bypass via DNS Rebinding. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Laravel (PHP).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 175. Server-Side Request Forgery - SSRF via Image Processing Library targeting Apigee

**Target Area**: Internal Logic / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via Image Processing Library within a Multi-tenant application environment. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via Image Processing Library within a Multi-tenant application environment. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee handles user-supplied data in the context of SSRF via Image Processing Library.</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF via Image Processing Library. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service via internal loopback requests.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Apigee.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 176. Server-Side Request Forgery - SSRF against Cloud Metadata (AWS IMDSv2) targeting Flask (Python)

**Target Area**: Internal Logic / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Flask (Python) handles user-supplied data in the context of SSRF against Cloud Metadata (AWS IMDSv2).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF against Cloud Metadata (AWS IMDSv2). Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Flask (Python).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 177. Server-Side Request Forgery - SSRF against Internal Redis Instances targeting Symfony (PHP)

**Target Area**: Internal Logic / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Internal Redis Instances within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Internal Redis Instances within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Symfony (PHP) handles user-supplied data in the context of SSRF against Internal Redis Instances.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF against Internal Redis Instances. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Symfony (PHP).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 178. Server-Side Request Forgery - SSRF against Cloud Metadata (AWS IMDSv2) targeting Go (Gin)

**Target Area**: Internal Logic / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Gin) handles user-supplied data in the context of SSRF against Cloud Metadata (AWS IMDSv2).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF against Cloud Metadata (AWS IMDSv2). Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Go (Gin).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 179. Server-Side Request Forgery - SSRF Filter Bypass via Octal IP Encodings targeting Django (Python)

**Target Area**: Internal Logic / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Mobile application backend API. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Mobile application backend API. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Django (Python) handles user-supplied data in the context of SSRF Filter Bypass via Octal IP Encodings.</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF Filter Bypass via Octal IP Encodings. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Django (Python).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 180. Server-Side Request Forgery - SSRF against Internal Redis Instances targeting Firebase

**Target Area**: Internal Logic / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Internal Redis Instances within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Internal Redis Instances within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase handles user-supplied data in the context of SSRF against Internal Redis Instances.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF against Internal Redis Instances. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Firebase.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 181. Server-Side Request Forgery - SSRF to Localhost Services targeting Go (Fiber)

**Target Area**: Internal Logic / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF to Localhost Services within a Third-party integration webhook. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF to Localhost Services within a Third-party integration webhook. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Fiber) handles user-supplied data in the context of SSRF to Localhost Services.</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF to Localhost Services. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Go (Fiber).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 182. Server-Side Request Forgery - SSRF to Localhost Services targeting Ruby on Rails

**Target Area**: Internal Logic / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF to Localhost Services within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF to Localhost Services within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails handles user-supplied data in the context of SSRF to Localhost Services.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF to Localhost Services. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Ruby on Rails.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 183. Server-Side Request Forgery - SSRF Filter Bypass via DNS Rebinding targeting Node.js/Express

**Target Area**: Internal Logic / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF Filter Bypass via DNS Rebinding within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF Filter Bypass via DNS Rebinding within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Node.js/Express handles user-supplied data in the context of SSRF Filter Bypass via DNS Rebinding.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF Filter Bypass via DNS Rebinding. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Node.js/Express.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 184. Server-Side Request Forgery - SSRF via SVG Uploads targeting Go (Fiber)

**Target Area**: Internal Logic / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Fiber) handles user-supplied data in the context of SSRF via SVG Uploads.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF via SVG Uploads. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Go (Fiber).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 185. Server-Side Request Forgery - SSRF via Image Processing Library targeting Ruby on Rails

**Target Area**: Internal Logic / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via Image Processing Library within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via Image Processing Library within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails handles user-supplied data in the context of SSRF via Image Processing Library.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF via Image Processing Library. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Ruby on Rails.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 186. Server-Side Request Forgery - SSRF Filter Bypass via Octal IP Encodings targeting ASP.NET Core

**Target Area**: Internal Logic / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core handles user-supplied data in the context of SSRF Filter Bypass via Octal IP Encodings.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF Filter Bypass via Octal IP Encodings. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to ASP.NET Core.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 187. Server-Side Request Forgery - SSRF Filter Bypass via Octal IP Encodings targeting FastAPI

**Target Area**: Internal Logic / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how FastAPI handles user-supplied data in the context of SSRF Filter Bypass via Octal IP Encodings.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF Filter Bypass via Octal IP Encodings. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to FastAPI.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 188. Server-Side Request Forgery - SSRF to Localhost Services targeting Laravel (PHP)

**Target Area**: Internal Logic / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF to Localhost Services within a Multi-tenant application environment. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF to Localhost Services within a Multi-tenant application environment. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) handles user-supplied data in the context of SSRF to Localhost Services.</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF to Localhost Services. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Laravel (PHP).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 189. Server-Side Request Forgery - SSRF Filter Bypass via Octal IP Encodings targeting Django (Python)

**Target Area**: Internal Logic / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Django (Python) handles user-supplied data in the context of SSRF Filter Bypass via Octal IP Encodings.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF Filter Bypass via Octal IP Encodings. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service via internal loopback requests.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Django (Python).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 190. Server-Side Request Forgery - SSRF via SVG Uploads targeting Flask (Python)

**Target Area**: Internal Logic / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Flask (Python) handles user-supplied data in the context of SSRF via SVG Uploads.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF via SVG Uploads. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Flask (Python).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 191. Server-Side Request Forgery - Blind SSRF via Webhooks targeting Firebase

**Target Area**: Internal Logic / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting Blind SSRF via Webhooks within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Blind SSRF via Webhooks within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase handles user-supplied data in the context of Blind SSRF via Webhooks.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Blind SSRF via Webhooks. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Firebase.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 192. Server-Side Request Forgery - Blind SSRF via Webhooks targeting Go (Fiber)

**Target Area**: Internal Logic / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting Blind SSRF via Webhooks within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Blind SSRF via Webhooks within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Fiber) handles user-supplied data in the context of Blind SSRF via Webhooks.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Blind SSRF via Webhooks. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service via internal loopback requests.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Go (Fiber).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 193. Server-Side Request Forgery - SSRF to Localhost Services targeting ASP.NET Core

**Target Area**: Internal Logic / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF to Localhost Services within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF to Localhost Services within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core handles user-supplied data in the context of SSRF to Localhost Services.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF to Localhost Services. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to ASP.NET Core.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 194. Server-Side Request Forgery - SSRF against Cloud Metadata (AWS IMDSv2) targeting Go (Gin)

**Target Area**: Internal Logic / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Gin) handles user-supplied data in the context of SSRF against Cloud Metadata (AWS IMDSv2).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF against Cloud Metadata (AWS IMDSv2). Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Go (Gin).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 195. Server-Side Request Forgery - SSRF via XML External Entity (XXE) targeting GraphQL (Relay)

**Target Area**: Internal Logic / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via XML External Entity (XXE) within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via XML External Entity (XXE) within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) handles user-supplied data in the context of SSRF via XML External Entity (XXE).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF via XML External Entity (XXE). Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service via internal loopback requests.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to GraphQL (Relay).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 196. Server-Side Request Forgery - Blind SSRF via Webhooks targeting GraphQL (Relay)

**Target Area**: Internal Logic / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting Blind SSRF via Webhooks within a Mobile application backend API. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Blind SSRF via Webhooks within a Mobile application backend API. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) handles user-supplied data in the context of Blind SSRF via Webhooks.</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Blind SSRF via Webhooks. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to GraphQL (Relay).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 197. Server-Side Request Forgery - SSRF Filter Bypass via Octal IP Encodings targeting Azure API Management

**Target Area**: Internal Logic / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Mobile application backend API. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Mobile application backend API. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Azure API Management handles user-supplied data in the context of SSRF Filter Bypass via Octal IP Encodings.</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF Filter Bypass via Octal IP Encodings. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Azure API Management.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 198. Server-Side Request Forgery - Blind SSRF via Webhooks targeting Supabase

**Target Area**: Internal Logic / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting Blind SSRF via Webhooks within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Blind SSRF via Webhooks within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Supabase handles user-supplied data in the context of Blind SSRF via Webhooks.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Blind SSRF via Webhooks. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Supabase.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 199. Server-Side Request Forgery - SSRF to Localhost Services targeting Go (Fiber)

**Target Area**: Internal Logic / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF to Localhost Services within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF to Localhost Services within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Fiber) handles user-supplied data in the context of SSRF to Localhost Services.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF to Localhost Services. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Go (Fiber).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 200. Server-Side Request Forgery - SSRF against Cloud Metadata (GCP/Azure) targeting Rust (Actix)

**Target Area**: Internal Logic / Rust (Actix) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (GCP/Azure) within a Third-party integration webhook. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (GCP/Azure) within a Third-party integration webhook. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Rust (Actix) handles user-supplied data in the context of SSRF against Cloud Metadata (GCP/Azure).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF against Cloud Metadata (GCP/Azure). Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Rust (Actix).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 201. Server-Side Request Forgery - SSRF via XML External Entity (XXE) targeting Node.js/Express

**Target Area**: Internal Logic / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via XML External Entity (XXE) within a Multi-tenant application environment. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via XML External Entity (XXE) within a Multi-tenant application environment. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Node.js/Express handles user-supplied data in the context of SSRF via XML External Entity (XXE).</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF via XML External Entity (XXE). Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Node.js/Express.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 202. Server-Side Request Forgery - SSRF via PDF Generation targeting Laravel (PHP)

**Target Area**: Internal Logic / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via PDF Generation within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via PDF Generation within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) handles user-supplied data in the context of SSRF via PDF Generation.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF via PDF Generation. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Laravel (PHP).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 203. Server-Side Request Forgery - Blind SSRF via Webhooks targeting Flask (Python)

**Target Area**: Internal Logic / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting Blind SSRF via Webhooks within a Third-party integration webhook. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Blind SSRF via Webhooks within a Third-party integration webhook. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Flask (Python) handles user-supplied data in the context of Blind SSRF via Webhooks.</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Blind SSRF via Webhooks. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service via internal loopback requests.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Flask (Python).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 204. Server-Side Request Forgery - SSRF Filter Bypass via Octal IP Encodings targeting ASP.NET Core

**Target Area**: Internal Logic / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core handles user-supplied data in the context of SSRF Filter Bypass via Octal IP Encodings.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF Filter Bypass via Octal IP Encodings. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to ASP.NET Core.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 205. Server-Side Request Forgery - SSRF Filter Bypass via Octal IP Encodings targeting Kong API Gateway

**Target Area**: Internal Logic / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Kong API Gateway handles user-supplied data in the context of SSRF Filter Bypass via Octal IP Encodings.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF Filter Bypass via Octal IP Encodings. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service via internal loopback requests.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Kong API Gateway.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 206. Server-Side Request Forgery - SSRF via PDF Generation targeting Firebase

**Target Area**: Internal Logic / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via PDF Generation within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via PDF Generation within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase handles user-supplied data in the context of SSRF via PDF Generation.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF via PDF Generation. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Firebase.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 207. Server-Side Request Forgery - Blind SSRF via Webhooks targeting FastAPI

**Target Area**: Internal Logic / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting Blind SSRF via Webhooks within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Blind SSRF via Webhooks within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how FastAPI handles user-supplied data in the context of Blind SSRF via Webhooks.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Blind SSRF via Webhooks. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to FastAPI.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 208. Server-Side Request Forgery - SSRF against Cloud Metadata (GCP/Azure) targeting Azure API Management

**Target Area**: Internal Logic / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (GCP/Azure) within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (GCP/Azure) within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Azure API Management handles user-supplied data in the context of SSRF against Cloud Metadata (GCP/Azure).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF against Cloud Metadata (GCP/Azure). Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Azure API Management.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 209. Server-Side Request Forgery - SSRF via Image Processing Library targeting Symfony (PHP)

**Target Area**: Internal Logic / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via Image Processing Library within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via Image Processing Library within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Symfony (PHP) handles user-supplied data in the context of SSRF via Image Processing Library.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF via Image Processing Library. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service via internal loopback requests.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Symfony (PHP).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 210. Server-Side Request Forgery - SSRF via Image Processing Library targeting GraphQL (Relay)

**Target Area**: Internal Logic / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via Image Processing Library within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via Image Processing Library within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) handles user-supplied data in the context of SSRF via Image Processing Library.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF via Image Processing Library. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to GraphQL (Relay).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 211. Server-Side Request Forgery - SSRF against Cloud Metadata (AWS IMDSv2) targeting ASP.NET Core

**Target Area**: Internal Logic / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core handles user-supplied data in the context of SSRF against Cloud Metadata (AWS IMDSv2).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF against Cloud Metadata (AWS IMDSv2). Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to ASP.NET Core.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 212. Server-Side Request Forgery - SSRF Filter Bypass via Octal IP Encodings targeting Symfony (PHP)

**Target Area**: Internal Logic / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Symfony (PHP) handles user-supplied data in the context of SSRF Filter Bypass via Octal IP Encodings.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF Filter Bypass via Octal IP Encodings. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Symfony (PHP).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 213. Server-Side Request Forgery - SSRF via XML External Entity (XXE) targeting Flask (Python)

**Target Area**: Internal Logic / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via XML External Entity (XXE) within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via XML External Entity (XXE) within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Flask (Python) handles user-supplied data in the context of SSRF via XML External Entity (XXE).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF via XML External Entity (XXE). Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Flask (Python).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 214. Server-Side Request Forgery - SSRF against Cloud Metadata (AWS IMDSv2) targeting GraphQL (Relay)

**Target Area**: Internal Logic / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) handles user-supplied data in the context of SSRF against Cloud Metadata (AWS IMDSv2).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF against Cloud Metadata (AWS IMDSv2). Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to GraphQL (Relay).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 215. Server-Side Request Forgery - SSRF against Cloud Metadata (AWS IMDSv2) targeting Rust (Actix)

**Target Area**: Internal Logic / Rust (Actix) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Rust (Actix) handles user-supplied data in the context of SSRF against Cloud Metadata (AWS IMDSv2).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF against Cloud Metadata (AWS IMDSv2). Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service via internal loopback requests.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Rust (Actix).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 216. Server-Side Request Forgery - SSRF Filter Bypass via Octal IP Encodings targeting Node.js/Express

**Target Area**: Internal Logic / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Node.js/Express handles user-supplied data in the context of SSRF Filter Bypass via Octal IP Encodings.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF Filter Bypass via Octal IP Encodings. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service via internal loopback requests.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Node.js/Express.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 217. Server-Side Request Forgery - Blind SSRF via Webhooks targeting GraphQL (Relay)

**Target Area**: Internal Logic / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting Blind SSRF via Webhooks within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Blind SSRF via Webhooks within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) handles user-supplied data in the context of Blind SSRF via Webhooks.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Blind SSRF via Webhooks. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to GraphQL (Relay).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 218. Server-Side Request Forgery - SSRF against Internal Redis Instances targeting Apigee

**Target Area**: Internal Logic / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Internal Redis Instances within a Third-party integration webhook. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Internal Redis Instances within a Third-party integration webhook. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee handles user-supplied data in the context of SSRF against Internal Redis Instances.</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF against Internal Redis Instances. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Apigee.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 219. Server-Side Request Forgery - SSRF via SVG Uploads targeting Flask (Python)

**Target Area**: Internal Logic / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Flask (Python) handles user-supplied data in the context of SSRF via SVG Uploads.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF via SVG Uploads. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Flask (Python).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 220. Server-Side Request Forgery - SSRF Filter Bypass via DNS Rebinding targeting Laravel (PHP)

**Target Area**: Internal Logic / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF Filter Bypass via DNS Rebinding within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF Filter Bypass via DNS Rebinding within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) handles user-supplied data in the context of SSRF Filter Bypass via DNS Rebinding.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF Filter Bypass via DNS Rebinding. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Laravel (PHP).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 221. Server-Side Request Forgery - SSRF via PDF Generation targeting Laravel (PHP)

**Target Area**: Internal Logic / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via PDF Generation within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via PDF Generation within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) handles user-supplied data in the context of SSRF via PDF Generation.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF via PDF Generation. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service via internal loopback requests.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Laravel (PHP).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 222. Server-Side Request Forgery - SSRF via PDF Generation targeting Go (Fiber)

**Target Area**: Internal Logic / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via PDF Generation within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via PDF Generation within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Fiber) handles user-supplied data in the context of SSRF via PDF Generation.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF via PDF Generation. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Go (Fiber).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 223. Server-Side Request Forgery - SSRF against Internal Redis Instances targeting AWS API Gateway

**Target Area**: Internal Logic / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Internal Redis Instances within a Multi-tenant application environment. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Internal Redis Instances within a Multi-tenant application environment. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how AWS API Gateway handles user-supplied data in the context of SSRF against Internal Redis Instances.</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF against Internal Redis Instances. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to AWS API Gateway.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 224. Server-Side Request Forgery - SSRF via Image Processing Library targeting ASP.NET Core

**Target Area**: Internal Logic / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via Image Processing Library within a Third-party integration webhook. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via Image Processing Library within a Third-party integration webhook. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core handles user-supplied data in the context of SSRF via Image Processing Library.</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF via Image Processing Library. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to ASP.NET Core.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 225. Server-Side Request Forgery - SSRF against Cloud Metadata (AWS IMDSv2) targeting Ruby on Rails

**Target Area**: Internal Logic / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails handles user-supplied data in the context of SSRF against Cloud Metadata (AWS IMDSv2).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF against Cloud Metadata (AWS IMDSv2). Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Ruby on Rails.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 226. Server-Side Request Forgery - SSRF via Image Processing Library targeting GraphQL (Apollo)

**Target Area**: Internal Logic / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via Image Processing Library within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via Image Processing Library within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) handles user-supplied data in the context of SSRF via Image Processing Library.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF via Image Processing Library. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to GraphQL (Apollo).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 227. Server-Side Request Forgery - SSRF via XML External Entity (XXE) targeting Supabase

**Target Area**: Internal Logic / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via XML External Entity (XXE) within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via XML External Entity (XXE) within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Supabase handles user-supplied data in the context of SSRF via XML External Entity (XXE).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF via XML External Entity (XXE). Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Supabase.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 228. Server-Side Request Forgery - SSRF against Cloud Metadata (GCP/Azure) targeting Laravel (PHP)

**Target Area**: Internal Logic / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (GCP/Azure) within a Mobile application backend API. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (GCP/Azure) within a Mobile application backend API. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) handles user-supplied data in the context of SSRF against Cloud Metadata (GCP/Azure).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF against Cloud Metadata (GCP/Azure). Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Laravel (PHP).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 229. Server-Side Request Forgery - SSRF via PDF Generation targeting Ruby on Rails

**Target Area**: Internal Logic / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via PDF Generation within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via PDF Generation within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails handles user-supplied data in the context of SSRF via PDF Generation.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF via PDF Generation. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Ruby on Rails.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 230. Server-Side Request Forgery - SSRF via PDF Generation targeting Firebase

**Target Area**: Internal Logic / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via PDF Generation within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via PDF Generation within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase handles user-supplied data in the context of SSRF via PDF Generation.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF via PDF Generation. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Firebase.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 231. Server-Side Request Forgery - SSRF via XML External Entity (XXE) targeting Laravel (PHP)

**Target Area**: Internal Logic / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via XML External Entity (XXE) within a Mobile application backend API. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via XML External Entity (XXE) within a Mobile application backend API. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) handles user-supplied data in the context of SSRF via XML External Entity (XXE).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF via XML External Entity (XXE). Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service via internal loopback requests.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Laravel (PHP).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 232. Server-Side Request Forgery - Blind SSRF via Webhooks targeting Apigee

**Target Area**: Internal Logic / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting Blind SSRF via Webhooks within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Blind SSRF via Webhooks within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee handles user-supplied data in the context of Blind SSRF via Webhooks.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Blind SSRF via Webhooks. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Apigee.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 233. Server-Side Request Forgery - SSRF Filter Bypass via Octal IP Encodings targeting GraphQL (Relay)

**Target Area**: Internal Logic / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Multi-tenant application environment. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF Filter Bypass via Octal IP Encodings within a Multi-tenant application environment. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) handles user-supplied data in the context of SSRF Filter Bypass via Octal IP Encodings.</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF Filter Bypass via Octal IP Encodings. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to GraphQL (Relay).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 234. Server-Side Request Forgery - SSRF against Cloud Metadata (GCP/Azure) targeting Flask (Python)

**Target Area**: Internal Logic / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (GCP/Azure) within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (GCP/Azure) within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Flask (Python) handles user-supplied data in the context of SSRF against Cloud Metadata (GCP/Azure).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF against Cloud Metadata (GCP/Azure). Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Flask (Python).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 235. Server-Side Request Forgery - SSRF via PDF Generation targeting Node.js/Express

**Target Area**: Internal Logic / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via PDF Generation within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via PDF Generation within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Node.js/Express handles user-supplied data in the context of SSRF via PDF Generation.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF via PDF Generation. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Node.js/Express.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 236. Server-Side Request Forgery - SSRF via PDF Generation targeting Supabase

**Target Area**: Internal Logic / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via PDF Generation within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via PDF Generation within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Supabase handles user-supplied data in the context of SSRF via PDF Generation.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF via PDF Generation. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Supabase.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 237. Server-Side Request Forgery - SSRF via SVG Uploads targeting Symfony (PHP)

**Target Area**: Internal Logic / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Symfony (PHP) handles user-supplied data in the context of SSRF via SVG Uploads.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF via SVG Uploads. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service via internal loopback requests.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Symfony (PHP).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 238. Server-Side Request Forgery - SSRF against Cloud Metadata (AWS IMDSv2) targeting Rust (Actix)

**Target Area**: Internal Logic / Rust (Actix) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF against Cloud Metadata (AWS IMDSv2) within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Rust (Actix) handles user-supplied data in the context of SSRF against Cloud Metadata (AWS IMDSv2).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF against Cloud Metadata (AWS IMDSv2). Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting into internal CI/CD pipelines.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Rust (Actix).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 239. Server-Side Request Forgery - Blind SSRF via Webhooks targeting Kong API Gateway

**Target Area**: Internal Logic / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting Blind SSRF via Webhooks within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Blind SSRF via Webhooks within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Kong API Gateway handles user-supplied data in the context of Blind SSRF via Webhooks.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Blind SSRF via Webhooks. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Interaction with unauthenticated administrative microservices.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Kong API Gateway.
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 240. Server-Side Request Forgery - SSRF via SVG Uploads targeting Laravel (PHP)

**Target Area**: Internal Logic / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Third-party integration webhook. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via SVG Uploads within a Third-party integration webhook. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) handles user-supplied data in the context of SSRF via SVG Uploads.</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF via SVG Uploads. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Laravel (PHP).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 241. Server-Side Request Forgery - SSRF via Image Processing Library targeting Go (Gin)

**Target Area**: Internal Logic / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via Image Processing Library within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via Image Processing Library within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Gin) handles user-supplied data in the context of SSRF via Image Processing Library.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF via Image Processing Library. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of temporary cloud security credentials.</step>
  </execution_steps>
  <output_format>
  A comprehensive Markdown report section containing:
  - The analytical breakdown of the flaw.
  - The weaponized proof-of-concept (curl command or Burp Suite HTTP request).
  - Remediation advice specific to Go (Gin).
  </output_format>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

