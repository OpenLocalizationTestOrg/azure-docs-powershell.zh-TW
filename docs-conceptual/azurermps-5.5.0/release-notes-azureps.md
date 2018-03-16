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
ms.date: 2/20/2018
ms.openlocfilehash: 61306d057c81f533267a452f7a7e11b839b09718
ms.sourcegitcommit: 20af779cd523c758d40e23d60eb989a4ef982d5c
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 03/15/2018
---
# <a name="release-notes"></a><span data-ttu-id="7f689-103">版本資訊</span><span class="sxs-lookup"><span data-stu-id="7f689-103">Release notes</span></span>

<span data-ttu-id="7f689-104">這是此版本中對 Azure PowerShell 所做的變更清單。</span><span class="sxs-lookup"><span data-stu-id="7f689-104">This is a list of changes made to Azure PowerShell in this release.</span></span>

---

## <a name="550---march-2018"></a><span data-ttu-id="7f689-105">5.5.0 - 2018 年 3 月</span><span class="sxs-lookup"><span data-stu-id="7f689-105">5.5.0 - March 2018</span></span>
#### <a name="azurermprofile"></a><span data-ttu-id="7f689-106">AzureRM.Profile</span><span class="sxs-lookup"><span data-stu-id="7f689-106">AzureRM.Profile</span></span>
* <span data-ttu-id="7f689-107">已修正匯入別名的問題</span><span class="sxs-lookup"><span data-stu-id="7f689-107">Fixed issue with importing aliases</span></span>
* <span data-ttu-id="7f689-108">與版本 6.0.8 並行載入 Newtonsoft.Json 版本 10.0.3</span><span class="sxs-lookup"><span data-stu-id="7f689-108">Load version 10.0.3 of Newtonsoft.Json side-by-side with version 6.0.8</span></span>

#### <a name="azurestorage"></a><span data-ttu-id="7f689-109">Azure.Storage</span><span class="sxs-lookup"><span data-stu-id="7f689-109">Azure.Storage</span></span>
* <span data-ttu-id="7f689-110">支援虛刪除功能</span><span class="sxs-lookup"><span data-stu-id="7f689-110">Support Soft-Delete feature</span></span>
    - <span data-ttu-id="7f689-111">Enable-AzureStorageDeleteRetentionPolicy</span><span class="sxs-lookup"><span data-stu-id="7f689-111">Enable-AzureStorageDeleteRetentionPolicy</span></span>
    - <span data-ttu-id="7f689-112">Disable-AzureStorageDeleteRetentionPolicy</span><span class="sxs-lookup"><span data-stu-id="7f689-112">Disable-AzureStorageDeleteRetentionPolicy</span></span>
    - <span data-ttu-id="7f689-113">Get-AzureStorageBlob</span><span class="sxs-lookup"><span data-stu-id="7f689-113">Get-AzureStorageBlob</span></span>

#### <a name="azurermanalysisservices"></a><span data-ttu-id="7f689-114">AzureRM.AnalysisServices</span><span class="sxs-lookup"><span data-stu-id="7f689-114">AzureRM.AnalysisServices</span></span>
* <span data-ttu-id="7f689-115">已修正匯入別名的問題</span><span class="sxs-lookup"><span data-stu-id="7f689-115">Fixed issue with importing aliases</span></span>
* <span data-ttu-id="7f689-116">新增防火牆和查詢向外延展功能的支援，並支援 2017-08-01 API 版本。</span><span class="sxs-lookup"><span data-stu-id="7f689-116">Add support of firewall and query scaleout feature, as well as support of 2017-08-01 api version.</span></span>

#### <a name="azurermautomation"></a><span data-ttu-id="7f689-117">AzureRM.Automation</span><span class="sxs-lookup"><span data-stu-id="7f689-117">AzureRM.Automation</span></span>
* <span data-ttu-id="7f689-118">已修正匯入別名的問題</span><span class="sxs-lookup"><span data-stu-id="7f689-118">Fixed issue with importing aliases</span></span>

#### <a name="azurermcdn"></a><span data-ttu-id="7f689-119">AzureRM.Cdn</span><span class="sxs-lookup"><span data-stu-id="7f689-119">AzureRM.Cdn</span></span>
* <span data-ttu-id="7f689-120">已修正匯入別名的問題</span><span class="sxs-lookup"><span data-stu-id="7f689-120">Fixed issue with importing aliases</span></span>

#### <a name="azurermcognitiveservices"></a><span data-ttu-id="7f689-121">AzureRM.CognitiveServices</span><span class="sxs-lookup"><span data-stu-id="7f689-121">AzureRM.CognitiveServices</span></span>
* <span data-ttu-id="7f689-122">更新 notice.txt 和通知訊息。</span><span class="sxs-lookup"><span data-stu-id="7f689-122">Update notice.txt and notice message.</span></span>

#### <a name="azurermcompute"></a><span data-ttu-id="7f689-123">AzureRM.Compute</span><span class="sxs-lookup"><span data-stu-id="7f689-123">AzureRM.Compute</span></span>
* <span data-ttu-id="7f689-124">'New-AzureRmVMSS' 在詳細資訊模式中列印連接字串。</span><span class="sxs-lookup"><span data-stu-id="7f689-124">'New-AzureRmVMSS' prints connection strings in verbose mode.</span></span>
* <span data-ttu-id="7f689-125">'New-AzureRmVmss' 支援公用 IP 位址、載入平衡規則、傳入的 NAT 規則。</span><span class="sxs-lookup"><span data-stu-id="7f689-125">'New-AzureRmVmss' supports public IP address, load balancing rules, inbound NAT rules.</span></span>
* <span data-ttu-id="7f689-126">WriteAccelerator 功能</span><span class="sxs-lookup"><span data-stu-id="7f689-126">WriteAccelerator feature</span></span>
    - <span data-ttu-id="7f689-127">已將 WriteAccelerator 切換參數新增至下列 Cmdlet：Set-AzureRmVMOSDisk Set-AzureRmVMDataDisk Add-AzureRmVMDataDisk Add-AzureRmVmssDataDisk</span><span class="sxs-lookup"><span data-stu-id="7f689-127">Added WriteAccelerator switch parameter to the following cmdlets: Set-AzureRmVMOSDisk Set-AzureRmVMDataDisk Add-AzureRmVMDataDisk Add-AzureRmVmssDataDisk</span></span>
    - <span data-ttu-id="7f689-128">已將 OsDiskWriteAccelerator 切換參數新增至下列 Cmdlet：Set-AzureRmVmssStorageProfile。</span><span class="sxs-lookup"><span data-stu-id="7f689-128">Added OsDiskWriteAccelerator switch parameter to the following cmdlet:     Set-AzureRmVmssStorageProfile.</span></span>
    - <span data-ttu-id="7f689-129">已將 OsDiskWriteAccelerator 布林值參數新增至下列 Cdlets：Update-AzureRmVM     Update-AzureRmVmss</span><span class="sxs-lookup"><span data-stu-id="7f689-129">Added OsDiskWriteAccelerator Boolean parameter to the following cmdlets:     Update-AzureRmVM     Update-AzureRmVmss</span></span>

#### <a name="azurermdatafactories"></a><span data-ttu-id="7f689-130">AzureRM.DataFactories</span><span class="sxs-lookup"><span data-stu-id="7f689-130">AzureRM.DataFactories</span></span>
* <span data-ttu-id="7f689-131">修正會造成部分加密作業生產無意義錯誤的認證加密問題</span><span class="sxs-lookup"><span data-stu-id="7f689-131">Fix credential encryption issue that caused no meaningful error for some encryption operations</span></span>
* <span data-ttu-id="7f689-132">啟用要在資料處理站間共用的整合執行階段</span><span class="sxs-lookup"><span data-stu-id="7f689-132">Enable integration runtime to be shared across data factory</span></span>

#### <a name="azurermdatafactoryv2"></a><span data-ttu-id="7f689-133">AzureRM.DataFactoryV2</span><span class="sxs-lookup"><span data-stu-id="7f689-133">AzureRM.DataFactoryV2</span></span>
* <span data-ttu-id="7f689-134">為 "Set-AzureRmDataFactoryV2IntegrationRuntime" cmd 新增參數 "SetupScriptContainerSasUri" 和 "Edition"，以啟用自訂設定和編輯選項功能</span><span class="sxs-lookup"><span data-stu-id="7f689-134">Add parameter "SetupScriptContainerSasUri" and "Edition" for "Set-AzureRmDataFactoryV2IntegrationRuntime" cmd to enable custom setup and edition selection functionality</span></span>
* <span data-ttu-id="7f689-135">修正會造成部分加密作業生產無意義錯誤的認證加密問題。</span><span class="sxs-lookup"><span data-stu-id="7f689-135">Fix credential encryption issue that caused no meaningful error for some encryption operations.</span></span>
* <span data-ttu-id="7f689-136">啟用要在資料處理站間共用的整合執行階段</span><span class="sxs-lookup"><span data-stu-id="7f689-136">Enable integration runtime to be shared across data factory</span></span>

#### <a name="azurermhdinsight"></a><span data-ttu-id="7f689-137">AzureRM.HDInsight</span><span class="sxs-lookup"><span data-stu-id="7f689-137">AzureRM.HDInsight</span></span>
* <span data-ttu-id="7f689-138">已修正匯入別名的問題</span><span class="sxs-lookup"><span data-stu-id="7f689-138">Fixed issue with importing aliases</span></span>

#### <a name="azurermkeyvault"></a><span data-ttu-id="7f689-139">AzureRM.KeyVault</span><span class="sxs-lookup"><span data-stu-id="7f689-139">AzureRM.KeyVault</span></span>
* <span data-ttu-id="7f689-140">已修正 Set-AzureRmKeyVaultAccessPolicy 範例</span><span class="sxs-lookup"><span data-stu-id="7f689-140">Fixed example for Set-AzureRmKeyVaultAccessPolicy</span></span>

#### <a name="azurermnetwork"></a><span data-ttu-id="7f689-141">AzureRM.Network</span><span class="sxs-lookup"><span data-stu-id="7f689-141">AzureRM.Network</span></span>
* <span data-ttu-id="7f689-142">已修正匯入別名的問題</span><span class="sxs-lookup"><span data-stu-id="7f689-142">Fixed issue with importing aliases</span></span>

#### <a name="azurermoperationalinsights"></a><span data-ttu-id="7f689-143">AzureRM.OperationalInsights</span><span class="sxs-lookup"><span data-stu-id="7f689-143">AzureRM.OperationalInsights</span></span>
* <span data-ttu-id="7f689-144">已修正匯入別名的問題</span><span class="sxs-lookup"><span data-stu-id="7f689-144">Fixed issue with importing aliases</span></span>

#### <a name="azurermrecoveryservices"></a><span data-ttu-id="7f689-145">AzureRM.RecoveryServices</span><span class="sxs-lookup"><span data-stu-id="7f689-145">AzureRM.RecoveryServices</span></span>
* <span data-ttu-id="7f689-146">已修正匯入別名的問題</span><span class="sxs-lookup"><span data-stu-id="7f689-146">Fixed issue with importing aliases</span></span>

#### <a name="azurermrecoveryservicessiterecovery"></a><span data-ttu-id="7f689-147">AzureRM.RecoveryServices.SiteRecovery</span><span class="sxs-lookup"><span data-stu-id="7f689-147">AzureRM.RecoveryServices.SiteRecovery</span></span>
* <span data-ttu-id="7f689-148">已修正匯入別名的問題</span><span class="sxs-lookup"><span data-stu-id="7f689-148">Fixed issue with importing aliases</span></span>

#### <a name="azurermresources"></a><span data-ttu-id="7f689-149">AzureRM.Resources</span><span class="sxs-lookup"><span data-stu-id="7f689-149">AzureRM.Resources</span></span>
* <span data-ttu-id="7f689-150">已修正匯入別名的問題</span><span class="sxs-lookup"><span data-stu-id="7f689-150">Fixed issue with importing aliases</span></span>

#### <a name="azurermservicebus"></a><span data-ttu-id="7f689-151">AzureRM.ServiceBus</span><span class="sxs-lookup"><span data-stu-id="7f689-151">AzureRM.ServiceBus</span></span>
* <span data-ttu-id="7f689-152">已將 EnableBatchedOperations 屬性新增至佇列</span><span class="sxs-lookup"><span data-stu-id="7f689-152">Added EnableBatchedOperations property to Queue</span></span>
* <span data-ttu-id="7f689-153">已將 DeadLetteringOnFilterEvaluationExceptions 屬性新增至訂用帳戶</span><span class="sxs-lookup"><span data-stu-id="7f689-153">Added DeadLetteringOnFilterEvaluationExceptions property to Subscriptions</span></span>

#### <a name="azurermservicefabric"></a><span data-ttu-id="7f689-154">AzureRM.ServiceFabric</span><span class="sxs-lookup"><span data-stu-id="7f689-154">AzureRM.ServiceFabric</span></span>
* <span data-ttu-id="7f689-155">Service Fabric Cmdlet 重新整理</span><span class="sxs-lookup"><span data-stu-id="7f689-155">Service Fabric cmdlet refresh</span></span>
  - <span data-ttu-id="7f689-156">已更新 ARM 範本</span><span class="sxs-lookup"><span data-stu-id="7f689-156">Updated ARM templates</span></span>
  - <span data-ttu-id="7f689-157">不再復原失敗的作業</span><span class="sxs-lookup"><span data-stu-id="7f689-157">Failed operations no longer rollback</span></span>
  - <span data-ttu-id="7f689-158">Add-AzureRmServiceFabricNodeType</span><span class="sxs-lookup"><span data-stu-id="7f689-158">Add-AzureRmServiceFabricNodeType</span></span>
    - <span data-ttu-id="7f689-159">VM 預設位於受控磁碟</span><span class="sxs-lookup"><span data-stu-id="7f689-159">VMs default to managed disks</span></span>
    - <span data-ttu-id="7f689-160">使用現有的 VMSS 子網路</span><span class="sxs-lookup"><span data-stu-id="7f689-160">Existing VMSS subnet used</span></span>
    - <span data-ttu-id="7f689-161">均為等冪作業</span><span class="sxs-lookup"><span data-stu-id="7f689-161">All operations are idempotent</span></span>
  - <span data-ttu-id="7f689-162">Remove-AzureRmServiceFabricNodeType 會清除所立的部分 VMSS 和/或叢集節點類型</span><span class="sxs-lookup"><span data-stu-id="7f689-162">Remove-AzureRmServiceFabricNodeType cleans up partially created VMSS and/or cluster node types</span></span>
  - <span data-ttu-id="7f689-163">已修正複雜屬性類型的 PSCluster 物件輸出</span><span class="sxs-lookup"><span data-stu-id="7f689-163">Fixed output of PSCluster object for complex property types</span></span>

#### <a name="azurermsql"></a><span data-ttu-id="7f689-164">AzureRM.Sql</span><span class="sxs-lookup"><span data-stu-id="7f689-164">AzureRM.Sql</span></span>
* <span data-ttu-id="7f689-165">已修正匯入別名的問題</span><span class="sxs-lookup"><span data-stu-id="7f689-165">Fixed issue with importing aliases</span></span>
* <span data-ttu-id="7f689-166">Get-AzureRmSqlServer、New-AzureRmSqlServer 和 Remove-AzureRmSqlServer 回覆現在包括 FullyQualifiedDomainName 屬性。</span><span class="sxs-lookup"><span data-stu-id="7f689-166">Get-AzureRmSqlServer, New-AzureRmSqlServer, and Remove-AzureRmSqlServer response now includes FullyQualifiedDomainName property.</span></span>

#### <a name="azurermwebsites"></a><span data-ttu-id="7f689-167">AzureRM.Websites</span><span class="sxs-lookup"><span data-stu-id="7f689-167">AzureRM.Websites</span></span>
* <span data-ttu-id="7f689-168">已修正匯入別名的問題</span><span class="sxs-lookup"><span data-stu-id="7f689-168">Fixed issue with importing aliases</span></span>
* <span data-ttu-id="7f689-169">New-AzureRMWebApp - 已新增參數集供建立簡化 WebApp 之用，搭配本機 GIT 存放庫支援。</span><span class="sxs-lookup"><span data-stu-id="7f689-169">New-AzureRMWebApp - added parameter set for simplified WebApp creation, with local git repository support.</span></span>

## <a name="540---february-2018"></a><span data-ttu-id="7f689-170">5.4.0 - 2018 年 2 月</span><span class="sxs-lookup"><span data-stu-id="7f689-170">5.4.0 - February 2018</span></span>
#### <a name="azurermautomation"></a><span data-ttu-id="7f689-171">AzureRM.Automation</span><span class="sxs-lookup"><span data-stu-id="7f689-171">AzureRM.Automation</span></span>
* <span data-ttu-id="7f689-172">將別名從 New-AzureRmAutomationModule 新增至 Import-AzureRmAutomationModule</span><span class="sxs-lookup"><span data-stu-id="7f689-172">Added alias from New-AzureRmAutomationModule to Import-AzureRmAutomationModule</span></span>

#### <a name="azurermcompute"></a><span data-ttu-id="7f689-173">AzureRM.Compute</span><span class="sxs-lookup"><span data-stu-id="7f689-173">AzureRM.Compute</span></span>
* <span data-ttu-id="7f689-174">修正某些 Get Cmdlet 的 ErrorAction 問題。</span><span class="sxs-lookup"><span data-stu-id="7f689-174">Fix ErrorAction issue for some of Get cmdlets.</span></span>

#### <a name="azurermcontainerinstance"></a><span data-ttu-id="7f689-175">AzureRM.ContainerInstance</span><span class="sxs-lookup"><span data-stu-id="7f689-175">AzureRM.ContainerInstance</span></span>
* <span data-ttu-id="7f689-176">套用 Azure 容器執行個體 SDK 2018-02-01</span><span class="sxs-lookup"><span data-stu-id="7f689-176">Apply Azure Container Instance SDK 2018-02-01</span></span>
    - <span data-ttu-id="7f689-177">支援 DNS 名稱標籤</span><span class="sxs-lookup"><span data-stu-id="7f689-177">Support DNS name label</span></span>

#### <a name="azurermdevtestlabs"></a><span data-ttu-id="7f689-178">AzureRM.DevTestLabs</span><span class="sxs-lookup"><span data-stu-id="7f689-178">AzureRM.DevTestLabs</span></span>
* <span data-ttu-id="7f689-179">修正所有先前未正常運作的 GET Cmdlet。</span><span class="sxs-lookup"><span data-stu-id="7f689-179">Fixed all of the GET cmdlets which previously weren't working.</span></span>

