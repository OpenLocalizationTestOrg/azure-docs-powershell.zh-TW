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
ms.date: 05/18/2017
ms.openlocfilehash: 97a23180a1fc65d96fdc9dbdffcbe3501a4c4c2a
ms.sourcegitcommit: 226527be7cb647acfe2ea9ab151185053ab3c6db
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 06/29/2017
---
# <span data-ttu-id="fa762-103">版本資訊</span><span class="sxs-lookup"><span data-stu-id="fa762-103">Release notes</span></span>
<a id="release-notes" class="xliff"></a>

<span data-ttu-id="fa762-104">這是此版本中對 Azure PowerShell 所做的變更清單。</span><span class="sxs-lookup"><span data-stu-id="fa762-104">This is a list of changes made to Azure PowerShell in this release.</span></span>

## <span data-ttu-id="fa762-105">4.0.0 版</span><span class="sxs-lookup"><span data-stu-id="fa762-105">Version 4.0.0</span></span>
<a id="version-400" class="xliff"></a>

* <span data-ttu-id="fa762-106">此版本包含重大變更。</span><span class="sxs-lookup"><span data-stu-id="fa762-106">This release contains breaking changes.</span></span> <span data-ttu-id="fa762-107">如需變更詳細資料和對現有指令碼的影響，請參閱[移轉指南 (英文)](https://aka.ms/azps-migration-guide)。</span><span class="sxs-lookup"><span data-stu-id="fa762-107">Please see [the migration guide](https://aka.ms/azps-migration-guide) for change details and the impact on existing scripts.</span></span>
* <span data-ttu-id="fa762-108">ApiManagement</span><span class="sxs-lookup"><span data-stu-id="fa762-108">ApiManagement</span></span>
  - <span data-ttu-id="fa762-109">新增在 New-AzureRmApiManagementGroup 中設定外部群組的支援。</span><span class="sxs-lookup"><span data-stu-id="fa762-109">Added support for configuring external groups in New-AzureRmApiManagementGroup.</span></span>
* <span data-ttu-id="fa762-110">計費</span><span class="sxs-lookup"><span data-stu-id="fa762-110">Billing</span></span>
  - <span data-ttu-id="fa762-111">新的 Get-AzureRmBillingPeriod Cmdlet</span><span class="sxs-lookup"><span data-stu-id="fa762-111">New Cmdlet Get-AzureRmBillingPeriod</span></span>
    + <span data-ttu-id="fa762-112">用來擷取 Azure 訂用帳戶計費週期的 Cmdlet。</span><span class="sxs-lookup"><span data-stu-id="fa762-112">cmdlet to retrieve azure billing periods of the subscription.</span></span>
  - <span data-ttu-id="fa762-113">更新 Get-AzureRmBillingInvoice Cmdlet</span><span class="sxs-lookup"><span data-stu-id="fa762-113">Update Cmdlet Get-AzureRmBillingInvoice</span></span>
  - <span data-ttu-id="fa762-114">新的 BillingPeriodNames 屬性</span><span class="sxs-lookup"><span data-stu-id="fa762-114">new property BillingPeriodNames</span></span>
  - <span data-ttu-id="fa762-115">在清單檢視中輸出</span><span class="sxs-lookup"><span data-stu-id="fa762-115">output in list view</span></span>
* <span data-ttu-id="fa762-116">計算</span><span class="sxs-lookup"><span data-stu-id="fa762-116">Compute</span></span>
  - <span data-ttu-id="fa762-117">已更新 Set-AzureRmVMAEMExtension 和 Test-AzureRmVMAEMExtension Cmdlet，以支援進階受控磁碟</span><span class="sxs-lookup"><span data-stu-id="fa762-117">Updated Set-AzureRmVMAEMExtension and Test-AzureRmVMAEMExtension cmdlets to support Premium managed disks</span></span>
  - <span data-ttu-id="fa762-118">適用於 IaaS VM 和失敗時還原的備份加密設定</span><span class="sxs-lookup"><span data-stu-id="fa762-118">Backup encryption settings for IaaS VMs and restore on failure</span></span>
  - <span data-ttu-id="fa762-119">ChefServiceInterval 選項現已重新命名為 ChefDaemonInterval。</span><span class="sxs-lookup"><span data-stu-id="fa762-119">ChefServiceInterval option is renamed to ChefDaemonInterval now.</span></span> <span data-ttu-id="fa762-120">但舊選項將繼續運作。</span><span class="sxs-lookup"><span data-stu-id="fa762-120">Old one will continue to work however.</span></span>
  - <span data-ttu-id="fa762-121">移除 PS VM 物件中重複的 DataDiskNames 和 NetworkInterfaceIDs 屬性。</span><span class="sxs-lookup"><span data-stu-id="fa762-121">Remove duplicated DataDiskNames and NetworkInterfaceIDs properties from PS VM object.</span></span>
  - <span data-ttu-id="fa762-122">使個別位於 Remove-AzureRmVMDataDisk 和 Remove-AzureRmVMNetworkInterface 中的 DataDiskNames 和 NetworkInterfaceIDs 參數成為選擇性。</span><span class="sxs-lookup"><span data-stu-id="fa762-122">Make DataDiskNames and NetworkInterfaceIDs parameters optional in Remove-AzureRmVMDataDisk and Remove-AzureRmVMNetworkInterface, respectively.</span></span>
  - <span data-ttu-id="fa762-123">修正 Get Cmdlet 傳回清單物件時的管線問題。</span><span class="sxs-lookup"><span data-stu-id="fa762-123">Fix the piping issue of Get cmdlets when the Get cmdlets return a list object.</span></span>
  - <span data-ttu-id="fa762-124">已重新命名和 RDFE Cmdlet 衝突的 Cmdlet。</span><span class="sxs-lookup"><span data-stu-id="fa762-124">Cmdlets that conflicted with RDFE cmdlets have been renamed.</span></span> <span data-ttu-id="fa762-125">如需詳細資料，請參閱此問題：https://github.com/Azure/azure-powershell/issues/2917</span><span class="sxs-lookup"><span data-stu-id="fa762-125">See issue https://github.com/Azure/azure-powershell/issues/2917 for more details</span></span>
    + <span data-ttu-id="fa762-126">`New-AzureVMSqlServerAutoBackupConfig` 已重新命名為 `New-AzureRmVMSqlServerAutoBackupConfig`</span><span class="sxs-lookup"><span data-stu-id="fa762-126">`New-AzureVMSqlServerAutoBackupConfig` has been renamed to `New-AzureRmVMSqlServerAutoBackupConfig`</span></span>
    + <span data-ttu-id="fa762-127">`New-AzureVMSqlServerAutoPatchingConfig` 已重新命名為 `New-AzureRmVMSqlServerAutoPatchingConfig`</span><span class="sxs-lookup"><span data-stu-id="fa762-127">`New-AzureVMSqlServerAutoPatchingConfig` has been renamed to `New-AzureRmVMSqlServerAutoPatchingConfig`</span></span>
    + <span data-ttu-id="fa762-128">`New-AzureVMSqlServerKeyVaultCredentialConfig` 已重新命名為 `New-AzureRmVMSqlServerKeyVaultCredentialConfig`</span><span class="sxs-lookup"><span data-stu-id="fa762-128">`New-AzureVMSqlServerKeyVaultCredentialConfig` has been renamed to `New-AzureRmVMSqlServerKeyVaultCredentialConfig`</span></span>
* <span data-ttu-id="fa762-129">耗用量</span><span class="sxs-lookup"><span data-stu-id="fa762-129">Consumption</span></span>
  - <span data-ttu-id="fa762-130">新的 Get-AzureRmConsumptionUsageDetail Cmdlet</span><span class="sxs-lookup"><span data-stu-id="fa762-130">New Cmdlet Get-AzureRmConsumptionUsageDetail</span></span>
    + <span data-ttu-id="fa762-131">用於擷取訂用帳戶使用量詳細資料的 Cmdlet。</span><span class="sxs-lookup"><span data-stu-id="fa762-131">cmdlet to retrieve usage details of the subscription.</span></span>
* <span data-ttu-id="fa762-132">ContainerRegistry</span><span class="sxs-lookup"><span data-stu-id="fa762-132">ContainerRegistry</span></span>
  - <span data-ttu-id="fa762-133">新增 Azure Container Registry 的 PowerShell Cmdlet</span><span class="sxs-lookup"><span data-stu-id="fa762-133">Add PowerShell cmdlets for Azure Container Registry</span></span>
    + <span data-ttu-id="fa762-134">New-AzureRmContainerRegistry</span><span class="sxs-lookup"><span data-stu-id="fa762-134">New-AzureRmContainerRegistry</span></span>
    + <span data-ttu-id="fa762-135">Get-AzureRmContainerRegistry</span><span class="sxs-lookup"><span data-stu-id="fa762-135">Get-AzureRmContainerRegistry</span></span>
    + <span data-ttu-id="fa762-136">Update-AzureRmContainerRegistry</span><span class="sxs-lookup"><span data-stu-id="fa762-136">Update-AzureRmContainerRegistry</span></span>
    + <span data-ttu-id="fa762-137">Remove-AzureRmContainerRegistry</span><span class="sxs-lookup"><span data-stu-id="fa762-137">Remove-AzureRmContainerRegistry</span></span>
    + <span data-ttu-id="fa762-138">Get-AzureRmContainerRegistryCredential</span><span class="sxs-lookup"><span data-stu-id="fa762-138">Get-AzureRmContainerRegistryCredential</span></span>
    + <span data-ttu-id="fa762-139">Update-AzureRmContainerRegistryCredential</span><span class="sxs-lookup"><span data-stu-id="fa762-139">Update-AzureRmContainerRegistryCredential</span></span>
    + <span data-ttu-id="fa762-140">Test-AzureRmContainerRegistryNameAvailability</span><span class="sxs-lookup"><span data-stu-id="fa762-140">Test-AzureRmContainerRegistryNameAvailability</span></span>
* <span data-ttu-id="fa762-141">DataLakeAnalytics</span><span class="sxs-lookup"><span data-stu-id="fa762-141">DataLakeAnalytics</span></span>
  - <span data-ttu-id="fa762-142">新增取得和列出目錄套件的支援</span><span class="sxs-lookup"><span data-stu-id="fa762-142">Add support for catalog package get and list</span></span>
  - <span data-ttu-id="fa762-143">新增從更深層的上階列出下列目錄項目的支援：</span><span class="sxs-lookup"><span data-stu-id="fa762-143">Add support for listing the following catalog items from deeper ancestors:</span></span>
    + <span data-ttu-id="fa762-144">資料表</span><span class="sxs-lookup"><span data-stu-id="fa762-144">Table</span></span>
    + <span data-ttu-id="fa762-145">TVF</span><span class="sxs-lookup"><span data-stu-id="fa762-145">TVF</span></span>
    + <span data-ttu-id="fa762-146">檢視</span><span class="sxs-lookup"><span data-stu-id="fa762-146">View</span></span>
    + <span data-ttu-id="fa762-147">統計資料</span><span class="sxs-lookup"><span data-stu-id="fa762-147">Statistics</span></span>
* <span data-ttu-id="fa762-148">DataLakeStore</span><span class="sxs-lookup"><span data-stu-id="fa762-148">DataLakeStore</span></span>
  - <span data-ttu-id="fa762-149">對於 `Import-AzureRMDataLakeStoreItem` 和 `Export-AzureRMDataLakeStoreItem`，預設已停用追蹤記錄以改善效能。</span><span class="sxs-lookup"><span data-stu-id="fa762-149">For `Import-AzureRMDataLakeStoreItem` and `Export-AzureRMDataLakeStoreItem` trace logging has been disabled by default to improve performance.</span></span> <span data-ttu-id="fa762-150">如果需要追蹤記錄，請使用 `-DiagnosticLogLevel` 和 `-DiagnosticLogPath` 參數</span><span class="sxs-lookup"><span data-stu-id="fa762-150">If trace logging is desired please use the `-DiagnosticLogLevel` and `-DiagnosticLogPath` parameters</span></span>
  - <span data-ttu-id="fa762-151">已修正將大量的小型檔案上傳到 ADLS 時偶爾會導致 PowerShell 當機的問題。</span><span class="sxs-lookup"><span data-stu-id="fa762-151">Fixed a bug that would sometimes cause PowerShell to crash when uploading lots of small file to ADLS.</span></span>
* <span data-ttu-id="fa762-152">EventHub</span><span class="sxs-lookup"><span data-stu-id="fa762-152">EventHub</span></span>
  - <span data-ttu-id="fa762-153">錯誤修正：</span><span class="sxs-lookup"><span data-stu-id="fa762-153">Bug fix :</span></span>
    + <span data-ttu-id="fa762-154">修正 Set-AzureRmEventHubNamespace Cmdlet 錯誤 - 'Tier' 不能為 Null，而必須是 'SkuName'</span><span class="sxs-lookup"><span data-stu-id="fa762-154">Fix for Set-AzureRmEventHubNamespace cmdlet error  - 'Tier' cannot be null, where it should be 'SkuName'</span></span>
    + <span data-ttu-id="fa762-155">Set-AzureRmEventHub - 修正更新 EventHub 時的「物件參考未設定成物件的執行個體」錯誤</span><span class="sxs-lookup"><span data-stu-id="fa762-155">Set-AzureRmEventHub - Fix 'Object reference not set to an instance of an object' error while updating EventHub</span></span>
* <span data-ttu-id="fa762-156">深入解析</span><span class="sxs-lookup"><span data-stu-id="fa762-156">Insights</span></span>
  - <span data-ttu-id="fa762-157">Add-AzureRm*AlertRule</span><span class="sxs-lookup"><span data-stu-id="fa762-157">Add-AzureRm*AlertRule</span></span>
    + <span data-ttu-id="fa762-158">傳回單一物件︰newResource、statusCode、requestId</span><span class="sxs-lookup"><span data-stu-id="fa762-158">Returns a single object: newResource, statusCode, requestId</span></span>
  - <span data-ttu-id="fa762-159">Get-AzureRmAlertRule</span><span class="sxs-lookup"><span data-stu-id="fa762-159">Get-AzureRmAlertRule</span></span>
    + <span data-ttu-id="fa762-160">現在會對輸出進行列舉，而不是將它視為單一物件。</span><span class="sxs-lookup"><span data-stu-id="fa762-160">The output is now enumerated instead of considered a single object.</span></span> <span data-ttu-id="fa762-161">它的類型並未變更，仍然是清單。</span><span class="sxs-lookup"><span data-stu-id="fa762-161">Its type did not change, it is still a list.</span></span>
  - <span data-ttu-id="fa762-162">Remove-AzureRmAlertRule</span><span class="sxs-lookup"><span data-stu-id="fa762-162">Remove-AzureRmAlertRule</span></span>
    + <span data-ttu-id="fa762-163">statusCode 會遵循要求所傳回的狀態碼，先前一律是「良好」。</span><span class="sxs-lookup"><span data-stu-id="fa762-163">The statusCode follows the status code returned by the request, before it was Ok always.</span></span>
  - <span data-ttu-id="fa762-164">Add-AzureRmAutoscaleSetting</span><span class="sxs-lookup"><span data-stu-id="fa762-164">Add-AzureRmAutoscaleSetting</span></span>
    + <span data-ttu-id="fa762-165">現在會傳回包含 statusCode、requestId，以及最近所建立/更新資源的單一物件 (而非先前的清單)。</span><span class="sxs-lookup"><span data-stu-id="fa762-165">Returns now a single object (not a list as before) containing statusCode, requestId, and the newly created/updated resource.</span></span>
    + <span data-ttu-id="fa762-166">狀態碼會遵循要求所傳回的狀態，先前一律是「良好」。</span><span class="sxs-lookup"><span data-stu-id="fa762-166">The status code follows the status returned by the request, before it was always Ok.</span></span>
  - <span data-ttu-id="fa762-167">New-AzureRmAutoscaleRule</span><span class="sxs-lookup"><span data-stu-id="fa762-167">New-AzureRmAutoscaleRule</span></span>
    + <span data-ttu-id="fa762-168">已擴充 ScaleActionType 參數，現在它會接收下列值：ChangeCount、PercentChangeCount、ExactCount。</span><span class="sxs-lookup"><span data-stu-id="fa762-168">The parameter ScaleActionType has been extended, it receives the following values now: ChangeCount, PercentChangeCount, ExactCount.</span></span>
  - <span data-ttu-id="fa762-169">Remove-AzureRmAutoscaleSetting</span><span class="sxs-lookup"><span data-stu-id="fa762-169">Remove-AzureRmAutoscaleSetting</span></span>
    + <span data-ttu-id="fa762-170">輸出中的 statusCode 會遵循要求所傳回的 statusCode。</span><span class="sxs-lookup"><span data-stu-id="fa762-170">The statusCode in the output follows the statusCode returned by the request.</span></span> <span data-ttu-id="fa762-171">先前一律是「良好」。</span><span class="sxs-lookup"><span data-stu-id="fa762-171">Before it was always Ok.</span></span>
  - <span data-ttu-id="fa762-172">Get-AzureRMLogProfile</span><span class="sxs-lookup"><span data-stu-id="fa762-172">Get-AzureRMLogProfile</span></span>
    + <span data-ttu-id="fa762-173">現在會對輸出進行列舉。</span><span class="sxs-lookup"><span data-stu-id="fa762-173">The output is now enumerated.</span></span> <span data-ttu-id="fa762-174">先前是將它視為單一物件。</span><span class="sxs-lookup"><span data-stu-id="fa762-174">Before it was considered a single object.</span></span> <span data-ttu-id="fa762-175">輸出的類型仍為先前的清單。</span><span class="sxs-lookup"><span data-stu-id="fa762-175">The type of the output remains a list as before.</span></span>
  - <span data-ttu-id="fa762-176">Remove-AzureRmLogProfile</span><span class="sxs-lookup"><span data-stu-id="fa762-176">Remove-AzureRmLogProfile</span></span>
    + <span data-ttu-id="fa762-177">已實作 PassThru 參數。</span><span class="sxs-lookup"><span data-stu-id="fa762-177">The PassThru parameter has been implemented.</span></span>
  - <span data-ttu-id="fa762-178">計量 API</span><span class="sxs-lookup"><span data-stu-id="fa762-178">Metrics API</span></span>
    + <span data-ttu-id="fa762-179">SDK 現在會從 MDM 擷取計量。</span><span class="sxs-lookup"><span data-stu-id="fa762-179">The SDK now retrieves metrics from MDM.</span></span>
  - <span data-ttu-id="fa762-180">Get-AzureRmMetricDefinition</span><span class="sxs-lookup"><span data-stu-id="fa762-180">Get-AzureRmMetricDefinition</span></span>
    + <span data-ttu-id="fa762-181">輸出仍是清單，但清單的結構已變更。</span><span class="sxs-lookup"><span data-stu-id="fa762-181">The output is still a list, but the structure of the list changed.</span></span>
  - <span data-ttu-id="fa762-182">Get-AzureRmMetric</span><span class="sxs-lookup"><span data-stu-id="fa762-182">Get-AzureRmMetric</span></span>
    + <span data-ttu-id="fa762-183">呼叫已變更。</span><span class="sxs-lookup"><span data-stu-id="fa762-183">The call has changed.</span></span> <span data-ttu-id="fa762-184">新的語法如下：Get-AzureRmMetric ResourceId [MetricNames [TimeGrain] [AggregationType] [StartTime] [EndTime]] [DetailedOutput]</span><span class="sxs-lookup"><span data-stu-id="fa762-184">This is the new syntax: Get-AzureRmMetric ResourceId [MetricNames [TimeGrain] [AggregationType] [StartTime] [EndTime]] [DetailedOutput]</span></span>
    + <span data-ttu-id="fa762-185">輸出是清單，但其元素的結構已變更。</span><span class="sxs-lookup"><span data-stu-id="fa762-185">The output is a list, and the structure of its elements has changed.</span></span>
* <span data-ttu-id="fa762-186">KeyVault</span><span class="sxs-lookup"><span data-stu-id="fa762-186">KeyVault</span></span>
  - <span data-ttu-id="fa762-187">新增備份/還原 KeyVault 密碼的支援</span><span class="sxs-lookup"><span data-stu-id="fa762-187">Adding backup/restore support for KeyVault secrets</span></span>
    + <span data-ttu-id="fa762-188">可以對密碼進行備份和還原，以符合目前對於金鑰所支援的功能</span><span class="sxs-lookup"><span data-stu-id="fa762-188">Secrets can be backed up and restored, matching the functionality currently supported for Keys</span></span>

  - <span data-ttu-id="fa762-189">金鑰和密碼的備份 Cmdlet 現在接受以對應的物件做為輸入參數</span><span class="sxs-lookup"><span data-stu-id="fa762-189">Backup cmdlets for Keys and Secrets now accept a corresponding object as an input parameter</span></span>
    + <span data-ttu-id="fa762-190">呼叫端可鏈結擷取和備份作業︰Get-AzureKeyVaultKey -VaultName myVault -Name myKey | Backup-AzureKeyVaultKey</span><span class="sxs-lookup"><span data-stu-id="fa762-190">The caller may chain retrieval and backup operations: Get-AzureKeyVaultKey -VaultName myVault -Name myKey | Backup-AzureKeyVaultKey</span></span>

  - <span data-ttu-id="fa762-191">備份 Cmdlet 現在支援用於覆寫現有檔案的 -Force 參數</span><span class="sxs-lookup"><span data-stu-id="fa762-191">Backup cmdlets now support a -Force switch to overwrite an existing file</span></span>
    + <span data-ttu-id="fa762-192">請注意，嘗試覆寫現有檔案將不再會擲回，而是改為提示使用者選擇繼續的方式。</span><span class="sxs-lookup"><span data-stu-id="fa762-192">Note that attempting to overwrite an existing file will no longer throw, and will instead prompt the user for a choice on how to proceed.</span></span>
* <span data-ttu-id="fa762-193">LogicApp</span><span class="sxs-lookup"><span data-stu-id="fa762-193">LogicApp</span></span>
  - <span data-ttu-id="fa762-194">交換控制編號災害復原 Cmdlet 的新參數︰</span><span class="sxs-lookup"><span data-stu-id="fa762-194">New parameters for Interchange Control Number disaster recovery cmdlets:</span></span>
    + <span data-ttu-id="fa762-195">用於指定相關控制編號的選擇性 -AgreementType 參數 ("X12" 或 "Edifact")</span><span class="sxs-lookup"><span data-stu-id="fa762-195">Optional -AgreementType parameter ("X12", or "Edifact") to specify the relevant control numbers</span></span>
* <span data-ttu-id="fa762-196">MachineLearning</span><span class="sxs-lookup"><span data-stu-id="fa762-196">MachineLearning</span></span>
  - <span data-ttu-id="fa762-197">使用新版的 Azure Machine Learning .Net SDK，並新增 Cmdlet</span><span class="sxs-lookup"><span data-stu-id="fa762-197">Consume new version of Azure Machine Learning .Net SDK and add a new cmdlet</span></span>
    + <span data-ttu-id="fa762-198">Add-AzureRmMlWebServiceRegionalProperty</span><span class="sxs-lookup"><span data-stu-id="fa762-198">Add-AzureRmMlWebServiceRegionalProperty</span></span>
  - <span data-ttu-id="fa762-199">說明文字中的次要措辭修正。</span><span class="sxs-lookup"><span data-stu-id="fa762-199">Minor wording fixes in help text.</span></span>
* <span data-ttu-id="fa762-200">網路</span><span class="sxs-lookup"><span data-stu-id="fa762-200">Network</span></span>
  - <span data-ttu-id="fa762-201">已新增 Test-AzureRmNetworkWatcherConnectivity Cmdlet</span><span class="sxs-lookup"><span data-stu-id="fa762-201">Added Test-AzureRmNetworkWatcherConnectivity cmdlet</span></span>
    + <span data-ttu-id="fa762-202">傳回指定來源 VM 和目的地的連線資訊</span><span class="sxs-lookup"><span data-stu-id="fa762-202">Returns connectivity information for a specified source VM and a destination</span></span>
    + <span data-ttu-id="fa762-203">如果無法建立來源與目的地之間的連線，此 Cmdlet 會傳回問題的詳細資料</span><span class="sxs-lookup"><span data-stu-id="fa762-203">If connectivity between the source and destination cannot be established, the cmdlet returns details about the issue</span></span>
* <span data-ttu-id="fa762-204">設定檔</span><span class="sxs-lookup"><span data-stu-id="fa762-204">Profile</span></span>
  - <span data-ttu-id="fa762-205">已新增 'Send-Feedback' Cmdlet︰可讓使用者起始一組提示，以傳送意見反應給 Azure PowerShell 小組。</span><span class="sxs-lookup"><span data-stu-id="fa762-205">Added \`Send-Feedback' cmdlet: allows a user to initiate a set of prompts which sends feedback to the Azure PowerShell team.</span></span>
  - <span data-ttu-id="fa762-206">已移除下列別名，因為它們與 Azure 模組中現有的 Cmdlet 名稱衝突︰</span><span class="sxs-lookup"><span data-stu-id="fa762-206">The following aliases have been removed as they conflicted with existing cmdlet names in the Azure module:</span></span>
    + <span data-ttu-id="fa762-207">`Enable-AzureDataCollection` (受 `Enable-AzureRmDataCollection` 支援)</span><span class="sxs-lookup"><span data-stu-id="fa762-207">`Enable-AzureDataCollection` (supported by `Enable-AzureRmDataCollection`)</span></span>
    + <span data-ttu-id="fa762-208">`Disable-AzureDataCollection` (受 `Disable-AzureRmDataCollection` 支援)</span><span class="sxs-lookup"><span data-stu-id="fa762-208">`Disable-AzureDataCollection` (supported by `Disable-AzureRmDataCollection`)</span></span>
* <span data-ttu-id="fa762-209">轉送</span><span class="sxs-lookup"><span data-stu-id="fa762-209">Relay</span></span>
  - <span data-ttu-id="fa762-210">新增 Azure 轉送適用的 Cmdlet，方便使用者建立和管理所有 Azure 轉送資源。</span><span class="sxs-lookup"><span data-stu-id="fa762-210">Adds cmdlets for the Azure Relay which allows users to create and manage all Azure Relay resources.</span></span>
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
* <span data-ttu-id="fa762-211">資源</span><span class="sxs-lookup"><span data-stu-id="fa762-211">Resources</span></span>
  - <span data-ttu-id="fa762-212">支援適用於 AzureRmResourceGroupDeployment 的跨資源群組部署</span><span class="sxs-lookup"><span data-stu-id="fa762-212">Support cross-resource-group deployments for New-AzureRmResourceGroupDeployment</span></span>
    + <span data-ttu-id="fa762-213">使用者現在可以使用巢狀部署以部署至不同的資源群組。</span><span class="sxs-lookup"><span data-stu-id="fa762-213">Users can now use nested deployments to deploy to different resource groups.</span></span>
* <span data-ttu-id="fa762-214">ServiceBus</span><span class="sxs-lookup"><span data-stu-id="fa762-214">ServiceBus</span></span>

  - <span data-ttu-id="fa762-215">錯誤修正：ServiceBus 佇列物件屬性值已設為 Null，該物件是做為 Set-AzureRmServiceBusQueue Cmdlet 中的輸入參數使用以更新佇列。</span><span class="sxs-lookup"><span data-stu-id="fa762-215">Bug Fix: ServiceBus Queue object property values were set to null, the object is used as input parameter in Set-AzureRmServiceBusQueue cmdlet to update Queue.</span></span>
   - <span data-ttu-id="fa762-216">受影響的屬性包括 LockDuration、EntityAvailabilityStatus、DuplicateDetectionHistoryTimeWindow、MaxDeliveryCount 和 MessageCount</span><span class="sxs-lookup"><span data-stu-id="fa762-216">Properties affected are LockDuration, EntityAvailabilityStatus, DuplicateDetectionHistoryTimeWindow, MaxDeliveryCount and MessageCount</span></span>
* <span data-ttu-id="fa762-217">ServiceFabric</span><span class="sxs-lookup"><span data-stu-id="fa762-217">ServiceFabric</span></span>

  - <span data-ttu-id="fa762-218">已新增適用於 Service Fabric 的 Cmdlet</span><span class="sxs-lookup"><span data-stu-id="fa762-218">Added cmdlets for service fabric</span></span>
    + <span data-ttu-id="fa762-219">Add-AzureRmServiceFabricApplicationCertificate       新增將做為應用程式憑證使用的憑證</span><span class="sxs-lookup"><span data-stu-id="fa762-219">Add-AzureRmServiceFabricApplicationCertificate       Add a certificate which will be used as application certificate</span></span>
    + <span data-ttu-id="fa762-220">Add-AzureRmServiceFabricClientCertificate       在叢集設定新增用於用戶端驗證的一般名稱或指紋</span><span class="sxs-lookup"><span data-stu-id="fa762-220">Add-AzureRmServiceFabricClientCertificate       Add a common name or thumbprint to the cluster settings for client authentication</span></span>
    + <span data-ttu-id="fa762-221">Add-AzureRmServiceFabricClusterCertificate       在叢集新增次要叢集憑證以更換現有的憑證</span><span class="sxs-lookup"><span data-stu-id="fa762-221">Add-AzureRmServiceFabricClusterCertificate       Add a secondary cluster certificate to the cluster for rolling over the existing certificate</span></span>
    + <span data-ttu-id="fa762-222">Add-AzureRmServiceFabricNodes       在叢集新增特定節點類型的節點/VM</span><span class="sxs-lookup"><span data-stu-id="fa762-222">Add-AzureRmServiceFabricNodes       Add nodes/VMs of a specific node type to a cluster</span></span>
    + <span data-ttu-id="fa762-223">Add-AzureRmServiceFabricNodeType       在現有叢集新增節點類型/VM</span><span class="sxs-lookup"><span data-stu-id="fa762-223">Add-AzureRmServiceFabricNodeType       Add a node type/VMs to an existing cluster</span></span>
    + <span data-ttu-id="fa762-224">Get-AzureRmServiceFabricCluster       取得叢集資源的詳細資料</span><span class="sxs-lookup"><span data-stu-id="fa762-224">Get-AzureRmServiceFabricCluster       Get the details of the cluster resource</span></span>
    + <span data-ttu-id="fa762-225">New-AzureRmServiceFabricCluster 建立新的 ServiceFabric 叢集。</span><span class="sxs-lookup"><span data-stu-id="fa762-225">New-AzureRmServiceFabricCluster Create a new ServiceFabric cluster.</span></span> <span data-ttu-id="fa762-226">此命令有許多的多載，可涵蓋各種案例</span><span class="sxs-lookup"><span data-stu-id="fa762-226">This command has many overloads to cover various scenarios</span></span>
    + <span data-ttu-id="fa762-227">Remove-AzureRmServiceFabricClientCertificate       移除某個用戶端憑證以防止將它用於存取叢集</span><span class="sxs-lookup"><span data-stu-id="fa762-227">Remove-AzureRmServiceFabricClientCertificate       Remove a client certificate from being used to access a cluster</span></span>
    + <span data-ttu-id="fa762-228">Remove-AzureRmServiceFabricClusterCertificate       移除某個用戶端憑證以防止將它用於叢集安全性</span><span class="sxs-lookup"><span data-stu-id="fa762-228">Remove-AzureRmServiceFabricClusterCertificate       Remove a cluster certificate from being used for cluster security</span></span>
    + <span data-ttu-id="fa762-229">Remove-AzureRmServiceFabricNodes       自叢集中移除特定節點類型的節點</span><span class="sxs-lookup"><span data-stu-id="fa762-229">Remove-AzureRmServiceFabricNodes       Remove nodes from a specific node type from a cluster</span></span>
    + <span data-ttu-id="fa762-230">Remove-AzureRmServiceFabricNodeType       自叢集中移除某個節點類型</span><span class="sxs-lookup"><span data-stu-id="fa762-230">Remove-AzureRmServiceFabricNodeType       Remove a node type from a cluster</span></span>
    + <span data-ttu-id="fa762-231">Remove-AzureRmServiceFabricSettings       自叢集中移除一或多個 ServiceFabric 設定</span><span class="sxs-lookup"><span data-stu-id="fa762-231">Remove-AzureRmServiceFabricSettings       Remove one or more ServiceFabric settings from a cluster</span></span>
    + <span data-ttu-id="fa762-232">Set-AzureRmServiceFabricSettings       新增或更新叢集的一或多個 ServiceFabric 設定</span><span class="sxs-lookup"><span data-stu-id="fa762-232">Set-AzureRmServiceFabricSettings       Add or update one or more ServiceFabric settings of a cluster</span></span>
    + <span data-ttu-id="fa762-233">Set-AzureRmServiceFabricUpgradeType       變更叢集的 ServiceFabric 升級類型</span><span class="sxs-lookup"><span data-stu-id="fa762-233">Set-AzureRmServiceFabricUpgradeType       Change the ServiceFabric upgrade type of a cluster</span></span>
    + <span data-ttu-id="fa762-234">Update-AzureRmServiceFabricDurability       變更叢集的持久性層</span><span class="sxs-lookup"><span data-stu-id="fa762-234">Update-AzureRmServiceFabricDurability       Change the durability tier of a cluster</span></span>
    + <span data-ttu-id="fa762-235">Update-AzureRmServiceFabricReliability       變更叢集的可靠性層</span><span class="sxs-lookup"><span data-stu-id="fa762-235">Update-AzureRmServiceFabricReliability       Change the reliability tier of a cluster</span></span>
* <span data-ttu-id="fa762-236">Sql</span><span class="sxs-lookup"><span data-stu-id="fa762-236">Sql</span></span>
  - <span data-ttu-id="fa762-237">已將 -SampleName 參數新增至 New-AzureRmSqlDatabase</span><span class="sxs-lookup"><span data-stu-id="fa762-237">Added -SampleName parameter to New-AzureRmSqlDatabase</span></span>
  - <span data-ttu-id="fa762-238">更新容錯移轉群組 Cmdlet</span><span class="sxs-lookup"><span data-stu-id="fa762-238">Updates to Failover Group cmdlets</span></span>
  - <span data-ttu-id="fa762-239">移除 'Tag' 參數</span><span class="sxs-lookup"><span data-stu-id="fa762-239">Remove 'Tag' parameters</span></span>
  - <span data-ttu-id="fa762-240">從 Remove-AzureRmSqlDatabaseFailoverGroup Cmdlet 中移除 'PartnerResourceGroupName' 和 'PartnerServerName' 參數</span><span class="sxs-lookup"><span data-stu-id="fa762-240">Remove 'PartnerResourceGroupName' and 'PartnerServerName' parameters from Remove-AzureRmSqlDatabaseFailoverGroup cmdlet</span></span>
  - <span data-ttu-id="fa762-241">將 'GracePeriodWithDataLossHours' 參數新增至 New- 和 Set- Cmdlet，此參數最終會取代 'GracePeriodWithDataLossHour'</span><span class="sxs-lookup"><span data-stu-id="fa762-241">Add 'GracePeriodWithDataLossHours' parameter to New- and Set- cmdlets, which shall eventually replace 'GracePeriodWithDataLossHour'</span></span>
  - <span data-ttu-id="fa762-242">文件已增補並更新</span><span class="sxs-lookup"><span data-stu-id="fa762-242">Documentation has been fleshed out and updated</span></span>
  - <span data-ttu-id="fa762-243">變更傳回物件的格式，並修正欄位有時不會填入的錯誤</span><span class="sxs-lookup"><span data-stu-id="fa762-243">Change formatting of returned objects and fix some bugs where fields were not always populated</span></span>
  - <span data-ttu-id="fa762-244">將 'DatabaseNames' 和 'PartnerLocation' 屬性新增至容錯移轉群組物件</span><span class="sxs-lookup"><span data-stu-id="fa762-244">Add 'DatabaseNames' and 'PartnerLocation' properties to Failover Group object</span></span>
  - <span data-ttu-id="fa762-245">修正造成 Switch- Cmdlet 立即傳回 (而非等待作業完成後再傳回) 的錯誤</span><span class="sxs-lookup"><span data-stu-id="fa762-245">Fix bug causing Switch- cmdlet to return immediately rather than waiting for operation to complete</span></span>
  - <span data-ttu-id="fa762-246">修正使用高寬限期值時的整數溢位錯誤</span><span class="sxs-lookup"><span data-stu-id="fa762-246">Fix integer overflow bug when high grace period values are used</span></span>
  - <span data-ttu-id="fa762-247">在提供的值比 1 小時的下限還要低的情況下，將寬限期調整為 1 小時</span><span class="sxs-lookup"><span data-stu-id="fa762-247">Adjust grace period to a minimum of 1 hour if a lower one is provided</span></span>
  - <span data-ttu-id="fa762-248">從 Set-AzureRmSqlDatabaseThreatDetectionPolicy Cmdlet 和 Set-AzureRmSqlServerThreatDetectionPolicy Cmdlet 之 "ExcludedDetectionType" 參數的可接受值中移除 "Usage_Anomaly"。</span><span class="sxs-lookup"><span data-stu-id="fa762-248">Remove "Usage_Anomaly" from the accepted values for "ExcludedDetectionType" parameter of Set-AzureRmSqlDatabaseThreatDetectionPolicy cmdlet and Set-AzureRmSqlServerThreatDetectionPolicy cmdlet.</span></span>
* <span data-ttu-id="fa762-249">儲存體</span><span class="sxs-lookup"><span data-stu-id="fa762-249">Storage</span></span>
  - <span data-ttu-id="fa762-250">將 SRP SDK 升級至 6.3.0</span><span class="sxs-lookup"><span data-stu-id="fa762-250">Upgrade SRP SDK to 6.3.0</span></span>
  - <span data-ttu-id="fa762-251">New/Set-AzureRmStorageAccount：新增參數以支援 EnableHttpsTrafficOnly</span><span class="sxs-lookup"><span data-stu-id="fa762-251">New/Set-AzureRmStorageAccount:Add a new parameter to support EnableHttpsTrafficOnly</span></span>
  - <span data-ttu-id="fa762-252">New/Set/Get-AzureRmStorageAccount：傳回的儲存體帳戶包含新的 EnableHttpsTrafficOnly 屬性</span><span class="sxs-lookup"><span data-stu-id="fa762-252">New/Set/Get-AzureRmStorageAccount: Returned Storage Account contains a new attribute EnableHttpsTrafficOnly</span></span>
* <span data-ttu-id="fa762-253">Azure.Storage</span><span class="sxs-lookup"><span data-stu-id="fa762-253">Azure.Storage</span></span>
  - <span data-ttu-id="fa762-254">升級至 Azure 儲存體用戶端程式庫 8.1.1 及 Azure 儲存體資料移動程式庫 0.5.1</span><span class="sxs-lookup"><span data-stu-id="fa762-254">Upgrade to Azure Storage Client Library 8.1.1 and Azure Storage DataMovement Library 0.5.1</span></span>
  - <span data-ttu-id="fa762-255">新增 Cmdlet 以支援 Blob 增量複製功能</span><span class="sxs-lookup"><span data-stu-id="fa762-255">Add a new cmdlet to support blob Incremental Copy feature</span></span>
