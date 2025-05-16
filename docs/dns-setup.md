# 🌐 DNS Setup & Management

Our platform includes integrated DNS management, allowing you to configure DNS records for your protected domains.

---

## 🔧 Features

- Add and manage standard DNS records:
  - A / AAAA
  - CNAME
  - MX
  - TXT
  - NS
- Subdomain creation and management
- TTL configuration
- DNS record propagation status
- Origin server obfuscation to hide your infrastructure

---

## 📝 Example DNS Record

```json
{
  "domain": "example.com",
  "type": "A",
  "name": "www",
  "value": "203.0.113.42",
  "ttl": 300
}
