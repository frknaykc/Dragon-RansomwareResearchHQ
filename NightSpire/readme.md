# 💡 NIGHTSPIRE INTEL

## 📅 Overview
- **First Discovered:** March 2025  
- **Victim Count:** ~66 in a short span (very active)  
- **Targeted Countries:** 34 (excluding CIS and China 🇨🇳)  
- **Top Victim:** United States 🇺🇸  
- **Other Heavily Affected Countries:** Taiwan 🇹🇼, Hong Kong 🇭🇰, Egypt 🇪🇬, Spain 🇪🇸, Turkey 🇹🇷  

## 🌐 Infrastructure
- **Data Leak Sites (DLS):**  
  - One Vanity TOR domain  
  - One Non-Vanity TOR mirror  
- **Vanity Domain Tech Stack:** PHP 8.2.12  
- **Non-Vanity Domain Server:** nginx  
- **DDoS Protection:**  
  - Under attack; implemented Anti-DDoS measures  
  - Protected by Cloudflare  
- **Victim Data Exposure:**  
  - Samples displayed on DLS  
  - Data listed for sale to interested parties  
- **Data Storage:** Uses **MEGA** cloud service  
- **Communication Channels:**  
  - Telegram  
  - Session  
  - TOX  
  - Email  

## 🛠 Exploitation & Affiliations
- **Exploited Vulnerability:** CVE-2024-55591 (S-RM Report)  
- **Affiliate Links:** Former affiliates linked to **Rbfs Ransomware** (S-RM Report)  

---

# 🔬 Sample Analysis

- **Encrypted File Extension:** `.nspire`  
- **Compiled With:** Go language  
- **Encryption Techniques:**  
  - AES (via x86 extensions)  
  - RC4 PRGA  
  - Salsa20 / ChaCha  
- **Encoding Methods:**  
  - Base64  
  - XOR  
- **Integrity & Authentication:**  
  - Hashed Message Authentication Code (HMAC)  
- **Hashing Algorithms Used:**  
  - murmur3  
  - FNV  
- **Code Correlation:** Strong similarities found with **Snatch Ransomware**  

---

# 📝 RANSOM NOTE (readme.txt)

- A file named `readme.txt` is dropped **in every directory containing encrypted files**.
- Key highlights from the note:
  - Victim is warned their hotel network is hacked.
  - OneDrive files are also encrypted **without changing extensions**.
  - Decryption is only possible via the attacker's key; third-party tools are discouraged.
  - Communication methods are listed including email, qTox ID, and TOR links.
  - Victim UUID is embedded in the message for reference.

---

# 📞 NIGHTSPIRE CONTACT

- **Email:** `nightspireteam.receiver@onionmail.org`  
- **Session ID:**  
  `057d49830799b1fb3f73d7c6111f67a82322efedd8a04ff08011a38ade05459a02`  
- **TOX:**  
  `3B61CFD6E12D789A439816E1DE08CFDA58D76EB0B26585AA34CDA617C41D5943CDD15DB0B7E6`  
- **Telegram:** `@nightspireteam2025`

---

# 🌐 TOR DOMAINS

- `http://nspiremkiq44zcxjbgvab4mdedyh2pzj5kzbmvftcuqg3mczx3dqogid.onion`  
- `http://a2lyiiaq4n74tlgz4fk3ft4akolapfrzk772dk24iq32cznjsmzpanqd.onion`

---

