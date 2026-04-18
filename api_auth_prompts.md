# API Authentication Bug Bounty Skills

A curated, extensive collection of 157 advanced skills for API Authentication bug bounty hunting. Built for the Bug Bounty System Harness.

### 1. API Auth - GraphQL Introspection against Flask (Python)

**Target Area**: API Keys / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting GraphQL Introspection within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting GraphQL Introspection within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Flask (Python) parses API Keys mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on GraphQL Introspection. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Elevation of privilege within a specific tenant space. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 2. API Auth - KID Manipulation against Ruby on Rails

**Target Area**: SSO (OIDC) / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting KID Manipulation within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting KID Manipulation within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Ruby on Rails parses SSO (OIDC) mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on KID Manipulation. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Elevation of privilege within a specific tenant space. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 3. API Auth - Signature Stripping against Kong API Gateway

**Target Area**: JWT / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting Signature Stripping within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Signature Stripping within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Kong API Gateway parses JWT mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Signature Stripping. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 4. API Auth - KID Manipulation against Symfony (PHP)

**Target Area**: JWT / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting KID Manipulation within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting KID Manipulation within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Symfony (PHP) parses JWT mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on KID Manipulation. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 5. API Auth - KID Manipulation against Azure API Management

**Target Area**: Magic Links / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting KID Manipulation within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting KID Manipulation within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Azure API Management parses Magic Links mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on KID Manipulation. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 6. API Auth - Type Confusion against Node.js/Express

**Target Area**: Bearer Tokens / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting Type Confusion within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Type Confusion within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Node.js/Express parses Bearer Tokens mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Type Confusion. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Elevation of privilege within a specific tenant space. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 7. API Auth - Type Confusion against Ruby on Rails

**Target Area**: OAuth2 / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting Type Confusion within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Type Confusion within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Ruby on Rails parses OAuth2 mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Type Confusion. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 8. API Auth - BFLA against Flask (Python)

**Target Area**: OTP via Email / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting BFLA within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting BFLA within a Third-party integration webhook. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Flask (Python) parses OTP via Email mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on BFLA. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 9. API Auth - SSRF via Webhook against Spring Boot (Java)

**Target Area**: OAuth2 / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via Webhook within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via Webhook within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Spring Boot (Java) parses OAuth2 mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on SSRF via Webhook. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 10. API Auth - Signature Stripping against Azure API Management

**Target Area**: OTP via Email / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting Signature Stripping within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Signature Stripping within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Azure API Management parses OTP via Email mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Mobile application backend API. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Signature Stripping. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Elevation of privilege within a specific tenant space. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 11. API Auth - Rate Limiting Bypass against Laravel (PHP)

**Target Area**: MFA Totp / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting Rate Limiting Bypass within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Rate Limiting Bypass within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Laravel (PHP) parses MFA Totp mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Rate Limiting Bypass. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 12. API Auth - SSRF via Webhook against Go (Gin)

**Target Area**: OAuth2 / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via Webhook within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via Webhook within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Go (Gin) parses OAuth2 mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on SSRF via Webhook. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 13. API Auth - Type Confusion against Supabase

**Target Area**: Basic Auth / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting Type Confusion within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Type Confusion within a Third-party integration webhook. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Supabase parses Basic Auth mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Type Confusion. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 14. API Auth - KID Manipulation against Go (Fiber)

**Target Area**: MFA Totp / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting KID Manipulation within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting KID Manipulation within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Go (Fiber) parses MFA Totp mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on KID Manipulation. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 15. API Auth - Improper Asset Management against Symfony (PHP)

**Target Area**: Bearer Tokens / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting Improper Asset Management within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Improper Asset Management within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Symfony (PHP) parses Bearer Tokens mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Improper Asset Management. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 16. API Auth - GraphQL Introspection against Azure API Management

**Target Area**: Basic Auth / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting GraphQL Introspection within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting GraphQL Introspection within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Azure API Management parses Basic Auth mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on GraphQL Introspection. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Elevation of privilege within a specific tenant space. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 17. API Auth - KID Manipulation against Spring Boot (Java)

**Target Area**: API Keys / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting KID Manipulation within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting KID Manipulation within a Third-party integration webhook. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Spring Boot (Java) parses API Keys mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on KID Manipulation. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 18. API Auth - KID Manipulation against Kong API Gateway

**Target Area**: MFA Totp / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting KID Manipulation within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting KID Manipulation within a Third-party integration webhook. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Kong API Gateway parses MFA Totp mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on KID Manipulation. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 19. API Auth - BFLA against Supabase

**Target Area**: SAML / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting BFLA within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting BFLA within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Supabase parses SAML mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on BFLA. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 20. API Auth - GraphQL Aliasing against Azure API Management

**Target Area**: SSO (OIDC) / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting GraphQL Aliasing within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting GraphQL Aliasing within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Azure API Management parses SSO (OIDC) mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on GraphQL Aliasing. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 21. API Auth - BFLA against Kong API Gateway

**Target Area**: Session Cookies / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting BFLA within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting BFLA within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Kong API Gateway parses Session Cookies mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on BFLA. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 22. API Auth - Improper Asset Management against Firebase

**Target Area**: OAuth2 / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting Improper Asset Management within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Improper Asset Management within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Firebase parses OAuth2 mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Improper Asset Management. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 23. API Auth - GraphQL Introspection against ASP.NET Core

**Target Area**: OAuth2 / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting GraphQL Introspection within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting GraphQL Introspection within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how ASP.NET Core parses OAuth2 mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on GraphQL Introspection. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 24. API Auth - BFLA against Apigee

**Target Area**: API Keys / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting BFLA within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting BFLA within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Apigee parses API Keys mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on BFLA. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 25. API Auth - Algorithm Confusion against Flask (Python)

**Target Area**: MFA Totp / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting Algorithm Confusion within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Algorithm Confusion within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Flask (Python) parses MFA Totp mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Algorithm Confusion. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 26. API Auth - Signature Stripping against Go (Gin)

**Target Area**: Magic Links / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting Signature Stripping within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Signature Stripping within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Go (Gin) parses Magic Links mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Signature Stripping. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 27. API Auth - GraphQL Aliasing against Go (Fiber)

**Target Area**: OTP via SMS / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting GraphQL Aliasing within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting GraphQL Aliasing within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Go (Fiber) parses OTP via SMS mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on GraphQL Aliasing. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 28. API Auth - GraphQL Introspection against Go (Gin)

**Target Area**: Session Cookies / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting GraphQL Introspection within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting GraphQL Introspection within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Go (Gin) parses Session Cookies mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on GraphQL Introspection. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 29. API Auth - BOLA/IDOR against ASP.NET Core

**Target Area**: JWT / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting BOLA/IDOR within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting BOLA/IDOR within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how ASP.NET Core parses JWT mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on BOLA/IDOR. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 30. API Auth - BOLA/IDOR against Firebase

**Target Area**: Basic Auth / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting BOLA/IDOR within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting BOLA/IDOR within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Firebase parses Basic Auth mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on BOLA/IDOR. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 31. API Auth - KID Manipulation against Spring Boot (Java)

