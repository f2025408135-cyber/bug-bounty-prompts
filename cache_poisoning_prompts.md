# Advanced HTTP Attacks Bug Bounty Skills

A curated, extensive collection of 155 advanced skills for Web Cache Poisoning & Request Smuggling bug bounty hunting. Built for the Bug Bounty System Harness.

### 1. Advanced HTTP Attacks - HTTP Request Smuggling (TE.TE) targeting Ruby on Rails

**Target Area**: Edge Proxies / Databases / Parsers / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (TE.TE) within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (TE.TE). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 2. Advanced HTTP Attacks - HTTP Request Smuggling (TE.CL) targeting Django (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (TE.CL) within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Django (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (TE.CL). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 3. Advanced HTTP Attacks - Web Cache Poisoning via Parameter Cloaking targeting Node.js/Express

**Target Area**: Edge Proxies / Databases / Parsers / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Parameter Cloaking within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Node.js/Express parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Parameter Cloaking. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 4. Advanced HTTP Attacks - HTTP Request Smuggling (TE.TE) targeting Firebase

**Target Area**: Edge Proxies / Databases / Parsers / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (TE.TE) within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (TE.TE). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 5. Advanced HTTP Attacks - HTTP Request Smuggling (TE.TE) targeting Laravel (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (TE.TE) within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (TE.TE). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 6. Advanced HTTP Attacks - Web Cache Deception targeting Node.js/Express

**Target Area**: Edge Proxies / Databases / Parsers / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Deception within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Node.js/Express parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Deception. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 7. Advanced HTTP Attacks - HTTP Request Smuggling (CL.TE) targeting Go (Gin)

**Target Area**: Edge Proxies / Databases / Parsers / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (CL.TE) within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Gin) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (CL.TE). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 8. Advanced HTTP Attacks - HTTP Host Header Injection targeting Apigee

**Target Area**: Edge Proxies / Databases / Parsers / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Host Header Injection within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Host Header Injection. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 9. Advanced HTTP Attacks - Web Cache Deception targeting Laravel (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Deception within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Deception. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 10. Advanced HTTP Attacks - Web Cache Poisoning via Unkeyed Headers targeting Rust (Actix)

**Target Area**: Edge Proxies / Databases / Parsers / Rust (Actix) architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Unkeyed Headers within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Rust (Actix) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Unkeyed Headers. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 11. Advanced HTTP Attacks - Web Cache Poisoning via Parameter Cloaking targeting Flask (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Parameter Cloaking within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Flask (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Parameter Cloaking. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of frontend WAFs/Proxies to access restricted backend endpoints.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 12. Advanced HTTP Attacks - HTTP Request Smuggling (TE.TE) targeting AWS API Gateway

**Target Area**: Edge Proxies / Databases / Parsers / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (TE.TE) within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how AWS API Gateway parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (TE.TE). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 13. Advanced HTTP Attacks - HTTP Request Smuggling (CL.TE) targeting Go (Fiber)

**Target Area**: Edge Proxies / Databases / Parsers / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (CL.TE) within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Fiber) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (CL.TE). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 14. Advanced HTTP Attacks - H2C Smuggling targeting GraphQL (Relay)

**Target Area**: Edge Proxies / Databases / Parsers / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting H2C Smuggling within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on H2C Smuggling. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 15. Advanced HTTP Attacks - Web Cache Poisoning via Parameter Cloaking targeting Azure API Management

**Target Area**: Edge Proxies / Databases / Parsers / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Parameter Cloaking within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Azure API Management parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Parameter Cloaking. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 16. Advanced HTTP Attacks - Web Cache Poisoning via Parameter Cloaking targeting GraphQL (Apollo)

**Target Area**: Edge Proxies / Databases / Parsers / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Parameter Cloaking within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Parameter Cloaking. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 17. Advanced HTTP Attacks - HTTP Request Smuggling (CL.TE) targeting Flask (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (CL.TE) within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Flask (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (CL.TE). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of frontend WAFs/Proxies to access restricted backend endpoints.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 18. Advanced HTTP Attacks - HTTP Host Header Injection targeting AWS API Gateway

**Target Area**: Edge Proxies / Databases / Parsers / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Host Header Injection within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how AWS API Gateway parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Host Header Injection. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 19. Advanced HTTP Attacks - HTTP Request Smuggling (TE.TE) targeting Firebase

**Target Area**: Edge Proxies / Databases / Parsers / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (TE.TE) within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (TE.TE). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 20. Advanced HTTP Attacks - HTTP Request Smuggling (TE.TE) targeting FastAPI

**Target Area**: Edge Proxies / Databases / Parsers / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (TE.TE) within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how FastAPI parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (TE.TE). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of frontend WAFs/Proxies to access restricted backend endpoints.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 21. Advanced HTTP Attacks - Web Cache Deception targeting Firebase

**Target Area**: Edge Proxies / Databases / Parsers / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Deception within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Deception. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 22. Advanced HTTP Attacks - Web Cache Poisoning via Parameter Cloaking targeting Go (Fiber)

**Target Area**: Edge Proxies / Databases / Parsers / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Parameter Cloaking within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Fiber) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Parameter Cloaking. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of frontend WAFs/Proxies to access restricted backend endpoints.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 23. Advanced HTTP Attacks - HTTP Host Header Injection targeting Firebase

**Target Area**: Edge Proxies / Databases / Parsers / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Host Header Injection within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Host Header Injection. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 24. Advanced HTTP Attacks - H2C Smuggling targeting Go (Gin)

**Target Area**: Edge Proxies / Databases / Parsers / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting H2C Smuggling within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Gin) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on H2C Smuggling. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of frontend WAFs/Proxies to access restricted backend endpoints.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 25. Advanced HTTP Attacks - H2C Smuggling targeting Rust (Actix)

**Target Area**: Edge Proxies / Databases / Parsers / Rust (Actix) architecture
**Description**: An extensive operational guide for identifying and exploiting H2C Smuggling within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Rust (Actix) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on H2C Smuggling. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 26. Advanced HTTP Attacks - Web Cache Poisoning via Parameter Cloaking targeting Kong API Gateway

**Target Area**: Edge Proxies / Databases / Parsers / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Parameter Cloaking within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Kong API Gateway parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Parameter Cloaking. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 27. Advanced HTTP Attacks - Web Cache Poisoning via Unkeyed Headers targeting Supabase

**Target Area**: Edge Proxies / Databases / Parsers / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Unkeyed Headers within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Supabase parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Unkeyed Headers. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 28. Advanced HTTP Attacks - Web Cache Deception targeting Go (Gin)

**Target Area**: Edge Proxies / Databases / Parsers / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Deception within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Gin) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Deception. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 29. Advanced HTTP Attacks - Web Cache Poisoning via Parameter Cloaking targeting ASP.NET Core

**Target Area**: Edge Proxies / Databases / Parsers / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Parameter Cloaking within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Parameter Cloaking. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 30. Advanced HTTP Attacks - HTTP Request Smuggling (TE.TE) targeting Apigee

**Target Area**: Edge Proxies / Databases / Parsers / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (TE.TE) within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (TE.TE). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of frontend WAFs/Proxies to access restricted backend endpoints.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 31. Advanced HTTP Attacks - Web Cache Poisoning via Unkeyed Headers targeting Kong API Gateway

**Target Area**: Edge Proxies / Databases / Parsers / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Unkeyed Headers within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Kong API Gateway parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Unkeyed Headers. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 32. Advanced HTTP Attacks - HTTP Request Smuggling (TE.CL) targeting Apigee

**Target Area**: Edge Proxies / Databases / Parsers / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (TE.CL) within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (TE.CL). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 33. Advanced HTTP Attacks - HTTP Host Header Injection targeting Go (Gin)

**Target Area**: Edge Proxies / Databases / Parsers / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Host Header Injection within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Gin) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Host Header Injection. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 34. Advanced HTTP Attacks - HTTP Request Smuggling (CL.TE) targeting ASP.NET Core

**Target Area**: Edge Proxies / Databases / Parsers / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (CL.TE) within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (CL.TE). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 35. Advanced HTTP Attacks - Web Cache Deception targeting Ruby on Rails

**Target Area**: Edge Proxies / Databases / Parsers / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Deception within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Deception. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 36. Advanced HTTP Attacks - Web Cache Poisoning via Parameter Cloaking targeting Rust (Actix)

**Target Area**: Edge Proxies / Databases / Parsers / Rust (Actix) architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Parameter Cloaking within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Rust (Actix) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Parameter Cloaking. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 37. Advanced HTTP Attacks - HTTP Request Smuggling (TE.CL) targeting Supabase

**Target Area**: Edge Proxies / Databases / Parsers / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (TE.CL) within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Supabase parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (TE.CL). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of frontend WAFs/Proxies to access restricted backend endpoints.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 38. Advanced HTTP Attacks - Web Cache Deception targeting GraphQL (Relay)

**Target Area**: Edge Proxies / Databases / Parsers / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Deception within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Deception. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 39. Advanced HTTP Attacks - Web Cache Poisoning via Unkeyed Headers targeting Azure API Management

**Target Area**: Edge Proxies / Databases / Parsers / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Unkeyed Headers within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Azure API Management parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Unkeyed Headers. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of frontend WAFs/Proxies to access restricted backend endpoints.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 40. Advanced HTTP Attacks - H2C Smuggling targeting Go (Fiber)

**Target Area**: Edge Proxies / Databases / Parsers / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting H2C Smuggling within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Fiber) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on H2C Smuggling. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of frontend WAFs/Proxies to access restricted backend endpoints.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 41. Advanced HTTP Attacks - H2C Smuggling targeting Kong API Gateway

**Target Area**: Edge Proxies / Databases / Parsers / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting H2C Smuggling within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Kong API Gateway parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on H2C Smuggling. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 42. Advanced HTTP Attacks - Web Cache Poisoning via Unkeyed Headers targeting Laravel (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Unkeyed Headers within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Unkeyed Headers. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 43. Advanced HTTP Attacks - HTTP Request Smuggling (TE.TE) targeting Django (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (TE.TE) within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Django (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (TE.TE). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 44. Advanced HTTP Attacks - Web Cache Poisoning via Unkeyed Headers targeting Apigee

**Target Area**: Edge Proxies / Databases / Parsers / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Unkeyed Headers within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Unkeyed Headers. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of frontend WAFs/Proxies to access restricted backend endpoints.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 45. Advanced HTTP Attacks - HTTP Host Header Injection targeting AWS API Gateway

**Target Area**: Edge Proxies / Databases / Parsers / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Host Header Injection within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how AWS API Gateway parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Host Header Injection. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 46. Advanced HTTP Attacks - Web Cache Poisoning via Unkeyed Headers targeting FastAPI

**Target Area**: Edge Proxies / Databases / Parsers / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Unkeyed Headers within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how FastAPI parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Unkeyed Headers. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 47. Advanced HTTP Attacks - HTTP Request Smuggling (TE.TE) targeting Spring Boot (Java)

**Target Area**: Edge Proxies / Databases / Parsers / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (TE.TE) within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Spring Boot (Java) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (TE.TE). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of frontend WAFs/Proxies to access restricted backend endpoints.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 48. Advanced HTTP Attacks - Web Cache Poisoning via Unkeyed Headers targeting Ruby on Rails

**Target Area**: Edge Proxies / Databases / Parsers / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Unkeyed Headers within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Unkeyed Headers. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 49. Advanced HTTP Attacks - HTTP Request Smuggling (CL.TE) targeting Firebase

**Target Area**: Edge Proxies / Databases / Parsers / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (CL.TE) within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (CL.TE). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of frontend WAFs/Proxies to access restricted backend endpoints.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 50. Advanced HTTP Attacks - HTTP Request Smuggling (CL.TE) targeting AWS API Gateway

**Target Area**: Edge Proxies / Databases / Parsers / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (CL.TE) within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how AWS API Gateway parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (CL.TE). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 51. Advanced HTTP Attacks - HTTP Request Smuggling (TE.TE) targeting Firebase

**Target Area**: Edge Proxies / Databases / Parsers / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (TE.TE) within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (TE.TE). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of frontend WAFs/Proxies to access restricted backend endpoints.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 52. Advanced HTTP Attacks - Web Cache Poisoning via Unkeyed Headers targeting Spring Boot (Java)

**Target Area**: Edge Proxies / Databases / Parsers / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Unkeyed Headers within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Spring Boot (Java) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Unkeyed Headers. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 53. Advanced HTTP Attacks - Web Cache Poisoning via Parameter Cloaking targeting Spring Boot (Java)

**Target Area**: Edge Proxies / Databases / Parsers / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Parameter Cloaking within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Spring Boot (Java) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Parameter Cloaking. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 54. Advanced HTTP Attacks - HTTP Request Smuggling (TE.CL) targeting Ruby on Rails

**Target Area**: Edge Proxies / Databases / Parsers / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (TE.CL) within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (TE.CL). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 55. Advanced HTTP Attacks - HTTP Request Smuggling (CL.TE) targeting Go (Fiber)

**Target Area**: Edge Proxies / Databases / Parsers / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (CL.TE) within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Fiber) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (CL.TE). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 56. Advanced HTTP Attacks - Web Cache Poisoning via Unkeyed Headers targeting Django (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Unkeyed Headers within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Django (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Unkeyed Headers. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 57. Advanced HTTP Attacks - HTTP Request Smuggling (TE.TE) targeting Azure API Management

**Target Area**: Edge Proxies / Databases / Parsers / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (TE.TE) within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Azure API Management parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (TE.TE). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 58. Advanced HTTP Attacks - HTTP Request Smuggling (CL.TE) targeting Node.js/Express

**Target Area**: Edge Proxies / Databases / Parsers / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (CL.TE) within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Node.js/Express parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (CL.TE). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 59. Advanced HTTP Attacks - HTTP Request Smuggling (TE.TE) targeting Node.js/Express

**Target Area**: Edge Proxies / Databases / Parsers / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (TE.TE) within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Node.js/Express parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (TE.TE). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 60. Advanced HTTP Attacks - Web Cache Poisoning via Unkeyed Headers targeting AWS API Gateway

**Target Area**: Edge Proxies / Databases / Parsers / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Unkeyed Headers within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how AWS API Gateway parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Unkeyed Headers. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 61. Advanced HTTP Attacks - Web Cache Deception targeting Go (Fiber)

**Target Area**: Edge Proxies / Databases / Parsers / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Deception within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Fiber) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Deception. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of frontend WAFs/Proxies to access restricted backend endpoints.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 62. Advanced HTTP Attacks - HTTP Host Header Injection targeting Node.js/Express

**Target Area**: Edge Proxies / Databases / Parsers / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Host Header Injection within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Node.js/Express parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Host Header Injection. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of frontend WAFs/Proxies to access restricted backend endpoints.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 63. Advanced HTTP Attacks - HTTP Request Smuggling (TE.CL) targeting Django (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (TE.CL) within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Django (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (TE.CL). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 64. Advanced HTTP Attacks - HTTP Host Header Injection targeting Kong API Gateway

**Target Area**: Edge Proxies / Databases / Parsers / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Host Header Injection within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Kong API Gateway parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Host Header Injection. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 65. Advanced HTTP Attacks - H2C Smuggling targeting GraphQL (Apollo)

**Target Area**: Edge Proxies / Databases / Parsers / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting H2C Smuggling within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on H2C Smuggling. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of frontend WAFs/Proxies to access restricted backend endpoints.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 66. Advanced HTTP Attacks - Web Cache Poisoning via Parameter Cloaking targeting Node.js/Express

**Target Area**: Edge Proxies / Databases / Parsers / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Parameter Cloaking within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Node.js/Express parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Parameter Cloaking. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 67. Advanced HTTP Attacks - Web Cache Poisoning via Parameter Cloaking targeting Go (Fiber)

**Target Area**: Edge Proxies / Databases / Parsers / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Parameter Cloaking within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Fiber) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Parameter Cloaking. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 68. Advanced HTTP Attacks - HTTP Request Smuggling (TE.CL) targeting AWS API Gateway

**Target Area**: Edge Proxies / Databases / Parsers / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (TE.CL) within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how AWS API Gateway parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (TE.CL). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 69. Advanced HTTP Attacks - HTTP Request Smuggling (TE.TE) targeting Azure API Management

**Target Area**: Edge Proxies / Databases / Parsers / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (TE.TE) within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Azure API Management parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (TE.TE). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of frontend WAFs/Proxies to access restricted backend endpoints.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 70. Advanced HTTP Attacks - HTTP Host Header Injection targeting Apigee

**Target Area**: Edge Proxies / Databases / Parsers / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Host Header Injection within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Host Header Injection. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 71. Advanced HTTP Attacks - HTTP Host Header Injection targeting Kong API Gateway

**Target Area**: Edge Proxies / Databases / Parsers / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Host Header Injection within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Kong API Gateway parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Host Header Injection. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 72. Advanced HTTP Attacks - HTTP Request Smuggling (CL.TE) targeting AWS API Gateway

**Target Area**: Edge Proxies / Databases / Parsers / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (CL.TE) within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how AWS API Gateway parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (CL.TE). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 73. Advanced HTTP Attacks - Web Cache Poisoning via Parameter Cloaking targeting Rust (Actix)

**Target Area**: Edge Proxies / Databases / Parsers / Rust (Actix) architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Parameter Cloaking within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Rust (Actix) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Parameter Cloaking. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 74. Advanced HTTP Attacks - H2C Smuggling targeting Flask (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting H2C Smuggling within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Flask (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on H2C Smuggling. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 75. Advanced HTTP Attacks - Web Cache Poisoning via Parameter Cloaking targeting Flask (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Parameter Cloaking within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Flask (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Parameter Cloaking. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 76. Advanced HTTP Attacks - Web Cache Poisoning via Unkeyed Headers targeting Kong API Gateway

**Target Area**: Edge Proxies / Databases / Parsers / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Unkeyed Headers within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Kong API Gateway parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Unkeyed Headers. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 77. Advanced HTTP Attacks - Web Cache Poisoning via Unkeyed Headers targeting Laravel (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Unkeyed Headers within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Unkeyed Headers. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of frontend WAFs/Proxies to access restricted backend endpoints.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 78. Advanced HTTP Attacks - HTTP Request Smuggling (CL.TE) targeting Rust (Actix)

**Target Area**: Edge Proxies / Databases / Parsers / Rust (Actix) architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (CL.TE) within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Rust (Actix) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (CL.TE). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 79. Advanced HTTP Attacks - HTTP Host Header Injection targeting Laravel (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Host Header Injection within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Host Header Injection. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of frontend WAFs/Proxies to access restricted backend endpoints.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 80. Advanced HTTP Attacks - Web Cache Poisoning via Parameter Cloaking targeting Azure API Management

**Target Area**: Edge Proxies / Databases / Parsers / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Parameter Cloaking within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Azure API Management parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Parameter Cloaking. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 81. Advanced HTTP Attacks - Web Cache Deception targeting Laravel (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Deception within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Deception. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 82. Advanced HTTP Attacks - HTTP Request Smuggling (CL.TE) targeting Rust (Actix)

**Target Area**: Edge Proxies / Databases / Parsers / Rust (Actix) architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (CL.TE) within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Rust (Actix) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (CL.TE). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 83. Advanced HTTP Attacks - Web Cache Poisoning via Unkeyed Headers targeting Laravel (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Unkeyed Headers within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Unkeyed Headers. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 84. Advanced HTTP Attacks - Web Cache Poisoning via Parameter Cloaking targeting Laravel (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Parameter Cloaking within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Parameter Cloaking. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 85. Advanced HTTP Attacks - HTTP Host Header Injection targeting ASP.NET Core

**Target Area**: Edge Proxies / Databases / Parsers / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Host Header Injection within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Host Header Injection. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 86. Advanced HTTP Attacks - Web Cache Deception targeting AWS API Gateway

**Target Area**: Edge Proxies / Databases / Parsers / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Deception within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how AWS API Gateway parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Deception. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 87. Advanced HTTP Attacks - Web Cache Poisoning via Parameter Cloaking targeting Django (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Parameter Cloaking within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Django (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Parameter Cloaking. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of frontend WAFs/Proxies to access restricted backend endpoints.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 88. Advanced HTTP Attacks - HTTP Host Header Injection targeting Django (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Host Header Injection within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Django (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Host Header Injection. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 89. Advanced HTTP Attacks - Web Cache Poisoning via Unkeyed Headers targeting Firebase

**Target Area**: Edge Proxies / Databases / Parsers / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Unkeyed Headers within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Unkeyed Headers. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 90. Advanced HTTP Attacks - Web Cache Poisoning via Parameter Cloaking targeting Ruby on Rails

**Target Area**: Edge Proxies / Databases / Parsers / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Parameter Cloaking within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Parameter Cloaking. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 91. Advanced HTTP Attacks - H2C Smuggling targeting Node.js/Express

**Target Area**: Edge Proxies / Databases / Parsers / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting H2C Smuggling within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Node.js/Express parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on H2C Smuggling. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of frontend WAFs/Proxies to access restricted backend endpoints.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 92. Advanced HTTP Attacks - Web Cache Poisoning via Parameter Cloaking targeting Node.js/Express

**Target Area**: Edge Proxies / Databases / Parsers / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Parameter Cloaking within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Node.js/Express parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Parameter Cloaking. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 93. Advanced HTTP Attacks - H2C Smuggling targeting AWS API Gateway

**Target Area**: Edge Proxies / Databases / Parsers / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting H2C Smuggling within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how AWS API Gateway parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on H2C Smuggling. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of frontend WAFs/Proxies to access restricted backend endpoints.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 94. Advanced HTTP Attacks - HTTP Host Header Injection targeting FastAPI

**Target Area**: Edge Proxies / Databases / Parsers / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Host Header Injection within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how FastAPI parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Host Header Injection. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of frontend WAFs/Proxies to access restricted backend endpoints.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 95. Advanced HTTP Attacks - HTTP Request Smuggling (CL.TE) targeting GraphQL (Relay)

**Target Area**: Edge Proxies / Databases / Parsers / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (CL.TE) within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (CL.TE). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 96. Advanced HTTP Attacks - HTTP Request Smuggling (TE.CL) targeting Spring Boot (Java)

**Target Area**: Edge Proxies / Databases / Parsers / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (TE.CL) within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Spring Boot (Java) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (TE.CL). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 97. Advanced HTTP Attacks - HTTP Request Smuggling (CL.TE) targeting ASP.NET Core

**Target Area**: Edge Proxies / Databases / Parsers / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (CL.TE) within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (CL.TE). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 98. Advanced HTTP Attacks - Web Cache Poisoning via Unkeyed Headers targeting Azure API Management

**Target Area**: Edge Proxies / Databases / Parsers / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Unkeyed Headers within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Azure API Management parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Unkeyed Headers. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 99. Advanced HTTP Attacks - HTTP Request Smuggling (TE.TE) targeting Ruby on Rails

**Target Area**: Edge Proxies / Databases / Parsers / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (TE.TE) within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (TE.TE). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 100. Advanced HTTP Attacks - H2C Smuggling targeting AWS API Gateway

**Target Area**: Edge Proxies / Databases / Parsers / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting H2C Smuggling within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how AWS API Gateway parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on H2C Smuggling. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 101. Advanced HTTP Attacks - HTTP Request Smuggling (CL.TE) targeting Firebase

**Target Area**: Edge Proxies / Databases / Parsers / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (CL.TE) within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (CL.TE). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 102. Advanced HTTP Attacks - Web Cache Poisoning via Unkeyed Headers targeting Django (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Unkeyed Headers within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Django (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Unkeyed Headers. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 103. Advanced HTTP Attacks - HTTP Request Smuggling (TE.CL) targeting Django (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (TE.CL) within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Django (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (TE.CL). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 104. Advanced HTTP Attacks - Web Cache Deception targeting Flask (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Deception within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Flask (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Deception. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 105. Advanced HTTP Attacks - Web Cache Poisoning via Unkeyed Headers targeting Apigee

**Target Area**: Edge Proxies / Databases / Parsers / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Unkeyed Headers within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Unkeyed Headers. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 106. Advanced HTTP Attacks - HTTP Request Smuggling (TE.TE) targeting ASP.NET Core

**Target Area**: Edge Proxies / Databases / Parsers / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (TE.TE) within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (TE.TE). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of frontend WAFs/Proxies to access restricted backend endpoints.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 107. Advanced HTTP Attacks - Web Cache Poisoning via Unkeyed Headers targeting Spring Boot (Java)

**Target Area**: Edge Proxies / Databases / Parsers / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Unkeyed Headers within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Spring Boot (Java) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Unkeyed Headers. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 108. Advanced HTTP Attacks - Web Cache Poisoning via Parameter Cloaking targeting Flask (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Parameter Cloaking within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Flask (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Parameter Cloaking. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of frontend WAFs/Proxies to access restricted backend endpoints.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 109. Advanced HTTP Attacks - HTTP Request Smuggling (TE.CL) targeting Azure API Management

**Target Area**: Edge Proxies / Databases / Parsers / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (TE.CL) within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Azure API Management parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (TE.CL). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of frontend WAFs/Proxies to access restricted backend endpoints.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 110. Advanced HTTP Attacks - HTTP Request Smuggling (TE.CL) targeting Node.js/Express

**Target Area**: Edge Proxies / Databases / Parsers / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (TE.CL) within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Node.js/Express parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (TE.CL). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of frontend WAFs/Proxies to access restricted backend endpoints.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 111. Advanced HTTP Attacks - Web Cache Poisoning via Unkeyed Headers targeting AWS API Gateway

**Target Area**: Edge Proxies / Databases / Parsers / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Unkeyed Headers within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how AWS API Gateway parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Unkeyed Headers. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 112. Advanced HTTP Attacks - Web Cache Poisoning via Unkeyed Headers targeting Firebase

**Target Area**: Edge Proxies / Databases / Parsers / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Unkeyed Headers within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Unkeyed Headers. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of frontend WAFs/Proxies to access restricted backend endpoints.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 113. Advanced HTTP Attacks - Web Cache Poisoning via Parameter Cloaking targeting Symfony (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Parameter Cloaking within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Symfony (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Parameter Cloaking. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 114. Advanced HTTP Attacks - HTTP Request Smuggling (TE.CL) targeting GraphQL (Relay)

**Target Area**: Edge Proxies / Databases / Parsers / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (TE.CL) within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (TE.CL). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of frontend WAFs/Proxies to access restricted backend endpoints.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 115. Advanced HTTP Attacks - Web Cache Poisoning via Unkeyed Headers targeting Rust (Actix)

**Target Area**: Edge Proxies / Databases / Parsers / Rust (Actix) architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Unkeyed Headers within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Rust (Actix) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Unkeyed Headers. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 116. Advanced HTTP Attacks - HTTP Request Smuggling (CL.TE) targeting Apigee

**Target Area**: Edge Proxies / Databases / Parsers / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (CL.TE) within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (CL.TE). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 117. Advanced HTTP Attacks - HTTP Request Smuggling (CL.TE) targeting Symfony (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (CL.TE) within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Symfony (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (CL.TE). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 118. Advanced HTTP Attacks - Web Cache Deception targeting Rust (Actix)

**Target Area**: Edge Proxies / Databases / Parsers / Rust (Actix) architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Deception within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Rust (Actix) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Deception. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of frontend WAFs/Proxies to access restricted backend endpoints.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 119. Advanced HTTP Attacks - Web Cache Poisoning via Parameter Cloaking targeting AWS API Gateway

**Target Area**: Edge Proxies / Databases / Parsers / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Parameter Cloaking within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how AWS API Gateway parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Parameter Cloaking. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 120. Advanced HTTP Attacks - Web Cache Poisoning via Unkeyed Headers targeting Supabase

**Target Area**: Edge Proxies / Databases / Parsers / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Unkeyed Headers within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Supabase parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Unkeyed Headers. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of frontend WAFs/Proxies to access restricted backend endpoints.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 121. Advanced HTTP Attacks - Web Cache Poisoning via Unkeyed Headers targeting ASP.NET Core

**Target Area**: Edge Proxies / Databases / Parsers / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Unkeyed Headers within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Unkeyed Headers. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 122. Advanced HTTP Attacks - HTTP Request Smuggling (TE.CL) targeting FastAPI

**Target Area**: Edge Proxies / Databases / Parsers / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (TE.CL) within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how FastAPI parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (TE.CL). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of frontend WAFs/Proxies to access restricted backend endpoints.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 123. Advanced HTTP Attacks - Web Cache Deception targeting Supabase

**Target Area**: Edge Proxies / Databases / Parsers / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Deception within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Supabase parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Deception. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of frontend WAFs/Proxies to access restricted backend endpoints.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 124. Advanced HTTP Attacks - H2C Smuggling targeting ASP.NET Core

**Target Area**: Edge Proxies / Databases / Parsers / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting H2C Smuggling within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on H2C Smuggling. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 125. Advanced HTTP Attacks - HTTP Host Header Injection targeting Supabase

**Target Area**: Edge Proxies / Databases / Parsers / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Host Header Injection within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Supabase parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Host Header Injection. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 126. Advanced HTTP Attacks - HTTP Request Smuggling (TE.CL) targeting GraphQL (Apollo)

**Target Area**: Edge Proxies / Databases / Parsers / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (TE.CL) within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (TE.CL). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 127. Advanced HTTP Attacks - Web Cache Deception targeting Azure API Management

**Target Area**: Edge Proxies / Databases / Parsers / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Deception within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Azure API Management parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Deception. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of frontend WAFs/Proxies to access restricted backend endpoints.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 128. Advanced HTTP Attacks - Web Cache Deception targeting Spring Boot (Java)

**Target Area**: Edge Proxies / Databases / Parsers / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Deception within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Spring Boot (Java) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Deception. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 129. Advanced HTTP Attacks - Web Cache Deception targeting FastAPI

**Target Area**: Edge Proxies / Databases / Parsers / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Deception within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how FastAPI parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Deception. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of frontend WAFs/Proxies to access restricted backend endpoints.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 130. Advanced HTTP Attacks - HTTP Request Smuggling (TE.CL) targeting Flask (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (TE.CL) within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Flask (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (TE.CL). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 131. Advanced HTTP Attacks - Web Cache Poisoning via Unkeyed Headers targeting FastAPI

**Target Area**: Edge Proxies / Databases / Parsers / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Unkeyed Headers within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how FastAPI parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Unkeyed Headers. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 132. Advanced HTTP Attacks - Web Cache Poisoning via Unkeyed Headers targeting Firebase

**Target Area**: Edge Proxies / Databases / Parsers / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Unkeyed Headers within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Unkeyed Headers. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 133. Advanced HTTP Attacks - HTTP Request Smuggling (TE.CL) targeting Go (Gin)

**Target Area**: Edge Proxies / Databases / Parsers / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (TE.CL) within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Gin) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (TE.CL). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of frontend WAFs/Proxies to access restricted backend endpoints.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 134. Advanced HTTP Attacks - HTTP Request Smuggling (TE.CL) targeting Symfony (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (TE.CL) within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Symfony (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (TE.CL). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 135. Advanced HTTP Attacks - H2C Smuggling targeting Node.js/Express

**Target Area**: Edge Proxies / Databases / Parsers / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting H2C Smuggling within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Node.js/Express parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on H2C Smuggling. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of frontend WAFs/Proxies to access restricted backend endpoints.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 136. Advanced HTTP Attacks - Web Cache Poisoning via Parameter Cloaking targeting Firebase

**Target Area**: Edge Proxies / Databases / Parsers / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Parameter Cloaking within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Parameter Cloaking. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 137. Advanced HTTP Attacks - HTTP Request Smuggling (TE.CL) targeting Ruby on Rails

**Target Area**: Edge Proxies / Databases / Parsers / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (TE.CL) within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (TE.CL). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 138. Advanced HTTP Attacks - HTTP Host Header Injection targeting Ruby on Rails

**Target Area**: Edge Proxies / Databases / Parsers / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Host Header Injection within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Host Header Injection. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 139. Advanced HTTP Attacks - HTTP Request Smuggling (CL.TE) targeting GraphQL (Relay)

**Target Area**: Edge Proxies / Databases / Parsers / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (CL.TE) within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (CL.TE). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 140. Advanced HTTP Attacks - HTTP Request Smuggling (TE.CL) targeting Firebase

**Target Area**: Edge Proxies / Databases / Parsers / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (TE.CL) within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (TE.CL). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 141. Advanced HTTP Attacks - HTTP Request Smuggling (TE.TE) targeting Spring Boot (Java)

**Target Area**: Edge Proxies / Databases / Parsers / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (TE.TE) within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Spring Boot (Java) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (TE.TE). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 142. Advanced HTTP Attacks - HTTP Request Smuggling (CL.TE) targeting Spring Boot (Java)

**Target Area**: Edge Proxies / Databases / Parsers / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (CL.TE) within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Spring Boot (Java) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (CL.TE). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of frontend WAFs/Proxies to access restricted backend endpoints.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 143. Advanced HTTP Attacks - HTTP Request Smuggling (TE.CL) targeting GraphQL (Apollo)

**Target Area**: Edge Proxies / Databases / Parsers / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (TE.CL) within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (TE.CL). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 144. Advanced HTTP Attacks - HTTP Request Smuggling (CL.TE) targeting AWS API Gateway

**Target Area**: Edge Proxies / Databases / Parsers / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (CL.TE) within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how AWS API Gateway parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (CL.TE). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 145. Advanced HTTP Attacks - HTTP Request Smuggling (TE.TE) targeting ASP.NET Core

**Target Area**: Edge Proxies / Databases / Parsers / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (TE.TE) within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (TE.TE). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of frontend WAFs/Proxies to access restricted backend endpoints.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 146. Advanced HTTP Attacks - H2C Smuggling targeting Go (Gin)

**Target Area**: Edge Proxies / Databases / Parsers / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting H2C Smuggling within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Gin) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on H2C Smuggling. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 147. Advanced HTTP Attacks - HTTP Request Smuggling (TE.CL) targeting Firebase

**Target Area**: Edge Proxies / Databases / Parsers / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (TE.CL) within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (TE.CL). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 148. Advanced HTTP Attacks - Web Cache Poisoning via Unkeyed Headers targeting Apigee

**Target Area**: Edge Proxies / Databases / Parsers / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Unkeyed Headers within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Unkeyed Headers. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 149. Advanced HTTP Attacks - HTTP Request Smuggling (TE.TE) targeting Ruby on Rails

**Target Area**: Edge Proxies / Databases / Parsers / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (TE.TE) within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (TE.TE). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 150. Advanced HTTP Attacks - Web Cache Poisoning via Parameter Cloaking targeting Kong API Gateway

**Target Area**: Edge Proxies / Databases / Parsers / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Parameter Cloaking within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Kong API Gateway parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Parameter Cloaking. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of frontend WAFs/Proxies to access restricted backend endpoints.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 151. Advanced HTTP Attacks - Web Cache Poisoning via Unkeyed Headers targeting ASP.NET Core

**Target Area**: Edge Proxies / Databases / Parsers / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Unkeyed Headers within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Unkeyed Headers. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 152. Advanced HTTP Attacks - HTTP Request Smuggling (TE.CL) targeting AWS API Gateway

**Target Area**: Edge Proxies / Databases / Parsers / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (TE.CL) within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how AWS API Gateway parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (TE.CL). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypass of frontend WAFs/Proxies to access restricted backend endpoints.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 153. Advanced HTTP Attacks - HTTP Request Smuggling (TE.CL) targeting Laravel (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (TE.CL) within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (TE.CL). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Theft of sensitive user session cookies via Cache Deception.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 154. Advanced HTTP Attacks - HTTP Request Smuggling (TE.CL) targeting Spring Boot (Java)

**Target Area**: Edge Proxies / Databases / Parsers / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting HTTP Request Smuggling (TE.CL) within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Spring Boot (Java) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on HTTP Request Smuggling (TE.CL). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 155. Advanced HTTP Attacks - Web Cache Poisoning via Parameter Cloaking targeting Azure API Management

**Target Area**: Edge Proxies / Databases / Parsers / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting Web Cache Poisoning via Parameter Cloaking within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Azure API Management parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Web Cache Poisoning via Parameter Cloaking. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Execution of Stored XSS on all visitors caching the poisoned page.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

