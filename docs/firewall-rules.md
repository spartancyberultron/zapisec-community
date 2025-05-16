# 🔥 Application Firewall Rules

The Application Firewall allows users to apply domain-specific security policies using custom and managed rule sets. Below are the details of rule types, supported fields, and examples.

---

## 🧩 Rule Types

### 1. Custom Rules

Custom rules are user-defined rules tailored to protect specific application logic and attack surfaces.

#### Supported Match Fields:
| Field         | Description                                     |
|---------------|-------------------------------------------------|
| `ip`          | Source IP address (can use CIDR notation)       |
| `country`     | Country code of the request origin              |
| `asn`         | Autonomous System Number of the request         |
| `method`      | HTTP method (`GET`, `POST`, etc.)               |
| `path`        | Request path or URI (supports wildcards)        |
| `host`        | Request host (domain)                           |
| `user_agent`  | Full or partial user-agent string               |
| `cookie`      | Match cookies in requests                       |
| `header`      | Custom or default headers (e.g., `X-API-Key`)   |

#### Supported Actions:
- `allow` — Let the request through
- `block` — Deny the request
- `challenge` — Trigger CAPTCHA or other verification
- `log` — Log the request without taking action

#### Example Custom Rule
```json
{
  "rule_id": "rule-001",
  "domain": "example.com",
  "match": {
    "method": "POST",
    "path": "/admin",
    "country": "CN"
  },
  "action": "block",
  "description": "Block admin POSTs from China"
}
