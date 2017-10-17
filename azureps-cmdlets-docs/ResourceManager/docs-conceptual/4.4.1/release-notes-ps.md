Azure PowerShell 4.3.1 安裝程式：[連結](https://github.com/Azure/azure-powershell/releases/download/v4.3.1-August2017/azure-powershell.4.3.1.msi)

適用於 ARM Cmdlet 的資源庫模組：[連結](https://www.powershellgallery.com/packages/AzureRM/4.3.1)

適用於服務管理 (RDFE) 舊版 Cmdlet 的資源庫模組：[連結](https://www.powershellgallery.com/packages/Azure/4.3.1)

## <a name="changes-in-431"></a>4.3.1 的變更

- 修正了因為未簽署某些組件，而導致匯入模組時發生的 `could not load file or assembly` 錯誤

## <a name="changes-in-430"></a>4.3.0 的變更

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
    * 支援在 StartAzureAutomationDscCompilationJob 與 ImportAzureAutomationDscNodeConfiguration 中新增的 NodeConfiguration 組建版本設定。
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
    * 更新了新參數與參數別名可用的 Commandlet
        - 以下 Cmdlet 更新了命名空間與 EventHub 的參數集，以執行 AuthorizationRule 作業
        - New-AzureRmEventHubAuthorizationRule
            + 將新的 AuthorizationRule 新增至現有的命名空間或 EventHub。
        - Get-AzureRmEventHubAuthorizationRule
            + 取得現有命名空間或 EventHub 的 AuthorizationRule/AuthorizationRule 清單。
        - Set-AzureRmEventHubAuthorizationRule
            + 更新 EventHub 或命名空間現有 AuthorizationRule 的屬性。
        - Remove-AzureRmEventHubAuthorizationRule
            + 刪除現有命名空間或 EventHub 的現有 AuthorizationRule。
        - New-AzureRmEventHubKey
            + 為現有命名空間或 EventHub 的 AuthorizationRule 產生新的主要/次要索引鍵。
        - Get-AzureRmEventHubKey
            + 為現有命名空間或 EventHub 的 AuthorizationRule 取得主要/次要索引鍵。
* 網路
    * New-AzureRmExpressRouteCircuitPeeringConfig：新增 IPv6 支援。 新增了新的選擇性參數
        - PeerAddressType
    * Set-AzureRmExpressRouteCircuitPeeringConfig：新增了 IPv6 支援。 新增了新的選擇性參數
        - PeerAddressType
    * Remove-AzureRmExpressRouteCircuitPeeringConfig：新增了 IPv6 支援。 新增了新的選擇性參數
        - PeerAddressType
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
     - New-AzureRmServiceBusAuthorizationRule
       - 將新的 AuthorizationRule 新增至現有的 ServiceBus 命名空間/佇列/主題。
     - Get-AzureRmServiceBusAuthorizationRule
       - 取得現有 ServiceBus 命名空間/佇列/主題的AuthorizationRule/AuthorizationRule 清單。
     - Set-AzureRmServiceBusAuthorizationRule
       - 更新 Servicebus 命名空間/佇列/主題現有 AuthorizationRule 的屬性。
     - New-AzureRmServiceBusKey
       - 為現有 ServiceBus 命名空間/佇列/主題的 AuthorizationRule 產生新的主要/次要索引鍵。
     - Get-AzureRmServiceBusKey
       - 為現有 ServiceBus 命名空間/佇列/主題的 AuthorizationRule 取得主要/次要索引鍵。
     - Remove-AzureRmServiceBusNamespaceAuthorizationRule
       - 刪除 ServiceBus 命名空間/佇列/主題的現有 AuthorizationRule。
    * 新增了資源群組屬性至 NamespceAttributes
* Sql
    * 更新 Set-AzureRmSqlServerTransparentDataEncryptionProtector，以在加密保護裝置類型設為 AzureKeyVault 時，顯示警告並要求確認
    * 為稽核設定新增更新的 Cmdlet
        - 新增 Get-AzureRmSqlDatabaseAuditing Cmdlet，此 Cmdlet 可取得 Azure SQL 資料庫的稽核設定。
        - 新增 Get-AzureRmSqlServerAuditing Cmdlet，此 Cmdlet 可取得 Azure SQL 伺服器的稽核設定。
        - 新增 Set-AzureRmSqlDatabaseAuditing Cmdlet，此 Cmdlet 可變更 Azure SQL 資料庫的稽核設定。
        - 新增 Set-AzureRmSqlServerAuditing Cmdlet，此 Cmdlet 可變更 Azure SQL 伺服器的稽核設定。
    * 淘汰現有的稽核原則 Cmdlet
        - 淘汰 Get-AzureRmSqlDatabaseAuditingPolicy
        - 淘汰 Get-AzureRmSqlServerAuditingPolicy
        - 淘汰 Set-AzureRmSqlDatabaseAuditingPolicy
        - 淘汰 Set-AzureRmSqlServerAuditingPolicy
        - 淘汰 Use-AzureRmSqlServerAuditingPolicy
        - 淘汰 Remove-AzureRmSqlDatabaseAuditing
        - 淘汰 Remove-AzureRmSqlServerAuditing
    * Update-AzureRmSqlSyncGroup 的結構描述檔案剖析現在不區分大小寫。
* 儲存體
    * 為資源模式儲存體帳戶 Cmdlet 新增 NeworkRule 支援
        - New-AzureRmStorageAccount
        - Set-AzureRmStorageAccount
        - Get-AzureRmStorageAccountNetworkRuleSet
        - Update-AzureRmStorageAccountNetworkRuleSet
        - Add-AzureRmStorageAccountNetworkRule
        - Remove-AzureRmStorageAccountNetworkRule

檢視[自上次發行後的變更](https://github.com/Azure/azure-powershell/compare/v4.2.1-July2017...v4.3.1-August2017)
