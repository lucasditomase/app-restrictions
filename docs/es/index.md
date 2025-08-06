![Banner](../assets/banner.png)  

# Un Análisis de Amenazas del Sideloading  

## Puntos Clave  

- La fuerte privacidad y seguridad del iPhone es crítica debido a la naturaleza sensible de los datos personales que almacena.  
- El sideloading (instalación de apps fuera del App Store) representa una gran amenaza para este modelo de seguridad.  
- El malware es mucho más común en plataformas que permiten sideloading (por ejemplo, Android tiene de 15 a 47 veces más infecciones que iOS).  
- Los procesos de revisión del App Store y las protecciones del sistema reducen significativamente el riesgo de malware.  

## Riesgos del Sideloading  

- **Aumento de Malware**: El sideloading evita las revisiones del App Store, permitiendo adware, spyware, troyanos, etc.  
- **Ingeniería Social**: Los usuarios pueden ser engañados para instalar apps falsas que imitan a las legítimas.  
- **Menor Control del Usuario**: Las apps instaladas por sideload pueden eludir controles parentales, Transparencia en el Rastreo de Apps o solicitudes de permisos.  
- **Seguridad del Sistema Debilitada**: Podría requerir exponer APIs propietarias o internals del sistema operativo, amenazando la arquitectura central de seguridad de iOS.  
- **Efectos Negativos Colaterales**: Incluso los usuarios que no hacen sideload están en riesgo—por ejemplo, por coerción empresarial, tiendas de apps falsas o necesidades laborales.  

## Ejemplos de Malware  

- **Adware** (HiddenAds, CopyCat): Inunda al usuario con anuncios agresivos o fraudulentos.  
- **Ransomware** (CryCryptor, MalLocker.B): Encripta los datos del dispositivo y exige un rescate.  
- **Spyware** (SpyNote, HelloSpy): Monitorea la actividad, captura datos privados, usado en vigilancia entre parejas.  
- **Troyanos Bancarios** (BlackRock, Anubis): Roba credenciales mediante ataques superpuestos, incluso burlando el 2FA.  

## Consejos de Expertos en Seguridad  

> "Instale apps solo desde tiendas oficiales." — Europol  
> "Evite el sideloading en dispositivos BYOD." — Departamento de Seguridad Nacional de EE.UU.  
> "Las apps de terceros representan una seria amenaza de seguridad." — Interpol/Kaspersky  

## Posición de Apple  

- Apple ya permite un sideloading empresarial limitado con controles estrictos.  
- El uso indebido anterior (por ejemplo, app de investigación de Facebook, spyware Goontact) demuestra cuán rápido se abusa de estos mecanismos.  
- El sideloading generalizado amplificaría drásticamente este riesgo.  

## Conclusión  

El sideloading introduce riesgos generalizados para usuarios, desarrolladores y organizaciones. Apple afirma que degradaría la confianza en la plataforma, aumentaría las superficies de ataque y reduciría las protecciones de privacidad para todos los usuarios, no solo los que hacen sideload.  

---  

## Documentos Originales  

***Construyendo un Ecosistema Confiable para Millones de Apps*** (junio 2021)  
  -  [apple.com (oficial)](https://www.apple.com/privacy/docs/Building_a_Trusted_Ecosystem_for_Millions_of_Apps.pdf)  
  -  [github.com/lucasditomase (copia)](https://github.com/lucasditomase/app-restrictions/blob/main/summary.pdf)  

***Un Análisis de Amenazas del Sideloading*** (octubre 2021)  
  -  [apple.com (oficial)](https://www.apple.com/privacy/docs/Building_a_Trusted_Ecosystem_for_Millions_of_Apps_A_Threat_Analysis_of_Sideloading.pdf)  
  -  [github.com/lucasditomase (copia)](https://github.com/lucasditomase/app-restrictions/blob/main/threat-analysis.pdf)  
