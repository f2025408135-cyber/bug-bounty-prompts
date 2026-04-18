# SQL Injection Bug Bounty Skills

A curated, extensive collection of 159 advanced skills for SQLi bug bounty hunting. Built for the Bug Bounty System Harness.

### 1. SQL Injection - NoSQL Injection (CouchDB) targeting Rust (Actix)

**Target Area**: Edge Proxies / Databases / Parsers / Rust (Actix) architecture
**Description**: An extensive operational guide for identifying and exploiting NoSQL Injection (CouchDB) within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting NoSQL Injection (CouchDB) within a Third-party integration webhook. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Rust (Actix) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on NoSQL Injection (CouchDB). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 2. SQL Injection - Boolean-Based Blind SQLi targeting Go (Gin)

**Target Area**: Edge Proxies / Databases / Parsers / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting Boolean-Based Blind SQLi within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Boolean-Based Blind SQLi within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Gin) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Boolean-Based Blind SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 3. SQL Injection - SQLi in ORDER BY clauses targeting Go (Fiber)

**Target Area**: Edge Proxies / Databases / Parsers / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting SQLi in ORDER BY clauses within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SQLi in ORDER BY clauses within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Fiber) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on SQLi in ORDER BY clauses. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 4. SQL Injection - Union-Based SQLi targeting GraphQL (Relay)

**Target Area**: Edge Proxies / Databases / Parsers / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting Union-Based SQLi within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Union-Based SQLi within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Union-Based SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 5. SQL Injection - Out-of-Band (OOB) SQLi targeting GraphQL (Apollo)