**Target Area**: OAuth2 / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting KID Manipulation within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting KID Manipulation within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Spring Boot (Java) parses OAuth2 mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on KID Manipulation. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 32. API Auth - GraphQL Aliasing against Firebase

**Target Area**: SAML / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting GraphQL Aliasing within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting GraphQL Aliasing within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Firebase parses SAML mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on GraphQL Aliasing. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 33. API Auth - GraphQL Introspection against Firebase

**Target Area**: API Keys / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting GraphQL Introspection within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting GraphQL Introspection within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Firebase parses API Keys mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on GraphQL Introspection. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 34. API Auth - Rate Limiting Bypass against GraphQL (Relay)

**Target Area**: SSO (OIDC) / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting Rate Limiting Bypass within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Rate Limiting Bypass within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how GraphQL (Relay) parses SSO (OIDC) mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Rate Limiting Bypass. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 35. API Auth - GraphQL Aliasing against Go (Gin)

**Target Area**: MFA Totp / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting GraphQL Aliasing within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting GraphQL Aliasing within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Go (Gin) parses MFA Totp mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on GraphQL Aliasing. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Elevation of privilege within a specific tenant space. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 36. API Auth - Mass Assignment against AWS API Gateway

**Target Area**: Session Cookies / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting Mass Assignment within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Mass Assignment within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how AWS API Gateway parses Session Cookies mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Mass Assignment. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 37. API Auth - Signature Stripping against FastAPI

**Target Area**: OTP via SMS / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting Signature Stripping within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Signature Stripping within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how FastAPI parses OTP via SMS mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Signature Stripping. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 38. API Auth - Rate Limiting Bypass against Symfony (PHP)

**Target Area**: SSO (OIDC) / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting Rate Limiting Bypass within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Rate Limiting Bypass within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Symfony (PHP) parses SSO (OIDC) mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Rate Limiting Bypass. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 39. API Auth - KID Manipulation against Django (Python)

**Target Area**: OAuth2 / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting KID Manipulation within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting KID Manipulation within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Django (Python) parses OAuth2 mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on KID Manipulation. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 40. API Auth - KID Manipulation against Go (Fiber)

**Target Area**: OTP via SMS / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting KID Manipulation within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting KID Manipulation within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Go (Fiber) parses OTP via SMS mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on KID Manipulation. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 41. API Auth - GraphQL Aliasing against Kong API Gateway

**Target Area**: Magic Links / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting GraphQL Aliasing within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting GraphQL Aliasing within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Kong API Gateway parses Magic Links mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on GraphQL Aliasing. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 42. API Auth - KID Manipulation against Flask (Python)

**Target Area**: Bearer Tokens / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting KID Manipulation within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting KID Manipulation within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Flask (Python) parses Bearer Tokens mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on KID Manipulation. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Elevation of privilege within a specific tenant space. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 43. API Auth - BFLA against GraphQL (Relay)

**Target Area**: JWT / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting BFLA within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting BFLA within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how GraphQL (Relay) parses JWT mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on BFLA. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Elevation of privilege within a specific tenant space. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 44. API Auth - Algorithm Confusion against GraphQL (Apollo)

**Target Area**: Session Cookies / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting Algorithm Confusion within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Algorithm Confusion within a Third-party integration webhook. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how GraphQL (Apollo) parses Session Cookies mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Algorithm Confusion. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 45. API Auth - KID Manipulation against Azure API Management

**Target Area**: Bearer Tokens / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting KID Manipulation within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting KID Manipulation within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Azure API Management parses Bearer Tokens mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on KID Manipulation. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 46. API Auth - Type Confusion against Supabase

**Target Area**: Magic Links / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting Type Confusion within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Type Confusion within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Supabase parses Magic Links mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Type Confusion. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 47. API Auth - Signature Stripping against Spring Boot (Java)

**Target Area**: OAuth2 / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting Signature Stripping within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Signature Stripping within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Spring Boot (Java) parses OAuth2 mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Signature Stripping. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 48. API Auth - JKU/X5U Injection against GraphQL (Relay)

**Target Area**: Session Cookies / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting JKU/X5U Injection within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting JKU/X5U Injection within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how GraphQL (Relay) parses Session Cookies mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on JKU/X5U Injection. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 49. API Auth - Algorithm Confusion against ASP.NET Core

**Target Area**: Bearer Tokens / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting Algorithm Confusion within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Algorithm Confusion within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how ASP.NET Core parses Bearer Tokens mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Algorithm Confusion. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 50. API Auth - SSRF via Webhook against Supabase

**Target Area**: SSO (OIDC) / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via Webhook within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via Webhook within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Supabase parses SSO (OIDC) mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Mobile application backend API. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on SSRF via Webhook. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 51. API Auth - GraphQL Introspection against Firebase

**Target Area**: API Keys / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting GraphQL Introspection within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting GraphQL Introspection within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Firebase parses API Keys mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on GraphQL Introspection. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 52. API Auth - Algorithm Confusion against Kong API Gateway

**Target Area**: SSO (OIDC) / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting Algorithm Confusion within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Algorithm Confusion within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Kong API Gateway parses SSO (OIDC) mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Algorithm Confusion. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 53. API Auth - Algorithm Confusion against Spring Boot (Java)

**Target Area**: OTP via SMS / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting Algorithm Confusion within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Algorithm Confusion within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Spring Boot (Java) parses OTP via SMS mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Algorithm Confusion. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 54. API Auth - Algorithm Confusion against AWS API Gateway

**Target Area**: OAuth2 / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting Algorithm Confusion within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Algorithm Confusion within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how AWS API Gateway parses OAuth2 mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Algorithm Confusion. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 55. API Auth - Signature Stripping against Symfony (PHP)

**Target Area**: OTP via Email / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting Signature Stripping within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Signature Stripping within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Symfony (PHP) parses OTP via Email mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Signature Stripping. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 56. API Auth - Rate Limiting Bypass against Apigee

**Target Area**: OAuth2 / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting Rate Limiting Bypass within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Rate Limiting Bypass within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Apigee parses OAuth2 mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Rate Limiting Bypass. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 57. API Auth - GraphQL Introspection against Kong API Gateway

**Target Area**: API Keys / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting GraphQL Introspection within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting GraphQL Introspection within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Kong API Gateway parses API Keys mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on GraphQL Introspection. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 58. API Auth - GraphQL Introspection against FastAPI

**Target Area**: Bearer Tokens / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting GraphQL Introspection within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting GraphQL Introspection within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how FastAPI parses Bearer Tokens mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on GraphQL Introspection. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 59. API Auth - GraphQL Introspection against Go (Gin)

**Target Area**: OAuth2 / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting GraphQL Introspection within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting GraphQL Introspection within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Go (Gin) parses OAuth2 mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on GraphQL Introspection. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 60. API Auth - Mass Assignment against Apigee

**Target Area**: OTP via SMS / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting Mass Assignment within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Mass Assignment within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Apigee parses OTP via SMS mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Mass Assignment. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 61. API Auth - Improper Asset Management against Go (Fiber)

**Target Area**: OAuth2 / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting Improper Asset Management within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Improper Asset Management within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Go (Fiber) parses OAuth2 mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Improper Asset Management. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 62. API Auth - BOLA/IDOR against Go (Gin)