#### <a name="azurermeventhub"></a><span data-ttu-id="7f689-180">AzureRM.EventHub</span><span class="sxs-lookup"><span data-stu-id="7f689-180">AzureRM.EventHub</span></span>
* <span data-ttu-id="7f689-181">修正 Get-AzureRmEventHubGeoDRConfiguration 說明中的錯誤</span><span class="sxs-lookup"><span data-stu-id="7f689-181">Fix bug in Get-AzureRmEventHubGeoDRConfiguration help</span></span>

#### <a name="azurermnetwork"></a><span data-ttu-id="7f689-182">AzureRM.Network</span><span class="sxs-lookup"><span data-stu-id="7f689-182">AzureRM.Network</span></span>
* <span data-ttu-id="7f689-183">已新增用來建立新連線監視的 Cmdlet</span><span class="sxs-lookup"><span data-stu-id="7f689-183">Added cmdlet to create a new connection monitor</span></span>
    - <span data-ttu-id="7f689-184">New-AzureRmNetworkWatcherConnectionMonitor</span><span class="sxs-lookup"><span data-stu-id="7f689-184">New-AzureRmNetworkWatcherConnectionMonitor</span></span>
* <span data-ttu-id="7f689-185">已新增用來更新連線監視的 Cmdlet</span><span class="sxs-lookup"><span data-stu-id="7f689-185">Added cmdlet to update a connection monitor</span></span>
    - <span data-ttu-id="7f689-186">Set-AzureRmNetworkWatcherConnectionMonitor</span><span class="sxs-lookup"><span data-stu-id="7f689-186">Set-AzureRmNetworkWatcherConnectionMonitor</span></span>
* <span data-ttu-id="7f689-187">已新增用來取得連線監視或連線監視清單的 Cmdlet</span><span class="sxs-lookup"><span data-stu-id="7f689-187">Added cmdlet to get connection monitor or connection monitor list</span></span>
    - <span data-ttu-id="7f689-188">Get-AzureRmNetworkWatcherConnectionMonitor</span><span class="sxs-lookup"><span data-stu-id="7f689-188">Get-AzureRmNetworkWatcherConnectionMonitor</span></span>
* <span data-ttu-id="7f689-189">已新增用來查詢連線監視的 Cmdlet</span><span class="sxs-lookup"><span data-stu-id="7f689-189">Added cmdlet to query connection monitor</span></span>
    - <span data-ttu-id="7f689-190">Get-AzureRmNetworkWatcherConnectionMonitorReport</span><span class="sxs-lookup"><span data-stu-id="7f689-190">Get-AzureRmNetworkWatcherConnectionMonitorReport</span></span>
* <span data-ttu-id="7f689-191">已新增用來啟動連線監視的 Cmdlet</span><span class="sxs-lookup"><span data-stu-id="7f689-191">Added cmdlet to start connection monitor</span></span>
    - <span data-ttu-id="7f689-192">Start-AzureRmNetworkWatcherConnectionMonitor</span><span class="sxs-lookup"><span data-stu-id="7f689-192">Start-AzureRmNetworkWatcherConnectionMonitor</span></span>
* <span data-ttu-id="7f689-193">已新增用來停止連線監視的 Cmdlet</span><span class="sxs-lookup"><span data-stu-id="7f689-193">Added cmdlet to stop connection monitor</span></span>
    - <span data-ttu-id="7f689-194">Stop-AzureRmNetworkWatcherConnectionMonitor</span><span class="sxs-lookup"><span data-stu-id="7f689-194">Stop-AzureRmNetworkWatcherConnectionMonitor</span></span>
* <span data-ttu-id="7f689-195">已新增用來移除連線監視的 Cmdlet</span><span class="sxs-lookup"><span data-stu-id="7f689-195">Added cmdlet to remove connection monitor</span></span>
    - <span data-ttu-id="7f689-196">Remove-AzureRmNetworkWatcherConnectionMonitor</span><span class="sxs-lookup"><span data-stu-id="7f689-196">Remove-AzureRmNetworkWatcherConnectionMonitor</span></span>
* <span data-ttu-id="7f689-197">已更新 Set-AzureRmApplicationGatewayBackendAddressPool 文件從而移除已淘汰的範例</span><span class="sxs-lookup"><span data-stu-id="7f689-197">Updated Set-AzureRmApplicationGatewayBackendAddressPool documentation to remove deprecated example</span></span>
* <span data-ttu-id="7f689-198">已對應用程式閘道新增 EnableHttp2 旗標</span><span class="sxs-lookup"><span data-stu-id="7f689-198">Added EnableHttp2 flag to Application Gateway</span></span>
    - <span data-ttu-id="7f689-199">已更新 New-AzureRmApplicationGateway：已新增選擇性參數 -EnableHttp2</span><span class="sxs-lookup"><span data-stu-id="7f689-199">Updated New-AzureRmApplicationGateway: Added optional parameter -EnableHttp2</span></span>
* <span data-ttu-id="7f689-200">將 IpTags 新增至 PublicIpAddress</span><span class="sxs-lookup"><span data-stu-id="7f689-200">Add IpTags to PublicIpAddress</span></span>
    - <span data-ttu-id="7f689-201">已更新 New-AzureRmPublicIpAddress：已新增 IpTags</span><span class="sxs-lookup"><span data-stu-id="7f689-201">Updated New-AzureRmPublicIpAddress: Added IpTags</span></span>
    - <span data-ttu-id="7f689-202">New-AzureRmPublicIpTag 以新增 Iptag</span><span class="sxs-lookup"><span data-stu-id="7f689-202">New-AzureRmPublicIpTag to add Iptag</span></span>
* <span data-ttu-id="7f689-203">在 RouteTable 和 effectiveRoute 中新增 DisableBgpRoutePropagation 屬性。</span><span class="sxs-lookup"><span data-stu-id="7f689-203">Add DisableBgpRoutePropagation property in RouteTable and effectiveRoute.</span></span>

#### <a name="azurermresources"></a><span data-ttu-id="7f689-204">AzureRM.Resources</span><span class="sxs-lookup"><span data-stu-id="7f689-204">AzureRM.Resources</span></span>
* <span data-ttu-id="7f689-205">Register-AzureRmProviderFeature：已在文件中新增遺漏的範例</span><span class="sxs-lookup"><span data-stu-id="7f689-205">Register-AzureRmProviderFeature: Added missing example in the docs</span></span>
* <span data-ttu-id="7f689-206">Register-AzureRmResourceProvider：已在文件中新增遺漏的範例</span><span class="sxs-lookup"><span data-stu-id="7f689-206">Register-AzureRmResourceProvider: Added missing example in the docs</span></span>

#### <a name="azurermstorage"></a><span data-ttu-id="7f689-207">AzureRM.Storage</span><span class="sxs-lookup"><span data-stu-id="7f689-207">AzureRM.Storage</span></span>
* <span data-ttu-id="7f689-208">在新的和設定的儲存體帳戶 Cmdlet 中淘汰下列參數：EnableEncryptionService 和 DisableEncryptionService，因為預設會啟用待用加密，且無法加以停用。</span><span class="sxs-lookup"><span data-stu-id="7f689-208">Obsolete following parameters in new and set Storage Account cmdlets: EnableEncryptionService and DisableEncryptionService, since Encryption at Rest is enabled by default and can't be disabled.</span></span>
    - <span data-ttu-id="7f689-209">New-AzureRmStorageAccount</span><span class="sxs-lookup"><span data-stu-id="7f689-209">New-AzureRmStorageAccount</span></span>
    - <span data-ttu-id="7f689-210">Set-AzureRmStorageAccount</span><span class="sxs-lookup"><span data-stu-id="7f689-210">Set-AzureRmStorageAccount</span></span>


## <a name="530---february-2018"></a><span data-ttu-id="7f689-211">5.3.0 - 2018 年 2 月</span><span class="sxs-lookup"><span data-stu-id="7f689-211">5.3.0 - February 2018</span></span>
### <a name="azurermprofile"></a><span data-ttu-id="7f689-212">AzureRM.Profile</span><span class="sxs-lookup"><span data-stu-id="7f689-212">AzureRM.Profile</span></span>
* <span data-ttu-id="7f689-213">已新增 PowerShell 3 和 4 的取代警告</span><span class="sxs-lookup"><span data-stu-id="7f689-213">Added deprecation warning for PowerShell 3 and 4</span></span>
* <span data-ttu-id="7f689-214">`Add-AzureRmAccount` 已重新命名為 `Connect-AzureRmAccount`；舊的 Cmdlet 名稱已新增別名，而其他別名 (`Login-AzAccount` 和 `Login-AzureRmAccount`) 已重新導向至新的 Cmdlet 名稱。</span><span class="sxs-lookup"><span data-stu-id="7f689-214">`Add-AzureRmAccount` has been renamed as `Connect-AzureRmAccount`; an alias has been added for the old cmdlet name, and other aliases (`Login-AzAccount` and `Login-AzureRmAccount`) have been redirected to the new cmdlet name.</span></span>
* <span data-ttu-id="7f689-215">`Remove-AzureRmAccount` 已重新命名為 `Disconnect-AzureRmAccount`；舊的 Cmdlet 名稱已新增別名，而其他別名 (`Logout-AzAccount` 和 `Logout-AzureRmAccount`) 已重新導向至新的 Cmdlet 名稱。</span><span class="sxs-lookup"><span data-stu-id="7f689-215">`Remove-AzureRmAccount` has been renamed as `Disconnect-AzureRmAccount`; an alias has been added for the old cmdlet name, and other aliases (`Logout-AzAccount` and `Logout-AzureRmAccount`) have been redirected to the new cmdlet name.</span></span>
* <span data-ttu-id="7f689-216">已更正資源字串使用 `Connect-AzureRmAccount`，而不是 `Login-AzureRmAccount`</span><span class="sxs-lookup"><span data-stu-id="7f689-216">Corrected Resource Strings to use `Connect-AzureRmAccount` instead of `Login-AzureRmAccount`</span></span>
* <span data-ttu-id="7f689-217">`Add-AzureRmEnvironment`和`Set-AzureRmEnvironment`</span><span class="sxs-lookup"><span data-stu-id="7f689-217">`Add-AzureRmEnvironment` and `Set-AzureRmEnvironment`</span></span>
  - <span data-ttu-id="7f689-218">已將 `-AzureOperationalInsightsEndpoint` 和 `-AzureOperationalInsightsEndpointResourceId`新增為參數，搭配 OperationalInsights 資料平面 RP 使用。</span><span class="sxs-lookup"><span data-stu-id="7f689-218">Added `-AzureOperationalInsightsEndpoint` and `-AzureOperationalInsightsEndpointResourceId` as parameters for use with OperationalInsights data plane RP.</span></span>

### <a name="azurermanalysisservices"></a><span data-ttu-id="7f689-219">AzureRM.AnalysisServices</span><span class="sxs-lookup"><span data-stu-id="7f689-219">AzureRM.AnalysisServices</span></span>
* <span data-ttu-id="7f689-220">已更正 `Login-AzureRmAccount` 的使用方式來使用 `Connect-AzureRmAccount`</span><span class="sxs-lookup"><span data-stu-id="7f689-220">Corrected usage of `Login-AzureRmAccount` to use `Connect-AzureRmAccount`</span></span>

### <a name="azurermcompute"></a><span data-ttu-id="7f689-221">AzureRM.Compute</span><span class="sxs-lookup"><span data-stu-id="7f689-221">AzureRM.Compute</span></span>
* <span data-ttu-id="7f689-222">已將 `-AvailabilitySetName` 參數新增至簡化的 `New-AzureRmVM` 參數集。</span><span class="sxs-lookup"><span data-stu-id="7f689-222">Added `-AvailabilitySetName` parameter to the simplified parameterset of `New-AzureRmVM`.</span></span>
* <span data-ttu-id="7f689-223">已更正 `Login-AzureRmAccount` 的使用方式來使用 `Connect-AzureRmAccount`</span><span class="sxs-lookup"><span data-stu-id="7f689-223">Corrected usage of `Login-AzureRmAccount` to use `Connect-AzureRmAccount`</span></span>
* <span data-ttu-id="7f689-224">適用於 VM 和 VM 擴展集的使用者指派識別身分支援</span><span class="sxs-lookup"><span data-stu-id="7f689-224">User assigned identity support for VM and VM scale set</span></span>
    - <span data-ttu-id="7f689-225">已將 `-IdentityType` 和 `-IdentityId` 參數新增至 `New-AzureRmVMConfig`、`New-AzureRmVmssConfig`、`Update-AzureRmVM` 和 `Update-AzureRmVmss`</span><span class="sxs-lookup"><span data-stu-id="7f689-225">`-IdentityType` and `-IdentityId` parameters are added to `New-AzureRmVMConfig`, `New-AzureRmVmssConfig`, `Update-AzureRmVM` and `Update-AzureRmVmss`</span></span>
* <span data-ttu-id="7f689-226">在 `Add-AzureRmVmssNetworkInterfaceConfig` 中新增 `-EnableIPForwarding` 參數</span><span class="sxs-lookup"><span data-stu-id="7f689-226">Added `-EnableIPForwarding` parameter to `Add-AzureRmVmssNetworkInterfaceConfig`</span></span>
* <span data-ttu-id="7f689-227">在 `New-AzureRmVmssConfig` 中新增 `-Priority` 參數</span><span class="sxs-lookup"><span data-stu-id="7f689-227">Added `-Priority` parameter to `New-AzureRmVmssConfig`</span></span>

### <a name="azurermdatalakeanalytics"></a><span data-ttu-id="7f689-228">AzureRM.DataLakeAnalytics</span><span class="sxs-lookup"><span data-stu-id="7f689-228">AzureRM.DataLakeAnalytics</span></span>
* <span data-ttu-id="7f689-229">已更正 `Login-AzureRmAccount` 的使用方式來使用 `Connect-AzureRmAccount`</span><span class="sxs-lookup"><span data-stu-id="7f689-229">Corrected usage of `Login-AzureRmAccount` to use `Connect-AzureRmAccount`</span></span>

### <a name="azurermdatalakestore"></a><span data-ttu-id="7f689-230">AzureRM.DataLakeStore</span><span class="sxs-lookup"><span data-stu-id="7f689-230">AzureRM.DataLakeStore</span></span>
* <span data-ttu-id="7f689-231">已更正 `Login-AzureRmAccount` 的使用方式來使用 `Connect-AzureRmAccount`</span><span class="sxs-lookup"><span data-stu-id="7f689-231">Corrected usage of `Login-AzureRmAccount` to use `Connect-AzureRmAccount`</span></span>
* <span data-ttu-id="7f689-232">已更正執行此 Cmdlet 而不需要登入 `Login-AzureRmAccount` 時的 `Test-AzureRmDataLakeStoreAccount` 錯誤訊息</span><span class="sxs-lookup"><span data-stu-id="7f689-232">Corrected the error message of `Test-AzureRmDataLakeStoreAccount` when running this cmdlet without having logged in with `Login-AzureRmAccount`</span></span>

### <a name="azurermeventgrid"></a><span data-ttu-id="7f689-233">AzureRM.EventGrid</span><span class="sxs-lookup"><span data-stu-id="7f689-233">AzureRM.EventGrid</span></span>
* <span data-ttu-id="7f689-234">已更新使用 2018-01-01 API 版本。</span><span class="sxs-lookup"><span data-stu-id="7f689-234">Updated to use the 2018-01-01 API version.</span></span>

### <a name="azurermeventhub"></a><span data-ttu-id="7f689-235">AzureRM.EventHub</span><span class="sxs-lookup"><span data-stu-id="7f689-235">AzureRM.EventHub</span></span>
* <span data-ttu-id="7f689-236">已新增下列異地災害復原作業的新命令。</span><span class="sxs-lookup"><span data-stu-id="7f689-236">Added below new commands for Geo Disaster Recovery operations.</span></span>
    <span data-ttu-id="7f689-237">-建立新的別名 (災害復原設定)：- `New-AzureRmEventHubGeoDRConfiguration` -擷取別名 (災害復原設定)：- `Get-AzureRmEventHubGeoDRConfiguration` -停用災害復原，並停止複寫從主要到次要命名空間的變更 - `Set-AzureRmEventHubGeoDRConfigurationBreakPair` -叫用災害復原容錯移轉並重新設定別名指向次要命名空間 - `Set-AzureRmEventHubGeoDRConfigurationFailOver` -刪除別名 (災害復原設定) - `Remove-AzureRmEventHubGeoDRConfiguration`</span><span class="sxs-lookup"><span data-stu-id="7f689-237">-Creating a new Alias(Disaster Recovery configuration): - `New-AzureRmEventHubGeoDRConfiguration` -Retrieve Alias(Disaster Recovery configuration) : - `Get-AzureRmEventHubGeoDRConfiguration` -Disabling the Disaster Recovery and stops replicating changes from primary to secondary namespaces - `Set-AzureRmEventHubGeoDRConfigurationBreakPair` -Invoking Disaster Recovery failover and reconfigure the alias to point to the secondary namespace - `Set-AzureRmEventHubGeoDRConfigurationFailOver` -Deleting an Alias(Disaster Recovery configuration) - `Remove-AzureRmEventHubGeoDRConfiguration`</span></span>
* <span data-ttu-id="7f689-238">已新增下列命令，用以檢查命名空間名稱和 GeoDr 設定名稱 - 別名可用性。</span><span class="sxs-lookup"><span data-stu-id="7f689-238">Added below new commands for checking the Namespace Name and GeoDr Configuration Name - Alias availability.</span></span>
    <span data-ttu-id="7f689-239">-檢查命名空間名稱或別名 (災害復原設定) 名稱的可用性：- `Test-AzureRmEventHubName`</span><span class="sxs-lookup"><span data-stu-id="7f689-239">-Check the Availability of Namespace name or Alias(Disaster Recovery configuration) name: - `Test-AzureRmEventHubName`</span></span>

### <a name="azurerminsights"></a><span data-ttu-id="7f689-240">AzureRM.Insights</span><span class="sxs-lookup"><span data-stu-id="7f689-240">AzureRM.Insights</span></span>
* <span data-ttu-id="7f689-241">已更正 `Login-AzureRmAccount` 的使用方式來使用 `Connect-AzureRmAccount`</span><span class="sxs-lookup"><span data-stu-id="7f689-241">Corrected usage of `Login-AzureRmAccount` to use `Connect-AzureRmAccount`</span></span>

### <a name="azurermkeyvault"></a><span data-ttu-id="7f689-242">AzureRM.KeyVault</span><span class="sxs-lookup"><span data-stu-id="7f689-242">AzureRM.KeyVault</span></span>
* <span data-ttu-id="7f689-243">已更正 `Login-AzureRmAccount` 的使用方式來使用 `Connect-AzureRmAccount`</span><span class="sxs-lookup"><span data-stu-id="7f689-243">Corrected usage of `Login-AzureRmAccount` to use `Connect-AzureRmAccount`</span></span>

