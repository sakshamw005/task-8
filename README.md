# Task 8: Test and Analyze VPN Usage

## Objective
Use a free VPN service to observe how VPNs work, verify encryption, IP masking, and analyze benefits & limitations.

---

## Step-by-Step Guide & Observations

### 1. Choose a Reputable Free VPN Service
- **Selected VPN:** ProtonVPN  
- **Reason:** Open-source, based in Switzerland, strong privacy policy.

### 2. Download and Install the VPN Client
- Downloaded from: [https://protonvpn.com](https://protonvpn.com)
- Installed on: Windows

### 3. Connect to a VPN Server
- **Location Connected:** Japan (Free Server)
- Chose this for lower latency and better performance.

### 4. Verify IP Address Has Changed
- **Before VPN:** `183.82.162.11`  
- **After VPN:** `212.102.51.79` (Japan)
- **Tool Used:** [https://whatismyipaddress.com](https://whatismyipaddress.com)

### 5. Browse a Website to Confirm Traffic is Encrypted
- Visited Reddit, GitHub, and Instagram.
- Confirmed encrypted traffic via HTTPS and VPN tunnel.
- Noted: Instagram accounts restricted in India (e.g., Pakistani actors) became visible after VPN activation.

### 6. Disconnect VPN and Compare Speed/IP
- **After Disconnecting:**
  - IP reverted to local IP.
  - Browsing speed improved slightly.
  - Speed tested using: [https://speedtest.net](https://speedtest.net)

### 7. Researched VPN Encryption and Privacy Features
- **Encryption:** AES-256 with 4096-bit RSA key exchange.
- **Protocols:** OpenVPN and WireGuard
- **Privacy Features:** No logs, DNS leak protection, Kill switch enabled

---

## 📋 Summary

### Benefits:
- IP masking and anonymity
- Traffic encryption
- Bypasses geo-restrictions (e.g., content blocked in India)
- Safe browsing on public Wi-Fi

### Limitations:
- Slower internet speeds due to routing
- Limited features in free plans (fewer servers)
- Trust required in VPN provider


## 🏁 Outcome
Successfully tested ProtonVPN. Understood how VPNs enhance privacy, how encryption works, and identified both strengths and weaknesses in real-world usage.