**Target Area**: OTP via SMS / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting BOLA/IDOR within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting BOLA/IDOR within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Go (Gin) parses OTP via SMS mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on BOLA/IDOR. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 63. API Auth - Rate Limiting Bypass against AWS API Gateway

**Target Area**: OTP via SMS / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting Rate Limiting Bypass within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Rate Limiting Bypass within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how AWS API Gateway parses OTP via SMS mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Rate Limiting Bypass. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Elevation of privilege within a specific tenant space. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 64. API Auth - GraphQL Introspection against Flask (Python)

**Target Area**: OAuth2 / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting GraphQL Introspection within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting GraphQL Introspection within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Flask (Python) parses OAuth2 mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on GraphQL Introspection. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 65. API Auth - GraphQL Aliasing against Azure API Management

**Target Area**: API Keys / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting GraphQL Aliasing within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting GraphQL Aliasing within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Azure API Management parses API Keys mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on GraphQL Aliasing. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 66. API Auth - KID Manipulation against FastAPI

**Target Area**: MFA Totp / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting KID Manipulation within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting KID Manipulation within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how FastAPI parses MFA Totp mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on KID Manipulation. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Elevation of privilege within a specific tenant space. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 67. API Auth - Improper Asset Management against Firebase

**Target Area**: OAuth2 / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting Improper Asset Management within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Improper Asset Management within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Firebase parses OAuth2 mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Mobile application backend API. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Improper Asset Management. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 68. API Auth - Type Confusion against Spring Boot (Java)

**Target Area**: SAML / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting Type Confusion within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Type Confusion within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Spring Boot (Java) parses SAML mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Type Confusion. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 69. API Auth - JKU/X5U Injection against Supabase

**Target Area**: Bearer Tokens / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting JKU/X5U Injection within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting JKU/X5U Injection within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Supabase parses Bearer Tokens mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on JKU/X5U Injection. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Elevation of privilege within a specific tenant space. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 70. API Auth - Algorithm Confusion against Flask (Python)

**Target Area**: SAML / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting Algorithm Confusion within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Algorithm Confusion within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Flask (Python) parses SAML mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Algorithm Confusion. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Elevation of privilege within a specific tenant space. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 71. API Auth - Algorithm Confusion against Rust (Actix)

**Target Area**: Bearer Tokens / Rust (Actix) architecture
**Description**: An extensive operational guide for identifying and exploiting Algorithm Confusion within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Algorithm Confusion within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Rust (Actix) parses Bearer Tokens mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Algorithm Confusion. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 72. API Auth - Algorithm Confusion against Go (Gin)

**Target Area**: Basic Auth / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting Algorithm Confusion within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Algorithm Confusion within a Third-party integration webhook. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Go (Gin) parses Basic Auth mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Algorithm Confusion. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 73. API Auth - GraphQL Introspection against Symfony (PHP)

**Target Area**: OTP via SMS / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting GraphQL Introspection within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting GraphQL Introspection within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Symfony (PHP) parses OTP via SMS mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on GraphQL Introspection. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 74. API Auth - Rate Limiting Bypass against Ruby on Rails

**Target Area**: SAML / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting Rate Limiting Bypass within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Rate Limiting Bypass within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Ruby on Rails parses SAML mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Rate Limiting Bypass. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 75. API Auth - Algorithm Confusion against ASP.NET Core

**Target Area**: MFA Totp / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting Algorithm Confusion within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Algorithm Confusion within a Third-party integration webhook. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how ASP.NET Core parses MFA Totp mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Algorithm Confusion. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 76. API Auth - Type Confusion against ASP.NET Core

**Target Area**: JWT / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting Type Confusion within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Type Confusion within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how ASP.NET Core parses JWT mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Type Confusion. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 77. API Auth - KID Manipulation against Laravel (PHP)

**Target Area**: API Keys / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting KID Manipulation within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting KID Manipulation within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Laravel (PHP) parses API Keys mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on KID Manipulation. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 78. API Auth - KID Manipulation against Node.js/Express

**Target Area**: Basic Auth / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting KID Manipulation within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting KID Manipulation within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Node.js/Express parses Basic Auth mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on KID Manipulation. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 79. API Auth - Signature Stripping against Go (Fiber)

**Target Area**: OTP via SMS / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting Signature Stripping within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Signature Stripping within a Third-party integration webhook. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Go (Fiber) parses OTP via SMS mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Signature Stripping. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Elevation of privilege within a specific tenant space. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 80. API Auth - GraphQL Introspection against Azure API Management

**Target Area**: OAuth2 / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting GraphQL Introspection within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting GraphQL Introspection within a Third-party integration webhook. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Azure API Management parses OAuth2 mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on GraphQL Introspection. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 81. API Auth - JKU/X5U Injection against Kong API Gateway

**Target Area**: OAuth2 / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting JKU/X5U Injection within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting JKU/X5U Injection within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Kong API Gateway parses OAuth2 mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Mobile application backend API. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on JKU/X5U Injection. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 82. API Auth - BFLA against Rust (Actix)

**Target Area**: OTP via Email / Rust (Actix) architecture
**Description**: An extensive operational guide for identifying and exploiting BFLA within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting BFLA within a Third-party integration webhook. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Rust (Actix) parses OTP via Email mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on BFLA. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 83. API Auth - Signature Stripping against GraphQL (Apollo)

**Target Area**: JWT / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting Signature Stripping within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Signature Stripping within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how GraphQL (Apollo) parses JWT mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Signature Stripping. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 84. API Auth - Algorithm Confusion against AWS API Gateway

**Target Area**: SSO (OIDC) / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting Algorithm Confusion within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Algorithm Confusion within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how AWS API Gateway parses SSO (OIDC) mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Algorithm Confusion. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Elevation of privilege within a specific tenant space. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 85. API Auth - BOLA/IDOR against GraphQL (Relay)

**Target Area**: Basic Auth / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting BOLA/IDOR within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting BOLA/IDOR within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how GraphQL (Relay) parses Basic Auth mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on BOLA/IDOR. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Elevation of privilege within a specific tenant space. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 86. API Auth - BOLA/IDOR against Flask (Python)

**Target Area**: API Keys / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting BOLA/IDOR within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting BOLA/IDOR within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Flask (Python) parses API Keys mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Mobile application backend API. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on BOLA/IDOR. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 87. API Auth - BOLA/IDOR against GraphQL (Apollo)

**Target Area**: SAML / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting BOLA/IDOR within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting BOLA/IDOR within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how GraphQL (Apollo) parses SAML mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Mobile application backend API. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on BOLA/IDOR. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 88. API Auth - BFLA against GraphQL (Apollo)

**Target Area**: OTP via Email / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting BFLA within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting BFLA within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how GraphQL (Apollo) parses OTP via Email mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on BFLA. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 89. API Auth - BFLA against Azure API Management

**Target Area**: API Keys / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting BFLA within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting BFLA within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Azure API Management parses API Keys mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on BFLA. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 90. API Auth - BFLA against Kong API Gateway

**Target Area**: Magic Links / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting BFLA within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting BFLA within a Third-party integration webhook. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Kong API Gateway parses Magic Links mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on BFLA. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 91. API Auth - GraphQL Introspection against Laravel (PHP)