### <a name="azurermnetwork"></a><span data-ttu-id="7f689-244">AzureRM.Network</span><span class="sxs-lookup"><span data-stu-id="7f689-244">AzureRM.Network</span></span>
* <span data-ttu-id="7f689-245">修正覆寫訊息「您確定要覆寫來源嗎」</span><span class="sxs-lookup"><span data-stu-id="7f689-245">Fix overwrite message 'Are you sure you want to overwriteresource'</span></span>

#### <a name="azurermoperationalinsights"></a><span data-ttu-id="7f689-246">AzureRM.OperationalInsights</span><span class="sxs-lookup"><span data-stu-id="7f689-246">AzureRM.OperationalInsights</span></span>
* <span data-ttu-id="7f689-247">已新增透過 `Invoke-AzureRmOperationalInsightsQuery` 進行 V2 API 查詢的支援。</span><span class="sxs-lookup"><span data-stu-id="7f689-247">Added support for V2 API querying via `Invoke-AzureRmOperationalInsightsQuery`.</span></span> <span data-ttu-id="7f689-248">請參閱 [https://dev.loganalytics.io/](https://dev.loganalytics.io/) 以取得新 API 的詳細資訊。</span><span class="sxs-lookup"><span data-stu-id="7f689-248">See [https://dev.loganalytics.io/](https://dev.loganalytics.io/) for more info on the new API.</span></span>

### <a name="azurermresources"></a><span data-ttu-id="7f689-249">AzureRM.Resources</span><span class="sxs-lookup"><span data-stu-id="7f689-249">AzureRM.Resources</span></span>
* <span data-ttu-id="7f689-250">`Get-AzureRmADServicePrincipal`：已將 `-ServicePrincipalName` 從預設的空參數集移除，因為它是多餘的 SPN 參數集</span><span class="sxs-lookup"><span data-stu-id="7f689-250">`Get-AzureRmADServicePrincipal`: Removed `-ServicePrincipalName` from the default Empty parameter set as it was redundant with the SPN parameter set</span></span>

### <a name="azurermservicebus"></a><span data-ttu-id="7f689-251">AzureRM.ServiceBus</span><span class="sxs-lookup"><span data-stu-id="7f689-251">AzureRM.ServiceBus</span></span>
* <span data-ttu-id="7f689-252">已新增 `Remove-AzureRmServiceBusRule` 和 `Get-AzureRmServiceBusKey` 的功能修正</span><span class="sxs-lookup"><span data-stu-id="7f689-252">Added functionality fix for `Remove-AzureRmServiceBusRule` and `Get-AzureRmServiceBusKey`</span></span>
* <span data-ttu-id="7f689-253">已新增下列異地災害復原作業的新 Commandlet。</span><span class="sxs-lookup"><span data-stu-id="7f689-253">Added below new commandlets for Geo Disaster Recovery operations.</span></span>
    <span data-ttu-id="7f689-254">-建立新的別名 (災害復原設定)：- `New-AzureRmServiceBusDRConfigurations` -擷取別名 (災害復原設定)：- `Get-AzureRmServiceBusDRConfigurations` -停用災害復原，並停止複寫從主要到次要命名空間的變更 - `Set-AzureRmServiceBusDRConfigurationsBreakPairing` -叫用災害復原容錯移轉並重新設定別名指向次要命名空間 - `Set-AzureRmServiceBusDRConfigurationsFailOver` -刪除別名 (災害復原設定) - `Remove-AzureRmServiceBusDRConfigurations`</span><span class="sxs-lookup"><span data-stu-id="7f689-254">-Creating a new Alias(Disaster Recovery configuration): - `New-AzureRmServiceBusDRConfigurations` -Retrieve Alias(Disaster Recovery configuration) : - `Get-AzureRmServiceBusDRConfigurations` -Disabling the Disaster Recovery and stops replicating changes from primary to secondary namespaces - `Set-AzureRmServiceBusDRConfigurationsBreakPairing` -Invoking Disaster Recovery failover and reconfigure the alias to point to the secondary namespace - `Set-AzureRmServiceBusDRConfigurationsFailOver` -Deleting an Alias(Disaster Recovery configuration) - `Remove-AzureRmServiceBusDRConfigurations`</span></span>
* <span data-ttu-id="7f689-255">已更新 `Test-AzureRmServiceBusName` Commandlet 以支援異地災害復原 - 別名名稱檢查可用性作業。</span><span class="sxs-lookup"><span data-stu-id="7f689-255">Updated `Test-AzureRmServiceBusName` commandlets to support Geo Disaster Recovery - Alias name check availability operations.</span></span>
    <span data-ttu-id="7f689-256">-檢查命名空間名稱或別名 (災害復原設定) 名稱的可用性：- `Test-AzureRmServiceBusName`</span><span class="sxs-lookup"><span data-stu-id="7f689-256">-Check the Availability of Namespace name or Alias(Disaster Recovery configuration) name: - `Test-AzureRmServiceBusName`</span></span>

### <a name="azurermusageaggregates"></a><span data-ttu-id="7f689-257">AzureRM.UsageAggregates</span><span class="sxs-lookup"><span data-stu-id="7f689-257">AzureRM.UsageAggregates</span></span>
* <span data-ttu-id="7f689-258">已更正 `Login-AzureRmAccount` 的使用方式來使用 `Connect-AzureRmAccount`</span><span class="sxs-lookup"><span data-stu-id="7f689-258">Corrected usage of `Login-AzureRmAccount` to use `Connect-AzureRmAccount`</span></span>

## <a name="520---january-2018"></a><span data-ttu-id="7f689-259">5.2.0 - 2018 年 1 月</span><span class="sxs-lookup"><span data-stu-id="7f689-259">5.2.0 - January 2018</span></span>
#### <a name="azurermprofile"></a><span data-ttu-id="7f689-260">AzureRM.Profile</span><span class="sxs-lookup"><span data-stu-id="7f689-260">AzureRM.Profile</span></span>
* <span data-ttu-id="7f689-261">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-261">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>
* <span data-ttu-id="7f689-262">Add-AzureRmAccount</span><span class="sxs-lookup"><span data-stu-id="7f689-262">Add-AzureRmAccount</span></span>
  * <span data-ttu-id="7f689-263">已新增 -MSI 登入，以便使用目前虛擬機器/服務的受管理服務身分識別之認證來進行驗證</span><span class="sxs-lookup"><span data-stu-id="7f689-263">Added -MSI login for authenticationg using the credentials of the Managed Service Identity of the current VM / Service</span></span>
  * <span data-ttu-id="7f689-264">修正了以使用者所提供的存取權杖登入時，KeyVault 驗證所發生的問題</span><span class="sxs-lookup"><span data-stu-id="7f689-264">Fixed KeyVault Authentication when logging in with user-provided access tokens</span></span>

#### <a name="azurestorage"></a><span data-ttu-id="7f689-265">Azure.Storage</span><span class="sxs-lookup"><span data-stu-id="7f689-265">Azure.Storage</span></span>
* <span data-ttu-id="7f689-266">新增用以取得和設定儲存體服務屬性的 Cmdlet</span><span class="sxs-lookup"><span data-stu-id="7f689-266">Add cmdlets to get and set Storage service properties</span></span>
    - <span data-ttu-id="7f689-267">Get-AzureStorageServiceProperty</span><span class="sxs-lookup"><span data-stu-id="7f689-267">Get-AzureStorageServiceProperty</span></span>
    - <span data-ttu-id="7f689-268">Update-AzureStorageServiceProperty</span><span class="sxs-lookup"><span data-stu-id="7f689-268">Update-AzureStorageServiceProperty</span></span>

#### <a name="azurermanalysisservices"></a><span data-ttu-id="7f689-269">AzureRM.AnalysisServices</span><span class="sxs-lookup"><span data-stu-id="7f689-269">AzureRM.AnalysisServices</span></span>
* <span data-ttu-id="7f689-270">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-270">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermapimanagement"></a><span data-ttu-id="7f689-271">AzureRM.ApiManagement</span><span class="sxs-lookup"><span data-stu-id="7f689-271">AzureRM.ApiManagement</span></span>
* <span data-ttu-id="7f689-272">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-272">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="7f689-273">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-273">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>
* <span data-ttu-id="7f689-274">針對 New-AzureRmApiManagementProperty、Set-AzureRmApiManagementProperty 和 New-AzureRmApiManagement，已淘汰 -Tags 並改用 -Tag</span><span class="sxs-lookup"><span data-stu-id="7f689-274">Obsoleted -Tags in favor of -Tag for New-AzureRmApiManagementProperty, Set-AzureRmApiManagementProperty, and New-AzureRmApiManagement</span></span>

#### <a name="azurermapplicationinsights"></a><span data-ttu-id="7f689-275">AzureRM.ApplicationInsights</span><span class="sxs-lookup"><span data-stu-id="7f689-275">AzureRM.ApplicationInsights</span></span>
* <span data-ttu-id="7f689-276">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-276">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="7f689-277">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-277">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermautomation"></a><span data-ttu-id="7f689-278">AzureRM.Automation</span><span class="sxs-lookup"><span data-stu-id="7f689-278">AzureRM.Automation</span></span>
* <span data-ttu-id="7f689-279">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-279">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="7f689-280">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-280">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>
* <span data-ttu-id="7f689-281">針對 Set-AzureRmAutomationRunbook，已淘汰 -Tags 並改用 -Tag</span><span class="sxs-lookup"><span data-stu-id="7f689-281">Obsoleted -Tags in favor of -Tag for Set-AzureRmAutomationRunbook</span></span>

#### <a name="azurermbackup"></a><span data-ttu-id="7f689-282">AzureRM.Backup</span><span class="sxs-lookup"><span data-stu-id="7f689-282">AzureRM.Backup</span></span>
* <span data-ttu-id="7f689-283">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-283">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="7f689-284">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-284">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermbatch"></a><span data-ttu-id="7f689-285">AzureRM.Batch</span><span class="sxs-lookup"><span data-stu-id="7f689-285">AzureRM.Batch</span></span>
* <span data-ttu-id="7f689-286">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-286">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="7f689-287">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-287">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermcdn"></a><span data-ttu-id="7f689-288">AzureRM.Cdn</span><span class="sxs-lookup"><span data-stu-id="7f689-288">AzureRM.Cdn</span></span>
* <span data-ttu-id="7f689-289">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-289">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="7f689-290">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-290">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>
* <span data-ttu-id="7f689-291">針對 New-AzureRmCdnEndpoint 和 New-AzureRmCdnProfile，已淘汰 -Tags 並改用 -Tag</span><span class="sxs-lookup"><span data-stu-id="7f689-291">Obsoleted -Tags in favor of -Tag for New-AzureRmCdnEndpoint and New-AzureRmCdnProfile</span></span>

#### <a name="azurermcognitiveservices"></a><span data-ttu-id="7f689-292">AzureRM.CognitiveServices</span><span class="sxs-lookup"><span data-stu-id="7f689-292">AzureRM.CognitiveServices</span></span>
* <span data-ttu-id="7f689-293">整合認知服務管理 SDK 3.0.0 版。</span><span class="sxs-lookup"><span data-stu-id="7f689-293">Integrate with Cognitive Services Management SDK version 3.0.0.</span></span>

#### <a name="azurermcompute"></a><span data-ttu-id="7f689-294">AzureRM.Compute</span><span class="sxs-lookup"><span data-stu-id="7f689-294">AzureRM.Compute</span></span>
* <span data-ttu-id="7f689-295">已將簡化的參數新增到 New-AzureRmVmss，後者會使用智慧型預設值建立虛擬機器擴展集和所有必要的資源</span><span class="sxs-lookup"><span data-stu-id="7f689-295">Added simplified parameter set to New-AzureRmVmss, which creates a Virtual Machine Scale Set and all required resources using smart defaults</span></span>
* <span data-ttu-id="7f689-296">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-296">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="7f689-297">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-297">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>
* <span data-ttu-id="7f689-298">針對 New-AzureRmVm 和 Update-AzureRmVm，已淘汰 -Tags 並改用 -Tag</span><span class="sxs-lookup"><span data-stu-id="7f689-298">Obsoleted -Tags in favor of -Tag for New-AzureRmVm and Update-AzureRmVm</span></span>
* <span data-ttu-id="7f689-299">修正了限制中包含區域時，Get-AzureRmComputeResourceSku Cmdlet 所發生的問題。</span><span class="sxs-lookup"><span data-stu-id="7f689-299">Fixed Get-AzureRmComputeResourceSku cmdlet when Zone is included in restriction.</span></span>
* <span data-ttu-id="7f689-300">為了支援 Azure 監視器的接收，已更新診斷代理程式的設定結構描述。</span><span class="sxs-lookup"><span data-stu-id="7f689-300">Updated Diagnostics Agent configuration schema for Azure Monitor sink support.</span></span>

#### <a name="azurermcontainerinstance"></a><span data-ttu-id="7f689-301">AzureRM.ContainerInstance</span><span class="sxs-lookup"><span data-stu-id="7f689-301">AzureRM.ContainerInstance</span></span>
* <span data-ttu-id="7f689-302">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-302">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="7f689-303">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-303">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermcontainerregistry"></a><span data-ttu-id="7f689-304">AzureRM.ContainerRegistry</span><span class="sxs-lookup"><span data-stu-id="7f689-304">AzureRM.ContainerRegistry</span></span>
* <span data-ttu-id="7f689-305">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-305">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="7f689-306">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-306">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermdatafactories"></a><span data-ttu-id="7f689-307">AzureRM.DataFactories</span><span class="sxs-lookup"><span data-stu-id="7f689-307">AzureRM.DataFactories</span></span>
* <span data-ttu-id="7f689-308">已讓所有資料存放區所連結的服務都支援 Azure Key Vault</span><span class="sxs-lookup"><span data-stu-id="7f689-308">Enabled Azure Key Vault support for all data store linked services</span></span>
* <span data-ttu-id="7f689-309">已新增 Azure SSIS 整合執行階段的授權類型屬性</span><span class="sxs-lookup"><span data-stu-id="7f689-309">Added license type property for Azure SSIS integration runtime</span></span>
* <span data-ttu-id="7f689-310">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-310">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="7f689-311">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-311">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>
* <span data-ttu-id="7f689-312">針對 New-AzureRmDataFactory，已淘汰 -Tags 並改用 -Tag</span><span class="sxs-lookup"><span data-stu-id="7f689-312">Obsoleted -Tags in favor of -Tag for New-AzureRmDataFactory</span></span>

#### <a name="azurermdatafactoryv2"></a><span data-ttu-id="7f689-313">AzureRM.DataFactoryV2</span><span class="sxs-lookup"><span data-stu-id="7f689-313">AzureRM.DataFactoryV2</span></span>
* <span data-ttu-id="7f689-314">已讓所有資料存放區所連結的服務都支援 Azure Key Vault</span><span class="sxs-lookup"><span data-stu-id="7f689-314">Enabled Azure Key Vault support for all data store linked services</span></span>
* <span data-ttu-id="7f689-315">已新增 Azure SSIS 整合執行階段的授權類型屬性</span><span class="sxs-lookup"><span data-stu-id="7f689-315">Added license type property for Azure SSIS integration runtime</span></span>
* <span data-ttu-id="7f689-316">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-316">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="7f689-317">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-317">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>
* <span data-ttu-id="7f689-318">新增「Set-AzureRmDataFactoryV2IntegrationRuntime」cmd 的參數「LicenseType」以啟用 AHUB 功能</span><span class="sxs-lookup"><span data-stu-id="7f689-318">Add parameter "LicenseType" for "Set-AzureRmDataFactoryV2IntegrationRuntime" cmd to enable AHUB functionality</span></span>

#### <a name="azurermdatalakeanalytics"></a><span data-ttu-id="7f689-319">AzureRM.DataLakeAnalytics</span><span class="sxs-lookup"><span data-stu-id="7f689-319">AzureRM.DataLakeAnalytics</span></span>
* <span data-ttu-id="7f689-320">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-320">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="7f689-321">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-321">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>
* <span data-ttu-id="7f689-322">針對 AzureRmDataLakeAnalyticsAccount 和 Set-AzureRmDataLakeAnalyticsAccount，已淘汰 -Tags 並改用 -Tag</span><span class="sxs-lookup"><span data-stu-id="7f689-322">Obsoleted -Tags in favor of -Tag for New-AzureRmDataLakeAnalyticsAccount and Set-AzureRmDataLakeAnalyticsAccount</span></span>

#### <a name="azurermdatalakestore"></a><span data-ttu-id="7f689-323">AzureRM.DataLakeStore</span><span class="sxs-lookup"><span data-stu-id="7f689-323">AzureRM.DataLakeStore</span></span>
* <span data-ttu-id="7f689-324">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-324">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="7f689-325">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-325">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>
* <span data-ttu-id="7f689-326">針對 New-AzureRmDataLakeStoreAccount 和 Set-AzureRmDataLakeStoreAccount，已淘汰 -Tags 並改用 -Tag</span><span class="sxs-lookup"><span data-stu-id="7f689-326">Obsoleted -Tags in favor of -Tag for New-AzureRmDataLakeStoreAccount and Set-AzureRmDataLakeStoreAccount</span></span>

#### <a name="azurermdevtestlabs"></a><span data-ttu-id="7f689-327">AzureRM.DevTestLabs</span><span class="sxs-lookup"><span data-stu-id="7f689-327">AzureRM.DevTestLabs</span></span>
* <span data-ttu-id="7f689-328">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-328">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermdns"></a><span data-ttu-id="7f689-329">AzureRM.Dns</span><span class="sxs-lookup"><span data-stu-id="7f689-329">AzureRM.Dns</span></span>
* <span data-ttu-id="7f689-330">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-330">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermeventgrid"></a><span data-ttu-id="7f689-331">AzureRM.EventGrid</span><span class="sxs-lookup"><span data-stu-id="7f689-331">AzureRM.EventGrid</span></span>
* <span data-ttu-id="7f689-332">已新增下列的新 Cmdlet：</span><span class="sxs-lookup"><span data-stu-id="7f689-332">Added the following new cmdlet:</span></span>
    - <span data-ttu-id="7f689-333">Update-AzureRmEventGridSubscription</span><span class="sxs-lookup"><span data-stu-id="7f689-333">Update-AzureRmEventGridSubscription</span></span>
        - <span data-ttu-id="7f689-334">更新 Event Grid 事件訂閱的屬性。</span><span class="sxs-lookup"><span data-stu-id="7f689-334">Update the properties of an Event Grid event subscription.</span></span>
* <span data-ttu-id="7f689-335">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-335">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="7f689-336">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-336">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermeventhub"></a><span data-ttu-id="7f689-337">AzureRM.EventHub</span><span class="sxs-lookup"><span data-stu-id="7f689-337">AzureRM.EventHub</span></span>
* <span data-ttu-id="7f689-338">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-338">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="7f689-339">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-339">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermhdinsight"></a><span data-ttu-id="7f689-340">AzureRM.HDInsight</span><span class="sxs-lookup"><span data-stu-id="7f689-340">AzureRM.HDInsight</span></span>
* <span data-ttu-id="7f689-341">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-341">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="7f689-342">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-342">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurerminsights"></a><span data-ttu-id="7f689-343">AzureRM.Insights</span><span class="sxs-lookup"><span data-stu-id="7f689-343">AzureRM.Insights</span></span>
* <span data-ttu-id="7f689-344">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-344">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="7f689-345">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-345">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermiothub"></a><span data-ttu-id="7f689-346">AzureRM.IotHub</span><span class="sxs-lookup"><span data-stu-id="7f689-346">AzureRM.IotHub</span></span>
* <span data-ttu-id="7f689-347">新增 IoTHub Cmdlet 的憑證支援</span><span class="sxs-lookup"><span data-stu-id="7f689-347">Add Certificate support for IoTHub cmdlets</span></span>
* <span data-ttu-id="7f689-348">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-348">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="7f689-349">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-349">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermkeyvault"></a><span data-ttu-id="7f689-350">AzureRM.KeyVault</span><span class="sxs-lookup"><span data-stu-id="7f689-350">AzureRM.KeyVault</span></span>
* <span data-ttu-id="7f689-351">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-351">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="7f689-352">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-352">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>
* <span data-ttu-id="7f689-353">已針對長時間執行的 KeyVault Cmdlet 新增 -AsJob 支援。</span><span class="sxs-lookup"><span data-stu-id="7f689-353">Added -AsJob support for long-running KeyVault cmdlets.</span></span> <span data-ttu-id="7f689-354">允許選取的 Cmdlet 在背景中執行，並傳回作業以追蹤及控制進度。</span><span class="sxs-lookup"><span data-stu-id="7f689-354">Allows selected cmdlets to run in the background and return a job to track and control progress.</span></span>
    * <span data-ttu-id="7f689-355">受影響的 Cmdlet 是：Remove-AzureRmKeyVault</span><span class="sxs-lookup"><span data-stu-id="7f689-355">Affected cmdlet is: Remove-AzureRmKeyVault</span></span>
* <span data-ttu-id="7f689-356">修正了 Set-AzureRmKeyVaultAccessPolicy 中，AAD 篩選器會將 SPN 設為提供的 UPN 而非設定 UPN 本身的錯誤</span><span class="sxs-lookup"><span data-stu-id="7f689-356">Fixed bug in Set-AzureRmKeyVaultAccessPolicy where the AAD filter was setting SPN to the provided UPN, rather than setting the UPN</span></span>
   - <span data-ttu-id="7f689-357">請參閱下列問題以取得更多資訊：https://github.com/Azure/azure-powershell/issues/5201</span><span class="sxs-lookup"><span data-stu-id="7f689-357">See the following issue for more information: https://github.com/Azure/azure-powershell/issues/5201</span></span>

#### <a name="azurermlogicapp"></a><span data-ttu-id="7f689-358">AzureRM.LogicApp</span><span class="sxs-lookup"><span data-stu-id="7f689-358">AzureRM.LogicApp</span></span>
* <span data-ttu-id="7f689-359">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-359">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="7f689-360">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-360">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermmachinelearning"></a><span data-ttu-id="7f689-361">AzureRM.MachineLearning</span><span class="sxs-lookup"><span data-stu-id="7f689-361">AzureRM.MachineLearning</span></span>
* <span data-ttu-id="7f689-362">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-362">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="7f689-363">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-363">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>
* <span data-ttu-id="7f689-364">針對 Update-AzureRmMlCommitmentPlan，已淘汰 -Tags 並改用 -Tag</span><span class="sxs-lookup"><span data-stu-id="7f689-364">Obsoleted -Tags in favor of -Tag for Update-AzureRmMlCommitmentPlan</span></span>

#### <a name="azurermmachinelearningcompute"></a><span data-ttu-id="7f689-365">AzureRM.MachineLearningCompute</span><span class="sxs-lookup"><span data-stu-id="7f689-365">AzureRM.MachineLearningCompute</span></span>
* <span data-ttu-id="7f689-366">將 IncludeAllResources 參數新增到 Remove-AzureRmMlOpCluster Cmdlet</span><span class="sxs-lookup"><span data-stu-id="7f689-366">Add IncludeAllResources parameter to Remove-AzureRmMlOpCluster cmdlet</span></span>
    - <span data-ttu-id="7f689-367">使用此切換參數，將移除原本與叢集一起建立的所有資源</span><span class="sxs-lookup"><span data-stu-id="7f689-367">Using this switch parameter will remove all resources that were created with the cluster originally</span></span>
* <span data-ttu-id="7f689-368">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-368">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="7f689-369">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-369">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermmedia"></a><span data-ttu-id="7f689-370">AzureRM.Media</span><span class="sxs-lookup"><span data-stu-id="7f689-370">AzureRM.Media</span></span>
* <span data-ttu-id="7f689-371">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-371">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="7f689-372">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-372">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>
* <span data-ttu-id="7f689-373">針對 Set-AzureRmMediaService 和 New-AzureRmMediaService，已淘汰 -Tags 並改用 -Tag</span><span class="sxs-lookup"><span data-stu-id="7f689-373">Obsoleted -Tags in favor of -Tag for Set-AzureRmMediaService and New-AzureRmMediaService</span></span>

#### <a name="azurermnetwork"></a><span data-ttu-id="7f689-374">AzureRM.Network</span><span class="sxs-lookup"><span data-stu-id="7f689-374">AzureRM.Network</span></span>
* <span data-ttu-id="7f689-375">已針對長時間執行的 Network Cmdlet 新增 -AsJob 支援。</span><span class="sxs-lookup"><span data-stu-id="7f689-375">Added -AsJob support for long-running Network cmdlets.</span></span> <span data-ttu-id="7f689-376">允許選取的 Cmdlet 在背景中執行，並傳回作業以追蹤及控制進度。</span><span class="sxs-lookup"><span data-stu-id="7f689-376">Allows selected cmdlets to run in the background and return a job to track and control progress.</span></span>
* <span data-ttu-id="7f689-377">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-377">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="7f689-378">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-378">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermnotificationhubs"></a><span data-ttu-id="7f689-379">AzureRM.NotificationHubs</span><span class="sxs-lookup"><span data-stu-id="7f689-379">AzureRM.NotificationHubs</span></span>
* <span data-ttu-id="7f689-380">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-380">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="7f689-381">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-381">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>
* <span data-ttu-id="7f689-382">針對 New-AzureRmNotificationHubsNamespace 和 Set-AzureRmNotificationHubsNamespace，已淘汰 -Tags 並改用 -Tag</span><span class="sxs-lookup"><span data-stu-id="7f689-382">Obsoleted -Tags in favor of -Tag for New-AzureRmNotificationHubsNamespace and Set-AzureRmNotificationHubsNamespace</span></span>

#### <a name="azurermoperationalinsights"></a><span data-ttu-id="7f689-383">AzureRM.OperationalInsights</span><span class="sxs-lookup"><span data-stu-id="7f689-383">AzureRM.OperationalInsights</span></span>
* <span data-ttu-id="7f689-384">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-384">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="7f689-385">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-385">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>
* <span data-ttu-id="7f689-386">針對 New-AzureRmOperationalInsightsSavedSearch、Set-AzureRmOperationalInsightsSavedSearch、New-AzureRmOperationalInsightsWorkspace 和 Set-AzureRmOperationalInsightsWorkspace，已淘汰 -Tags 並改用 -Tag</span><span class="sxs-lookup"><span data-stu-id="7f689-386">Obsoleted -Tags in favor of -Tag for New-AzureRmOperationalInsightsSavedSearch, Set-AzureRmOperationalInsightsSavedSearch, New-AzureRmOperationalInsightsWorkspace, and Set-AzureRmOperationalInsightsWorkspace</span></span>

#### <a name="azurermpowerbiembedded"></a><span data-ttu-id="7f689-387">AzureRM.PowerBIEmbedded</span><span class="sxs-lookup"><span data-stu-id="7f689-387">AzureRM.PowerBIEmbedded</span></span>
* <span data-ttu-id="7f689-388">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-388">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="7f689-389">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-389">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermrecoveryservices"></a><span data-ttu-id="7f689-390">AzureRM.RecoveryServices</span><span class="sxs-lookup"><span data-stu-id="7f689-390">AzureRM.RecoveryServices</span></span>
* <span data-ttu-id="7f689-391">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-391">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="7f689-392">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-392">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermrecoveryservicesbackup"></a><span data-ttu-id="7f689-393">AzureRM.RecoveryServices.Backup</span><span class="sxs-lookup"><span data-stu-id="7f689-393">AzureRM.RecoveryServices.Backup</span></span>
* <span data-ttu-id="7f689-394">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-394">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>
* <span data-ttu-id="7f689-395">已將 -UseOriginalStorageAccount 選項新增到 Restore-AzureRmRecoveryServicesBackupItem Cmdlet。</span><span class="sxs-lookup"><span data-stu-id="7f689-395">Added -UseOriginalStorageAccount option to the Restore-AzureRmRecoveryServicesBackupItem cmdlet.</span></span>
    - <span data-ttu-id="7f689-396">啟用此旗標會將磁碟還原到原始的儲存體帳戶，這可讓使用者將所還原虛擬機器的設定，盡可能重設回原始虛擬機器的設定。</span><span class="sxs-lookup"><span data-stu-id="7f689-396">Enabling this flag results in restoring disks to their original storage accounts which allows users to maintain the configuration of restored VM as close to the original VMs as possible.</span></span>
    - <span data-ttu-id="7f689-397">這也有助於改善還原作業的效能。</span><span class="sxs-lookup"><span data-stu-id="7f689-397">It also helps in improving the performance of the restore operation.</span></span>

#### <a name="azurermrediscache"></a><span data-ttu-id="7f689-398">AzureRM.RedisCache</span><span class="sxs-lookup"><span data-stu-id="7f689-398">AzureRM.RedisCache</span></span>
* <span data-ttu-id="7f689-399">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-399">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="7f689-400">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-400">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>
* <span data-ttu-id="7f689-401">已新增 3 個防火牆規則的新 Cmdlet</span><span class="sxs-lookup"><span data-stu-id="7f689-401">Added  3 new cmdlets for firewall rules</span></span>
* <span data-ttu-id="7f689-402">已新增 3 個異地複寫的新 Cmdlet</span><span class="sxs-lookup"><span data-stu-id="7f689-402">Added  3 new cmdlets for geo replication</span></span>
* <span data-ttu-id="7f689-403">已新增區域和標籤的支援</span><span class="sxs-lookup"><span data-stu-id="7f689-403">Added support for zones and tags</span></span>
* <span data-ttu-id="7f689-404">盡可能將 ResourceGroup 設為選用。</span><span class="sxs-lookup"><span data-stu-id="7f689-404">Make ResourceGroup as optional whenever possible.</span></span>

#### <a name="azurermrelay"></a><span data-ttu-id="7f689-405">AzureRM.Relay</span><span class="sxs-lookup"><span data-stu-id="7f689-405">AzureRM.Relay</span></span>
* <span data-ttu-id="7f689-406">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-406">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="7f689-407">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-407">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermresources"></a><span data-ttu-id="7f689-408">AzureRM.Resources</span><span class="sxs-lookup"><span data-stu-id="7f689-408">AzureRM.Resources</span></span>
* <span data-ttu-id="7f689-409">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-409">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="7f689-410">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-410">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>
* <span data-ttu-id="7f689-411">已針對長時間執行的 Resources Cmdlet 新增 -AsJob 支援。</span><span class="sxs-lookup"><span data-stu-id="7f689-411">Added -AsJob support for long-running Resources cmdlets.</span></span> <span data-ttu-id="7f689-412">允許選取的 Cmdlet 在背景中執行，並傳回作業以追蹤及控制進度。</span><span class="sxs-lookup"><span data-stu-id="7f689-412">Allows selected cmdlets to run in the background and return a job to track and control progress.</span></span>
* <span data-ttu-id="7f689-413">已從 Get-AzureRmProviderOperation 新增別名到 Get-AzureRmResourceProviderAction 以符合命名慣例</span><span class="sxs-lookup"><span data-stu-id="7f689-413">Added alias from Get-AzureRmProviderOperation to Get-AzureRmResourceProviderAction to conform with naming conventions</span></span>

#### <a name="azurermscheduler"></a><span data-ttu-id="7f689-414">AzureRM.Scheduler</span><span class="sxs-lookup"><span data-stu-id="7f689-414">AzureRM.Scheduler</span></span>
* <span data-ttu-id="7f689-415">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-415">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="7f689-416">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-416">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermservermanagement"></a><span data-ttu-id="7f689-417">AzureRM.ServerManagement</span><span class="sxs-lookup"><span data-stu-id="7f689-417">AzureRM.ServerManagement</span></span>
* <span data-ttu-id="7f689-418">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-418">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="7f689-419">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-419">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>
* <span data-ttu-id="7f689-420">針對 New-AzureRmServerManagementNode 和 New-AzureRmServerManagementGateway，已淘汰 -Tags 並改用 -Tag</span><span class="sxs-lookup"><span data-stu-id="7f689-420">Obsoleted -Tags in favor of -Tag for New-AzureRmServerManagementNode and New-AzureRmServerManagementGateway</span></span>

#### <a name="azurermservicebus"></a><span data-ttu-id="7f689-421">AzureRM.ServiceBus</span><span class="sxs-lookup"><span data-stu-id="7f689-421">AzureRM.ServiceBus</span></span>
* <span data-ttu-id="7f689-422">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-422">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="7f689-423">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-423">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermservicefabric"></a><span data-ttu-id="7f689-424">AzureRM.ServiceFabric</span><span class="sxs-lookup"><span data-stu-id="7f689-424">AzureRM.ServiceFabric</span></span>
* <span data-ttu-id="7f689-425">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-425">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="7f689-426">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-426">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermsiterecovery"></a><span data-ttu-id="7f689-427">AzureRM.SiteRecovery</span><span class="sxs-lookup"><span data-stu-id="7f689-427">AzureRM.SiteRecovery</span></span>
* <span data-ttu-id="7f689-428">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-428">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="7f689-429">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-429">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermsql"></a><span data-ttu-id="7f689-430">AzureRM.Sql</span><span class="sxs-lookup"><span data-stu-id="7f689-430">AzureRM.Sql</span></span>
* <span data-ttu-id="7f689-431">更新 Auditing 命令參數描述</span><span class="sxs-lookup"><span data-stu-id="7f689-431">Update the Auditing commands parameters description</span></span>
* <span data-ttu-id="7f689-432">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-432">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="7f689-433">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-433">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>
* <span data-ttu-id="7f689-434">已將 -AsJob 參數新增到長時間執行的 Cmdlet</span><span class="sxs-lookup"><span data-stu-id="7f689-434">Added -AsJob parameter to long running cmdlets</span></span>
* <span data-ttu-id="7f689-435">已從 Get-AzureRmSqlServiceObjective 中淘汰了 -DatabaseName 參數</span><span class="sxs-lookup"><span data-stu-id="7f689-435">Obsoleted -DatabaseName parameter from Get-AzureRmSqlServiceObjective</span></span>

#### <a name="azurermstorage"></a><span data-ttu-id="7f689-436">AzureRM.Storage</span><span class="sxs-lookup"><span data-stu-id="7f689-436">AzureRM.Storage</span></span>
* <span data-ttu-id="7f689-437">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-437">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="7f689-438">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-438">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>
* <span data-ttu-id="7f689-439">修正了以參數 -EnableEncryptionService None 執行 Cmdlet New-AzureRMStorageAccount 時，所發生的 null 參考問題</span><span class="sxs-lookup"><span data-stu-id="7f689-439">Fix a null reference issue of run cmdlet New-AzureRMStorageAccount with parameter -EnableEncryptionService None</span></span>
* <span data-ttu-id="7f689-440">已針對長時間執行的 Storage Cmdlet 新增 -AsJob 支援。</span><span class="sxs-lookup"><span data-stu-id="7f689-440">Added -AsJob support for long-running Storage cmdlets.</span></span> <span data-ttu-id="7f689-441">允許選取的 Cmdlet 在背景中執行，並傳回作業以追蹤及控制進度。</span><span class="sxs-lookup"><span data-stu-id="7f689-441">Allows selected cmdlets to run in the background and return a job to track and control progress.</span></span>
    - <span data-ttu-id="7f689-442">受影響的 Cmdlet 是適用於儲存體帳戶和儲存體帳戶網路規則的 New-、Remove-、Add- 和 Update-。</span><span class="sxs-lookup"><span data-stu-id="7f689-442">Affected cmdlets are New-, Remove-, Add-, and Update- for Storage Account and Storage Account Network Rule.</span></span>

#### <a name="azurermstreamanalytics"></a><span data-ttu-id="7f689-443">AzureRM.StreamAnalytics</span><span class="sxs-lookup"><span data-stu-id="7f689-443">AzureRM.StreamAnalytics</span></span>
* <span data-ttu-id="7f689-444">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-444">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="7f689-445">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-445">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermtrafficmanager"></a><span data-ttu-id="7f689-446">AzureRM.TrafficManager</span><span class="sxs-lookup"><span data-stu-id="7f689-446">AzureRM.TrafficManager</span></span>
* <span data-ttu-id="7f689-447">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-447">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="7f689-448">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-448">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermwebsites"></a><span data-ttu-id="7f689-449">AzureRM.Websites</span><span class="sxs-lookup"><span data-stu-id="7f689-449">AzureRM.Websites</span></span>
* <span data-ttu-id="7f689-450">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-450">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="7f689-451">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="7f689-451">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>
* <span data-ttu-id="7f689-452">已針對長時間執行的 Websites Cmdlet 新增 -AsJob 支援。</span><span class="sxs-lookup"><span data-stu-id="7f689-452">Added -AsJob support for long-running Websites cmdlets.</span></span> <span data-ttu-id="7f689-453">允許選取的 Cmdlet 在背景中執行，並傳回作業以追蹤及控制進度。</span><span class="sxs-lookup"><span data-stu-id="7f689-453">Allows selected cmdlets to run in the background and return a job to track and control progress.</span></span>
     - <span data-ttu-id="7f689-454">WebApps、AppServicePlan 和 Slots中，受影響的 Cmdlet 是 New-、Remove-、Add- 和 Set-</span><span class="sxs-lookup"><span data-stu-id="7f689-454">Affected cmdlets are New-, Remove-, Add-, and Set- for WebApps, AppServicePlan and Slots</span></span>

## <a name="2017128-version-511"></a><span data-ttu-id="7f689-455">2017.12.8 版本 5.1.1</span><span class="sxs-lookup"><span data-stu-id="7f689-455">2017.12.8 Version 5.1.1</span></span>
* <span data-ttu-id="7f689-456">AnalysisServices</span><span class="sxs-lookup"><span data-stu-id="7f689-456">AnalysisServices</span></span>
    - <span data-ttu-id="7f689-457">將位置的驗證集變更為動態對應，以便支援所有雲端。</span><span class="sxs-lookup"><span data-stu-id="7f689-457">Change validate set of location to dynamic lookup so that all clouds are supported.</span></span>
* <span data-ttu-id="7f689-458">自動化</span><span class="sxs-lookup"><span data-stu-id="7f689-458">Automation</span></span>
    - <span data-ttu-id="7f689-459">更新至 Import-AzureRMAutomationRunbook</span><span class="sxs-lookup"><span data-stu-id="7f689-459">Update to Import-AzureRMAutomationRunbook</span></span>
        - <span data-ttu-id="7f689-460">現在可支援 Python2 Runbook</span><span class="sxs-lookup"><span data-stu-id="7f689-460">Support is now being provided for Python2 runbooks</span></span>
* <span data-ttu-id="7f689-461">Batch</span><span class="sxs-lookup"><span data-stu-id="7f689-461">Batch</span></span>
    - <span data-ttu-id="7f689-462">修正錯誤：不含資源群組的帳戶作業無法自動偵測資源群組</span><span class="sxs-lookup"><span data-stu-id="7f689-462">Fixed a bug where account operations without a resource group failed to auto-detect the resource group</span></span>
* <span data-ttu-id="7f689-463">計算</span><span class="sxs-lookup"><span data-stu-id="7f689-463">Compute</span></span>
    - <span data-ttu-id="7f689-464">Get-AzureRmComputeResourceSku 會顯示區域資訊。</span><span class="sxs-lookup"><span data-stu-id="7f689-464">Get-AzureRmComputeResourceSku shows zone information.</span></span>
    - <span data-ttu-id="7f689-465">更新 Disable-AzureRmVmssDiskEncryption 以修正問題 https://github.com/Azure/azure-powershell/issues/5038</span><span class="sxs-lookup"><span data-stu-id="7f689-465">Update Disable-AzureRmVmssDiskEncryption to fix issue https://github.com/Azure/azure-powershell/issues/5038</span></span>
    - <span data-ttu-id="7f689-466">針對長時間執行的計算 Cmdlet 新增 -AsJob 支援。</span><span class="sxs-lookup"><span data-stu-id="7f689-466">Added -AsJob support for long-running Compute cmdlets.</span></span> <span data-ttu-id="7f689-467">允許選取的 Cmdlet 在背景中執行，並傳回作業以追蹤及控制進度。</span><span class="sxs-lookup"><span data-stu-id="7f689-467">Allows selected cmdlets to run in the background and return a job to track and control progress.</span></span>
        - <span data-ttu-id="7f689-468">受影響的 Cmdlet 包括：適用於虛擬機器和虛擬機器擴展集的 New-、Update-、Set-、Remove-、Start-、Restart- 和 Stop- Cmdlet</span><span class="sxs-lookup"><span data-stu-id="7f689-468">Affected cmdlets include: New-, Update-, Set-, Remove-, Start-, Restart-, Stop- cmdlets for Virtual Machines and Virtual Machine Scale Sets</span></span>
    - <span data-ttu-id="7f689-469">將簡化的參數集新增至 New-AzureRmVM，New-AzureRmVM 可使用智慧型預設值建立虛擬機器和所有必要的資源</span><span class="sxs-lookup"><span data-stu-id="7f689-469">Added simplified parameter set to New-AzureRmVM, which creates a Virtual Machine and all required resources using smart defaults</span></span>
* <span data-ttu-id="7f689-470">ContainerInstance</span><span class="sxs-lookup"><span data-stu-id="7f689-470">ContainerInstance</span></span>
    - <span data-ttu-id="7f689-471">套用 Azure 容器執行個體 SDK 2017-10-01</span><span class="sxs-lookup"><span data-stu-id="7f689-471">Apply Azure Container Instance SDK 2017-10-01</span></span>
        - <span data-ttu-id="7f689-472">支援容器的「執行到完成」作業</span><span class="sxs-lookup"><span data-stu-id="7f689-472">Support container run-to-completion</span></span>
        - <span data-ttu-id="7f689-473">支援 Azure 檔案磁碟區掛接</span><span class="sxs-lookup"><span data-stu-id="7f689-473">Support Azure File volume mount</span></span>
        - <span data-ttu-id="7f689-474">支援開啟多個公用 IP 的連接埠</span><span class="sxs-lookup"><span data-stu-id="7f689-474">Support opening multiple ports for public IP</span></span>
* <span data-ttu-id="7f689-475">ContainerRegistry</span><span class="sxs-lookup"><span data-stu-id="7f689-475">ContainerRegistry</span></span>
    - <span data-ttu-id="7f689-476">新增異地複寫與 Webhook 的 Cmdlet</span><span class="sxs-lookup"><span data-stu-id="7f689-476">New cmdlets for geo-replication and webhooks</span></span>
        - <span data-ttu-id="7f689-477">Get/New/Remove-AzureRmContainerRegistryReplication</span><span class="sxs-lookup"><span data-stu-id="7f689-477">Get/New/Remove-AzureRmContainerRegistryReplication</span></span>
        - <span data-ttu-id="7f689-478">Get/New/Remove/Test/Update-AzureRmContainerRegistryWebhook</span><span class="sxs-lookup"><span data-stu-id="7f689-478">Get/New/Remove/Test/Update-AzureRmContainerRegistryWebhook</span></span>
* <span data-ttu-id="7f689-479">DataFactories</span><span class="sxs-lookup"><span data-stu-id="7f689-479">DataFactories</span></span>
    - <span data-ttu-id="7f689-480">認證加密功能現在可與啟用的「遠端存取」(透過網路) 和停用的「遠端存取」(本機電腦) 搭配使用。</span><span class="sxs-lookup"><span data-stu-id="7f689-480">Credential encryption functionality now works with both "Remote Access" enabled (Over Network) and "Remote Access" disabled (Local Machine).</span></span>
* <span data-ttu-id="7f689-481">DataFactoryV2</span><span class="sxs-lookup"><span data-stu-id="7f689-481">DataFactoryV2</span></span>
    - <span data-ttu-id="7f689-482">新增兩個 Cmdlet：Update-AzureRmDataFactoryV2 和 Stop-AzureRmDataFactoryV2PipelineRun</span><span class="sxs-lookup"><span data-stu-id="7f689-482">Added two new cmdlets: Update-AzureRmDataFactoryV2 and Stop-AzureRmDataFactoryV2PipelineRun</span></span>
* <span data-ttu-id="7f689-483">DataLakeAnalytics</span><span class="sxs-lookup"><span data-stu-id="7f689-483">DataLakeAnalytics</span></span>
    - <span data-ttu-id="7f689-484">將名為 ScriptParameter 的參數新增至 Submit-AzureRmDataLakeAnalyticsJob</span><span class="sxs-lookup"><span data-stu-id="7f689-484">Added a parameter called ScriptParameter to Submit-AzureRmDataLakeAnalyticsJob</span></span>
        - <span data-ttu-id="7f689-485">可在 Submit-AzureRmDataLakeAnalyticsJob 上使用 Get-help 找到 ScriptParameter 的詳細資訊</span><span class="sxs-lookup"><span data-stu-id="7f689-485">Detailed information about ScriptParameter can be found using Get-Help on Submit-AzureRmDataLakeAnalyticsJob</span></span>
    - <span data-ttu-id="7f689-486">針對 New-AzureRmDataLakeAnalyticsAccount，已將參數 MaxDegreeOfParallelism 變更為 MaxAnalyticsUnits</span><span class="sxs-lookup"><span data-stu-id="7f689-486">For New-AzureRmDataLakeAnalyticsAccount, changed the parameter MaxDegreeOfParallelism to MaxAnalyticsUnits</span></span>
        - <span data-ttu-id="7f689-487">新增參數 MaxAnalyticsUnits 的別名：MaxDegreeOfParallelism</span><span class="sxs-lookup"><span data-stu-id="7f689-487">Added an alias for the parameter MaxAnalyticsUnits: MaxDegreeOfParallelism</span></span>
    - <span data-ttu-id="7f689-488">針對 New-AzureRmDataLakeAnalyticsComputePolicy，已將參數 MaxDegreeOfParallelismPerJob 變更為 MaxAnalyticsUnitsPerJob</span><span class="sxs-lookup"><span data-stu-id="7f689-488">For New-AzureRmDataLakeAnalyticsComputePolicy, changed the parameter MaxDegreeOfParallelismPerJob to MaxAnalyticsUnitsPerJob</span></span>
        - <span data-ttu-id="7f689-489">新增參數 MaxAnalyticsUnitsPerJob 的別名：MaxDegreeOfParallelismPerJob</span><span class="sxs-lookup"><span data-stu-id="7f689-489">Added an alias for the parameter MaxAnalyticsUnitsPerJob: MaxDegreeOfParallelismPerJob</span></span>
    - <span data-ttu-id="7f689-490">針對 Set-AzureRmDataLakeAnalyticsAccount，已將參數 MaxDegreeOfParallelism 變更為 MaxAnalyticsUnits</span><span class="sxs-lookup"><span data-stu-id="7f689-490">For Set-AzureRmDataLakeAnalyticsAccount, changed the parameter MaxDegreeOfParallelism to MaxAnalyticsUnits</span></span>
        - <span data-ttu-id="7f689-491">新增參數 MaxAnalyticsUnits 的別名：MaxDegreeOfParallelism</span><span class="sxs-lookup"><span data-stu-id="7f689-491">Added an alias for the parameter MaxAnalyticsUnits: MaxDegreeOfParallelism</span></span>
    - <span data-ttu-id="7f689-492">針對 Submit-AzureRmDataLakeAnalyticsJob，已將參數 DegreeOfParallelism 變更為 AnalyticsUnits</span><span class="sxs-lookup"><span data-stu-id="7f689-492">For Submit-AzureRmDataLakeAnalyticsJob, changed the parameter DegreeOfParallelism to AnalyticsUnits</span></span>
        - <span data-ttu-id="7f689-493">新增參數 AnalyticsUnits 的別名：DegreeOfParallelism</span><span class="sxs-lookup"><span data-stu-id="7f689-493">Added an alias for the parameter AnalyticsUnits: DegreeOfParallelism</span></span>
    - <span data-ttu-id="7f689-494">針對 Update-AzureRmDataLakeAnalyticsComputePolicy，已將參數 MaxDegreeOfParallelismPerJob 變更為 MaxAnalyticsUnitsPerJob</span><span class="sxs-lookup"><span data-stu-id="7f689-494">For Update-AzureRmDataLakeAnalyticsComputePolicy, changed the parameter MaxDegreeOfParallelismPerJob to MaxAnalyticsUnitsPerJob</span></span>
        - <span data-ttu-id="7f689-495">新增參數 MaxAnalyticsUnitsPerJob 的別名：MaxDegreeOfParallelismPerJob</span><span class="sxs-lookup"><span data-stu-id="7f689-495">Added an alias for the parameter MaxAnalyticsUnitsPerJob: MaxDegreeOfParallelismPerJob</span></span>
* <span data-ttu-id="7f689-496">MachineLearningCompute</span><span class="sxs-lookup"><span data-stu-id="7f689-496">MachineLearningCompute</span></span>
    - <span data-ttu-id="7f689-497">新增 Set-AzureRmMlOpCluster</span><span class="sxs-lookup"><span data-stu-id="7f689-497">Add Set-AzureRmMlOpCluster</span></span>
        - <span data-ttu-id="7f689-498">更新叢集的代理程式計數或 SSL 設定</span><span class="sxs-lookup"><span data-stu-id="7f689-498">Update a cluster's agent count or SSL configuration</span></span>
    - <span data-ttu-id="7f689-499">協調器屬性是選擇性項目</span><span class="sxs-lookup"><span data-stu-id="7f689-499">Orchestrator properties are optional</span></span>
        - <span data-ttu-id="7f689-500">服務會建立服務主體 (如果未提供的話)，因此協調器屬性現在是選擇性項目</span><span class="sxs-lookup"><span data-stu-id="7f689-500">The service will create a service principal if not provided, so the orchestrator properties are now optional</span></span>
* <span data-ttu-id="7f689-501">PowerBIEmbedded</span><span class="sxs-lookup"><span data-stu-id="7f689-501">PowerBIEmbedded</span></span>
    - <span data-ttu-id="7f689-502">新增 Power BI Embedded 容量 Cmdlet 的支援</span><span class="sxs-lookup"><span data-stu-id="7f689-502">Add support for Power BI Embedded Capacity cmdlets</span></span>
    - <span data-ttu-id="7f689-503">新增 Get-AzureRmPowerBIEmbeddedCapacity Cmdlet - 取得 PowerBI Embedded 容量的詳細資料。</span><span class="sxs-lookup"><span data-stu-id="7f689-503">New Cmdlet Get-AzureRmPowerBIEmbeddedCapacity - Gets the details of a PowerBI Embedded Capacity.</span></span>
    - <span data-ttu-id="7f689-504">新增 New-AzureRmPowerBIEmbeddedCapacity Cmdlet - 建立新的 PowerBI Embedded 容量</span><span class="sxs-lookup"><span data-stu-id="7f689-504">New Cmdlet New-AzureRmPowerBIEmbeddedCapacity - Creates a new PowerBI Embedded Capacity</span></span>
    - <span data-ttu-id="7f689-505">新增 Remove-AzureRmPowerBIEmbeddedCapacity Cmdlet - 刪除 PowerBI Embedded 容量的執行個體</span><span class="sxs-lookup"><span data-stu-id="7f689-505">New Cmdlet Remove-AzureRmPowerBIEmbeddedCapacity - Deletes an instance of PowerBI Embedded Capacity</span></span>
    - <span data-ttu-id="7f689-506">新增 Resume-AzureRmPowerBIEmbeddedCapacity Cmdlet - 恢復 PowerBI Embedded 容量的執行個體</span><span class="sxs-lookup"><span data-stu-id="7f689-506">New Cmdlet Resume-AzureRmPowerBIEmbeddedCapacity - Resumes an instance of PowerBI Embedded Capacity</span></span>
    - <span data-ttu-id="7f689-507">新增 Suspend-AzureRmPowerBIEmbeddedCapacity Cmdlet - 暫止 PowerBI Embedded 容量的執行個體</span><span class="sxs-lookup"><span data-stu-id="7f689-507">New Cmdlet Suspend-AzureRmPowerBIEmbeddedCapacity - Suspends an instance of PowerBI Embedded Capacity</span></span>
    - <span data-ttu-id="7f689-508">新增 Test-AzureRmPowerBIEmbeddedCapacity Cmdlet - 測試 PowerBI Embedded 容量執行個體是否存在</span><span class="sxs-lookup"><span data-stu-id="7f689-508">New Cmdlet Test-AzureRmPowerBIEmbeddedCapacity - Tests the existence of an instance of PowerBI Embedded Capacity</span></span>
    - <span data-ttu-id="7f689-509">新增 Update-AzureRmPowerBIEmbeddedCapacity Cmdlet - 修改 PowerBI Embedded 容量的執行個體</span><span class="sxs-lookup"><span data-stu-id="7f689-509">New Cmdlet Update-AzureRmPowerBIEmbeddedCapacity - Modifies an instance of PowerBI Embedded Capacity</span></span>
* <span data-ttu-id="7f689-510">設定檔</span><span class="sxs-lookup"><span data-stu-id="7f689-510">Profile</span></span>
    - <span data-ttu-id="7f689-511">已將 USGovernmentActiveDirectoryEndpoint 更新為 https://login.microsoftonline.us/</span><span class="sxs-lookup"><span data-stu-id="7f689-511">Updated USGovernmentActiveDirectoryEndpoint to https://login.microsoftonline.us/</span></span>
        - <span data-ttu-id="7f689-512">如需更多關於 Azure Government 端點對應的資訊，請參閱以下文章：https://docs.microsoft.com/en-us/azure/azure-government/documentation-government-developer-guide#endpoint-mapping</span><span class="sxs-lookup"><span data-stu-id="7f689-512">For more information about the Azure Government endpoint mappings, please see the following: https://docs.microsoft.com/en-us/azure/azure-government/documentation-government-developer-guide#endpoint-mapping</span></span>
    - <span data-ttu-id="7f689-513">新增 Cmdlet 的 -AsJob 支援，讓選取的 Cmdlet 可在背景中執行並傳回作業以追蹤和控制進度</span><span class="sxs-lookup"><span data-stu-id="7f689-513">Added -AsJob support for cmdlets, enabling selected cmdlets to execute in the background and return a job to track and control progress</span></span>
    - <span data-ttu-id="7f689-514">將 -AsJob 參數新增至 Get-AzureRmSubscription Cmdlet</span><span class="sxs-lookup"><span data-stu-id="7f689-514">Added -AsJob parameter to Get-AzureRmSubscription cmdlet</span></span>
* <span data-ttu-id="7f689-515">RecoveryServices.Backup</span><span class="sxs-lookup"><span data-stu-id="7f689-515">RecoveryServices.Backup</span></span>
    - <span data-ttu-id="7f689-516">修正錯誤：Get-AzureRmRecoveryServicesBackupItem 應針對容器名稱的篩選，執行不區分大小寫的比較。</span><span class="sxs-lookup"><span data-stu-id="7f689-516">Fixed bug - Get-AzureRmRecoveryServicesBackupItem should do case insensitive comparison for container name filter.</span></span>
    - <span data-ttu-id="7f689-517">修正錯誤：AzureVmItem 現在有屬性可顯示最後一次發生備份作業的時間 (LastBackupTime)。</span><span class="sxs-lookup"><span data-stu-id="7f689-517">Fixed bug - AzureVmItem now has a property that shows the last time a backup operation has happened - LastBackupTime.</span></span>
* <span data-ttu-id="7f689-518">資源</span><span class="sxs-lookup"><span data-stu-id="7f689-518">Resources</span></span>
    - <span data-ttu-id="7f689-519">修正問題：Get-AzureRMRoleAssignment 產生的指派結果沒有自訂角色的角色定義名稱</span><span class="sxs-lookup"><span data-stu-id="7f689-519">Fixed issue where Get-AzureRMRoleAssignment would result in a assignments without roledefiniton name for custom roles</span></span>
        - <span data-ttu-id="7f689-520">使用者現在使用 Get-AzureRMRoleAssignment 產生的指派，會具有任何角色類型的角色定義名稱</span><span class="sxs-lookup"><span data-stu-id="7f689-520">Users can now use Get-AzureRMRoleAssignment with assignments having roledefinition names irrespective of the type of role</span></span>
    - <span data-ttu-id="7f689-521">修正問題：當可指派的範圍內有新範圍時，Set-AzureRMRoleRoleDefinition 會用來擲回找不到 RD 的錯誤</span><span class="sxs-lookup"><span data-stu-id="7f689-521">Fixed issue where Set-AzureRMRoleRoleDefinition used to throw RD not found error when there was a new scope in assignablescopes</span></span>
        - <span data-ttu-id="7f689-522">使用者現在能在可指派的範圍內有新範圍時，使用 Set-AzureRMRoleRoleDefinition，且不受限於範圍的位置</span><span class="sxs-lookup"><span data-stu-id="7f689-522">Users can now use Set-AzureRMRoleRoleDefinition with assignable scopes including new scopes irrespective of the position of the scope</span></span>
    - <span data-ttu-id="7f689-523">允許範圍以 "/" 結尾</span><span class="sxs-lookup"><span data-stu-id="7f689-523">Allow scopes to end with "/"</span></span>
        - <span data-ttu-id="7f689-524">使用者現在可以使用範圍結尾為 "/" 的 RoleDefinition 和 RoleAssignment Commandlet (與 API 和 CLI 一致)</span><span class="sxs-lookup"><span data-stu-id="7f689-524">Users can now use RoleDefinition and RoleAssignment commandlets with scopes ending with "/" ,consistent with API and CLI</span></span>
    - <span data-ttu-id="7f689-525">允許使用者使用委派旗標建立 RoleAssignment</span><span class="sxs-lookup"><span data-stu-id="7f689-525">Allow users to create RoleAssignment using delegation flag</span></span>
        - <span data-ttu-id="7f689-526">使用者現在可以使用具有新增委派旗標選項的 New-AzureRMRoleAssignment</span><span class="sxs-lookup"><span data-stu-id="7f689-526">Users can now use New-AzureRMRoleAssignment with an option of adding the delegation flag</span></span>
    - <span data-ttu-id="7f689-527">修正 RoleAssignment 以遵守範圍參數</span><span class="sxs-lookup"><span data-stu-id="7f689-527">Fix RoleAssignment get to respect the scope parameter</span></span>
    - <span data-ttu-id="7f689-528">在 New-AzureRmRoleAssignment Commandlet 中新增 ServicePrincipalName 的別名</span><span class="sxs-lookup"><span data-stu-id="7f689-528">Add an alias for ServicePrincipalName in the New-AzureRmRoleAssignment Commandlet</span></span>
        - <span data-ttu-id="7f689-529">使用者現在使用 New-AzureRmRoleAssignment Commandlet 時，可使用 ApplicationId 而不是 ServicePrincipalName</span><span class="sxs-lookup"><span data-stu-id="7f689-529">Users can now use the ApplicationId instead of the ServicePrincipalName when using the New-AzureRmRoleAssignment commandlet</span></span>
* <span data-ttu-id="7f689-530">SiteRecovery</span><span class="sxs-lookup"><span data-stu-id="7f689-530">SiteRecovery</span></span>
    - <span data-ttu-id="7f689-531">針對此模組中的所有 Cmdlet 新增取代警告，為下一次的重大變更發行做好準備。</span><span class="sxs-lookup"><span data-stu-id="7f689-531">Add deprecation warnings for all cmdlets in this module in preparation for the next breaking change release.</span></span>
        - <span data-ttu-id="7f689-532">請參閱即將發行的重大變更指南，以了解如何從 AzureRM 移轉您的 Cmdlet。</span><span class="sxs-lookup"><span data-stu-id="7f689-532">Please see the upcoming breaking changes guide for more information on how to migrate your cmdlets from AzureRM.</span></span>
* <span data-ttu-id="7f689-533">Sql</span><span class="sxs-lookup"><span data-stu-id="7f689-533">Sql</span></span>
    - <span data-ttu-id="7f689-534">新增使用 Set-AzureRmSqlDatabase 重新命名資料庫的功能</span><span class="sxs-lookup"><span data-stu-id="7f689-534">Added ability to rename database using Set-AzureRmSqlDatabase</span></span>
    - <span data-ttu-id="7f689-535">已修正的問題 https://github.com/Azure/azure-powershell/issues/4974</span><span class="sxs-lookup"><span data-stu-id="7f689-535">Fixed issue https://github.com/Azure/azure-powershell/issues/4974</span></span>
        - <span data-ttu-id="7f689-536">對稽核 Cmdlet 提供無效的 AUDIT_CHANGED_GROUP 值不會再擲回錯誤，並且將在近期版本中移除。</span><span class="sxs-lookup"><span data-stu-id="7f689-536">Providing invalid AUDIT_CHANGED_GROUP value for auditing cmdlets no longer throws an error and will be removed in an upcoming release.</span></span>
    - <span data-ttu-id="7f689-537">已修正的問題 https://github.com/Azure/azure-powershell/issues/5046</span><span class="sxs-lookup"><span data-stu-id="7f689-537">Fixed issue https://github.com/Azure/azure-powershell/issues/5046</span></span>
        - <span data-ttu-id="7f689-538">稽核 Cmdlet 中的 AuditAction 參數不再遭到忽略</span><span class="sxs-lookup"><span data-stu-id="7f689-538">AuditAction parameter in auditing cmdlets is no longer being ignored</span></span>
    - <span data-ttu-id="7f689-539">修正在稽核 Cmdlet 中提供 'Secondary' StorageKeyType 時的問題</span><span class="sxs-lookup"><span data-stu-id="7f689-539">Fixed an issue in Auditing cmdlets when 'Secondary' StorageKeyType is provided</span></span>
        - <span data-ttu-id="7f689-540">在設定 Blob 稽核時，針對 StorageKeyType 參數提供 'Secondary' 值時，系統使用的不是次要金鑰，而是主要儲存體帳戶金鑰。</span><span class="sxs-lookup"><span data-stu-id="7f689-540">When setting blob auditing, the primary storage account key was used instead of the secondary key when providing 'Secondary' value for StorageKeyType parameter.</span></span>
    - <span data-ttu-id="7f689-541">變更 Set-AzureRmSqlServerTransparentDataEncryptionProtector 中的確認訊息文字</span><span class="sxs-lookup"><span data-stu-id="7f689-541">Changing the wording for confirmation message from Set-AzureRmSqlServerTransparentDataEncryptionProtector</span></span>
* <span data-ttu-id="7f689-542">Azure (RDFE)</span><span class="sxs-lookup"><span data-stu-id="7f689-542">Azure (RDFE)</span></span>
    - <span data-ttu-id="7f689-543">移除所有 RemoteApp Cmdlet</span><span class="sxs-lookup"><span data-stu-id="7f689-543">Removed all RemoteApp Cmdles</span></span>
* <span data-ttu-id="7f689-544">Azure.Storage</span><span class="sxs-lookup"><span data-stu-id="7f689-544">Azure.Storage</span></span>
    - <span data-ttu-id="7f689-545">升級至 Azure 儲存體用戶端程式庫 8.6.0 及 Azure 儲存體資料移動程式庫 0.6.5</span><span class="sxs-lookup"><span data-stu-id="7f689-545">Upgrade to Azure Storage Client Library 8.6.0 and Azure Storage DataMovement Library 0.6.5</span></span>

## <a name="20171110-version-501"></a><span data-ttu-id="7f689-546">2017.11.10 版本 5.0.1</span><span class="sxs-lookup"><span data-stu-id="7f689-546">2017.11.10 Version 5.0.1</span></span>
* <span data-ttu-id="7f689-547">固定組件載入問題造成在下列模組中執行 Cmdlet 時失敗：</span><span class="sxs-lookup"><span data-stu-id="7f689-547">Fixed assembly loading issue that caused some cmdlets to fail when executing in the following modules:</span></span>
    - <span data-ttu-id="7f689-548">AzureRM.ApiManagement</span><span class="sxs-lookup"><span data-stu-id="7f689-548">AzureRM.ApiManagement</span></span>
    - <span data-ttu-id="7f689-549">AzureRM.Backup</span><span class="sxs-lookup"><span data-stu-id="7f689-549">AzureRM.Backup</span></span>
    - <span data-ttu-id="7f689-550">AzureRM.Batch</span><span class="sxs-lookup"><span data-stu-id="7f689-550">AzureRM.Batch</span></span>
    - <span data-ttu-id="7f689-551">AzureRM.Compute</span><span class="sxs-lookup"><span data-stu-id="7f689-551">AzureRM.Compute</span></span>
    - <span data-ttu-id="7f689-552">AzureRM.DataFactories</span><span class="sxs-lookup"><span data-stu-id="7f689-552">AzureRM.DataFactories</span></span>
    - <span data-ttu-id="7f689-553">AzureRM.HDInsight</span><span class="sxs-lookup"><span data-stu-id="7f689-553">AzureRM.HDInsight</span></span>
    - <span data-ttu-id="7f689-554">AzureRM.KeyVault</span><span class="sxs-lookup"><span data-stu-id="7f689-554">AzureRM.KeyVault</span></span>
    - <span data-ttu-id="7f689-555">AzureRM.RecoveryServices</span><span class="sxs-lookup"><span data-stu-id="7f689-555">AzureRM.RecoveryServices</span></span>
    - <span data-ttu-id="7f689-556">AzureRM.RecoveryServices.Backup</span><span class="sxs-lookup"><span data-stu-id="7f689-556">AzureRM.RecoveryServices.Backup</span></span>
    - <span data-ttu-id="7f689-557">AzureRM.RecoveryServices.SiteRecovery</span><span class="sxs-lookup"><span data-stu-id="7f689-557">AzureRM.RecoveryServices.SiteRecovery</span></span>
    - <span data-ttu-id="7f689-558">AzureRM.RedisCache</span><span class="sxs-lookup"><span data-stu-id="7f689-558">AzureRM.RedisCache</span></span>
    - <span data-ttu-id="7f689-559">AzureRM.SiteRecovery</span><span class="sxs-lookup"><span data-stu-id="7f689-559">AzureRM.SiteRecovery</span></span>
    - <span data-ttu-id="7f689-560">AzureRM.Sql</span><span class="sxs-lookup"><span data-stu-id="7f689-560">AzureRM.Sql</span></span>
    - <span data-ttu-id="7f689-561">AzureRM.Storage</span><span class="sxs-lookup"><span data-stu-id="7f689-561">AzureRM.Storage</span></span>
    - <span data-ttu-id="7f689-562">AzureRM.StreamAnalytics</span><span class="sxs-lookup"><span data-stu-id="7f689-562">AzureRM.StreamAnalytics</span></span>

## <a name="2017118---version-500"></a><span data-ttu-id="7f689-563">2017.11.8 - 版本 5.0.0</span><span class="sxs-lookup"><span data-stu-id="7f689-563">2017.11.8 - Version 5.0.0</span></span>
* <span data-ttu-id="7f689-564">注意：這是重大變更版本。</span><span class="sxs-lookup"><span data-stu-id="7f689-564">NOTE: This is a breaking change release.</span></span> <span data-ttu-id="7f689-565">有關導入的重大變更完整清單，請參閱移轉指南 (https://aka.ms/azps-migration-guide)。</span><span class="sxs-lookup"><span data-stu-id="7f689-565">Please see the migration guide (https://aka.ms/azps-migration-guide) for a full list of introduced breaking changes.</span></span>
* <span data-ttu-id="7f689-566">AzureRM 中所有的 Cmdlet 現在都支援線上說明</span><span class="sxs-lookup"><span data-stu-id="7f689-566">All cmdlets in AzureRM now support online help</span></span>
    - <span data-ttu-id="7f689-567">執行 Get-Help 搭配 -Online 參數，以在您的預設網際網路瀏覽器中開啟線上說明</span><span class="sxs-lookup"><span data-stu-id="7f689-567">Run Get-Help with the -Online parameter to open the online help in your default Internet browser</span></span>
* <span data-ttu-id="7f689-568">AnalysisServices</span><span class="sxs-lookup"><span data-stu-id="7f689-568">AnalysisServices</span></span>
    * <span data-ttu-id="7f689-569">固定的 Synchronize-AzureAsInstance 命令搭配使用新 AsAzure REST API 以進行同步處理</span><span class="sxs-lookup"><span data-stu-id="7f689-569">Fixed Synchronize-AzureAsInstance command to work with new AsAzure REST API for sync</span></span>
* <span data-ttu-id="7f689-570">ApiManagement</span><span class="sxs-lookup"><span data-stu-id="7f689-570">ApiManagement</span></span>
    * <span data-ttu-id="7f689-571">有關 ApiManagement 在這一版所做的重大變更，請參閱移轉指南</span><span class="sxs-lookup"><span data-stu-id="7f689-571">Please see the migration guide for breaking changes made to ApiManagement this release</span></span>
    * <span data-ttu-id="7f689-572">已更新 Cmdlet Get-AzureRmApiManagementUser 以修正問題 https://github.com/Azure/azure-powershell/issues/4510</span><span class="sxs-lookup"><span data-stu-id="7f689-572">Updated Cmdlet Get-AzureRmApiManagementUser to fix issue https://github.com/Azure/azure-powershell/issues/4510</span></span>
    * <span data-ttu-id="7f689-573">已更新 Cmdlet New-AzureRmApiManagementApi 以建立具備 Empty Path 的 API https://github.com/Azure/azure-powershell/issues/4069</span><span class="sxs-lookup"><span data-stu-id="7f689-573">Updated Cmdlet New-AzureRmApiManagementApi to create Api with Empty Path https://github.com/Azure/azure-powershell/issues/4069</span></span>
* <span data-ttu-id="7f689-574">ApplicationInsights</span><span class="sxs-lookup"><span data-stu-id="7f689-574">ApplicationInsights</span></span>
    * <span data-ttu-id="7f689-575">新增命令以取得/建立/移除應用程式深入解析資源</span><span class="sxs-lookup"><span data-stu-id="7f689-575">Add commands to get/create/remove applicaiton insights resource</span></span>
        - <span data-ttu-id="7f689-576">Get-AzureRmApplicationInsights</span><span class="sxs-lookup"><span data-stu-id="7f689-576">Get-AzureRmApplicationInsights</span></span>
        - <span data-ttu-id="7f689-577">New-AzureRmApplicationInsights</span><span class="sxs-lookup"><span data-stu-id="7f689-577">New-AzureRmApplicationInsights</span></span>
        - <span data-ttu-id="7f689-578">Remove-AzureRmApplicationInsights</span><span class="sxs-lookup"><span data-stu-id="7f689-578">Remove-AzureRmApplicationInsights</span></span>
    * <span data-ttu-id="7f689-579">新增命令以取得/更新價格/應用程式深入解析資源的每日上限</span><span class="sxs-lookup"><span data-stu-id="7f689-579">Add commands to get/update pricing/daily cap of applicaiton insights resource</span></span>
        - <span data-ttu-id="7f689-580">Get-AzureRmApplicationInsights -IncludeDailyCap</span><span class="sxs-lookup"><span data-stu-id="7f689-580">Get-AzureRmApplicationInsights -IncludeDailyCap</span></span>
        - <span data-ttu-id="7f689-581">Set-AzureRmApplicationInsightsPricingPlan</span><span class="sxs-lookup"><span data-stu-id="7f689-581">Set-AzureRmApplicationInsightsPricingPlan</span></span>
        - <span data-ttu-id="7f689-582">Set-AzureRmApplicationInsightsDailyCap</span><span class="sxs-lookup"><span data-stu-id="7f689-582">Set-AzureRmApplicationInsightsDailyCap</span></span>
    * <span data-ttu-id="7f689-583">新增命令以取得/建立/更新/移除應用程式深入解析資源的連續匯出</span><span class="sxs-lookup"><span data-stu-id="7f689-583">Add commands to get/create/update/remove continuous export of applicaiton insights resource</span></span>
        - <span data-ttu-id="7f689-584">Get-AzureRmApplicationInsightsContinuousExport</span><span class="sxs-lookup"><span data-stu-id="7f689-584">Get-AzureRmApplicationInsightsContinuousExport</span></span>
        - <span data-ttu-id="7f689-585">Set-AzureRmApplicationInsightsContinuousExport</span><span class="sxs-lookup"><span data-stu-id="7f689-585">Set-AzureRmApplicationInsightsContinuousExport</span></span>
        - <span data-ttu-id="7f689-586">New-AzureRmApplicationInsightsContinuousExport</span><span class="sxs-lookup"><span data-stu-id="7f689-586">New-AzureRmApplicationInsightsContinuousExport</span></span>
        - <span data-ttu-id="7f689-587">Remove-AzureRmApplicationInsightsContinuousExport</span><span class="sxs-lookup"><span data-stu-id="7f689-587">Remove-AzureRmApplicationInsightsContinuousExport</span></span>
    * <span data-ttu-id="7f689-588">新增命令以取得/建立/移除應用程式深入解析資源的 API 金鑰</span><span class="sxs-lookup"><span data-stu-id="7f689-588">Add commands to get/create/remove api keys of applicaiton insights resoruce</span></span>
        - <span data-ttu-id="7f689-589">Get-AzureRmApplicationInsightsApiKey</span><span class="sxs-lookup"><span data-stu-id="7f689-589">Get-AzureRmApplicationInsightsApiKey</span></span>
        - <span data-ttu-id="7f689-590">New-AzureRmApplicationInsightsApiKey</span><span class="sxs-lookup"><span data-stu-id="7f689-590">New-AzureRmApplicationInsightsApiKey</span></span>
        - <span data-ttu-id="7f689-591">Remove-AzureRmApplicationInsightsApiKey</span><span class="sxs-lookup"><span data-stu-id="7f689-591">Remove-AzureRmApplicationInsightsApiKey</span></span>
* <span data-ttu-id="7f689-592">AzureBatch</span><span class="sxs-lookup"><span data-stu-id="7f689-592">AzureBatch</span></span>
    * <span data-ttu-id="7f689-593">將新參數新增至 `New-AzureRmBatchAccount`。</span><span class="sxs-lookup"><span data-stu-id="7f689-593">Added new parameters to `New-AzureRmBatchAccount`.</span></span>
        - <span data-ttu-id="7f689-594">`PoolAllocationMode`：在 Batch 帳戶中建立集區所使用的配置模式。</span><span class="sxs-lookup"><span data-stu-id="7f689-594">`PoolAllocationMode`: The allocation mode to use for creating pools in the Batch account.</span></span> <span data-ttu-id="7f689-595">若要在使用者的訂用帳戶中建立配置集區節點的 Batch 帳戶，請將此設為 `UserSubscription`。</span><span class="sxs-lookup"><span data-stu-id="7f689-595">To create a Batch account which allocates pool nodes in the user's subscription, set this to `UserSubscription`.</span></span>
        - <span data-ttu-id="7f689-596">`KeyVaultId`：與 Batch 帳戶相關的 Azure 金鑰保存庫之資源識別碼。</span><span class="sxs-lookup"><span data-stu-id="7f689-596">`KeyVaultId`: The resource ID of the Azure key vault associated with the Batch account.</span></span>
        - <span data-ttu-id="7f689-597">`KeyVaultUrl`：與 Batch 帳戶相關的 Azure 金鑰保存庫之 URL。</span><span class="sxs-lookup"><span data-stu-id="7f689-597">`KeyVaultUrl`: The URL of the Azure key vault associated with the Batch account.</span></span>
    * <span data-ttu-id="7f689-598">將參數更新為 `New-AzureBatchTask`。</span><span class="sxs-lookup"><span data-stu-id="7f689-598">Updated parameters to `New-AzureBatchTask`.</span></span>
        - <span data-ttu-id="7f689-599">移除 `RunElevated` 參數。</span><span class="sxs-lookup"><span data-stu-id="7f689-599">Removed the `RunElevated` switch.</span></span> <span data-ttu-id="7f689-600">已新增 `UserIdentity` 參數來取代 `RunElevated`，且對等的行為可藉由建構 `PSUserIdentity` 來達成，如下所示：</span><span class="sxs-lookup"><span data-stu-id="7f689-600">The `UserIdentity` parameter has been added to replace `RunElevated`, and the equivalent behavior can be achieved by constructing a `PSUserIdentity` as shown below:</span></span>
            - <span data-ttu-id="7f689-601">$autoUser = New-Object Microsoft.Azure.Commands.Batch.Models.PSAutoUserSpecification -ArgumentList @("Task", "Admin")</span><span class="sxs-lookup"><span data-stu-id="7f689-601">$autoUser = New-Object Microsoft.Azure.Commands.Batch.Models.PSAutoUserSpecification -ArgumentList @("Task", "Admin")</span></span>
            - <span data-ttu-id="7f689-602">$userIdentity = New-Object Microsoft.Azure.Commands.Batch.Models.PSUserIdentity $autoUser</span><span class="sxs-lookup"><span data-stu-id="7f689-602">$userIdentity = New-Object Microsoft.Azure.Commands.Batch.Models.PSUserIdentity $autoUser</span></span>
        - <span data-ttu-id="7f689-603">新增 `AuthenticationTokenSettings` 參數。</span><span class="sxs-lookup"><span data-stu-id="7f689-603">Added the `AuthenticationTokenSettings` parameter.</span></span> <span data-ttu-id="7f689-604">這個參數可讓您要求 Batch 服務在執行時向工作提供驗證權杖，而不必先將 Batch 帳戶金鑰傳遞至工作，才能對 Batch 服務發出要求。</span><span class="sxs-lookup"><span data-stu-id="7f689-604">This parameter allows you to request the Batch service provide an authentication token to the task when it runs, avoiding the need to pass Batch account keys to the task in order to issue requests to the Batch service.</span></span>
        - <span data-ttu-id="7f689-605">新增 `ContainerSettings` 參數。</span><span class="sxs-lookup"><span data-stu-id="7f689-605">Added the `ContainerSettings` parameter.</span></span>
            - <span data-ttu-id="7f689-606">這個參數可讓您要求 Batch 服務在容器內執行工作。</span><span class="sxs-lookup"><span data-stu-id="7f689-606">This parameter allows you to request the Batch service run the task inside a container.</span></span>
        - <span data-ttu-id="7f689-607">新增 `OutputFiles` 參數。</span><span class="sxs-lookup"><span data-stu-id="7f689-607">Added the `OutputFiles` parameter.</span></span>
            - <span data-ttu-id="7f689-608">這個參數可讓您設定在工作完成之後將檔案上傳至 Azure 儲存體。</span><span class="sxs-lookup"><span data-stu-id="7f689-608">This parameter allows you to configure the task to upload files to Azure Storage after it has finished.</span></span>
    * <span data-ttu-id="7f689-609">將參數更新為 `New-AzureBatchPool`。</span><span class="sxs-lookup"><span data-stu-id="7f689-609">Updated parameters to `New-AzureBatchPool`.</span></span>
        - <span data-ttu-id="7f689-610">新增 `UserAccounts` 參數。</span><span class="sxs-lookup"><span data-stu-id="7f689-610">Added the `UserAccounts` parameter.</span></span>
            - <span data-ttu-id="7f689-611">這個參數可定義集區中每個節點上所建立的使用者帳戶。</span><span class="sxs-lookup"><span data-stu-id="7f689-611">This parameter defines user accounts created on each node in the pool.</span></span>
        - <span data-ttu-id="7f689-612">新增 `TargetLowPriorityComputeNodes` 並將 `TargetDedicated` 重新命名為 `TargetDedicatedComputeNodes`。</span><span class="sxs-lookup"><span data-stu-id="7f689-612">Added `TargetLowPriorityComputeNodes` and renamed `TargetDedicated` to `TargetDedicatedComputeNodes`.</span></span>
            - <span data-ttu-id="7f689-613">針對 `TargetDedicatedComputeNodes` 參數已建立 `TargetDedicated` 別名。</span><span class="sxs-lookup"><span data-stu-id="7f689-613">A `TargetDedicated` alias was created for the `TargetDedicatedComputeNodes` parameter.</span></span>
        - <span data-ttu-id="7f689-614">新增 `NetworkConfiguration` 參數。</span><span class="sxs-lookup"><span data-stu-id="7f689-614">Added the `NetworkConfiguration` parameter.</span></span>
            - <span data-ttu-id="7f689-615">這個參數可讓您設定集區的網路設定。</span><span class="sxs-lookup"><span data-stu-id="7f689-615">This parameter allows you to configure the pools network settings.</span></span>
    * <span data-ttu-id="7f689-616">將參數更新為 `New-AzureBatchCertificate`。</span><span class="sxs-lookup"><span data-stu-id="7f689-616">Updated parameters to `New-AzureBatchCertificate`.</span></span>
        - <span data-ttu-id="7f689-617">`Password` 參數現在是 `SecureString`。</span><span class="sxs-lookup"><span data-stu-id="7f689-617">The `Password` parameter is now a `SecureString`.</span></span>
    * <span data-ttu-id="7f689-618">將參數更新為 `New-AzureBatchComputeNodeUser`。</span><span class="sxs-lookup"><span data-stu-id="7f689-618">Updated parameters to `New-AzureBatchComputeNodeUser`.</span></span>
        - <span data-ttu-id="7f689-619">`Password` 參數現在是 `SecureString`。</span><span class="sxs-lookup"><span data-stu-id="7f689-619">The `Password` parameter is now a `SecureString`.</span></span>
    * <span data-ttu-id="7f689-620">將參數更新為 `Set-AzureBatchComputeNodeUser`。</span><span class="sxs-lookup"><span data-stu-id="7f689-620">Updated parameters to `Set-AzureBatchComputeNodeUser`.</span></span>
        - <span data-ttu-id="7f689-621">`Password` 參數現在是 `SecureString`。</span><span class="sxs-lookup"><span data-stu-id="7f689-621">The `Password` parameter is now a `SecureString`.</span></span>
    * <span data-ttu-id="7f689-622">在 `Get-AzureBatchNodeFile`、`Get-AzureBatchNodeFileContent` 和 `Remove-AzureBatchNodeFile` 上將 `Name` 參數重新命名為 `Path`。</span><span class="sxs-lookup"><span data-stu-id="7f689-622">Renamed the `Name` parameter to `Path` on `Get-AzureBatchNodeFile`, `Get-AzureBatchNodeFileContent`, and `Remove-AzureBatchNodeFile`.</span></span>
        - <span data-ttu-id="7f689-623">針對 `Path` 參數已建立 `Name` 別名。</span><span class="sxs-lookup"><span data-stu-id="7f689-623">A `Name` alias was created for the `Path` parameter.</span></span>
    * <span data-ttu-id="7f689-624">物件的變更</span><span class="sxs-lookup"><span data-stu-id="7f689-624">Changes to objects</span></span>
        - <span data-ttu-id="7f689-625">請參閱 Batch 變更記錄取得完整清單</span><span class="sxs-lookup"><span data-stu-id="7f689-625">Please see the Batch change log for the full list</span></span>
    * <span data-ttu-id="7f689-626">新增 Azure Active Directory 型驗證支援。</span><span class="sxs-lookup"><span data-stu-id="7f689-626">Added support for Azure Active Directory based authentication.</span></span>
        - <span data-ttu-id="7f689-627">若要使用 Azure Active Directory 驗證，請使用 `Get-AzureRmBatchAccount` Cmdlet 擷取 `BatchAccountContext` 物件，並將此 `BatchAccountContext` 提供至 Batch 服務 Cmdlet 的 `-BatchContext` 參數。</span><span class="sxs-lookup"><span data-stu-id="7f689-627">To use Azure Active Directory authentication, retrieve a `BatchAccountContext` object using the `Get-AzureRmBatchAccount` cmdlet, and supply this `BatchAccountContext` to the `-BatchContext` parameter of a Batch service cmdlet.</span></span> <span data-ttu-id="7f689-628">對於具有 `PoolAllocationMode = UserSubscription` 的帳戶，Azure Active Directory 驗證為必要。</span><span class="sxs-lookup"><span data-stu-id="7f689-628">Azure Active Directory authentication is mandatory for accounts with `PoolAllocationMode = UserSubscription`.</span></span>
        - <span data-ttu-id="7f689-629">對於現有帳戶或以 `PoolAllocationMode = BatchService` 建立的新帳戶，您可以藉由使用 `Get-AzureRmBatchAccoutKeys` Cmdlet 擷取 `BatchAccountContext` 物件，繼續使用共用金鑰驗證。</span><span class="sxs-lookup"><span data-stu-id="7f689-629">For existing accounts or for new accounts created with `PoolAllocationMode = BatchService`, you may continue to use shared key authentication by retrieving a `BatchAccountContext` object using the `Get-AzureRmBatchAccoutKeys` cmdlet.</span></span>
* <span data-ttu-id="7f689-630">計算</span><span class="sxs-lookup"><span data-stu-id="7f689-630">Compute</span></span>
    * <span data-ttu-id="7f689-631">Azure 磁碟加密延伸模組命令</span><span class="sxs-lookup"><span data-stu-id="7f689-631">Azure Disk Encryption Extension Commands</span></span>
        - <span data-ttu-id="7f689-632">'Set-AzureRmVmDiskEncryptionExtension' 的新參數：'-EncryptFormatAll' 加密格式資料磁碟</span><span class="sxs-lookup"><span data-stu-id="7f689-632">New Parameter for 'Set-AzureRmVmDiskEncryptionExtension': '-EncryptFormatAll' encrypt formats data disks</span></span>
        - <span data-ttu-id="7f689-633">'Set-AzureRmVmDiskEncryptionExtension' 的新參數：'-ExtensionPublisherName' 和 '-ExtensionType' 允許切換至延伸模組的其他版本</span><span class="sxs-lookup"><span data-stu-id="7f689-633">New Parameters for 'Set-AzureRmVmDiskEncryptionExtension': '-ExtensionPublisherName' and '-ExtensionType' allow switching to other versions of the extension</span></span>
        - <span data-ttu-id="7f689-634">'Disable-AzureRmVmDiskEncryption' 的新參數：'-ExtensionPublisherName' 和 '-ExtensionType' 允許切換至延伸模組的其他版本</span><span class="sxs-lookup"><span data-stu-id="7f689-634">New Parameters for 'Disable-AzureRmVmDiskEncryption': '-ExtensionPublisherName' and '-ExtensionType' allow switching to other versions of the extension</span></span>
        - <span data-ttu-id="7f689-635">'Get-AzureRmVmDiskEncryptionStatus' 的新參數：'-ExtensionPublisherName' 和 '-ExtensionType' 允許切換至延伸模組的其他版本</span><span class="sxs-lookup"><span data-stu-id="7f689-635">New Parameters for 'Get-AzureRmVmDiskEncryptionStatus': '-ExtensionPublisherName' and '-ExtensionType' allow switching to other versions of the extension</span></span>
* <span data-ttu-id="7f689-636">DataLakeAnalytics</span><span class="sxs-lookup"><span data-stu-id="7f689-636">DataLakeAnalytics</span></span>
    * <span data-ttu-id="7f689-637">有關 DataLakeAnalytics 在這一版所做的重大變更，請參閱移轉指南</span><span class="sxs-lookup"><span data-stu-id="7f689-637">Please see the migration guide for breaking changes made to DataLakeAnalytics this release</span></span>
    * <span data-ttu-id="7f689-638">變更 Get-AzureRmDataLakeAnalyticsAccount 兩種 OutputTypes 的其中一種</span><span class="sxs-lookup"><span data-stu-id="7f689-638">Changed one of the two OutputTypes of Get-AzureRmDataLakeAnalyticsAccount</span></span>
        - <span data-ttu-id="7f689-639">List\<DataLakeAnalyticsAccount> 到 List\<PSDataLakeAnalyticsAccountBasic></span><span class="sxs-lookup"><span data-stu-id="7f689-639">List\<DataLakeAnalyticsAccount> to List\<PSDataLakeAnalyticsAccountBasic></span></span>
        - <span data-ttu-id="7f689-640">PSDataLakeAnalyticsAccountBasic 的屬性是 DataLakeAnalyticsAccount 屬性的 strict 子集</span><span class="sxs-lookup"><span data-stu-id="7f689-640">The properties of PSDataLakeAnalyticsAccountBasic is a strict subset of the properties of DataLakeAnalyticsAccount</span></span>
        - <span data-ttu-id="7f689-641">服務不會傳回 DataLakeAnalyticsAccount 中的其他屬性。</span><span class="sxs-lookup"><span data-stu-id="7f689-641">The additional properties that are in DataLakeAnalyticsAccount are not returned by the service.</span></span>  <span data-ttu-id="7f689-642">因此，這項變更是為了準確反映此情況。</span><span class="sxs-lookup"><span data-stu-id="7f689-642">Therefore, this change is to reflect this accurately.</span></span> <span data-ttu-id="7f689-643">這些額外屬性仍然在 PSDataLakeAnalyticsAccountBasic 中，但被標記為 [已淘汰]。</span><span class="sxs-lookup"><span data-stu-id="7f689-643">These additional properties are still in PSDataLakeAnalyticsAccountBasic, but they are tagged as Obsolete.</span></span>
    * <span data-ttu-id="7f689-644">變更 Get-AzureRmDataLakeAnalyticsJob 兩種 OutputTypes 的其中一種</span><span class="sxs-lookup"><span data-stu-id="7f689-644">Changed one of the two OutputTypes of Get-AzureRmDataLakeAnalyticsJob</span></span>
        - <span data-ttu-id="7f689-645">List\<JobInformation> 到 List\<PSJobInformationBasic></span><span class="sxs-lookup"><span data-stu-id="7f689-645">List\<JobInformation> to List\<PSJobInformationBasic></span></span>
        - <span data-ttu-id="7f689-646">PSJobInformationBasic 的屬性是 JobInformation 屬性的 strict 子集</span><span class="sxs-lookup"><span data-stu-id="7f689-646">The properties of PSJobInformationBasic is a strict subset of the properties of JobInformation</span></span>
        - <span data-ttu-id="7f689-647">服務不會傳回 JobInformation 中的其他屬性。</span><span class="sxs-lookup"><span data-stu-id="7f689-647">The additional properties that are in JobInformation are not returned by the service.</span></span>  <span data-ttu-id="7f689-648">因此，這項變更是為了準確反映此情況。</span><span class="sxs-lookup"><span data-stu-id="7f689-648">Therefore, this change is to reflect this accurately.</span></span> <span data-ttu-id="7f689-649">這些額外屬性仍然在 PSJobInformationBasic 中，但被標記為 [已淘汰]。</span><span class="sxs-lookup"><span data-stu-id="7f689-649">These additional properties are still in PSJobInformationBasic, but they are tagged as Obsolete.</span></span>
* <span data-ttu-id="7f689-650">DataLakeStore</span><span class="sxs-lookup"><span data-stu-id="7f689-650">DataLakeStore</span></span>
    * <span data-ttu-id="7f689-651">有關 DataLakeStore 在這一版所做的重大變更，請參閱移轉指南</span><span class="sxs-lookup"><span data-stu-id="7f689-651">Please see the migration guide for breaking changes made to DataLakeStore this release</span></span>
    * <span data-ttu-id="7f689-652">變更 Get-AzureRmDataLakeStoreAccount 兩種 OutputTypes 的其中一種</span><span class="sxs-lookup"><span data-stu-id="7f689-652">Changed one of the two OutputTypes of Get-AzureRmDataLakeStoreAccount</span></span>
        - <span data-ttu-id="7f689-653">List\<PSDataLakeStoreAccount> 到 List\<PSDataLakeStoreAccountBasic></span><span class="sxs-lookup"><span data-stu-id="7f689-653">List\<PSDataLakeStoreAccount> to List\<PSDataLakeStoreAccountBasic></span></span>
        - <span data-ttu-id="7f689-654">PSDataLakeStoreAccountBasic 的屬性是 PSDataLakeStoreAccount 屬性的 strict 子集</span><span class="sxs-lookup"><span data-stu-id="7f689-654">The properties of PSDataLakeStoreAccountBasic is a strict subset of the properties of PSDataLakeStoreAccount</span></span>
        - <span data-ttu-id="7f689-655">服務不會傳回 PSDataLakeStoreAccount 中的其他屬性。</span><span class="sxs-lookup"><span data-stu-id="7f689-655">The additional properties that are in PSDataLakeStoreAccount are not returned by the service.</span></span>  <span data-ttu-id="7f689-656">因此，這項變更是為了準確反映此情況。</span><span class="sxs-lookup"><span data-stu-id="7f689-656">Therefore, this change is to reflect this accurately.</span></span> <span data-ttu-id="7f689-657">這些額外屬性仍然在 PSDataLakeStoreAccountBasic 中，但被標記為 [已淘汰]。</span><span class="sxs-lookup"><span data-stu-id="7f689-657">These additional properties are still in PSDataLakeStoreAccountBasic, but they are tagged as Obsolete.</span></span>
* <span data-ttu-id="7f689-658">Dns</span><span class="sxs-lookup"><span data-stu-id="7f689-658">Dns</span></span>
    * <span data-ttu-id="7f689-659">Azure DNS 中 CAA 記錄型別的支援</span><span class="sxs-lookup"><span data-stu-id="7f689-659">Support for CAA record types in Azure DNS</span></span>
       - <span data-ttu-id="7f689-660">支援 CAA 記錄型別上的所有作業</span><span class="sxs-lookup"><span data-stu-id="7f689-660">Supports all operations on CAA record type</span></span>
* <span data-ttu-id="7f689-661">EventHub</span><span class="sxs-lookup"><span data-stu-id="7f689-661">EventHub</span></span>
    * <span data-ttu-id="7f689-662">有關 EventHub 在這一版所做的重大變更，請參閱移轉指南</span><span class="sxs-lookup"><span data-stu-id="7f689-662">Please see the migration guide for breaking changes made to EventHub this release</span></span>
* <span data-ttu-id="7f689-663">深入解析</span><span class="sxs-lookup"><span data-stu-id="7f689-663">Insights</span></span>
    * <span data-ttu-id="7f689-664">有關深入解析在這一版所做的重大變更，請參閱移轉指南</span><span class="sxs-lookup"><span data-stu-id="7f689-664">Please see the migration guide for breaking changes made to Insights this release</span></span>
* <span data-ttu-id="7f689-665">網路</span><span class="sxs-lookup"><span data-stu-id="7f689-665">Network</span></span>
    * <span data-ttu-id="7f689-666">有關網路在這一版所做的重大變更，請參閱移轉指南</span><span class="sxs-lookup"><span data-stu-id="7f689-666">Please see the migration guide for breaking changes made to Network this release</span></span>
    * <span data-ttu-id="7f689-667">新增 Cmdlet 以針對指定的 Azure 區域列出可用的網際網路服務提供者</span><span class="sxs-lookup"><span data-stu-id="7f689-667">Added cmdlet to list available internet service providers for a specified Azure region</span></span>
        - <span data-ttu-id="7f689-668">Get-AzureRmNetworkWatcherReachabilityProvidersList</span><span class="sxs-lookup"><span data-stu-id="7f689-668">Get-AzureRmNetworkWatcherReachabilityProvidersList</span></span>
    * <span data-ttu-id="7f689-669">新增 Cmdlet 以取得從指定位置到 Azure 區域的網際網路服務提供者相對延遲分數</span><span class="sxs-lookup"><span data-stu-id="7f689-669">Added cmdlet to get the relative latency score for internet service providers from a specified location to Azure regions</span></span>
        - <span data-ttu-id="7f689-670">Get-AzureRmNetworkWatcherReachabilityReport</span><span class="sxs-lookup"><span data-stu-id="7f689-670">Get-AzureRmNetworkWatcherReachabilityReport</span></span>
* <span data-ttu-id="7f689-671">設定檔</span><span class="sxs-lookup"><span data-stu-id="7f689-671">Profile</span></span>
    - <span data-ttu-id="7f689-672">Set-AzureRmDefault</span><span class="sxs-lookup"><span data-stu-id="7f689-672">Set-AzureRmDefault</span></span>
        - <span data-ttu-id="7f689-673">使用這個 Cmdlet 設定預設的資源群組。</span><span class="sxs-lookup"><span data-stu-id="7f689-673">Use this cmdlet to set a default resource group.</span></span>  <span data-ttu-id="7f689-674">對於某些 Cmdlet，這會讓 -ResourceGroup 參數成為選用，且在未指定資源群組時將使用預設值</span><span class="sxs-lookup"><span data-stu-id="7f689-674">This will make the -ResourceGroup parameter optional for some cmdlets, and will use the default when a resource group is not specified</span></span>
        - ```Set-AzureRmDefault -ResourceGroupName "ExampleResourceGroup"```
        - <span data-ttu-id="7f689-675">如果指定的資源群組存在於訂用帳戶中，則此資源群組將會設為預設值。</span><span class="sxs-lookup"><span data-stu-id="7f689-675">If resource group specified exists in the subscription, this resource group will be set to default.</span></span>  <span data-ttu-id="7f689-676">否則，將會建立該資源群組，並將其設為預設值。</span><span class="sxs-lookup"><span data-stu-id="7f689-676">Otherwise, the resource group will be created and then set to default.</span></span>
    - <span data-ttu-id="7f689-677">Get-AzureRmDefault</span><span class="sxs-lookup"><span data-stu-id="7f689-677">Get-AzureRmDefault</span></span>
        - <span data-ttu-id="7f689-678">使用這個 Cmdlet 取得目前預設的資源群組 (和未來其他的預設)。</span><span class="sxs-lookup"><span data-stu-id="7f689-678">Use this cmdlet to get the current default resource group (and other defaults in the future).</span></span>
        - ```Get-AzureRmDefault -ResourceGroup```
    - <span data-ttu-id="7f689-679">Clear-AzureRmDefault</span><span class="sxs-lookup"><span data-stu-id="7f689-679">Clear-AzureRmDefault</span></span>
        - <span data-ttu-id="7f689-680">使用這個 Cmdlet 移除目前預設的資源群組</span><span class="sxs-lookup"><span data-stu-id="7f689-680">Use this cmdlet to remove the current default resource group</span></span>
        - ```Clear-AzureRmDefault -ResourceGroup```
    - <span data-ttu-id="7f689-681">Add-AzureRmEnvironment 和 Set-AzureRmEnvironment</span><span class="sxs-lookup"><span data-stu-id="7f689-681">Add-AzureRmEnvironment and Set-AzureRmEnvironment</span></span>
        - <span data-ttu-id="7f689-682">新增 BatchAudience 參數，可讓您指定在取得 Batch 服務驗證權杖時所要使用的 Azure Batch Active Directory 對象。</span><span class="sxs-lookup"><span data-stu-id="7f689-682">Add the BatchAudience parameter, which allows you to specify the Azure Batch Active Directory audience to use when acquiring authentication tokens for the Batch service.</span></span>
* <span data-ttu-id="7f689-683">RecoveryServices.Backup</span><span class="sxs-lookup"><span data-stu-id="7f689-683">RecoveryServices.Backup</span></span>
    * <span data-ttu-id="7f689-684">新增 Cmdlet 以執行立即檔案復原。</span><span class="sxs-lookup"><span data-stu-id="7f689-684">Added cmdlets to perform instant file recovery.</span></span>
        - <span data-ttu-id="7f689-685">Get-AzureRmRecoveryServicesBackupRPMountScript</span><span class="sxs-lookup"><span data-stu-id="7f689-685">Get-AzureRmRecoveryServicesBackupRPMountScript</span></span>
        - <span data-ttu-id="7f689-686">Disable-AzureRmRecoveryServicesBackupRPMountScript</span><span class="sxs-lookup"><span data-stu-id="7f689-686">Disable-AzureRmRecoveryServicesBackupRPMountScript</span></span>
    * <span data-ttu-id="7f689-687">將 RecoveryServices.Backup SDK 更新至最新版本</span><span class="sxs-lookup"><span data-stu-id="7f689-687">Updated RecoveryServices.Backup SDK version to the latest</span></span>
    * <span data-ttu-id="7f689-688">更新 Azure VM 工作負載的測試，如此一來測試回合所需的所有設定便由測試本身完成。</span><span class="sxs-lookup"><span data-stu-id="7f689-688">Updated tests for the Azure VM workload so that, all setups needed for test runs are done by the tests themselves.</span></span>
    * <span data-ttu-id="7f689-689">修正 https://github.com/Azure/azure-powershell/issues/3164</span><span class="sxs-lookup"><span data-stu-id="7f689-689">Fixes https://github.com/Azure/azure-powershell/issues/3164</span></span>
* <span data-ttu-id="7f689-690">RecoveryServices.SiteRecovery</span><span class="sxs-lookup"><span data-stu-id="7f689-690">RecoveryServices.SiteRecovery</span></span>
    * <span data-ttu-id="7f689-691">ASR VMware 到 Azure Site Recovery 的變更 (Cmdlet 目前支援企業到企業、企業到 Azure、HyperV 到 Azure 的作業)</span><span class="sxs-lookup"><span data-stu-id="7f689-691">Changes for ASR VMware to Azure Site Recovery (cmdlets are currently supporting operations for Enterprise to Enterprise, Enterprise to Azure, HyperV to Azure)</span></span>
        - <span data-ttu-id="7f689-692">New-AzureRmRecoveryServicesAsrPolicy</span><span class="sxs-lookup"><span data-stu-id="7f689-692">New-AzureRmRecoveryServicesAsrPolicy</span></span>
        - <span data-ttu-id="7f689-693">New-AzureRmRecoveryServicesAsrProtectedItem</span><span class="sxs-lookup"><span data-stu-id="7f689-693">New-AzureRmRecoveryServicesAsrProtectedItem</span></span>
        - <span data-ttu-id="7f689-694">Update-AzureRmRecoveryServicesAsrPolicy</span><span class="sxs-lookup"><span data-stu-id="7f689-694">Update-AzureRmRecoveryServicesAsrPolicy</span></span>
        - <span data-ttu-id="7f689-695">Update-AzureRmRecoveryServicesAsrProtectionDirection</span><span class="sxs-lookup"><span data-stu-id="7f689-695">Update-AzureRmRecoveryServicesAsrProtectionDirection</span></span>
    * <span data-ttu-id="7f689-696">新增以 AAD 為基礎的保存庫支援</span><span class="sxs-lookup"><span data-stu-id="7f689-696">Added support to AAD-based vault</span></span>
    * <span data-ttu-id="7f689-697">新增 Cmdlet 以管理 VCenter 資源</span><span class="sxs-lookup"><span data-stu-id="7f689-697">Added cmdlets to manage VCenter resources</span></span>
        - <span data-ttu-id="7f689-698">Get-AzureRmRecoveryServicesAsrVCenter</span><span class="sxs-lookup"><span data-stu-id="7f689-698">Get-AzureRmRecoveryServicesAsrVCenter</span></span>
        - <span data-ttu-id="7f689-699">New-AzureRmRecoveryServicesAsrVCenter</span><span class="sxs-lookup"><span data-stu-id="7f689-699">New-AzureRmRecoveryServicesAsrVCenter</span></span>
        - <span data-ttu-id="7f689-700">Remove-AzureRmRecoveryServicesAsrVCenter</span><span class="sxs-lookup"><span data-stu-id="7f689-700">Remove-AzureRmRecoveryServicesAsrVCenter</span></span>
        - <span data-ttu-id="7f689-701">Update-AzureRmRecoveryServicesAsrVCenter</span><span class="sxs-lookup"><span data-stu-id="7f689-701">Update-AzureRmRecoveryServicesAsrVCenter</span></span>
    * <span data-ttu-id="7f689-702">新增其他 Cmdlet</span><span class="sxs-lookup"><span data-stu-id="7f689-702">Added other cmdlets</span></span>
        - <span data-ttu-id="7f689-703">Get-AzureRmRecoveryServicesAsrAlertSetting</span><span class="sxs-lookup"><span data-stu-id="7f689-703">Get-AzureRmRecoveryServicesAsrAlertSetting</span></span>
        - <span data-ttu-id="7f689-704">Get-AzureRmRecoveryServicesAsrEvent</span><span class="sxs-lookup"><span data-stu-id="7f689-704">Get-AzureRmRecoveryServicesAsrEvent</span></span>
        - <span data-ttu-id="7f689-705">New-AzureRmRecoveryServicesAsrProtectableItem</span><span class="sxs-lookup"><span data-stu-id="7f689-705">New-AzureRmRecoveryServicesAsrProtectableItem</span></span>
        - <span data-ttu-id="7f689-706">Set-AzureRmRecoveryServicesAsrAlertSetting</span><span class="sxs-lookup"><span data-stu-id="7f689-706">Set-AzureRmRecoveryServicesAsrAlertSetting</span></span>
        - <span data-ttu-id="7f689-707">Start-AzureRmRecoveryServicesAsrResynchronizeReplicationJob</span><span class="sxs-lookup"><span data-stu-id="7f689-707">Start-AzureRmRecoveryServicesAsrResynchronizeReplicationJob</span></span>
        - <span data-ttu-id="7f689-708">Start-AzureRmRecoveryServicesAsrSwitchProcessServerJob</span><span class="sxs-lookup"><span data-stu-id="7f689-708">Start-AzureRmRecoveryServicesAsrSwitchProcessServerJob</span></span>
        - <span data-ttu-id="7f689-709">Start-AzureRmRecoveryServicesAsrTestFailoverCleanupJob</span><span class="sxs-lookup"><span data-stu-id="7f689-709">Start-AzureRmRecoveryServicesAsrTestFailoverCleanupJob</span></span>
        - <span data-ttu-id="7f689-710">Update-AzureRmRecoveryServicesAsrMobilityService</span><span class="sxs-lookup"><span data-stu-id="7f689-710">Update-AzureRmRecoveryServicesAsrMobilityService</span></span>
* <span data-ttu-id="7f689-711">ServiceBus</span><span class="sxs-lookup"><span data-stu-id="7f689-711">ServiceBus</span></span>
    - <span data-ttu-id="7f689-712">有關 ServiceBus 在這一版所做的重大變更，請參閱移轉指南</span><span class="sxs-lookup"><span data-stu-id="7f689-712">Please see the migration guide for breaking changes made to ServiceBus this release</span></span>
* <span data-ttu-id="7f689-713">Sql</span><span class="sxs-lookup"><span data-stu-id="7f689-713">Sql</span></span>
    * <span data-ttu-id="7f689-714">新增對列出和取消資料庫上非同步 updateslo 作業的支援</span><span class="sxs-lookup"><span data-stu-id="7f689-714">Adding support for list and cancel the asynchronous updateslo operation on the database</span></span>
        - <span data-ttu-id="7f689-715">更新現有的 Cmdlet Get-AzureRmSqlDatabaseActivity 以傳回 DB updateslo 作業狀態。</span><span class="sxs-lookup"><span data-stu-id="7f689-715">update existing cmdlet Get-AzureRmSqlDatabaseActivity to return DB updateslo operation status.</span></span>
        - <span data-ttu-id="7f689-716">新增新的 Cmdlet Stop-AzureRmSqlDatabaseActivity 以取消資料庫上的非同步 updateslo 作業。</span><span class="sxs-lookup"><span data-stu-id="7f689-716">add new cmdlet Stop-AzureRmSqlDatabaseActivity for cancel the asynchronous updateslo operation on the database.</span></span>
    * <span data-ttu-id="7f689-717">新增對資料庫和彈性集區的區域備援支援</span><span class="sxs-lookup"><span data-stu-id="7f689-717">Adding support for Zone Redundancy for databases and elastic pools</span></span>
        - <span data-ttu-id="7f689-718">將 ZoneRedundant 切換參數新增至 New-AzureRmSqlDatabase</span><span class="sxs-lookup"><span data-stu-id="7f689-718">Adding ZoneRedundant switch parameter to New-AzureRmSqlDatabase</span></span>
        - <span data-ttu-id="7f689-719">將 ZoneRedundant 切換參數新增至 Set-AzureRmSqlDatabase</span><span class="sxs-lookup"><span data-stu-id="7f689-719">Adding ZoneRedundant switch parameter to Set-AzureRmSqlDatabase</span></span>
        - <span data-ttu-id="7f689-720">將 ZoneRedundant 切換參數新增至 New-AzureRmSqlElasticPool</span><span class="sxs-lookup"><span data-stu-id="7f689-720">Adding ZoneRedundant switch parameter to New-AzureRmSqlElasticPool</span></span>
        - <span data-ttu-id="7f689-721">將 ZoneRedundant 切換參數新增至 Set-AzureRmSqlElasticPool</span><span class="sxs-lookup"><span data-stu-id="7f689-721">Adding ZoneRedundant switch parameter to Set-AzureRmSqlElasticPool</span></span>
    * <span data-ttu-id="7f689-722">新增對伺服器 DNS 別名的支援</span><span class="sxs-lookup"><span data-stu-id="7f689-722">Adding support for Server DNS Aliases</span></span>
        - <span data-ttu-id="7f689-723">新增 Get-AzureRmSqlServerDnsAlias Cmdlet，其可按照伺服器和別名名稱取得伺服器 dns 別名，或 Azure Sql Server 的伺服器 dns 別名清單。</span><span class="sxs-lookup"><span data-stu-id="7f689-723">Adding Get-AzureRmSqlServerDnsAlias cmdlet which gets server dns aliases by server and alias name or a list of server dns aliases for an azure Sql Server.</span></span>
        - <span data-ttu-id="7f689-724">新增 New-AzureRmSqlServerDnsAlias Cmdlet，其可建立指定的 Azure Sql 伺服器的新伺服器 dns 別名</span><span class="sxs-lookup"><span data-stu-id="7f689-724">Adding New-AzureRmSqlServerDnsAlias cmdlet which creates new server dns alias for a given Azure Sql server</span></span>
        - <span data-ttu-id="7f689-725">新增 Set-AzurermSqlServerDnsAlias Cmdlet，其可讓伺服器 dns 別名指向的 Azure Sql Server 進行更新</span><span class="sxs-lookup"><span data-stu-id="7f689-725">Adding Set-AzurermSqlServerDnsAlias cmlet which allows updating a Azure Sql Server to which server dns alias is pointing</span></span>
        - <span data-ttu-id="7f689-726">新增 Remove-AzureRmSqlServerDnsAlias Cmdlet，其可移除 Azure Sql 伺服器的伺服器 dns 別名</span><span class="sxs-lookup"><span data-stu-id="7f689-726">Adding Remove-AzureRmSqlServerDnsAlias cmdlet which removes a server dns alias for a Azure Sql Server</span></span>
* <span data-ttu-id="7f689-727">Azure.Storage</span><span class="sxs-lookup"><span data-stu-id="7f689-727">Azure.Storage</span></span>
    * <span data-ttu-id="7f689-728">升級至 Azure 儲存體用戶端程式庫 8.5.0 及 Azure 儲存體資料移動程式庫 0.6.3</span><span class="sxs-lookup"><span data-stu-id="7f689-728">Upgrade to Azure Storage Client Library 8.5.0 and Azure Storage DataMovement Library 0.6.3</span></span>
    * <span data-ttu-id="7f689-729">新增檔案共用快照集支援功能</span><span class="sxs-lookup"><span data-stu-id="7f689-729">Add File Share Snapshot Support Feature</span></span>
        - <span data-ttu-id="7f689-730">將 'SnapshotTime' 參數新增至 Get-AzureStorageShare</span><span class="sxs-lookup"><span data-stu-id="7f689-730">Add 'SnapshotTime' parameter to Get-AzureStorageShare</span></span>
        - <span data-ttu-id="7f689-731">將 'IncludeAllSnapshot' 參數新增至 Remove-AzureStorageShare</span><span class="sxs-lookup"><span data-stu-id="7f689-731">Add 'IncludeAllSnapshot' parameter to Remove-AzureStorageShare</span></span>
