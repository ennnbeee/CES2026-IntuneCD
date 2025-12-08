## Configuration Profiles
### POC_AND_D_CO_SBL_MSZT_WiFi
#### Configuration
|               setting                |                            value                             |
|--------------------------------------|--------------------------------------------------------------|
|Odata type                            |#microsoft.graph.androidDeviceOwnerEnterpriseWiFiConfiguration|
|Role Scope Tag Ids                    |Default<br/>                                                  |
|Display Name                          |POC_AND_D_CO_SBL_MSZT_WiFi                                    |
|Network Name                          |0c62cdc3-8312-4cfd-92b1-f17268655270                          |
|Ssid                                  |wifi                                                          |
|Connect Automatically                 |True                                                          |
|Connect When Network Name Is Hidden   |False                                                         |
|Wi Fi Security Type                   |wpaEnterprise                                                 |
|Pre Shared Key Is Set                 |False                                                         |
|Proxy Settings                        |none                                                          |
|Eap Type                              |peap                                                          |
|Authentication Method                 |usernameAndPassword                                           |
|Inner Authentication Protocol For Peap|none                                                          |

### POC_IOS_D_CO_SBL_MSZT_WiFi
#### Configuration
|              setting              |                     value                     |
|-----------------------------------|-----------------------------------------------|
|Odata type                         |#microsoft.graph.iosEnterpriseWiFiConfiguration|
|Role Scope Tag Ids                 |Default<br/>                                   |
|Display Name                       |POC_IOS_D_CO_SBL_MSZT_WiFi                     |
|Network Name                       |wifi                                           |
|Ssid                               |wifi                                           |
|Connect Automatically              |False                                          |
|Connect When Network Name Is Hidden|False                                          |
|Wi Fi Security Type                |wpa2Enterprise                                 |
|Proxy Settings                     |none                                           |
|Eap Type                           |peap                                           |
|Authentication Method              |usernameAndPassword                            |

### POC_MAC_D_CO_SBL_MSZT_WiFi
#### Configuration
|              setting              |                      value                      |
|-----------------------------------|-------------------------------------------------|
|Odata type                         |#microsoft.graph.macOSEnterpriseWiFiConfiguration|
|Role Scope Tag Ids                 |Default<br/>                                     |
|Display Name                       |POC_MAC_D_CO_SBL_MSZT_WiFi                       |
|Network Name                       |fd09d487-a246-48fb-8f00-7a0964c1ff35             |
|Ssid                               |wifi                                             |
|Connect Automatically              |True                                             |
|Connect When Network Name Is Hidden|True                                             |
|Wi Fi Security Type                |wpaEnterprise                                    |
|Proxy Settings                     |none                                             |
|Deployment Channel                 |deviceChannel                                    |
|Eap Type                           |peap                                             |
|Authentication Method              |usernameAndPassword                              |

### POC_WIN_D_CO_SBL_MSZT_EndpointAnalytics
#### Configuration
|               setting               |                        value                        |
|-------------------------------------|-----------------------------------------------------|
|Odata type                           |#microsoft.graph.windowsHealthMonitoringConfiguration|
|Role Scope Tag Ids                   |Default<br/>                                         |
|Display Name                         |POC_WIN_D_CO_SBL_MSZT_EndpointAnalytics              |
|Allow Device Health Monitoring       |enabled                                              |
|Config Device Health Monitoring Scope|bootPerformance                                      |

### POC_WIN_D_CO_SBL_MSZT_Updates
#### Configuration
|                setting                 |                                                                          value                                                                           |
|----------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------|
|Odata type                              |#microsoft.graph.windowsUpdateForBusinessConfiguration                                                                                                    |
|Role Scope Tag Ids                      |Default<br/>                                                                                                                                              |
|Display Name                            |POC_WIN_D_CO_SBL_MSZT_Updates                                                                                                                             |
|Delivery Optimization Mode              |userDefined                                                                                                                                               |
|Prerelease Features                     |userDefined                                                                                                                                               |
|Automatic Update Mode                   |autoInstallAtMaintenanceTime                                                                                                                              |
|Microsoft Update Service Allowed        |True                                                                                                                                                      |
|Drivers Excluded                        |False                                                                                                                                                     |
|Quality Updates Paused                  |False                                                                                                                                                     |
|Feature Updates Paused                  |False                                                                                                                                                     |
|Quality Updates Pause Expiry Date Time  |0001-01-01T00:00:00Z                                                                                                                                      |
|Feature Updates Pause Expiry Date Time  |0001-01-01T00:00:00Z                                                                                                                                      |
|Business Ready Updates Only             |userDefined                                                                                                                                               |
|Skip Checks Before Restart              |False                                                                                                                                                     |
|Feature Updates Rollback Window In Days |                                                                                                                                                        30|
|Quality Updates Will Be Rolled Back     |False                                                                                                                                                     |
|Feature Updates Will Be Rolled Back     |False                                                                                                                                                     |
|Quality Updates Rollback Start Date Time|0001-01-01T00:00:00Z                                                                                                                                      |
|Feature Updates Rollback Start Date Time|0001-01-01T00:00:00Z                                                                                                                                      |
|Deadline For Quality Updates In Days    |                                                                                                                                                        10|
|Deadline Grace Period In Days           |                                                                                                                                                         4|
|Postpone Reboot Until After Deadline    |True                                                                                                                                                      |
|Auto Restart Notification Dismissal     |notConfigured                                                                                                                                             |
|User Pause Access                       |enabled                                                                                                                                                   |
|User Windows Update Scan Access         |enabled                                                                                                                                                   |
|Update Notification Level               |defaultNotifications                                                                                                                                      |
|Allow Windows11 Upgrade                 |False                                                                                                                                                     |
|Installation Schedule                   |**@odata.type:** #microsoft.graph.windowsUpdateActiveHoursInstall<br/>**activeHoursStart:** 08:00:00.0000000<br/>**activeHoursEnd:** 17:00:00.0000000<br/>|

