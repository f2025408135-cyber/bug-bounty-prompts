# Client-Side Bug Bounty Skills

A curated, extensive collection of 151 advanced skills for Client-Side bug bounty hunting. Built for the Bug Bounty System Harness.

### 1. Client-Side - Reflected XSS against GraphQL (Apollo)

**Target Area**: SSO (OIDC) / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting Reflected XSS within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how GraphQL (Apollo) parses SSO (OIDC) mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Reflected XSS. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 2. Client-Side - CSRF via CORS Bypass against Django (Python)

**Target Area**: SSO (OIDC) / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting CSRF via CORS Bypass within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Django (Python) parses SSO (OIDC) mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on CSRF via CORS Bypass. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 3. Client-Side - CSS Injection against Kong API Gateway

**Target Area**: JWT / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting CSS Injection within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Kong API Gateway parses JWT mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on CSS Injection. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 4. Client-Side - PostMessage Vulnerabilities against FastAPI

**Target Area**: Magic Links / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting PostMessage Vulnerabilities within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how FastAPI parses Magic Links mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on PostMessage Vulnerabilities. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Elevation of privilege within a specific tenant space. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 5. Client-Side - Client-Side Path Traversal against ASP.NET Core

**Target Area**: SSO (OIDC) / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting Client-Side Path Traversal within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how ASP.NET Core parses SSO (OIDC) mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Client-Side Path Traversal. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 6. Client-Side - Reflected XSS against Go (Gin)

**Target Area**: Session Cookies / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting Reflected XSS within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Go (Gin) parses Session Cookies mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Reflected XSS. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 7. Client-Side - CSRF via CORS Bypass against Go (Gin)

**Target Area**: OTP via SMS / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting CSRF via CORS Bypass within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Go (Gin) parses OTP via SMS mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on CSRF via CORS Bypass. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 8. Client-Side - CSRF Auto-submission against Spring Boot (Java)

**Target Area**: Basic Auth / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting CSRF Auto-submission within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Spring Boot (Java) parses Basic Auth mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on CSRF Auto-submission. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 9. Client-Side - HTML Injection against FastAPI

**Target Area**: Basic Auth / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting HTML Injection within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how FastAPI parses Basic Auth mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Mobile application backend API. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on HTML Injection. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 10. Client-Side - Clickjacking against Supabase

**Target Area**: SAML / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting Clickjacking within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Supabase parses SAML mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Clickjacking. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 11. Client-Side - Open Redirect against Firebase

**Target Area**: API Keys / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting Open Redirect within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Firebase parses API Keys mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Open Redirect. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 12. Client-Side - Open Redirect against GraphQL (Relay)

**Target Area**: OTP via Email / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting Open Redirect within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how GraphQL (Relay) parses OTP via Email mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Open Redirect. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 13. Client-Side - PostMessage Vulnerabilities against Go (Gin)

**Target Area**: OAuth2 / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting PostMessage Vulnerabilities within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Go (Gin) parses OAuth2 mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on PostMessage Vulnerabilities. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 14. Client-Side - Client-Side Path Traversal against Go (Gin)

**Target Area**: OTP via Email / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting Client-Side Path Traversal within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Go (Gin) parses OTP via Email mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Mobile application backend API. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Client-Side Path Traversal. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 15. Client-Side - DOM-based XSS against Supabase

**Target Area**: JWT / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting DOM-based XSS within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Supabase parses JWT mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on DOM-based XSS. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 16. Client-Side - Prototype Pollution against GraphQL (Relay)

**Target Area**: JWT / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting Prototype Pollution within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how GraphQL (Relay) parses JWT mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Mobile application backend API. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Prototype Pollution. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Elevation of privilege within a specific tenant space. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 17. Client-Side - Client-Side Path Traversal against GraphQL (Apollo)

**Target Area**: SSO (OIDC) / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting Client-Side Path Traversal within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how GraphQL (Apollo) parses SSO (OIDC) mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Client-Side Path Traversal. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 18. Client-Side - Reflected XSS against Ruby on Rails

**Target Area**: SAML / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting Reflected XSS within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Ruby on Rails parses SAML mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Reflected XSS. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 19. Client-Side - Blind XSS against Rust (Actix)

**Target Area**: OTP via Email / Rust (Actix) architecture
**Description**: An extensive operational guide for identifying and exploiting Blind XSS within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Rust (Actix) parses OTP via Email mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Blind XSS. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 20. Client-Side - Prototype Pollution against Ruby on Rails

**Target Area**: Basic Auth / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting Prototype Pollution within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Ruby on Rails parses Basic Auth mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Prototype Pollution. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 21. Client-Side - CSS Injection against Django (Python)

**Target Area**: Basic Auth / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting CSS Injection within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Django (Python) parses Basic Auth mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on CSS Injection. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 22. Client-Side - CSRF via CORS Bypass against Go (Fiber)

**Target Area**: JWT / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting CSRF via CORS Bypass within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Go (Fiber) parses JWT mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on CSRF via CORS Bypass. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 23. Client-Side - WebSockets Hijacking against AWS API Gateway

**Target Area**: OAuth2 / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting WebSockets Hijacking within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how AWS API Gateway parses OAuth2 mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on WebSockets Hijacking. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 24. Client-Side - CSS Injection against Go (Fiber)

**Target Area**: OTP via Email / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting CSS Injection within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Go (Fiber) parses OTP via Email mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on CSS Injection. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 25. Client-Side - Open Redirect against Firebase

**Target Area**: SAML / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting Open Redirect within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Firebase parses SAML mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Open Redirect. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 26. Client-Side - WebSockets Hijacking against ASP.NET Core

**Target Area**: MFA Totp / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting WebSockets Hijacking within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how ASP.NET Core parses MFA Totp mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on WebSockets Hijacking. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 27. Client-Side - Client-Side Path Traversal against Rust (Actix)

**Target Area**: OTP via SMS / Rust (Actix) architecture
**Description**: An extensive operational guide for identifying and exploiting Client-Side Path Traversal within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Rust (Actix) parses OTP via SMS mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Client-Side Path Traversal. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 28. Client-Side - CSRF Auto-submission against ASP.NET Core

**Target Area**: OTP via SMS / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting CSRF Auto-submission within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how ASP.NET Core parses OTP via SMS mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on CSRF Auto-submission. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 29. Client-Side - Stored XSS against Laravel (PHP)

**Target Area**: Magic Links / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting Stored XSS within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Laravel (PHP) parses Magic Links mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Stored XSS. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 30. Client-Side - CSRF via CORS Bypass against Azure API Management

**Target Area**: OTP via SMS / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting CSRF via CORS Bypass within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Azure API Management parses OTP via SMS mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on CSRF via CORS Bypass. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 31. Client-Side - Prototype Pollution against Django (Python)

**Target Area**: Bearer Tokens / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting Prototype Pollution within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Django (Python) parses Bearer Tokens mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Prototype Pollution. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 32. Client-Side - PostMessage Vulnerabilities against GraphQL (Relay)

**Target Area**: OAuth2 / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting PostMessage Vulnerabilities within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how GraphQL (Relay) parses OAuth2 mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on PostMessage Vulnerabilities. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 33. Client-Side - CSRF via CORS Bypass against Django (Python)

**Target Area**: MFA Totp / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting CSRF via CORS Bypass within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Django (Python) parses MFA Totp mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on CSRF via CORS Bypass. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 34. Client-Side - CSRF via CORS Bypass against Ruby on Rails