**Target Area**: SSO (OIDC) / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting GraphQL Introspection within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting GraphQL Introspection within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Laravel (PHP) parses SSO (OIDC) mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on GraphQL Introspection. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 92. API Auth - GraphQL Introspection against Django (Python)

**Target Area**: MFA Totp / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting GraphQL Introspection within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting GraphQL Introspection within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Django (Python) parses MFA Totp mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Mobile application backend API. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on GraphQL Introspection. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 93. API Auth - BOLA/IDOR against Django (Python)

**Target Area**: API Keys / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting BOLA/IDOR within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting BOLA/IDOR within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Django (Python) parses API Keys mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on BOLA/IDOR. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Elevation of privilege within a specific tenant space. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 94. API Auth - SSRF via Webhook against Laravel (PHP)

**Target Area**: JWT / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via Webhook within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via Webhook within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Laravel (PHP) parses JWT mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on SSRF via Webhook. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 95. API Auth - Mass Assignment against Apigee

**Target Area**: Bearer Tokens / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting Mass Assignment within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Mass Assignment within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Apigee parses Bearer Tokens mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Mass Assignment. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 96. API Auth - KID Manipulation against GraphQL (Apollo)

**Target Area**: Session Cookies / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting KID Manipulation within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting KID Manipulation within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how GraphQL (Apollo) parses Session Cookies mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on KID Manipulation. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 97. API Auth - GraphQL Introspection against Node.js/Express

**Target Area**: Session Cookies / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting GraphQL Introspection within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting GraphQL Introspection within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Node.js/Express parses Session Cookies mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on GraphQL Introspection. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 98. API Auth - SSRF via Webhook against AWS API Gateway

**Target Area**: OTP via SMS / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via Webhook within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via Webhook within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how AWS API Gateway parses OTP via SMS mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on SSRF via Webhook. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 99. API Auth - Signature Stripping against Supabase

**Target Area**: MFA Totp / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting Signature Stripping within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Signature Stripping within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Supabase parses MFA Totp mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Signature Stripping. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 100. API Auth - Improper Asset Management against Apigee

**Target Area**: OTP via Email / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting Improper Asset Management within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Improper Asset Management within a Third-party integration webhook. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Apigee parses OTP via Email mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Improper Asset Management. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 101. API Auth - BFLA against Azure API Management

**Target Area**: SSO (OIDC) / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting BFLA within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting BFLA within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Azure API Management parses SSO (OIDC) mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on BFLA. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 102. API Auth - Mass Assignment against Go (Fiber)

**Target Area**: API Keys / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting Mass Assignment within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Mass Assignment within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Go (Fiber) parses API Keys mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Mass Assignment. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Elevation of privilege within a specific tenant space. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 103. API Auth - Mass Assignment against Symfony (PHP)

**Target Area**: OAuth2 / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting Mass Assignment within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Mass Assignment within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Symfony (PHP) parses OAuth2 mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Mobile application backend API. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Mass Assignment. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 104. API Auth - KID Manipulation against Go (Fiber)

**Target Area**: OTP via SMS / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting KID Manipulation within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting KID Manipulation within a Third-party integration webhook. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Go (Fiber) parses OTP via SMS mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on KID Manipulation. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 105. API Auth - JKU/X5U Injection against Ruby on Rails

**Target Area**: SSO (OIDC) / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting JKU/X5U Injection within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting JKU/X5U Injection within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Ruby on Rails parses SSO (OIDC) mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on JKU/X5U Injection. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 106. API Auth - GraphQL Aliasing against Laravel (PHP)

**Target Area**: Bearer Tokens / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting GraphQL Aliasing within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting GraphQL Aliasing within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Laravel (PHP) parses Bearer Tokens mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on GraphQL Aliasing. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 107. API Auth - Improper Asset Management against Supabase

**Target Area**: Session Cookies / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting Improper Asset Management within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Improper Asset Management within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Supabase parses Session Cookies mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Improper Asset Management. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 108. API Auth - BFLA against Kong API Gateway

**Target Area**: Bearer Tokens / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting BFLA within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting BFLA within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Kong API Gateway parses Bearer Tokens mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on BFLA. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 109. API Auth - Algorithm Confusion against Rust (Actix)

**Target Area**: Bearer Tokens / Rust (Actix) architecture
**Description**: An extensive operational guide for identifying and exploiting Algorithm Confusion within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Algorithm Confusion within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Rust (Actix) parses Bearer Tokens mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Mobile application backend API. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Algorithm Confusion. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 110. API Auth - GraphQL Aliasing against Azure API Management

**Target Area**: Session Cookies / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting GraphQL Aliasing within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting GraphQL Aliasing within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Azure API Management parses Session Cookies mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on GraphQL Aliasing. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 111. API Auth - BFLA against Firebase

**Target Area**: Basic Auth / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting BFLA within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting BFLA within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Firebase parses Basic Auth mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on BFLA. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 112. API Auth - GraphQL Aliasing against ASP.NET Core

**Target Area**: OTP via Email / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting GraphQL Aliasing within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting GraphQL Aliasing within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how ASP.NET Core parses OTP via Email mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on GraphQL Aliasing. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 113. API Auth - Algorithm Confusion against GraphQL (Apollo)

**Target Area**: MFA Totp / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting Algorithm Confusion within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Algorithm Confusion within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how GraphQL (Apollo) parses MFA Totp mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Algorithm Confusion. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 114. API Auth - JKU/X5U Injection against Supabase

**Target Area**: API Keys / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting JKU/X5U Injection within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting JKU/X5U Injection within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Supabase parses API Keys mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on JKU/X5U Injection. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 115. API Auth - BOLA/IDOR against Laravel (PHP)

**Target Area**: Basic Auth / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting BOLA/IDOR within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting BOLA/IDOR within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Laravel (PHP) parses Basic Auth mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on BOLA/IDOR. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 116. API Auth - Type Confusion against GraphQL (Relay)

**Target Area**: Magic Links / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting Type Confusion within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Type Confusion within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how GraphQL (Relay) parses Magic Links mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Mobile application backend API. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Type Confusion. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 117. API Auth - GraphQL Aliasing against Azure API Management

**Target Area**: Session Cookies / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting GraphQL Aliasing within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting GraphQL Aliasing within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Azure API Management parses Session Cookies mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on GraphQL Aliasing. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 118. API Auth - SSRF via Webhook against Spring Boot (Java)

**Target Area**: Session Cookies / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via Webhook within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via Webhook within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Spring Boot (Java) parses Session Cookies mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on SSRF via Webhook. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 119. API Auth - Rate Limiting Bypass against Ruby on Rails

**Target Area**: Magic Links / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting Rate Limiting Bypass within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Rate Limiting Bypass within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Ruby on Rails parses Magic Links mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Rate Limiting Bypass. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 120. API Auth - Rate Limiting Bypass against Laravel (PHP)

**Target Area**: API Keys / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting Rate Limiting Bypass within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Rate Limiting Bypass within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Laravel (PHP) parses API Keys mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Rate Limiting Bypass. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Elevation of privilege within a specific tenant space. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 121. API Auth - JKU/X5U Injection against Apigee

