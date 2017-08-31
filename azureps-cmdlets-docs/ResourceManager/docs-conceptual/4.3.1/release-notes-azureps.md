---
title: "Azure PowerShell 變更記錄 | Microsoft Docs"
description: "這是在最新版中對 Azure powershell 所做的變更歷程記錄。"
services: azure
author: sdwheeler
ms.author: sewhee
manager: carmonm
ms.service: azure-powershell
ms.product: azure
ms.devlang: powershell
ms.topic: conceptual
ms.workload: 
ms.date: 07/26/2017
ms.openlocfilehash: beaa30dbac11d1ce65eea3fb09ae5d748793342e
ms.sourcegitcommit: db5c50de90764a9bdc7c1f1dbca3aed5bfeb05fa
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 08/22/2017
---
# <a name="release-notes"></a>版本資訊

這是此版本中對 Azure PowerShell 所做的變更清單。

## <a name="20170810---version-431"></a>2017.08.10 - 版本 4.3.1
  * 更新以修正組件簽署問題

## <a name="20170807---version-430"></a>2017.08.07 - 版本 4.3.0
* AnalysisServices
  * 修正了 Set-AzureRmAnalysisServciesServer 中的錯誤 (bug)
    - 若未提供管理員，會移除管理員。
  * 在 New-AzureRmAnalysisServicesServer 與 Set-AzureRmAnalysisServicesServer 中新增了 BackupBlobContainerUri
    - 啟用此功能可設定/停用用於備份/還原 Azure Analysis Services 伺服器的備份 BLOb 容器
  * 更新了 New-AzureRmAnalysisServicesServer 與 Set-AzureRmAnalysisServicesServer 中的 Sku 查閱功能
    - 將硬式編碼的 Sku 變更為動態查閱。
  * 新增 Add-AzureAnalysisServicesAccount 以支援透過服務主體登入
* 自動化
  * 變更了 AutomationDSC* Cmdlet，現可從 100 多筆記錄中提取資料
  * 解決了 Verbose 串流在呼叫某些自動化 Cmdlet (例如 Get-AzureRmAutomationVariable、Get-AzureRmAutomationJob) 後，停止運作的問題。
  * 支援在 StartAzureAutomationDscCompilationJob 與 ImportAzureAutomationDscNodeConfiguration 中新增的 NodeConfiguration 組建版本設定
  * 修正現有問題的錯誤 (bug) - 修正別名問題 #3775，以及修正 runOn 別名和 HybridWorkers 的支援。
* 計算
  * Set-AzureRmVMAEMExtension：新增對新高階磁碟大小的支援
  * Set-AzureRmVMAEMExtension：新增對 M 系列的支援
  * 將 ForceUpdateTag 參數新增至 Add-AzureRmVmssExtension
  * 將 Primary 參數新增至 New-AzureRmVmssIpConfig
  * 將 EnableAcceleratedNetworking 參數新增至 Add-AzureRmVmssNetworkInterfaceConfig
  * 將 InstanceId 新增至 Set-AzureRmVmss
  * 對 Get-AzureRmVM -Status 輸出公開 MaintenanceRedeployStatus
  * 對 Get-AzureRmComputeResourceSku 的表格格式公開限制與功能
* DataLakeStore
  * 問題的修正：https://github.com/Azure/azure-powershell/issues/4323
* EventHub
  * 為 NamespaceAttributes 新增了 ResourceGroup 屬性
    - 「ResourceGroup」獲得命名空間所在資源群組的名稱
  * 更新了可以在執行用於操作 AuthorizationRule 的命名空間與 EventHub 的參數集時使用的 Cmdlet
    - New-AzureRmEventHubAuthorizationRule - 將新的 AuthorizationRule 新增至現有的命名空間或 EventHub 。
    - Get-AzureRmEventHubAuthorizationRule - 取得現有命名空間或 EventHub 的 AuthorizationRule/AuthorizationRule 清單。
    - Set-AzureRmEventHubAuthorizationRule - 更新 EventHub 或命名空間現有 AuthorizationRule 的屬性。
    - Remove-AzureRmEventHubAuthorizationRule - 刪除現有命名空間或 EventHub 的現有 AuthorizationRule。
    - New-AzureRmEventHubKey - 為現有命名空間或 EventHub 的 AuthorizationRule 產生新的主要/次要索引鍵。
    - Get-AzureRmEventHubKey - 為現有命名空間或 EventHub 的 AuthorizationRule 取得主要/次要索引鍵。
* 網路
    * 新增了 IPv6 支援與新的選擇性參數 -PeerAddressType
      * New-AzureRmExpressRouteCircuitPeeringConfig：
      * Set-AzureRmExpressRouteCircuitPeeringConfig：新增了 IPv6 支援。 新增了新的選擇性參數
      * Remove-AzureRmExpressRouteCircuitPeeringConfig：新增了 IPv6 支援。 新增了新的選擇性參數
    * 將參數 -ProbeEnabled 標示為已淘汰
      - Add-AzureRmApplicationGatewayBackendHttpSettings
      - New-AzureRmApplicationGatewayBackendHttpSettings
      - Set-AzureRmApplicationGatewayBackendHttpSettings
