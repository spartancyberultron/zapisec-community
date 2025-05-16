# 🛡️ DDoS Protection

Our DDoS mitigation engine prevents large-scale attacks that aim to exhaust your application's bandwidth, CPU, or memory.

---

## ⚙️ Defense Capabilities

- Automated detection of:
  - SYN floods
  - HTTP floods (GET/POST)
  - Layer 7 attacks (e.g., login brute-force)
  - Botnet-based traffic spikes
- Real-time rule application
- High-performance edge filtering

---

## 🧩 Filter Criteria

You can block or challenge traffic based on:

| Field        | Description                           |
|--------------|----------------------------------------|
| `ip`         | Exact IP or IP range (CIDR)            |
| `country`    | Block traffic from specific countries  |
| `asn`        | Block traffic from entire ISPs/networks|
| `method`     | HTTP method (e.g., POST/DELETE)        |
| `path`       | Specific route like `/login`           |
| `host`       | Domain being accessed                  |
| `user_agent` | Malicious or unknown browsers/clients  |
| `cookie`     | Suspicious cookie pattern              |
| `header`     | Custom header indicators               |

---

## 🚨 Mitigation Actions

- `block`: Instantly drop malicious requests
- `challenge`: Force CAPTCHA or verification
- `log`: Pass traffic but log for review

---

## 🔒 Example DDoS Rule

```json
{
  "domain": "example.com",
  "match": {
    "country": "RU",
    "method": "POST",
    "path": "/auth"
  },
  "action": "challenge",
  "description": "Challenge Russian POSTs to /auth"
}