**Target Area**: OTP via Email / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting CSRF via CORS Bypass within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Ruby on Rails parses OTP via Email mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on CSRF via CORS Bypass. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Elevation of privilege within a specific tenant space. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 35. Client-Side - CSS Injection against Ruby on Rails

**Target Area**: JWT / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting CSS Injection within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Ruby on Rails parses JWT mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on CSS Injection. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 36. Client-Side - PostMessage Vulnerabilities against Ruby on Rails

**Target Area**: SAML / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting PostMessage Vulnerabilities within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Ruby on Rails parses SAML mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Mobile application backend API. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on PostMessage Vulnerabilities. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 37. Client-Side - Open Redirect against Symfony (PHP)

**Target Area**: API Keys / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting Open Redirect within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Symfony (PHP) parses API Keys mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Open Redirect. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 38. Client-Side - CSRF Auto-submission against Laravel (PHP)

**Target Area**: SAML / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting CSRF Auto-submission within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Laravel (PHP) parses SAML mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on CSRF Auto-submission. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 39. Client-Side - Prototype Pollution against Azure API Management

**Target Area**: MFA Totp / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting Prototype Pollution within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Azure API Management parses MFA Totp mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Prototype Pollution. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 40. Client-Side - Prototype Pollution against Kong API Gateway

**Target Area**: MFA Totp / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting Prototype Pollution within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Kong API Gateway parses MFA Totp mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Prototype Pollution. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 41. Client-Side - Open Redirect against Apigee

**Target Area**: JWT / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting Open Redirect within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Apigee parses JWT mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Open Redirect. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 42. Client-Side - Stored XSS against Spring Boot (Java)

**Target Area**: Session Cookies / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting Stored XSS within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Spring Boot (Java) parses Session Cookies mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Mobile application backend API. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Stored XSS. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Elevation of privilege within a specific tenant space. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 43. Client-Side - Clickjacking against Apigee

**Target Area**: MFA Totp / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting Clickjacking within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Apigee parses MFA Totp mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Clickjacking. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 44. Client-Side - CSRF Auto-submission against Go (Gin)

**Target Area**: MFA Totp / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting CSRF Auto-submission within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Go (Gin) parses MFA Totp mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on CSRF Auto-submission. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 45. Client-Side - CSRF Auto-submission against Supabase

**Target Area**: JWT / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting CSRF Auto-submission within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Supabase parses JWT mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on CSRF Auto-submission. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Elevation of privilege within a specific tenant space. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 46. Client-Side - WebSockets Hijacking against GraphQL (Relay)

**Target Area**: Session Cookies / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting WebSockets Hijacking within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how GraphQL (Relay) parses Session Cookies mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on WebSockets Hijacking. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 47. Client-Side - Prototype Pollution against Ruby on Rails

**Target Area**: Basic Auth / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting Prototype Pollution within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Ruby on Rails parses Basic Auth mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Prototype Pollution. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Elevation of privilege within a specific tenant space. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 48. Client-Side - Clickjacking against Ruby on Rails

**Target Area**: OTP via SMS / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting Clickjacking within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Ruby on Rails parses OTP via SMS mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Clickjacking. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 49. Client-Side - CSRF via CORS Bypass against Symfony (PHP)

**Target Area**: API Keys / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting CSRF via CORS Bypass within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Symfony (PHP) parses API Keys mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on CSRF via CORS Bypass. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 50. Client-Side - Blind XSS against Ruby on Rails

**Target Area**: API Keys / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting Blind XSS within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Ruby on Rails parses API Keys mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Blind XSS. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 51. Client-Side - HTML Injection against Apigee

**Target Area**: SAML / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting HTML Injection within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Apigee parses SAML mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on HTML Injection. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 52. Client-Side - Prototype Pollution against FastAPI

**Target Area**: Magic Links / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting Prototype Pollution within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how FastAPI parses Magic Links mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Prototype Pollution. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 53. Client-Side - WebSockets Hijacking against Firebase

**Target Area**: JWT / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting WebSockets Hijacking within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Firebase parses JWT mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Mobile application backend API. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on WebSockets Hijacking. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 54. Client-Side - Clickjacking against AWS API Gateway

**Target Area**: Session Cookies / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting Clickjacking within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how AWS API Gateway parses Session Cookies mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Clickjacking. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 55. Client-Side - CSRF via CORS Bypass against Spring Boot (Java)

**Target Area**: Magic Links / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting CSRF via CORS Bypass within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Spring Boot (Java) parses Magic Links mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on CSRF via CORS Bypass. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 56. Client-Side - HTML Injection against Firebase

**Target Area**: JWT / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting HTML Injection within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Firebase parses JWT mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Mobile application backend API. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on HTML Injection. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 57. Client-Side - Clickjacking against Ruby on Rails

**Target Area**: Basic Auth / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting Clickjacking within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Ruby on Rails parses Basic Auth mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Mobile application backend API. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Clickjacking. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Elevation of privilege within a specific tenant space. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 58. Client-Side - CSRF via CORS Bypass against Spring Boot (Java)

**Target Area**: OTP via Email / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting CSRF via CORS Bypass within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Spring Boot (Java) parses OTP via Email mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on CSRF via CORS Bypass. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 59. Client-Side - Blind XSS against Rust (Actix)

**Target Area**: OAuth2 / Rust (Actix) architecture
**Description**: An extensive operational guide for identifying and exploiting Blind XSS within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Rust (Actix) parses OAuth2 mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Blind XSS. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 60. Client-Side - PostMessage Vulnerabilities against Supabase

**Target Area**: OTP via Email / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting PostMessage Vulnerabilities within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Supabase parses OTP via Email mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on PostMessage Vulnerabilities. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 61. Client-Side - Stored XSS against Ruby on Rails

**Target Area**: Basic Auth / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting Stored XSS within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Ruby on Rails parses Basic Auth mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Stored XSS. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 62. Client-Side - PostMessage Vulnerabilities against Rust (Actix)

**Target Area**: OTP via Email / Rust (Actix) architecture
**Description**: An extensive operational guide for identifying and exploiting PostMessage Vulnerabilities within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Rust (Actix) parses OTP via Email mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on PostMessage Vulnerabilities. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 63. Client-Side - Clickjacking against AWS API Gateway

**Target Area**: JWT / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting Clickjacking within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how AWS API Gateway parses JWT mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Clickjacking. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 64. Client-Side - Open Redirect against FastAPI

**Target Area**: Magic Links / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting Open Redirect within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how FastAPI parses Magic Links mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Open Redirect. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 65. Client-Side - Prototype Pollution against AWS API Gateway

**Target Area**: OTP via Email / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting Prototype Pollution within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how AWS API Gateway parses OTP via Email mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Prototype Pollution. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 66. Client-Side - DOM-based XSS against GraphQL (Apollo)

**Target Area**: Basic Auth / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting DOM-based XSS within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how GraphQL (Apollo) parses Basic Auth mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Mobile application backend API. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on DOM-based XSS. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 67. Client-Side - HTML Injection against AWS API Gateway

**Target Area**: SSO (OIDC) / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting HTML Injection within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how AWS API Gateway parses SSO (OIDC) mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on HTML Injection. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 68. Client-Side - CSRF Auto-submission against Firebase

**Target Area**: Basic Auth / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting CSRF Auto-submission within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Firebase parses Basic Auth mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on CSRF Auto-submission. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 69. Client-Side - Clickjacking against Kong API Gateway

**Target Area**: SSO (OIDC) / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting Clickjacking within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Kong API Gateway parses SSO (OIDC) mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Mobile application backend API. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Clickjacking. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Elevation of privilege within a specific tenant space. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 70. Client-Side - Prototype Pollution against Firebase

