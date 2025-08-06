![Banner](../assets/banner.png)

# 側載行為的威脅分析

## 主要見解

- iPhone 的強大隱私與安全性至關重要，因為其儲存了高度敏感的個人資料。
- 側載（在 App Store 之外安裝應用程式）對此安全模型構成重大威脅。
- 支援側載的平台上的惡意軟體明顯更多（例如 Android 的感染量是 iOS 的 15–47 倍）。
- App Store 的審核流程與系統保護機制大幅降低了惡意軟體的風險。

## 側載的風險

- **惡意軟體增加**：側載繞過 App Store 的檢查，讓廣告軟體、間諜程式、木馬等有機可乘。
- **社交工程攻擊**：用戶可能會被誘騙安裝仿冒合法應用的惡意程式。
- **使用者控制權下降**：側載的應用可能繞過家長監控、App 追蹤透明度或權限提示。
- **平台安全性削弱**：可能需要公開私有 API 或作業系統內部實作，威脅 iOS 核心安全架構。
- **負面外部效應**：即便不側載的使用者也有風險，例如企業強迫、偽造 App Store、或工作需求等。

## 惡意軟體實例

- **廣告軟體**（HiddenAds、CopyCat）：對使用者大量推播具攻擊性或詐騙性的廣告。
- **勒索軟體**（CryCryptor、MalLocker.B）：加密裝置資料並索取贖金。
- **間諜軟體**（SpyNote、HelloSpy）：監控使用者行為、竊取私人資料，常用於親密關係監控。
- **銀行木馬**（BlackRock、Anubis）：透過畫面覆蓋攻擊竊取帳號資訊，甚至可繞過雙重驗證（2FA）。

## 資安專家建議

> 「僅從官方應用商店安裝應用程式。」— 歐洲刑警組織 Europol
> 「避免在 BYOD 裝置上側載。」— 美國國土安全部
> 「第三方應用程式構成嚴重的安全威脅。」— 國際刑警組織 / 卡巴斯基

## Apple 的立場

- Apple 已允許企業端在嚴格控管下進行有限的側載。
- 過往濫用實例（如 Facebook Research 應用、Goontact 間諜軟體）顯示該機制很容易被濫用。
- 若普遍開放側載，這些風險將大幅提升。

## 結論

側載行為為使用者、開發者與組織帶來廣泛風險。Apple 表示，這將削弱對平台的信任、擴大攻擊面，並降低對所有使用者（不僅是側載者）的隱私保護。

---

## 原始文件

- *為數百萬應用程式打造可信賴的生態系統*（2021 年 6 月）
  -  [apple.com（官方）](https://www.apple.com/privacy/docs/Building_a_Trusted_Ecosystem_for_Millions_of_Apps.pdf)
  -  [github.com/lucasditomase（備份）](https://github.com/lucasditomase/app-restrictions/blob/main/summary.pdf)

- *側載行為的威脅分析*（2021 年 10 月）
  -  [apple.com（官方）](https://www.apple.com/privacy/docs/Building_a_Trusted_Ecosystem_for_Millions_of_Apps_A_Threat_Analysis_of_Sideloading.pdf)
  -  [github.com/lucasditomase（備份）](https://github.com/lucasditomase/app-restrictions/blob/main/threat-analysis.pdf)