* 設定檔
    * 資料收集功能依預設啟用。 Microsoft 會收集使用資料來改善使用者體驗。 資料為匿名，且不包含命令列引數值。
      - 使用 Disable-AzureRmDataCollection Cmdlet 可將該功能關閉
      - 使用 Enable-AzureRmDataCollection Cmdlet 可將該功能開啟
* 資源
    * 新增在將要求傳送到 ARM 之前，對下列 roledefinition 與 roleassignment Commandlet 提供的驗證範圍支援
      - Get-AzureRMRoleAssignment
      - New-AzureRMRoleAssignment
      - Remove-AzureRMRoleAssignment
      - Get-AzureRMRoleDefinition
      - New-AzureRMRoleDefinition
      - Remove-AzureRMRoleDefinition
      - Set-AzureRMRoleDefinition
* ServiceBus
    * 為命名空間、佇列與主題新增了以下新的 Commandlet。 授權規則作業是根據參數集而執行。
     - New-AzureRmServiceBusAuthorizationRule - 將新的 AuthorizationRule 新增至現有的 ServiceBus 命名空間/佇列/主題。
     - Get-AzureRmServiceBusAuthorizationRule - 取得現有 ServiceBus 命名空間/佇列/主題的 AuthorizationRule/AuthorizationRule 清單。
     - Set-AzureRmServiceBusAuthorizationRule - 更新 Servicebus 命名空間/佇列/主題現有 AuthorizationRule 的屬性。
     - New-AzureRmServiceBusKey - 為現有 ServiceBus 命名空間/佇列/主題的 AuthorizationRule 產生新的主要/次要索引鍵。
     - Get-AzureRmServiceBusKey - 取得現有 ServiceBus 命名空間/佇列/主題的 AuthorizationRule 的主要/次要索引鍵。
     - Remove-AzureRmServiceBusNamespaceAuthorizationRule - 刪除 ServiceBus 命名空間/佇列/主題的現有 AuthorizationRule。
    * 新增了資源群組屬性至 NamespceAttributes
* Sql
    * 更新 Set-AzureRmSqlServerTransparentDataEncryptionProtector，以在加密保護裝置類型設為 AzureKeyVault 時，顯示警告並要求確認
    * 為稽核設定新增更新的 Cmdlet
      - Get-AzureRmSqlDatabaseAuditing Cmdlet，此 Cmdlet 可取得 Azure SQL 資料庫的稽核設定。
      - Get-AzureRmSqlServerAuditing Cmdlet，此 Cmdlet 可取得 Azure SQL 伺服器的稽核設定。
      - Set-AzureRmSqlDatabaseAuditing Cmdlet，此 Cmdlet 可變更 Azure SQL 資料庫的稽核設定。
      - Set-AzureRmSqlServerAuditing Cmdlet，此 Cmdlet 可變更 Azure SQL 伺服器的稽核設定。
    * 淘汰現有的稽核原則 Cmdlet
      - Get-AzureRmSqlDatabaseAuditingPolicy
      - Get-AzureRmSqlServerAuditingPolicy
      - Set-AzureRmSqlDatabaseAuditingPolicy
      - Set-AzureRmSqlServerAuditingPolicy
      - Use-AzureRmSqlServerAuditingPolicy
      - Remove-AzureRmSqlDatabaseAuditing
      - Remove-AzureRmSqlServerAuditing
    * Update-AzureRmSqlSyncGroup 的結構描述檔案剖析現在不區分大小寫。
* 儲存體
    * 為資源模式儲存體帳戶 Cmdlet 新增 NeworkRule 支援
      - New-AzureRmStorageAccount
      - Set-AzureRmStorageAccount
      - Get-AzureRmStorageAccountNetworkRuleSet
      - Update-AzureRmStorageAccountNetworkRuleSet
      - Add-AzureRmStorageAccountNetworkRule
      - Remove-AzureRmStorageAccountNetworkRule

