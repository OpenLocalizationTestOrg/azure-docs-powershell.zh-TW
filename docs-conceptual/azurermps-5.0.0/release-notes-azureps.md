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
ms.date: 11/14/2017
ms.openlocfilehash: ab35cbc4ec1a0bd4e7ee40e1864bd7941f5bca87
ms.sourcegitcommit: 79dd3700b5cb4cb90b268778b482082052160093
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 11/14/2017
---
# <a name="release-notes"></a>版本資訊

這是此版本中對 Azure PowerShell 所做的變更清單。

## <a name="20171110-version-501"></a>2017.11.10 版本 5.0.1
* 固定組件載入問題造成在下列模組中執行 Cmdlet 時失敗：
    - AzureRM.ApiManagement
    - AzureRM.Backup
    - AzureRM.Batch
    - AzureRM.Compute
    - AzureRM.DataFactories
    - AzureRM.HDInsight
    - AzureRM.KeyVault
    - AzureRM.RecoveryServices
    - AzureRM.RecoveryServices.Backup
    - AzureRM.RecoveryServices.SiteRecovery
    - AzureRM.RedisCache
    - AzureRM.SiteRecovery
    - AzureRM.Sql
    - AzureRM.Storage
    - AzureRM.StreamAnalytics

## <a name="2017118---version-500"></a>2017.11.8 - 版本 5.0.0
* 注意：這是重大變更版本。 有關導入的重大變更完整清單，請參閱移轉指南 (https://aka.ms/azps-migration-guide)。
* AzureRM 中所有的 Cmdlet 現在都支援線上說明
    - 執行 Get-Help 搭配 -Online 參數，以在您的預設網際網路瀏覽器中開啟線上說明
* AnalysisServices
    * 固定的 Synchronize-AzureAsInstance 命令搭配使用新 AsAzure REST API 以進行同步處理
* ApiManagement
    * 有關 ApiManagement 在這一版所做的重大變更，請參閱移轉指南
    * 更新 Cmdlet Get-AzureRmApiManagementUser 以修正問題 https://github.com/Azure/azure-powershell/issues/4510
    * 更新 Cmdlet New-AzureRmApiManagementApi 以建立具空白路徑的 API https://github.com/Azure/azure-powershell/issues/4069
* ApplicationInsights
    * 新增命令以取得/建立/移除應用程式深入解析資源
        - Get-AzureRmApplicationInsights
        - New-AzureRmApplicationInsights
        - Remove-AzureRmApplicationInsights
    * 新增命令以取得/更新價格/應用程式深入解析資源的每日上限
        - Get-AzureRmApplicationInsights -IncludeDailyCap
        - Set-AzureRmApplicationInsightsPricingPlan
        - Set-AzureRmApplicationInsightsDailyCap
    * 新增命令以取得/建立/更新/移除應用程式深入解析資源的連續匯出
        - Get-AzureRmApplicationInsightsContinuousExport
        - Set-AzureRmApplicationInsightsContinuousExport
        - New-AzureRmApplicationInsightsContinuousExport
        - Remove-AzureRmApplicationInsightsContinuousExport
    * 新增命令以取得/建立/移除應用程式深入解析資源的 API 金鑰
        - Get-AzureRmApplicationInsightsApiKey
        - New-AzureRmApplicationInsightsApiKey
        - Remove-AzureRmApplicationInsightsApiKey
* AzureBatch
    * 將新參數新增至 `New-AzureRmBatchAccount`。
        - `PoolAllocationMode`：在 Batch 帳戶中建立集區所使用的配置模式。 若要在使用者的訂用帳戶中建立配置集區節點的 Batch 帳戶，請將此設為 `UserSubscription`。
        - `KeyVaultId`：與 Batch 帳戶相關的 Azure 金鑰保存庫之資源識別碼。
        - `KeyVaultUrl`：與 Batch 帳戶相關的 Azure 金鑰保存庫之 URL。
    * 將參數更新為 `New-AzureBatchTask`。
        - 移除 `RunElevated` 參數。 已新增 `UserIdentity` 參數來取代 `RunElevated`，且對等的行為可藉由建構 `PSUserIdentity` 來達成，如下所示：
            - $autoUser = New-Object Microsoft.Azure.Commands.Batch.Models.PSAutoUserSpecification -ArgumentList @("Task", "Admin")
            - $userIdentity = New-Object Microsoft.Azure.Commands.Batch.Models.PSUserIdentity $autoUser
        - 新增 `AuthenticationTokenSettings` 參數。 這個參數可讓您要求 Batch 服務在執行時向工作提供驗證權杖，而不必先將 Batch 帳戶金鑰傳遞至工作，才能對 Batch 服務發出要求。
        - 新增 `ContainerSettings` 參數。
            - 這個參數可讓您要求 Batch 服務在容器內執行工作。
        - 新增 `OutputFiles` 參數。
            - 這個參數可讓您設定在工作完成之後將檔案上傳至 Azure 儲存體。
    * 將參數更新為 `New-AzureBatchPool`。
        - 新增 `UserAccounts` 參數。
            - 這個參數可定義集區中每個節點上所建立的使用者帳戶。
        - 新增 `TargetLowPriorityComputeNodes` 並將 `TargetDedicated` 重新命名為 `TargetDedicatedComputeNodes`。
            - 針對 `TargetDedicatedComputeNodes` 參數已建立 `TargetDedicated` 別名。
        - 新增 `NetworkConfiguration` 參數。
            - 這個參數可讓您設定集區的網路設定。
    * 將參數更新為 `New-AzureBatchCertificate`。
        - `Password` 參數現在是 `SecureString`。
    * 將參數更新為 `New-AzureBatchComputeNodeUser`。
        - `Password` 參數現在是 `SecureString`。
    * 將參數更新為 `Set-AzureBatchComputeNodeUser`。
        - `Password` 參數現在是 `SecureString`。
    * 在 `Get-AzureBatchNodeFile`、`Get-AzureBatchNodeFileContent` 和 `Remove-AzureBatchNodeFile` 上將 `Name` 參數重新命名為 `Path`。
        - 針對 `Path` 參數已建立 `Name` 別名。
    * 物件的變更
        - 請參閱 Batch 變更記錄取得完整清單
    * 新增 Azure Active Directory 型驗證支援。
        - 若要使用 Azure Active Directory 驗證，請使用 `Get-AzureRmBatchAccount` Cmdlet 擷取 `BatchAccountContext` 物件，並將此 `BatchAccountContext` 提供至 Batch 服務 Cmdlet 的 `-BatchContext` 參數。 對於具有 `PoolAllocationMode = UserSubscription` 的帳戶，Azure Active Directory 驗證為必要。
        - 對於現有帳戶或以 `PoolAllocationMode = BatchService` 建立的新帳戶，您可以藉由使用 `Get-AzureRmBatchAccoutKeys` Cmdlet 擷取 `BatchAccountContext` 物件，繼續使用共用金鑰驗證。
* 計算
    * Azure 磁碟加密延伸模組命令
        - 'Set-AzureRmVmDiskEncryptionExtension' 的新參數：'-EncryptFormatAll' 加密格式資料磁碟
        - 'Set-AzureRmVmDiskEncryptionExtension' 的新參數：'-ExtensionPublisherName' 和 '-ExtensionType' 允許切換至延伸模組的其他版本
        - 'Disable-AzureRmVmDiskEncryption' 的新參數：'-ExtensionPublisherName' 和 '-ExtensionType' 允許切換至延伸模組的其他版本
        - 'Get-AzureRmVmDiskEncryptionStatus' 的新參數：'-ExtensionPublisherName' 和 '-ExtensionType' 允許切換至延伸模組的其他版本
* DataLakeAnalytics
    * 有關 DataLakeAnalytics 在這一版所做的重大變更，請參閱移轉指南
    * 變更 Get-AzureRmDataLakeAnalyticsAccount 兩種 OutputTypes 的其中一種
        - List\<DataLakeAnalyticsAccount> 到 List\<PSDataLakeAnalyticsAccountBasic>
        - PSDataLakeAnalyticsAccountBasic 的屬性是 DataLakeAnalyticsAccount 屬性的 strict 子集
        - 服務不會傳回 DataLakeAnalyticsAccount 中的其他屬性。  因此，這項變更是為了準確反映此情況。 這些額外屬性仍然在 PSDataLakeAnalyticsAccountBasic 中，但被標記為 [已淘汰]。
    * 變更 Get-AzureRmDataLakeAnalyticsJob 兩種 OutputTypes 的其中一種
        - List\<JobInformation> 到 List\<PSJobInformationBasic>
        - PSJobInformationBasic 的屬性是 JobInformation 屬性的 strict 子集
        - 服務不會傳回 JobInformation 中的其他屬性。  因此，這項變更是為了準確反映此情況。 這些額外屬性仍然在 PSJobInformationBasic 中，但被標記為 [已淘汰]。
* DataLakeStore
    * 有關 DataLakeStore 在這一版所做的重大變更，請參閱移轉指南
    * 變更 Get-AzureRmDataLakeStoreAccount 兩種 OutputTypes 的其中一種
        - List\<PSDataLakeStoreAccount> 到 List\<PSDataLakeStoreAccountBasic>
        - PSDataLakeStoreAccountBasic 的屬性是 PSDataLakeStoreAccount 屬性的 strict 子集
        - 服務不會傳回 PSDataLakeStoreAccount 中的其他屬性。  因此，這項變更是為了準確反映此情況。 這些額外屬性仍然在 PSDataLakeStoreAccountBasic 中，但被標記為 [已淘汰]。
* Dns
    * Azure DNS 中 CAA 記錄型別的支援
       - 支援 CAA 記錄型別上的所有作業
* EventHub
    * 有關 EventHub 在這一版所做的重大變更，請參閱移轉指南
* 深入解析
    * 有關深入解析在這一版所做的重大變更，請參閱移轉指南
* 網路
    * 有關網路在這一版所做的重大變更，請參閱移轉指南
    * 新增 Cmdlet 以針對指定的 Azure 區域列出可用的網際網路服務提供者
        - Get-AzureRmNetworkWatcherReachabilityProvidersList
    * 新增 Cmdlet 以取得從指定位置到 Azure 區域的網際網路服務提供者相對延遲分數
        - Get-AzureRmNetworkWatcherReachabilityReport
* 設定檔
    - Set-AzureRmDefault
        - 使用這個 Cmdlet 設定預設的資源群組。  對於某些 Cmdlet，這會讓 -ResourceGroup 參數成為選用，且在未指定資源群組時將使用預設值
        - ```Set-AzureRmDefault -ResourceGroupName "ExampleResourceGroup"```
        - 如果指定的資源群組存在於訂用帳戶中，則此資源群組將會設為預設值。  否則，將會建立該資源群組，並將其設為預設值。
    - Get-AzureRmDefault
        - 使用這個 Cmdlet 取得目前預設的資源群組 (和未來其他的預設)。
        - ```Get-AzureRmDefault -ResourceGroup```
    - Clear-AzureRmDefault
        - 使用這個 Cmdlet 移除目前預設的資源群組
        - ```Clear-AzureRmDefault -ResourceGroup```
    - Add-AzureRmEnvironment 和 Set-AzureRmEnvironment
        - 新增 BatchAudience 參數，可讓您指定在取得 Batch 服務驗證權杖時所要使用的 Azure Batch Active Directory 對象。
* RecoveryServices.Backup
    * 新增 Cmdlet 以執行立即檔案復原。
        - Get-AzureRmRecoveryServicesBackupRPMountScript
        - Disable-AzureRmRecoveryServicesBackupRPMountScript
    * 將 RecoveryServices.Backup SDK 更新至最新版本
    * 更新 Azure VM 工作負載的測試，如此一來測試回合所需的所有設定便由測試本身完成。
    * 修正 https://github.com/Azure/azure-powershell/issues/3164
* RecoveryServices.SiteRecovery
    * ASR VMware 到 Azure Site Recovery 的變更 (Cmdlet 目前支援企業到企業、企業到 Azure、HyperV 到 Azure 的作業)
        - New-AzureRmRecoveryServicesAsrPolicy
        - New-AzureRmRecoveryServicesAsrProtectedItem
        - Update-AzureRmRecoveryServicesAsrPolicy
        - Update-AzureRmRecoveryServicesAsrProtectionDirection
    * 新增以 AAD 為基礎的保存庫支援
    * 新增 Cmdlet 以管理 VCenter 資源
        - Get-AzureRmRecoveryServicesAsrVCenter
        - New-AzureRmRecoveryServicesAsrVCenter
        - Remove-AzureRmRecoveryServicesAsrVCenter
        - Update-AzureRmRecoveryServicesAsrVCenter
    * 新增其他 Cmdlet
        - Get-AzureRmRecoveryServicesAsrAlertSetting
        - Get-AzureRmRecoveryServicesAsrEvent
        - New-AzureRmRecoveryServicesAsrProtectableItem
        - Set-AzureRmRecoveryServicesAsrAlertSetting
        - Start-AzureRmRecoveryServicesAsrResynchronizeReplicationJob
        - Start-AzureRmRecoveryServicesAsrSwitchProcessServerJob
        - Start-AzureRmRecoveryServicesAsrTestFailoverCleanupJob
        - Update-AzureRmRecoveryServicesAsrMobilityService
* ServiceBus
    - 有關 ServiceBus 在這一版所做的重大變更，請參閱移轉指南
* Sql
    * 新增對列出和取消資料庫上非同步 updateslo 作業的支援
        - 更新現有的 Cmdlet Get-AzureRmSqlDatabaseActivity 以傳回 DB updateslo 作業狀態。
        - 新增新的 Cmdlet Stop-AzureRmSqlDatabaseActivity 以取消資料庫上的非同步 updateslo 作業。
    * 新增對資料庫和彈性集區的區域備援支援
        - 將 ZoneRedundant 切換參數新增至 New-AzureRmSqlDatabase
        - 將 ZoneRedundant 切換參數新增至 Set-AzureRmSqlDatabase
        - 將 ZoneRedundant 切換參數新增至 New-AzureRmSqlElasticPool
        - 將 ZoneRedundant 切換參數新增至 Set-AzureRmSqlElasticPool
    * 新增對伺服器 DNS 別名的支援
        - 新增 Get-AzureRmSqlServerDnsAlias Cmdlet，其可按照伺服器和別名名稱取得伺服器 dns 別名，或 Azure Sql Server 的伺服器 dns 別名清單。
        - 新增 New-AzureRmSqlServerDnsAlias Cmdlet，其可建立指定的 Azure Sql 伺服器的新伺服器 dns 別名
        - 新增 Set-AzurermSqlServerDnsAlias Cmdlet，其可讓伺服器 dns 別名指向的 Azure Sql Server 進行更新
        - 新增 Remove-AzureRmSqlServerDnsAlias Cmdlet，其可移除 Azure Sql 伺服器的伺服器 dns 別名
* Azure.Storage
    * 升級至 Azure 儲存體用戶端程式庫 8.5.0 及 Azure 儲存體資料移動程式庫 0.6.3
    * 新增檔案共用快照集支援功能
        - 將 'SnapshotTime' 參數新增至 Get-AzureStorageShare
        - 將 'IncludeAllSnapshot' 參數新增至 Remove-AzureStorageShare