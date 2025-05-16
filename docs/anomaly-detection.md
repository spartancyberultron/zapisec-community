---

```markdown
# 📈 Anomaly Detection

Our anomaly detection system monitors traffic behavior and identifies abnormal spikes, patterns, and threats in real time.

---

## 🧠 Detection Capabilities

- Traffic spike detection by:
  - Requests per second/minute/hour
  - IP, Path, or Country
- Behavioral deviations
  - Sudden bursts from new IPs
  - Sharp increase in POST/PUT/DELETE methods
- Protocol or header anomalies

---

## ⚙️ Configuration

No manual setup required. Anomaly detection is **enabled by default** and automatically adapts to your baseline traffic.

You may adjust:
- Sensitivity threshold
- Notification preferences (email/webhook)
- Automated action (`log`, `challenge`, or `block`)

---

## 📊 Response Actions

Once an anomaly is detected:
- Logs are generated with full request context
- Mitigation rule is automatically applied if needed
- Option to challenge or block traffic from anomalous sources

---

## 🛠 Use Cases

- Detect DDoS attempts early
- Identify botnet behavior
- Spot scraping or brute-force spikes
- Flag sudden traffic from a country or ASN
