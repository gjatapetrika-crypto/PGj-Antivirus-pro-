# PGj Antivirus Pro — test prototype

Bilingual Albanian/English native Android starter project.

## Included
- Dark security dashboard and menu.
- Basic heuristic review of launcher-visible apps based on requested sensitive permissions.
- User-selected file read and SHA-256 hash calculation.
- In-session scan history.

## Not a complete antivirus
This prototype does **not** include a malware-signature database, cloud reputation service, real-time protection, quarantine, automatic malware removal, or a threat-definition update service. Permission heuristics are not proof of malware. The history is currently stored in memory only. Do not market this version as a complete antivirus.

## Build requirements
- Android SDK 35
- JDK 17
- Compatible Android Gradle Plugin / Gradle
- Build task: `:app:assembleDebug`

Package: `com.pgj.antivirus`
Version: `0.1.0-test`

Before Google Play publication: test on devices and Android versions, implement and validate threat detection, provide a privacy policy, review Data safety and advertising disclosures, and comply with current Play policies.
