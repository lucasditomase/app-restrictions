![Banner](../assets/banner.png)  

# 对侧载行为的威胁分析  

## 关键信息  

- iPhone 强大的隐私和安全性至关重要，因为其存储的个人数据具有高度敏感性。  
- 侧载（在 App Store 之外安装应用）对这一安全模型构成严重威胁。  
- 在支持侧载的平台上，恶意软件的传播率高得多（例如 Android 的感染数量是 iOS 的 15–47 倍）。  
- App Store 的审核流程和系统保护机制大大降低了恶意软件的风险。  

## 侧载的风险  

- **恶意软件增多**：侧载绕过 App Store 审查，可导致广告软件、间谍软件、木马等泛滥。  
- **社会工程攻击**：用户可能被诱导安装伪装成合法应用的恶意应用。  
- **用户控制力下降**：侧载应用可能绕过家长控制、App 跟踪透明度或权限提示。  
- **平台安全性削弱**：可能要求公开专有 API 或操作系统内部机制，从而威胁 iOS 的核心安全架构。  
- **外部负面影响**：即使是避免侧载的用户也可能受到影响——例如，企业强制、仿冒 App Store 或工作需求等。  

## 恶意软件示例  

- **广告软件**（HiddenAds、CopyCat）：向用户推送大量具有攻击性或欺诈性的广告。  
- **勒索软件**（CryCryptor、MalLocker.B）：加密设备数据并勒索赎金。  
- **间谍软件**（SpyNote、HelloSpy）：监视用户行为，窃取私人数据，常用于亲密伴侣监控。  
- **银行木马**（BlackRock、Anubis）：通过界面覆盖攻击窃取账户信息，甚至可绕过双重验证（2FA）。  

## 安全专家建议  

> “只从官方应用商店安装应用。” — 欧洲刑警组织  
> “避免在 BYOD（自带设备）上进行侧载。” — 美国国土安全部  
> “第三方应用构成严重的安全威胁。” — 国际刑警组织 / 卡巴斯基  

## Apple 的立场  

- Apple 已允许企业在严格控制下进行有限的侧载。  
- 过往的滥用案例（如 Facebook Research 应用、Goontact 间谍软件）表明，这些机制极易被恶意利用。  
- 广泛开放侧载将极大放大这些风险。  

## 总结  

侧载行为给用户、开发者和组织带来了广泛的风险。Apple 表示，侧载将削弱用户对平台的信任，增加攻击面，并降低所有用户（不仅是侧载用户）的隐私保护。  

---  

## 原始文档  

- *为数百万应用构建可信生态系统*（2021 年 6 月）  
  -  [apple.com（官方）](https://www.apple.com/privacy/docs/Building_a_Trusted_Ecosystem_for_Millions_of_Apps.pdf)  
  -  [github.com/lucasditomase（备份）](https://github.com/lucasditomase/app-restrictions/blob/main/summary.pdf)  

- *对侧载行为的威胁分析*（2021 年 10 月）  
  -  [apple.com（官方）](https://www.apple.com/privacy/docs/Building_a_Trusted_Ecosystem_for_Millions_of_Apps_A_Threat_Analysis_of_Sideloading.pdf)  
  -  [github.com/lucasditomase（备份）](https://github.com/lucasditomase/app-restrictions/blob/main/threat-analysis.pdf)  