**Target Area**: API Keys / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting JKU/X5U Injection within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting JKU/X5U Injection within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Apigee parses API Keys mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on JKU/X5U Injection. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 122. API Auth - Rate Limiting Bypass against Node.js/Express

**Target Area**: MFA Totp / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting Rate Limiting Bypass within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Rate Limiting Bypass within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Node.js/Express parses MFA Totp mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Mobile application backend API. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Rate Limiting Bypass. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 123. API Auth - BFLA against Laravel (PHP)

**Target Area**: SSO (OIDC) / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting BFLA within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting BFLA within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Laravel (PHP) parses SSO (OIDC) mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on BFLA. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 124. API Auth - Signature Stripping against Go (Gin)

**Target Area**: JWT / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting Signature Stripping within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Signature Stripping within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Go (Gin) parses JWT mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Signature Stripping. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 125. API Auth - Improper Asset Management against GraphQL (Relay)

**Target Area**: OTP via SMS / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting Improper Asset Management within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Improper Asset Management within a Third-party integration webhook. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how GraphQL (Relay) parses OTP via SMS mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Improper Asset Management. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 126. API Auth - Algorithm Confusion against GraphQL (Relay)

**Target Area**: Bearer Tokens / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting Algorithm Confusion within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Algorithm Confusion within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how GraphQL (Relay) parses Bearer Tokens mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Algorithm Confusion. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 127. API Auth - GraphQL Introspection against Supabase

**Target Area**: SAML / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting GraphQL Introspection within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting GraphQL Introspection within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Supabase parses SAML mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on GraphQL Introspection. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 128. API Auth - GraphQL Introspection against Go (Fiber)

**Target Area**: Magic Links / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting GraphQL Introspection within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting GraphQL Introspection within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Go (Fiber) parses Magic Links mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on GraphQL Introspection. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 129. API Auth - GraphQL Aliasing against Kong API Gateway

**Target Area**: Session Cookies / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting GraphQL Aliasing within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting GraphQL Aliasing within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Kong API Gateway parses Session Cookies mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Mobile application backend API. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on GraphQL Aliasing. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 130. API Auth - Type Confusion against Supabase

**Target Area**: OTP via Email / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting Type Confusion within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Type Confusion within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Supabase parses OTP via Email mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Type Confusion. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 131. API Auth - GraphQL Introspection against GraphQL (Apollo)

**Target Area**: Magic Links / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting GraphQL Introspection within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting GraphQL Introspection within a Third-party integration webhook. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how GraphQL (Apollo) parses Magic Links mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on GraphQL Introspection. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 132. API Auth - JKU/X5U Injection against Firebase

**Target Area**: API Keys / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting JKU/X5U Injection within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting JKU/X5U Injection within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Firebase parses API Keys mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on JKU/X5U Injection. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 133. API Auth - Type Confusion against Apigee

**Target Area**: JWT / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting Type Confusion within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Type Confusion within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Apigee parses JWT mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Mobile application backend API. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Type Confusion. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 134. API Auth - KID Manipulation against Django (Python)

**Target Area**: Bearer Tokens / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting KID Manipulation within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting KID Manipulation within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Django (Python) parses Bearer Tokens mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on KID Manipulation. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Elevation of privilege within a specific tenant space. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 135. API Auth - Improper Asset Management against Symfony (PHP)

**Target Area**: SSO (OIDC) / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting Improper Asset Management within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Improper Asset Management within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Symfony (PHP) parses SSO (OIDC) mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Improper Asset Management. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Elevation of privilege within a specific tenant space. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 136. API Auth - Mass Assignment against Node.js/Express

**Target Area**: Session Cookies / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting Mass Assignment within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Mass Assignment within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Node.js/Express parses Session Cookies mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Mass Assignment. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 137. API Auth - GraphQL Aliasing against Symfony (PHP)

**Target Area**: OTP via Email / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting GraphQL Aliasing within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting GraphQL Aliasing within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Symfony (PHP) parses OTP via Email mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Mobile application backend API. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on GraphQL Aliasing. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Elevation of privilege within a specific tenant space. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 138. API Auth - Mass Assignment against Azure API Management

**Target Area**: Bearer Tokens / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting Mass Assignment within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Mass Assignment within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Azure API Management parses Bearer Tokens mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Mass Assignment. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 139. API Auth - BOLA/IDOR against Rust (Actix)

**Target Area**: API Keys / Rust (Actix) architecture
**Description**: An extensive operational guide for identifying and exploiting BOLA/IDOR within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting BOLA/IDOR within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Rust (Actix) parses API Keys mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on BOLA/IDOR. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 140. API Auth - KID Manipulation against Flask (Python)

**Target Area**: OAuth2 / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting KID Manipulation within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting KID Manipulation within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Flask (Python) parses OAuth2 mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on KID Manipulation. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 141. API Auth - SSRF via Webhook against ASP.NET Core

**Target Area**: SSO (OIDC) / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via Webhook within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via Webhook within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how ASP.NET Core parses SSO (OIDC) mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on SSRF via Webhook. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 142. API Auth - Type Confusion against Kong API Gateway

**Target Area**: API Keys / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting Type Confusion within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Type Confusion within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Kong API Gateway parses API Keys mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Type Confusion. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 143. API Auth - KID Manipulation against Go (Gin)

**Target Area**: SAML / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting KID Manipulation within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting KID Manipulation within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Go (Gin) parses SAML mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on KID Manipulation. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 144. API Auth - Algorithm Confusion against Azure API Management

**Target Area**: JWT / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting Algorithm Confusion within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Algorithm Confusion within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Azure API Management parses JWT mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Algorithm Confusion. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 145. API Auth - Improper Asset Management against Go (Gin)

**Target Area**: Magic Links / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting Improper Asset Management within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Improper Asset Management within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Go (Gin) parses Magic Links mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Improper Asset Management. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Elevation of privilege within a specific tenant space. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 146. API Auth - Algorithm Confusion against Kong API Gateway

**Target Area**: Magic Links / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting Algorithm Confusion within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Algorithm Confusion within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Kong API Gateway parses Magic Links mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Mobile application backend API. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Algorithm Confusion. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 147. API Auth - BOLA/IDOR against ASP.NET Core

**Target Area**: Magic Links / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting BOLA/IDOR within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting BOLA/IDOR within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how ASP.NET Core parses Magic Links mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on BOLA/IDOR. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 148. API Auth - Signature Stripping against GraphQL (Apollo)

**Target Area**: OTP via Email / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting Signature Stripping within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Signature Stripping within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how GraphQL (Apollo) parses OTP via Email mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Signature Stripping. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 149. API Auth - JKU/X5U Injection against Ruby on Rails

**Target Area**: Session Cookies / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting JKU/X5U Injection within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting JKU/X5U Injection within a Mobile application backend API. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Ruby on Rails parses Session Cookies mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Mobile application backend API. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on JKU/X5U Injection. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 150. API Auth - Improper Asset Management against GraphQL (Relay)

**Target Area**: Bearer Tokens / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting Improper Asset Management within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Improper Asset Management within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how GraphQL (Relay) parses Bearer Tokens mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Improper Asset Management. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 151. API Auth - Mass Assignment against Go (Gin)

**Target Area**: OTP via Email / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting Mass Assignment within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Mass Assignment within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Go (Gin) parses OTP via Email mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Mass Assignment. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 152. API Auth - Algorithm Confusion against Apigee

