# CYBER GRID SENTINEL 🛡️

> NEURAL PAY SCANNER · SECURITY PROTOCOL V4.0.2 · ACTIVE

## The Problem
UPI QR and link scams are costing Indians crores every year. Default scanners just redirect to payment apps. They never analyze *who* you’re paying, *what* the payload is, or *if* the link is safe.

Users enter the Grid blind.

## Our Solution: Neural Pay Scanner
Cyber Grid Sentinel is a TRON-themed security protocol that runs deep analysis on UPI URLs and payment links before you pay. The system executes 4 core security checks and gives a clear RISK INDEX.

### 4 Core Security Checks

| Module | Function | Stops This Scam |
| --- | --- | --- |
| **ID / VPA VERIFY** | Decodes and validates UPI ID recipient | Fake merchant VPA like `fake@upi` |
| **ENTITY MATCH** | Cross-checks displayed name vs VPA owner | QR says “Amazon” but VPA belongs to scammer |
| **PAYLOAD RISK** | Scans for pre-filled amounts & malicious params | ₹15000 auto-filled “refund” QRs |
| **LINK INTEGRITY** | Flags HTTP, unknown, or suspicious URLs | Phishing links masked as UPI |

**Flag Legend:** `SECURE` `CAUTION` `THREAT`

## Demo
![Cyber Grid Sentinel UI](https://github.com/kadam45-arch/Tron-CyberGridSentinel-/blob/main/Tron.png?raw=true)

**Live Link:** `[Add your GitHub Pages link here]`

## System Features
- **System Status**: NODE: ONLINE · SHIELD: ACTIVE · THREAT: DYNAMIC
- **Protocol Checks**: UPI://PAY ✓ · HTTPS:// ✓ · HTTP:// ✗ · UNKNOWN ✗
- **Scan Counter**: Tracks TOTAL SCANS
- **Activity Log**: Real-time system feed of all analysis
- **Risk Index**: Final threat score before payment

## Test Cases

**SAFE:**

**SUSPICIOUS:
**SUSPICIOUS:**upi://pay?pa=unknown@upi&pn=Unknown&am=6000
bank-login.com
verify-account.com
secure-update.netjavascript
**DANGEROUS:**secure@fake-bank.com
login-secure-update@fraud.com
paytm-secure-login@hack.ru
upi://pay?pa=fake@upi&pn=Amazon&am=15000javascript
**EXAMPLE CASE:**secure-login-verify-update-bank-account-user-confirmation.comjavascript
## How to Run
1. Open terminal in this folder
2. Run: `pip install flask`
3. Run: `python app.py`
4. Open: `http://127.0.0.1:5000`

## Tech Stack
HTML5, CSS3, Vanilla JS, Flask, QR-Scanner Library  
Neural Pay Scanner runs locally for privacy. No data leaves your Grid.

## Built For
Jarvis 2.0 – Fighting UPI fraud with gamified security protocols.

---
**Build:** v4.0.2  
**Team:** TRON  
**Grid Runner:** kadam45-arch  
**Mission Status:** ONLINE  
END OF LINE.
