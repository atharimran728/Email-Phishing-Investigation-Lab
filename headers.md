# Email Header Analysis

## Basic Metadata
- **Subject:** Individuelle Prognose für schnellen Gewichtsverlust
- **From Display Name:** Magisches Schlankheitssystem
- **From Address:** otto-newsletter@newsletter.otto.de
- **Reply-To:** reply_to@winner-win.art
- **Return-Path:** return@winner-win.art
- **Date:** Thu, 03 Aug 2023 04:14:33 +0200

---

## Authentication Results
- **SPF:** SoftFail  
  - Sending IP `80.96.157.90` is not authorized for `winner-win.art`
- **DKIM:** None (message not signed)
- **DMARC:** Fail (policy = none)

**Conclusion:** Sender failed basic email authentication checks. This strongly indicates spoofing or unauthorized mailing infrastructure.

---

## Sender Infrastructure
- **Sending Hostname:** qktfxthukmwfnksijbkrjxkzhstbswa.whstr8
- **Sender IP:** 80.96.157.90
- **ASN / Hosting:** Likely low-reputation bulk email infrastructure

Hostname is random-generated and does not align with the claimed brand (OTTO).

---

## Header Anomalies
- Mismatch between `From` domain and `Return-Path`
- `Reply-To` points to unrelated domain (`winner-win.art`)
- DKIM completely absent despite impersonating a major brand
- High spam confidence:
  - **SCL:** 7
  - **BCL:** 8

---

## Header Verdict
This email is **not legitimately sent by OTTO**.  
Authentication failures + infrastructure mismatch confirm **brand impersonation phishing / scam email**.
