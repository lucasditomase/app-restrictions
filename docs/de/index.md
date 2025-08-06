# Eine Bedrohungsanalyse des Sideloadings  

## 📌 Zentrale Erkenntnisse  

- Der starke Datenschutz und die Sicherheit des iPhones sind entscheidend aufgrund der sensiblen Natur der darauf gespeicherten persönlichen Daten.  
- Sideloading (Installation von Apps außerhalb des App Stores) stellt große Bedrohungen für dieses Sicherheitsmodell dar.  
- Malware ist auf Plattformen, die Sideloading unterstützen, weitaus verbreiteter (z.B. hat Android 15–47x mehr Infektionen als iOS).  
- App Store-Überprüfungsprozesse und Systemschutzmaßnahmen reduzieren das Malware-Risiko erheblich.  

## 📉 Risiken des Sideloadings  

- **Erhöhte Malware**: Sideloading umgeht App Store-Überprüfungen und ermöglicht Adware, Spyware, Trojaner usw.  
- **Social Engineering**: Benutzer können dazu verleitet werden, gefälschte Apps zu installieren, die legitime nachahmen.  
- **Reduzierte Benutzerkontrolle**: Sidegeladene Apps können Kindersicherungen, App-Tracking-Transparenz oder Berechtigungsabfragen umgehen.  
- **Geschwächte Plattformsicherheit**: Könnte die Offenlegung proprietärer APIs oder OS-Interna erfordern und damit die Kernsicherheitsarchitektur von iOS bedrohen.  
- **Negative Externalitäten**: Selbst Benutzer, die Sideloading vermeiden, sind gefährdet—z.B. durch Unternehmenszwang, Nachahmung gefälschter App Stores oder geschäftliche/berufliche Bedürfnisse.  

## 🔍 Malware-Beispiele  

- **Adware** (HiddenAds, CopyCat): Überschwemmt Benutzer mit aggressiven oder betrügerischen Anzeigen.  
- **Ransomware** (CryCryptor, MalLocker.B): Verschlüsselt Gerätedaten und fordert Lösegeld.  
- **Spyware** (SpyNote, HelloSpy): Überwacht Aktivitäten, erfasst private Daten, wird bei der Überwachung von Intimpartnern eingesetzt.  
- **Banking-Trojaner** (BlackRock, Anubis): Stiehlt Anmeldedaten über Overlay-Angriffe, umgeht sogar 2FA.  

## 🧠 Sicherheitsexperten-Rat  

> "Installieren Sie Apps nur aus offiziellen App Stores." — Europol  
> "Vermeiden Sie Sideloading auf BYOD-Geräten." — US-Ministerium für Heimatschutz  
> "Apps von Drittanbietern stellen eine ernsthafte Sicherheitsbedrohung dar." — Interpol/Kaspersky  

## 🚫 Apples Position  

- Apple erlaubt bereits begrenztes Unternehmens-Sideloading mit strengen Kontrollen.  
- Früherer Missbrauch (z.B. Facebook Research-App, Goontact-Spyware) zeigt, wie schnell diese Mechanismen missbraucht werden.  
- Breites Sideloading würde dieses Risiko drastisch verstärken.  

## 📎 Fazit  

Sideloading führt zu weitreichenden Risiken für Benutzer, Entwickler und Organisationen. Apple behauptet, dass es das Plattformvertrauen beeinträchtigen, Angriffsflächen vergrößern und den Datenschutz für alle Benutzer verringern würde—nicht nur für diejenigen, die Sideloading nutzen.  

---  

## 📄 Originaldokumente  

- 🧷 *Building a Trusted Ecosystem for Millions of Apps* (Juni 2021)  
  ↪️ [apple.com (offiziell)](https://www.apple.com/privacy/docs/Building_a_Trusted_Ecosystem_for_Millions_of_Apps.pdf)  
  ↪️ [github.com/lucasditomase (Backup)](https://github.com/lucasditomase/app-restrictions/blob/main/summary.pdf)  

- 🧷 *A Threat Analysis of Sideloading* (Oktober 2021)  
  ↪️ [apple.com (offiziell)](https://www.apple.com/privacy/docs/Building_a_Trusted_Ecosystem_for_Millions_of_Apps_A_Threat_Analysis_of_Sideloading.pdf)  
  ↪️ [github.com/lucasditomase (Backup)](https://github.com/lucasditomase/app-restrictions/blob/main/threat-analysis.pdf)  