**Target Area**: OTP via Email / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting Prototype Pollution within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Firebase parses OTP via Email mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Mobile application backend API. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Prototype Pollution. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Elevation of privilege within a specific tenant space. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 71. Client-Side - Blind XSS against Spring Boot (Java)

**Target Area**: OTP via SMS / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting Blind XSS within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Spring Boot (Java) parses OTP via SMS mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Blind XSS. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 72. Client-Side - CSS Injection against GraphQL (Apollo)

**Target Area**: Session Cookies / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting CSS Injection within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how GraphQL (Apollo) parses Session Cookies mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on CSS Injection. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Elevation of privilege within a specific tenant space. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 73. Client-Side - Prototype Pollution against Flask (Python)

**Target Area**: Magic Links / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting Prototype Pollution within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Flask (Python) parses Magic Links mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Prototype Pollution. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 74. Client-Side - Clickjacking against Ruby on Rails

**Target Area**: Session Cookies / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting Clickjacking within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Ruby on Rails parses Session Cookies mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Clickjacking. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Elevation of privilege within a specific tenant space. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 75. Client-Side - PostMessage Vulnerabilities against Apigee

**Target Area**: SSO (OIDC) / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting PostMessage Vulnerabilities within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Apigee parses SSO (OIDC) mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on PostMessage Vulnerabilities. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Elevation of privilege within a specific tenant space. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 76. Client-Side - Open Redirect against Ruby on Rails

**Target Area**: OTP via SMS / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting Open Redirect within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Ruby on Rails parses OTP via SMS mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Open Redirect. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 77. Client-Side - Client-Side Path Traversal against Firebase

**Target Area**: Basic Auth / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting Client-Side Path Traversal within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Firebase parses Basic Auth mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Client-Side Path Traversal. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 78. Client-Side - WebSockets Hijacking against Azure API Management

**Target Area**: Basic Auth / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting WebSockets Hijacking within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Azure API Management parses Basic Auth mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on WebSockets Hijacking. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 79. Client-Side - Prototype Pollution against Firebase

**Target Area**: API Keys / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting Prototype Pollution within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Firebase parses API Keys mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Prototype Pollution. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 80. Client-Side - CSRF Auto-submission against Symfony (PHP)

**Target Area**: SSO (OIDC) / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting CSRF Auto-submission within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Symfony (PHP) parses SSO (OIDC) mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Mobile application backend API. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on CSRF Auto-submission. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 81. Client-Side - Open Redirect against Firebase

**Target Area**: Basic Auth / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting Open Redirect within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Firebase parses Basic Auth mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Open Redirect. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 82. Client-Side - CSS Injection against Go (Fiber)

**Target Area**: OTP via Email / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting CSS Injection within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Go (Fiber) parses OTP via Email mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Mobile application backend API. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on CSS Injection. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 83. Client-Side - Clickjacking against GraphQL (Apollo)

**Target Area**: API Keys / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting Clickjacking within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how GraphQL (Apollo) parses API Keys mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Clickjacking. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 84. Client-Side - CSRF Auto-submission against Django (Python)

**Target Area**: MFA Totp / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting CSRF Auto-submission within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Django (Python) parses MFA Totp mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on CSRF Auto-submission. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 85. Client-Side - Open Redirect against Firebase

**Target Area**: OTP via SMS / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting Open Redirect within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Firebase parses OTP via SMS mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Open Redirect. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 86. Client-Side - PostMessage Vulnerabilities against Go (Fiber)

**Target Area**: OTP via Email / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting PostMessage Vulnerabilities within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Go (Fiber) parses OTP via Email mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on PostMessage Vulnerabilities. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 87. Client-Side - Blind XSS against Symfony (PHP)

**Target Area**: OTP via SMS / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting Blind XSS within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Symfony (PHP) parses OTP via SMS mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Blind XSS. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Elevation of privilege within a specific tenant space. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 88. Client-Side - Client-Side Path Traversal against Symfony (PHP)

**Target Area**: Bearer Tokens / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting Client-Side Path Traversal within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Symfony (PHP) parses Bearer Tokens mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Client-Side Path Traversal. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 89. Client-Side - Open Redirect against Firebase

**Target Area**: SAML / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting Open Redirect within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Firebase parses SAML mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Open Redirect. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Elevation of privilege within a specific tenant space. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 90. Client-Side - PostMessage Vulnerabilities against ASP.NET Core

**Target Area**: Magic Links / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting PostMessage Vulnerabilities within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how ASP.NET Core parses Magic Links mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on PostMessage Vulnerabilities. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Elevation of privilege within a specific tenant space. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 91. Client-Side - Client-Side Path Traversal against Laravel (PHP)

**Target Area**: API Keys / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting Client-Side Path Traversal within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Laravel (PHP) parses API Keys mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Mobile application backend API. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Client-Side Path Traversal. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 92. Client-Side - CSS Injection against Django (Python)

**Target Area**: SSO (OIDC) / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting CSS Injection within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Django (Python) parses SSO (OIDC) mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on CSS Injection. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 93. Client-Side - DOM-based XSS against GraphQL (Relay)

**Target Area**: Bearer Tokens / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting DOM-based XSS within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how GraphQL (Relay) parses Bearer Tokens mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on DOM-based XSS. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 94. Client-Side - DOM-based XSS against Go (Gin)

**Target Area**: API Keys / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting DOM-based XSS within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Go (Gin) parses API Keys mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on DOM-based XSS. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 95. Client-Side - Prototype Pollution against Flask (Python)

**Target Area**: Magic Links / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting Prototype Pollution within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Flask (Python) parses Magic Links mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Prototype Pollution. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 96. Client-Side - PostMessage Vulnerabilities against Firebase

**Target Area**: Magic Links / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting PostMessage Vulnerabilities within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Firebase parses Magic Links mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on PostMessage Vulnerabilities. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 97. Client-Side - Blind XSS against Flask (Python)

**Target Area**: SSO (OIDC) / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting Blind XSS within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Flask (Python) parses SSO (OIDC) mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Blind XSS. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 98. Client-Side - Client-Side Path Traversal against Go (Fiber)

**Target Area**: SSO (OIDC) / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting Client-Side Path Traversal within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Go (Fiber) parses SSO (OIDC) mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Client-Side Path Traversal. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 99. Client-Side - CSS Injection against Go (Gin)

**Target Area**: OTP via Email / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting CSS Injection within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Go (Gin) parses OTP via Email mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on CSS Injection. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 100. Client-Side - HTML Injection against GraphQL (Relay)

**Target Area**: OAuth2 / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting HTML Injection within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how GraphQL (Relay) parses OAuth2 mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on HTML Injection. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 101. Client-Side - Client-Side Path Traversal against Flask (Python)

**Target Area**: Magic Links / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting Client-Side Path Traversal within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Flask (Python) parses Magic Links mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Client-Side Path Traversal. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 102. Client-Side - Blind XSS against Node.js/Express

**Target Area**: Session Cookies / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting Blind XSS within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Node.js/Express parses Session Cookies mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Mobile application backend API. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Blind XSS. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 103. Client-Side - CSS Injection against Go (Fiber)

**Target Area**: OTP via Email / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting CSS Injection within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Go (Fiber) parses OTP via Email mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on CSS Injection. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 104. Client-Side - Reflected XSS against Go (Fiber)

**Target Area**: Session Cookies / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting Reflected XSS within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Go (Fiber) parses Session Cookies mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Reflected XSS. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Elevation of privilege within a specific tenant space. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 105. Client-Side - Client-Side Path Traversal against Flask (Python)

