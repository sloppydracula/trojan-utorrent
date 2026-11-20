# Malware Analysis Report: uTorrent Pro Patch (HackTool / Trojan)   
#discovery
#execution
#spyware
#trojan
#upx
#adware
#defense_evasion
#persistence
#stealer
#malware

3ec610acd74ffc30e54aee5970132482b0975172016010cb596aaceed2167750 - uTorrent Pro 3.6.0 Build 47224 Incl Patch - KhanPC.zip


0fef3ad596aea60227f82be01af84a4cfc0c206adc3f4a80c3a825a165fa8269  - Patch_UT.47224.exe
                                https://www.techspot.com/
        

## 📌 General Information
https://fotovssylku.ru/i/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA-%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0-2026-11-20-205144.nt1nP
*   **Target Archive:** `uTorrent Pro 3.6.0 Build 47224 Incl Patch - KhanPC.zip`
*   **Target File:** `Patch/Patch.exe` (also known as `Patch_UT_47224.exe`)
*   **Archive Size:** 27.8 MB
*   **File Size:** 24.5 MB
*   **Archive SHA256:** `3ec610acd74ffc30e54aee5970132482b0975172016010cb596aaceed2167750`
*   **Executable SHA256:** `0fef3ad596aea60227f82be01af84a4cfc0c206adc3f4a80c3a825a165fa8269`
*   **Overall Score (Sandbox):** 10/10 (Critical)

## 🚨 VirusTotal & Sandbox Analysis
https://fotovssylku.ru/i/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA-%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0-2026-11-20-205047.ntEgk
https://fotovssylku.ru/i/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA-%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0-2026-11-20-205029.ntaCR
This sample is a classic example of a **software crack/patch** that contains hidden malware. 

### Detection Rates
*   **Archive Detection:** 30/68 security vendors flagged this file as malicious.
*   **Executable Detection:** 42/69 security vendors flagged the extracted `Patch.exe` as malicious.
*   **Popular Threat Labels:** `hacktool`, `trojan`, `riskware`.
https://fotovssylku.ru/i/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA-%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0-2026-11-20-205029.ntiTu
### Threat Tags (Sandbox)
*   **HACKTOOL** (Crack/Patch tool)
*   **TROJAN**
*   **STEALER**
*   **SPYWARE**
*   **PERSISTENCE**
*   **DEFENSE_EVASION**
https://fotovssylku.ru/i/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA-%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0-2026-11-20-205006.ntz41
## ⚠️ Critical Behavioral Findings

While the archive is disguised as a "Pro" patch for uTorrent, the sandbox revealed severe malicious behaviors:
*   **Modifies WinLogon for persistence:** The malware alters core Windows registry keys to ensure it automatically runs every time the system boots, making it difficult to remove.
*   **Executes dropped files:** It extracts and runs hidden payloads.
*   **Steals data:** Tagged as a Stealer and Spyware, indicating it targets user data.

## Conclusion
The file **`Patch_UT_47224.exe`** is **highly malicious**. Threat actors often bundle malware, stealers, and backdoors into popular software cracks (like uTorrent Pro). The "Persistence" mechanism (modifying WinLogon) indicates that the malware wants to establish a deep root in the system.

**Recommendations:**
1. **Never** run software patches or cracks from untrusted sources.
2. Purchase legitimate software licenses to avoid exposing systems to Trojans.
3. If this file was executed, the system should be considered compromised and requires immediate OS reinstallation.