**Target Area**: MFA Totp / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting Algorithm Confusion within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Algorithm Confusion within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Apigee parses MFA Totp mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Algorithm Confusion. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 153. API Auth - Type Confusion against Django (Python)

**Target Area**: SAML / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting Type Confusion within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Type Confusion within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Django (Python) parses SAML mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Type Confusion. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 154. API Auth - Signature Stripping against ASP.NET Core

**Target Area**: Magic Links / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting Signature Stripping within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Signature Stripping within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how ASP.NET Core parses Magic Links mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Signature Stripping. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 155. API Auth - Mass Assignment against Go (Gin)

**Target Area**: API Keys / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting Mass Assignment within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Mass Assignment within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Go (Gin) parses API Keys mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Mass Assignment. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 156. API Auth - GraphQL Aliasing against Supabase

**Target Area**: Session Cookies / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting GraphQL Aliasing within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting GraphQL Aliasing within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Supabase parses Session Cookies mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on GraphQL Aliasing. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Elevation of privilege within a specific tenant space. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 157. API Auth - SSRF via Webhook against Kong API Gateway

**Target Area**: OAuth2 / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via Webhook within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via Webhook within a Multi-tenant application environment. This module is built for rigorous edge-case testing.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Kong API Gateway parses OAuth2 mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on SSRF via Webhook. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
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

### 158. API Auth - KID Manipulation targeting Supabase

**Target Area**: Internal Logic / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting KID Manipulation within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting KID Manipulation within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Supabase handles user-supplied data in the context of KID Manipulation.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on KID Manipulation. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data.</step>
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

### 159. API Auth - Type Confusion targeting FastAPI

**Target Area**: Internal Logic / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting Type Confusion within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Type Confusion within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how FastAPI handles user-supplied data in the context of Type Confusion.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Type Confusion. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users.</step>
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

### 160. API Auth - GraphQL Introspection targeting Apigee

**Target Area**: Internal Logic / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting GraphQL Introspection within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting GraphQL Introspection within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee handles user-supplied data in the context of GraphQL Introspection.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on GraphQL Introspection. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data.</step>
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

### 161. API Auth - Type Confusion targeting Flask (Python)

**Target Area**: Internal Logic / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting Type Confusion within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Type Confusion within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Flask (Python) handles user-supplied data in the context of Type Confusion.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Type Confusion. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users.</step>
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

### 162. API Auth - Signature Stripping targeting Node.js/Express

**Target Area**: Internal Logic / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting Signature Stripping within a Third-party integration webhook. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Signature Stripping within a Third-party integration webhook. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Node.js/Express handles user-supplied data in the context of Signature Stripping.</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Signature Stripping. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data.</step>
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

### 163. API Auth - Type Confusion targeting Flask (Python)

**Target Area**: Internal Logic / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting Type Confusion within a Multi-tenant application environment. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Type Confusion within a Multi-tenant application environment. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Flask (Python) handles user-supplied data in the context of Type Confusion.</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Type Confusion. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data.</step>
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

### 164. API Auth - JKU/X5U Injection targeting GraphQL (Relay)

**Target Area**: Internal Logic / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting JKU/X5U Injection within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting JKU/X5U Injection within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) handles user-supplied data in the context of JKU/X5U Injection.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on JKU/X5U Injection. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data.</step>
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

### 165. API Auth - JKU/X5U Injection targeting Kong API Gateway

**Target Area**: Internal Logic / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting JKU/X5U Injection within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting JKU/X5U Injection within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Kong API Gateway handles user-supplied data in the context of JKU/X5U Injection.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on JKU/X5U Injection. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users.</step>
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

### 166. API Auth - Improper Asset Management targeting Go (Fiber)

**Target Area**: Internal Logic / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting Improper Asset Management within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Improper Asset Management within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Fiber) handles user-supplied data in the context of Improper Asset Management.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Improper Asset Management. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users.</step>
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

### 167. API Auth - Mass Assignment targeting ASP.NET Core

**Target Area**: Internal Logic / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting Mass Assignment within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Mass Assignment within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core handles user-supplied data in the context of Mass Assignment.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Mass Assignment. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data.</step>
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

### 168. API Auth - KID Manipulation targeting Kong API Gateway

**Target Area**: Internal Logic / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting KID Manipulation within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting KID Manipulation within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Kong API Gateway handles user-supplied data in the context of KID Manipulation.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on KID Manipulation. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users.</step>
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

### 169. API Auth - JKU/X5U Injection targeting Firebase

**Target Area**: Internal Logic / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting JKU/X5U Injection within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting JKU/X5U Injection within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase handles user-supplied data in the context of JKU/X5U Injection.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on JKU/X5U Injection. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data.</step>
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

### 170. API Auth - BOLA/IDOR targeting Go (Gin)

**Target Area**: Internal Logic / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting BOLA/IDOR within a Multi-tenant application environment. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting BOLA/IDOR within a Multi-tenant application environment. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Gin) handles user-supplied data in the context of BOLA/IDOR.</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on BOLA/IDOR. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users.</step>
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

### 171. API Auth - Signature Stripping targeting Azure API Management

**Target Area**: Internal Logic / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting Signature Stripping within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Signature Stripping within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Azure API Management handles user-supplied data in the context of Signature Stripping.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Signature Stripping. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users.</step>
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

### 172. API Auth - Rate Limiting Bypass targeting Go (Fiber)

**Target Area**: Internal Logic / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting Rate Limiting Bypass within a Mobile application backend API. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Rate Limiting Bypass within a Mobile application backend API. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Fiber) handles user-supplied data in the context of Rate Limiting Bypass.</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Rate Limiting Bypass. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users.</step>
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

### 173. API Auth - GraphQL Aliasing targeting Flask (Python)

**Target Area**: Internal Logic / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting GraphQL Aliasing within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting GraphQL Aliasing within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Flask (Python) handles user-supplied data in the context of GraphQL Aliasing.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on GraphQL Aliasing. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data.</step>
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

### 174. API Auth - GraphQL Introspection targeting Firebase

**Target Area**: Internal Logic / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting GraphQL Introspection within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting GraphQL Introspection within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase handles user-supplied data in the context of GraphQL Introspection.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on GraphQL Introspection. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data.</step>
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

### 175. API Auth - Mass Assignment targeting FastAPI

**Target Area**: Internal Logic / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting Mass Assignment within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Mass Assignment within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how FastAPI handles user-supplied data in the context of Mass Assignment.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Mass Assignment. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data.</step>
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

### 176. API Auth - Improper Asset Management targeting Apigee

**Target Area**: Internal Logic / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting Improper Asset Management within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Improper Asset Management within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee handles user-supplied data in the context of Improper Asset Management.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Improper Asset Management. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users.</step>
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

### 177. API Auth - SSRF via Webhook targeting Spring Boot (Java)

**Target Area**: Internal Logic / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via Webhook within a Third-party integration webhook. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via Webhook within a Third-party integration webhook. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Spring Boot (Java) handles user-supplied data in the context of SSRF via Webhook.</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF via Webhook. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data.</step>
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

### 178. API Auth - Improper Asset Management targeting GraphQL (Relay)