**Target Area**: SAML / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting Client-Side Path Traversal within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Flask (Python) parses SAML mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Client-Side Path Traversal. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 106. Client-Side - Client-Side Path Traversal against AWS API Gateway

**Target Area**: OAuth2 / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting Client-Side Path Traversal within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how AWS API Gateway parses OAuth2 mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Mobile application backend API. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Client-Side Path Traversal. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Elevation of privilege within a specific tenant space. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 107. Client-Side - CSRF via CORS Bypass against Apigee

**Target Area**: SAML / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting CSRF via CORS Bypass within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Apigee parses SAML mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on CSRF via CORS Bypass. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 108. Client-Side - DOM-based XSS against Supabase

**Target Area**: SSO (OIDC) / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting DOM-based XSS within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Supabase parses SSO (OIDC) mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on DOM-based XSS. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 109. Client-Side - WebSockets Hijacking against Azure API Management

**Target Area**: MFA Totp / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting WebSockets Hijacking within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Azure API Management parses MFA Totp mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on WebSockets Hijacking. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 110. Client-Side - HTML Injection against Django (Python)

**Target Area**: OTP via SMS / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting HTML Injection within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Django (Python) parses OTP via SMS mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on HTML Injection. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 111. Client-Side - Stored XSS against Kong API Gateway

**Target Area**: OTP via SMS / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting Stored XSS within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Kong API Gateway parses OTP via SMS mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Stored XSS. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 112. Client-Side - Blind XSS against Kong API Gateway

**Target Area**: SAML / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting Blind XSS within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Kong API Gateway parses SAML mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Blind XSS. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 113. Client-Side - HTML Injection against AWS API Gateway

**Target Area**: MFA Totp / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting HTML Injection within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how AWS API Gateway parses MFA Totp mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on HTML Injection. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 114. Client-Side - Open Redirect against Kong API Gateway

**Target Area**: OTP via SMS / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting Open Redirect within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Kong API Gateway parses OTP via SMS mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Open Redirect. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 115. Client-Side - CSS Injection against Spring Boot (Java)

**Target Area**: OTP via SMS / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting CSS Injection within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Spring Boot (Java) parses OTP via SMS mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on CSS Injection. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 116. Client-Side - WebSockets Hijacking against Kong API Gateway

**Target Area**: Magic Links / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting WebSockets Hijacking within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Kong API Gateway parses Magic Links mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on WebSockets Hijacking. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 117. Client-Side - Open Redirect against Node.js/Express

**Target Area**: JWT / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting Open Redirect within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Node.js/Express parses JWT mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Open Redirect. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 118. Client-Side - Prototype Pollution against Django (Python)

**Target Area**: Basic Auth / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting Prototype Pollution within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Django (Python) parses Basic Auth mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Prototype Pollution. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 119. Client-Side - PostMessage Vulnerabilities against Spring Boot (Java)

**Target Area**: JWT / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting PostMessage Vulnerabilities within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Spring Boot (Java) parses JWT mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on PostMessage Vulnerabilities. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 120. Client-Side - Clickjacking against ASP.NET Core

**Target Area**: SSO (OIDC) / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting Clickjacking within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how ASP.NET Core parses SSO (OIDC) mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Clickjacking. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Elevation of privilege within a specific tenant space. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 121. Client-Side - CSRF via CORS Bypass against GraphQL (Apollo)

**Target Area**: Bearer Tokens / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting CSRF via CORS Bypass within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how GraphQL (Apollo) parses Bearer Tokens mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on CSRF via CORS Bypass. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 122. Client-Side - Client-Side Path Traversal against Azure API Management

**Target Area**: Basic Auth / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting Client-Side Path Traversal within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Azure API Management parses Basic Auth mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Client-Side Path Traversal. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Elevation of privilege within a specific tenant space. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 123. Client-Side - DOM-based XSS against Azure API Management

**Target Area**: SAML / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting DOM-based XSS within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Azure API Management parses SAML mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on DOM-based XSS. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 124. Client-Side - HTML Injection against Node.js/Express

**Target Area**: Magic Links / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting HTML Injection within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Node.js/Express parses Magic Links mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on HTML Injection. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 125. Client-Side - Clickjacking against Azure API Management

**Target Area**: Session Cookies / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting Clickjacking within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Azure API Management parses Session Cookies mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Clickjacking. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 126. Client-Side - CSRF via CORS Bypass against Ruby on Rails

**Target Area**: SSO (OIDC) / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting CSRF via CORS Bypass within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Ruby on Rails parses SSO (OIDC) mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Mobile application backend API. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on CSRF via CORS Bypass. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 127. Client-Side - Reflected XSS against GraphQL (Relay)

**Target Area**: Session Cookies / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting Reflected XSS within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how GraphQL (Relay) parses Session Cookies mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Reflected XSS. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 128. Client-Side - Stored XSS against Apigee

**Target Area**: OTP via Email / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting Stored XSS within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Apigee parses OTP via Email mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Stored XSS. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 129. Client-Side - Blind XSS against Spring Boot (Java)

**Target Area**: Session Cookies / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting Blind XSS within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Spring Boot (Java) parses Session Cookies mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Blind XSS. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 130. Client-Side - Blind XSS against Spring Boot (Java)

**Target Area**: API Keys / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting Blind XSS within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Spring Boot (Java) parses API Keys mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Blind XSS. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 131. Client-Side - HTML Injection against Kong API Gateway

**Target Area**: OTP via Email / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting HTML Injection within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Kong API Gateway parses OTP via Email mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on HTML Injection. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 132. Client-Side - Blind XSS against Go (Gin)

**Target Area**: OTP via SMS / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting Blind XSS within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Go (Gin) parses OTP via SMS mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Blind XSS. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Elevation of privilege within a specific tenant space. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 133. Client-Side - Clickjacking against Go (Gin)

**Target Area**: OTP via SMS / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting Clickjacking within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Go (Gin) parses OTP via SMS mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Mobile application backend API. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Clickjacking. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Complete account takeover of administrative users. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 134. Client-Side - Open Redirect against ASP.NET Core

**Target Area**: Magic Links / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting Open Redirect within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how ASP.NET Core parses Magic Links mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Open Redirect. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 135. Client-Side - CSRF via CORS Bypass against GraphQL (Apollo)

**Target Area**: SSO (OIDC) / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting CSRF via CORS Bypass within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how GraphQL (Apollo) parses SSO (OIDC) mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on CSRF via CORS Bypass. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 136. Client-Side - Clickjacking against Ruby on Rails

**Target Area**: SAML / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting Clickjacking within a Mobile application backend API. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Ruby on Rails parses SAML mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Mobile application backend API. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Clickjacking. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 137. Client-Side - WebSockets Hijacking against Symfony (PHP)

**Target Area**: SSO (OIDC) / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting WebSockets Hijacking within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Symfony (PHP) parses SSO (OIDC) mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on WebSockets Hijacking. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 138. Client-Side - CSS Injection against Supabase

**Target Area**: Bearer Tokens / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting CSS Injection within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Supabase parses Bearer Tokens mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on CSS Injection. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 139. Client-Side - PostMessage Vulnerabilities against AWS API Gateway

**Target Area**: Session Cookies / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting PostMessage Vulnerabilities within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how AWS API Gateway parses Session Cookies mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on PostMessage Vulnerabilities. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 140. Client-Side - Blind XSS against FastAPI

**Target Area**: Basic Auth / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting Blind XSS within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how FastAPI parses Basic Auth mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Blind XSS. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 141. Client-Side - PostMessage Vulnerabilities against Laravel (PHP)

