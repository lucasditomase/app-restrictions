![Banner](../assets/banner.png)

# Analiza zagrożeń związanych z sideloadingiem

## Kluczowe informacje

- Silna prywatność i bezpieczeństwo iPhone’a są kluczowe ze względu na wrażliwy charakter przechowywanych danych osobowych.
- Sideloading (instalowanie aplikacji spoza App Store) stanowi poważne zagrożenie dla tego modelu bezpieczeństwa.
- Złośliwe oprogramowanie jest znacznie bardziej powszechne na platformach, które wspierają sideloading (np. Android ma 15–47 razy więcej infekcji niż iOS).
- Procesy weryfikacji App Store i zabezpieczenia systemowe znacząco zmniejszają ryzyko infekcji.

## Zagrożenia związane z sideloadingiem

- **Więcej złośliwego oprogramowania**: Sideloading omija kontrole App Store, umożliwiając instalację adware, spyware, trojanów itp.
- **Inżynieria społeczna**: Użytkownicy mogą zostać oszukani do instalacji fałszywych aplikacji, które naśladują legalne.
- **Ograniczona kontrola użytkownika**: Aplikacje sideloaded mogą omijać kontrolę rodzicielską, App Tracking Transparency lub prośby o uprawnienia.
- **Osłabienie bezpieczeństwa platformy**: Może wymagać ujawnienia zastrzeżonych API lub wewnętrznych mechanizmów systemu operacyjnego, zagrażając podstawowej architekturze bezpieczeństwa iOS.
- **Negatywne skutki zewnętrzne**: Nawet użytkownicy, którzy nie korzystają z sideloadingu, są narażeni — np. poprzez przymus korporacyjny, fałszywe sklepy z aplikacjami lub wymagania zawodowe.

## Przykłady złośliwego oprogramowania

- **Adware** (HiddenAds, CopyCat): Zasypuje użytkowników agresywnymi lub oszukańczymi reklamami.
- **Ransomware** (CryCryptor, MalLocker.B): Szyfruje dane urządzenia i żąda okupu.
- **Spyware** (SpyNote, HelloSpy): Monitoruje aktywność, przechwytuje dane osobowe, wykorzystywane do inwigilacji partnerów.
- **Trojany bankowe** (BlackRock, Anubis): Kradną dane logowania za pomocą ataków nakładkowych, omijają nawet 2FA.

## Rady ekspertów ds. bezpieczeństwa

> „Instaluj aplikacje tylko z oficjalnych sklepów.” — Europol
> „Unikaj sideloadingu na urządzeniach BYOD.” — Departament Bezpieczeństwa Wewnętrznego USA
> „Aplikacje firm trzecich stanowią poważne zagrożenie bezpieczeństwa.” — Interpol/Kaspersky

## Stanowisko Apple

- Apple już pozwala na ograniczony sideloading korporacyjny z rygorystycznymi kontrolami.
- Wcześniejsze nadużycia (np. aplikacja Facebook Research, spyware Goontact) pokazują, jak szybko te mechanizmy mogą zostać wykorzystane.
- Powszechny sideloading drastycznie zwiększyłby to ryzyko.

## Wnioski

Sideloading niesie ze sobą szerokie ryzyka dla użytkowników, deweloperów i organizacji. Apple twierdzi, że podważyłoby to zaufanie do platformy, zwiększyło powierzchnię ataku i osłabiło ochronę prywatności dla wszystkich użytkowników — nie tylko tych, którzy korzystają z sideloadingu.

---

## Dokumenty źródłowe

- *Budowanie zaufanego ekosystemu dla milionów aplikacji* (czerwiec 2021)
  [apple.com (oficjalna)](https://www.apple.com/privacy/docs/Building_a_Trusted_Ecosystem_for_Millions_of_Apps.pdf)
  [github.com/lucasditomase (kopia)](https://github.com/lucasditomase/app-restrictions/blob/main/summary.pdf)

- *Analiza zagrożeń związanych z sideloadingiem* (październik 2021)
  [apple.com (oficjalna)](https://www.apple.com/privacy/docs/Building_a_Trusted_Ecosystem_for_Millions_of_Apps_A_Threat_Analysis_of_Sideloading.pdf)
  [github.com/lucasditomase (kopia)](https://github.com/lucasditomase/app-restrictions/blob/main/threat-analysis.pdf)
