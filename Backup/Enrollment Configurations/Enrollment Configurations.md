## Enrollment Configurations
### All users and all devices
Description: This is the default Device Limit Restriction applied with the lowest priority to all users regardless of group membership\.
#### Assignments
|intent |  target   |filter type|filter name|
|-------|-----------|-----------|-----------|
|Include|All Devices|none       |           |

#### Configuration
|              setting               |                       value                       |
|------------------------------------|---------------------------------------------------|
|Odata type                          |#microsoft.graph.deviceEnrollmentLimitConfiguration|
|Display Name                        |All users and all devices                          |
|Device Enrollment Configuration Type|limit                                              |
|Limit                               |                                                  5|

### All users and all devices
Description: This is the default Device Type Restriction applied with the lowest priority to all users regardless of group membership\.
#### Assignments
|intent |  target   |filter type|filter name|
|-------|-----------|-----------|-----------|
|Include|All Devices|none       |           |

#### Configuration
|              setting               |                                                                                                  value                                                                                                  |
|------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|Odata type                          |#microsoft.graph.deviceEnrollmentPlatformRestrictionsConfiguration                                                                                                                                       |
|Display Name                        |All users and all devices                                                                                                                                                                                |
|Device Enrollment Configuration Type|platformRestrictions                                                                                                                                                                                     |
|Ios Restriction                     |**platformBlocked:** False<br/>**personalDeviceEnrollmentBlocked:** False<br/>**osMinimumVersion:** <br/>**osMaximumVersion:** <br/>**blockedManufacturers:** <ul></ul>**blockedSkus:** <ul></ul>        |
|Windows Restriction                 |**platformBlocked:** False<br/>**personalDeviceEnrollmentBlocked:** False<br/>**osMinimumVersion:** <br/>**osMaximumVersion:** <br/>**blockedManufacturers:** <ul></ul>**blockedSkus:** <ul></ul>        |
|Windows Home Sku Restriction        |**platformBlocked:** False<br/>**personalDeviceEnrollmentBlocked:** False<br/>**osMinimumVersion:** None<br/>**osMaximumVersion:** None<br/>**blockedManufacturers:** <ul></ul>**blockedSkus:** <ul></ul>|
|Windows Mobile Restriction          |**platformBlocked:** True<br/>**personalDeviceEnrollmentBlocked:** False<br/>**osMinimumVersion:** <br/>**osMaximumVersion:** <br/>**blockedManufacturers:** <ul></ul>**blockedSkus:** <ul></ul>         |
|Android Restriction                 |**platformBlocked:** False<br/>**personalDeviceEnrollmentBlocked:** False<br/>**osMinimumVersion:** <br/>**osMaximumVersion:** <br/>**blockedManufacturers:** <ul></ul>**blockedSkus:** <ul></ul>        |
|Android For Work Restriction        |**platformBlocked:** False<br/>**personalDeviceEnrollmentBlocked:** False<br/>**osMinimumVersion:** <br/>**osMaximumVersion:** <br/>**blockedManufacturers:** <ul></ul>**blockedSkus:** <ul></ul>        |
|Mac Restriction                     |**platformBlocked:** False<br/>**personalDeviceEnrollmentBlocked:** False<br/>**osMinimumVersion:** None<br/>**osMaximumVersion:** None<br/>**blockedManufacturers:** <ul></ul>**blockedSkus:** <ul></ul>|
|Mac O S Restriction                 |**platformBlocked:** False<br/>**personalDeviceEnrollmentBlocked:** False<br/>**osMinimumVersion:** None<br/>**osMaximumVersion:** None<br/>**blockedManufacturers:** <ul></ul>**blockedSkus:** <ul></ul>|

### All users and all devices
Description: This is the default Windows Hello for Business configuration applied with the lowest priority to all users regardless of group membership\.
#### Assignments
|intent |  target   |filter type|filter name|
|-------|-----------|-----------|-----------|
|Include|All Devices|none       |           |

#### Configuration
|              setting               |                                value                                |
|------------------------------------|---------------------------------------------------------------------|
|Odata type                          |#microsoft.graph.deviceEnrollmentWindowsHelloForBusinessConfiguration|
|Display Name                        |All users and all devices                                            |
|Device Enrollment Configuration Type|windowsHelloForBusiness                                              |
|Pin Minimum Length                  |                                                                    6|
|Pin Maximum Length                  |                                                                  127|
|Pin Uppercase Characters Usage      |allowed                                                              |
|Pin Lowercase Characters Usage      |allowed                                                              |
|Pin Special Characters Usage        |allowed                                                              |
|State                               |enabled                                                              |
|Security Device Required            |True                                                                 |
|Unlock With Biometrics Enabled      |True                                                                 |
|Remote Passport Enabled             |False                                                                |
|Pin Previous Block Count            |                                                                   24|
|Enhanced Biometrics State           |enabled                                                              |
|Security Key For Sign In            |disabled                                                             |
|Enhanced Sign In Security           |                                                                    1|

### All users and all devices
Description: This is the default Windows Restore configuration applied with the lowest priority to all users and all devices regardless of group membership\.
#### Assignments
|intent |  target   |filter type|filter name|
|-------|-----------|-----------|-----------|
|Include|All Devices|none       |           |

#### Configuration
|              setting               |                           value                            |
|------------------------------------|------------------------------------------------------------|
|Odata type                          |#microsoft.graph.windowsRestoreDeviceEnrollmentConfiguration|
|Display Name                        |All users and all devices                                   |
|Device Enrollment Configuration Type|windowsRestore                                              |
|State                               |notConfigured                                               |

### POC_WIN_D_CO_Intune_AllUsers
#### Configuration
|                     setting                     |                                                             value                                                             |
|-------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------|
|Odata type                                       |#microsoft.graph.deviceComanagementAuthorityConfiguration                                                                      |
|Display Name                                     |POC_WIN_D_CO_Intune_AllUsers                                                                                                   |
|Priority                                         |                                                                                                                              1|
|Role Scope Tag Ids                               |Default<br/>                                                                                                                   |
|Device Enrollment Configuration Type             |deviceComanagementAuthorityConfiguration                                                                                       |
|Managed Device Authority                         |                                                                                                                              1|
|Install Configuration Manager Agent              |True                                                                                                                           |
|Configuration Manager Agent Command Line Argument|/mp:<CloudManagementGatewayURL> /nocrlcheck CCMHOSTNAME=<CloudManagementGateway> SMSSiteCode=<SiteCode> SMSMP=<ManagementPoint>|