**Target Area**: Bearer Tokens / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting PostMessage Vulnerabilities within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Laravel (PHP) parses Bearer Tokens mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on PostMessage Vulnerabilities. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 142. Client-Side - Prototype Pollution against Spring Boot (Java)

**Target Area**: OTP via Email / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting Prototype Pollution within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Spring Boot (Java) parses OTP via Email mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Prototype Pollution. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 143. Client-Side - Blind XSS against Firebase

**Target Area**: API Keys / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting Blind XSS within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Firebase parses API Keys mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Blind XSS. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 144. Client-Side - Blind XSS against Laravel (PHP)

**Target Area**: Magic Links / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting Blind XSS within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Laravel (PHP) parses Magic Links mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Blind XSS. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Elevation of privilege within a specific tenant space. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 145. Client-Side - Open Redirect against Apigee

**Target Area**: Session Cookies / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting Open Redirect within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Apigee parses Session Cookies mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Open Redirect. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 146. Client-Side - CSRF via CORS Bypass against Go (Gin)

**Target Area**: OTP via SMS / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting CSRF via CORS Bypass within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Go (Gin) parses OTP via SMS mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on CSRF via CORS Bypass. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Unauthorized modification of critical business records. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 147. Client-Side - CSRF Auto-submission against Go (Fiber)

**Target Area**: Magic Links / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting CSRF Auto-submission within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Go (Fiber) parses Magic Links mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on CSRF Auto-submission. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 148. Client-Side - Stored XSS against Firebase

**Target Area**: Basic Auth / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting Stored XSS within a Third-party integration webhook. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Firebase parses Basic Auth mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Third-party integration webhook. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Stored XSS. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Extraction of PII or sensitive financial data. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 149. Client-Side - Clickjacking against Spring Boot (Java)

**Target Area**: SAML / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting Clickjacking within a Multi-tenant application environment. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Spring Boot (Java) parses SAML mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Multi-tenant application environment. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on Clickjacking. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Elevation of privilege within a specific tenant space. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 150. Client-Side - CSRF Auto-submission against Azure API Management

**Target Area**: SAML / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting CSRF Auto-submission within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Azure API Management parses SAML mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on CSRF Auto-submission. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Bypassing billing mechanisms resulting in financial loss. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 151. Client-Side - CSRF via CORS Bypass against Symfony (PHP)

**Target Area**: Session Cookies / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting CSRF via CORS Bypass within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data, paying specific attention to how Symfony (PHP) parses Session Cookies mechanisms natively. Identify discrepancies between RFC standards and common implementation mistakes in this stack.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Determine if authorization checks are handled at the gateway layer or the application logic layer. Map out all user-controllable input vectors (headers, query parameters, JSON body).</step>
    <step>Formulate hypotheses focused specifically on CSRF via CORS Bypass. Consider edge cases like malformed headers, unexpected types, or parameter pollution. If WAF signatures are present, develop obfuscation strategies.</step>
    <step>Generate  highly specific, weaponized HTTP requests or payloads targeting the hypothesized flaws. Ensure all payloads are syntactically valid and account for content-length changes.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Denial of service through resource exhaustion. Formulate a non-destructive verification strategy that definitively proves the vulnerability without alerting SOC teams.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 152. Client-Side - Blind XSS targeting GraphQL (Apollo)

**Target Area**: Internal Logic / GraphQL (Apollo) architecture
**Description**: An extensive operational guide for identifying and exploiting Blind XSS within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Apollo) handles user-supplied data in the context of Blind XSS.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Blind XSS. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 6 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Defacement or unauthorized actions performed on behalf of the user.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 153. Client-Side - Client-Side Path Traversal targeting Laravel (PHP)

**Target Area**: Internal Logic / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting Client-Side Path Traversal within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) handles user-supplied data in the context of Client-Side Path Traversal.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Client-Side Path Traversal. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 3 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Session hijacking and account takeover.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 154. Client-Side - HTML Injection targeting GraphQL (Relay)

**Target Area**: Internal Logic / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting HTML Injection within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) handles user-supplied data in the context of HTML Injection.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on HTML Injection. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 4 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Defacement or unauthorized actions performed on behalf of the user.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 155. Client-Side - Prototype Pollution targeting Supabase

**Target Area**: Internal Logic / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting Prototype Pollution within a Third-party integration webhook. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Supabase handles user-supplied data in the context of Prototype Pollution.</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Prototype Pollution. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 6 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Session hijacking and account takeover.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 156. Client-Side - HTML Injection targeting Laravel (PHP)

**Target Area**: Internal Logic / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting HTML Injection within a Multi-tenant application environment. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) handles user-supplied data in the context of HTML Injection.</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on HTML Injection. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 5 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Session hijacking and account takeover.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 157. Client-Side - Stored XSS targeting Azure API Management

**Target Area**: Internal Logic / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting Stored XSS within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Azure API Management handles user-supplied data in the context of Stored XSS.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Stored XSS. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 5 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Session hijacking and account takeover.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 158. Client-Side - PostMessage Vulnerabilities targeting Rust (Actix)

**Target Area**: Internal Logic / Rust (Actix) architecture
**Description**: An extensive operational guide for identifying and exploiting PostMessage Vulnerabilities within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Rust (Actix) handles user-supplied data in the context of PostMessage Vulnerabilities.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on PostMessage Vulnerabilities. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 4 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Session hijacking and account takeover.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 159. Client-Side - DOM-based XSS targeting ASP.NET Core

**Target Area**: Internal Logic / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting DOM-based XSS within a Multi-tenant application environment. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core handles user-supplied data in the context of DOM-based XSS.</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on DOM-based XSS. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 7 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Session hijacking and account takeover.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 160. Client-Side - CSRF Auto-submission targeting Go (Fiber)

**Target Area**: Internal Logic / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting CSRF Auto-submission within a Multi-tenant application environment. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Fiber) handles user-supplied data in the context of CSRF Auto-submission.</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on CSRF Auto-submission. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 7 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Defacement or unauthorized actions performed on behalf of the user.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 161. Client-Side - CSRF Auto-submission targeting Supabase

**Target Area**: Internal Logic / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting CSRF Auto-submission within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Supabase handles user-supplied data in the context of CSRF Auto-submission.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on CSRF Auto-submission. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 6 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Defacement or unauthorized actions performed on behalf of the user.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 162. Client-Side - Stored XSS targeting Flask (Python)

**Target Area**: Internal Logic / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting Stored XSS within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Flask (Python) handles user-supplied data in the context of Stored XSS.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Stored XSS. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 4 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Defacement or unauthorized actions performed on behalf of the user.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 163. Client-Side - Stored XSS targeting Laravel (PHP)

**Target Area**: Internal Logic / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting Stored XSS within a Third-party integration webhook. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) handles user-supplied data in the context of Stored XSS.</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Stored XSS. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 7 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Defacement or unauthorized actions performed on behalf of the user.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 164. Client-Side - CSRF Auto-submission targeting Kong API Gateway

**Target Area**: Internal Logic / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting CSRF Auto-submission within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Kong API Gateway handles user-supplied data in the context of CSRF Auto-submission.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on CSRF Auto-submission. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 8 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Defacement or unauthorized actions performed on behalf of the user.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 165. Client-Side - HTML Injection targeting Symfony (PHP)

**Target Area**: Internal Logic / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting HTML Injection within a Mobile application backend API. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Symfony (PHP) handles user-supplied data in the context of HTML Injection.</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on HTML Injection. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 5 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Session hijacking and account takeover.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 166. Client-Side - Open Redirect targeting Laravel (PHP)

