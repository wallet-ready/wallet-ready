# Sandbox-Wishlist

## Hintergrund und Zielsetzung
Das vorliegende Dokument trägt einige Wünsche und Bitten zur weiteren Optimierung 
der Zusammenarbeit in der Sandbox zusammen.

## 1. Wünsche 

### W1. Klarer definierte EUDI-Wallet Roadmap   
Damit die Teilnehmer an der Sandbox als angehende "Wallet-relying Parties" (WRPs) ihre eigenen Entwicklungen zielgerichtet planen 
können, wäre es **wünschenswert**, wenn durch das SPRIND-Team eine klarer definierte EUDI-Wallet Roadmap mit den jeweils aktuellen 
Planungen erstellt, mit WRPs geteilt und kontinuierlich fortgeschrieben werden könnte.

### W2. Reaktivierung der Logfunktionalität
In der aktuellen Version `0.25.13` der Sandbox-Wallet für Android wurde die Logfunktionalität offenbar dahin überarbeitet, dass keine
für WRPs 
nützlichen Logs mehr erzeugt werden. Das beispielhafte Log unten ist zumindest ohne eine weitere Dokumentation leider nicht allzu hilfreich. 
Es wäre **wünschenswert**, wenn die in vorherigen Versionen verfügbare Logfunktionalität wieder reaktiviert werden könnte.     

`07-25 12:22:27:706 D/FeatureFlagUpdateServiceImpl$fetchAndStoreFeatureFlags(1160) : FeatureFlags from API: [FeatureFlagOverrides(id=16980d22-7bcf-46fc-ab48-9880adeb67b2, features=[JsonFlagOverride(id=0b8a5871-d763-49a6-ba9d-31c5ea0a84ad, key=test_json, l=false, version=1, value={"color":"yellow","size":787542431434,"other":"best"}, strategies=[]), StringFlagOverride(id=a6f84a7a-937b-4ef5-b140-9f25e9ac60a2, key=minimum_app_version, l=false, version=10, value=0.25.13, strategies=[]), StringFlagOverride(id=38ac891e-51e0-4f00-a6ff-87f76ec01601, key=test_string, l=false, version=1, value=black, strategies=[]), BooleanFlagOverride(id=b939f899-b4e9-4185-b5de-af28703d48ca, key=test_feature, l=true, version=1, value=false, strategies=[]), IntFlagOverride(id=0827f3af-a512-4092-b8e4-cd9f01d6c0c8, key=test_number, l=false, version=1, value=42, strategies=[])])]`


## 2. Roadmap
### 2.1 EUDI-Wallet

| Anforderung                                                   | Feature                                    | Geplantes Bereitstellungsdatum  (Sandbox) | Geplantes Bereitstellungsdatum  (Produktion) |   
|---------------------------------------------------------------|--------------------------------------------|-------------------------------------------|----------------------------------------------|
| [Art. 5a (4) **(a)**](https://www.eid.as/de/#article5a)       | EAA-Management                             | OK                                        | ...                                          |
| [Art. 5a (4) **(b)**](https://www.eid.as/de/#article5a)       | Pseudonyme                                 | ...                                       | ...                                          |
| [Art. 5a (4) **(c)**](https://www.eid.as/de/#article5a)       | Wallet-to-Wallet                           | ...                                       | ...                                          |
| [Art. 5a (4) **(d)**](https://www.eid.as/de/#article5a)       | Transaktionslog                            | ...                                       | ...                                          |
| [Art. 5a (4) **(d) (i)**](https://www.eid.as/de/#article5a)   | Liste der WRPs                             | ...                                       | ...                                          |
| [Art. 5a (4) **(d) (ii)**](https://www.eid.as/de/#article5a)  | Anforderung der Datenlöschung              | ...                                       | ...                                          |
| [Art. 5a (4) **(d) (iii)**](https://www.eid.as/de/#article5a) | Reporting von WRPs an Datenschutzaufsicht  | ...                                       | ...                                          |
| [Art. 5a (4) **(e)**](https://www.eid.as/de/#article5a)       | QES / QESeal (`transaction_data`)          | ...                                       | ...                                          |
| [Art. 5a (4) **(f)**](https://www.eid.as/de/#article5a)       | Download der Nutzerdaten und Konfiguration | ...                                       | ...                                          |
| [Art. 5a (4) **(g)**](https://www.eid.as/de/#article5a)       | Datenübertragbarkeit                       | ...                                       | ...                                          |
| [Art. 5a (16) **(b)**](https://www.eid.as/de/#article5a)      | Unverknüpfbarkeit (ZKPs?)                  | ...                                       | ...                                          |
| [Art. 5a **(17)**](https://www.eid.as/de/#article5a)          | Nachweis der DSGVO-Konformität             | ...                                       | ...                                          |
| [Art. 5a **(21)**](https://www.eid.as/de/#article5a)          | Barrierefreiheit                           | ...                                       | ...                                          |

### 2.2 Registrar 

| Anforderung                                                  | Feature                     | Geplantes Bereitstellungsdatum  (Sandbox) | Geplantes Bereitstellungsdatum  (Produktion) |   
|--------------------------------------------------------------|-----------------------------|--------------------------------|----------------------------------------------|
| [Art. 5b **(1)**](https://www.eid.as/de/#article5b)          | Registrar (Portal)          | ...                          | ...                                          |
| [Art. 5b **(1)**](https://www.eid.as/de/#article5b)          | Registrar (API)             | ...                          | ...                                          |
| [Art. 5b **(10)**](https://www.eid.as/de/#article5b) | Regelungen für Intermediäre | ...                            | ...                                          |

### 2.3 Zertifizierung
... 

### 2.4 Grenzüberschreitende Verwendung

| Anforderung                                          | Feature                                                                            | Geplantes Bereitstellungsdatum  (Sandbox) | Geplantes Bereitstellungsdatum  (Produktion) |   
|------------------------------------------------------|------------------------------------------------------------------------------------|--------------------------------|----------------------------------------------|
| [Art. 5f **(2)**](https://www.eid.as/de/#article5f)  | Details der starken Kundenauthentifizierung (`transaction_data`)                   | ...                          | ...                                          |
| [Art. 5f **(4)**](https://www.eid.as/de/#article5f) | Verhaltenskodizes | ...                          | ...                                          |

### 2.5 Authentic Source Interface

| Anforderung                                           | Feature                                                                                                                                                          | Geplantes Bereitstellungsdatum  (Sandbox) | Geplantes Bereitstellungsdatum  (Produktion)  |   
|-------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------|---------------------------|
| [Art. 45e **(1)**](https://www.eid.as/de/#article45e) | Authentic Source Interface (`Verify` gemäß [ETSI TS 119 478](https://www.etsi.org/deliver/etsi_ts/119400_119499/119478/01.01.01_60/ts_119478v010101p.pdf))       | ...                                       | ...                       |
| [Art. 45e **(1)**](https://www.eid.as/de/#article45e) | Authentic Source Interface (`Retrieve` (?) gemäß [ETSI TS 119 478](https://www.etsi.org/deliver/etsi_ts/119400_119499/119478/01.01.01_60/ts_119478v010101p.pdf)) | ...                                       | ...                       |