**Target Area**: Internal Logic / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting Improper Asset Management within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Improper Asset Management within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) handles user-supplied data in the context of Improper Asset Management.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Improper Asset Management. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data.</step>
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

### 179. API Auth - GraphQL Introspection targeting Firebase

**Target Area**: Internal Logic / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting GraphQL Introspection within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting GraphQL Introspection within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase handles user-supplied data in the context of GraphQL Introspection.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on GraphQL Introspection. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users.</step>
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

### 180. API Auth - Mass Assignment targeting Rust (Actix)

**Target Area**: Internal Logic / Rust (Actix) architecture
**Description**: An extensive operational guide for identifying and exploiting Mass Assignment within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Mass Assignment within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Rust (Actix) handles user-supplied data in the context of Mass Assignment.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Mass Assignment. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data.</step>
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

### 181. API Auth - JKU/X5U Injection targeting FastAPI

**Target Area**: Internal Logic / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting JKU/X5U Injection within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting JKU/X5U Injection within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how FastAPI handles user-supplied data in the context of JKU/X5U Injection.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on JKU/X5U Injection. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data.</step>
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

### 182. API Auth - Type Confusion targeting GraphQL (Relay)

**Target Area**: Internal Logic / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting Type Confusion within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Type Confusion within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) handles user-supplied data in the context of Type Confusion.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Type Confusion. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data.</step>
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

### 183. API Auth - JKU/X5U Injection targeting Django (Python)

**Target Area**: Internal Logic / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting JKU/X5U Injection within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting JKU/X5U Injection within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Django (Python) handles user-supplied data in the context of JKU/X5U Injection.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on JKU/X5U Injection. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users.</step>
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

### 184. API Auth - Signature Stripping targeting GraphQL (Apollo)

**Target Area**: Internal Logic / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting Signature Stripping within a Multi-tenant application environment. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Signature Stripping within a Multi-tenant application environment. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) handles user-supplied data in the context of Signature Stripping.</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Signature Stripping. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users.</step>
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

### 185. API Auth - Signature Stripping targeting Apigee

**Target Area**: Internal Logic / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting Signature Stripping within a Mobile application backend API. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Signature Stripping within a Mobile application backend API. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee handles user-supplied data in the context of Signature Stripping.</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Signature Stripping. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data.</step>
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

### 186. API Auth - Rate Limiting Bypass targeting GraphQL (Relay)

**Target Area**: Internal Logic / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting Rate Limiting Bypass within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Rate Limiting Bypass within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) handles user-supplied data in the context of Rate Limiting Bypass.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Rate Limiting Bypass. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data.</step>
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

### 187. API Auth - Algorithm Confusion targeting Laravel (PHP)

**Target Area**: Internal Logic / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting Algorithm Confusion within a Third-party integration webhook. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Algorithm Confusion within a Third-party integration webhook. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) handles user-supplied data in the context of Algorithm Confusion.</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Algorithm Confusion. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users.</step>
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

### 188. API Auth - BFLA targeting Firebase

**Target Area**: Internal Logic / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting BFLA within a Third-party integration webhook. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting BFLA within a Third-party integration webhook. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase handles user-supplied data in the context of BFLA.</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on BFLA. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data.</step>
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

### 189. API Auth - SSRF via Webhook targeting Spring Boot (Java)

**Target Area**: Internal Logic / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via Webhook within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via Webhook within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Spring Boot (Java) handles user-supplied data in the context of SSRF via Webhook.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF via Webhook. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data.</step>
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

### 190. API Auth - Signature Stripping targeting FastAPI

**Target Area**: Internal Logic / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting Signature Stripping within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Signature Stripping within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how FastAPI handles user-supplied data in the context of Signature Stripping.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Signature Stripping. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data.</step>
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

### 191. API Auth - Improper Asset Management targeting Node.js/Express

**Target Area**: Internal Logic / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting Improper Asset Management within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Improper Asset Management within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Node.js/Express handles user-supplied data in the context of Improper Asset Management.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Improper Asset Management. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users.</step>
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

### 192. API Auth - Rate Limiting Bypass targeting ASP.NET Core

**Target Area**: Internal Logic / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting Rate Limiting Bypass within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Rate Limiting Bypass within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core handles user-supplied data in the context of Rate Limiting Bypass.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Rate Limiting Bypass. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data.</step>
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

### 193. API Auth - Type Confusion targeting Firebase

**Target Area**: Internal Logic / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting Type Confusion within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Type Confusion within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase handles user-supplied data in the context of Type Confusion.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Type Confusion. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data.</step>
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

### 194. API Auth - SSRF via Webhook targeting Supabase

**Target Area**: Internal Logic / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via Webhook within a Multi-tenant application environment. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via Webhook within a Multi-tenant application environment. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Supabase handles user-supplied data in the context of SSRF via Webhook.</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF via Webhook. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data.</step>
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

### 195. API Auth - GraphQL Introspection targeting Laravel (PHP)

**Target Area**: Internal Logic / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting GraphQL Introspection within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting GraphQL Introspection within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) handles user-supplied data in the context of GraphQL Introspection.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on GraphQL Introspection. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data.</step>
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

### 196. API Auth - GraphQL Introspection targeting Go (Fiber)

**Target Area**: Internal Logic / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting GraphQL Introspection within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting GraphQL Introspection within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Fiber) handles user-supplied data in the context of GraphQL Introspection.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on GraphQL Introspection. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data.</step>
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

### 197. API Auth - BFLA targeting Laravel (PHP)

**Target Area**: Internal Logic / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting BFLA within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting BFLA within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) handles user-supplied data in the context of BFLA.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on BFLA. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users.</step>
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

### 198. API Auth - KID Manipulation targeting AWS API Gateway

**Target Area**: Internal Logic / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting KID Manipulation within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting KID Manipulation within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how AWS API Gateway handles user-supplied data in the context of KID Manipulation.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on KID Manipulation. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data.</step>
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

### 199. API Auth - Improper Asset Management targeting GraphQL (Apollo)

**Target Area**: Internal Logic / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting Improper Asset Management within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Improper Asset Management within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) handles user-supplied data in the context of Improper Asset Management.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Improper Asset Management. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data.</step>
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

### 200. API Auth - BOLA/IDOR targeting Node.js/Express

**Target Area**: Internal Logic / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting BOLA/IDOR within a Mobile application backend API. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting BOLA/IDOR within a Mobile application backend API. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Node.js/Express handles user-supplied data in the context of BOLA/IDOR.</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on BOLA/IDOR. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users.</step>
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

### 201. API Auth - BFLA targeting Firebase

**Target Area**: Internal Logic / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting BFLA within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting BFLA within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase handles user-supplied data in the context of BFLA.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on BFLA. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data.</step>
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

### 202. API Auth - SSRF via Webhook targeting Spring Boot (Java)

**Target Area**: Internal Logic / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via Webhook within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via Webhook within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Spring Boot (Java) handles user-supplied data in the context of SSRF via Webhook.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF via Webhook. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users.</step>
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

### 203. API Auth - Type Confusion targeting Go (Gin)

**Target Area**: Internal Logic / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting Type Confusion within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Type Confusion within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Gin) handles user-supplied data in the context of Type Confusion.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Type Confusion. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data.</step>
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