**Target Area**: Internal Logic / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting Open Redirect within a Mobile application backend API. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) handles user-supplied data in the context of Open Redirect.</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Open Redirect. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 4 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Defacement or unauthorized actions performed on behalf of the user.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 167. Client-Side - PostMessage Vulnerabilities targeting Apigee

**Target Area**: Internal Logic / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting PostMessage Vulnerabilities within a Multi-tenant application environment. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee handles user-supplied data in the context of PostMessage Vulnerabilities.</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on PostMessage Vulnerabilities. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 7 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Session hijacking and account takeover.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 168. Client-Side - HTML Injection targeting Spring Boot (Java)

**Target Area**: Internal Logic / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting HTML Injection within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Spring Boot (Java) handles user-supplied data in the context of HTML Injection.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on HTML Injection. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 6 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Defacement or unauthorized actions performed on behalf of the user.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 169. Client-Side - Stored XSS targeting ASP.NET Core

**Target Area**: Internal Logic / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting Stored XSS within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core handles user-supplied data in the context of Stored XSS.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Stored XSS. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 3 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Session hijacking and account takeover.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 170. Client-Side - Reflected XSS targeting GraphQL (Relay)

**Target Area**: Internal Logic / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting Reflected XSS within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) handles user-supplied data in the context of Reflected XSS.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Reflected XSS. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 8 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Defacement or unauthorized actions performed on behalf of the user.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 171. Client-Side - Reflected XSS targeting Azure API Management

**Target Area**: Internal Logic / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting Reflected XSS within a Multi-tenant application environment. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Azure API Management handles user-supplied data in the context of Reflected XSS.</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Reflected XSS. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 6 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Session hijacking and account takeover.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 172. Client-Side - CSRF Auto-submission targeting Symfony (PHP)

**Target Area**: Internal Logic / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting CSRF Auto-submission within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Symfony (PHP) handles user-supplied data in the context of CSRF Auto-submission.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on CSRF Auto-submission. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 7 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Session hijacking and account takeover.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 173. Client-Side - Open Redirect targeting Apigee

**Target Area**: Internal Logic / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting Open Redirect within a Third-party integration webhook. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee handles user-supplied data in the context of Open Redirect.</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Open Redirect. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 5 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Defacement or unauthorized actions performed on behalf of the user.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 174. Client-Side - WebSockets Hijacking targeting Apigee

**Target Area**: Internal Logic / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting WebSockets Hijacking within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee handles user-supplied data in the context of WebSockets Hijacking.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on WebSockets Hijacking. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 8 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Defacement or unauthorized actions performed on behalf of the user.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 175. Client-Side - CSRF Auto-submission targeting Symfony (PHP)

**Target Area**: Internal Logic / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting CSRF Auto-submission within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Symfony (PHP) handles user-supplied data in the context of CSRF Auto-submission.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on CSRF Auto-submission. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 3 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Defacement or unauthorized actions performed on behalf of the user.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 176. Client-Side - Blind XSS targeting FastAPI

**Target Area**: Internal Logic / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting Blind XSS within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how FastAPI handles user-supplied data in the context of Blind XSS.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Blind XSS. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 7 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Session hijacking and account takeover.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 177. Client-Side - PostMessage Vulnerabilities targeting Flask (Python)

**Target Area**: Internal Logic / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting PostMessage Vulnerabilities within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Flask (Python) handles user-supplied data in the context of PostMessage Vulnerabilities.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on PostMessage Vulnerabilities. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 8 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Defacement or unauthorized actions performed on behalf of the user.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 178. Client-Side - Client-Side Path Traversal targeting Rust (Actix)

**Target Area**: Internal Logic / Rust (Actix) architecture
**Description**: An extensive operational guide for identifying and exploiting Client-Side Path Traversal within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Rust (Actix) handles user-supplied data in the context of Client-Side Path Traversal.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Client-Side Path Traversal. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 7 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Defacement or unauthorized actions performed on behalf of the user.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 179. Client-Side - PostMessage Vulnerabilities targeting Laravel (PHP)

**Target Area**: Internal Logic / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting PostMessage Vulnerabilities within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) handles user-supplied data in the context of PostMessage Vulnerabilities.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on PostMessage Vulnerabilities. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 4 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Defacement or unauthorized actions performed on behalf of the user.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 180. Client-Side - Prototype Pollution targeting Spring Boot (Java)

**Target Area**: Internal Logic / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting Prototype Pollution within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Spring Boot (Java) handles user-supplied data in the context of Prototype Pollution.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Prototype Pollution. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 3 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Defacement or unauthorized actions performed on behalf of the user.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 181. Client-Side - PostMessage Vulnerabilities targeting Azure API Management

**Target Area**: Internal Logic / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting PostMessage Vulnerabilities within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Azure API Management handles user-supplied data in the context of PostMessage Vulnerabilities.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on PostMessage Vulnerabilities. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 7 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Defacement or unauthorized actions performed on behalf of the user.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 182. Client-Side - Prototype Pollution targeting Go (Gin)

**Target Area**: Internal Logic / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting Prototype Pollution within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Gin) handles user-supplied data in the context of Prototype Pollution.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Prototype Pollution. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 4 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Defacement or unauthorized actions performed on behalf of the user.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 183. Client-Side - CSS Injection targeting Firebase

**Target Area**: Internal Logic / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting CSS Injection within a Mobile application backend API. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase handles user-supplied data in the context of CSS Injection.</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on CSS Injection. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 3 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Session hijacking and account takeover.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 184. Client-Side - CSRF via CORS Bypass targeting Flask (Python)

**Target Area**: Internal Logic / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting CSRF via CORS Bypass within a Third-party integration webhook. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Flask (Python) handles user-supplied data in the context of CSRF via CORS Bypass.</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on CSRF via CORS Bypass. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 3 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Session hijacking and account takeover.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 185. Client-Side - Blind XSS targeting Go (Gin)

**Target Area**: Internal Logic / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting Blind XSS within a Mobile application backend API. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Gin) handles user-supplied data in the context of Blind XSS.</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Blind XSS. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 3 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Defacement or unauthorized actions performed on behalf of the user.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 186. Client-Side - CSRF Auto-submission targeting Apigee

**Target Area**: Internal Logic / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting CSRF Auto-submission within a Third-party integration webhook. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee handles user-supplied data in the context of CSRF Auto-submission.</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on CSRF Auto-submission. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 5 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Defacement or unauthorized actions performed on behalf of the user.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 187. Client-Side - DOM-based XSS targeting Firebase

**Target Area**: Internal Logic / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting DOM-based XSS within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase handles user-supplied data in the context of DOM-based XSS.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on DOM-based XSS. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 5 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Session hijacking and account takeover.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 188. Client-Side - CSRF Auto-submission targeting ASP.NET Core

**Target Area**: Internal Logic / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting CSRF Auto-submission within a Mobile application backend API. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core handles user-supplied data in the context of CSRF Auto-submission.</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on CSRF Auto-submission. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 6 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Session hijacking and account takeover.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 189. Client-Side - Blind XSS targeting Spring Boot (Java)

**Target Area**: Internal Logic / Spring Boot (Java) architecture
**Description**: An extensive operational guide for identifying and exploiting Blind XSS within a Third-party integration webhook. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Spring Boot (Java) handles user-supplied data in the context of Blind XSS.</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Blind XSS. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 6 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Defacement or unauthorized actions performed on behalf of the user.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 190. Client-Side - CSRF via CORS Bypass targeting Node.js/Express

