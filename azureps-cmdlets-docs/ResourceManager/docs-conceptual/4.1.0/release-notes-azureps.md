---
title: "Azure PowerShell 變更記錄 | Microsoft Docs"
description: "這是在最新版中對 Azure powershell 所做的變更歷程記錄。"
services: azure
author: sdwheeler
ms.author: sewhee
manager: carmonm
ms.service: azure-resource-manager
ms.product: azure
ms.devlang: powershell
ms.topic: conceptual
ms.workload: 
ms.date: 05/18/2017
ms.openlocfilehash: 5c8fa2a5a8f94cd24b66f42c237749a7b89af3b3
ms.sourcegitcommit: ec0b3565264ff7c9f03315ded182f3d5cce534fc
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/13/2017
---
# <a name="release-notes"></a>版本資訊

這是此版本中對 Azure PowerShell 所做的變更清單。

## <a name="version-400"></a>4.0.0 版

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