## <a name="20170717---version-421"></a>2017.07.17 - 版本 4.2.1
* 計算
    - 透過 VM 磁碟和 VM 磁碟快照集修正問題，建立並更新 Cmdlet，(連結) (英文) [https://github.com/azure/azure-powershell/issues/4309]
      - New-AzureRmDisk
      - New-AzureRmSnapshot
      - Update-AzureRmDisk
      - Update-AzureRmSnapshot
* 設定檔
    - 在 RDFE 使用非互動使用者驗證修正問題 (連結) (英文) [https://github.com/Azure/azure-powershell/issues/4299]
* ServiceManagement
    - 使用非互動使用者驗證修正問題 (連結) (英文) [https://github.com/Azure/azure-powershell/issues/4299]

## <a name="2017711---version-420"></a>2017.7.11 - 版本 4.2.0
* AnalysisServices
    * 新增資料平面 API
        - 引進用以擷取 AS 伺服器記錄檔 Export-AzureAnalysisServicesInstanceLog 的 API
* 自動化
    * 針對 New-AzureRmAutomationSchedule，正確設定每週和每月排程的 TimeZone 值
        - 詳細資訊可以在本問題找到 (英文)：https://github.com/Azure/azure-powershell/issues/3043
* AzureBatch
    - 新增 Get-AzureBatchJobPreparationAndReleaseTaskStatus cmdlet。
    - 將位元組範圍的開始與結束加入 Get-AzureBatchNodeFileContent 參數。
* CognitiveServices
    * 整合辨識服務管理 SDK 1.0.0 版。
    * 修正帳戶名稱長度檢查錯誤。
* 計算
    * 儲存體帳戶類型支援映像磁碟：
        - 「StorageAccountType」參數已加入 Set-AzureRmImageOsDisk 和 Add-AzureRmImageDataDisk
    * 採用 Vmss IP 組態的 PrivateIP 和 PublicIP 功能：
        - 「PrivateIPAddressVersion」、「PublicIPAddressConfigurationName」、「PublicIPAddressConfigurationIdleTimeoutInMinutes」、「DnsSetting」名稱已加入 New-AzureRmVmssIpConfig
        - 指定 IPv4 或 IPv6 的「PrivateIPAddressVersion」參數已加入 New-AzureRmVmssIpConfig
    * 效能維護功能：
        - 「PerformMaintenance」切換參數已加入 Restart-AzureRmVM。
        - Get-AzureRmVM -Status 會顯示特定 VM 的效能維護資訊
    * 虛擬機器身分識別功能：
        - 「IdentityType」參數已加入 New-AzureRmVMConfig 和 UpdateAzureRmVM
        - Get-AzureRmVM 顯示特定 VM 的身分識別資訊
    * Vmss 身分識別功能：
        - 「IdentityType」參數已加入 New-AzureRmVmssConfig
        - Get-AzureRmVmss 顯示特定 Vmss 的身分識別資訊
    * Vmss 開機診斷功能：
        - 設定 Vmss 物件開機診斷的新 Cmdlet：Set-AzureRmVmssBootDiagnostics
        - 「BootDiagnostic」參數已加入 New-AzureRmVmssConfig
    * Vmss LicenseType 功能：
        - 「LicenseType」參數已加入 New-AzureRmVmssConfig
    * RecoveryPolicyMode 支援：
        - 「RecoveryPolicyMode」參數已加入 New-AzureRmVmssConfig
    * 計算資源 Sku 功能：
        - 新 Cmdlet「Get-AzureRmComputeResourceSku」列出所有計算資源 sku
* DataFactories
    * 取代 New-AzureRmDataFactoryGatewayKey
    * 加入 New-AzureRmDataFactoryGatewayAuthKey 和 Get-AzureRmDataFactoryGatewayAuthKey，推出閘道驗證金鑰功能
* DataLakeAnalytics
    * 透過下列命令，加入計算原則 CRUD 支援：
        - New-AzureRMDataLakeAnalyticsComputePolicy
        - Get-AzureRMDataLakeAnalyticsComputePolicy
        - Remove-AzureRMDataLakeAnalyticsComputePolicy
        - Update-AzureRMDataLakeAnalyticsComputePolicy
    * 新增支援作業關係中繼資料，協助處理週期性作業和作業流程。 已更新或新增下列命令：
        - Submit-AzureRMDataLakeAnalyticsJob
        - Get-AzureRMDataLakeAnalyticsJob
        - Get-AzureRMDataLakeAnalyticsJobRecurrence
        - Get-AzureRMDataLakeAnalyticsJobPipeline
    * 針對作業和目錄 API 更新 Token 對象，以使用正確的 Data Lake 特定對象，而非 Azure 資源對象。
* DataLakeStore
    * 新增支援在 Set-AzureRMDataLakeStoreAccount Cmdlet 由使用者管理 KeyVault 金鑰輪替
    * 新增生活品質更新，在新增使用者管理的 KeyVault 或金鑰輪替時，自動觸發 `enableKeyVault` 呼叫。
    * 針對作業和目錄 API 更新 Token 對象，以使用正確的 Data Lake 特定對象，而非 Azure 資源對象。
    * 已修正錯誤，該錯誤會使用下列 Cmdlet 限制建立/附加檔案的大小：
        - New-AzureRmDataLakeStoreItem
        - Add-AzureRmDataLakeStoreItemContent
* Dns
    * 針對 Get-AzureRmDnsZone 修正管線情節中的錯誤
        - 詳細資訊可以在這裡找到 (英文)：https://github.com/Azure/azure-powershell/issues/4203
* HDInsight
    * 新增支援以啟用/停用 Operations Management Suite (OMS)
    * 新的 Cmdlet
        - Enable-AzureRmHDInsightOperationsManagementSuite
        - Disable-AzureRmHDInsightOperationsManagementSuite
        - Get-AzureRmHDInsightOperationsManagementSuite
    * 加入新的參數，將 Spark 自訂設定設為 Add-AzureRmHDInsightConfigValues
        - Spark 1.6 適用的參數 SparkDefaults 和 SparkThriftConf
        - Spark 2.0 適用的參數 Spark2Defaults 和 Spark2ThriftConf
* 深入解析
    * 問題 #4215 (變更要求) 移除 Get-AzureRmLog Cmdlet 的 15 天期間限制。 此外亦小幅變更了單元測試名稱。
    * 已針對 Get-AzureRmLog 修正問題 #3957
        - 問題 #1：後端傳回的記錄，每頁 200 筆，透過接續 Token 連結下一頁。 客戶會看到 Cmdlet 只傳回 200 筆記錄，但確知應還有更多記錄。 除非 MaxEvents 小於 200，否則不論客戶設定的值為何，都會發生這種情形。
        - 問題 #2：文件包含不正確的 Cmdlet 相關資料，例如：預設期間是 1 小時。
        - 修正 #1：Cmdlet 現在會遵循後端傳回的接續 Token，直到達到 MaxEvents 或集合的結束為止。<br>MaxEvents 的預設值為 1000，最大值為 100000。 凡 MaxEvents 值小於 1 都會忽略，並改為使用預設值。 這些值和行為並未變更，現在都已正確地記錄。<br>由於 Cmdlet 名稱未說明相關事件，而只提供了記錄檔，因此已新增 MaxEvents 別名 -MaxRecords-。
        - 修正 #2：文件包含正確及更詳細的資訊：新的別名、正確的期間、正確的預設值、最小值和最大值。
* KeyVault
    * 將 -UserPrincipalName 指定到 Set-AzureRMKeyVaultAccessPolicy 和 Remove-AzureRMKeyVaultAccessPolicy Cmdlet 時，請從目錄查詢中移除電子郵件地址。
      - 兩個 Cmdlet 現在會有適當的 -EmailAddress 參數，在需要查詢電子郵件地址時可供使用，而不使用 -UserPrincipalName 參數。  如果目錄中有多個相符的電子郵件地址，則此 Cmdlet 的電子郵件地址將會失效。
* 網路
    * New-AzureRmIpsecPolicy：SALifeTimeSeconds 和 SADataSizeKilobytes 不再是必要參數
        - SALifeTimeSeconds 預設值為 27000 秒
        - SADataSizeKilobytes 預設值為 102400000 KB
    * 使用 ssl 原則，並在應用程式閘道列出所有 ssl 選項 api，以新增支援自訂加密套件設定
        - 新增選擇性參數 -PolicyType、-PolicyName、-MinProtocolVersion、-Ciphersuite
            - Add-AzureRmApplicationGatewaySslPolicy
            - New-AzureRmApplicationGatewaySslPolicy
            - Set-AzureRmApplicationGatewaySslPolicy
        - 新增 Get-AzureRmApplicationGatewayAvailableSslOptions (別名：List-AzureRmApplicationGatewayAvailableSslOptions)
        - 新增 Get AzureRmApplicationGatewaySslPredefinedPolicy (別名：List-AzureRmApplicationGatewaySslPredefinedPolicy)
    * 應用程式閘道中新增重新導向支援
        - 新增 Add-AzureRmApplicationGatewayRedirectConfiguration
        - 新增 Get-AzureRmApplicationGatewayRedirectConfiguration
        - 新增 New-AzureRmApplicationGatewayRedirectConfiguration
        - 新增 Remove-AzureRmApplicationGatewayRedirectConfiguration
        - 新增 Set-AzureRmApplicationGatewayRedirectConfiguration
        - 新增選擇性參數 -RedirectConfiguration
            - Add-AzureRmApplicationGatewayRequestRoutingRule
            - New-AzureRmApplicationGatewayRequestRoutingRule
            - Set-AzureRmApplicationGatewayRequestRoutingRule
        - 新增選擇性參數-DefaultRedirectConfiguration
            - Add-AzureRmApplicationGatewayUrlPathMapConfig
            - New-AzureRmApplicationGatewayUrlPathMapConfig
            - Set-AzureRmApplicationGatewayUrlPathMapConfig
        - 新增選擇性參數 -RedirectConfiguration
            - Add-AzureRmApplicationGatewayPathRuleConfig
            - New-AzureRmApplicationGatewayPathRuleConfig
            - Set-AzureRmApplicationGatewayPathRuleConfig
        - 新增選擇性參數 -RedirectConfigurations
            - New-AzureRmApplicationGateway
            - Set-AzureRmApplicationGateway
    * 在應用程式閘道中新增支援 azure 網站
        - 新增 New-AzureRmApplicationGatewayProbeHealthResponseMatch
        - 新增選擇性參數 -PickHostNameFromBackendHttpSettings、-MinServers、-Match
            - Add-AzureRmApplicationGatewayProbeConfig
            - New-AzureRmApplicationGatewayProbeConfig
            - Set-AzureRmApplicationGatewayProbeConfig
        - 新增選擇性參數 -PickHostNameFromBackendAddress、-AffinityCookieName、-ProbeEnabled、-Path
            - Add-AzureRmApplicationGatewayBackendHttpSettings
            - New-AzureRmApplicationGatewayBackendHttpSettings
            - Set-AzureRmApplicationGatewayBackendHttpSettings
    * 更新 Get-AzureRmPublicIPaddress，以擷取透過 VM 擴展集建立的 publicipaddress 資源
    * 新增 Cmdlet 取得虛擬網路的目前使用情形
        - Get-AzureRmVirtualNetworkUsageList
* 設定檔
    * 修正使用 Import-AzureRmContext 或 Save-AzureRmContext 時的錯誤
        - 詳細資訊可以在本問題找到 (英文)：https://github.com/Azure/azure-powershell/issues/3954
* RecoveryServices.SiteRecovery
    * 推出新的 Azure Site Recovery 作業模組。
        - 所有 Cmdlet 的開頭均為 AzureRmRecoveryServicesAsr*
* Sql
    * 將資料同步 PowerShell Cmdlet 加入 AzureRM.Sql
    * 更新 AzureRmSqlServer Cmdlet 以使用新的 REST API 版本，避免建立伺服器時發生逾時。
    * 已取代的伺服器升級 Cmdlet，因為舊的伺服器版本 (2.0) 已經不存在。
    * 將新的選擇性切換參數「AssignIdentity」加入 New-AzureRmSqlServer 和 Set-AzureRmSqlServer Cmdlet，以支援佈建 SQL 伺服器資源的資源身分識別
    * 參數 ResourceGroupName 現在是 Get-AzureRmSqlServer 的選擇性項目
        - 詳細資訊可在下列問題中找到 (英文)：https://github.com/Azure/azure-powershell/issues/635
* ExpressRoute 的 ServiceManagement：
    * 更新 New-AzureBgpPeering Cmdlet，新增下列選項：
        - PeerAddressType：可指定「IPv4」或「IPv6」的值，以建立對應位址系列類型的 BGP 對等互連
    * 更新 Set-AzureBgpPeering Cmdlet，新增下列選項：
        - PeerAddressType：可指定「IPv4」或「IPv6」的值，以更新對應位址系列類型的 BGP 對等互連
    * 更新 Remove-AzureBgpPeering Cmdlet，新增下列選項：
        - PeerAddressType：可指定「IPv4」、「IPv6」或所有的值，以移除對應位址系列類型或所有的 BGP 對等互連

## <a name="20170607---version-410"></a>2017.06.07 - 版本 4.1.0
* AnalysisServices
    * 新增的 SKU：B1、B2、S0
    * 新增相應增加/減少支援
* CognitiveServices
    * 更新在建立辨識服務資源時的授權合約詳細顯示內容
* 計算
    * 針對具有多個受控磁碟的虛擬機器，修正 Test-AzureRmVMAEMExtension
    * 更新 Set-AzureRmVMAEMExtension：新增進階受控磁碟的快取資訊
    * Add-AzureRmVhd：vhd 的大小限制會增加至 4TB。
    * Stop-AzureRmVM：釐清 STayProvisioned 參數的文件
    * New-AzureRmDiskUpdateConfig
      * 已取代的參數 CreateOption、StorageAccountId、ImageReference、SourceUri、SourceResourceId
    * Set-AzureRmDiskUpdateImageReference：已取代的 Cmdlet
    * New-AzureRmSnapshotUpdateConfig
      * 已取代的參數 CreateOption、StorageAccountId、ImageReference、SourceUri、SourceResourceId
    * Set-AzureRmSnapshotUpdateImageReference：已取代的 Cmdlet
* DataLakeStore
    * Enable-AzureRmDataLakeStoreKeyVault (Enable-AdlStoreKeyVault)
      * 啟用 DataLake 存放區的 KeyVault 受控加密
* DevTestLabs
    * 更新 Cmdlet 以處理目前和更新的 DevTest Labs API 版本。
* IotHub
    * 新增 IoTHub Cmdlet 的路由支援
* KeyVault
  * 新的 Cmdlet，可支援 KeyVault 受控儲存體帳戶金鑰
    * Get-AzureKeyVaultManagedStorageAccount
    * Add-AzureKeyVaultManagedStorageAccount
    * Remove-AzureKeyVaultManagedStorageAccount
    * Update-AzureKeyVaultManagedStorageAccount
    * Update-AzureKeyVaultManagedStorageAccountKey
    * Get-AzureKeyVaultManagedStorageSasDefinition
    * Set-AzureKeyVaultManagedStorageSasDefinition
    * Remove-AzureKeyVaultManagedStorageSasDefinition
* 網路
    * Get-AzureRmNetworkUsage：新的 Cmdlet，可顯示網路使用量和容量詳細資料
    * 新增 VirtualNetworkGateways 的 GatewaySku 選項
        * VpnGw1、VpnGw2、VpnGw3 是針對 Vpn 閘道新增的 Sku
    * Set-AzureRmNetworkWatcherConfigFlowLog
      * 固定說明範例
* NotificationHubs
    * 針對新 API 的 NotificationHubs Cmdlet 進行透明更新
* 設定檔
    * Resolve-AzureRmError
      * 新的 Cmdlet，可顯示詳細錯誤和 Cmdlet 產生的例外狀況，包括伺服器要求/回應資料
    * Send-Feedback
      * 啟用傳送意見反應而無須登入
    * Get-AzureRmSubscription
      * 修正擷取 CSP 訂用帳戶時的錯誤
* 資源
    * 已修正問題，其中若 roleassignments 的數字大於 1000，Get-AzureRMRoleAssignment 會導致錯誤的要求
        * 現在即使要傳回的 roleassignments 大於 1000，使用者仍可使用 Get-AzureRMRoleAssignment
* Sql
    * Restore-AzureRmSqlDatabase：更新文件範例
* 儲存體
    * 在資源模式的儲存體帳戶 Cmdlet，新增 AssignIdentity 設定支援
        * New-AzureRmStorageAccount
        * Set-AzureRmStorageAccount
    * 在資源模式的儲存體帳戶 Cmdlet，新增客戶金鑰支援
        * Set-AzureRmStorageAccount
        * New-AzureRmStorageAccountEncryptionKeySource
* TrafficManager

    * 新監視器設定「MonitorIntervalInSeconds」、「MonitorTimeoutInSeconds」、「MonitorToleratedNumberOfFailures」
    * 新監視器通訊協定「TCP」
* ServiceManagement
    * Add-AzureVhd：vhd 的大小限制會增加至 4TB。
    * New-AzureBGPPeering：支援 LegacyMode
* Azure.Storage
    * 針對可接受萬用字元的參數更新說明，並更新 StorageContext 類型

## <a name="20170523---version-402"></a>2017.05.23 - 版本 4.0.2
* 設定檔
    * Add-AzureRmAccount
      * 新增 `-EnvironmentName` 參數別名，以便回溯相容於 AzureRM.profile 的 2.x 版本

## <a name="20170512---version-401"></a>2017.05.12 - 版本 4.0.1
 * 修正離線情況下 New-AzureStorageContext 的問題 (英文)：https://github.com/Azure/azure-powershell/issues/3939

## <a name="20170510---version-400"></a>2017.05.10 - 版本 4.0.0


* 此版本包含重大變更。 如需變更詳細資料和對現有指令碼的影響，請參閱[移轉指南 (英文)](https://aka.ms/azps-migration-guide)。
* ApiManagement
  - 新增在 New-AzureRmApiManagementGroup 中設定外部群組的支援。
* 計費
  - 新的 Get-AzureRmBillingPeriod Cmdlet
    + 用來擷取 Azure 訂用帳戶計費週期的 Cmdlet。
  - 更新 Get-AzureRmBillingInvoice Cmdlet
  - 新的 BillingPeriodNames 屬性
  - 在清單檢視中輸出
* 計算
  - 已更新 Set-AzureRmVMAEMExtension 和 Test-AzureRmVMAEMExtension Cmdlet，以支援進階受控磁碟
  - 適用於 IaaS VM 和失敗時還原的備份加密設定
  - ChefServiceInterval 選項現已重新命名為 ChefDaemonInterval。 但舊選項將繼續運作。
  - 移除 PS VM 物件中重複的 DataDiskNames 和 NetworkInterfaceIDs 屬性。
  - 使個別位於 Remove-AzureRmVMDataDisk 和 Remove-AzureRmVMNetworkInterface 中的 DataDiskNames 和 NetworkInterfaceIDs 參數成為選擇性。
  - 修正 Get Cmdlet 傳回清單物件時的管線問題。
  - 已重新命名和 RDFE Cmdlet 衝突的 Cmdlet。 如需詳細資料，請參閱此問題：https://github.com/Azure/azure-powershell/issues/2917
    + `New-AzureVMSqlServerAutoBackupConfig` 已重新命名為 `New-AzureRmVMSqlServerAutoBackupConfig`
    + `New-AzureVMSqlServerAutoPatchingConfig` 已重新命名為 `New-AzureRmVMSqlServerAutoPatchingConfig`
    + `New-AzureVMSqlServerKeyVaultCredentialConfig` 已重新命名為 `New-AzureRmVMSqlServerKeyVaultCredentialConfig`
* 耗用量
  - 新的 Get-AzureRmConsumptionUsageDetail Cmdlet
    + 用於擷取訂用帳戶使用量詳細資料的 Cmdlet。
* ContainerRegistry
  - 新增 Azure Container Registry 的 PowerShell Cmdlet
    + New-AzureRmContainerRegistry
    + Get-AzureRmContainerRegistry
    + Update-AzureRmContainerRegistry
    + Remove-AzureRmContainerRegistry
    + Get-AzureRmContainerRegistryCredential
    + Update-AzureRmContainerRegistryCredential
    + Test-AzureRmContainerRegistryNameAvailability
* DataLakeAnalytics
  - 新增取得和列出目錄套件的支援
  - 新增從更深層的上階列出下列目錄項目的支援：
    + 資料表
    + TVF
    + 檢視
    + 統計資料
* DataLakeStore
  - 對於 `Import-AzureRMDataLakeStoreItem` 和 `Export-AzureRMDataLakeStoreItem`，預設已停用追蹤記錄以改善效能。 如果需要追蹤記錄，請使用 `-DiagnosticLogLevel` 和 `-DiagnosticLogPath` 參數
  - 已修正將大量的小型檔案上傳到 ADLS 時偶爾會導致 PowerShell 當機的問題。
* EventHub
  - 錯誤修正：
    + 修正 Set-AzureRmEventHubNamespace Cmdlet 錯誤 - 'Tier' 不能為 Null，而必須是 'SkuName'
    + Set-AzureRmEventHub - 修正更新 EventHub 時的「物件參考未設定成物件的執行個體」錯誤
* 深入解析
  - Add-AzureRm*AlertRule
    + 傳回單一物件︰newResource、statusCode、requestId
  - Get-AzureRmAlertRule
    + 現在會對輸出進行列舉，而不是將它視為單一物件。 它的類型並未變更，仍然是清單。
  - Remove-AzureRmAlertRule
    + statusCode 會遵循要求所傳回的狀態碼，先前一律是「良好」。
  - Add-AzureRmAutoscaleSetting
    + 現在會傳回包含 statusCode、requestId，以及最近所建立/更新資源的單一物件 (而非先前的清單)。
    + 狀態碼會遵循要求所傳回的狀態，先前一律是「良好」。
  - New-AzureRmAutoscaleRule
    + 已擴充 ScaleActionType 參數，現在它會接收下列值：ChangeCount、PercentChangeCount、ExactCount。
  - Remove-AzureRmAutoscaleSetting
    + 輸出中的 statusCode 會遵循要求所傳回的 statusCode。 先前一律是「良好」。
  - Get-AzureRMLogProfile
    + 現在會對輸出進行列舉。 先前是將它視為單一物件。 輸出的類型仍為先前的清單。
  - Remove-AzureRmLogProfile
    + 已實作 PassThru 參數。
  - 計量 API
    + SDK 現在會從 MDM 擷取計量。
  - Get-AzureRmMetricDefinition
    + 輸出仍是清單，但清單的結構已變更。
  - Get-AzureRmMetric
    + 呼叫已變更。 新的語法如下：Get-AzureRmMetric ResourceId [MetricNames [TimeGrain] [AggregationType] [StartTime] [EndTime]] [DetailedOutput]
    + 輸出是清單，但其元素的結構已變更。
* KeyVault
  - 新增備份/還原 KeyVault 密碼的支援
    + 可以對密碼進行備份和還原，以符合目前對於金鑰所支援的功能

  - 金鑰和密碼的備份 Cmdlet 現在接受以對應的物件做為輸入參數
    + 呼叫端可鏈結擷取和備份作業︰Get-AzureKeyVaultKey -VaultName myVault -Name myKey | Backup-AzureKeyVaultKey

  - 備份 Cmdlet 現在支援用於覆寫現有檔案的 -Force 參數
    + 請注意，嘗試覆寫現有檔案將不再會擲回，而是改為提示使用者選擇繼續的方式。
* LogicApp
  - 交換控制編號災害復原 Cmdlet 的新參數︰
    + 用於指定相關控制編號的選擇性 -AgreementType 參數 ("X12" 或 "Edifact")
* MachineLearning
  - 使用新版的 Azure Machine Learning .Net SDK，並新增 Cmdlet
    + Add-AzureRmMlWebServiceRegionalProperty
  - 說明文字中的次要措辭修正。
* 網路
  - 已新增 Test-AzureRmNetworkWatcherConnectivity Cmdlet
    + 傳回指定來源 VM 和目的地的連線資訊
    + 如果無法建立來源與目的地之間的連線，此 Cmdlet 會傳回問題的詳細資料
* 設定檔
  - 已新增 'Send-Feedback' Cmdlet︰可讓使用者起始一組提示，以傳送意見反應給 Azure PowerShell 小組。
  - 已移除下列別名，因為它們與 Azure 模組中現有的 Cmdlet 名稱衝突︰
    + `Enable-AzureDataCollection` (受 `Enable-AzureRmDataCollection` 支援)
    + `Disable-AzureDataCollection` (受 `Disable-AzureRmDataCollection` 支援)
* 轉送
  - 新增 Azure 轉送適用的 Cmdlet，方便使用者建立和管理所有 Azure 轉送資源。
    + `New-AzureRmRelayNamespace`
    + `Get-AzureRmRelayNamespace`
    + `Set-AzureRmRelayNamespace`
    + `Remove-AzureRmRelayNamespace`
    + `New-AzureRmWcfRelay`
    + `Get-AzureRmWcfRelay`
    + `Set-AzureRmWcfRelay`
    + `Remove-AzureRmWcfRelay`
    + `New-AzureRmRelayHybridConnection`
    + `Get-AzureRmRelayHybridConnection`
    + `Set-AzureRmRelayHybridConnection`
    + `Remove-AzureRmRelayHybridConnection`
    + `Test-AzureRmRelayName`
    + `Get-AzureRmRelayOperation`
    + `New-AzureRmRelayKey`
    + `Get-AzureRmRelayKey`
    + `New-AzureRmRelayAuthorizationRule`
    + `Get-AzureRmRelayAuthorizationRule`
    + `Set-AzureRmRelayAuthorizationRule`
    + `Remove-AzureRmRelayAuthorizationRule`
* 資源
  - 支援適用於 AzureRmResourceGroupDeployment 的跨資源群組部署
    + 使用者現在可以使用巢狀部署以部署至不同的資源群組。
* ServiceBus

  - 錯誤修正：ServiceBus 佇列物件屬性值已設為 Null，該物件是做為 Set-AzureRmServiceBusQueue Cmdlet 中的輸入參數使用以更新佇列。
   - 受影響的屬性包括 LockDuration、EntityAvailabilityStatus、DuplicateDetectionHistoryTimeWindow、MaxDeliveryCount 和 MessageCount
* ServiceFabric

  - 已新增適用於 Service Fabric 的 Cmdlet
    + Add-AzureRmServiceFabricApplicationCertificate       新增將做為應用程式憑證使用的憑證
    + Add-AzureRmServiceFabricClientCertificate       在叢集設定新增用於用戶端驗證的一般名稱或指紋
    + Add-AzureRmServiceFabricClusterCertificate       在叢集新增次要叢集憑證以更換現有的憑證
    + Add-AzureRmServiceFabricNodes       在叢集新增特定節點類型的節點/VM
    + Add-AzureRmServiceFabricNodeType       在現有叢集新增節點類型/VM
    + Get-AzureRmServiceFabricCluster       取得叢集資源的詳細資料
    + New-AzureRmServiceFabricCluster 建立新的 ServiceFabric 叢集。 此命令有許多的多載，可涵蓋各種案例
    + Remove-AzureRmServiceFabricClientCertificate       移除某個用戶端憑證以防止將它用於存取叢集
    + Remove-AzureRmServiceFabricClusterCertificate       移除某個用戶端憑證以防止將它用於叢集安全性
    + Remove-AzureRmServiceFabricNodes       自叢集中移除特定節點類型的節點
    + Remove-AzureRmServiceFabricNodeType       自叢集中移除某個節點類型
    + Remove-AzureRmServiceFabricSettings       自叢集中移除一或多個 ServiceFabric 設定
    + Set-AzureRmServiceFabricSettings       新增或更新叢集的一或多個 ServiceFabric 設定
    + Set-AzureRmServiceFabricUpgradeType       變更叢集的 ServiceFabric 升級類型
    + Update-AzureRmServiceFabricDurability       變更叢集的持久性層
    + Update-AzureRmServiceFabricReliability       變更叢集的可靠性層
* Sql
  - 已將 -SampleName 參數新增至 New-AzureRmSqlDatabase
  - 更新容錯移轉群組 Cmdlet
  - 移除 'Tag' 參數
  - 從 Remove-AzureRmSqlDatabaseFailoverGroup Cmdlet 中移除 'PartnerResourceGroupName' 和 'PartnerServerName' 參數
  - 將 'GracePeriodWithDataLossHours' 參數新增至 New- 和 Set- Cmdlet，此參數最終會取代 'GracePeriodWithDataLossHour'
  - 文件已增補並更新
  - 變更傳回物件的格式，並修正欄位有時不會填入的錯誤
  - 將 'DatabaseNames' 和 'PartnerLocation' 屬性新增至容錯移轉群組物件
  - 修正造成 Switch- Cmdlet 立即傳回 (而非等待作業完成後再傳回) 的錯誤
  - 修正使用高寬限期值時的整數溢位錯誤
  - 在提供的值比 1 小時的下限還要低的情況下，將寬限期調整為 1 小時
  - 從 Set-AzureRmSqlDatabaseThreatDetectionPolicy Cmdlet 和 Set-AzureRmSqlServerThreatDetectionPolicy Cmdlet 之 "ExcludedDetectionType" 參數的可接受值中移除 "Usage_Anomaly"。
* 儲存體
  - 將 SRP SDK 升級至 6.3.0
  - New/Set-AzureRmStorageAccount：新增參數以支援 EnableHttpsTrafficOnly
  - New/Set/Get-AzureRmStorageAccount：傳回的儲存體帳戶包含新的 EnableHttpsTrafficOnly 屬性
* Azure.Storage
  - 升級至 Azure 儲存體用戶端程式庫 8.1.1 及 Azure 儲存體資料移動程式庫 0.5.1
  - 新增 Cmdlet 以支援 Blob 增量複製功能