**Target Area**: Internal Logic / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting CSRF via CORS Bypass within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Node.js/Express handles user-supplied data in the context of CSRF via CORS Bypass.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on CSRF via CORS Bypass. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 3 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Defacement or unauthorized actions performed on behalf of the user.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 191. Client-Side - PostMessage Vulnerabilities targeting GraphQL (Relay)

**Target Area**: Internal Logic / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting PostMessage Vulnerabilities within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) handles user-supplied data in the context of PostMessage Vulnerabilities.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on PostMessage Vulnerabilities. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 5 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Defacement or unauthorized actions performed on behalf of the user.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 192. Client-Side - DOM-based XSS targeting Supabase

**Target Area**: Internal Logic / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting DOM-based XSS within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Supabase handles user-supplied data in the context of DOM-based XSS.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on DOM-based XSS. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 7 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Session hijacking and account takeover.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 193. Client-Side - Stored XSS targeting GraphQL (Relay)

**Target Area**: Internal Logic / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting Stored XSS within a Third-party integration webhook. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) handles user-supplied data in the context of Stored XSS.</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Stored XSS. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 6 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Session hijacking and account takeover.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 194. Client-Side - DOM-based XSS targeting Firebase

**Target Area**: Internal Logic / Firebase architecture
**Description**: An extensive operational guide for identifying and exploiting DOM-based XSS within a Multi-tenant application environment. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Firebase handles user-supplied data in the context of DOM-based XSS.</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on DOM-based XSS. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 3 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Session hijacking and account takeover.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 195. Client-Side - Prototype Pollution targeting Symfony (PHP)

**Target Area**: Internal Logic / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting Prototype Pollution within a Third-party integration webhook. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Symfony (PHP) handles user-supplied data in the context of Prototype Pollution.</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Prototype Pollution. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 8 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Defacement or unauthorized actions performed on behalf of the user.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 196. Client-Side - Reflected XSS targeting Kong API Gateway

**Target Area**: Internal Logic / Kong API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting Reflected XSS within a Third-party integration webhook. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Kong API Gateway handles user-supplied data in the context of Reflected XSS.</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Reflected XSS. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 4 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Defacement or unauthorized actions performed on behalf of the user.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 197. Client-Side - PostMessage Vulnerabilities targeting Laravel (PHP)

**Target Area**: Internal Logic / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting PostMessage Vulnerabilities within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) handles user-supplied data in the context of PostMessage Vulnerabilities.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on PostMessage Vulnerabilities. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 4 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Defacement or unauthorized actions performed on behalf of the user.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 198. Client-Side - CSRF Auto-submission targeting Azure API Management

**Target Area**: Internal Logic / Azure API Management architecture
**Description**: An extensive operational guide for identifying and exploiting CSRF Auto-submission within a Multi-tenant application environment. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Azure API Management handles user-supplied data in the context of CSRF Auto-submission.</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on CSRF Auto-submission. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 8 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Defacement or unauthorized actions performed on behalf of the user.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 199. Client-Side - Stored XSS targeting Ruby on Rails

**Target Area**: Internal Logic / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting Stored XSS within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails handles user-supplied data in the context of Stored XSS.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Stored XSS. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 7 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Defacement or unauthorized actions performed on behalf of the user.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 200. Client-Side - PostMessage Vulnerabilities targeting Apigee

**Target Area**: Internal Logic / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting PostMessage Vulnerabilities within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee handles user-supplied data in the context of PostMessage Vulnerabilities.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on PostMessage Vulnerabilities. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 8 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Defacement or unauthorized actions performed on behalf of the user.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 201. Client-Side - Client-Side Path Traversal targeting Go (Fiber)

**Target Area**: Internal Logic / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting Client-Side Path Traversal within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Fiber) handles user-supplied data in the context of Client-Side Path Traversal.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Client-Side Path Traversal. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 7 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Session hijacking and account takeover.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 202. Client-Side - Stored XSS targeting Rust (Actix)

**Target Area**: Internal Logic / Rust (Actix) architecture
**Description**: An extensive operational guide for identifying and exploiting Stored XSS within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Rust (Actix) handles user-supplied data in the context of Stored XSS.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Stored XSS. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 3 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Defacement or unauthorized actions performed on behalf of the user.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 203. Client-Side - HTML Injection targeting Supabase

**Target Area**: Internal Logic / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting HTML Injection within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Supabase handles user-supplied data in the context of HTML Injection.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on HTML Injection. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 8 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Defacement or unauthorized actions performed on behalf of the user.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 204. Client-Side - CSS Injection targeting Ruby on Rails

**Target Area**: Internal Logic / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting CSS Injection within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails handles user-supplied data in the context of CSS Injection.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on CSS Injection. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 4 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Session hijacking and account takeover.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 205. Client-Side - Reflected XSS targeting Apigee

**Target Area**: Internal Logic / Apigee architecture
**Description**: An extensive operational guide for identifying and exploiting Reflected XSS within a Third-party integration webhook. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Apigee handles user-supplied data in the context of Reflected XSS.</step>
    <step>Analyze the context: Third-party integration webhook. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Reflected XSS. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 6 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Session hijacking and account takeover.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 206. Client-Side - HTML Injection targeting GraphQL (Relay)

**Target Area**: Internal Logic / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting HTML Injection within a Multi-tenant application environment. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) handles user-supplied data in the context of HTML Injection.</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on HTML Injection. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 4 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Session hijacking and account takeover.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 207. Client-Side - Blind XSS targeting Go (Fiber)

**Target Area**: Internal Logic / Go (Fiber) architecture
**Description**: An extensive operational guide for identifying and exploiting Blind XSS within a Multi-tenant application environment. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Fiber) handles user-supplied data in the context of Blind XSS.</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Blind XSS. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 4 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Session hijacking and account takeover.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 208. Client-Side - Reflected XSS targeting AWS API Gateway

**Target Area**: Internal Logic / AWS API Gateway architecture
**Description**: An extensive operational guide for identifying and exploiting Reflected XSS within a Beta feature accessible via feature flags. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how AWS API Gateway handles user-supplied data in the context of Reflected XSS.</step>
    <step>Analyze the context: Beta feature accessible via feature flags. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Reflected XSS. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 5 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Defacement or unauthorized actions performed on behalf of the user.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 209. Client-Side - CSS Injection targeting Laravel (PHP)