### 204. API Auth - SSRF via Webhook targeting FastAPI

**Target Area**: Internal Logic / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via Webhook within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via Webhook within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how FastAPI handles user-supplied data in the context of SSRF via Webhook.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF via Webhook. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users.</step>
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

### 205. API Auth - SSRF via Webhook targeting FastAPI

**Target Area**: Internal Logic / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via Webhook within a Third-party integration webhook. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via Webhook within a Third-party integration webhook. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how FastAPI handles user-supplied data in the context of SSRF via Webhook.</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF via Webhook. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data.</step>
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

### 206. API Auth - JKU/X5U Injection targeting GraphQL (Relay)

**Target Area**: Internal Logic / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting JKU/X5U Injection within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting JKU/X5U Injection within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) handles user-supplied data in the context of JKU/X5U Injection.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on JKU/X5U Injection. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data.</step>
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

### 207. API Auth - Type Confusion targeting Flask (Python)

**Target Area**: Internal Logic / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting Type Confusion within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Type Confusion within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Flask (Python) handles user-supplied data in the context of Type Confusion.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Type Confusion. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users.</step>
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

### 208. API Auth - Improper Asset Management targeting Firebase

**Target Area**: Internal Logic / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting Improper Asset Management within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Improper Asset Management within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase handles user-supplied data in the context of Improper Asset Management.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Improper Asset Management. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data.</step>
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

### 209. API Auth - SSRF via Webhook targeting Supabase

**Target Area**: Internal Logic / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via Webhook within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via Webhook within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Supabase handles user-supplied data in the context of SSRF via Webhook.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF via Webhook. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data.</step>
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

### 210. API Auth - KID Manipulation targeting AWS API Gateway

**Target Area**: Internal Logic / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting KID Manipulation within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting KID Manipulation within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how AWS API Gateway handles user-supplied data in the context of KID Manipulation.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on KID Manipulation. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users.</step>
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

### 211. API Auth - SSRF via Webhook targeting Ruby on Rails

**Target Area**: Internal Logic / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via Webhook within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via Webhook within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails handles user-supplied data in the context of SSRF via Webhook.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF via Webhook. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users.</step>
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

### 212. API Auth - KID Manipulation targeting Django (Python)

**Target Area**: Internal Logic / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting KID Manipulation within a Mobile application backend API. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting KID Manipulation within a Mobile application backend API. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Django (Python) handles user-supplied data in the context of KID Manipulation.</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on KID Manipulation. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data.</step>
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

### 213. API Auth - GraphQL Introspection targeting FastAPI

**Target Area**: Internal Logic / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting GraphQL Introspection within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting GraphQL Introspection within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how FastAPI handles user-supplied data in the context of GraphQL Introspection.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on GraphQL Introspection. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users.</step>
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

### 214. API Auth - GraphQL Aliasing targeting Flask (Python)

**Target Area**: Internal Logic / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting GraphQL Aliasing within a Mobile application backend API. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting GraphQL Aliasing within a Mobile application backend API. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Flask (Python) handles user-supplied data in the context of GraphQL Aliasing.</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on GraphQL Aliasing. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users.</step>
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

### 215. API Auth - BFLA targeting Kong API Gateway

**Target Area**: Internal Logic / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting BFLA within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting BFLA within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Kong API Gateway handles user-supplied data in the context of BFLA.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on BFLA. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users.</step>
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

### 216. API Auth - Mass Assignment targeting GraphQL (Relay)

**Target Area**: Internal Logic / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting Mass Assignment within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Mass Assignment within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) handles user-supplied data in the context of Mass Assignment.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Mass Assignment. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users.</step>
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

### 217. API Auth - Mass Assignment targeting ASP.NET Core

**Target Area**: Internal Logic / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting Mass Assignment within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Mass Assignment within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core handles user-supplied data in the context of Mass Assignment.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Mass Assignment. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users.</step>
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

### 218. API Auth - Mass Assignment targeting GraphQL (Apollo)

**Target Area**: Internal Logic / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting Mass Assignment within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Mass Assignment within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) handles user-supplied data in the context of Mass Assignment.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Mass Assignment. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data.</step>
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

### 219. API Auth - Algorithm Confusion targeting GraphQL (Apollo)

**Target Area**: Internal Logic / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting Algorithm Confusion within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Algorithm Confusion within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) handles user-supplied data in the context of Algorithm Confusion.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Algorithm Confusion. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users.</step>
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

### 220. API Auth - SSRF via Webhook targeting Apigee

**Target Area**: Internal Logic / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via Webhook within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via Webhook within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee handles user-supplied data in the context of SSRF via Webhook.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF via Webhook. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users.</step>
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

### 221. API Auth - JKU/X5U Injection targeting Node.js/Express

**Target Area**: Internal Logic / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting JKU/X5U Injection within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting JKU/X5U Injection within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Node.js/Express handles user-supplied data in the context of JKU/X5U Injection.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on JKU/X5U Injection. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data.</step>
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

### 222. API Auth - Improper Asset Management targeting Django (Python)

**Target Area**: Internal Logic / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting Improper Asset Management within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Improper Asset Management within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Django (Python) handles user-supplied data in the context of Improper Asset Management.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Improper Asset Management. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users.</step>
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

### 223. API Auth - Mass Assignment targeting Flask (Python)

**Target Area**: Internal Logic / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting Mass Assignment within a Third-party integration webhook. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Mass Assignment within a Third-party integration webhook. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Flask (Python) handles user-supplied data in the context of Mass Assignment.</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Mass Assignment. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users.</step>
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

### 224. API Auth - Improper Asset Management targeting Rust (Actix)

**Target Area**: Internal Logic / Rust (Actix) architecture
**Description**: An extensive operational guide for identifying and exploiting Improper Asset Management within a Mobile application backend API. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Improper Asset Management within a Mobile application backend API. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Rust (Actix) handles user-supplied data in the context of Improper Asset Management.</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Improper Asset Management. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users.</step>
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

### 225. API Auth - Rate Limiting Bypass targeting Azure API Management

**Target Area**: Internal Logic / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting Rate Limiting Bypass within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Rate Limiting Bypass within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Azure API Management handles user-supplied data in the context of Rate Limiting Bypass.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Rate Limiting Bypass. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data.</step>
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

### 226. API Auth - BFLA targeting Ruby on Rails

**Target Area**: Internal Logic / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting BFLA within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting BFLA within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails handles user-supplied data in the context of BFLA.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on BFLA. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users.</step>
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

### 227. API Auth - SSRF via Webhook targeting Rust (Actix)

**Target Area**: Internal Logic / Rust (Actix) architecture
**Description**: An extensive operational guide for identifying and exploiting SSRF via Webhook within a Mobile application backend API. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting SSRF via Webhook within a Mobile application backend API. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Rust (Actix) handles user-supplied data in the context of SSRF via Webhook.</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on SSRF via Webhook. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users.</step>
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

### 228. API Auth - Improper Asset Management targeting Django (Python)

**Target Area**: Internal Logic / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting Improper Asset Management within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    An extensive operational guide for identifying and exploiting Improper Asset Management within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing and deep analysis.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Django (Python) handles user-supplied data in the context of Improper Asset Management.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Improper Asset Management. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users.</step>
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

