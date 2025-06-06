<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://zapisec.ai/wp-content/uploads/2023/09/Logo-ZAPISEC-removebg-preview-e1743969524490.png">
  <source media="(prefers-color-scheme: light)" srcset="https://zapisec.ai/wp-content/uploads/2023/09/Logo-ZAPISEC-removebg-preview-e1743969524490.png">
  <img src="https://zapisec.ai/wp-content/uploads/2023/09/Logo-ZAPISEC-removebg-preview-e1743969524490.png">
</picture>

# 🔐 ZAPISEC: AI-Application Firewall & API Security Monitoring Platform

Welcome to **[ZAPISEC](https://zapisec.ai/)** – a next-generation, SaaS-based **Application Firewall (AF)** and **API Security Monitoring** platform crafted by **[Cyberultron Consulting Private Limited](https://cyberultron.com/)**. ZAPISEC is designed to proactively safeguard modern web applications, APIs, and cloud-native services against an ever-evolving landscape of cyber threats. Built with scalability and performance in mind, it leverages advanced rule engines, AI-powered anomaly detection, and managed prevention strategies to deliver enterprise-grade security through a streamlined platform.

ZAPISEC combines the capabilities of traditional firewalls with deep API intelligence, supporting real-time traffic inspection, threat pattern analysis, and behavior-based blocking. Whether defending against OWASP Top 10 vulnerabilities, bot attacks, DDoS floods, or LLM-based prompt injections, ZAPISEC ensures your digital assets remain secure with minimal latency. The platform features a powerful 7000+ rule engine, DNS-level protection, bot management, and continuous AI learning for zero-day detection and mitigation.

Ideal for developers, DevSecOps teams, and enterprise security leaders, ZAPISEC provides a centralized, cloud-native interface for configuring rules, analyzing threats, and integrating with CI/CD pipelines. Its support for REST, GraphQL, and LLM APIs makes it a future-ready defense layer for modern architectures. ZAPISEC isn’t just a security tool — it's a mission-critical partner in building resilient and compliant digital ecosystems.

---

## 🔥 What ZAPISEC Offers

| Feature                        | Description                                                                                      |
|-------------------------------|--------------------------------------------------------------------------------------------------|
| 🛡️ **Application Firewall**     | AI-powered with **7000+ rules** to detect and block injection attacks, XSS, zero-day exploits, and more.|
| 🌐 **DDoS Mitigation**          | Comprehensive Layer 3, 4, and 7 protection using real-time traffic analysis, rate limiting, IP reputation, and geo-fencing. |
| 🤖 **Bot Protection**           | Sophisticated bot fingerprinting & behavior analysis — allowing good bots while blocking scrapers, credential stuffers, and automation attacks. |
| 📊 **Anomaly Detection**        | AI-driven engines that detect suspicious API usage, traffic anomalies, and emerging threats proactively. |

---

## 💡 About ZAPISEC

**ZAPISEC** is designed to secure your web applications, APIs, and DNS infrastructure against today’s most sophisticated attacks, including:

- OWASP Top 10 vulnerabilities  
- Malicious bot traffic  
- Volumetric and application-layer DDoS attacks  
- AI-identified behavioral anomalies

### Key Security Modules

#### Application Firewall
Protect your infrastructure with customizable, behavior-based rulesets that adapt to evolving threats — blocking SQL injections, cross-site scripting, and unknown zero-day exploits.

#### Bot Protection
Maintain control over automated traffic by differentiating between trusted crawlers (Google, Bing, etc.) and malicious bots with dynamic scoring and real-time mitigation.

#### DDoS Management
Defend against large-scale attacks at all layers with granular traffic control, IP reputation insights, and geo-fencing to keep your services available and responsive.

#### Anomaly Detection
Harness AI to spot unusual patterns and suspicious API activity early — empowering your security team to act before threats escalate.

---

## 🧩 Control & Visibility

ZAPISEC offers your security teams complete command with:

- **Intuitive Rule Builders** for granular firewall customization  
- **Real-Time Traffic Dashboards** with spike alerts and detailed analytics  
- **Rate Limiting, Geo-Blocking & Session Management**  
- **Comprehensive API & DNS Protection** using protocol-aware defenses  

All managed through a centralized, easy-to-use dashboard that streamlines complex security workflows — making enterprise-grade protection accessible to everyone.

---

## 🚀 Key Features

# 🌐 Application Firewall

The **Application Firewall** is designed to provide robust security for your web applications by filtering, monitoring, and blocking malicious HTTP/S traffic. It comes with an embedded engine of **7,000+ rules**, organized into **customizable**, **managed**, and **rate-limiting** components.

## ✅ Core Components

### 🔒 1. Custom Rules
Define and enforce **domain-specific security logic** using:

- **IP-based filtering** (whitelist/blacklist)
- **Country-based access control**
- **URL path matching**
- **HTTP method restrictions (GET, POST, PUT, DELETE, etc.)**
- **Custom headers validation**
- **Regex-based payload inspection**
- **Time-based access control**

Create and update your rule sets dynamically based on threat intelligence and evolving business requirements.

---

### 📦 2. Managed Prevention Rules (48 Core Rule Books)
Our managed ruleset includes **48 security rulebooks** addressing high-impact threats and compliance standards.

Each rulebook is built on expert-curated rules derived from OWASP, MITRE ATT&CK, and industry intelligence. Examples include:

| Rule Book Category                                       | Description                                                                 |
|----------------------------------------------------------|-----------------------------------------------------------------------------|
| SQL Injection Prevention                                 | Blocks classic and advanced SQLi payloads                                   |
| Cross-site Scripting (XSS) Prevention                    | Detects reflective and stored XSS attacks                                  |
| Remote Code Execution (RCE) Detection                    | Blocks system call and command injection patterns                          |
| Directory Traversal Protection                           | Detects `../` style path traversal attempts                                |
| Admin Path Protection                                    | Secures sensitive admin and backend paths                                  |
| Authentication Bypass Protection                         | Prevents bypass of login/OTP endpoints                                     |
| API Abuse Detection                                      | Limits endpoint flooding, fuzzing, and abuse                               |
| Broken Access Control Rule Group                         | Detects unauthorized access patterns                                       |
| HTTP Protocol Anomaly Detection                          | Flags malformed headers and uncommon request sequences                     |
| Session Hijacking Detection                              | Identifies session token anomalies                                         |
| Bot Behavior Detection                                   | Blocks non-human traffic patterns using heuristics                         |
| Account Takeover (ATO) Prevention                        | Stops credential stuffing and password spraying                           |
| LLM Injection & Prompt Injection Prevention              | Prevents LLM-specific prompt attacks and prompt leakage                    |
| Payload Obfuscation Detection                            | Blocks base64, Unicode, hex-encoded malicious payloads                     |
| File Upload Risk Detection                               | Validates MIME types, file extensions, and embedded scripts                |
| Command Injection Detection                              | Detects `eval()`, `exec()`, `system()`, and shell command payloads         |
| CSRF Protection                                          | Detects forged requests from unknown or unauthorized origins               |
| CVE Signature Matching                                   | Monitors for known vulnerabilities via CVE rule patterns                   |
| Web Shell Upload Prevention                              | Blocks web shell deployment attempts and backdoor installation             |
| LFI/RFI Detection                                        | Flags local and remote file inclusion payloads                             |
| SSRF Protection                                          | Detects server-side request forgery attempts                               |
| NoSQL Injection Detection                                | Blocks MongoDB, Firebase, and other NoSQL attack vectors                   |
| Business Logic Abuse Detection                           | Identifies coupon abuse, gift card fraud, etc.                             |
| Rate Abuse & Pricing Manipulation                        | Detects high-frequency cart/checkout anomalies                            |
| WebSocket Anomaly Detection                              | Scans WebSocket headers and message flows                                  |
| HTTP Method Tampering                                    | Detects use of uncommon or deprecated methods                              |
| XML External Entity (XXE) Detection                      | Detects external entity expansion attempts                                |
| JSON Parser Abuse Detection                              | Blocks malicious input targeting JSON parsers                             |
| URL Encoding Abuse Detection                             | Flags double or mixed encoding for evasion                                |
| L7 DDoS Mitigation Core Rules                            | Blocks Layer 7 application-level DDoS attempts                             |
| CDN Bypass Attempt Detection                             | Detects attempts to bypass reverse proxies/CDNs                           |
| Reflected Parameter Echo Checks                          | Scans for input reflection in responses                                   |
| IP Reputation Enforcement                                | Uses threat intelligence for malicious IP filtering                       |
| Malware URL Pattern Blocking                             | Blocks outbound or inbound malware indicators                             |
| Shadow API Detection                                     | Flags undocumented or deprecated endpoints                                |
| Phishing Site Request Detection                          | Blocks requests resembling phishing site behaviors                        |
| Broken Cryptography Detection                            | Scans for insecure crypto practices in responses                          |
| Authentication Token Misuse Detection                    | Checks for token replay, theft, or injection                              |
| Hidden Parameter Tampering                               | Detects and blocks tampering of hidden or internal form parameters        |
| Application Fingerprinting Prevention                    | Blocks scanning tools and fingerprinting attempts                         |
| Header Injection Detection                               | Detects CRLF injection and header manipulation                           |
| HTTP Smuggling Detection                                 | Detects request splitting/smuggling patterns                             |
| Response Behavior Anomaly Detection                      | Monitors deviation in normal HTTP response sizes and types               |
| Content Spoofing Detection                               | Prevents HTML injection and content mismatch attempts                     |
| Clickjacking Protection                                  | Enforces proper `X-Frame-Options` and behavior analysis                   |
| OAuth/OpenID Misuse Detection                            | Detects misuse or abuse of auth endpoints                                 |
| Browser Exploit Prevention                               | Blocks outdated browser versions and vulnerable UAs                      |
| CSP Bypass & Inline Script Injection Detection           | Flags inline scripts and CSP violation attempts                           |
| Honeypot Triggered Bot Detection                         | Uses decoy forms and fields to flag bots                                  |

> 🔧 *These 48 rulebooks are continuously updated and tuned based on live telemetry, honeypot signals, and zero-day intelligence.*

---

### 🚦 3. Rate Limiting

| Control Mechanism          | Description                                            |
| -------------------------- | ------------------------------------------------------ |
| **IP Address**             | Control requests based on the user's IP address       |
| **Geo-location**           | Control requests based on geographic location         |
| **Request Path**           | Control requests based on the URL path                |
| **User-Agent**             | Control requests based on the user agent (browser)    |
| **Authenticated Session**  | Control requests based on the authenticated session  |

**Actions triggered**: Throttle, Block, CAPTCHA, Redirect, Alert

#### Use cases:

- Prevent brute-force login attacks
- Deter API scraping or enumeration
- Stop rapid abuse of search/product listing

---

## ⚙️ Embedded Rules Engine (7000+ Rules)

| Rule Component                   | Description                                                  |
| --------------------------------- | ------------------------------------------------------------ |
| **Core Rule Groups**              | Pre-defined rule groups targeting common attack patterns     |
| **Managed Rulebooks (48)**        | Managed sets of rules for various security concerns          |
| **Heuristics and Behavior Analyzers** | Identify abnormal request patterns using heuristics          |
| **AI/LLM Prompt Analyzers**       | AI-powered analysis of suspicious prompts and behaviors       |
| **Bot Detection Heuristics**     | Detect bot-like behavior using advanced heuristics           |
| **Malware and CVE Signature Matchers** | Detect known malware and vulnerabilities based on signatures |

Each rule is scored, versioned, and has contextual metadata for:

- Threat classification
- False positive suppression
- Tunable confidence thresholds

---

> ✅ **Deploy as is** or fully **customize rules** for your specific industry (e.g., fintech, healthcare, e-commerce, SaaS).
>  
> 🚀 Built for **low-latency**, **high-throughput**, and **zero-trust environments**.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./others/application_firewall.png">
  <source media="(prefers-color-scheme: light)" srcset="./others/application_firewall.png">
  <img src="./others/application_firewall.png" width="100%">
</picture>

## 🤖 Bot Protection

Bot Protection is a critical security layer designed to distinguish between **good bots** (legitimate, helpful bots) and **bad bots** (malicious or abusive agents). This feature uses **behavioral analysis**, **signature-based detection**, **rate-limiting**, and **challenge-based validation** to control automated access.

---

### ✅ Good Bots

These are bots from trusted sources that are automatically allowed based on user-agent verification, IP reputation, and reverse DNS lookups:

| Category         | Verified Bots                                     | Description                                                                 |
|------------------|---------------------------------------------------|-----------------------------------------------------------------------------|
| **Search Engines** | Googlebot, Bingbot, Yahoo Slurp, DuckDuckBot, YandexBot, BaiduSpider | Official crawlers indexing content for search visibility and ranking.       |
| **Social Networks** | Facebook External Hit, Twitterbot, LinkedInBot   | Bots used to generate link previews and rich media embeds for shared URLs. |
| **Cloud Services** | AWS Health Check, Azure Monitor, GCP AppEngine   | Cloud service bots used for uptime monitoring, diagnostics, or syncs.      |

---

### 🚫 Bad Bots

Bad bots are blocked or challenged using behavior tracking (mouse movement, keyboard emulation), header validation, IP fingerprinting, and known bot signatures.

| Type                        | Examples / Indicators                                 | Description                                                                 |
|-----------------------------|-------------------------------------------------------|-----------------------------------------------------------------------------|
| **Security Violators**     | SQLi scanners, XSS payloads, path fuzzers             | Attempt to exploit vulnerabilities through automated requests.             |
| **Content Scrapers**       | HTTrack, Scrapy, Python-urllib, curl, wget            | Try to copy entire site content or competitive intelligence.               |
| **Bot Emulating Humans**   | Headless Chrome, Puppeteer, Selenium, PhantomJS       | Mimic user behavior using automation to bypass detection.                  |
| **Social Networks (Fake)** | Fake engagement bots on X, Instagram, or Reddit       | Post spam, inflate engagement, or distribute misinformation.               |
| **Suspicious Behavior**    | Irregular intervals, rapid clicks, non-human patterns | Fails browser challenges or exhibits erratic navigational paths.           |
| **Cloud Services (Abuse)** | Abuse from proxy networks like AWS, GCP, Azure        | Used to mask botnet origins or launch attacks at scale.                    |
| **Human Routing Channels** | Residential proxy, mobile proxy, P2P botnets          | Bots routed via real users or infected devices to bypass IP blocks.        |


By deploying Bot Protection, you safeguard your application against **automated abuse**, **credential stuffing**, **data theft**, and **fake traffic**, while ensuring uninterrupted access to beneficial bots.


### 📈 Anomaly Detection

| **Feature**                | **Description**                                                                                                                                       |
|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Real-time Detection**     | Monitors traffic for anomalies such as request spikes, pattern deviations, and behavioral oddities in real-time.                                      |
| **How It Works**            | Utilizes advanced algorithms to continuously analyze data, detect trends, and identify deviations from established patterns.                          |
| **Data Analysis**           | Statistical models and machine learning techniques are employed to evaluate data and define normal traffic patterns.                                   |
| **Anomaly Identification**  | Flags any data point or behavior that deviates significantly from the established norm, potentially indicating errors, fraud, or unusual system behavior. |
| **Custom Thresholds**       | Allows the configuration of specific thresholds to customize detection based on unique requirements, enhancing precision and reducing false positives. |
| **Alerts and Insights**     | Instant alerts are triggered upon detecting an anomaly, along with detailed reports to aid in the investigation and resolution of the issue.             |
| **Actionable Solutions**    | Provides insights for corrective actions, optimization, and prevention of potential risks or damages based on the detected anomaly.                   |

### Anomaly Detection in ZAPISEC

| **Component**               | **Details**                                                                                                                            |
|-----------------------------|-----------------------------------------------------------------------------------------------------------------------------------------|
| **Anomaly Detection Service** | Utilizes advanced algorithms for real-time monitoring and analysis of traffic data.                                                   |
| **Continuous Monitoring**    | Data is continuously evaluated for normal behavior using statistical models and machine learning.                                      |
| **Real-time Alerts**        | Anomalies trigger real-time alerts and detailed reports for investigation.                                                              |
| **Customizable Thresholds** | Enables custom threshold settings for precise anomaly detection tailored to specific requirements.                                      |
| **Actionable Insights**     | Anomalies are accompanied by actionable insights to help mitigate potential risks and optimize system processes.                         |


### 🛡️ DDoS Protection

Defends against L3-L7 DDoS attacks using smart rule logic and filtering.

| **Block or Challenge Based On**               | **Details**                           |
|-----------------------------------------------|-------------------------------------|
| IP Address or Range                            | Blocks or challenges by IP or IP range |
| Geographic Location (Country)                  | Blocks or challenges by country     |
| ASN (Autonomous System Number)                 | Blocks or challenges by ASN          |
| HTTP Method, Path, Host                        | Blocks or challenges by HTTP method, path, or host |
| Headers, Cookies, and User Agent               | Blocks or challenges by headers, cookies, or user agent |

| **Layer**            | **Metrics**                                                                                              |
|----------------------|---------------------------------------------------------------------------------------------------------|
| **Layer 3 (Network)**| Packets Per Second (PPS), Bits Per Second (BPS), ICMP Request Rate (Active Session), IP Fragmentation Rate, Source IP Entropy |
| **Layer 4 (Transport)**| SYN Packet Rate, UDP Packet Rate, Connection Request Rate (Active Session), Retransmission Rate, Port Distribution |
| **Layer 7 (Application)**| HTTP Request Rate, Failed Authentication, Response Time (Latency), Error Rate (SXX HTTP Responses), Bot vs Human Traffic Distribution, DNS Query Rate |


## 🌐 DNS Management

DNS configuration, record management, and propagation monitoring.  
Seamless integration with firewall rules for unified security management.

| Feature                      | Description                                        |
|------------------------------|--------------------------------------------------|
| DNS Records Management        | Manage DNS records efficiently and securely.     |
| NameServers Management        | Configure and monitor authoritative name servers.|
| SSL Encryption               | Enable SSL certificates for secure DNS queries.  |
| CDN Automation from Backend  | Automate Content Delivery Network integration and updates. |

---

## 🧩 Use Cases
- Secure your SaaS or eCommerce platform from automated threats
- Protect APIs from abuse or credential stuffing attacks
- Enable selective bot access for indexing and social engagement
- Monitor and mitigate high-traffic anomalies in real-time
- Manage DNS and firewall rules for multi-domain infrastructure

---
# ZAPISEC - Application Firewall Rules Matrix

Below is a comprehensive comparison of feature availability across different ZAPISEC editions.

| Firewall Rule Group                                                                 | Community | Basic | Premium | Enterprise |
|--------------------------------------------------------------------------------------|:---------:|:-----:|:-------:|:----------:|
| Core Fraud Prevention Framework for Account Creation                                 | ✅        | ✅    | ✅      | ✅         |
| Bot Detection & Blocking Core Rules                                                  | ✅        | ✅    | ✅      | ✅         |
| Account Take Over Prevention Core Rule                                               | ✅        | ✅    | ✅      | ✅         |
| Common Weak Enumeration & CVE Prevention Core Rule Group                             | ✅        | ✅    | ✅      | ✅         |
| Admin Protection Managed Prevention Core Rule Group                                  | ✅        | ✅    | ✅      | ✅         |
| Known Bad Inputs Managed Prevention Core Rule Group                                  | ✅        | ✅    | ✅      | ✅         |
| Linux/Unix Operation Systems Managed Prevention Core Rule Group                      | ✅        | ✅    | ✅      | ✅         |
| Windows Operation Systems Managed Prevention Core Rule Group                         | ✅        | ✅    | ✅      | ✅         |
| IP Reputation/Malicious IP’s Managed Prevention Core Rule Group                      | ✅        | ✅    | ✅      | ✅         |
| Sensitive Files and Folders Managed Prevention Core Rule Group                       | ✅        | ✅    | ✅      | ✅         |
| Outdated Browsers Managed Prevention Core Rule Group                                 | ❌        | ✅    | ✅      | ✅         |
| Backup Files Managed Prevention Core Rule Group                                      | ❌        | ✅    | ✅      | ✅         |
| HTTP Protocol Violation Managed Prevention Core Rule Group                           | ❌        | ✅    | ✅      | ✅         |
| LLM Based Injection/AI Based Injection Prevention Core Rule Group                    | ❌        | ✅    | ✅      | ✅         |
| Prompt Based Injection Prevention Core Rule Group                                    | ❌        | ✅    | ✅      | ✅         |
| Credential Stuffing Prevention Core Rule Group                                       | ❌        | ✅    | ✅      | ✅         |
| Malware and Virus Prevention Group Core Rule Group                                   | ❌        | ✅    | ✅      | ✅         |
| API Abuse Prevention Core Rule Group                                                 | ❌        | ✅    | ✅      | ✅         |
| Zero-Day Exploit Protection Core Rule Group                                          | ❌        | ✅    | ✅      | ✅         |
| Device Fingerprinting Core Rule Group                                                | ❌        | ❌    | ✅      | ✅         |
| Geolocation and IP Reputation Core Rule Group                                        | ❌        | ❌    | ✅      | ✅         |
| Web Shell Detection Core Rule Group                                                  | ❌        | ❌    | ✅      | ✅         |
| Content Security Group Core Rule Group                                               | ❌        | ❌    | ✅      | ✅         |
| Phishing Prevention Core Rule Group                                                  | ❌        | ❌    | ✅      | ✅         |
| Laravel PHP Framework Core Rule Group                                                | ❌        | ❌    | ✅      | ✅         |
| Spring Boot Framework Core Rule Group                                                | ❌        | ❌    | ✅      | ✅         |
| Wordpress Framework Core Rule Group                                                  | ❌        | ❌    | ✅      | ✅         |
| Drupal Framework Core Rule Group                                                     | ❌        | ❌    | ✅      | ✅         |
| Joomla Framework Core Rule Group                                                     | ❌        | ❌    | ✅      | ✅         |
| Magento Framework Core Rule Group                                                    | ❌        | ❌    | ❌      | ✅         |
| Express Node Framework Core Rule Group                                               | ❌        | ❌    | ❌      | ✅         |
| Flask Python Framework Core Rule Group                                               | ❌        | ❌    | ❌      | ✅         |
| SQL Injection Prevention Core Rule Group                                             | ❌        | ❌    | ❌      | ✅         |
| XSS Injection Prevention Core Rule Group                                             | ❌        | ❌    | ❌      | ✅         |
| Command Injection Prevention Core Rule Group                                         | ❌        | ❌    | ❌      | ✅         |
| Open Redirect Prevention Core Rule Group                                             | ❌        | ❌    | ❌      | ✅         |
| XXE Injection Prevention Core Rule Group                                             | ❌        | ❌    | ❌      | ✅         |
| RFI-LFI Injection Prevention Core Rule Group                                         | ❌        | ❌    | ❌      | ✅         |
| ASP.NET Language Prevention Core Rule Group                                          | ❌        | ❌    | ❌      | ✅         |
| Known REST API Exploits Prevention Core Rule Group                                   | ❌        | ❌    | ❌      | ✅         |
| Known GRAPHQL API Exploits Prevention Core Rule Group                                | ❌        | ❌    | ❌      | ✅         |
| Spring MVC Prevention Core Rule Group                                                | ❌        | ❌    | ❌      | ✅         |
| CakePHP Prevention Core Rule Group                                                   | ❌        | ❌    | ❌      | ✅         |
| Kubernetes API Prevention Core Rule Group                                            | ❌        | ❌    | ❌      | ✅         |
| Docker API Prevention Core Rule Group                                                | ❌        | ❌    | ❌      | ✅         |
| AWS API’s Prevention Core Rule Group                                                 | ❌        | ❌    | ❌      | ✅         |
| Azure API’s Prevention Core Rule Group                                               | ❌        | ❌    | ❌      | ✅         |
| GCP API’s Prevention Core Rule Group                                                 | ❌        | ❌    | ❌      | ✅         |

# Application Firewall Rules & Features

This table provides an overview of the features available in different editions of the Application Firewall. The tick marks (✅) indicate availability, while the cross marks (❌) indicate features not available in that edition.

| Feature                                               | <a href="https://github.com/spartancyberultron/zapisec-community/" target="_blank">Community Edition</a> | <a href="https://zapisec.ai/pricing/" target="_blank">Basic Edition</a> | <a href="https://zapisec.ai/pricing/" target="_blank">Premium Plan</a> | <a href="https://zapisec.ai/pricing/" target="_blank">Enterprise Edition</a> |
|-------------------------------------------------------|-------------------|---------------|-----------------|---------------------|
| **Application Firewall**                              | ✅                | ✅            | ✅              | ✅                  |
| **Bot Protection**                                     | ❌                 | ❌             | ✅              | ✅                  |
| **DDoS Mitigation**                                    | ❌                | ❌             | ✅              | ✅                  |
| **Anomaly Detection**                                  | ❌                | ❌            | ❌               | ✅                  |

## Application Firewall Architecture

| Application Firewall Architecture | Anomaly Detection Architecture | DDOS Agent Architecture | BOT Agent Architecture |
|:----------------------------------:|:------------------------------:|:------------------------:|:-----------------------:|
| ![Application Firewall](https://github.com/spartancyberultron/zapisec-community/blob/main/docs/Application-Firewall-Architecture.jpg) | ![Anomaly Detection](https://github.com/spartancyberultron/zapisec-community/blob/main/docs/Anomaly-Detection-Architecture.jpg) | ![DDOS Agent](https://github.com/spartancyberultron/zapisec-community/blob/main/docs/DDOS-Agent-Architecture.png) | ![BOT Agent](https://github.com/spartancyberultron/zapisec-community/blob/main/docs/BOT-Agent-Architecture.png) |


## 📚 Docs & Resources

- 📘 [Platform Features](docs/features.md)
- 🛠️ [Firewall Rules](docs/firewall-rules.md)
- 🚦 [Bot Protection Overview](docs/bot-protection.md)
- 📊 [Anomaly Detection Explained](docs/anomaly-detection.md)
- 🛡️ [DDoS Rule Examples](docs/ddos-protection.md)
- 🌍 [DNS Setup Guide](docs/dns-setup.md)
- 📦 [Sample JSON Configs](docs/examples/)
- 🙋‍♂️ [Support](SUPPORT.md)
- 🔐 [Security Policy](SECURITY.md)
- ❓ [Frequently Asked Questions](community/faq.md)

---

## 💬 Get Involved

We welcome contributions from developers, researchers, and users alike. Here's how to participate:

- 💭 [Start or Join a Discussion](community/discussions.md)  
- 🐞 [Report Bugs](https://github.com/your-org/zapisec/issues/new?template=bug_report.md)
- ✨ [Request Features](https://github.com/your-org/zapisec/issues/new?template=feature_request.md)
- 👨‍💻 [Contribute Code or Docs](CONTRIBUTING.md)
- 📬 Stay updated via [Changelog](community/changelog.md)

---

## 🧑‍🤝‍🧑 Community Guidelines

We are committed to creating a safe and welcoming space for everyone. Please review our [Code of Conduct](.github/CODE_OF_CONDUCT.md) before contributing or engaging.

---

## 🌍 Join the Security Revolution

ZAPISEC is more than a firewall — it's a security ecosystem for the modern web. This community is your gateway to mastering and shaping the future of web defense. Share feedback, suggest improvements, learn from others, and secure the internet — together.

---