**Target Area**: Internal Logic / Laravel (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting CSS Injection within a Multi-tenant application environment. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Laravel (PHP) handles user-supplied data in the context of CSS Injection.</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on CSS Injection. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 6 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Session hijacking and account takeover.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 210. Client-Side - Client-Side Path Traversal targeting Rust (Actix)

**Target Area**: Internal Logic / Rust (Actix) architecture
**Description**: An extensive operational guide for identifying and exploiting Client-Side Path Traversal within a Mobile application backend API. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Rust (Actix) handles user-supplied data in the context of Client-Side Path Traversal.</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Client-Side Path Traversal. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 7 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Defacement or unauthorized actions performed on behalf of the user.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 211. Client-Side - PostMessage Vulnerabilities targeting ASP.NET Core

**Target Area**: Internal Logic / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting PostMessage Vulnerabilities within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core handles user-supplied data in the context of PostMessage Vulnerabilities.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on PostMessage Vulnerabilities. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 5 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Defacement or unauthorized actions performed on behalf of the user.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 212. Client-Side - CSRF via CORS Bypass targeting Symfony (PHP)

**Target Area**: Internal Logic / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting CSRF via CORS Bypass within a Authenticated endpoint acting as a standard user. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Symfony (PHP) handles user-supplied data in the context of CSRF via CORS Bypass.</step>
    <step>Analyze the context: Authenticated endpoint acting as a standard user. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on CSRF via CORS Bypass. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 8 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Defacement or unauthorized actions performed on behalf of the user.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 213. Client-Side - DOM-based XSS targeting FastAPI

**Target Area**: Internal Logic / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting DOM-based XSS within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how FastAPI handles user-supplied data in the context of DOM-based XSS.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on DOM-based XSS. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 5 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Defacement or unauthorized actions performed on behalf of the user.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 214. Client-Side - DOM-based XSS targeting Ruby on Rails

**Target Area**: Internal Logic / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting DOM-based XSS within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails handles user-supplied data in the context of DOM-based XSS.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on DOM-based XSS. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 4 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Defacement or unauthorized actions performed on behalf of the user.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 215. Client-Side - CSRF via CORS Bypass targeting Flask (Python)

**Target Area**: Internal Logic / Flask (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting CSRF via CORS Bypass within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Flask (Python) handles user-supplied data in the context of CSRF via CORS Bypass.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on CSRF via CORS Bypass. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 8 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Defacement or unauthorized actions performed on behalf of the user.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 216. Client-Side - CSRF via CORS Bypass targeting Ruby on Rails

**Target Area**: Internal Logic / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting CSRF via CORS Bypass within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails handles user-supplied data in the context of CSRF via CORS Bypass.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on CSRF via CORS Bypass. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 4 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Session hijacking and account takeover.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 217. Client-Side - Reflected XSS targeting Symfony (PHP)

**Target Area**: Internal Logic / Symfony (PHP) architecture
**Description**: An extensive operational guide for identifying and exploiting Reflected XSS within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Symfony (PHP) handles user-supplied data in the context of Reflected XSS.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Reflected XSS. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 5 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Defacement or unauthorized actions performed on behalf of the user.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 218. Client-Side - Open Redirect targeting Node.js/Express

**Target Area**: Internal Logic / Node.js/Express architecture
**Description**: An extensive operational guide for identifying and exploiting Open Redirect within a Multi-tenant application environment. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Node.js/Express handles user-supplied data in the context of Open Redirect.</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Open Redirect. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 6 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Session hijacking and account takeover.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 219. Client-Side - DOM-based XSS targeting FastAPI

**Target Area**: Internal Logic / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting DOM-based XSS within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how FastAPI handles user-supplied data in the context of DOM-based XSS.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on DOM-based XSS. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 3 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Session hijacking and account takeover.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 220. Client-Side - WebSockets Hijacking targeting Go (Gin)

**Target Area**: Internal Logic / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting WebSockets Hijacking within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Gin) handles user-supplied data in the context of WebSockets Hijacking.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on WebSockets Hijacking. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 3 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Defacement or unauthorized actions performed on behalf of the user.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 221. Client-Side - Open Redirect targeting ASP.NET Core

**Target Area**: Internal Logic / ASP.NET Core architecture
**Description**: An extensive operational guide for identifying and exploiting Open Redirect within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how ASP.NET Core handles user-supplied data in the context of Open Redirect.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Open Redirect. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 6 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Defacement or unauthorized actions performed on behalf of the user.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 222. Client-Side - Blind XSS targeting Ruby on Rails

**Target Area**: Internal Logic / Ruby on Rails architecture
**Description**: An extensive operational guide for identifying and exploiting Blind XSS within a Unauthenticated endpoint exposed to the public. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Ruby on Rails handles user-supplied data in the context of Blind XSS.</step>
    <step>Analyze the context: Unauthenticated endpoint exposed to the public. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Blind XSS. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 6 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Session hijacking and account takeover.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 223. Client-Side - Client-Side Path Traversal targeting Go (Gin)

**Target Area**: Internal Logic / Go (Gin) architecture
**Description**: An extensive operational guide for identifying and exploiting Client-Side Path Traversal within a Authenticated endpoint acting as an administrator. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Go (Gin) handles user-supplied data in the context of Client-Side Path Traversal.</step>
    <step>Analyze the context: Authenticated endpoint acting as an administrator. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Client-Side Path Traversal. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 8 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Defacement or unauthorized actions performed on behalf of the user.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 224. Client-Side - WebSockets Hijacking targeting GraphQL (Relay)

**Target Area**: Internal Logic / GraphQL (Relay) architecture
**Description**: An extensive operational guide for identifying and exploiting WebSockets Hijacking within a Internal microservice communicating via proxy. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how GraphQL (Relay) handles user-supplied data in the context of WebSockets Hijacking.</step>
    <step>Analyze the context: Internal microservice communicating via proxy. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on WebSockets Hijacking. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 4 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Session hijacking and account takeover.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 225. Client-Side - Prototype Pollution targeting Rust (Actix)

**Target Area**: Internal Logic / Rust (Actix) architecture
**Description**: An extensive operational guide for identifying and exploiting Prototype Pollution within a Multi-tenant application environment. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Rust (Actix) handles user-supplied data in the context of Prototype Pollution.</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Prototype Pollution. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 3 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Defacement or unauthorized actions performed on behalf of the user.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 226. Client-Side - Clickjacking targeting Supabase

**Target Area**: Internal Logic / Supabase architecture
**Description**: An extensive operational guide for identifying and exploiting Clickjacking within a Mobile application backend API. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Supabase handles user-supplied data in the context of Clickjacking.</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Clickjacking. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 8 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Defacement or unauthorized actions performed on behalf of the user.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 227. Client-Side - Client-Side Path Traversal targeting Rust (Actix)

**Target Area**: Internal Logic / Rust (Actix) architecture
**Description**: An extensive operational guide for identifying and exploiting Client-Side Path Traversal within a Legacy API endpoint slated for deprecation. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Rust (Actix) handles user-supplied data in the context of Client-Side Path Traversal.</step>
    <step>Analyze the context: Legacy API endpoint slated for deprecation. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Client-Side Path Traversal. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 6 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Defacement or unauthorized actions performed on behalf of the user.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 228. Client-Side - CSRF via CORS Bypass targeting Django (Python)

**Target Area**: Internal Logic / Django (Python) architecture
**Description**: An extensive operational guide for identifying and exploiting CSRF via CORS Bypass within a Mobile application backend API. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how Django (Python) handles user-supplied data in the context of CSRF via CORS Bypass.</step>
    <step>Analyze the context: Mobile application backend API. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on CSRF via CORS Bypass. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 6 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Session hijacking and account takeover.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

### 229. Client-Side - Open Redirect targeting FastAPI

**Target Area**: Internal Logic / FastAPI architecture
**Description**: An extensive operational guide for identifying and exploiting Open Redirect within a Multi-tenant application environment. This module is built for rigorous edge-case testing and deep analysis.

```xml
<skill_module>
  <task_description>
    Execute the bug bounty analysis based on the overarching description and target area defined above.
  </task_description>
  <execution_steps>
    <step>Deconstruct the input data. Specifically observe how FastAPI handles user-supplied data in the context of Open Redirect.</step>
    <step>Analyze the context: Multi-tenant application environment. Evaluate if the input is directly reflected, evaluated, or passed to an insecure deserializer/parser.</step>
    <step>Formulate hypotheses focused on Open Redirect. Map out exactly how the vulnerability could be triggered, bypassing any apparent frontend validation.</step>
    <step>Generate 3 specific, weaponized payloads designed to exploit the logic flow, utilizing advanced evasion techniques if necessary.</step>
    <step>Evaluate the potential business impact. If the exploit is successful, assess if it leads to: Session hijacking and account takeover.</step>
  </execution_steps>
  <input_data>
    [PASTE RAW HTTP REQUEST / RESPONSE / CODE SNIPPET HERE. DO NOT FORMAT.]
  </input_data>
</skill_module>
```