**Target Area**: Edge Proxies / Databases / Parsers / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting Out-of-Band (OOB) SQLi within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Out-of-Band (OOB) SQLi within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Out-of-Band (OOB) SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 6. SQL Injection - NoSQL Injection (MongoDB) targeting Symfony (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting NoSQL Injection (MongoDB) within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting NoSQL Injection (MongoDB) within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Symfony (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on NoSQL Injection (MongoDB). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 7. SQL Injection - Error-Based SQLi targeting Go (Gin)

**Target Area**: Edge Proxies / Databases / Parsers / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting Error-Based SQLi within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Error-Based SQLi within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Gin) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Error-Based SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 8. SQL Injection - Boolean-Based Blind SQLi targeting Ruby on Rails

**Target Area**: Edge Proxies / Databases / Parsers / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting Boolean-Based Blind SQLi within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Boolean-Based Blind SQLi within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Boolean-Based Blind SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 9. SQL Injection - Time-Based Blind SQLi targeting GraphQL (Relay)

**Target Area**: Edge Proxies / Databases / Parsers / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting Time-Based Blind SQLi within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Time-Based Blind SQLi within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Time-Based Blind SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 10. SQL Injection - Boolean-Based Blind SQLi targeting Symfony (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting Boolean-Based Blind SQLi within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Boolean-Based Blind SQLi within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Symfony (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Boolean-Based Blind SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 11. SQL Injection - NoSQL Injection (MongoDB) targeting Rust (Actix)

**Target Area**: Edge Proxies / Databases / Parsers / Rust (Actix) architecture
**Description**: An extensive operational guide for identifying and exploiting NoSQL Injection (MongoDB) within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting NoSQL Injection (MongoDB) within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Rust (Actix) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on NoSQL Injection (MongoDB). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 12. SQL Injection - Second-Order SQLi targeting Kong API Gateway

**Target Area**: Edge Proxies / Databases / Parsers / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting Second-Order SQLi within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Second-Order SQLi within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Kong API Gateway parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Second-Order SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 13. SQL Injection - Boolean-Based Blind SQLi targeting ASP.NET Core

**Target Area**: Edge Proxies / Databases / Parsers / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting Boolean-Based Blind SQLi within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Boolean-Based Blind SQLi within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Boolean-Based Blind SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 14. SQL Injection - Second-Order SQLi targeting FastAPI

**Target Area**: Edge Proxies / Databases / Parsers / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting Second-Order SQLi within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Second-Order SQLi within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how FastAPI parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Second-Order SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 15. SQL Injection - Boolean-Based Blind SQLi targeting ASP.NET Core

**Target Area**: Edge Proxies / Databases / Parsers / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting Boolean-Based Blind SQLi within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Boolean-Based Blind SQLi within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Boolean-Based Blind SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 16. SQL Injection - NoSQL Injection (CouchDB) targeting Spring Boot (Java)

**Target Area**: Edge Proxies / Databases / Parsers / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting NoSQL Injection (CouchDB) within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting NoSQL Injection (CouchDB) within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Spring Boot (Java) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on NoSQL Injection (CouchDB). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 17. SQL Injection - SQLi in ORDER BY clauses targeting Apigee

**Target Area**: Edge Proxies / Databases / Parsers / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting SQLi in ORDER BY clauses within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SQLi in ORDER BY clauses within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on SQLi in ORDER BY clauses. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 18. SQL Injection - Union-Based SQLi targeting ASP.NET Core

**Target Area**: Edge Proxies / Databases / Parsers / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting Union-Based SQLi within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Union-Based SQLi within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Union-Based SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 19. SQL Injection - NoSQL Injection (MongoDB) targeting Go (Gin)

**Target Area**: Edge Proxies / Databases / Parsers / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting NoSQL Injection (MongoDB) within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting NoSQL Injection (MongoDB) within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Gin) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on NoSQL Injection (MongoDB). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 20. SQL Injection - Time-Based Blind SQLi targeting Laravel (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting Time-Based Blind SQLi within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Time-Based Blind SQLi within a Third-party integration webhook. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Time-Based Blind SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 21. SQL Injection - NoSQL Injection (MongoDB) targeting ASP.NET Core

**Target Area**: Edge Proxies / Databases / Parsers / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting NoSQL Injection (MongoDB) within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting NoSQL Injection (MongoDB) within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on NoSQL Injection (MongoDB). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 22. SQL Injection - NoSQL Injection (CouchDB) targeting Go (Gin)

**Target Area**: Edge Proxies / Databases / Parsers / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting NoSQL Injection (CouchDB) within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting NoSQL Injection (CouchDB) within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Gin) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on NoSQL Injection (CouchDB). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 23. SQL Injection - Second-Order SQLi targeting Firebase

**Target Area**: Edge Proxies / Databases / Parsers / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting Second-Order SQLi within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Second-Order SQLi within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Second-Order SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 24. SQL Injection - Time-Based Blind SQLi targeting ASP.NET Core

**Target Area**: Edge Proxies / Databases / Parsers / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting Time-Based Blind SQLi within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Time-Based Blind SQLi within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Time-Based Blind SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 25. SQL Injection - NoSQL Injection (CouchDB) targeting Azure API Management

**Target Area**: Edge Proxies / Databases / Parsers / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting NoSQL Injection (CouchDB) within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting NoSQL Injection (CouchDB) within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Azure API Management parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on NoSQL Injection (CouchDB). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 26. SQL Injection - Boolean-Based Blind SQLi targeting Symfony (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting Boolean-Based Blind SQLi within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Boolean-Based Blind SQLi within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Symfony (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Boolean-Based Blind SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 27. SQL Injection - SQLi in ORDER BY clauses targeting Apigee

**Target Area**: Edge Proxies / Databases / Parsers / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting SQLi in ORDER BY clauses within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SQLi in ORDER BY clauses within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on SQLi in ORDER BY clauses. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 28. SQL Injection - Time-Based Blind SQLi targeting Rust (Actix)

**Target Area**: Edge Proxies / Databases / Parsers / Rust (Actix) architecture
**Description**: An extensive operational guide for identifying and exploiting Time-Based Blind SQLi within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Time-Based Blind SQLi within a Third-party integration webhook. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Rust (Actix) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Time-Based Blind SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 29. SQL Injection - SQLi in ORDER BY clauses targeting Supabase

**Target Area**: Edge Proxies / Databases / Parsers / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting SQLi in ORDER BY clauses within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SQLi in ORDER BY clauses within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Supabase parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on SQLi in ORDER BY clauses. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 30. SQL Injection - NoSQL Injection (MongoDB) targeting Ruby on Rails

**Target Area**: Edge Proxies / Databases / Parsers / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting NoSQL Injection (MongoDB) within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting NoSQL Injection (MongoDB) within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on NoSQL Injection (MongoDB). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 31. SQL Injection - Out-of-Band (OOB) SQLi targeting GraphQL (Apollo)

**Target Area**: Edge Proxies / Databases / Parsers / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting Out-of-Band (OOB) SQLi within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Out-of-Band (OOB) SQLi within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Out-of-Band (OOB) SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 32. SQL Injection - NoSQL Injection (MongoDB) targeting Symfony (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting NoSQL Injection (MongoDB) within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting NoSQL Injection (MongoDB) within a Third-party integration webhook. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Symfony (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on NoSQL Injection (MongoDB). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 33. SQL Injection - Second-Order SQLi targeting Apigee

**Target Area**: Edge Proxies / Databases / Parsers / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting Second-Order SQLi within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Second-Order SQLi within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Second-Order SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 34. SQL Injection - Union-Based SQLi targeting Ruby on Rails

**Target Area**: Edge Proxies / Databases / Parsers / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting Union-Based SQLi within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Union-Based SQLi within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Union-Based SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 35. SQL Injection - Union-Based SQLi targeting Kong API Gateway

**Target Area**: Edge Proxies / Databases / Parsers / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting Union-Based SQLi within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Union-Based SQLi within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Kong API Gateway parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Union-Based SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 36. SQL Injection - SQLi via HTTP Headers targeting Supabase

**Target Area**: Edge Proxies / Databases / Parsers / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting SQLi via HTTP Headers within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SQLi via HTTP Headers within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Supabase parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on SQLi via HTTP Headers. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 37. SQL Injection - SQLi in ORDER BY clauses targeting Azure API Management

**Target Area**: Edge Proxies / Databases / Parsers / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting SQLi in ORDER BY clauses within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SQLi in ORDER BY clauses within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Azure API Management parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on SQLi in ORDER BY clauses. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 38. SQL Injection - Second-Order SQLi targeting Apigee

**Target Area**: Edge Proxies / Databases / Parsers / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting Second-Order SQLi within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Second-Order SQLi within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Second-Order SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 39. SQL Injection - Time-Based Blind SQLi targeting GraphQL (Apollo)

**Target Area**: Edge Proxies / Databases / Parsers / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting Time-Based Blind SQLi within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Time-Based Blind SQLi within a Third-party integration webhook. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Time-Based Blind SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 40. SQL Injection - Boolean-Based Blind SQLi targeting Azure API Management

**Target Area**: Edge Proxies / Databases / Parsers / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting Boolean-Based Blind SQLi within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Boolean-Based Blind SQLi within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Azure API Management parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Boolean-Based Blind SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 41. SQL Injection - Error-Based SQLi targeting Laravel (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting Error-Based SQLi within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Error-Based SQLi within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Error-Based SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 42. SQL Injection - SQLi in ORDER BY clauses targeting Azure API Management

**Target Area**: Edge Proxies / Databases / Parsers / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting SQLi in ORDER BY clauses within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SQLi in ORDER BY clauses within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Azure API Management parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on SQLi in ORDER BY clauses. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 43. SQL Injection - Union-Based SQLi targeting Flask (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting Union-Based SQLi within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Union-Based SQLi within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Flask (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Union-Based SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 44. SQL Injection - NoSQL Injection (CouchDB) targeting Supabase

**Target Area**: Edge Proxies / Databases / Parsers / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting NoSQL Injection (CouchDB) within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting NoSQL Injection (CouchDB) within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Supabase parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on NoSQL Injection (CouchDB). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 45. SQL Injection - Out-of-Band (OOB) SQLi targeting AWS API Gateway

**Target Area**: Edge Proxies / Databases / Parsers / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting Out-of-Band (OOB) SQLi within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Out-of-Band (OOB) SQLi within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how AWS API Gateway parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Out-of-Band (OOB) SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 46. SQL Injection - SQLi via HTTP Headers targeting ASP.NET Core

**Target Area**: Edge Proxies / Databases / Parsers / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting SQLi via HTTP Headers within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SQLi via HTTP Headers within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on SQLi via HTTP Headers. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 47. SQL Injection - Boolean-Based Blind SQLi targeting Firebase

**Target Area**: Edge Proxies / Databases / Parsers / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting Boolean-Based Blind SQLi within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Boolean-Based Blind SQLi within a Third-party integration webhook. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Boolean-Based Blind SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 48. SQL Injection - NoSQL Injection (CouchDB) targeting Symfony (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting NoSQL Injection (CouchDB) within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting NoSQL Injection (CouchDB) within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Symfony (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on NoSQL Injection (CouchDB). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 49. SQL Injection - Time-Based Blind SQLi targeting GraphQL (Apollo)

**Target Area**: Edge Proxies / Databases / Parsers / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting Time-Based Blind SQLi within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Time-Based Blind SQLi within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Time-Based Blind SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 50. SQL Injection - NoSQL Injection (CouchDB) targeting Django (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting NoSQL Injection (CouchDB) within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting NoSQL Injection (CouchDB) within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Django (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on NoSQL Injection (CouchDB). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 51. SQL Injection - Out-of-Band (OOB) SQLi targeting Django (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting Out-of-Band (OOB) SQLi within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Out-of-Band (OOB) SQLi within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Django (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Out-of-Band (OOB) SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 52. SQL Injection - NoSQL Injection (CouchDB) targeting Laravel (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting NoSQL Injection (CouchDB) within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting NoSQL Injection (CouchDB) within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on NoSQL Injection (CouchDB). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 53. SQL Injection - SQLi via HTTP Headers targeting Azure API Management

**Target Area**: Edge Proxies / Databases / Parsers / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting SQLi via HTTP Headers within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SQLi via HTTP Headers within a Third-party integration webhook. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Azure API Management parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on SQLi via HTTP Headers. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 54. SQL Injection - SQLi in ORDER BY clauses targeting Kong API Gateway

**Target Area**: Edge Proxies / Databases / Parsers / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting SQLi in ORDER BY clauses within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SQLi in ORDER BY clauses within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Kong API Gateway parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on SQLi in ORDER BY clauses. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 55. SQL Injection - Time-Based Blind SQLi targeting Kong API Gateway

**Target Area**: Edge Proxies / Databases / Parsers / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting Time-Based Blind SQLi within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Time-Based Blind SQLi within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Kong API Gateway parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Time-Based Blind SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 56. SQL Injection - NoSQL Injection (CouchDB) targeting Kong API Gateway

**Target Area**: Edge Proxies / Databases / Parsers / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting NoSQL Injection (CouchDB) within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting NoSQL Injection (CouchDB) within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Kong API Gateway parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on NoSQL Injection (CouchDB). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 57. SQL Injection - SQLi in ORDER BY clauses targeting Apigee

**Target Area**: Edge Proxies / Databases / Parsers / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting SQLi in ORDER BY clauses within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SQLi in ORDER BY clauses within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on SQLi in ORDER BY clauses. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 58. SQL Injection - Second-Order SQLi targeting Django (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting Second-Order SQLi within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Second-Order SQLi within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Django (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Second-Order SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 59. SQL Injection - Second-Order SQLi targeting Flask (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting Second-Order SQLi within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Second-Order SQLi within a Third-party integration webhook. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Flask (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Second-Order SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 60. SQL Injection - NoSQL Injection (MongoDB) targeting Firebase

**Target Area**: Edge Proxies / Databases / Parsers / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting NoSQL Injection (MongoDB) within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting NoSQL Injection (MongoDB) within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on NoSQL Injection (MongoDB). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 61. SQL Injection - NoSQL Injection (CouchDB) targeting Go (Fiber)

**Target Area**: Edge Proxies / Databases / Parsers / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting NoSQL Injection (CouchDB) within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting NoSQL Injection (CouchDB) within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Fiber) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on NoSQL Injection (CouchDB). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 62. SQL Injection - Time-Based Blind SQLi targeting Rust (Actix)

**Target Area**: Edge Proxies / Databases / Parsers / Rust (Actix) architecture
**Description**: An extensive operational guide for identifying and exploiting Time-Based Blind SQLi within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Time-Based Blind SQLi within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Rust (Actix) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Time-Based Blind SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 63. SQL Injection - NoSQL Injection (MongoDB) targeting Spring Boot (Java)

**Target Area**: Edge Proxies / Databases / Parsers / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting NoSQL Injection (MongoDB) within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting NoSQL Injection (MongoDB) within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Spring Boot (Java) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on NoSQL Injection (MongoDB). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 64. SQL Injection - NoSQL Injection (CouchDB) targeting Laravel (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting NoSQL Injection (CouchDB) within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting NoSQL Injection (CouchDB) within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on NoSQL Injection (CouchDB). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 65. SQL Injection - Boolean-Based Blind SQLi targeting GraphQL (Apollo)

**Target Area**: Edge Proxies / Databases / Parsers / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting Boolean-Based Blind SQLi within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Boolean-Based Blind SQLi within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Boolean-Based Blind SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 66. SQL Injection - SQLi in ORDER BY clauses targeting ASP.NET Core

**Target Area**: Edge Proxies / Databases / Parsers / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting SQLi in ORDER BY clauses within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SQLi in ORDER BY clauses within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on SQLi in ORDER BY clauses. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 67. SQL Injection - Out-of-Band (OOB) SQLi targeting Supabase

**Target Area**: Edge Proxies / Databases / Parsers / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting Out-of-Band (OOB) SQLi within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Out-of-Band (OOB) SQLi within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Supabase parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Out-of-Band (OOB) SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 68. SQL Injection - Out-of-Band (OOB) SQLi targeting Azure API Management

**Target Area**: Edge Proxies / Databases / Parsers / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting Out-of-Band (OOB) SQLi within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Out-of-Band (OOB) SQLi within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Azure API Management parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Out-of-Band (OOB) SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 69. SQL Injection - NoSQL Injection (CouchDB) targeting Laravel (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting NoSQL Injection (CouchDB) within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting NoSQL Injection (CouchDB) within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on NoSQL Injection (CouchDB). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 70. SQL Injection - Second-Order SQLi targeting Kong API Gateway

**Target Area**: Edge Proxies / Databases / Parsers / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting Second-Order SQLi within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Second-Order SQLi within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Kong API Gateway parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Second-Order SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 71. SQL Injection - NoSQL Injection (CouchDB) targeting Ruby on Rails

**Target Area**: Edge Proxies / Databases / Parsers / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting NoSQL Injection (CouchDB) within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting NoSQL Injection (CouchDB) within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on NoSQL Injection (CouchDB). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 72. SQL Injection - Union-Based SQLi targeting Kong API Gateway

**Target Area**: Edge Proxies / Databases / Parsers / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting Union-Based SQLi within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Union-Based SQLi within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Kong API Gateway parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Union-Based SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 73. SQL Injection - Out-of-Band (OOB) SQLi targeting ASP.NET Core

**Target Area**: Edge Proxies / Databases / Parsers / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting Out-of-Band (OOB) SQLi within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Out-of-Band (OOB) SQLi within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Out-of-Band (OOB) SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 74. SQL Injection - Boolean-Based Blind SQLi targeting Go (Gin)

**Target Area**: Edge Proxies / Databases / Parsers / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting Boolean-Based Blind SQLi within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Boolean-Based Blind SQLi within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Gin) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Boolean-Based Blind SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 75. SQL Injection - SQLi via HTTP Headers targeting Apigee

**Target Area**: Edge Proxies / Databases / Parsers / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting SQLi via HTTP Headers within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SQLi via HTTP Headers within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on SQLi via HTTP Headers. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 76. SQL Injection - Out-of-Band (OOB) SQLi targeting Django (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting Out-of-Band (OOB) SQLi within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Out-of-Band (OOB) SQLi within a Third-party integration webhook. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Django (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Out-of-Band (OOB) SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 77. SQL Injection - Boolean-Based Blind SQLi targeting Ruby on Rails

**Target Area**: Edge Proxies / Databases / Parsers / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting Boolean-Based Blind SQLi within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Boolean-Based Blind SQLi within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Boolean-Based Blind SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 78. SQL Injection - Error-Based SQLi targeting Laravel (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting Error-Based SQLi within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Error-Based SQLi within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Error-Based SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 79. SQL Injection - Time-Based Blind SQLi targeting Node.js/Express

**Target Area**: Edge Proxies / Databases / Parsers / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting Time-Based Blind SQLi within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Time-Based Blind SQLi within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Node.js/Express parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Time-Based Blind SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 80. SQL Injection - Boolean-Based Blind SQLi targeting GraphQL (Apollo)

**Target Area**: Edge Proxies / Databases / Parsers / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting Boolean-Based Blind SQLi within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Boolean-Based Blind SQLi within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Boolean-Based Blind SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 81. SQL Injection - Out-of-Band (OOB) SQLi targeting Symfony (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting Out-of-Band (OOB) SQLi within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Out-of-Band (OOB) SQLi within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Symfony (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Out-of-Band (OOB) SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 82. SQL Injection - Second-Order SQLi targeting Spring Boot (Java)

**Target Area**: Edge Proxies / Databases / Parsers / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting Second-Order SQLi within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Second-Order SQLi within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Spring Boot (Java) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Second-Order SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 83. SQL Injection - NoSQL Injection (CouchDB) targeting FastAPI

**Target Area**: Edge Proxies / Databases / Parsers / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting NoSQL Injection (CouchDB) within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting NoSQL Injection (CouchDB) within a Third-party integration webhook. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how FastAPI parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on NoSQL Injection (CouchDB). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 84. SQL Injection - Boolean-Based Blind SQLi targeting GraphQL (Relay)

**Target Area**: Edge Proxies / Databases / Parsers / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting Boolean-Based Blind SQLi within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Boolean-Based Blind SQLi within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Boolean-Based Blind SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 85. SQL Injection - Out-of-Band (OOB) SQLi targeting Node.js/Express

**Target Area**: Edge Proxies / Databases / Parsers / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting Out-of-Band (OOB) SQLi within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Out-of-Band (OOB) SQLi within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Node.js/Express parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Out-of-Band (OOB) SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 86. SQL Injection - NoSQL Injection (MongoDB) targeting Firebase

**Target Area**: Edge Proxies / Databases / Parsers / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting NoSQL Injection (MongoDB) within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting NoSQL Injection (MongoDB) within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on NoSQL Injection (MongoDB). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 87. SQL Injection - Second-Order SQLi targeting Django (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting Second-Order SQLi within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Second-Order SQLi within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Django (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Second-Order SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 88. SQL Injection - SQLi via HTTP Headers targeting Go (Gin)

**Target Area**: Edge Proxies / Databases / Parsers / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting SQLi via HTTP Headers within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SQLi via HTTP Headers within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Gin) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on SQLi via HTTP Headers. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 89. SQL Injection - SQLi in ORDER BY clauses targeting Go (Fiber)

**Target Area**: Edge Proxies / Databases / Parsers / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting SQLi in ORDER BY clauses within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SQLi in ORDER BY clauses within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Fiber) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on SQLi in ORDER BY clauses. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 90. SQL Injection - NoSQL Injection (CouchDB) targeting Firebase

**Target Area**: Edge Proxies / Databases / Parsers / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting NoSQL Injection (CouchDB) within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting NoSQL Injection (CouchDB) within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on NoSQL Injection (CouchDB). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 91. SQL Injection - Boolean-Based Blind SQLi targeting Apigee

**Target Area**: Edge Proxies / Databases / Parsers / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting Boolean-Based Blind SQLi within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Boolean-Based Blind SQLi within a Third-party integration webhook. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Boolean-Based Blind SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 92. SQL Injection - Union-Based SQLi targeting Go (Gin)

**Target Area**: Edge Proxies / Databases / Parsers / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting Union-Based SQLi within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Union-Based SQLi within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Gin) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Union-Based SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 93. SQL Injection - SQLi in ORDER BY clauses targeting Ruby on Rails

**Target Area**: Edge Proxies / Databases / Parsers / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting SQLi in ORDER BY clauses within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SQLi in ORDER BY clauses within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on SQLi in ORDER BY clauses. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 94. SQL Injection - SQLi in ORDER BY clauses targeting GraphQL (Apollo)

**Target Area**: Edge Proxies / Databases / Parsers / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting SQLi in ORDER BY clauses within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SQLi in ORDER BY clauses within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on SQLi in ORDER BY clauses. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 95. SQL Injection - NoSQL Injection (CouchDB) targeting Kong API Gateway

**Target Area**: Edge Proxies / Databases / Parsers / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting NoSQL Injection (CouchDB) within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting NoSQL Injection (CouchDB) within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Kong API Gateway parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on NoSQL Injection (CouchDB). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 96. SQL Injection - Boolean-Based Blind SQLi targeting Firebase

**Target Area**: Edge Proxies / Databases / Parsers / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting Boolean-Based Blind SQLi within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Boolean-Based Blind SQLi within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Boolean-Based Blind SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 97. SQL Injection - NoSQL Injection (CouchDB) targeting Django (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting NoSQL Injection (CouchDB) within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting NoSQL Injection (CouchDB) within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Django (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on NoSQL Injection (CouchDB). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 98. SQL Injection - Out-of-Band (OOB) SQLi targeting Django (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting Out-of-Band (OOB) SQLi within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Out-of-Band (OOB) SQLi within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Django (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Out-of-Band (OOB) SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 99. SQL Injection - Second-Order SQLi targeting ASP.NET Core

**Target Area**: Edge Proxies / Databases / Parsers / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting Second-Order SQLi within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Second-Order SQLi within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Second-Order SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 100. SQL Injection - Union-Based SQLi targeting Django (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting Union-Based SQLi within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Union-Based SQLi within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Django (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Union-Based SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 101. SQL Injection - Error-Based SQLi targeting Node.js/Express

**Target Area**: Edge Proxies / Databases / Parsers / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting Error-Based SQLi within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Error-Based SQLi within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Node.js/Express parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Error-Based SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 102. SQL Injection - NoSQL Injection (CouchDB) targeting Go (Fiber)

**Target Area**: Edge Proxies / Databases / Parsers / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting NoSQL Injection (CouchDB) within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting NoSQL Injection (CouchDB) within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Fiber) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on NoSQL Injection (CouchDB). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 103. SQL Injection - NoSQL Injection (MongoDB) targeting Django (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting NoSQL Injection (MongoDB) within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting NoSQL Injection (MongoDB) within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Django (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on NoSQL Injection (MongoDB). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 104. SQL Injection - Out-of-Band (OOB) SQLi targeting Ruby on Rails

**Target Area**: Edge Proxies / Databases / Parsers / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting Out-of-Band (OOB) SQLi within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Out-of-Band (OOB) SQLi within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Out-of-Band (OOB) SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 105. SQL Injection - NoSQL Injection (MongoDB) targeting Spring Boot (Java)

**Target Area**: Edge Proxies / Databases / Parsers / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting NoSQL Injection (MongoDB) within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting NoSQL Injection (MongoDB) within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Spring Boot (Java) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on NoSQL Injection (MongoDB). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 106. SQL Injection - NoSQL Injection (MongoDB) targeting Ruby on Rails

**Target Area**: Edge Proxies / Databases / Parsers / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting NoSQL Injection (MongoDB) within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting NoSQL Injection (MongoDB) within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on NoSQL Injection (MongoDB). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 107. SQL Injection - Out-of-Band (OOB) SQLi targeting Apigee

**Target Area**: Edge Proxies / Databases / Parsers / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting Out-of-Band (OOB) SQLi within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Out-of-Band (OOB) SQLi within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Out-of-Band (OOB) SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 108. SQL Injection - Error-Based SQLi targeting Laravel (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting Error-Based SQLi within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Error-Based SQLi within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Error-Based SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 109. SQL Injection - SQLi in ORDER BY clauses targeting Symfony (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting SQLi in ORDER BY clauses within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SQLi in ORDER BY clauses within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Symfony (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on SQLi in ORDER BY clauses. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 110. SQL Injection - SQLi in ORDER BY clauses targeting Azure API Management

**Target Area**: Edge Proxies / Databases / Parsers / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting SQLi in ORDER BY clauses within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SQLi in ORDER BY clauses within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Azure API Management parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on SQLi in ORDER BY clauses. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 111. SQL Injection - Second-Order SQLi targeting ASP.NET Core

**Target Area**: Edge Proxies / Databases / Parsers / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting Second-Order SQLi within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Second-Order SQLi within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Second-Order SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 112. SQL Injection - Out-of-Band (OOB) SQLi targeting Rust (Actix)

**Target Area**: Edge Proxies / Databases / Parsers / Rust (Actix) architecture
**Description**: An extensive operational guide for identifying and exploiting Out-of-Band (OOB) SQLi within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Out-of-Band (OOB) SQLi within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Rust (Actix) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Out-of-Band (OOB) SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 113. SQL Injection - Error-Based SQLi targeting Django (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting Error-Based SQLi within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Error-Based SQLi within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Django (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Error-Based SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 114. SQL Injection - NoSQL Injection (CouchDB) targeting GraphQL (Relay)

**Target Area**: Edge Proxies / Databases / Parsers / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting NoSQL Injection (CouchDB) within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting NoSQL Injection (CouchDB) within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on NoSQL Injection (CouchDB). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 115. SQL Injection - Second-Order SQLi targeting Go (Gin)

**Target Area**: Edge Proxies / Databases / Parsers / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting Second-Order SQLi within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Second-Order SQLi within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Gin) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Second-Order SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 116. SQL Injection - Time-Based Blind SQLi targeting Ruby on Rails

**Target Area**: Edge Proxies / Databases / Parsers / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting Time-Based Blind SQLi within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Time-Based Blind SQLi within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Time-Based Blind SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 117. SQL Injection - Out-of-Band (OOB) SQLi targeting Flask (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting Out-of-Band (OOB) SQLi within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Out-of-Band (OOB) SQLi within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Flask (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Out-of-Band (OOB) SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 118. SQL Injection - Out-of-Band (OOB) SQLi targeting Go (Fiber)

**Target Area**: Edge Proxies / Databases / Parsers / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting Out-of-Band (OOB) SQLi within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Out-of-Band (OOB) SQLi within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Fiber) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Out-of-Band (OOB) SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 119. SQL Injection - Time-Based Blind SQLi targeting Go (Fiber)

**Target Area**: Edge Proxies / Databases / Parsers / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting Time-Based Blind SQLi within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Time-Based Blind SQLi within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Fiber) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Time-Based Blind SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 120. SQL Injection - SQLi in ORDER BY clauses targeting Flask (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting SQLi in ORDER BY clauses within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SQLi in ORDER BY clauses within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Flask (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on SQLi in ORDER BY clauses. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 121. SQL Injection - Time-Based Blind SQLi targeting Azure API Management

**Target Area**: Edge Proxies / Databases / Parsers / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting Time-Based Blind SQLi within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Time-Based Blind SQLi within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Azure API Management parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Time-Based Blind SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 122. SQL Injection - Boolean-Based Blind SQLi targeting Supabase

**Target Area**: Edge Proxies / Databases / Parsers / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting Boolean-Based Blind SQLi within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Boolean-Based Blind SQLi within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Supabase parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Boolean-Based Blind SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 123. SQL Injection - Time-Based Blind SQLi targeting Apigee

**Target Area**: Edge Proxies / Databases / Parsers / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting Time-Based Blind SQLi within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Time-Based Blind SQLi within a Third-party integration webhook. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Time-Based Blind SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 124. SQL Injection - Error-Based SQLi targeting Apigee

**Target Area**: Edge Proxies / Databases / Parsers / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting Error-Based SQLi within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Error-Based SQLi within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Error-Based SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 125. SQL Injection - Second-Order SQLi targeting Spring Boot (Java)

**Target Area**: Edge Proxies / Databases / Parsers / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting Second-Order SQLi within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Second-Order SQLi within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Spring Boot (Java) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Second-Order SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 126. SQL Injection - Error-Based SQLi targeting Laravel (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting Error-Based SQLi within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Error-Based SQLi within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Error-Based SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 127. SQL Injection - Error-Based SQLi targeting Django (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting Error-Based SQLi within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Error-Based SQLi within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Django (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Error-Based SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 128. SQL Injection - Boolean-Based Blind SQLi targeting ASP.NET Core

**Target Area**: Edge Proxies / Databases / Parsers / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting Boolean-Based Blind SQLi within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Boolean-Based Blind SQLi within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Boolean-Based Blind SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 129. SQL Injection - Boolean-Based Blind SQLi targeting Flask (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting Boolean-Based Blind SQLi within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Boolean-Based Blind SQLi within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Flask (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Boolean-Based Blind SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 130. SQL Injection - Second-Order SQLi targeting Apigee

**Target Area**: Edge Proxies / Databases / Parsers / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting Second-Order SQLi within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Second-Order SQLi within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Second-Order SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 131. SQL Injection - Time-Based Blind SQLi targeting ASP.NET Core

**Target Area**: Edge Proxies / Databases / Parsers / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting Time-Based Blind SQLi within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Time-Based Blind SQLi within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Time-Based Blind SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 132. SQL Injection - SQLi in ORDER BY clauses targeting AWS API Gateway

**Target Area**: Edge Proxies / Databases / Parsers / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting SQLi in ORDER BY clauses within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SQLi in ORDER BY clauses within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how AWS API Gateway parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on SQLi in ORDER BY clauses. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 133. SQL Injection - NoSQL Injection (MongoDB) targeting Ruby on Rails

**Target Area**: Edge Proxies / Databases / Parsers / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting NoSQL Injection (MongoDB) within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting NoSQL Injection (MongoDB) within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on NoSQL Injection (MongoDB). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 134. SQL Injection - Error-Based SQLi targeting Node.js/Express

**Target Area**: Edge Proxies / Databases / Parsers / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting Error-Based SQLi within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Error-Based SQLi within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Node.js/Express parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Error-Based SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 135. SQL Injection - SQLi in ORDER BY clauses targeting GraphQL (Apollo)

**Target Area**: Edge Proxies / Databases / Parsers / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting SQLi in ORDER BY clauses within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SQLi in ORDER BY clauses within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on SQLi in ORDER BY clauses. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 136. SQL Injection - SQLi via HTTP Headers targeting GraphQL (Apollo)

**Target Area**: Edge Proxies / Databases / Parsers / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting SQLi via HTTP Headers within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SQLi via HTTP Headers within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on SQLi via HTTP Headers. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 137. SQL Injection - Time-Based Blind SQLi targeting Azure API Management

**Target Area**: Edge Proxies / Databases / Parsers / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting Time-Based Blind SQLi within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Time-Based Blind SQLi within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Azure API Management parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Time-Based Blind SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 138. SQL Injection - SQLi via HTTP Headers targeting Node.js/Express

**Target Area**: Edge Proxies / Databases / Parsers / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting SQLi via HTTP Headers within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SQLi via HTTP Headers within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Node.js/Express parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on SQLi via HTTP Headers. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 139. SQL Injection - Error-Based SQLi targeting Firebase

**Target Area**: Edge Proxies / Databases / Parsers / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting Error-Based SQLi within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Error-Based SQLi within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Error-Based SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 140. SQL Injection - Second-Order SQLi targeting Apigee

**Target Area**: Edge Proxies / Databases / Parsers / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting Second-Order SQLi within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Second-Order SQLi within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Second-Order SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 141. SQL Injection - SQLi via HTTP Headers targeting AWS API Gateway

**Target Area**: Edge Proxies / Databases / Parsers / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting SQLi via HTTP Headers within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SQLi via HTTP Headers within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how AWS API Gateway parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on SQLi via HTTP Headers. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 142. SQL Injection - SQLi in ORDER BY clauses targeting Node.js/Express

**Target Area**: Edge Proxies / Databases / Parsers / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting SQLi in ORDER BY clauses within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SQLi in ORDER BY clauses within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Node.js/Express parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on SQLi in ORDER BY clauses. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 143. SQL Injection - NoSQL Injection (CouchDB) targeting Azure API Management

**Target Area**: Edge Proxies / Databases / Parsers / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting NoSQL Injection (CouchDB) within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting NoSQL Injection (CouchDB) within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Azure API Management parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on NoSQL Injection (CouchDB). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 144. SQL Injection - SQLi in ORDER BY clauses targeting Django (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting SQLi in ORDER BY clauses within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SQLi in ORDER BY clauses within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Django (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on SQLi in ORDER BY clauses. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 145. SQL Injection - Second-Order SQLi targeting Ruby on Rails

**Target Area**: Edge Proxies / Databases / Parsers / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting Second-Order SQLi within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Second-Order SQLi within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Second-Order SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 146. SQL Injection - Second-Order SQLi targeting ASP.NET Core

**Target Area**: Edge Proxies / Databases / Parsers / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting Second-Order SQLi within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Second-Order SQLi within a Third-party integration webhook. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Second-Order SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 147. SQL Injection - Second-Order SQLi targeting AWS API Gateway

**Target Area**: Edge Proxies / Databases / Parsers / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting Second-Order SQLi within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Second-Order SQLi within a Third-party integration webhook. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how AWS API Gateway parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Second-Order SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 148. SQL Injection - NoSQL Injection (CouchDB) targeting Rust (Actix)

**Target Area**: Edge Proxies / Databases / Parsers / Rust (Actix) architecture
**Description**: An extensive operational guide for identifying and exploiting NoSQL Injection (CouchDB) within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting NoSQL Injection (CouchDB) within a Third-party integration webhook. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Rust (Actix) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on NoSQL Injection (CouchDB). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 149. SQL Injection - Boolean-Based Blind SQLi targeting Spring Boot (Java)

**Target Area**: Edge Proxies / Databases / Parsers / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting Boolean-Based Blind SQLi within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Boolean-Based Blind SQLi within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Spring Boot (Java) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Boolean-Based Blind SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 150. SQL Injection - Time-Based Blind SQLi targeting Supabase

**Target Area**: Edge Proxies / Databases / Parsers / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting Time-Based Blind SQLi within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Time-Based Blind SQLi within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Supabase parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Time-Based Blind SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 151. SQL Injection - Error-Based SQLi targeting Node.js/Express

**Target Area**: Edge Proxies / Databases / Parsers / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting Error-Based SQLi within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Error-Based SQLi within a Third-party integration webhook. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Node.js/Express parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Error-Based SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 152. SQL Injection - NoSQL Injection (MongoDB) targeting AWS API Gateway

**Target Area**: Edge Proxies / Databases / Parsers / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting NoSQL Injection (MongoDB) within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting NoSQL Injection (MongoDB) within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how AWS API Gateway parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on NoSQL Injection (MongoDB). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 153. SQL Injection - Second-Order SQLi targeting FastAPI

**Target Area**: Edge Proxies / Databases / Parsers / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting Second-Order SQLi within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Second-Order SQLi within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how FastAPI parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Second-Order SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 154. SQL Injection - Out-of-Band (OOB) SQLi targeting Kong API Gateway

**Target Area**: Edge Proxies / Databases / Parsers / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting Out-of-Band (OOB) SQLi within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Out-of-Band (OOB) SQLi within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Kong API Gateway parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Out-of-Band (OOB) SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 155. SQL Injection - SQLi in ORDER BY clauses targeting Ruby on Rails

**Target Area**: Edge Proxies / Databases / Parsers / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting SQLi in ORDER BY clauses within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SQLi in ORDER BY clauses within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on SQLi in ORDER BY clauses. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 156. SQL Injection - Out-of-Band (OOB) SQLi targeting GraphQL (Apollo)

**Target Area**: Edge Proxies / Databases / Parsers / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting Out-of-Band (OOB) SQLi within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Out-of-Band (OOB) SQLi within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Out-of-Band (OOB) SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

### 157. SQL Injection - Boolean-Based Blind SQLi targeting Go (Fiber)

**Target Area**: Edge Proxies / Databases / Parsers / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting Boolean-Based Blind SQLi within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Boolean-Based Blind SQLi within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Fiber) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Boolean-Based Blind SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of login mechanisms to assume administrative privileges.</step>
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

### 158. SQL Injection - SQLi in ORDER BY clauses targeting ASP.NET Core

**Target Area**: Edge Proxies / Databases / Parsers / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting SQLi in ORDER BY clauses within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SQLi in ORDER BY clauses within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on SQLi in ORDER BY clauses. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of OS commands via database extended stored procedures (e.g., xp_cmdshell).</step>
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

### 159. SQL Injection - Union-Based SQLi targeting Apigee

**Target Area**: Edge Proxies / Databases / Parsers / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting Union-Based SQLi within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Union-Based SQLi within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Union-Based SQLi. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete extraction of backend database tables.</step>
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

