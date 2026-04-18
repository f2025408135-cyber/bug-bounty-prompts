# XXE Bug Bounty Skills

A curated, extensive collection of 162 advanced skills for XXE bug bounty hunting. Built for the Bug Bounty System Harness.

### 1. XML External Entity - XXE leading to SSRF targeting Spring Boot (Java)

**Target Area**: Edge Proxies / Databases / Parsers / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE leading to SSRF within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Spring Boot (Java) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE leading to SSRF. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 2. XML External Entity - Error-Based XXE targeting Spring Boot (Java)

**Target Area**: Edge Proxies / Databases / Parsers / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting Error-Based XXE within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Spring Boot (Java) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Error-Based XXE. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 3. XML External Entity - Parameter Entity Injection in DTD targeting Laravel (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting Parameter Entity Injection in DTD within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Parameter Entity Injection in DTD. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting internal network scans via SSRF.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 4. XML External Entity - XXE Billion Laughs Attack (DoS) targeting Laravel (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE Billion Laughs Attack (DoS) within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE Billion Laughs Attack (DoS). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 5. XML External Entity - XXE via SVG File Uploads targeting Laravel (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE via SVG File Uploads within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE via SVG File Uploads. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 6. XML External Entity - XXE leading to SSRF targeting Django (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE leading to SSRF within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Django (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE leading to SSRF. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 7. XML External Entity - XXE via XLSX/DOCX Document Uploads targeting Django (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE via XLSX/DOCX Document Uploads within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Django (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE via XLSX/DOCX Document Uploads. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 8. XML External Entity - Blind XXE via Out-of-Band Interaction targeting Apigee

**Target Area**: Edge Proxies / Databases / Parsers / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting Blind XXE via Out-of-Band Interaction within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Blind XXE via Out-of-Band Interaction. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting internal network scans via SSRF.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 9. XML External Entity - XXE via XLSX/DOCX Document Uploads targeting Laravel (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE via XLSX/DOCX Document Uploads within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE via XLSX/DOCX Document Uploads. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 10. XML External Entity - XXE Billion Laughs Attack (DoS) targeting GraphQL (Apollo)

**Target Area**: Edge Proxies / Databases / Parsers / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE Billion Laughs Attack (DoS) within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE Billion Laughs Attack (DoS). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 11. XML External Entity - XXE via XLSX/DOCX Document Uploads targeting Firebase

**Target Area**: Edge Proxies / Databases / Parsers / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting XXE via XLSX/DOCX Document Uploads within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE via XLSX/DOCX Document Uploads. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 12. XML External Entity - XXE in SOAP APIs targeting Flask (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE in SOAP APIs within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Flask (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE in SOAP APIs. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting internal network scans via SSRF.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 13. XML External Entity - Error-Based XXE targeting Django (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting Error-Based XXE within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Django (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Error-Based XXE. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 14. XML External Entity - XXE in SOAP APIs targeting Azure API Management

**Target Area**: Edge Proxies / Databases / Parsers / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting XXE in SOAP APIs within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Azure API Management parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE in SOAP APIs. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 15. XML External Entity - Parameter Entity Injection in DTD targeting Apigee

**Target Area**: Edge Proxies / Databases / Parsers / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting Parameter Entity Injection in DTD within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Parameter Entity Injection in DTD. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 16. XML External Entity - Parameter Entity Injection in DTD targeting Symfony (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting Parameter Entity Injection in DTD within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Symfony (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Parameter Entity Injection in DTD. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 17. XML External Entity - Error-Based XXE targeting Node.js/Express

**Target Area**: Edge Proxies / Databases / Parsers / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting Error-Based XXE within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Node.js/Express parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Error-Based XXE. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting internal network scans via SSRF.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 18. XML External Entity - Error-Based XXE targeting GraphQL (Apollo)

**Target Area**: Edge Proxies / Databases / Parsers / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting Error-Based XXE within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Error-Based XXE. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 19. XML External Entity - XXE via XLSX/DOCX Document Uploads targeting Supabase

**Target Area**: Edge Proxies / Databases / Parsers / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting XXE via XLSX/DOCX Document Uploads within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Supabase parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE via XLSX/DOCX Document Uploads. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 20. XML External Entity - XXE leading to SSRF targeting Django (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE leading to SSRF within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Django (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE leading to SSRF. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 21. XML External Entity - XXE via SVG File Uploads targeting Go (Gin)

**Target Area**: Edge Proxies / Databases / Parsers / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE via SVG File Uploads within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Gin) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE via SVG File Uploads. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 22. XML External Entity - XXE via XLSX/DOCX Document Uploads targeting Firebase

**Target Area**: Edge Proxies / Databases / Parsers / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting XXE via XLSX/DOCX Document Uploads within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE via XLSX/DOCX Document Uploads. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting internal network scans via SSRF.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 23. XML External Entity - XXE in SOAP APIs targeting Firebase

**Target Area**: Edge Proxies / Databases / Parsers / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting XXE in SOAP APIs within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE in SOAP APIs. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 24. XML External Entity - XXE via XLSX/DOCX Document Uploads targeting GraphQL (Apollo)

**Target Area**: Edge Proxies / Databases / Parsers / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE via XLSX/DOCX Document Uploads within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE via XLSX/DOCX Document Uploads. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 25. XML External Entity - XXE in SOAP APIs targeting Apigee

**Target Area**: Edge Proxies / Databases / Parsers / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting XXE in SOAP APIs within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE in SOAP APIs. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting internal network scans via SSRF.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 26. XML External Entity - Error-Based XXE targeting Node.js/Express

**Target Area**: Edge Proxies / Databases / Parsers / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting Error-Based XXE within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Node.js/Express parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Error-Based XXE. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 27. XML External Entity - In-Band XXE for File Retrieval targeting GraphQL (Apollo)

**Target Area**: Edge Proxies / Databases / Parsers / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting In-Band XXE for File Retrieval within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on In-Band XXE for File Retrieval. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 28. XML External Entity - In-Band XXE for File Retrieval targeting Flask (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting In-Band XXE for File Retrieval within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Flask (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on In-Band XXE for File Retrieval. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 29. XML External Entity - XXE in SOAP APIs targeting ASP.NET Core

**Target Area**: Edge Proxies / Databases / Parsers / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting XXE in SOAP APIs within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE in SOAP APIs. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting internal network scans via SSRF.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 30. XML External Entity - XXE in SOAP APIs targeting Node.js/Express

**Target Area**: Edge Proxies / Databases / Parsers / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting XXE in SOAP APIs within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Node.js/Express parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE in SOAP APIs. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 31. XML External Entity - XXE Billion Laughs Attack (DoS) targeting GraphQL (Apollo)

**Target Area**: Edge Proxies / Databases / Parsers / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE Billion Laughs Attack (DoS) within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE Billion Laughs Attack (DoS). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 32. XML External Entity - XXE Billion Laughs Attack (DoS) targeting GraphQL (Relay)

**Target Area**: Edge Proxies / Databases / Parsers / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE Billion Laughs Attack (DoS) within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE Billion Laughs Attack (DoS). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 33. XML External Entity - XXE via SVG File Uploads targeting Spring Boot (Java)

**Target Area**: Edge Proxies / Databases / Parsers / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE via SVG File Uploads within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Spring Boot (Java) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE via SVG File Uploads. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 34. XML External Entity - XXE via XLSX/DOCX Document Uploads targeting Apigee

**Target Area**: Edge Proxies / Databases / Parsers / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting XXE via XLSX/DOCX Document Uploads within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE via XLSX/DOCX Document Uploads. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 35. XML External Entity - Blind XXE via Out-of-Band Interaction targeting GraphQL (Apollo)

**Target Area**: Edge Proxies / Databases / Parsers / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting Blind XXE via Out-of-Band Interaction within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Blind XXE via Out-of-Band Interaction. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 36. XML External Entity - XXE in SOAP APIs targeting Azure API Management

**Target Area**: Edge Proxies / Databases / Parsers / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting XXE in SOAP APIs within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Azure API Management parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE in SOAP APIs. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting internal network scans via SSRF.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 37. XML External Entity - XXE in SOAP APIs targeting GraphQL (Relay)

**Target Area**: Edge Proxies / Databases / Parsers / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE in SOAP APIs within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE in SOAP APIs. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting internal network scans via SSRF.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 38. XML External Entity - XXE in SOAP APIs targeting Django (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE in SOAP APIs within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Django (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE in SOAP APIs. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting internal network scans via SSRF.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 39. XML External Entity - XXE via XLSX/DOCX Document Uploads targeting Kong API Gateway

**Target Area**: Edge Proxies / Databases / Parsers / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting XXE via XLSX/DOCX Document Uploads within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Kong API Gateway parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE via XLSX/DOCX Document Uploads. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 40. XML External Entity - Blind XXE via Out-of-Band Interaction targeting Firebase

**Target Area**: Edge Proxies / Databases / Parsers / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting Blind XXE via Out-of-Band Interaction within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Blind XXE via Out-of-Band Interaction. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 41. XML External Entity - Error-Based XXE targeting Flask (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting Error-Based XXE within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Flask (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Error-Based XXE. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 42. XML External Entity - XXE in SOAP APIs targeting Spring Boot (Java)

**Target Area**: Edge Proxies / Databases / Parsers / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE in SOAP APIs within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Spring Boot (Java) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE in SOAP APIs. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 43. XML External Entity - Error-Based XXE targeting AWS API Gateway

**Target Area**: Edge Proxies / Databases / Parsers / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting Error-Based XXE within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how AWS API Gateway parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Error-Based XXE. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 44. XML External Entity - XXE via XLSX/DOCX Document Uploads targeting Go (Fiber)

**Target Area**: Edge Proxies / Databases / Parsers / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE via XLSX/DOCX Document Uploads within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Fiber) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE via XLSX/DOCX Document Uploads. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 45. XML External Entity - Blind XXE via Out-of-Band Interaction targeting Go (Fiber)

**Target Area**: Edge Proxies / Databases / Parsers / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting Blind XXE via Out-of-Band Interaction within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Fiber) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Blind XXE via Out-of-Band Interaction. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 46. XML External Entity - In-Band XXE for File Retrieval targeting FastAPI

**Target Area**: Edge Proxies / Databases / Parsers / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting In-Band XXE for File Retrieval within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how FastAPI parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on In-Band XXE for File Retrieval. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 47. XML External Entity - Blind XXE via Out-of-Band Interaction targeting GraphQL (Relay)

**Target Area**: Edge Proxies / Databases / Parsers / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting Blind XXE via Out-of-Band Interaction within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Blind XXE via Out-of-Band Interaction. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 48. XML External Entity - XXE leading to SSRF targeting GraphQL (Relay)

**Target Area**: Edge Proxies / Databases / Parsers / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE leading to SSRF within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE leading to SSRF. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting internal network scans via SSRF.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 49. XML External Entity - XXE via XLSX/DOCX Document Uploads targeting Laravel (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE via XLSX/DOCX Document Uploads within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE via XLSX/DOCX Document Uploads. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 50. XML External Entity - XXE leading to SSRF targeting Spring Boot (Java)

**Target Area**: Edge Proxies / Databases / Parsers / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE leading to SSRF within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Spring Boot (Java) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE leading to SSRF. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 51. XML External Entity - XXE via SVG File Uploads targeting AWS API Gateway

**Target Area**: Edge Proxies / Databases / Parsers / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting XXE via SVG File Uploads within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how AWS API Gateway parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE via SVG File Uploads. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting internal network scans via SSRF.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 52. XML External Entity - XXE Billion Laughs Attack (DoS) targeting Ruby on Rails

**Target Area**: Edge Proxies / Databases / Parsers / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting XXE Billion Laughs Attack (DoS) within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE Billion Laughs Attack (DoS). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 53. XML External Entity - In-Band XXE for File Retrieval targeting Symfony (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting In-Band XXE for File Retrieval within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Symfony (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on In-Band XXE for File Retrieval. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 54. XML External Entity - XXE via XLSX/DOCX Document Uploads targeting Apigee

**Target Area**: Edge Proxies / Databases / Parsers / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting XXE via XLSX/DOCX Document Uploads within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE via XLSX/DOCX Document Uploads. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 55. XML External Entity - Error-Based XXE targeting Apigee

**Target Area**: Edge Proxies / Databases / Parsers / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting Error-Based XXE within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Error-Based XXE. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting internal network scans via SSRF.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 56. XML External Entity - XXE leading to SSRF targeting Django (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE leading to SSRF within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Django (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE leading to SSRF. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 57. XML External Entity - Blind XXE via Out-of-Band Interaction targeting Ruby on Rails

**Target Area**: Edge Proxies / Databases / Parsers / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting Blind XXE via Out-of-Band Interaction within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Blind XXE via Out-of-Band Interaction. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 58. XML External Entity - XXE via SVG File Uploads targeting Apigee

**Target Area**: Edge Proxies / Databases / Parsers / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting XXE via SVG File Uploads within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE via SVG File Uploads. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 59. XML External Entity - XXE leading to SSRF targeting FastAPI

**Target Area**: Edge Proxies / Databases / Parsers / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting XXE leading to SSRF within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how FastAPI parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE leading to SSRF. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 60. XML External Entity - Parameter Entity Injection in DTD targeting ASP.NET Core

**Target Area**: Edge Proxies / Databases / Parsers / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting Parameter Entity Injection in DTD within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Parameter Entity Injection in DTD. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 61. XML External Entity - XXE Billion Laughs Attack (DoS) targeting Go (Gin)

**Target Area**: Edge Proxies / Databases / Parsers / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE Billion Laughs Attack (DoS) within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Gin) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE Billion Laughs Attack (DoS). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 62. XML External Entity - Parameter Entity Injection in DTD targeting GraphQL (Relay)

**Target Area**: Edge Proxies / Databases / Parsers / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting Parameter Entity Injection in DTD within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Parameter Entity Injection in DTD. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting internal network scans via SSRF.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 63. XML External Entity - In-Band XXE for File Retrieval targeting AWS API Gateway

**Target Area**: Edge Proxies / Databases / Parsers / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting In-Band XXE for File Retrieval within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how AWS API Gateway parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on In-Band XXE for File Retrieval. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 64. XML External Entity - In-Band XXE for File Retrieval targeting Node.js/Express

**Target Area**: Edge Proxies / Databases / Parsers / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting In-Band XXE for File Retrieval within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Node.js/Express parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on In-Band XXE for File Retrieval. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting internal network scans via SSRF.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 65. XML External Entity - Error-Based XXE targeting Node.js/Express

**Target Area**: Edge Proxies / Databases / Parsers / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting Error-Based XXE within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Node.js/Express parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Error-Based XXE. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 66. XML External Entity - XXE via SVG File Uploads targeting GraphQL (Apollo)

**Target Area**: Edge Proxies / Databases / Parsers / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE via SVG File Uploads within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE via SVG File Uploads. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting internal network scans via SSRF.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 67. XML External Entity - Blind XXE via Out-of-Band Interaction targeting Django (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting Blind XXE via Out-of-Band Interaction within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Django (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Blind XXE via Out-of-Band Interaction. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting internal network scans via SSRF.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 68. XML External Entity - XXE leading to SSRF targeting GraphQL (Apollo)

**Target Area**: Edge Proxies / Databases / Parsers / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE leading to SSRF within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE leading to SSRF. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting internal network scans via SSRF.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 69. XML External Entity - Parameter Entity Injection in DTD targeting Firebase

**Target Area**: Edge Proxies / Databases / Parsers / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting Parameter Entity Injection in DTD within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Parameter Entity Injection in DTD. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting internal network scans via SSRF.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 70. XML External Entity - XXE leading to SSRF targeting Azure API Management

**Target Area**: Edge Proxies / Databases / Parsers / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting XXE leading to SSRF within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Azure API Management parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE leading to SSRF. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 71. XML External Entity - XXE via XLSX/DOCX Document Uploads targeting Symfony (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE via XLSX/DOCX Document Uploads within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Symfony (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE via XLSX/DOCX Document Uploads. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 72. XML External Entity - XXE Billion Laughs Attack (DoS) targeting Azure API Management

**Target Area**: Edge Proxies / Databases / Parsers / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting XXE Billion Laughs Attack (DoS) within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Azure API Management parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE Billion Laughs Attack (DoS). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 73. XML External Entity - Blind XXE via Out-of-Band Interaction targeting ASP.NET Core

**Target Area**: Edge Proxies / Databases / Parsers / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting Blind XXE via Out-of-Band Interaction within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Blind XXE via Out-of-Band Interaction. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 74. XML External Entity - XXE via XLSX/DOCX Document Uploads targeting Kong API Gateway

**Target Area**: Edge Proxies / Databases / Parsers / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting XXE via XLSX/DOCX Document Uploads within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Kong API Gateway parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE via XLSX/DOCX Document Uploads. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting internal network scans via SSRF.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 75. XML External Entity - XXE in SOAP APIs targeting Apigee

**Target Area**: Edge Proxies / Databases / Parsers / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting XXE in SOAP APIs within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE in SOAP APIs. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting internal network scans via SSRF.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 76. XML External Entity - XXE via XLSX/DOCX Document Uploads targeting Spring Boot (Java)

**Target Area**: Edge Proxies / Databases / Parsers / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE via XLSX/DOCX Document Uploads within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Spring Boot (Java) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE via XLSX/DOCX Document Uploads. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 77. XML External Entity - Parameter Entity Injection in DTD targeting Supabase

**Target Area**: Edge Proxies / Databases / Parsers / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting Parameter Entity Injection in DTD within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Supabase parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Parameter Entity Injection in DTD. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting internal network scans via SSRF.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 78. XML External Entity - XXE leading to SSRF targeting Apigee

**Target Area**: Edge Proxies / Databases / Parsers / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting XXE leading to SSRF within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE leading to SSRF. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 79. XML External Entity - XXE Billion Laughs Attack (DoS) targeting Ruby on Rails

**Target Area**: Edge Proxies / Databases / Parsers / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting XXE Billion Laughs Attack (DoS) within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE Billion Laughs Attack (DoS). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting internal network scans via SSRF.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 80. XML External Entity - XXE via SVG File Uploads targeting Kong API Gateway

**Target Area**: Edge Proxies / Databases / Parsers / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting XXE via SVG File Uploads within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Kong API Gateway parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE via SVG File Uploads. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 81. XML External Entity - XXE via SVG File Uploads targeting Spring Boot (Java)

**Target Area**: Edge Proxies / Databases / Parsers / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE via SVG File Uploads within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Spring Boot (Java) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE via SVG File Uploads. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting internal network scans via SSRF.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 82. XML External Entity - XXE Billion Laughs Attack (DoS) targeting Firebase

**Target Area**: Edge Proxies / Databases / Parsers / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting XXE Billion Laughs Attack (DoS) within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE Billion Laughs Attack (DoS). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 83. XML External Entity - XXE via SVG File Uploads targeting FastAPI

**Target Area**: Edge Proxies / Databases / Parsers / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting XXE via SVG File Uploads within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how FastAPI parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE via SVG File Uploads. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 84. XML External Entity - Blind XXE via Out-of-Band Interaction targeting Apigee

**Target Area**: Edge Proxies / Databases / Parsers / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting Blind XXE via Out-of-Band Interaction within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Blind XXE via Out-of-Band Interaction. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 85. XML External Entity - XXE Billion Laughs Attack (DoS) targeting Symfony (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE Billion Laughs Attack (DoS) within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Symfony (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE Billion Laughs Attack (DoS). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 86. XML External Entity - XXE Billion Laughs Attack (DoS) targeting FastAPI

**Target Area**: Edge Proxies / Databases / Parsers / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting XXE Billion Laughs Attack (DoS) within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how FastAPI parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE Billion Laughs Attack (DoS). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 87. XML External Entity - XXE Billion Laughs Attack (DoS) targeting GraphQL (Relay)

**Target Area**: Edge Proxies / Databases / Parsers / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE Billion Laughs Attack (DoS) within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE Billion Laughs Attack (DoS). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 88. XML External Entity - In-Band XXE for File Retrieval targeting Go (Gin)

**Target Area**: Edge Proxies / Databases / Parsers / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting In-Band XXE for File Retrieval within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Gin) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on In-Band XXE for File Retrieval. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 89. XML External Entity - XXE via XLSX/DOCX Document Uploads targeting ASP.NET Core

**Target Area**: Edge Proxies / Databases / Parsers / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting XXE via XLSX/DOCX Document Uploads within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE via XLSX/DOCX Document Uploads. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 90. XML External Entity - XXE via XLSX/DOCX Document Uploads targeting Go (Gin)

**Target Area**: Edge Proxies / Databases / Parsers / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE via XLSX/DOCX Document Uploads within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Gin) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE via XLSX/DOCX Document Uploads. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 91. XML External Entity - Parameter Entity Injection in DTD targeting Supabase

**Target Area**: Edge Proxies / Databases / Parsers / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting Parameter Entity Injection in DTD within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Supabase parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Parameter Entity Injection in DTD. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 92. XML External Entity - Error-Based XXE targeting Rust (Actix)

**Target Area**: Edge Proxies / Databases / Parsers / Rust (Actix) architecture
**Description**: An extensive operational guide for identifying and exploiting Error-Based XXE within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Rust (Actix) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Error-Based XXE. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting internal network scans via SSRF.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 93. XML External Entity - XXE via XLSX/DOCX Document Uploads targeting Firebase

**Target Area**: Edge Proxies / Databases / Parsers / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting XXE via XLSX/DOCX Document Uploads within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE via XLSX/DOCX Document Uploads. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 94. XML External Entity - XXE via XLSX/DOCX Document Uploads targeting Node.js/Express

**Target Area**: Edge Proxies / Databases / Parsers / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting XXE via XLSX/DOCX Document Uploads within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Node.js/Express parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE via XLSX/DOCX Document Uploads. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 95. XML External Entity - In-Band XXE for File Retrieval targeting Azure API Management

**Target Area**: Edge Proxies / Databases / Parsers / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting In-Band XXE for File Retrieval within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Azure API Management parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on In-Band XXE for File Retrieval. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 96. XML External Entity - XXE Billion Laughs Attack (DoS) targeting Spring Boot (Java)

**Target Area**: Edge Proxies / Databases / Parsers / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE Billion Laughs Attack (DoS) within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Spring Boot (Java) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE Billion Laughs Attack (DoS). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 97. XML External Entity - XXE via SVG File Uploads targeting Django (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE via SVG File Uploads within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Django (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE via SVG File Uploads. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting internal network scans via SSRF.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 98. XML External Entity - XXE via SVG File Uploads targeting Go (Gin)

**Target Area**: Edge Proxies / Databases / Parsers / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE via SVG File Uploads within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Gin) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE via SVG File Uploads. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 99. XML External Entity - XXE via SVG File Uploads targeting GraphQL (Apollo)

**Target Area**: Edge Proxies / Databases / Parsers / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE via SVG File Uploads within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE via SVG File Uploads. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 100. XML External Entity - In-Band XXE for File Retrieval targeting Node.js/Express

**Target Area**: Edge Proxies / Databases / Parsers / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting In-Band XXE for File Retrieval within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Node.js/Express parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on In-Band XXE for File Retrieval. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting internal network scans via SSRF.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 101. XML External Entity - Parameter Entity Injection in DTD targeting AWS API Gateway

**Target Area**: Edge Proxies / Databases / Parsers / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting Parameter Entity Injection in DTD within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how AWS API Gateway parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Parameter Entity Injection in DTD. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 102. XML External Entity - In-Band XXE for File Retrieval targeting ASP.NET Core

**Target Area**: Edge Proxies / Databases / Parsers / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting In-Band XXE for File Retrieval within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on In-Band XXE for File Retrieval. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 103. XML External Entity - XXE Billion Laughs Attack (DoS) targeting Apigee

**Target Area**: Edge Proxies / Databases / Parsers / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting XXE Billion Laughs Attack (DoS) within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE Billion Laughs Attack (DoS). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 104. XML External Entity - Blind XXE via Out-of-Band Interaction targeting Rust (Actix)

**Target Area**: Edge Proxies / Databases / Parsers / Rust (Actix) architecture
**Description**: An extensive operational guide for identifying and exploiting Blind XXE via Out-of-Band Interaction within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Rust (Actix) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Blind XXE via Out-of-Band Interaction. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 105. XML External Entity - XXE via XLSX/DOCX Document Uploads targeting Go (Gin)

**Target Area**: Edge Proxies / Databases / Parsers / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE via XLSX/DOCX Document Uploads within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Gin) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE via XLSX/DOCX Document Uploads. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 106. XML External Entity - XXE in SOAP APIs targeting Node.js/Express

**Target Area**: Edge Proxies / Databases / Parsers / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting XXE in SOAP APIs within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Node.js/Express parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE in SOAP APIs. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting internal network scans via SSRF.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 107. XML External Entity - XXE Billion Laughs Attack (DoS) targeting Symfony (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE Billion Laughs Attack (DoS) within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Symfony (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE Billion Laughs Attack (DoS). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 108. XML External Entity - XXE in SOAP APIs targeting Laravel (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE in SOAP APIs within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE in SOAP APIs. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 109. XML External Entity - XXE via XLSX/DOCX Document Uploads targeting Flask (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE via XLSX/DOCX Document Uploads within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Flask (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE via XLSX/DOCX Document Uploads. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 110. XML External Entity - In-Band XXE for File Retrieval targeting Azure API Management

**Target Area**: Edge Proxies / Databases / Parsers / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting In-Band XXE for File Retrieval within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Azure API Management parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on In-Band XXE for File Retrieval. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting internal network scans via SSRF.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 111. XML External Entity - In-Band XXE for File Retrieval targeting Rust (Actix)

**Target Area**: Edge Proxies / Databases / Parsers / Rust (Actix) architecture
**Description**: An extensive operational guide for identifying and exploiting In-Band XXE for File Retrieval within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Rust (Actix) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on In-Band XXE for File Retrieval. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 112. XML External Entity - Error-Based XXE targeting GraphQL (Relay)

**Target Area**: Edge Proxies / Databases / Parsers / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting Error-Based XXE within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Error-Based XXE. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 113. XML External Entity - XXE in SOAP APIs targeting GraphQL (Relay)

**Target Area**: Edge Proxies / Databases / Parsers / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE in SOAP APIs within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE in SOAP APIs. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting internal network scans via SSRF.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 114. XML External Entity - XXE in SOAP APIs targeting Go (Fiber)

**Target Area**: Edge Proxies / Databases / Parsers / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE in SOAP APIs within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Fiber) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE in SOAP APIs. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 115. XML External Entity - In-Band XXE for File Retrieval targeting Apigee

**Target Area**: Edge Proxies / Databases / Parsers / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting In-Band XXE for File Retrieval within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on In-Band XXE for File Retrieval. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 116. XML External Entity - XXE in SOAP APIs targeting FastAPI

**Target Area**: Edge Proxies / Databases / Parsers / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting XXE in SOAP APIs within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how FastAPI parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE in SOAP APIs. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 117. XML External Entity - Error-Based XXE targeting Flask (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting Error-Based XXE within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Flask (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Error-Based XXE. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 118. XML External Entity - Blind XXE via Out-of-Band Interaction targeting Laravel (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting Blind XXE via Out-of-Band Interaction within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Blind XXE via Out-of-Band Interaction. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting internal network scans via SSRF.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 119. XML External Entity - XXE Billion Laughs Attack (DoS) targeting Spring Boot (Java)

**Target Area**: Edge Proxies / Databases / Parsers / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE Billion Laughs Attack (DoS) within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Spring Boot (Java) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE Billion Laughs Attack (DoS). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 120. XML External Entity - Blind XXE via Out-of-Band Interaction targeting Symfony (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting Blind XXE via Out-of-Band Interaction within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Symfony (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Blind XXE via Out-of-Band Interaction. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 121. XML External Entity - XXE in SOAP APIs targeting Supabase

**Target Area**: Edge Proxies / Databases / Parsers / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting XXE in SOAP APIs within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Supabase parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE in SOAP APIs. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 122. XML External Entity - XXE via XLSX/DOCX Document Uploads targeting Azure API Management

**Target Area**: Edge Proxies / Databases / Parsers / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting XXE via XLSX/DOCX Document Uploads within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Azure API Management parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE via XLSX/DOCX Document Uploads. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting internal network scans via SSRF.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 123. XML External Entity - XXE Billion Laughs Attack (DoS) targeting Go (Gin)

**Target Area**: Edge Proxies / Databases / Parsers / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE Billion Laughs Attack (DoS) within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Gin) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE Billion Laughs Attack (DoS). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting internal network scans via SSRF.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 124. XML External Entity - XXE Billion Laughs Attack (DoS) targeting ASP.NET Core

**Target Area**: Edge Proxies / Databases / Parsers / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting XXE Billion Laughs Attack (DoS) within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE Billion Laughs Attack (DoS). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting internal network scans via SSRF.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 125. XML External Entity - XXE Billion Laughs Attack (DoS) targeting GraphQL (Apollo)

**Target Area**: Edge Proxies / Databases / Parsers / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE Billion Laughs Attack (DoS) within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE Billion Laughs Attack (DoS). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 126. XML External Entity - In-Band XXE for File Retrieval targeting FastAPI

**Target Area**: Edge Proxies / Databases / Parsers / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting In-Band XXE for File Retrieval within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how FastAPI parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on In-Band XXE for File Retrieval. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 127. XML External Entity - In-Band XXE for File Retrieval targeting Laravel (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting In-Band XXE for File Retrieval within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on In-Band XXE for File Retrieval. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 128. XML External Entity - XXE in SOAP APIs targeting Symfony (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE in SOAP APIs within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Symfony (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE in SOAP APIs. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting internal network scans via SSRF.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 129. XML External Entity - In-Band XXE for File Retrieval targeting Azure API Management

**Target Area**: Edge Proxies / Databases / Parsers / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting In-Band XXE for File Retrieval within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Azure API Management parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on In-Band XXE for File Retrieval. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 130. XML External Entity - XXE in SOAP APIs targeting GraphQL (Apollo)

**Target Area**: Edge Proxies / Databases / Parsers / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE in SOAP APIs within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE in SOAP APIs. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 131. XML External Entity - Error-Based XXE targeting GraphQL (Apollo)

**Target Area**: Edge Proxies / Databases / Parsers / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting Error-Based XXE within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Error-Based XXE. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 132. XML External Entity - XXE leading to SSRF targeting GraphQL (Apollo)

**Target Area**: Edge Proxies / Databases / Parsers / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE leading to SSRF within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE leading to SSRF. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting internal network scans via SSRF.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 133. XML External Entity - Parameter Entity Injection in DTD targeting ASP.NET Core

**Target Area**: Edge Proxies / Databases / Parsers / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting Parameter Entity Injection in DTD within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Parameter Entity Injection in DTD. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting internal network scans via SSRF.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 134. XML External Entity - XXE in SOAP APIs targeting Firebase

**Target Area**: Edge Proxies / Databases / Parsers / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting XXE in SOAP APIs within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE in SOAP APIs. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting internal network scans via SSRF.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 135. XML External Entity - Error-Based XXE targeting FastAPI

**Target Area**: Edge Proxies / Databases / Parsers / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting Error-Based XXE within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how FastAPI parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Error-Based XXE. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting internal network scans via SSRF.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 136. XML External Entity - In-Band XXE for File Retrieval targeting Apigee

**Target Area**: Edge Proxies / Databases / Parsers / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting In-Band XXE for File Retrieval within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on In-Band XXE for File Retrieval. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 137. XML External Entity - Error-Based XXE targeting Ruby on Rails

**Target Area**: Edge Proxies / Databases / Parsers / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting Error-Based XXE within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Error-Based XXE. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 138. XML External Entity - XXE via XLSX/DOCX Document Uploads targeting Django (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE via XLSX/DOCX Document Uploads within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Django (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE via XLSX/DOCX Document Uploads. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 139. XML External Entity - Blind XXE via Out-of-Band Interaction targeting Supabase

**Target Area**: Edge Proxies / Databases / Parsers / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting Blind XXE via Out-of-Band Interaction within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Supabase parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Blind XXE via Out-of-Band Interaction. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 140. XML External Entity - XXE via SVG File Uploads targeting AWS API Gateway

**Target Area**: Edge Proxies / Databases / Parsers / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting XXE via SVG File Uploads within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how AWS API Gateway parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE via SVG File Uploads. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting internal network scans via SSRF.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 141. XML External Entity - Blind XXE via Out-of-Band Interaction targeting GraphQL (Apollo)

**Target Area**: Edge Proxies / Databases / Parsers / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting Blind XXE via Out-of-Band Interaction within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Blind XXE via Out-of-Band Interaction. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 142. XML External Entity - Parameter Entity Injection in DTD targeting Laravel (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting Parameter Entity Injection in DTD within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Parameter Entity Injection in DTD. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 143. XML External Entity - Error-Based XXE targeting FastAPI

**Target Area**: Edge Proxies / Databases / Parsers / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting Error-Based XXE within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how FastAPI parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Error-Based XXE. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 144. XML External Entity - Parameter Entity Injection in DTD targeting GraphQL (Apollo)

**Target Area**: Edge Proxies / Databases / Parsers / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting Parameter Entity Injection in DTD within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Parameter Entity Injection in DTD. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 145. XML External Entity - XXE leading to SSRF targeting Symfony (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE leading to SSRF within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Symfony (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE leading to SSRF. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting internal network scans via SSRF.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 146. XML External Entity - XXE via XLSX/DOCX Document Uploads targeting Laravel (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE via XLSX/DOCX Document Uploads within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE via XLSX/DOCX Document Uploads. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 147. XML External Entity - Parameter Entity Injection in DTD targeting Kong API Gateway

**Target Area**: Edge Proxies / Databases / Parsers / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting Parameter Entity Injection in DTD within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Kong API Gateway parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Parameter Entity Injection in DTD. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 148. XML External Entity - XXE Billion Laughs Attack (DoS) targeting Spring Boot (Java)

**Target Area**: Edge Proxies / Databases / Parsers / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE Billion Laughs Attack (DoS) within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Spring Boot (Java) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE Billion Laughs Attack (DoS). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 149. XML External Entity - Blind XXE via Out-of-Band Interaction targeting AWS API Gateway

**Target Area**: Edge Proxies / Databases / Parsers / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting Blind XXE via Out-of-Band Interaction within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how AWS API Gateway parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Blind XXE via Out-of-Band Interaction. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 150. XML External Entity - XXE via XLSX/DOCX Document Uploads targeting Apigee

**Target Area**: Edge Proxies / Databases / Parsers / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting XXE via XLSX/DOCX Document Uploads within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE via XLSX/DOCX Document Uploads. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 151. XML External Entity - Blind XXE via Out-of-Band Interaction targeting Node.js/Express

**Target Area**: Edge Proxies / Databases / Parsers / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting Blind XXE via Out-of-Band Interaction within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Node.js/Express parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Blind XXE via Out-of-Band Interaction. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 152. XML External Entity - XXE Billion Laughs Attack (DoS) targeting Django (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE Billion Laughs Attack (DoS) within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Django (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE Billion Laughs Attack (DoS). Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 4 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting internal network scans via SSRF.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 153. XML External Entity - XXE via SVG File Uploads targeting Supabase

**Target Area**: Edge Proxies / Databases / Parsers / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting XXE via SVG File Uploads within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Supabase parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE via SVG File Uploads. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 154. XML External Entity - XXE via XLSX/DOCX Document Uploads targeting Laravel (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE via XLSX/DOCX Document Uploads within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE via XLSX/DOCX Document Uploads. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 155. XML External Entity - XXE via SVG File Uploads targeting Rust (Actix)

**Target Area**: Edge Proxies / Databases / Parsers / Rust (Actix) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE via SVG File Uploads within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Rust (Actix) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE via SVG File Uploads. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 156. XML External Entity - XXE in SOAP APIs targeting AWS API Gateway

**Target Area**: Edge Proxies / Databases / Parsers / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting XXE in SOAP APIs within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how AWS API Gateway parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE in SOAP APIs. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting internal network scans via SSRF.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 157. XML External Entity - Parameter Entity Injection in DTD targeting Laravel (PHP)

**Target Area**: Edge Proxies / Databases / Parsers / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting Parameter Entity Injection in DTD within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Parameter Entity Injection in DTD. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 3 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 158. XML External Entity - XXE via XLSX/DOCX Document Uploads targeting Node.js/Express

**Target Area**: Edge Proxies / Databases / Parsers / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting XXE via XLSX/DOCX Document Uploads within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Node.js/Express parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE via XLSX/DOCX Document Uploads. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 159. XML External Entity - Error-Based XXE targeting Go (Fiber)

**Target Area**: Edge Proxies / Databases / Parsers / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting Error-Based XXE within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Fiber) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Error-Based XXE. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 160. XML External Entity - Parameter Entity Injection in DTD targeting FastAPI

**Target Area**: Edge Proxies / Databases / Parsers / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting Parameter Entity Injection in DTD within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how FastAPI parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Parameter Entity Injection in DTD. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 7 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of Service leading to application crash.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 161. XML External Entity - XXE via SVG File Uploads targeting Flask (Python)

**Target Area**: Edge Proxies / Databases / Parsers / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting XXE via SVG File Uploads within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Flask (Python) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on XXE via SVG File Uploads. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 6 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Exfiltration of local files like /etc/passwd or AWS IAM tokens.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 162. XML External Entity - Parameter Entity Injection in DTD targeting Go (Fiber)

**Target Area**: Edge Proxies / Databases / Parsers / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting Parameter Entity Injection in DTD within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Fiber) parses requests and interacts with downstream components (e.g., database drivers, XML parsers, caching layers).</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or stored before processing.</step>
    <step>Formulate hypotheses focused on Parameter Entity Injection in DTD. Map out exactly how the vulnerability could be triggered in this environment.</step>
    <step>Generate 5 specific, weaponized payloads designed to bypass common WAFs and filter mechanisms.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Pivoting internal network scans via SSRF.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

