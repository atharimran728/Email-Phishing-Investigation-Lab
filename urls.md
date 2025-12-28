# URL Analysis

## Extracted URLs

### 1. https://t.co/eYVtqVunRC
- **Type:** URL shortener (Twitter/X)
- **Purpose:** Obfuscation
- **Risk:** High — destination hidden from user

Shortened URLs are commonly used in phishing to bypass user scrutiny and email filtering.

---

### 2. http://bsq2.firiri.shop/cGNjTnA0S1BmODB4K2U0...
- **Domain:** firiri.shop
- **Protocol:** HTTP (no TLS)
- **Characteristics:**
  - Randomized path
  - Likely tracking + redirect endpoint
  - Low-trust TLD

---

### 3. Unsubscribe & Tracking URLs
- Multiple encoded paths under `firiri.shop`
- Invisible tracking pixel present

---

## Behavioral Indicators
- Use of **URL shortener inside marketing-style email**
- Redirect chains instead of direct destination
- Insecure HTTP endpoints
- Encoded parameters (likely user tracking / affiliate fraud)

---

## URL Verdict
All URLs exhibit **deception and obfuscation techniques** consistent with:
- Scam campaigns
- Affiliate fraud
- Potential credential harvesting

No legitimate brand would route users this way.
