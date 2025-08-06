![Banner](../assets/banner.png)

# Analisis Ancaman Sideloading

## Wawasan Utama

- Privasi dan keamanan iPhone yang kuat sangat penting karena sifat sensitif dari data pribadi yang disimpan di dalamnya.
- Sideloading (menginstal aplikasi dari luar App Store) menimbulkan ancaman besar bagi model keamanan ini.
- Malware jauh lebih umum pada platform yang mendukung sideloading (misalnya, Android memiliki 15–47x lebih banyak infeksi daripada iOS).
- Proses peninjauan App Store dan perlindungan sistem secara signifikan mengurangi risiko malware.

## Risiko Sideloading

- **Peningkatan Malware**: Sideloading melewati pemeriksaan App Store, memungkinkan adware, spyware, trojan, dll.
- **Rekayasa Sosial**: Pengguna dapat ditipu untuk menginstal aplikasi palsu yang meniru aplikasi asli.
- **Kontrol Pengguna Berkurang**: Aplikasi yang disideload dapat melewati kontrol orang tua, Transparansi Pelacakan Aplikasi, atau permintaan izin.
- **Keamanan Platform Melemah**: Dapat memerlukan pengungkapan API eksklusif atau internal OS, mengancam arsitektur keamanan inti iOS.
- **Dampak Negatif Eksternal**: Bahkan pengguna yang tidak menggunakan sideloading dapat berisiko—misalnya, karena paksaan perusahaan, toko aplikasi palsu, atau kebutuhan pekerjaan.

## Contoh Malware

- **Adware** (HiddenAds, CopyCat): Membanjiri pengguna dengan iklan agresif atau penipuan.
- **Ransomware** (CryCryptor, MalLocker.B): Mengenkripsi data perangkat dan meminta tebusan.
- **Spyware** (SpyNote, HelloSpy): Memantau aktivitas, menangkap data pribadi, digunakan dalam pengawasan pasangan.
- **Trojan Perbankan** (BlackRock, Anubis): Mencuri kredensial melalui serangan overlay, bahkan melewati 2FA.

## Saran Ahli Keamanan

> "Hanya instal aplikasi dari toko aplikasi resmi." — Europol
> "Hindari sideloading pada perangkat BYOD." — Departemen Keamanan Dalam Negeri AS
> "Aplikasi pihak ketiga menimbulkan ancaman keamanan yang serius." — Interpol/Kaspersky

## Posisi Apple

- Apple sudah mengizinkan sideloading perusahaan terbatas dengan kontrol ketat.
- Penyalahgunaan sebelumnya (misalnya, aplikasi Facebook Research, spyware Goontact) menunjukkan seberapa cepat mekanisme ini bisa disalahgunakan.
- Sideloading secara luas akan sangat meningkatkan risiko ini.

## Kesimpulan

Sideloading menghadirkan risiko luas bagi pengguna, pengembang, dan organisasi. Apple menyatakan bahwa hal ini akan mengurangi kepercayaan terhadap platform, meningkatkan permukaan serangan, dan mengurangi perlindungan privasi bagi semua pengguna—bukan hanya yang melakukan sideload.

---

## Dokumen Asli

- *Membangun Ekosistem Tepercaya untuk Jutaan Aplikasi* (Juni 2021)
  [apple.com (resmi)](https://www.apple.com/privacy/docs/Building_a_Trusted_Ecosystem_for_Millions_of_Apps.pdf)
  [github.com/lucasditomase (salinan)](https://github.com/lucasditomase/app-restrictions/blob/main/summary.pdf)

- *Analisis Ancaman Sideloading* (Oktober 2021)
  [apple.com (resmi)](https://www.apple.com/privacy/docs/Building_a_Trusted_Ecosystem_for_Millions_of_Apps_A_Threat_Analysis_of_Sideloading.pdf)
  [github.com/lucasditomase (salinan)](https://github.com/lucasditomase/app-restrictions/blob/main/threat-analysis.pdf)
