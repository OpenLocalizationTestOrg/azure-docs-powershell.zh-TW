---
title: Azure PowerShell 變更記錄 | Microsoft Docs
description: 這是在最新版中對 Azure powershell 所做的變更歷程記錄。
services: azure
author: sdwheeler
ms.author: sewhee
manager: carmonm
ms.service: azure-powershell
ms.product: azure
ms.devlang: powershell
ms.topic: conceptual
ms.workload: ''
ms.date: 2/20/2018
ms.openlocfilehash: 985e0fbaa2da73b398d4c574515bcbab5b1a16e0
ms.sourcegitcommit: 15bf69bf95eceb936b3a429e741add95c308826a
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 03/28/2018
---
# <a name="release-notes"></a><span data-ttu-id="bc0e4-103">版本資訊</span><span class="sxs-lookup"><span data-stu-id="bc0e4-103">Release notes</span></span>

<span data-ttu-id="bc0e4-104">這是此版本中對 Azure PowerShell 所做的變更清單。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-104">This is a list of changes made to Azure PowerShell in this release.</span></span>

---

## <a name="560---march-2018"></a><span data-ttu-id="bc0e4-105">5.6.0 - 2018 年 3 月</span><span class="sxs-lookup"><span data-stu-id="bc0e4-105">5.6.0 - March 2018</span></span>

#### <a name="general"></a><span data-ttu-id="bc0e4-106">一般</span><span class="sxs-lookup"><span data-stu-id="bc0e4-106">General</span></span>
* <span data-ttu-id="bc0e4-107">修正 CloudShell 中的預設資源群組問題</span><span class="sxs-lookup"><span data-stu-id="bc0e4-107">Fix issue with Default Resource Group in CloudShell</span></span>
* <span data-ttu-id="bc0e4-108">修正在模組匯入期間執行不正確啟動指令碼的問題</span><span class="sxs-lookup"><span data-stu-id="bc0e4-108">Fix issue where incorrect startup scripts were being executed during module import</span></span>

#### <a name="azurermprofile"></a><span data-ttu-id="bc0e4-109">AzureRM.Profile</span><span class="sxs-lookup"><span data-stu-id="bc0e4-109">AzureRM.Profile</span></span>
* <span data-ttu-id="bc0e4-110">在不支援的案例中啟用 MSI 驗證</span><span class="sxs-lookup"><span data-stu-id="bc0e4-110">Enable MSI authentication in unsupported scenarios</span></span>
* <span data-ttu-id="bc0e4-111">新增使用者定義的受控服務識別支援</span><span class="sxs-lookup"><span data-stu-id="bc0e4-111">Add support for user-defined Managed Service Identity</span></span>

#### <a name="azurermanalysisservices"></a><span data-ttu-id="bc0e4-112">AzureRM.AnalysisServices</span><span class="sxs-lookup"><span data-stu-id="bc0e4-112">AzureRM.AnalysisServices</span></span>
* <span data-ttu-id="bc0e4-113">修正在組建中清理指令碼的問題</span><span class="sxs-lookup"><span data-stu-id="bc0e4-113">Fixed issue with cleaning up scripts in build</span></span>

#### <a name="azurermcdn"></a><span data-ttu-id="bc0e4-114">AzureRM.Cdn</span><span class="sxs-lookup"><span data-stu-id="bc0e4-114">AzureRM.Cdn</span></span>
* <span data-ttu-id="bc0e4-115">修正在組建中清理指令碼的問題</span><span class="sxs-lookup"><span data-stu-id="bc0e4-115">Fixed issue with cleaning up scripts in build</span></span>

#### <a name="azurermcompute"></a><span data-ttu-id="bc0e4-116">AzureRM.Compute</span><span class="sxs-lookup"><span data-stu-id="bc0e4-116">AzureRM.Compute</span></span>
* <span data-ttu-id="bc0e4-117">'New-AzureRmVM' 和 'New-AzureRmVMSS' 支援資料磁碟機。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-117">'New-AzureRmVM' and 'New-AzureRmVMSS' support data disks.</span></span>
* <span data-ttu-id="bc0e4-118">'New-AzureRmVM' 和 'New-AzureRmVMSS' 支援依名稱或識別碼的自訂映像。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-118">'New-AzureRmVM' and 'New-AzureRmVMSS' support custom image by name or by id.</span></span>
* <span data-ttu-id="bc0e4-119">記錄分析功能</span><span class="sxs-lookup"><span data-stu-id="bc0e4-119">Log analytic feature</span></span>
    - <span data-ttu-id="bc0e4-120">已新增 'Export-AzureRmLogAnalyticRequestRateByInterval' Cmdlet</span><span class="sxs-lookup"><span data-stu-id="bc0e4-120">Added 'Export-AzureRmLogAnalyticRequestRateByInterval' cmdlet</span></span>
    - <span data-ttu-id="bc0e4-121">已新增 'Export-AzureRmLogAnalyticThrottledRequests' Cmdlet</span><span class="sxs-lookup"><span data-stu-id="bc0e4-121">Added 'Export-AzureRmLogAnalyticThrottledRequests' cmdlet</span></span>

#### <a name="azurermcontainerinstance"></a><span data-ttu-id="bc0e4-122">AzureRM.ContainerInstance</span><span class="sxs-lookup"><span data-stu-id="bc0e4-122">AzureRM.ContainerInstance</span></span>
* <span data-ttu-id="bc0e4-123">修正登錄容器和 Azure 檔案磁碟區裝載的參數集問題</span><span class="sxs-lookup"><span data-stu-id="bc0e4-123">Fix parameter sets issue for container registry and azure file volume mount</span></span>

#### <a name="azurermdatafactoryv2"></a><span data-ttu-id="bc0e4-124">AzureRM.DataFactoryV2</span><span class="sxs-lookup"><span data-stu-id="bc0e4-124">AzureRM.DataFactoryV2</span></span>
* <span data-ttu-id="bc0e4-125">已將 ADF .Net SDK 更新為版本 0.6.0-preview，包含以下變更：</span><span class="sxs-lookup"><span data-stu-id="bc0e4-125">Updated the ADF .Net SDK to version 0.6.0-preview containing the following changes:</span></span>
    - <span data-ttu-id="bc0e4-126">已新增新的 AzureDatabricks LinkedService 和 DatabricksNotebook 活動</span><span class="sxs-lookup"><span data-stu-id="bc0e4-126">Added new AzureDatabricks LinkedService and DatabricksNotebook Activity</span></span>
    - <span data-ttu-id="bc0e4-127">已在 HDInsightOnDemand LinkedService 中新增 headNodeSize 和 dataNodeSize 屬性</span><span class="sxs-lookup"><span data-stu-id="bc0e4-127">Added headNodeSize and dataNodeSize properties in HDInsightOnDemand LinkedService</span></span>
    - <span data-ttu-id="bc0e4-128">已為 SalesforceMarketingCloud 新增 LinkedService、Dataset、CopySource</span><span class="sxs-lookup"><span data-stu-id="bc0e4-128">Added LinkedService, Dataset, CopySource for SalesforceMarketingCloud</span></span>
    - <span data-ttu-id="bc0e4-129">已在所有活動上新增對 SecureOutput 的支援</span><span class="sxs-lookup"><span data-stu-id="bc0e4-129">Added support for SecureOutput on all activities</span></span>
    - <span data-ttu-id="bc0e4-130">已在 ForEach 新增新的 BatchCount 屬性，可控制要執行的並行活動數量</span><span class="sxs-lookup"><span data-stu-id="bc0e4-130">Added new BatchCount property on ForEach activity which control how many concurrent activities to run</span></span>
    - <span data-ttu-id="bc0e4-131">已新增新的篩選條件活動</span><span class="sxs-lookup"><span data-stu-id="bc0e4-131">Added new Filter Activity</span></span>
    - <span data-ttu-id="bc0e4-132">已新增連結服務參數的支援</span><span class="sxs-lookup"><span data-stu-id="bc0e4-132">Added Linked Service Parameters support</span></span>

#### <a name="azurermdns"></a><span data-ttu-id="bc0e4-133">AzureRM.Dns</span><span class="sxs-lookup"><span data-stu-id="bc0e4-133">AzureRM.Dns</span></span>
* <span data-ttu-id="bc0e4-134">支援私人 DNS 區域 (公開預覽)</span><span class="sxs-lookup"><span data-stu-id="bc0e4-134">Support for Private DNS Zones (Public Preview)</span></span>
    - <span data-ttu-id="bc0e4-135">新增建立只有相關的虛擬網路才能看見的 DNS 區域之功能</span><span class="sxs-lookup"><span data-stu-id="bc0e4-135">Adds ability to create DNS zones that are visible only to the associated virtual networks</span></span>

#### <a name="azurermnetwork"></a><span data-ttu-id="bc0e4-136">AzureRM.Network</span><span class="sxs-lookup"><span data-stu-id="bc0e4-136">AzureRM.Network</span></span>
* <span data-ttu-id="bc0e4-137">更新模型類型以與 DNS Cmdlet 相容。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-137">Updating model types for compatibility with DNS cmdlets.</span></span>

#### <a name="azurermrecoveryservicessiterecovery"></a><span data-ttu-id="bc0e4-138">AzureRM.RecoveryServices.SiteRecovery</span><span class="sxs-lookup"><span data-stu-id="bc0e4-138">AzureRM.RecoveryServices.SiteRecovery</span></span>
* <span data-ttu-id="bc0e4-139">ASR Azure 到 Azure Site Recovery 的變更 (Cmdlet 目前支援企業到企業、企業到 Azure、HyperV 到 Azure 以及 VMware 到 Azure 的作業)</span><span class="sxs-lookup"><span data-stu-id="bc0e4-139">Changes for ASR Azure to Azure Site Recovery (cmdlets are currently supporting operations for Enterprise to Enterprise, Enterprise to Azure, HyperV to Azure,VMware to Azure)</span></span>
    - <span data-ttu-id="bc0e4-140">New-AzureRmRecoveryServicesAsrProtectionContainer</span><span class="sxs-lookup"><span data-stu-id="bc0e4-140">New-AzureRmRecoveryServicesAsrProtectionContainer</span></span>
    - <span data-ttu-id="bc0e4-141">New-AzureRmRecoveryServicesAsrAzureToAzureDiskReplicationConfig</span><span class="sxs-lookup"><span data-stu-id="bc0e4-141">New-AzureRmRecoveryServicesAsrAzureToAzureDiskReplicationConfig</span></span>
    - <span data-ttu-id="bc0e4-142">Remove-AzureRmRecoveryServicesAsrProtectionContainer</span><span class="sxs-lookup"><span data-stu-id="bc0e4-142">Remove-AzureRmRecoveryServicesAsrProtectionContainer</span></span>
    - <span data-ttu-id="bc0e4-143">Update-AzureRmRecoveryServicesAsrProtectionDirection</span><span class="sxs-lookup"><span data-stu-id="bc0e4-143">Update-AzureRmRecoveryServicesAsrProtectionDirection</span></span>

#### <a name="azurermstorage"></a><span data-ttu-id="bc0e4-144">AzureRM.Storage</span><span class="sxs-lookup"><span data-stu-id="bc0e4-144">AzureRM.Storage</span></span>
* <span data-ttu-id="bc0e4-145">在新的和設定的儲存體帳戶 Cmdlet 中淘汰下列參數：EnableEncryptionService 和 DisableEncryptionService，因為預設會啟用待用加密，且無法加以停用。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-145">Obsolete following parameters in new and set Storage Account cmdlets: EnableEncryptionService and DisableEncryptionService, since Encryption at Rest is enabled by default and can't be disabled.</span></span>
    - <span data-ttu-id="bc0e4-146">New-AzureRmStorageAccount</span><span class="sxs-lookup"><span data-stu-id="bc0e4-146">New-AzureRmStorageAccount</span></span>
    - <span data-ttu-id="bc0e4-147">Set-AzureRmStorageAccount</span><span class="sxs-lookup"><span data-stu-id="bc0e4-147">Set-AzureRmStorageAccount</span></span>

#### <a name="azurermwebsites"></a><span data-ttu-id="bc0e4-148">AzureRM.Websites</span><span class="sxs-lookup"><span data-stu-id="bc0e4-148">AzureRM.Websites</span></span>
* <span data-ttu-id="bc0e4-149">已修正 Remove-AzureRmWebAppSlot 的說明</span><span class="sxs-lookup"><span data-stu-id="bc0e4-149">Fixed the help for Remove-AzureRmWebAppSlot</span></span>

## <a name="550---march-2018"></a><span data-ttu-id="bc0e4-150">5.5.0 - 2018 年 3 月</span><span class="sxs-lookup"><span data-stu-id="bc0e4-150">5.5.0 - March 2018</span></span>
#### <a name="azurermprofile"></a><span data-ttu-id="bc0e4-151">AzureRM.Profile</span><span class="sxs-lookup"><span data-stu-id="bc0e4-151">AzureRM.Profile</span></span>
* <span data-ttu-id="bc0e4-152">已修正匯入別名的問題</span><span class="sxs-lookup"><span data-stu-id="bc0e4-152">Fixed issue with importing aliases</span></span>
* <span data-ttu-id="bc0e4-153">與版本 6.0.8 並行載入 Newtonsoft.Json 版本 10.0.3</span><span class="sxs-lookup"><span data-stu-id="bc0e4-153">Load version 10.0.3 of Newtonsoft.Json side-by-side with version 6.0.8</span></span>

#### <a name="azurestorage"></a><span data-ttu-id="bc0e4-154">Azure.Storage</span><span class="sxs-lookup"><span data-stu-id="bc0e4-154">Azure.Storage</span></span>
* <span data-ttu-id="bc0e4-155">支援虛刪除功能</span><span class="sxs-lookup"><span data-stu-id="bc0e4-155">Support Soft-Delete feature</span></span>
    - <span data-ttu-id="bc0e4-156">Enable-AzureStorageDeleteRetentionPolicy</span><span class="sxs-lookup"><span data-stu-id="bc0e4-156">Enable-AzureStorageDeleteRetentionPolicy</span></span>
    - <span data-ttu-id="bc0e4-157">Disable-AzureStorageDeleteRetentionPolicy</span><span class="sxs-lookup"><span data-stu-id="bc0e4-157">Disable-AzureStorageDeleteRetentionPolicy</span></span>
    - <span data-ttu-id="bc0e4-158">Get-AzureStorageBlob</span><span class="sxs-lookup"><span data-stu-id="bc0e4-158">Get-AzureStorageBlob</span></span>

#### <a name="azurermanalysisservices"></a><span data-ttu-id="bc0e4-159">AzureRM.AnalysisServices</span><span class="sxs-lookup"><span data-stu-id="bc0e4-159">AzureRM.AnalysisServices</span></span>
* <span data-ttu-id="bc0e4-160">已修正匯入別名的問題</span><span class="sxs-lookup"><span data-stu-id="bc0e4-160">Fixed issue with importing aliases</span></span>
* <span data-ttu-id="bc0e4-161">新增防火牆和查詢向外延展功能的支援，並支援 2017-08-01 API 版本。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-161">Add support of firewall and query scaleout feature, as well as support of 2017-08-01 api version.</span></span>

#### <a name="azurermautomation"></a><span data-ttu-id="bc0e4-162">AzureRM.Automation</span><span class="sxs-lookup"><span data-stu-id="bc0e4-162">AzureRM.Automation</span></span>
* <span data-ttu-id="bc0e4-163">已修正匯入別名的問題</span><span class="sxs-lookup"><span data-stu-id="bc0e4-163">Fixed issue with importing aliases</span></span>

#### <a name="azurermcdn"></a><span data-ttu-id="bc0e4-164">AzureRM.Cdn</span><span class="sxs-lookup"><span data-stu-id="bc0e4-164">AzureRM.Cdn</span></span>
* <span data-ttu-id="bc0e4-165">已修正匯入別名的問題</span><span class="sxs-lookup"><span data-stu-id="bc0e4-165">Fixed issue with importing aliases</span></span>

#### <a name="azurermcognitiveservices"></a><span data-ttu-id="bc0e4-166">AzureRM.CognitiveServices</span><span class="sxs-lookup"><span data-stu-id="bc0e4-166">AzureRM.CognitiveServices</span></span>
* <span data-ttu-id="bc0e4-167">更新 notice.txt 和通知訊息。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-167">Update notice.txt and notice message.</span></span>

#### <a name="azurermcompute"></a><span data-ttu-id="bc0e4-168">AzureRM.Compute</span><span class="sxs-lookup"><span data-stu-id="bc0e4-168">AzureRM.Compute</span></span>
* <span data-ttu-id="bc0e4-169">'New-AzureRmVMSS' 在詳細資訊模式中列印連接字串。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-169">'New-AzureRmVMSS' prints connection strings in verbose mode.</span></span>
* <span data-ttu-id="bc0e4-170">'New-AzureRmVmss' 支援公用 IP 位址、載入平衡規則、傳入的 NAT 規則。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-170">'New-AzureRmVmss' supports public IP address, load balancing rules, inbound NAT rules.</span></span>
* <span data-ttu-id="bc0e4-171">WriteAccelerator 功能</span><span class="sxs-lookup"><span data-stu-id="bc0e4-171">WriteAccelerator feature</span></span>
    - <span data-ttu-id="bc0e4-172">已將 WriteAccelerator 切換參數新增至下列 Cmdlet：Set-AzureRmVMOSDisk Set-AzureRmVMDataDisk Add-AzureRmVMDataDisk Add-AzureRmVmssDataDisk</span><span class="sxs-lookup"><span data-stu-id="bc0e4-172">Added WriteAccelerator switch parameter to the following cmdlets: Set-AzureRmVMOSDisk Set-AzureRmVMDataDisk Add-AzureRmVMDataDisk Add-AzureRmVmssDataDisk</span></span>
    - <span data-ttu-id="bc0e4-173">已將 OsDiskWriteAccelerator 切換參數新增至下列 Cmdlet：Set-AzureRmVmssStorageProfile。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-173">Added OsDiskWriteAccelerator switch parameter to the following cmdlet:     Set-AzureRmVmssStorageProfile.</span></span>
    - <span data-ttu-id="bc0e4-174">已將 OsDiskWriteAccelerator 布林值參數新增至下列 Cdlets：Update-AzureRmVM     Update-AzureRmVmss</span><span class="sxs-lookup"><span data-stu-id="bc0e4-174">Added OsDiskWriteAccelerator Boolean parameter to the following cmdlets:     Update-AzureRmVM     Update-AzureRmVmss</span></span>

#### <a name="azurermdatafactories"></a><span data-ttu-id="bc0e4-175">AzureRM.DataFactories</span><span class="sxs-lookup"><span data-stu-id="bc0e4-175">AzureRM.DataFactories</span></span>
* <span data-ttu-id="bc0e4-176">修正會造成部分加密作業生產無意義錯誤的認證加密問題</span><span class="sxs-lookup"><span data-stu-id="bc0e4-176">Fix credential encryption issue that caused no meaningful error for some encryption operations</span></span>
* <span data-ttu-id="bc0e4-177">啟用要在資料處理站間共用的整合執行階段</span><span class="sxs-lookup"><span data-stu-id="bc0e4-177">Enable integration runtime to be shared across data factory</span></span>

#### <a name="azurermdatafactoryv2"></a><span data-ttu-id="bc0e4-178">AzureRM.DataFactoryV2</span><span class="sxs-lookup"><span data-stu-id="bc0e4-178">AzureRM.DataFactoryV2</span></span>
* <span data-ttu-id="bc0e4-179">為 "Set-AzureRmDataFactoryV2IntegrationRuntime" cmd 新增參數 "SetupScriptContainerSasUri" 和 "Edition"，以啟用自訂設定和編輯選項功能</span><span class="sxs-lookup"><span data-stu-id="bc0e4-179">Add parameter "SetupScriptContainerSasUri" and "Edition" for "Set-AzureRmDataFactoryV2IntegrationRuntime" cmd to enable custom setup and edition selection functionality</span></span>
* <span data-ttu-id="bc0e4-180">修正會造成部分加密作業生產無意義錯誤的認證加密問題。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-180">Fix credential encryption issue that caused no meaningful error for some encryption operations.</span></span>
* <span data-ttu-id="bc0e4-181">啟用要在資料處理站間共用的整合執行階段</span><span class="sxs-lookup"><span data-stu-id="bc0e4-181">Enable integration runtime to be shared across data factory</span></span>

#### <a name="azurermhdinsight"></a><span data-ttu-id="bc0e4-182">AzureRM.HDInsight</span><span class="sxs-lookup"><span data-stu-id="bc0e4-182">AzureRM.HDInsight</span></span>
* <span data-ttu-id="bc0e4-183">已修正匯入別名的問題</span><span class="sxs-lookup"><span data-stu-id="bc0e4-183">Fixed issue with importing aliases</span></span>

#### <a name="azurermkeyvault"></a><span data-ttu-id="bc0e4-184">AzureRM.KeyVault</span><span class="sxs-lookup"><span data-stu-id="bc0e4-184">AzureRM.KeyVault</span></span>
* <span data-ttu-id="bc0e4-185">已修正 Set-AzureRmKeyVaultAccessPolicy 範例</span><span class="sxs-lookup"><span data-stu-id="bc0e4-185">Fixed example for Set-AzureRmKeyVaultAccessPolicy</span></span>

#### <a name="azurermnetwork"></a><span data-ttu-id="bc0e4-186">AzureRM.Network</span><span class="sxs-lookup"><span data-stu-id="bc0e4-186">AzureRM.Network</span></span>
* <span data-ttu-id="bc0e4-187">已修正匯入別名的問題</span><span class="sxs-lookup"><span data-stu-id="bc0e4-187">Fixed issue with importing aliases</span></span>

#### <a name="azurermoperationalinsights"></a><span data-ttu-id="bc0e4-188">AzureRM.OperationalInsights</span><span class="sxs-lookup"><span data-stu-id="bc0e4-188">AzureRM.OperationalInsights</span></span>
* <span data-ttu-id="bc0e4-189">已修正匯入別名的問題</span><span class="sxs-lookup"><span data-stu-id="bc0e4-189">Fixed issue with importing aliases</span></span>

#### <a name="azurermrecoveryservices"></a><span data-ttu-id="bc0e4-190">AzureRM.RecoveryServices</span><span class="sxs-lookup"><span data-stu-id="bc0e4-190">AzureRM.RecoveryServices</span></span>
* <span data-ttu-id="bc0e4-191">已修正匯入別名的問題</span><span class="sxs-lookup"><span data-stu-id="bc0e4-191">Fixed issue with importing aliases</span></span>

#### <a name="azurermrecoveryservicessiterecovery"></a><span data-ttu-id="bc0e4-192">AzureRM.RecoveryServices.SiteRecovery</span><span class="sxs-lookup"><span data-stu-id="bc0e4-192">AzureRM.RecoveryServices.SiteRecovery</span></span>
* <span data-ttu-id="bc0e4-193">已修正匯入別名的問題</span><span class="sxs-lookup"><span data-stu-id="bc0e4-193">Fixed issue with importing aliases</span></span>

#### <a name="azurermresources"></a><span data-ttu-id="bc0e4-194">AzureRM.Resources</span><span class="sxs-lookup"><span data-stu-id="bc0e4-194">AzureRM.Resources</span></span>
* <span data-ttu-id="bc0e4-195">已修正匯入別名的問題</span><span class="sxs-lookup"><span data-stu-id="bc0e4-195">Fixed issue with importing aliases</span></span>

#### <a name="azurermservicebus"></a><span data-ttu-id="bc0e4-196">AzureRM.ServiceBus</span><span class="sxs-lookup"><span data-stu-id="bc0e4-196">AzureRM.ServiceBus</span></span>
* <span data-ttu-id="bc0e4-197">已將 EnableBatchedOperations 屬性新增至佇列</span><span class="sxs-lookup"><span data-stu-id="bc0e4-197">Added EnableBatchedOperations property to Queue</span></span>
* <span data-ttu-id="bc0e4-198">已將 DeadLetteringOnFilterEvaluationExceptions 屬性新增至訂用帳戶</span><span class="sxs-lookup"><span data-stu-id="bc0e4-198">Added DeadLetteringOnFilterEvaluationExceptions property to Subscriptions</span></span>

#### <a name="azurermservicefabric"></a><span data-ttu-id="bc0e4-199">AzureRM.ServiceFabric</span><span class="sxs-lookup"><span data-stu-id="bc0e4-199">AzureRM.ServiceFabric</span></span>
* <span data-ttu-id="bc0e4-200">Service Fabric Cmdlet 重新整理</span><span class="sxs-lookup"><span data-stu-id="bc0e4-200">Service Fabric cmdlet refresh</span></span>
  - <span data-ttu-id="bc0e4-201">已更新 ARM 範本</span><span class="sxs-lookup"><span data-stu-id="bc0e4-201">Updated ARM templates</span></span>
  - <span data-ttu-id="bc0e4-202">不再復原失敗的作業</span><span class="sxs-lookup"><span data-stu-id="bc0e4-202">Failed operations no longer rollback</span></span>
  - <span data-ttu-id="bc0e4-203">Add-AzureRmServiceFabricNodeType</span><span class="sxs-lookup"><span data-stu-id="bc0e4-203">Add-AzureRmServiceFabricNodeType</span></span>
    - <span data-ttu-id="bc0e4-204">VM 預設位於受控磁碟</span><span class="sxs-lookup"><span data-stu-id="bc0e4-204">VMs default to managed disks</span></span>
    - <span data-ttu-id="bc0e4-205">使用現有的 VMSS 子網路</span><span class="sxs-lookup"><span data-stu-id="bc0e4-205">Existing VMSS subnet used</span></span>
    - <span data-ttu-id="bc0e4-206">均為等冪作業</span><span class="sxs-lookup"><span data-stu-id="bc0e4-206">All operations are idempotent</span></span>
  - <span data-ttu-id="bc0e4-207">Remove-AzureRmServiceFabricNodeType 會清除所立的部分 VMSS 和/或叢集節點類型</span><span class="sxs-lookup"><span data-stu-id="bc0e4-207">Remove-AzureRmServiceFabricNodeType cleans up partially created VMSS and/or cluster node types</span></span>
  - <span data-ttu-id="bc0e4-208">已修正複雜屬性類型的 PSCluster 物件輸出</span><span class="sxs-lookup"><span data-stu-id="bc0e4-208">Fixed output of PSCluster object for complex property types</span></span>

#### <a name="azurermsql"></a><span data-ttu-id="bc0e4-209">AzureRM.Sql</span><span class="sxs-lookup"><span data-stu-id="bc0e4-209">AzureRM.Sql</span></span>
* <span data-ttu-id="bc0e4-210">已修正匯入別名的問題</span><span class="sxs-lookup"><span data-stu-id="bc0e4-210">Fixed issue with importing aliases</span></span>
* <span data-ttu-id="bc0e4-211">Get-AzureRmSqlServer、New-AzureRmSqlServer 和 Remove-AzureRmSqlServer 回覆現在包括 FullyQualifiedDomainName 屬性。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-211">Get-AzureRmSqlServer, New-AzureRmSqlServer, and Remove-AzureRmSqlServer response now includes FullyQualifiedDomainName property.</span></span>

#### <a name="azurermwebsites"></a><span data-ttu-id="bc0e4-212">AzureRM.Websites</span><span class="sxs-lookup"><span data-stu-id="bc0e4-212">AzureRM.Websites</span></span>
* <span data-ttu-id="bc0e4-213">已修正匯入別名的問題</span><span class="sxs-lookup"><span data-stu-id="bc0e4-213">Fixed issue with importing aliases</span></span>
* <span data-ttu-id="bc0e4-214">New-AzureRMWebApp - 已新增參數集供建立簡化 WebApp 之用，搭配本機 GIT 存放庫支援。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-214">New-AzureRMWebApp - added parameter set for simplified WebApp creation, with local git repository support.</span></span>

## <a name="540---february-2018"></a><span data-ttu-id="bc0e4-215">5.4.0 - 2018 年 2 月</span><span class="sxs-lookup"><span data-stu-id="bc0e4-215">5.4.0 - February 2018</span></span>
#### <a name="azurermautomation"></a><span data-ttu-id="bc0e4-216">AzureRM.Automation</span><span class="sxs-lookup"><span data-stu-id="bc0e4-216">AzureRM.Automation</span></span>
* <span data-ttu-id="bc0e4-217">將別名從 New-AzureRmAutomationModule 新增至 Import-AzureRmAutomationModule</span><span class="sxs-lookup"><span data-stu-id="bc0e4-217">Added alias from New-AzureRmAutomationModule to Import-AzureRmAutomationModule</span></span>

#### <a name="azurermcompute"></a><span data-ttu-id="bc0e4-218">AzureRM.Compute</span><span class="sxs-lookup"><span data-stu-id="bc0e4-218">AzureRM.Compute</span></span>
* <span data-ttu-id="bc0e4-219">修正某些 Get Cmdlet 的 ErrorAction 問題。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-219">Fix ErrorAction issue for some of Get cmdlets.</span></span>

#### <a name="azurermcontainerinstance"></a><span data-ttu-id="bc0e4-220">AzureRM.ContainerInstance</span><span class="sxs-lookup"><span data-stu-id="bc0e4-220">AzureRM.ContainerInstance</span></span>
* <span data-ttu-id="bc0e4-221">套用 Azure 容器執行個體 SDK 2018-02-01</span><span class="sxs-lookup"><span data-stu-id="bc0e4-221">Apply Azure Container Instance SDK 2018-02-01</span></span>
    - <span data-ttu-id="bc0e4-222">支援 DNS 名稱標籤</span><span class="sxs-lookup"><span data-stu-id="bc0e4-222">Support DNS name label</span></span>

#### <a name="azurermdevtestlabs"></a><span data-ttu-id="bc0e4-223">AzureRM.DevTestLabs</span><span class="sxs-lookup"><span data-stu-id="bc0e4-223">AzureRM.DevTestLabs</span></span>
* <span data-ttu-id="bc0e4-224">修正所有先前未正常運作的 GET Cmdlet。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-224">Fixed all of the GET cmdlets which previously weren't working.</span></span>

#### <a name="azurermeventhub"></a><span data-ttu-id="bc0e4-225">AzureRM.EventHub</span><span class="sxs-lookup"><span data-stu-id="bc0e4-225">AzureRM.EventHub</span></span>
* <span data-ttu-id="bc0e4-226">修正 Get-AzureRmEventHubGeoDRConfiguration 說明中的錯誤</span><span class="sxs-lookup"><span data-stu-id="bc0e4-226">Fix bug in Get-AzureRmEventHubGeoDRConfiguration help</span></span>

#### <a name="azurermnetwork"></a><span data-ttu-id="bc0e4-227">AzureRM.Network</span><span class="sxs-lookup"><span data-stu-id="bc0e4-227">AzureRM.Network</span></span>
* <span data-ttu-id="bc0e4-228">已新增用來建立新連線監視的 Cmdlet</span><span class="sxs-lookup"><span data-stu-id="bc0e4-228">Added cmdlet to create a new connection monitor</span></span>
    - <span data-ttu-id="bc0e4-229">New-AzureRmNetworkWatcherConnectionMonitor</span><span class="sxs-lookup"><span data-stu-id="bc0e4-229">New-AzureRmNetworkWatcherConnectionMonitor</span></span>
* <span data-ttu-id="bc0e4-230">已新增用來更新連線監視的 Cmdlet</span><span class="sxs-lookup"><span data-stu-id="bc0e4-230">Added cmdlet to update a connection monitor</span></span>
    - <span data-ttu-id="bc0e4-231">Set-AzureRmNetworkWatcherConnectionMonitor</span><span class="sxs-lookup"><span data-stu-id="bc0e4-231">Set-AzureRmNetworkWatcherConnectionMonitor</span></span>
* <span data-ttu-id="bc0e4-232">已新增用來取得連線監視或連線監視清單的 Cmdlet</span><span class="sxs-lookup"><span data-stu-id="bc0e4-232">Added cmdlet to get connection monitor or connection monitor list</span></span>
    - <span data-ttu-id="bc0e4-233">Get-AzureRmNetworkWatcherConnectionMonitor</span><span class="sxs-lookup"><span data-stu-id="bc0e4-233">Get-AzureRmNetworkWatcherConnectionMonitor</span></span>
* <span data-ttu-id="bc0e4-234">已新增用來查詢連線監視的 Cmdlet</span><span class="sxs-lookup"><span data-stu-id="bc0e4-234">Added cmdlet to query connection monitor</span></span>
    - <span data-ttu-id="bc0e4-235">Get-AzureRmNetworkWatcherConnectionMonitorReport</span><span class="sxs-lookup"><span data-stu-id="bc0e4-235">Get-AzureRmNetworkWatcherConnectionMonitorReport</span></span>
* <span data-ttu-id="bc0e4-236">已新增用來啟動連線監視的 Cmdlet</span><span class="sxs-lookup"><span data-stu-id="bc0e4-236">Added cmdlet to start connection monitor</span></span>
    - <span data-ttu-id="bc0e4-237">Start-AzureRmNetworkWatcherConnectionMonitor</span><span class="sxs-lookup"><span data-stu-id="bc0e4-237">Start-AzureRmNetworkWatcherConnectionMonitor</span></span>
* <span data-ttu-id="bc0e4-238">已新增用來停止連線監視的 Cmdlet</span><span class="sxs-lookup"><span data-stu-id="bc0e4-238">Added cmdlet to stop connection monitor</span></span>
    - <span data-ttu-id="bc0e4-239">Stop-AzureRmNetworkWatcherConnectionMonitor</span><span class="sxs-lookup"><span data-stu-id="bc0e4-239">Stop-AzureRmNetworkWatcherConnectionMonitor</span></span>
* <span data-ttu-id="bc0e4-240">已新增用來移除連線監視的 Cmdlet</span><span class="sxs-lookup"><span data-stu-id="bc0e4-240">Added cmdlet to remove connection monitor</span></span>
    - <span data-ttu-id="bc0e4-241">Remove-AzureRmNetworkWatcherConnectionMonitor</span><span class="sxs-lookup"><span data-stu-id="bc0e4-241">Remove-AzureRmNetworkWatcherConnectionMonitor</span></span>
* <span data-ttu-id="bc0e4-242">已更新 Set-AzureRmApplicationGatewayBackendAddressPool 文件從而移除已淘汰的範例</span><span class="sxs-lookup"><span data-stu-id="bc0e4-242">Updated Set-AzureRmApplicationGatewayBackendAddressPool documentation to remove deprecated example</span></span>
* <span data-ttu-id="bc0e4-243">已對應用程式閘道新增 EnableHttp2 旗標</span><span class="sxs-lookup"><span data-stu-id="bc0e4-243">Added EnableHttp2 flag to Application Gateway</span></span>
    - <span data-ttu-id="bc0e4-244">已更新 New-AzureRmApplicationGateway：已新增選擇性參數 -EnableHttp2</span><span class="sxs-lookup"><span data-stu-id="bc0e4-244">Updated New-AzureRmApplicationGateway: Added optional parameter -EnableHttp2</span></span>
* <span data-ttu-id="bc0e4-245">將 IpTags 新增至 PublicIpAddress</span><span class="sxs-lookup"><span data-stu-id="bc0e4-245">Add IpTags to PublicIpAddress</span></span>
    - <span data-ttu-id="bc0e4-246">已更新 New-AzureRmPublicIpAddress：已新增 IpTags</span><span class="sxs-lookup"><span data-stu-id="bc0e4-246">Updated New-AzureRmPublicIpAddress: Added IpTags</span></span>
    - <span data-ttu-id="bc0e4-247">New-AzureRmPublicIpTag 以新增 Iptag</span><span class="sxs-lookup"><span data-stu-id="bc0e4-247">New-AzureRmPublicIpTag to add Iptag</span></span>
* <span data-ttu-id="bc0e4-248">在 RouteTable 和 effectiveRoute 中新增 DisableBgpRoutePropagation 屬性。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-248">Add DisableBgpRoutePropagation property in RouteTable and effectiveRoute.</span></span>

#### <a name="azurermresources"></a><span data-ttu-id="bc0e4-249">AzureRM.Resources</span><span class="sxs-lookup"><span data-stu-id="bc0e4-249">AzureRM.Resources</span></span>
* <span data-ttu-id="bc0e4-250">Register-AzureRmProviderFeature：已在文件中新增遺漏的範例</span><span class="sxs-lookup"><span data-stu-id="bc0e4-250">Register-AzureRmProviderFeature: Added missing example in the docs</span></span>
* <span data-ttu-id="bc0e4-251">Register-AzureRmResourceProvider：已在文件中新增遺漏的範例</span><span class="sxs-lookup"><span data-stu-id="bc0e4-251">Register-AzureRmResourceProvider: Added missing example in the docs</span></span>

#### <a name="azurermstorage"></a><span data-ttu-id="bc0e4-252">AzureRM.Storage</span><span class="sxs-lookup"><span data-stu-id="bc0e4-252">AzureRM.Storage</span></span>
* <span data-ttu-id="bc0e4-253">在新的和設定的儲存體帳戶 Cmdlet 中淘汰下列參數：EnableEncryptionService 和 DisableEncryptionService，因為預設會啟用待用加密，且無法加以停用。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-253">Obsolete following parameters in new and set Storage Account cmdlets: EnableEncryptionService and DisableEncryptionService, since Encryption at Rest is enabled by default and can't be disabled.</span></span>
    - <span data-ttu-id="bc0e4-254">New-AzureRmStorageAccount</span><span class="sxs-lookup"><span data-stu-id="bc0e4-254">New-AzureRmStorageAccount</span></span>
    - <span data-ttu-id="bc0e4-255">Set-AzureRmStorageAccount</span><span class="sxs-lookup"><span data-stu-id="bc0e4-255">Set-AzureRmStorageAccount</span></span>


## <a name="530---february-2018"></a><span data-ttu-id="bc0e4-256">5.3.0 - 2018 年 2 月</span><span class="sxs-lookup"><span data-stu-id="bc0e4-256">5.3.0 - February 2018</span></span>
### <a name="azurermprofile"></a><span data-ttu-id="bc0e4-257">AzureRM.Profile</span><span class="sxs-lookup"><span data-stu-id="bc0e4-257">AzureRM.Profile</span></span>
* <span data-ttu-id="bc0e4-258">已新增 PowerShell 3 和 4 的取代警告</span><span class="sxs-lookup"><span data-stu-id="bc0e4-258">Added deprecation warning for PowerShell 3 and 4</span></span>
* <span data-ttu-id="bc0e4-259">`Add-AzureRmAccount` 已重新命名為 `Connect-AzureRmAccount`；舊的 Cmdlet 名稱已新增別名，而其他別名 (`Login-AzAccount` 和 `Login-AzureRmAccount`) 已重新導向至新的 Cmdlet 名稱。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-259">`Add-AzureRmAccount` has been renamed as `Connect-AzureRmAccount`; an alias has been added for the old cmdlet name, and other aliases (`Login-AzAccount` and `Login-AzureRmAccount`) have been redirected to the new cmdlet name.</span></span>
* <span data-ttu-id="bc0e4-260">`Remove-AzureRmAccount` 已重新命名為 `Disconnect-AzureRmAccount`；舊的 Cmdlet 名稱已新增別名，而其他別名 (`Logout-AzAccount` 和 `Logout-AzureRmAccount`) 已重新導向至新的 Cmdlet 名稱。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-260">`Remove-AzureRmAccount` has been renamed as `Disconnect-AzureRmAccount`; an alias has been added for the old cmdlet name, and other aliases (`Logout-AzAccount` and `Logout-AzureRmAccount`) have been redirected to the new cmdlet name.</span></span>
* <span data-ttu-id="bc0e4-261">已更正資源字串使用 `Connect-AzureRmAccount`，而不是 `Login-AzureRmAccount`</span><span class="sxs-lookup"><span data-stu-id="bc0e4-261">Corrected Resource Strings to use `Connect-AzureRmAccount` instead of `Login-AzureRmAccount`</span></span>
* <span data-ttu-id="bc0e4-262">`Add-AzureRmEnvironment`和`Set-AzureRmEnvironment`</span><span class="sxs-lookup"><span data-stu-id="bc0e4-262">`Add-AzureRmEnvironment` and `Set-AzureRmEnvironment`</span></span>
  - <span data-ttu-id="bc0e4-263">已將 `-AzureOperationalInsightsEndpoint` 和 `-AzureOperationalInsightsEndpointResourceId`新增為參數，搭配 OperationalInsights 資料平面 RP 使用。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-263">Added `-AzureOperationalInsightsEndpoint` and `-AzureOperationalInsightsEndpointResourceId` as parameters for use with OperationalInsights data plane RP.</span></span>

### <a name="azurermanalysisservices"></a><span data-ttu-id="bc0e4-264">AzureRM.AnalysisServices</span><span class="sxs-lookup"><span data-stu-id="bc0e4-264">AzureRM.AnalysisServices</span></span>
* <span data-ttu-id="bc0e4-265">已更正 `Login-AzureRmAccount` 的使用方式來使用 `Connect-AzureRmAccount`</span><span class="sxs-lookup"><span data-stu-id="bc0e4-265">Corrected usage of `Login-AzureRmAccount` to use `Connect-AzureRmAccount`</span></span>

### <a name="azurermcompute"></a><span data-ttu-id="bc0e4-266">AzureRM.Compute</span><span class="sxs-lookup"><span data-stu-id="bc0e4-266">AzureRM.Compute</span></span>
* <span data-ttu-id="bc0e4-267">已將 `-AvailabilitySetName` 參數新增至簡化的 `New-AzureRmVM` 參數集。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-267">Added `-AvailabilitySetName` parameter to the simplified parameterset of `New-AzureRmVM`.</span></span>
* <span data-ttu-id="bc0e4-268">已更正 `Login-AzureRmAccount` 的使用方式來使用 `Connect-AzureRmAccount`</span><span class="sxs-lookup"><span data-stu-id="bc0e4-268">Corrected usage of `Login-AzureRmAccount` to use `Connect-AzureRmAccount`</span></span>
* <span data-ttu-id="bc0e4-269">適用於 VM 和 VM 擴展集的使用者指派識別身分支援</span><span class="sxs-lookup"><span data-stu-id="bc0e4-269">User assigned identity support for VM and VM scale set</span></span>
    - <span data-ttu-id="bc0e4-270">已將 `-IdentityType` 和 `-IdentityId` 參數新增至 `New-AzureRmVMConfig`、`New-AzureRmVmssConfig`、`Update-AzureRmVM` 和 `Update-AzureRmVmss`</span><span class="sxs-lookup"><span data-stu-id="bc0e4-270">`-IdentityType` and `-IdentityId` parameters are added to `New-AzureRmVMConfig`, `New-AzureRmVmssConfig`, `Update-AzureRmVM` and `Update-AzureRmVmss`</span></span>
* <span data-ttu-id="bc0e4-271">在 `Add-AzureRmVmssNetworkInterfaceConfig` 中新增 `-EnableIPForwarding` 參數</span><span class="sxs-lookup"><span data-stu-id="bc0e4-271">Added `-EnableIPForwarding` parameter to `Add-AzureRmVmssNetworkInterfaceConfig`</span></span>
* <span data-ttu-id="bc0e4-272">在 `New-AzureRmVmssConfig` 中新增 `-Priority` 參數</span><span class="sxs-lookup"><span data-stu-id="bc0e4-272">Added `-Priority` parameter to `New-AzureRmVmssConfig`</span></span>

### <a name="azurermdatalakeanalytics"></a><span data-ttu-id="bc0e4-273">AzureRM.DataLakeAnalytics</span><span class="sxs-lookup"><span data-stu-id="bc0e4-273">AzureRM.DataLakeAnalytics</span></span>
* <span data-ttu-id="bc0e4-274">已更正 `Login-AzureRmAccount` 的使用方式來使用 `Connect-AzureRmAccount`</span><span class="sxs-lookup"><span data-stu-id="bc0e4-274">Corrected usage of `Login-AzureRmAccount` to use `Connect-AzureRmAccount`</span></span>

### <a name="azurermdatalakestore"></a><span data-ttu-id="bc0e4-275">AzureRM.DataLakeStore</span><span class="sxs-lookup"><span data-stu-id="bc0e4-275">AzureRM.DataLakeStore</span></span>
* <span data-ttu-id="bc0e4-276">已更正 `Login-AzureRmAccount` 的使用方式來使用 `Connect-AzureRmAccount`</span><span class="sxs-lookup"><span data-stu-id="bc0e4-276">Corrected usage of `Login-AzureRmAccount` to use `Connect-AzureRmAccount`</span></span>
* <span data-ttu-id="bc0e4-277">已更正執行此 Cmdlet 而不需要登入 `Login-AzureRmAccount` 時的 `Test-AzureRmDataLakeStoreAccount` 錯誤訊息</span><span class="sxs-lookup"><span data-stu-id="bc0e4-277">Corrected the error message of `Test-AzureRmDataLakeStoreAccount` when running this cmdlet without having logged in with `Login-AzureRmAccount`</span></span>

### <a name="azurermeventgrid"></a><span data-ttu-id="bc0e4-278">AzureRM.EventGrid</span><span class="sxs-lookup"><span data-stu-id="bc0e4-278">AzureRM.EventGrid</span></span>
* <span data-ttu-id="bc0e4-279">已更新使用 2018-01-01 API 版本。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-279">Updated to use the 2018-01-01 API version.</span></span>

### <a name="azurermeventhub"></a><span data-ttu-id="bc0e4-280">AzureRM.EventHub</span><span class="sxs-lookup"><span data-stu-id="bc0e4-280">AzureRM.EventHub</span></span>

* <span data-ttu-id="bc0e4-281">已新增下列異地災害復原作業的新命令。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-281">Added below new commands for Geo Disaster Recovery operations.</span></span>
  - <span data-ttu-id="bc0e4-282">建立新的別名 (災害復原設定)：</span><span class="sxs-lookup"><span data-stu-id="bc0e4-282">Creating a new Alias (Disaster Recovery configuration):</span></span>
    - `New-AzureRmEventHubGeoDRConfiguration`
  - <span data-ttu-id="bc0e4-283">擷取別名 (災害復原設定)：</span><span class="sxs-lookup"><span data-stu-id="bc0e4-283">Retrieve Alias (Disaster Recovery configuration) :</span></span>
    - `Get-AzureRmEventHubGeoDRConfiguration`
  - <span data-ttu-id="bc0e4-284">停用災害復原，並停止將變更從主要命名空間複寫至次要命名空間</span><span class="sxs-lookup"><span data-stu-id="bc0e4-284">Disabling the Disaster Recovery and stops replicating changes from primary to secondary namespaces</span></span>
    - `Set-AzureRmEventHubGeoDRConfigurationBreakPair`
  - <span data-ttu-id="bc0e4-285">叫用災害復原容錯移轉，並將別名重新設定為指向次要命名空間</span><span class="sxs-lookup"><span data-stu-id="bc0e4-285">Invoking Disaster Recovery failover and reconfigure the alias to point to the secondary namespace</span></span>
    - `Set-AzureRmEventHubGeoDRConfigurationFailOver`
  - <span data-ttu-id="bc0e4-286">刪除別名 (災害復原設定)</span><span class="sxs-lookup"><span data-stu-id="bc0e4-286">Deleting an Alias(Disaster Recovery configuration)</span></span>
    - `Remove-AzureRmEventHubGeoDRConfiguration`
* <span data-ttu-id="bc0e4-287">已新增下列命令，用以檢查命名空間名稱和 GeoDr 設定名稱 - 別名可用性。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-287">Added below new commands for checking the Namespace Name and GeoDr Configuration Name - Alias availability.</span></span>
  - <span data-ttu-id="bc0e4-288">檢查命名空間名稱或別名 (災害復原設定) 名稱的可用性：</span><span class="sxs-lookup"><span data-stu-id="bc0e4-288">Check the Availability of Namespace name or Alias(Disaster Recovery configuration) name:</span></span>
    - `Test-AzureRmEventHubName`

### <a name="azurerminsights"></a><span data-ttu-id="bc0e4-289">AzureRM.Insights</span><span class="sxs-lookup"><span data-stu-id="bc0e4-289">AzureRM.Insights</span></span>
* <span data-ttu-id="bc0e4-290">已更正 `Login-AzureRmAccount` 的使用方式來使用 `Connect-AzureRmAccount`</span><span class="sxs-lookup"><span data-stu-id="bc0e4-290">Corrected usage of `Login-AzureRmAccount` to use `Connect-AzureRmAccount`</span></span>

### <a name="azurermkeyvault"></a><span data-ttu-id="bc0e4-291">AzureRM.KeyVault</span><span class="sxs-lookup"><span data-stu-id="bc0e4-291">AzureRM.KeyVault</span></span>
* <span data-ttu-id="bc0e4-292">已更正 `Login-AzureRmAccount` 的使用方式來使用 `Connect-AzureRmAccount`</span><span class="sxs-lookup"><span data-stu-id="bc0e4-292">Corrected usage of `Login-AzureRmAccount` to use `Connect-AzureRmAccount`</span></span>

### <a name="azurermnetwork"></a><span data-ttu-id="bc0e4-293">AzureRM.Network</span><span class="sxs-lookup"><span data-stu-id="bc0e4-293">AzureRM.Network</span></span>
* <span data-ttu-id="bc0e4-294">修正覆寫訊息「您確定要覆寫來源嗎」</span><span class="sxs-lookup"><span data-stu-id="bc0e4-294">Fix overwrite message 'Are you sure you want to overwriteresource'</span></span>

#### <a name="azurermoperationalinsights"></a><span data-ttu-id="bc0e4-295">AzureRM.OperationalInsights</span><span class="sxs-lookup"><span data-stu-id="bc0e4-295">AzureRM.OperationalInsights</span></span>
* <span data-ttu-id="bc0e4-296">已新增透過 `Invoke-AzureRmOperationalInsightsQuery` 進行 V2 API 查詢的支援。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-296">Added support for V2 API querying via `Invoke-AzureRmOperationalInsightsQuery`.</span></span> <span data-ttu-id="bc0e4-297">請參閱 [https://dev.loganalytics.io/](https://dev.loganalytics.io/) 以取得新 API 的詳細資訊。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-297">See [https://dev.loganalytics.io/](https://dev.loganalytics.io/) for more info on the new API.</span></span>

### <a name="azurermresources"></a><span data-ttu-id="bc0e4-298">AzureRM.Resources</span><span class="sxs-lookup"><span data-stu-id="bc0e4-298">AzureRM.Resources</span></span>
* <span data-ttu-id="bc0e4-299">`Get-AzureRmADServicePrincipal`：已將 `-ServicePrincipalName` 從預設的空參數集移除，因為它是多餘的 SPN 參數集</span><span class="sxs-lookup"><span data-stu-id="bc0e4-299">`Get-AzureRmADServicePrincipal`: Removed `-ServicePrincipalName` from the default Empty parameter set as it was redundant with the SPN parameter set</span></span>

### <a name="azurermservicebus"></a><span data-ttu-id="bc0e4-300">AzureRM.ServiceBus</span><span class="sxs-lookup"><span data-stu-id="bc0e4-300">AzureRM.ServiceBus</span></span>

* <span data-ttu-id="bc0e4-301">已新增 `Remove-AzureRmServiceBusRule` 和 `Get-AzureRmServiceBusKey` 的功能修正</span><span class="sxs-lookup"><span data-stu-id="bc0e4-301">Added functionality fix for `Remove-AzureRmServiceBusRule` and `Get-AzureRmServiceBusKey`</span></span>
* <span data-ttu-id="bc0e4-302">已新增下列異地災害復原作業的新 Commandlet。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-302">Added below new commandlets for Geo Disaster Recovery operations.</span></span>
  - <span data-ttu-id="bc0e4-303">建立新的別名 (災害復原設定)：</span><span class="sxs-lookup"><span data-stu-id="bc0e4-303">Creating a new Alias (Disaster Recovery configuration):</span></span>
    - `New-AzureRmServiceBusDRConfigurations`
  - <span data-ttu-id="bc0e4-304">擷取別名 (災害復原設定)：</span><span class="sxs-lookup"><span data-stu-id="bc0e4-304">Retrieve Alias (Disaster Recovery configuration) :</span></span>
    - `Get-AzureRmServiceBusDRConfigurations`
  - <span data-ttu-id="bc0e4-305">停用災害復原，並停止將變更從主要命名空間複寫至次要命名空間</span><span class="sxs-lookup"><span data-stu-id="bc0e4-305">Disabling the Disaster Recovery and stops replicating changes from primary to secondary namespaces</span></span>
    - `Set-AzureRmServiceBusDRConfigurationsBreakPairing`
  - <span data-ttu-id="bc0e4-306">叫用災害復原容錯移轉，並將別名重新設定為指向次要命名空間</span><span class="sxs-lookup"><span data-stu-id="bc0e4-306">Invoking Disaster Recovery failover and reconfigure the alias to point to the secondary namespace</span></span>
    - `Set-AzureRmServiceBusDRConfigurationsFailOver`
  - <span data-ttu-id="bc0e4-307">刪除別名 (災害復原設定)</span><span class="sxs-lookup"><span data-stu-id="bc0e4-307">Deleting an Alias(Disaster Recovery configuration)</span></span>
    - `Remove-AzureRmServiceBusDRConfigurations`
* <span data-ttu-id="bc0e4-308">已更新 `Test-AzureRmServiceBusName` Commandlet 以支援異地災害復原 - 別名名稱檢查可用性作業。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-308">Updated `Test-AzureRmServiceBusName` commandlets to support Geo Disaster Recovery - Alias name check availability operations.</span></span>
  - <span data-ttu-id="bc0e4-309">檢查命名空間名稱或別名 (災害復原設定) 名稱的可用性：</span><span class="sxs-lookup"><span data-stu-id="bc0e4-309">Check the Availability of Namespace name or Alias(Disaster Recovery configuration) name:</span></span>
    - `Test-AzureRmServiceBusName`

### <a name="azurermusageaggregates"></a><span data-ttu-id="bc0e4-310">AzureRM.UsageAggregates</span><span class="sxs-lookup"><span data-stu-id="bc0e4-310">AzureRM.UsageAggregates</span></span>
* <span data-ttu-id="bc0e4-311">已更正 `Login-AzureRmAccount` 的使用方式來使用 `Connect-AzureRmAccount`</span><span class="sxs-lookup"><span data-stu-id="bc0e4-311">Corrected usage of `Login-AzureRmAccount` to use `Connect-AzureRmAccount`</span></span>

## <a name="520---january-2018"></a><span data-ttu-id="bc0e4-312">5.2.0 - 2018 年 1 月</span><span class="sxs-lookup"><span data-stu-id="bc0e4-312">5.2.0 - January 2018</span></span>
#### <a name="azurermprofile"></a><span data-ttu-id="bc0e4-313">AzureRM.Profile</span><span class="sxs-lookup"><span data-stu-id="bc0e4-313">AzureRM.Profile</span></span>
* <span data-ttu-id="bc0e4-314">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-314">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>
* <span data-ttu-id="bc0e4-315">Add-AzureRmAccount</span><span class="sxs-lookup"><span data-stu-id="bc0e4-315">Add-AzureRmAccount</span></span>
  * <span data-ttu-id="bc0e4-316">已新增 -MSI 登入，以便使用目前虛擬機器/服務的受管理服務身分識別之認證來進行驗證</span><span class="sxs-lookup"><span data-stu-id="bc0e4-316">Added -MSI login for authenticationg using the credentials of the Managed Service Identity of the current VM / Service</span></span>
  * <span data-ttu-id="bc0e4-317">修正了以使用者所提供的存取權杖登入時，KeyVault 驗證所發生的問題</span><span class="sxs-lookup"><span data-stu-id="bc0e4-317">Fixed KeyVault Authentication when logging in with user-provided access tokens</span></span>

#### <a name="azurestorage"></a><span data-ttu-id="bc0e4-318">Azure.Storage</span><span class="sxs-lookup"><span data-stu-id="bc0e4-318">Azure.Storage</span></span>
* <span data-ttu-id="bc0e4-319">新增用以取得和設定儲存體服務屬性的 Cmdlet</span><span class="sxs-lookup"><span data-stu-id="bc0e4-319">Add cmdlets to get and set Storage service properties</span></span>
    - <span data-ttu-id="bc0e4-320">Get-AzureStorageServiceProperty</span><span class="sxs-lookup"><span data-stu-id="bc0e4-320">Get-AzureStorageServiceProperty</span></span>
    - <span data-ttu-id="bc0e4-321">Update-AzureStorageServiceProperty</span><span class="sxs-lookup"><span data-stu-id="bc0e4-321">Update-AzureStorageServiceProperty</span></span>

#### <a name="azurermanalysisservices"></a><span data-ttu-id="bc0e4-322">AzureRM.AnalysisServices</span><span class="sxs-lookup"><span data-stu-id="bc0e4-322">AzureRM.AnalysisServices</span></span>
* <span data-ttu-id="bc0e4-323">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-323">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermapimanagement"></a><span data-ttu-id="bc0e4-324">AzureRM.ApiManagement</span><span class="sxs-lookup"><span data-stu-id="bc0e4-324">AzureRM.ApiManagement</span></span>
* <span data-ttu-id="bc0e4-325">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-325">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="bc0e4-326">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-326">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>
* <span data-ttu-id="bc0e4-327">針對 New-AzureRmApiManagementProperty、Set-AzureRmApiManagementProperty 和 New-AzureRmApiManagement，已淘汰 -Tags 並改用 -Tag</span><span class="sxs-lookup"><span data-stu-id="bc0e4-327">Obsoleted -Tags in favor of -Tag for New-AzureRmApiManagementProperty, Set-AzureRmApiManagementProperty, and New-AzureRmApiManagement</span></span>

#### <a name="azurermapplicationinsights"></a><span data-ttu-id="bc0e4-328">AzureRM.ApplicationInsights</span><span class="sxs-lookup"><span data-stu-id="bc0e4-328">AzureRM.ApplicationInsights</span></span>
* <span data-ttu-id="bc0e4-329">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-329">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="bc0e4-330">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-330">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermautomation"></a><span data-ttu-id="bc0e4-331">AzureRM.Automation</span><span class="sxs-lookup"><span data-stu-id="bc0e4-331">AzureRM.Automation</span></span>
* <span data-ttu-id="bc0e4-332">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-332">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="bc0e4-333">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-333">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>
* <span data-ttu-id="bc0e4-334">針對 Set-AzureRmAutomationRunbook，已淘汰 -Tags 並改用 -Tag</span><span class="sxs-lookup"><span data-stu-id="bc0e4-334">Obsoleted -Tags in favor of -Tag for Set-AzureRmAutomationRunbook</span></span>

#### <a name="azurermbackup"></a><span data-ttu-id="bc0e4-335">AzureRM.Backup</span><span class="sxs-lookup"><span data-stu-id="bc0e4-335">AzureRM.Backup</span></span>
* <span data-ttu-id="bc0e4-336">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-336">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="bc0e4-337">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-337">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermbatch"></a><span data-ttu-id="bc0e4-338">AzureRM.Batch</span><span class="sxs-lookup"><span data-stu-id="bc0e4-338">AzureRM.Batch</span></span>
* <span data-ttu-id="bc0e4-339">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-339">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="bc0e4-340">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-340">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermcdn"></a><span data-ttu-id="bc0e4-341">AzureRM.Cdn</span><span class="sxs-lookup"><span data-stu-id="bc0e4-341">AzureRM.Cdn</span></span>
* <span data-ttu-id="bc0e4-342">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-342">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="bc0e4-343">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-343">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>
* <span data-ttu-id="bc0e4-344">針對 New-AzureRmCdnEndpoint 和 New-AzureRmCdnProfile，已淘汰 -Tags 並改用 -Tag</span><span class="sxs-lookup"><span data-stu-id="bc0e4-344">Obsoleted -Tags in favor of -Tag for New-AzureRmCdnEndpoint and New-AzureRmCdnProfile</span></span>

#### <a name="azurermcognitiveservices"></a><span data-ttu-id="bc0e4-345">AzureRM.CognitiveServices</span><span class="sxs-lookup"><span data-stu-id="bc0e4-345">AzureRM.CognitiveServices</span></span>
* <span data-ttu-id="bc0e4-346">整合認知服務管理 SDK 3.0.0 版。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-346">Integrate with Cognitive Services Management SDK version 3.0.0.</span></span>

#### <a name="azurermcompute"></a><span data-ttu-id="bc0e4-347">AzureRM.Compute</span><span class="sxs-lookup"><span data-stu-id="bc0e4-347">AzureRM.Compute</span></span>
* <span data-ttu-id="bc0e4-348">已將簡化的參數新增到 New-AzureRmVmss，後者會使用智慧型預設值建立虛擬機器擴展集和所有必要的資源</span><span class="sxs-lookup"><span data-stu-id="bc0e4-348">Added simplified parameter set to New-AzureRmVmss, which creates a Virtual Machine Scale Set and all required resources using smart defaults</span></span>
* <span data-ttu-id="bc0e4-349">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-349">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="bc0e4-350">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-350">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>
* <span data-ttu-id="bc0e4-351">針對 New-AzureRmVm 和 Update-AzureRmVm，已淘汰 -Tags 並改用 -Tag</span><span class="sxs-lookup"><span data-stu-id="bc0e4-351">Obsoleted -Tags in favor of -Tag for New-AzureRmVm and Update-AzureRmVm</span></span>
* <span data-ttu-id="bc0e4-352">修正了限制中包含區域時，Get-AzureRmComputeResourceSku Cmdlet 所發生的問題。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-352">Fixed Get-AzureRmComputeResourceSku cmdlet when Zone is included in restriction.</span></span>
* <span data-ttu-id="bc0e4-353">為了支援 Azure 監視器的接收，已更新診斷代理程式的設定結構描述。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-353">Updated Diagnostics Agent configuration schema for Azure Monitor sink support.</span></span>

#### <a name="azurermcontainerinstance"></a><span data-ttu-id="bc0e4-354">AzureRM.ContainerInstance</span><span class="sxs-lookup"><span data-stu-id="bc0e4-354">AzureRM.ContainerInstance</span></span>
* <span data-ttu-id="bc0e4-355">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-355">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="bc0e4-356">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-356">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermcontainerregistry"></a><span data-ttu-id="bc0e4-357">AzureRM.ContainerRegistry</span><span class="sxs-lookup"><span data-stu-id="bc0e4-357">AzureRM.ContainerRegistry</span></span>
* <span data-ttu-id="bc0e4-358">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-358">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="bc0e4-359">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-359">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermdatafactories"></a><span data-ttu-id="bc0e4-360">AzureRM.DataFactories</span><span class="sxs-lookup"><span data-stu-id="bc0e4-360">AzureRM.DataFactories</span></span>
* <span data-ttu-id="bc0e4-361">已讓所有資料存放區所連結的服務都支援 Azure Key Vault</span><span class="sxs-lookup"><span data-stu-id="bc0e4-361">Enabled Azure Key Vault support for all data store linked services</span></span>
* <span data-ttu-id="bc0e4-362">已新增 Azure SSIS 整合執行階段的授權類型屬性</span><span class="sxs-lookup"><span data-stu-id="bc0e4-362">Added license type property for Azure SSIS integration runtime</span></span>
* <span data-ttu-id="bc0e4-363">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-363">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="bc0e4-364">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-364">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>
* <span data-ttu-id="bc0e4-365">針對 New-AzureRmDataFactory，已淘汰 -Tags 並改用 -Tag</span><span class="sxs-lookup"><span data-stu-id="bc0e4-365">Obsoleted -Tags in favor of -Tag for New-AzureRmDataFactory</span></span>

#### <a name="azurermdatafactoryv2"></a><span data-ttu-id="bc0e4-366">AzureRM.DataFactoryV2</span><span class="sxs-lookup"><span data-stu-id="bc0e4-366">AzureRM.DataFactoryV2</span></span>
* <span data-ttu-id="bc0e4-367">已讓所有資料存放區所連結的服務都支援 Azure Key Vault</span><span class="sxs-lookup"><span data-stu-id="bc0e4-367">Enabled Azure Key Vault support for all data store linked services</span></span>
* <span data-ttu-id="bc0e4-368">已新增 Azure SSIS 整合執行階段的授權類型屬性</span><span class="sxs-lookup"><span data-stu-id="bc0e4-368">Added license type property for Azure SSIS integration runtime</span></span>
* <span data-ttu-id="bc0e4-369">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-369">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="bc0e4-370">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-370">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>
* <span data-ttu-id="bc0e4-371">新增「Set-AzureRmDataFactoryV2IntegrationRuntime」cmd 的參數「LicenseType」以啟用 AHUB 功能</span><span class="sxs-lookup"><span data-stu-id="bc0e4-371">Add parameter "LicenseType" for "Set-AzureRmDataFactoryV2IntegrationRuntime" cmd to enable AHUB functionality</span></span>

#### <a name="azurermdatalakeanalytics"></a><span data-ttu-id="bc0e4-372">AzureRM.DataLakeAnalytics</span><span class="sxs-lookup"><span data-stu-id="bc0e4-372">AzureRM.DataLakeAnalytics</span></span>
* <span data-ttu-id="bc0e4-373">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-373">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="bc0e4-374">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-374">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>
* <span data-ttu-id="bc0e4-375">針對 AzureRmDataLakeAnalyticsAccount 和 Set-AzureRmDataLakeAnalyticsAccount，已淘汰 -Tags 並改用 -Tag</span><span class="sxs-lookup"><span data-stu-id="bc0e4-375">Obsoleted -Tags in favor of -Tag for New-AzureRmDataLakeAnalyticsAccount and Set-AzureRmDataLakeAnalyticsAccount</span></span>

#### <a name="azurermdatalakestore"></a><span data-ttu-id="bc0e4-376">AzureRM.DataLakeStore</span><span class="sxs-lookup"><span data-stu-id="bc0e4-376">AzureRM.DataLakeStore</span></span>
* <span data-ttu-id="bc0e4-377">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-377">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="bc0e4-378">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-378">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>
* <span data-ttu-id="bc0e4-379">針對 New-AzureRmDataLakeStoreAccount 和 Set-AzureRmDataLakeStoreAccount，已淘汰 -Tags 並改用 -Tag</span><span class="sxs-lookup"><span data-stu-id="bc0e4-379">Obsoleted -Tags in favor of -Tag for New-AzureRmDataLakeStoreAccount and Set-AzureRmDataLakeStoreAccount</span></span>

#### <a name="azurermdevtestlabs"></a><span data-ttu-id="bc0e4-380">AzureRM.DevTestLabs</span><span class="sxs-lookup"><span data-stu-id="bc0e4-380">AzureRM.DevTestLabs</span></span>
* <span data-ttu-id="bc0e4-381">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-381">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermdns"></a><span data-ttu-id="bc0e4-382">AzureRM.Dns</span><span class="sxs-lookup"><span data-stu-id="bc0e4-382">AzureRM.Dns</span></span>
* <span data-ttu-id="bc0e4-383">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-383">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermeventgrid"></a><span data-ttu-id="bc0e4-384">AzureRM.EventGrid</span><span class="sxs-lookup"><span data-stu-id="bc0e4-384">AzureRM.EventGrid</span></span>
* <span data-ttu-id="bc0e4-385">已新增下列的新 Cmdlet：</span><span class="sxs-lookup"><span data-stu-id="bc0e4-385">Added the following new cmdlet:</span></span>
  - <span data-ttu-id="bc0e4-386">Update-AzureRmEventGridSubscription</span><span class="sxs-lookup"><span data-stu-id="bc0e4-386">Update-AzureRmEventGridSubscription</span></span>
    - <span data-ttu-id="bc0e4-387">更新 Event Grid 事件訂閱的屬性。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-387">Update the properties of an Event Grid event subscription.</span></span>
* <span data-ttu-id="bc0e4-388">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-388">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="bc0e4-389">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-389">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermeventhub"></a><span data-ttu-id="bc0e4-390">AzureRM.EventHub</span><span class="sxs-lookup"><span data-stu-id="bc0e4-390">AzureRM.EventHub</span></span>
* <span data-ttu-id="bc0e4-391">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-391">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="bc0e4-392">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-392">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermhdinsight"></a><span data-ttu-id="bc0e4-393">AzureRM.HDInsight</span><span class="sxs-lookup"><span data-stu-id="bc0e4-393">AzureRM.HDInsight</span></span>
* <span data-ttu-id="bc0e4-394">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-394">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="bc0e4-395">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-395">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurerminsights"></a><span data-ttu-id="bc0e4-396">AzureRM.Insights</span><span class="sxs-lookup"><span data-stu-id="bc0e4-396">AzureRM.Insights</span></span>
* <span data-ttu-id="bc0e4-397">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-397">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="bc0e4-398">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-398">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermiothub"></a><span data-ttu-id="bc0e4-399">AzureRM.IotHub</span><span class="sxs-lookup"><span data-stu-id="bc0e4-399">AzureRM.IotHub</span></span>
* <span data-ttu-id="bc0e4-400">新增 IoTHub Cmdlet 的憑證支援</span><span class="sxs-lookup"><span data-stu-id="bc0e4-400">Add Certificate support for IoTHub cmdlets</span></span>
* <span data-ttu-id="bc0e4-401">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-401">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="bc0e4-402">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-402">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermkeyvault"></a><span data-ttu-id="bc0e4-403">AzureRM.KeyVault</span><span class="sxs-lookup"><span data-stu-id="bc0e4-403">AzureRM.KeyVault</span></span>
* <span data-ttu-id="bc0e4-404">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-404">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="bc0e4-405">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-405">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>
* <span data-ttu-id="bc0e4-406">已針對長時間執行的 KeyVault Cmdlet 新增 -AsJob 支援。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-406">Added -AsJob support for long-running KeyVault cmdlets.</span></span> <span data-ttu-id="bc0e4-407">允許選取的 Cmdlet 在背景中執行，並傳回作業以追蹤及控制進度。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-407">Allows selected cmdlets to run in the background and return a job to track and control progress.</span></span>
  * <span data-ttu-id="bc0e4-408">受影響的 Cmdlet 是：Remove-AzureRmKeyVault</span><span class="sxs-lookup"><span data-stu-id="bc0e4-408">Affected cmdlet is: Remove-AzureRmKeyVault</span></span>
* <span data-ttu-id="bc0e4-409">修正了 Set-AzureRmKeyVaultAccessPolicy 中，AAD 篩選器會將 SPN 設為提供的 UPN 而非設定 UPN 本身的錯誤</span><span class="sxs-lookup"><span data-stu-id="bc0e4-409">Fixed bug in Set-AzureRmKeyVaultAccessPolicy where the AAD filter was setting SPN to the provided UPN, rather than setting the UPN</span></span>
  - <span data-ttu-id="bc0e4-410">請參閱下列問題以取得更多資訊：https://github.com/Azure/azure-powershell/issues/5201</span><span class="sxs-lookup"><span data-stu-id="bc0e4-410">See the following issue for more information: https://github.com/Azure/azure-powershell/issues/5201</span></span>

#### <a name="azurermlogicapp"></a><span data-ttu-id="bc0e4-411">AzureRM.LogicApp</span><span class="sxs-lookup"><span data-stu-id="bc0e4-411">AzureRM.LogicApp</span></span>
* <span data-ttu-id="bc0e4-412">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-412">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="bc0e4-413">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-413">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermmachinelearning"></a><span data-ttu-id="bc0e4-414">AzureRM.MachineLearning</span><span class="sxs-lookup"><span data-stu-id="bc0e4-414">AzureRM.MachineLearning</span></span>
* <span data-ttu-id="bc0e4-415">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-415">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="bc0e4-416">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-416">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>
* <span data-ttu-id="bc0e4-417">針對 Update-AzureRmMlCommitmentPlan，已淘汰 -Tags 並改用 -Tag</span><span class="sxs-lookup"><span data-stu-id="bc0e4-417">Obsoleted -Tags in favor of -Tag for Update-AzureRmMlCommitmentPlan</span></span>

#### <a name="azurermmachinelearningcompute"></a><span data-ttu-id="bc0e4-418">AzureRM.MachineLearningCompute</span><span class="sxs-lookup"><span data-stu-id="bc0e4-418">AzureRM.MachineLearningCompute</span></span>
* <span data-ttu-id="bc0e4-419">將 IncludeAllResources 參數新增到 Remove-AzureRmMlOpCluster Cmdlet</span><span class="sxs-lookup"><span data-stu-id="bc0e4-419">Add IncludeAllResources parameter to Remove-AzureRmMlOpCluster cmdlet</span></span>
  - <span data-ttu-id="bc0e4-420">使用此切換參數，將移除原本與叢集一起建立的所有資源</span><span class="sxs-lookup"><span data-stu-id="bc0e4-420">Using this switch parameter will remove all resources that were created with the cluster originally</span></span>
* <span data-ttu-id="bc0e4-421">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-421">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="bc0e4-422">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-422">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermmedia"></a><span data-ttu-id="bc0e4-423">AzureRM.Media</span><span class="sxs-lookup"><span data-stu-id="bc0e4-423">AzureRM.Media</span></span>
* <span data-ttu-id="bc0e4-424">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-424">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="bc0e4-425">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-425">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>
* <span data-ttu-id="bc0e4-426">針對 Set-AzureRmMediaService 和 New-AzureRmMediaService，已淘汰 -Tags 並改用 -Tag</span><span class="sxs-lookup"><span data-stu-id="bc0e4-426">Obsoleted -Tags in favor of -Tag for Set-AzureRmMediaService and New-AzureRmMediaService</span></span>

#### <a name="azurermnetwork"></a><span data-ttu-id="bc0e4-427">AzureRM.Network</span><span class="sxs-lookup"><span data-stu-id="bc0e4-427">AzureRM.Network</span></span>
* <span data-ttu-id="bc0e4-428">已針對長時間執行的 Network Cmdlet 新增 -AsJob 支援。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-428">Added -AsJob support for long-running Network cmdlets.</span></span> <span data-ttu-id="bc0e4-429">允許選取的 Cmdlet 在背景中執行，並傳回作業以追蹤及控制進度。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-429">Allows selected cmdlets to run in the background and return a job to track and control progress.</span></span>
* <span data-ttu-id="bc0e4-430">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-430">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="bc0e4-431">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-431">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermnotificationhubs"></a><span data-ttu-id="bc0e4-432">AzureRM.NotificationHubs</span><span class="sxs-lookup"><span data-stu-id="bc0e4-432">AzureRM.NotificationHubs</span></span>
* <span data-ttu-id="bc0e4-433">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-433">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="bc0e4-434">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-434">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>
* <span data-ttu-id="bc0e4-435">針對 New-AzureRmNotificationHubsNamespace 和 Set-AzureRmNotificationHubsNamespace，已淘汰 -Tags 並改用 -Tag</span><span class="sxs-lookup"><span data-stu-id="bc0e4-435">Obsoleted -Tags in favor of -Tag for New-AzureRmNotificationHubsNamespace and Set-AzureRmNotificationHubsNamespace</span></span>

#### <a name="azurermoperationalinsights"></a><span data-ttu-id="bc0e4-436">AzureRM.OperationalInsights</span><span class="sxs-lookup"><span data-stu-id="bc0e4-436">AzureRM.OperationalInsights</span></span>
* <span data-ttu-id="bc0e4-437">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-437">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="bc0e4-438">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-438">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>
* <span data-ttu-id="bc0e4-439">針對 New-AzureRmOperationalInsightsSavedSearch、Set-AzureRmOperationalInsightsSavedSearch、New-AzureRmOperationalInsightsWorkspace 和 Set-AzureRmOperationalInsightsWorkspace，已淘汰 -Tags 並改用 -Tag</span><span class="sxs-lookup"><span data-stu-id="bc0e4-439">Obsoleted -Tags in favor of -Tag for New-AzureRmOperationalInsightsSavedSearch, Set-AzureRmOperationalInsightsSavedSearch, New-AzureRmOperationalInsightsWorkspace, and Set-AzureRmOperationalInsightsWorkspace</span></span>

#### <a name="azurermpowerbiembedded"></a><span data-ttu-id="bc0e4-440">AzureRM.PowerBIEmbedded</span><span class="sxs-lookup"><span data-stu-id="bc0e4-440">AzureRM.PowerBIEmbedded</span></span>
* <span data-ttu-id="bc0e4-441">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-441">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="bc0e4-442">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-442">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermrecoveryservices"></a><span data-ttu-id="bc0e4-443">AzureRM.RecoveryServices</span><span class="sxs-lookup"><span data-stu-id="bc0e4-443">AzureRM.RecoveryServices</span></span>
* <span data-ttu-id="bc0e4-444">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-444">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="bc0e4-445">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-445">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermrecoveryservicesbackup"></a><span data-ttu-id="bc0e4-446">AzureRM.RecoveryServices.Backup</span><span class="sxs-lookup"><span data-stu-id="bc0e4-446">AzureRM.RecoveryServices.Backup</span></span>
* <span data-ttu-id="bc0e4-447">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-447">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>
* <span data-ttu-id="bc0e4-448">已將 -UseOriginalStorageAccount 選項新增到 Restore-AzureRmRecoveryServicesBackupItem Cmdlet。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-448">Added -UseOriginalStorageAccount option to the Restore-AzureRmRecoveryServicesBackupItem cmdlet.</span></span>
  - <span data-ttu-id="bc0e4-449">啟用此旗標會將磁碟還原到原始的儲存體帳戶，這可讓使用者將所還原虛擬機器的設定，盡可能重設回原始虛擬機器的設定。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-449">Enabling this flag results in restoring disks to their original storage accounts which allows users to maintain the configuration of restored VM as close to the original VMs as possible.</span></span>
  - <span data-ttu-id="bc0e4-450">這也有助於改善還原作業的效能。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-450">It also helps in improving the performance of the restore operation.</span></span>

#### <a name="azurermrediscache"></a><span data-ttu-id="bc0e4-451">AzureRM.RedisCache</span><span class="sxs-lookup"><span data-stu-id="bc0e4-451">AzureRM.RedisCache</span></span>
* <span data-ttu-id="bc0e4-452">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-452">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="bc0e4-453">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-453">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>
* <span data-ttu-id="bc0e4-454">已新增 3 個防火牆規則的新 Cmdlet</span><span class="sxs-lookup"><span data-stu-id="bc0e4-454">Added  3 new cmdlets for firewall rules</span></span>
* <span data-ttu-id="bc0e4-455">已新增 3 個異地複寫的新 Cmdlet</span><span class="sxs-lookup"><span data-stu-id="bc0e4-455">Added  3 new cmdlets for geo replication</span></span>
* <span data-ttu-id="bc0e4-456">已新增區域和標籤的支援</span><span class="sxs-lookup"><span data-stu-id="bc0e4-456">Added support for zones and tags</span></span>
* <span data-ttu-id="bc0e4-457">盡可能將 ResourceGroup 設為選用。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-457">Make ResourceGroup as optional whenever possible.</span></span>

#### <a name="azurermrelay"></a><span data-ttu-id="bc0e4-458">AzureRM.Relay</span><span class="sxs-lookup"><span data-stu-id="bc0e4-458">AzureRM.Relay</span></span>
* <span data-ttu-id="bc0e4-459">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-459">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="bc0e4-460">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-460">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermresources"></a><span data-ttu-id="bc0e4-461">AzureRM.Resources</span><span class="sxs-lookup"><span data-stu-id="bc0e4-461">AzureRM.Resources</span></span>
* <span data-ttu-id="bc0e4-462">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-462">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="bc0e4-463">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-463">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>
* <span data-ttu-id="bc0e4-464">已針對長時間執行的 Resources Cmdlet 新增 -AsJob 支援。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-464">Added -AsJob support for long-running Resources cmdlets.</span></span> <span data-ttu-id="bc0e4-465">允許選取的 Cmdlet 在背景中執行，並傳回作業以追蹤及控制進度。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-465">Allows selected cmdlets to run in the background and return a job to track and control progress.</span></span>
* <span data-ttu-id="bc0e4-466">已從 Get-AzureRmProviderOperation 新增別名到 Get-AzureRmResourceProviderAction 以符合命名慣例</span><span class="sxs-lookup"><span data-stu-id="bc0e4-466">Added alias from Get-AzureRmProviderOperation to Get-AzureRmResourceProviderAction to conform with naming conventions</span></span>

#### <a name="azurermscheduler"></a><span data-ttu-id="bc0e4-467">AzureRM.Scheduler</span><span class="sxs-lookup"><span data-stu-id="bc0e4-467">AzureRM.Scheduler</span></span>
* <span data-ttu-id="bc0e4-468">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-468">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="bc0e4-469">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-469">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermservermanagement"></a><span data-ttu-id="bc0e4-470">AzureRM.ServerManagement</span><span class="sxs-lookup"><span data-stu-id="bc0e4-470">AzureRM.ServerManagement</span></span>
* <span data-ttu-id="bc0e4-471">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-471">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="bc0e4-472">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-472">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>
* <span data-ttu-id="bc0e4-473">針對 New-AzureRmServerManagementNode 和 New-AzureRmServerManagementGateway，已淘汰 -Tags 並改用 -Tag</span><span class="sxs-lookup"><span data-stu-id="bc0e4-473">Obsoleted -Tags in favor of -Tag for New-AzureRmServerManagementNode and New-AzureRmServerManagementGateway</span></span>

#### <a name="azurermservicebus"></a><span data-ttu-id="bc0e4-474">AzureRM.ServiceBus</span><span class="sxs-lookup"><span data-stu-id="bc0e4-474">AzureRM.ServiceBus</span></span>
* <span data-ttu-id="bc0e4-475">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-475">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="bc0e4-476">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-476">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermservicefabric"></a><span data-ttu-id="bc0e4-477">AzureRM.ServiceFabric</span><span class="sxs-lookup"><span data-stu-id="bc0e4-477">AzureRM.ServiceFabric</span></span>
* <span data-ttu-id="bc0e4-478">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-478">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="bc0e4-479">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-479">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermsiterecovery"></a><span data-ttu-id="bc0e4-480">AzureRM.SiteRecovery</span><span class="sxs-lookup"><span data-stu-id="bc0e4-480">AzureRM.SiteRecovery</span></span>
* <span data-ttu-id="bc0e4-481">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-481">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="bc0e4-482">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-482">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermsql"></a><span data-ttu-id="bc0e4-483">AzureRM.Sql</span><span class="sxs-lookup"><span data-stu-id="bc0e4-483">AzureRM.Sql</span></span>
* <span data-ttu-id="bc0e4-484">更新 Auditing 命令參數描述</span><span class="sxs-lookup"><span data-stu-id="bc0e4-484">Update the Auditing commands parameters description</span></span>
* <span data-ttu-id="bc0e4-485">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-485">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="bc0e4-486">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-486">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>
* <span data-ttu-id="bc0e4-487">已將 -AsJob 參數新增到長時間執行的 Cmdlet</span><span class="sxs-lookup"><span data-stu-id="bc0e4-487">Added -AsJob parameter to long running cmdlets</span></span>
* <span data-ttu-id="bc0e4-488">已從 Get-AzureRmSqlServiceObjective 中淘汰了 -DatabaseName 參數</span><span class="sxs-lookup"><span data-stu-id="bc0e4-488">Obsoleted -DatabaseName parameter from Get-AzureRmSqlServiceObjective</span></span>

#### <a name="azurermstorage"></a><span data-ttu-id="bc0e4-489">AzureRM.Storage</span><span class="sxs-lookup"><span data-stu-id="bc0e4-489">AzureRM.Storage</span></span>
* <span data-ttu-id="bc0e4-490">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-490">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="bc0e4-491">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-491">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>
* <span data-ttu-id="bc0e4-492">修正了以參數 -EnableEncryptionService None 執行 Cmdlet New-AzureRMStorageAccount 時，所發生的 null 參考問題</span><span class="sxs-lookup"><span data-stu-id="bc0e4-492">Fix a null reference issue of run cmdlet New-AzureRMStorageAccount with parameter -EnableEncryptionService None</span></span>
* <span data-ttu-id="bc0e4-493">已針對長時間執行的 Storage Cmdlet 新增 -AsJob 支援。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-493">Added -AsJob support for long-running Storage cmdlets.</span></span> <span data-ttu-id="bc0e4-494">允許選取的 Cmdlet 在背景中執行，並傳回作業以追蹤及控制進度。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-494">Allows selected cmdlets to run in the background and return a job to track and control progress.</span></span>
    - <span data-ttu-id="bc0e4-495">受影響的 Cmdlet 是適用於儲存體帳戶和儲存體帳戶網路規則的 New-、Remove-、Add- 和 Update-。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-495">Affected cmdlets are New-, Remove-, Add-, and Update- for Storage Account and Storage Account Network Rule.</span></span>

#### <a name="azurermstreamanalytics"></a><span data-ttu-id="bc0e4-496">AzureRM.StreamAnalytics</span><span class="sxs-lookup"><span data-stu-id="bc0e4-496">AzureRM.StreamAnalytics</span></span>
* <span data-ttu-id="bc0e4-497">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-497">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="bc0e4-498">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-498">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermtrafficmanager"></a><span data-ttu-id="bc0e4-499">AzureRM.TrafficManager</span><span class="sxs-lookup"><span data-stu-id="bc0e4-499">AzureRM.TrafficManager</span></span>
* <span data-ttu-id="bc0e4-500">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-500">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="bc0e4-501">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-501">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>

#### <a name="azurermwebsites"></a><span data-ttu-id="bc0e4-502">AzureRM.Websites</span><span class="sxs-lookup"><span data-stu-id="bc0e4-502">AzureRM.Websites</span></span>
* <span data-ttu-id="bc0e4-503">已將 Location 完成碼新增到 -Location 參數中，以便透過有效的位置來實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-503">Added Location Completer to -Location parameters allowing tab completion through valid Locations</span></span>
* <span data-ttu-id="bc0e4-504">已將 ResourceGroup 完成碼新增到 -ResourceGroup 參數中，以便在目前的訂用帳戶中透過資源群組實現 Tab 鍵自動完成</span><span class="sxs-lookup"><span data-stu-id="bc0e4-504">Added ResourceGroup Completer to -ResourceGroup parameters allowing tab completion through resource groups in current subscription</span></span>
* <span data-ttu-id="bc0e4-505">已針對長時間執行的 Websites Cmdlet 新增 -AsJob 支援。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-505">Added -AsJob support for long-running Websites cmdlets.</span></span> <span data-ttu-id="bc0e4-506">允許選取的 Cmdlet 在背景中執行，並傳回作業以追蹤及控制進度。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-506">Allows selected cmdlets to run in the background and return a job to track and control progress.</span></span>
     - <span data-ttu-id="bc0e4-507">WebApps、AppServicePlan 和 Slots中，受影響的 Cmdlet 是 New-、Remove-、Add- 和 Set-</span><span class="sxs-lookup"><span data-stu-id="bc0e4-507">Affected cmdlets are New-, Remove-, Add-, and Set- for WebApps, AppServicePlan and Slots</span></span>

## <a name="2017128-version-511"></a><span data-ttu-id="bc0e4-508">2017.12.8 版本 5.1.1</span><span class="sxs-lookup"><span data-stu-id="bc0e4-508">2017.12.8 Version 5.1.1</span></span>
* <span data-ttu-id="bc0e4-509">AnalysisServices</span><span class="sxs-lookup"><span data-stu-id="bc0e4-509">AnalysisServices</span></span>
  - <span data-ttu-id="bc0e4-510">將位置的驗證集變更為動態對應，以便支援所有雲端。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-510">Change validate set of location to dynamic lookup so that all clouds are supported.</span></span>
* <span data-ttu-id="bc0e4-511">自動化</span><span class="sxs-lookup"><span data-stu-id="bc0e4-511">Automation</span></span>
  - <span data-ttu-id="bc0e4-512">更新至 Import-AzureRMAutomationRunbook</span><span class="sxs-lookup"><span data-stu-id="bc0e4-512">Update to Import-AzureRMAutomationRunbook</span></span>
    - <span data-ttu-id="bc0e4-513">現在可支援 Python2 Runbook</span><span class="sxs-lookup"><span data-stu-id="bc0e4-513">Support is now being provided for Python2 runbooks</span></span>
* <span data-ttu-id="bc0e4-514">Batch</span><span class="sxs-lookup"><span data-stu-id="bc0e4-514">Batch</span></span>
  - <span data-ttu-id="bc0e4-515">修正錯誤：不含資源群組的帳戶作業無法自動偵測資源群組</span><span class="sxs-lookup"><span data-stu-id="bc0e4-515">Fixed a bug where account operations without a resource group failed to auto-detect the resource group</span></span>
* <span data-ttu-id="bc0e4-516">計算</span><span class="sxs-lookup"><span data-stu-id="bc0e4-516">Compute</span></span>
  - <span data-ttu-id="bc0e4-517">Get-AzureRmComputeResourceSku 會顯示區域資訊。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-517">Get-AzureRmComputeResourceSku shows zone information.</span></span>
  - <span data-ttu-id="bc0e4-518">更新 Disable-AzureRmVmssDiskEncryption 以修正問題 https://github.com/Azure/azure-powershell/issues/5038</span><span class="sxs-lookup"><span data-stu-id="bc0e4-518">Update Disable-AzureRmVmssDiskEncryption to fix issue https://github.com/Azure/azure-powershell/issues/5038</span></span>
  - <span data-ttu-id="bc0e4-519">針對長時間執行的計算 Cmdlet 新增 -AsJob 支援。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-519">Added -AsJob support for long-running Compute cmdlets.</span></span> <span data-ttu-id="bc0e4-520">允許選取的 Cmdlet 在背景中執行，並傳回作業以追蹤及控制進度。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-520">Allows selected cmdlets to run in the background and return a job to track and control progress.</span></span>
    - <span data-ttu-id="bc0e4-521">受影響的 Cmdlet 包括：適用於虛擬機器和虛擬機器擴展集的 New-、Update-、Set-、Remove-、Start-、Restart- 和 Stop- Cmdlet</span><span class="sxs-lookup"><span data-stu-id="bc0e4-521">Affected cmdlets include: New-, Update-, Set-, Remove-, Start-, Restart-, Stop- cmdlets for Virtual Machines and Virtual Machine Scale Sets</span></span>
    - <span data-ttu-id="bc0e4-522">將簡化的參數集新增至 New-AzureRmVM，New-AzureRmVM 可使用智慧型預設值建立虛擬機器和所有必要的資源</span><span class="sxs-lookup"><span data-stu-id="bc0e4-522">Added simplified parameter set to New-AzureRmVM, which creates a Virtual Machine and all required resources using smart defaults</span></span>
* <span data-ttu-id="bc0e4-523">ContainerInstance</span><span class="sxs-lookup"><span data-stu-id="bc0e4-523">ContainerInstance</span></span>
  - <span data-ttu-id="bc0e4-524">套用 Azure 容器執行個體 SDK 2017-10-01</span><span class="sxs-lookup"><span data-stu-id="bc0e4-524">Apply Azure Container Instance SDK 2017-10-01</span></span>
    - <span data-ttu-id="bc0e4-525">支援容器的「執行到完成」作業</span><span class="sxs-lookup"><span data-stu-id="bc0e4-525">Support container run-to-completion</span></span>
    - <span data-ttu-id="bc0e4-526">支援 Azure 檔案磁碟區掛接</span><span class="sxs-lookup"><span data-stu-id="bc0e4-526">Support Azure File volume mount</span></span>
    - <span data-ttu-id="bc0e4-527">支援開啟多個公用 IP 的連接埠</span><span class="sxs-lookup"><span data-stu-id="bc0e4-527">Support opening multiple ports for public IP</span></span>
* <span data-ttu-id="bc0e4-528">ContainerRegistry</span><span class="sxs-lookup"><span data-stu-id="bc0e4-528">ContainerRegistry</span></span>
  - <span data-ttu-id="bc0e4-529">新增異地複寫與 Webhook 的 Cmdlet</span><span class="sxs-lookup"><span data-stu-id="bc0e4-529">New cmdlets for geo-replication and webhooks</span></span>
    - <span data-ttu-id="bc0e4-530">Get/New/Remove-AzureRmContainerRegistryReplication</span><span class="sxs-lookup"><span data-stu-id="bc0e4-530">Get/New/Remove-AzureRmContainerRegistryReplication</span></span>
    - <span data-ttu-id="bc0e4-531">Get/New/Remove/Test/Update-AzureRmContainerRegistryWebhook</span><span class="sxs-lookup"><span data-stu-id="bc0e4-531">Get/New/Remove/Test/Update-AzureRmContainerRegistryWebhook</span></span>
* <span data-ttu-id="bc0e4-532">DataFactories</span><span class="sxs-lookup"><span data-stu-id="bc0e4-532">DataFactories</span></span>
    - <span data-ttu-id="bc0e4-533">認證加密功能現在可與啟用的「遠端存取」(透過網路) 和停用的「遠端存取」(本機電腦) 搭配使用。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-533">Credential encryption functionality now works with both "Remote Access" enabled (Over Network) and "Remote Access" disabled (Local Machine).</span></span>
* <span data-ttu-id="bc0e4-534">DataFactoryV2</span><span class="sxs-lookup"><span data-stu-id="bc0e4-534">DataFactoryV2</span></span>
  - <span data-ttu-id="bc0e4-535">新增兩個 Cmdlet：Update-AzureRmDataFactoryV2 和 Stop-AzureRmDataFactoryV2PipelineRun</span><span class="sxs-lookup"><span data-stu-id="bc0e4-535">Added two new cmdlets: Update-AzureRmDataFactoryV2 and Stop-AzureRmDataFactoryV2PipelineRun</span></span>
* <span data-ttu-id="bc0e4-536">DataLakeAnalytics</span><span class="sxs-lookup"><span data-stu-id="bc0e4-536">DataLakeAnalytics</span></span>
  - <span data-ttu-id="bc0e4-537">將名為 ScriptParameter 的參數新增至 Submit-AzureRmDataLakeAnalyticsJob</span><span class="sxs-lookup"><span data-stu-id="bc0e4-537">Added a parameter called ScriptParameter to Submit-AzureRmDataLakeAnalyticsJob</span></span>
    - <span data-ttu-id="bc0e4-538">可在 Submit-AzureRmDataLakeAnalyticsJob 上使用 Get-help 找到 ScriptParameter 的詳細資訊</span><span class="sxs-lookup"><span data-stu-id="bc0e4-538">Detailed information about ScriptParameter can be found using Get-Help on Submit-AzureRmDataLakeAnalyticsJob</span></span>
  - <span data-ttu-id="bc0e4-539">針對 New-AzureRmDataLakeAnalyticsAccount，已將參數 MaxDegreeOfParallelism 變更為 MaxAnalyticsUnits</span><span class="sxs-lookup"><span data-stu-id="bc0e4-539">For New-AzureRmDataLakeAnalyticsAccount, changed the parameter MaxDegreeOfParallelism to MaxAnalyticsUnits</span></span>
    - <span data-ttu-id="bc0e4-540">新增參數 MaxAnalyticsUnits 的別名：MaxDegreeOfParallelism</span><span class="sxs-lookup"><span data-stu-id="bc0e4-540">Added an alias for the parameter MaxAnalyticsUnits: MaxDegreeOfParallelism</span></span>
  - <span data-ttu-id="bc0e4-541">針對 New-AzureRmDataLakeAnalyticsComputePolicy，已將參數 MaxDegreeOfParallelismPerJob 變更為 MaxAnalyticsUnitsPerJob</span><span class="sxs-lookup"><span data-stu-id="bc0e4-541">For New-AzureRmDataLakeAnalyticsComputePolicy, changed the parameter MaxDegreeOfParallelismPerJob to MaxAnalyticsUnitsPerJob</span></span>
    - <span data-ttu-id="bc0e4-542">新增參數 MaxAnalyticsUnitsPerJob 的別名：MaxDegreeOfParallelismPerJob</span><span class="sxs-lookup"><span data-stu-id="bc0e4-542">Added an alias for the parameter MaxAnalyticsUnitsPerJob: MaxDegreeOfParallelismPerJob</span></span>
  - <span data-ttu-id="bc0e4-543">針對 Set-AzureRmDataLakeAnalyticsAccount，已將參數 MaxDegreeOfParallelism 變更為 MaxAnalyticsUnits</span><span class="sxs-lookup"><span data-stu-id="bc0e4-543">For Set-AzureRmDataLakeAnalyticsAccount, changed the parameter MaxDegreeOfParallelism to MaxAnalyticsUnits</span></span>
    - <span data-ttu-id="bc0e4-544">新增參數 MaxAnalyticsUnits 的別名：MaxDegreeOfParallelism</span><span class="sxs-lookup"><span data-stu-id="bc0e4-544">Added an alias for the parameter MaxAnalyticsUnits: MaxDegreeOfParallelism</span></span>
  - <span data-ttu-id="bc0e4-545">針對 Submit-AzureRmDataLakeAnalyticsJob，已將參數 DegreeOfParallelism 變更為 AnalyticsUnits</span><span class="sxs-lookup"><span data-stu-id="bc0e4-545">For Submit-AzureRmDataLakeAnalyticsJob, changed the parameter DegreeOfParallelism to AnalyticsUnits</span></span>
    - <span data-ttu-id="bc0e4-546">新增參數 AnalyticsUnits 的別名：DegreeOfParallelism</span><span class="sxs-lookup"><span data-stu-id="bc0e4-546">Added an alias for the parameter AnalyticsUnits: DegreeOfParallelism</span></span>
  - <span data-ttu-id="bc0e4-547">針對 Update-AzureRmDataLakeAnalyticsComputePolicy，已將參數 MaxDegreeOfParallelismPerJob 變更為 MaxAnalyticsUnitsPerJob</span><span class="sxs-lookup"><span data-stu-id="bc0e4-547">For Update-AzureRmDataLakeAnalyticsComputePolicy, changed the parameter MaxDegreeOfParallelismPerJob to MaxAnalyticsUnitsPerJob</span></span>
    - <span data-ttu-id="bc0e4-548">新增參數 MaxAnalyticsUnitsPerJob 的別名：MaxDegreeOfParallelismPerJob</span><span class="sxs-lookup"><span data-stu-id="bc0e4-548">Added an alias for the parameter MaxAnalyticsUnitsPerJob: MaxDegreeOfParallelismPerJob</span></span>
* <span data-ttu-id="bc0e4-549">MachineLearningCompute</span><span class="sxs-lookup"><span data-stu-id="bc0e4-549">MachineLearningCompute</span></span>
  - <span data-ttu-id="bc0e4-550">新增 Set-AzureRmMlOpCluster</span><span class="sxs-lookup"><span data-stu-id="bc0e4-550">Add Set-AzureRmMlOpCluster</span></span>
    - <span data-ttu-id="bc0e4-551">更新叢集的代理程式計數或 SSL 設定</span><span class="sxs-lookup"><span data-stu-id="bc0e4-551">Update a cluster's agent count or SSL configuration</span></span>
  - <span data-ttu-id="bc0e4-552">協調器屬性是選擇性項目</span><span class="sxs-lookup"><span data-stu-id="bc0e4-552">Orchestrator properties are optional</span></span>
    - <span data-ttu-id="bc0e4-553">服務會建立服務主體 (如果未提供的話)，因此協調器屬性現在是選擇性項目</span><span class="sxs-lookup"><span data-stu-id="bc0e4-553">The service will create a service principal if not provided, so the orchestrator properties are now optional</span></span>
* <span data-ttu-id="bc0e4-554">PowerBIEmbedded</span><span class="sxs-lookup"><span data-stu-id="bc0e4-554">PowerBIEmbedded</span></span>
  - <span data-ttu-id="bc0e4-555">新增 Power BI Embedded 容量 Cmdlet 的支援</span><span class="sxs-lookup"><span data-stu-id="bc0e4-555">Add support for Power BI Embedded Capacity cmdlets</span></span>
  - <span data-ttu-id="bc0e4-556">新增 Get-AzureRmPowerBIEmbeddedCapacity Cmdlet - 取得 PowerBI Embedded 容量的詳細資料。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-556">New Cmdlet Get-AzureRmPowerBIEmbeddedCapacity - Gets the details of a PowerBI Embedded Capacity.</span></span>
  - <span data-ttu-id="bc0e4-557">新增 New-AzureRmPowerBIEmbeddedCapacity Cmdlet - 建立新的 PowerBI Embedded 容量</span><span class="sxs-lookup"><span data-stu-id="bc0e4-557">New Cmdlet New-AzureRmPowerBIEmbeddedCapacity - Creates a new PowerBI Embedded Capacity</span></span>
  - <span data-ttu-id="bc0e4-558">新增 Remove-AzureRmPowerBIEmbeddedCapacity Cmdlet - 刪除 PowerBI Embedded 容量的執行個體</span><span class="sxs-lookup"><span data-stu-id="bc0e4-558">New Cmdlet Remove-AzureRmPowerBIEmbeddedCapacity - Deletes an instance of PowerBI Embedded Capacity</span></span>
  - <span data-ttu-id="bc0e4-559">新增 Resume-AzureRmPowerBIEmbeddedCapacity Cmdlet - 恢復 PowerBI Embedded 容量的執行個體</span><span class="sxs-lookup"><span data-stu-id="bc0e4-559">New Cmdlet Resume-AzureRmPowerBIEmbeddedCapacity - Resumes an instance of PowerBI Embedded Capacity</span></span>
  - <span data-ttu-id="bc0e4-560">新增 Suspend-AzureRmPowerBIEmbeddedCapacity Cmdlet - 暫止 PowerBI Embedded 容量的執行個體</span><span class="sxs-lookup"><span data-stu-id="bc0e4-560">New Cmdlet Suspend-AzureRmPowerBIEmbeddedCapacity - Suspends an instance of PowerBI Embedded Capacity</span></span>
  - <span data-ttu-id="bc0e4-561">新增 Test-AzureRmPowerBIEmbeddedCapacity Cmdlet - 測試 PowerBI Embedded 容量執行個體是否存在</span><span class="sxs-lookup"><span data-stu-id="bc0e4-561">New Cmdlet Test-AzureRmPowerBIEmbeddedCapacity - Tests the existence of an instance of PowerBI Embedded Capacity</span></span>
  - <span data-ttu-id="bc0e4-562">新增 Update-AzureRmPowerBIEmbeddedCapacity Cmdlet - 修改 PowerBI Embedded 容量的執行個體</span><span class="sxs-lookup"><span data-stu-id="bc0e4-562">New Cmdlet Update-AzureRmPowerBIEmbeddedCapacity - Modifies an instance of PowerBI Embedded Capacity</span></span>
* <span data-ttu-id="bc0e4-563">設定檔</span><span class="sxs-lookup"><span data-stu-id="bc0e4-563">Profile</span></span>
  - <span data-ttu-id="bc0e4-564">已將 USGovernmentActiveDirectoryEndpoint 更新為 https://login.microsoftonline.us/</span><span class="sxs-lookup"><span data-stu-id="bc0e4-564">Updated USGovernmentActiveDirectoryEndpoint to https://login.microsoftonline.us/</span></span>
    - <span data-ttu-id="bc0e4-565">如需更多關於 Azure Government 端點對應的資訊，請參閱以下文章：https://docs.microsoft.com/en-us/azure/azure-government/documentation-government-developer-guide#endpoint-mapping</span><span class="sxs-lookup"><span data-stu-id="bc0e4-565">For more information about the Azure Government endpoint mappings, please see the following: https://docs.microsoft.com/en-us/azure/azure-government/documentation-government-developer-guide#endpoint-mapping</span></span>
    - <span data-ttu-id="bc0e4-566">新增 Cmdlet 的 -AsJob 支援，讓選取的 Cmdlet 可在背景中執行並傳回作業以追蹤和控制進度</span><span class="sxs-lookup"><span data-stu-id="bc0e4-566">Added -AsJob support for cmdlets, enabling selected cmdlets to execute in the background and return a job to track and control progress</span></span>
    - <span data-ttu-id="bc0e4-567">將 -AsJob 參數新增至 Get-AzureRmSubscription Cmdlet</span><span class="sxs-lookup"><span data-stu-id="bc0e4-567">Added -AsJob parameter to Get-AzureRmSubscription cmdlet</span></span>
* <span data-ttu-id="bc0e4-568">RecoveryServices.Backup</span><span class="sxs-lookup"><span data-stu-id="bc0e4-568">RecoveryServices.Backup</span></span>
  - <span data-ttu-id="bc0e4-569">修正錯誤：Get-AzureRmRecoveryServicesBackupItem 應針對容器名稱的篩選，執行不區分大小寫的比較。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-569">Fixed bug - Get-AzureRmRecoveryServicesBackupItem should do case insensitive comparison for container name filter.</span></span>
  - <span data-ttu-id="bc0e4-570">修正錯誤：AzureVmItem 現在有屬性可顯示最後一次發生備份作業的時間 (LastBackupTime)。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-570">Fixed bug - AzureVmItem now has a property that shows the last time a backup operation has happened - LastBackupTime.</span></span>
* <span data-ttu-id="bc0e4-571">資源</span><span class="sxs-lookup"><span data-stu-id="bc0e4-571">Resources</span></span>
  - <span data-ttu-id="bc0e4-572">修正問題：Get-AzureRMRoleAssignment 產生的指派結果沒有自訂角色的角色定義名稱</span><span class="sxs-lookup"><span data-stu-id="bc0e4-572">Fixed issue where Get-AzureRMRoleAssignment would result in a assignments without roledefiniton name for custom roles</span></span>
    - <span data-ttu-id="bc0e4-573">使用者現在使用 Get-AzureRMRoleAssignment 產生的指派，會具有任何角色類型的角色定義名稱</span><span class="sxs-lookup"><span data-stu-id="bc0e4-573">Users can now use Get-AzureRMRoleAssignment with assignments having roledefinition names irrespective of the type of role</span></span>
  - <span data-ttu-id="bc0e4-574">修正問題：當可指派的範圍內有新範圍時，Set-AzureRMRoleRoleDefinition 會用來擲回找不到 RD 的錯誤</span><span class="sxs-lookup"><span data-stu-id="bc0e4-574">Fixed issue where Set-AzureRMRoleRoleDefinition used to throw RD not found error when there was a new scope in assignablescopes</span></span>
    - <span data-ttu-id="bc0e4-575">使用者現在能在可指派的範圍內有新範圍時，使用 Set-AzureRMRoleRoleDefinition，且不受限於範圍的位置</span><span class="sxs-lookup"><span data-stu-id="bc0e4-575">Users can now use Set-AzureRMRoleRoleDefinition with assignable scopes including new scopes irrespective of the position of the scope</span></span>
  - <span data-ttu-id="bc0e4-576">允許範圍以 "/" 結尾</span><span class="sxs-lookup"><span data-stu-id="bc0e4-576">Allow scopes to end with "/"</span></span>
    - <span data-ttu-id="bc0e4-577">使用者現在可以使用範圍結尾為 "/" 的 RoleDefinition 和 RoleAssignment Commandlet (與 API 和 CLI 一致)</span><span class="sxs-lookup"><span data-stu-id="bc0e4-577">Users can now use RoleDefinition and RoleAssignment commandlets with scopes ending with "/" ,consistent with API and CLI</span></span>
  - <span data-ttu-id="bc0e4-578">允許使用者使用委派旗標建立 RoleAssignment</span><span class="sxs-lookup"><span data-stu-id="bc0e4-578">Allow users to create RoleAssignment using delegation flag</span></span>
    - <span data-ttu-id="bc0e4-579">使用者現在可以使用具有新增委派旗標選項的 New-AzureRMRoleAssignment</span><span class="sxs-lookup"><span data-stu-id="bc0e4-579">Users can now use New-AzureRMRoleAssignment with an option of adding the delegation flag</span></span>
  - <span data-ttu-id="bc0e4-580">修正 RoleAssignment 以遵守範圍參數</span><span class="sxs-lookup"><span data-stu-id="bc0e4-580">Fix RoleAssignment get to respect the scope parameter</span></span>
  - <span data-ttu-id="bc0e4-581">在 New-AzureRmRoleAssignment Commandlet 中新增 ServicePrincipalName 的別名</span><span class="sxs-lookup"><span data-stu-id="bc0e4-581">Add an alias for ServicePrincipalName in the New-AzureRmRoleAssignment Commandlet</span></span>
    - <span data-ttu-id="bc0e4-582">使用者現在使用 New-AzureRmRoleAssignment Commandlet 時，可使用 ApplicationId 而不是 ServicePrincipalName</span><span class="sxs-lookup"><span data-stu-id="bc0e4-582">Users can now use the ApplicationId instead of the ServicePrincipalName when using the New-AzureRmRoleAssignment commandlet</span></span>
* <span data-ttu-id="bc0e4-583">SiteRecovery</span><span class="sxs-lookup"><span data-stu-id="bc0e4-583">SiteRecovery</span></span>
  - <span data-ttu-id="bc0e4-584">針對此模組中的所有 Cmdlet 新增取代警告，為下一次的重大變更發行做好準備。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-584">Add deprecation warnings for all cmdlets in this module in preparation for the next breaking change release.</span></span>
    - <span data-ttu-id="bc0e4-585">請參閱即將發行的重大變更指南，以了解如何從 AzureRM 移轉您的 Cmdlet。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-585">Please see the upcoming breaking changes guide for more information on how to migrate your cmdlets from AzureRM.</span></span>
* <span data-ttu-id="bc0e4-586">Sql</span><span class="sxs-lookup"><span data-stu-id="bc0e4-586">Sql</span></span>
  - <span data-ttu-id="bc0e4-587">新增使用 Set-AzureRmSqlDatabase 重新命名資料庫的功能</span><span class="sxs-lookup"><span data-stu-id="bc0e4-587">Added ability to rename database using Set-AzureRmSqlDatabase</span></span>
  - <span data-ttu-id="bc0e4-588">已修正的問題 https://github.com/Azure/azure-powershell/issues/4974</span><span class="sxs-lookup"><span data-stu-id="bc0e4-588">Fixed issue https://github.com/Azure/azure-powershell/issues/4974</span></span>
    - <span data-ttu-id="bc0e4-589">對稽核 Cmdlet 提供無效的 AUDIT_CHANGED_GROUP 值不會再擲回錯誤，並且將在近期版本中移除。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-589">Providing invalid AUDIT_CHANGED_GROUP value for auditing cmdlets no longer throws an error and will be removed in an upcoming release.</span></span>
  - <span data-ttu-id="bc0e4-590">已修正的問題 https://github.com/Azure/azure-powershell/issues/5046</span><span class="sxs-lookup"><span data-stu-id="bc0e4-590">Fixed issue https://github.com/Azure/azure-powershell/issues/5046</span></span>
    - <span data-ttu-id="bc0e4-591">稽核 Cmdlet 中的 AuditAction 參數不再遭到忽略</span><span class="sxs-lookup"><span data-stu-id="bc0e4-591">AuditAction parameter in auditing cmdlets is no longer being ignored</span></span>
  - <span data-ttu-id="bc0e4-592">修正在稽核 Cmdlet 中提供 'Secondary' StorageKeyType 時的問題</span><span class="sxs-lookup"><span data-stu-id="bc0e4-592">Fixed an issue in Auditing cmdlets when 'Secondary' StorageKeyType is provided</span></span>
    - <span data-ttu-id="bc0e4-593">在設定 Blob 稽核時，針對 StorageKeyType 參數提供 'Secondary' 值時，系統使用的不是次要金鑰，而是主要儲存體帳戶金鑰。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-593">When setting blob auditing, the primary storage account key was used instead of the secondary key when providing 'Secondary' value for StorageKeyType parameter.</span></span>
  - <span data-ttu-id="bc0e4-594">變更 Set-AzureRmSqlServerTransparentDataEncryptionProtector 中的確認訊息文字</span><span class="sxs-lookup"><span data-stu-id="bc0e4-594">Changing the wording for confirmation message from Set-AzureRmSqlServerTransparentDataEncryptionProtector</span></span>
* <span data-ttu-id="bc0e4-595">Azure (RDFE)</span><span class="sxs-lookup"><span data-stu-id="bc0e4-595">Azure (RDFE)</span></span>
    - <span data-ttu-id="bc0e4-596">移除所有 RemoteApp Cmdlet</span><span class="sxs-lookup"><span data-stu-id="bc0e4-596">Removed all RemoteApp Cmdles</span></span>
* <span data-ttu-id="bc0e4-597">Azure.Storage</span><span class="sxs-lookup"><span data-stu-id="bc0e4-597">Azure.Storage</span></span>
    - <span data-ttu-id="bc0e4-598">升級至 Azure 儲存體用戶端程式庫 8.6.0 及 Azure 儲存體資料移動程式庫 0.6.5</span><span class="sxs-lookup"><span data-stu-id="bc0e4-598">Upgrade to Azure Storage Client Library 8.6.0 and Azure Storage DataMovement Library 0.6.5</span></span>

## <a name="20171110-version-501"></a><span data-ttu-id="bc0e4-599">2017.11.10 版本 5.0.1</span><span class="sxs-lookup"><span data-stu-id="bc0e4-599">2017.11.10 Version 5.0.1</span></span>
* <span data-ttu-id="bc0e4-600">固定組件載入問題造成在下列模組中執行 Cmdlet 時失敗：</span><span class="sxs-lookup"><span data-stu-id="bc0e4-600">Fixed assembly loading issue that caused some cmdlets to fail when executing in the following modules:</span></span>
  - <span data-ttu-id="bc0e4-601">AzureRM.ApiManagement</span><span class="sxs-lookup"><span data-stu-id="bc0e4-601">AzureRM.ApiManagement</span></span>
  - <span data-ttu-id="bc0e4-602">AzureRM.Backup</span><span class="sxs-lookup"><span data-stu-id="bc0e4-602">AzureRM.Backup</span></span>
  - <span data-ttu-id="bc0e4-603">AzureRM.Batch</span><span class="sxs-lookup"><span data-stu-id="bc0e4-603">AzureRM.Batch</span></span>
  - <span data-ttu-id="bc0e4-604">AzureRM.Compute</span><span class="sxs-lookup"><span data-stu-id="bc0e4-604">AzureRM.Compute</span></span>
  - <span data-ttu-id="bc0e4-605">AzureRM.DataFactories</span><span class="sxs-lookup"><span data-stu-id="bc0e4-605">AzureRM.DataFactories</span></span>
  - <span data-ttu-id="bc0e4-606">AzureRM.HDInsight</span><span class="sxs-lookup"><span data-stu-id="bc0e4-606">AzureRM.HDInsight</span></span>
  - <span data-ttu-id="bc0e4-607">AzureRM.KeyVault</span><span class="sxs-lookup"><span data-stu-id="bc0e4-607">AzureRM.KeyVault</span></span>
  - <span data-ttu-id="bc0e4-608">AzureRM.RecoveryServices</span><span class="sxs-lookup"><span data-stu-id="bc0e4-608">AzureRM.RecoveryServices</span></span>
  - <span data-ttu-id="bc0e4-609">AzureRM.RecoveryServices.Backup</span><span class="sxs-lookup"><span data-stu-id="bc0e4-609">AzureRM.RecoveryServices.Backup</span></span>
  - <span data-ttu-id="bc0e4-610">AzureRM.RecoveryServices.SiteRecovery</span><span class="sxs-lookup"><span data-stu-id="bc0e4-610">AzureRM.RecoveryServices.SiteRecovery</span></span>
  - <span data-ttu-id="bc0e4-611">AzureRM.RedisCache</span><span class="sxs-lookup"><span data-stu-id="bc0e4-611">AzureRM.RedisCache</span></span>
  - <span data-ttu-id="bc0e4-612">AzureRM.SiteRecovery</span><span class="sxs-lookup"><span data-stu-id="bc0e4-612">AzureRM.SiteRecovery</span></span>
  - <span data-ttu-id="bc0e4-613">AzureRM.Sql</span><span class="sxs-lookup"><span data-stu-id="bc0e4-613">AzureRM.Sql</span></span>
  - <span data-ttu-id="bc0e4-614">AzureRM.Storage</span><span class="sxs-lookup"><span data-stu-id="bc0e4-614">AzureRM.Storage</span></span>
  - <span data-ttu-id="bc0e4-615">AzureRM.StreamAnalytics</span><span class="sxs-lookup"><span data-stu-id="bc0e4-615">AzureRM.StreamAnalytics</span></span>

## <a name="2017118---version-500"></a><span data-ttu-id="bc0e4-616">2017.11.8 - 版本 5.0.0</span><span class="sxs-lookup"><span data-stu-id="bc0e4-616">2017.11.8 - Version 5.0.0</span></span>
* <span data-ttu-id="bc0e4-617">注意：這是重大變更版本。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-617">NOTE: This is a breaking change release.</span></span> <span data-ttu-id="bc0e4-618">有關導入的重大變更完整清單，請參閱移轉指南 (https://aka.ms/azps-migration-guide)。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-618">Please see the migration guide (https://aka.ms/azps-migration-guide) for a full list of introduced breaking changes.</span></span>
* <span data-ttu-id="bc0e4-619">AzureRM 中所有的 Cmdlet 現在都支援線上說明</span><span class="sxs-lookup"><span data-stu-id="bc0e4-619">All cmdlets in AzureRM now support online help</span></span>
  - <span data-ttu-id="bc0e4-620">執行 Get-Help 搭配 -Online 參數，以在您的預設網際網路瀏覽器中開啟線上說明</span><span class="sxs-lookup"><span data-stu-id="bc0e4-620">Run Get-Help with the -Online parameter to open the online help in your default Internet browser</span></span>
* <span data-ttu-id="bc0e4-621">AnalysisServices</span><span class="sxs-lookup"><span data-stu-id="bc0e4-621">AnalysisServices</span></span>
  * <span data-ttu-id="bc0e4-622">固定的 Synchronize-AzureAsInstance 命令搭配使用新 AsAzure REST API 以進行同步處理</span><span class="sxs-lookup"><span data-stu-id="bc0e4-622">Fixed Synchronize-AzureAsInstance command to work with new AsAzure REST API for sync</span></span>
* <span data-ttu-id="bc0e4-623">ApiManagement</span><span class="sxs-lookup"><span data-stu-id="bc0e4-623">ApiManagement</span></span>
  * <span data-ttu-id="bc0e4-624">有關 ApiManagement 在這一版所做的重大變更，請參閱移轉指南</span><span class="sxs-lookup"><span data-stu-id="bc0e4-624">Please see the migration guide for breaking changes made to ApiManagement this release</span></span>
  * <span data-ttu-id="bc0e4-625">已更新 Cmdlet Get-AzureRmApiManagementUser 以修正問題 https://github.com/Azure/azure-powershell/issues/4510</span><span class="sxs-lookup"><span data-stu-id="bc0e4-625">Updated Cmdlet Get-AzureRmApiManagementUser to fix issue https://github.com/Azure/azure-powershell/issues/4510</span></span>
  * <span data-ttu-id="bc0e4-626">已更新 Cmdlet New-AzureRmApiManagementApi 以建立具備 Empty Path 的 API https://github.com/Azure/azure-powershell/issues/4069</span><span class="sxs-lookup"><span data-stu-id="bc0e4-626">Updated Cmdlet New-AzureRmApiManagementApi to create Api with Empty Path https://github.com/Azure/azure-powershell/issues/4069</span></span>
* <span data-ttu-id="bc0e4-627">ApplicationInsights</span><span class="sxs-lookup"><span data-stu-id="bc0e4-627">ApplicationInsights</span></span>
  * <span data-ttu-id="bc0e4-628">新增命令以取得/建立/移除應用程式深入解析資源</span><span class="sxs-lookup"><span data-stu-id="bc0e4-628">Add commands to get/create/remove applicaiton insights resource</span></span>
    - <span data-ttu-id="bc0e4-629">Get-AzureRmApplicationInsights</span><span class="sxs-lookup"><span data-stu-id="bc0e4-629">Get-AzureRmApplicationInsights</span></span>
    - <span data-ttu-id="bc0e4-630">New-AzureRmApplicationInsights</span><span class="sxs-lookup"><span data-stu-id="bc0e4-630">New-AzureRmApplicationInsights</span></span>
    - <span data-ttu-id="bc0e4-631">Remove-AzureRmApplicationInsights</span><span class="sxs-lookup"><span data-stu-id="bc0e4-631">Remove-AzureRmApplicationInsights</span></span>
  * <span data-ttu-id="bc0e4-632">新增命令以取得/更新價格/應用程式深入解析資源的每日上限</span><span class="sxs-lookup"><span data-stu-id="bc0e4-632">Add commands to get/update pricing/daily cap of applicaiton insights resource</span></span>
    - <span data-ttu-id="bc0e4-633">Get-AzureRmApplicationInsights -IncludeDailyCap</span><span class="sxs-lookup"><span data-stu-id="bc0e4-633">Get-AzureRmApplicationInsights -IncludeDailyCap</span></span>
    - <span data-ttu-id="bc0e4-634">Set-AzureRmApplicationInsightsPricingPlan</span><span class="sxs-lookup"><span data-stu-id="bc0e4-634">Set-AzureRmApplicationInsightsPricingPlan</span></span>
    - <span data-ttu-id="bc0e4-635">Set-AzureRmApplicationInsightsDailyCap</span><span class="sxs-lookup"><span data-stu-id="bc0e4-635">Set-AzureRmApplicationInsightsDailyCap</span></span>
  * <span data-ttu-id="bc0e4-636">新增命令以取得/建立/更新/移除應用程式深入解析資源的連續匯出</span><span class="sxs-lookup"><span data-stu-id="bc0e4-636">Add commands to get/create/update/remove continuous export of applicaiton insights resource</span></span>
    - <span data-ttu-id="bc0e4-637">Get-AzureRmApplicationInsightsContinuousExport</span><span class="sxs-lookup"><span data-stu-id="bc0e4-637">Get-AzureRmApplicationInsightsContinuousExport</span></span>
    - <span data-ttu-id="bc0e4-638">Set-AzureRmApplicationInsightsContinuousExport</span><span class="sxs-lookup"><span data-stu-id="bc0e4-638">Set-AzureRmApplicationInsightsContinuousExport</span></span>
    - <span data-ttu-id="bc0e4-639">New-AzureRmApplicationInsightsContinuousExport</span><span class="sxs-lookup"><span data-stu-id="bc0e4-639">New-AzureRmApplicationInsightsContinuousExport</span></span>
    - <span data-ttu-id="bc0e4-640">Remove-AzureRmApplicationInsightsContinuousExport</span><span class="sxs-lookup"><span data-stu-id="bc0e4-640">Remove-AzureRmApplicationInsightsContinuousExport</span></span>
  * <span data-ttu-id="bc0e4-641">新增命令以取得/建立/移除應用程式深入解析資源的 API 金鑰</span><span class="sxs-lookup"><span data-stu-id="bc0e4-641">Add commands to get/create/remove api keys of applicaiton insights resoruce</span></span>
    - <span data-ttu-id="bc0e4-642">Get-AzureRmApplicationInsightsApiKey</span><span class="sxs-lookup"><span data-stu-id="bc0e4-642">Get-AzureRmApplicationInsightsApiKey</span></span>
    - <span data-ttu-id="bc0e4-643">New-AzureRmApplicationInsightsApiKey</span><span class="sxs-lookup"><span data-stu-id="bc0e4-643">New-AzureRmApplicationInsightsApiKey</span></span>
    - <span data-ttu-id="bc0e4-644">Remove-AzureRmApplicationInsightsApiKey</span><span class="sxs-lookup"><span data-stu-id="bc0e4-644">Remove-AzureRmApplicationInsightsApiKey</span></span>
* <span data-ttu-id="bc0e4-645">AzureBatch</span><span class="sxs-lookup"><span data-stu-id="bc0e4-645">AzureBatch</span></span>
  * <span data-ttu-id="bc0e4-646">將新參數新增至 `New-AzureRmBatchAccount`。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-646">Added new parameters to `New-AzureRmBatchAccount`.</span></span>
    - <span data-ttu-id="bc0e4-647">`PoolAllocationMode`：在 Batch 帳戶中建立集區所使用的配置模式。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-647">`PoolAllocationMode`: The allocation mode to use for creating pools in the Batch account.</span></span> <span data-ttu-id="bc0e4-648">若要在使用者的訂用帳戶中建立配置集區節點的 Batch 帳戶，請將此設為 `UserSubscription`。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-648">To create a Batch account which allocates pool nodes in the user's subscription, set this to `UserSubscription`.</span></span>
    - <span data-ttu-id="bc0e4-649">`KeyVaultId`：與 Batch 帳戶相關的 Azure 金鑰保存庫之資源識別碼。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-649">`KeyVaultId`: The resource ID of the Azure key vault associated with the Batch account.</span></span>
    - <span data-ttu-id="bc0e4-650">`KeyVaultUrl`：與 Batch 帳戶相關的 Azure 金鑰保存庫之 URL。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-650">`KeyVaultUrl`: The URL of the Azure key vault associated with the Batch account.</span></span>
  * <span data-ttu-id="bc0e4-651">將參數更新為 `New-AzureBatchTask`。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-651">Updated parameters to `New-AzureBatchTask`.</span></span>
    - <span data-ttu-id="bc0e4-652">移除 `RunElevated` 參數。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-652">Removed the `RunElevated` switch.</span></span> <span data-ttu-id="bc0e4-653">已新增 `UserIdentity` 參數來取代 `RunElevated`，且對等的行為可藉由建構 `PSUserIdentity` 來達成，如下所示：</span><span class="sxs-lookup"><span data-stu-id="bc0e4-653">The `UserIdentity` parameter has been added to replace `RunElevated`, and the equivalent behavior can be achieved by constructing a `PSUserIdentity` as shown below:</span></span>
      - <span data-ttu-id="bc0e4-654">$autoUser = New-Object Microsoft.Azure.Commands.Batch.Models.PSAutoUserSpecification -ArgumentList @("Task", "Admin")</span><span class="sxs-lookup"><span data-stu-id="bc0e4-654">$autoUser = New-Object Microsoft.Azure.Commands.Batch.Models.PSAutoUserSpecification -ArgumentList @("Task", "Admin")</span></span>
      - <span data-ttu-id="bc0e4-655">$userIdentity = New-Object Microsoft.Azure.Commands.Batch.Models.PSUserIdentity $autoUser</span><span class="sxs-lookup"><span data-stu-id="bc0e4-655">$userIdentity = New-Object Microsoft.Azure.Commands.Batch.Models.PSUserIdentity $autoUser</span></span>
    - <span data-ttu-id="bc0e4-656">新增 `AuthenticationTokenSettings` 參數。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-656">Added the `AuthenticationTokenSettings` parameter.</span></span> <span data-ttu-id="bc0e4-657">這個參數可讓您要求 Batch 服務在執行時向工作提供驗證權杖，而不必先將 Batch 帳戶金鑰傳遞至工作，才能對 Batch 服務發出要求。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-657">This parameter allows you to request the Batch service provide an authentication token to the task when it runs, avoiding the need to pass Batch account keys to the task in order to issue requests to the Batch service.</span></span>
    - <span data-ttu-id="bc0e4-658">新增 `ContainerSettings` 參數。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-658">Added the `ContainerSettings` parameter.</span></span>
      - <span data-ttu-id="bc0e4-659">這個參數可讓您要求 Batch 服務在容器內執行工作。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-659">This parameter allows you to request the Batch service run the task inside a container.</span></span>
    - <span data-ttu-id="bc0e4-660">新增 `OutputFiles` 參數。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-660">Added the `OutputFiles` parameter.</span></span>
      - <span data-ttu-id="bc0e4-661">這個參數可讓您設定在工作完成之後將檔案上傳至 Azure 儲存體。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-661">This parameter allows you to configure the task to upload files to Azure Storage after it has finished.</span></span>
  * <span data-ttu-id="bc0e4-662">將參數更新為 `New-AzureBatchPool`。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-662">Updated parameters to `New-AzureBatchPool`.</span></span>
    - <span data-ttu-id="bc0e4-663">新增 `UserAccounts` 參數。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-663">Added the `UserAccounts` parameter.</span></span>
      - <span data-ttu-id="bc0e4-664">這個參數可定義集區中每個節點上所建立的使用者帳戶。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-664">This parameter defines user accounts created on each node in the pool.</span></span>
    - <span data-ttu-id="bc0e4-665">新增 `TargetLowPriorityComputeNodes` 並將 `TargetDedicated` 重新命名為 `TargetDedicatedComputeNodes`。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-665">Added `TargetLowPriorityComputeNodes` and renamed `TargetDedicated` to `TargetDedicatedComputeNodes`.</span></span>
      - <span data-ttu-id="bc0e4-666">針對 `TargetDedicatedComputeNodes` 參數已建立 `TargetDedicated` 別名。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-666">A `TargetDedicated` alias was created for the `TargetDedicatedComputeNodes` parameter.</span></span>
    - <span data-ttu-id="bc0e4-667">新增 `NetworkConfiguration` 參數。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-667">Added the `NetworkConfiguration` parameter.</span></span>
      - <span data-ttu-id="bc0e4-668">這個參數可讓您設定集區的網路設定。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-668">This parameter allows you to configure the pools network settings.</span></span>
  * <span data-ttu-id="bc0e4-669">將參數更新為 `New-AzureBatchCertificate`。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-669">Updated parameters to `New-AzureBatchCertificate`.</span></span>
    - <span data-ttu-id="bc0e4-670">`Password` 參數現在是 `SecureString`。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-670">The `Password` parameter is now a `SecureString`.</span></span>
  * <span data-ttu-id="bc0e4-671">將參數更新為 `New-AzureBatchComputeNodeUser`。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-671">Updated parameters to `New-AzureBatchComputeNodeUser`.</span></span>
    - <span data-ttu-id="bc0e4-672">`Password` 參數現在是 `SecureString`。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-672">The `Password` parameter is now a `SecureString`.</span></span>
  * <span data-ttu-id="bc0e4-673">將參數更新為 `Set-AzureBatchComputeNodeUser`。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-673">Updated parameters to `Set-AzureBatchComputeNodeUser`.</span></span>
    - <span data-ttu-id="bc0e4-674">`Password` 參數現在是 `SecureString`。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-674">The `Password` parameter is now a `SecureString`.</span></span>
  * <span data-ttu-id="bc0e4-675">在 `Get-AzureBatchNodeFile`、`Get-AzureBatchNodeFileContent` 和 `Remove-AzureBatchNodeFile` 上將 `Name` 參數重新命名為 `Path`。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-675">Renamed the `Name` parameter to `Path` on `Get-AzureBatchNodeFile`, `Get-AzureBatchNodeFileContent`, and `Remove-AzureBatchNodeFile`.</span></span>
    - <span data-ttu-id="bc0e4-676">針對 `Path` 參數已建立 `Name` 別名。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-676">A `Name` alias was created for the `Path` parameter.</span></span>
  * <span data-ttu-id="bc0e4-677">物件的變更</span><span class="sxs-lookup"><span data-stu-id="bc0e4-677">Changes to objects</span></span>
    - <span data-ttu-id="bc0e4-678">請參閱 Batch 變更記錄取得完整清單</span><span class="sxs-lookup"><span data-stu-id="bc0e4-678">Please see the Batch change log for the full list</span></span>
  * <span data-ttu-id="bc0e4-679">新增 Azure Active Directory 型驗證支援。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-679">Added support for Azure Active Directory based authentication.</span></span>
    - <span data-ttu-id="bc0e4-680">若要使用 Azure Active Directory 驗證，請使用 `Get-AzureRmBatchAccount` Cmdlet 擷取 `BatchAccountContext` 物件，並將此 `BatchAccountContext` 提供至 Batch 服務 Cmdlet 的 `-BatchContext` 參數。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-680">To use Azure Active Directory authentication, retrieve a `BatchAccountContext` object using the `Get-AzureRmBatchAccount` cmdlet, and supply this `BatchAccountContext` to the `-BatchContext` parameter of a Batch service cmdlet.</span></span> <span data-ttu-id="bc0e4-681">對於具有 `PoolAllocationMode = UserSubscription` 的帳戶，Azure Active Directory 驗證為必要。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-681">Azure Active Directory authentication is mandatory for accounts with `PoolAllocationMode = UserSubscription`.</span></span>
    - <span data-ttu-id="bc0e4-682">對於現有帳戶或以 `PoolAllocationMode = BatchService` 建立的新帳戶，您可以藉由使用 `Get-AzureRmBatchAccoutKeys` Cmdlet 擷取 `BatchAccountContext` 物件，繼續使用共用金鑰驗證。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-682">For existing accounts or for new accounts created with `PoolAllocationMode = BatchService`, you may continue to use shared key authentication by retrieving a `BatchAccountContext` object using the `Get-AzureRmBatchAccoutKeys` cmdlet.</span></span>
* <span data-ttu-id="bc0e4-683">計算</span><span class="sxs-lookup"><span data-stu-id="bc0e4-683">Compute</span></span>
  * <span data-ttu-id="bc0e4-684">Azure 磁碟加密延伸模組命令</span><span class="sxs-lookup"><span data-stu-id="bc0e4-684">Azure Disk Encryption Extension Commands</span></span>
    - <span data-ttu-id="bc0e4-685">'Set-AzureRmVmDiskEncryptionExtension' 的新參數：'-EncryptFormatAll' 加密格式資料磁碟</span><span class="sxs-lookup"><span data-stu-id="bc0e4-685">New Parameter for 'Set-AzureRmVmDiskEncryptionExtension': '-EncryptFormatAll' encrypt formats data disks</span></span>
    - <span data-ttu-id="bc0e4-686">'Set-AzureRmVmDiskEncryptionExtension' 的新參數：'-ExtensionPublisherName' 和 '-ExtensionType' 允許切換至延伸模組的其他版本</span><span class="sxs-lookup"><span data-stu-id="bc0e4-686">New Parameters for 'Set-AzureRmVmDiskEncryptionExtension': '-ExtensionPublisherName' and '-ExtensionType' allow switching to other versions of the extension</span></span>
    - <span data-ttu-id="bc0e4-687">'Disable-AzureRmVmDiskEncryption' 的新參數：'-ExtensionPublisherName' 和 '-ExtensionType' 允許切換至延伸模組的其他版本</span><span class="sxs-lookup"><span data-stu-id="bc0e4-687">New Parameters for 'Disable-AzureRmVmDiskEncryption': '-ExtensionPublisherName' and '-ExtensionType' allow switching to other versions of the extension</span></span>
    - <span data-ttu-id="bc0e4-688">'Get-AzureRmVmDiskEncryptionStatus' 的新參數：'-ExtensionPublisherName' 和 '-ExtensionType' 允許切換至延伸模組的其他版本</span><span class="sxs-lookup"><span data-stu-id="bc0e4-688">New Parameters for 'Get-AzureRmVmDiskEncryptionStatus': '-ExtensionPublisherName' and '-ExtensionType' allow switching to other versions of the extension</span></span>
* <span data-ttu-id="bc0e4-689">DataLakeAnalytics</span><span class="sxs-lookup"><span data-stu-id="bc0e4-689">DataLakeAnalytics</span></span>
  * <span data-ttu-id="bc0e4-690">有關 DataLakeAnalytics 在這一版所做的重大變更，請參閱移轉指南</span><span class="sxs-lookup"><span data-stu-id="bc0e4-690">Please see the migration guide for breaking changes made to DataLakeAnalytics this release</span></span>
  * <span data-ttu-id="bc0e4-691">變更 Get-AzureRmDataLakeAnalyticsAccount 兩種 OutputTypes 的其中一種</span><span class="sxs-lookup"><span data-stu-id="bc0e4-691">Changed one of the two OutputTypes of Get-AzureRmDataLakeAnalyticsAccount</span></span>
    - <span data-ttu-id="bc0e4-692">List\<DataLakeAnalyticsAccount> 到 List\<PSDataLakeAnalyticsAccountBasic></span><span class="sxs-lookup"><span data-stu-id="bc0e4-692">List\<DataLakeAnalyticsAccount> to List\<PSDataLakeAnalyticsAccountBasic></span></span>
    - <span data-ttu-id="bc0e4-693">PSDataLakeAnalyticsAccountBasic 的屬性是 DataLakeAnalyticsAccount 屬性的 strict 子集</span><span class="sxs-lookup"><span data-stu-id="bc0e4-693">The properties of PSDataLakeAnalyticsAccountBasic is a strict subset of the properties of DataLakeAnalyticsAccount</span></span>
    - <span data-ttu-id="bc0e4-694">服務不會傳回 DataLakeAnalyticsAccount 中的其他屬性。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-694">The additional properties that are in DataLakeAnalyticsAccount are not returned by the service.</span></span>  <span data-ttu-id="bc0e4-695">因此，這項變更是為了準確反映此情況。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-695">Therefore, this change is to reflect this accurately.</span></span> <span data-ttu-id="bc0e4-696">這些額外屬性仍然在 PSDataLakeAnalyticsAccountBasic 中，但被標記為 [已淘汰]。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-696">These additional properties are still in PSDataLakeAnalyticsAccountBasic, but they are tagged as Obsolete.</span></span>
  * <span data-ttu-id="bc0e4-697">變更 Get-AzureRmDataLakeAnalyticsJob 兩種 OutputTypes 的其中一種</span><span class="sxs-lookup"><span data-stu-id="bc0e4-697">Changed one of the two OutputTypes of Get-AzureRmDataLakeAnalyticsJob</span></span>
    - <span data-ttu-id="bc0e4-698">List\<JobInformation> 到 List\<PSJobInformationBasic></span><span class="sxs-lookup"><span data-stu-id="bc0e4-698">List\<JobInformation> to List\<PSJobInformationBasic></span></span>
    - <span data-ttu-id="bc0e4-699">PSJobInformationBasic 的屬性是 JobInformation 屬性的 strict 子集</span><span class="sxs-lookup"><span data-stu-id="bc0e4-699">The properties of PSJobInformationBasic is a strict subset of the properties of JobInformation</span></span>
    - <span data-ttu-id="bc0e4-700">服務不會傳回 JobInformation 中的其他屬性。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-700">The additional properties that are in JobInformation are not returned by the service.</span></span>  <span data-ttu-id="bc0e4-701">因此，這項變更是為了準確反映此情況。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-701">Therefore, this change is to reflect this accurately.</span></span> <span data-ttu-id="bc0e4-702">這些額外屬性仍然在 PSJobInformationBasic 中，但被標記為 [已淘汰]。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-702">These additional properties are still in PSJobInformationBasic, but they are tagged as Obsolete.</span></span>
* <span data-ttu-id="bc0e4-703">DataLakeStore</span><span class="sxs-lookup"><span data-stu-id="bc0e4-703">DataLakeStore</span></span>
  * <span data-ttu-id="bc0e4-704">有關 DataLakeStore 在這一版所做的重大變更，請參閱移轉指南</span><span class="sxs-lookup"><span data-stu-id="bc0e4-704">Please see the migration guide for breaking changes made to DataLakeStore this release</span></span>
  * <span data-ttu-id="bc0e4-705">變更 Get-AzureRmDataLakeStoreAccount 兩種 OutputTypes 的其中一種</span><span class="sxs-lookup"><span data-stu-id="bc0e4-705">Changed one of the two OutputTypes of Get-AzureRmDataLakeStoreAccount</span></span>
    - <span data-ttu-id="bc0e4-706">List\<PSDataLakeStoreAccount> 到 List\<PSDataLakeStoreAccountBasic></span><span class="sxs-lookup"><span data-stu-id="bc0e4-706">List\<PSDataLakeStoreAccount> to List\<PSDataLakeStoreAccountBasic></span></span>
    - <span data-ttu-id="bc0e4-707">PSDataLakeStoreAccountBasic 的屬性是 PSDataLakeStoreAccount 屬性的 strict 子集</span><span class="sxs-lookup"><span data-stu-id="bc0e4-707">The properties of PSDataLakeStoreAccountBasic is a strict subset of the properties of PSDataLakeStoreAccount</span></span>
    - <span data-ttu-id="bc0e4-708">服務不會傳回 PSDataLakeStoreAccount 中的其他屬性。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-708">The additional properties that are in PSDataLakeStoreAccount are not returned by the service.</span></span>  <span data-ttu-id="bc0e4-709">因此，這項變更是為了準確反映此情況。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-709">Therefore, this change is to reflect this accurately.</span></span> <span data-ttu-id="bc0e4-710">這些額外屬性仍然在 PSDataLakeStoreAccountBasic 中，但被標記為 [已淘汰]。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-710">These additional properties are still in PSDataLakeStoreAccountBasic, but they are tagged as Obsolete.</span></span>
* <span data-ttu-id="bc0e4-711">Dns</span><span class="sxs-lookup"><span data-stu-id="bc0e4-711">Dns</span></span>
  * <span data-ttu-id="bc0e4-712">Azure DNS 中 CAA 記錄型別的支援</span><span class="sxs-lookup"><span data-stu-id="bc0e4-712">Support for CAA record types in Azure DNS</span></span>
    - <span data-ttu-id="bc0e4-713">支援 CAA 記錄型別上的所有作業</span><span class="sxs-lookup"><span data-stu-id="bc0e4-713">Supports all operations on CAA record type</span></span>
* <span data-ttu-id="bc0e4-714">EventHub</span><span class="sxs-lookup"><span data-stu-id="bc0e4-714">EventHub</span></span>
  * <span data-ttu-id="bc0e4-715">有關 EventHub 在這一版所做的重大變更，請參閱移轉指南</span><span class="sxs-lookup"><span data-stu-id="bc0e4-715">Please see the migration guide for breaking changes made to EventHub this release</span></span>
* <span data-ttu-id="bc0e4-716">深入解析</span><span class="sxs-lookup"><span data-stu-id="bc0e4-716">Insights</span></span>
  * <span data-ttu-id="bc0e4-717">有關深入解析在這一版所做的重大變更，請參閱移轉指南</span><span class="sxs-lookup"><span data-stu-id="bc0e4-717">Please see the migration guide for breaking changes made to Insights this release</span></span>
* <span data-ttu-id="bc0e4-718">網路</span><span class="sxs-lookup"><span data-stu-id="bc0e4-718">Network</span></span>
  * <span data-ttu-id="bc0e4-719">有關網路在這一版所做的重大變更，請參閱移轉指南</span><span class="sxs-lookup"><span data-stu-id="bc0e4-719">Please see the migration guide for breaking changes made to Network this release</span></span>
  * <span data-ttu-id="bc0e4-720">新增 Cmdlet 以針對指定的 Azure 區域列出可用的網際網路服務提供者</span><span class="sxs-lookup"><span data-stu-id="bc0e4-720">Added cmdlet to list available internet service providers for a specified Azure region</span></span>
    - <span data-ttu-id="bc0e4-721">Get-AzureRmNetworkWatcherReachabilityProvidersList</span><span class="sxs-lookup"><span data-stu-id="bc0e4-721">Get-AzureRmNetworkWatcherReachabilityProvidersList</span></span>
  * <span data-ttu-id="bc0e4-722">新增 Cmdlet 以取得從指定位置到 Azure 區域的網際網路服務提供者相對延遲分數</span><span class="sxs-lookup"><span data-stu-id="bc0e4-722">Added cmdlet to get the relative latency score for internet service providers from a specified location to Azure regions</span></span>
    - <span data-ttu-id="bc0e4-723">Get-AzureRmNetworkWatcherReachabilityReport</span><span class="sxs-lookup"><span data-stu-id="bc0e4-723">Get-AzureRmNetworkWatcherReachabilityReport</span></span>
* <span data-ttu-id="bc0e4-724">設定檔</span><span class="sxs-lookup"><span data-stu-id="bc0e4-724">Profile</span></span>
  - <span data-ttu-id="bc0e4-725">Set-AzureRmDefault</span><span class="sxs-lookup"><span data-stu-id="bc0e4-725">Set-AzureRmDefault</span></span>
    - <span data-ttu-id="bc0e4-726">使用這個 Cmdlet 設定預設的資源群組。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-726">Use this cmdlet to set a default resource group.</span></span>  <span data-ttu-id="bc0e4-727">對於某些 Cmdlet，這會讓 -ResourceGroup 參數成為選用，且在未指定資源群組時將使用預設值</span><span class="sxs-lookup"><span data-stu-id="bc0e4-727">This will make the -ResourceGroup parameter optional for some cmdlets, and will use the default when a resource group is not specified</span></span>
    - ```Set-AzureRmDefault -ResourceGroupName "ExampleResourceGroup"```
    - <span data-ttu-id="bc0e4-728">如果指定的資源群組存在於訂用帳戶中，則此資源群組將會設為預設值。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-728">If resource group specified exists in the subscription, this resource group will be set to default.</span></span>  <span data-ttu-id="bc0e4-729">否則，將會建立該資源群組，並將其設為預設值。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-729">Otherwise, the resource group will be created and then set to default.</span></span>
  - <span data-ttu-id="bc0e4-730">Get-AzureRmDefault</span><span class="sxs-lookup"><span data-stu-id="bc0e4-730">Get-AzureRmDefault</span></span>
    - <span data-ttu-id="bc0e4-731">使用這個 Cmdlet 取得目前預設的資源群組 (和未來其他的預設)。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-731">Use this cmdlet to get the current default resource group (and other defaults in the future).</span></span>
    - ```Get-AzureRmDefault -ResourceGroup```
  - <span data-ttu-id="bc0e4-732">Clear-AzureRmDefault</span><span class="sxs-lookup"><span data-stu-id="bc0e4-732">Clear-AzureRmDefault</span></span>
    - <span data-ttu-id="bc0e4-733">使用這個 Cmdlet 移除目前預設的資源群組</span><span class="sxs-lookup"><span data-stu-id="bc0e4-733">Use this cmdlet to remove the current default resource group</span></span>
    - ```Clear-AzureRmDefault -ResourceGroup```
  - <span data-ttu-id="bc0e4-734">Add-AzureRmEnvironment 和 Set-AzureRmEnvironment</span><span class="sxs-lookup"><span data-stu-id="bc0e4-734">Add-AzureRmEnvironment and Set-AzureRmEnvironment</span></span>
    - <span data-ttu-id="bc0e4-735">新增 BatchAudience 參數，可讓您指定在取得 Batch 服務驗證權杖時所要使用的 Azure Batch Active Directory 對象。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-735">Add the BatchAudience parameter, which allows you to specify the Azure Batch Active Directory audience to use when acquiring authentication tokens for the Batch service.</span></span>
* <span data-ttu-id="bc0e4-736">RecoveryServices.Backup</span><span class="sxs-lookup"><span data-stu-id="bc0e4-736">RecoveryServices.Backup</span></span>
  * <span data-ttu-id="bc0e4-737">新增 Cmdlet 以執行立即檔案復原。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-737">Added cmdlets to perform instant file recovery.</span></span>
    - <span data-ttu-id="bc0e4-738">Get-AzureRmRecoveryServicesBackupRPMountScript</span><span class="sxs-lookup"><span data-stu-id="bc0e4-738">Get-AzureRmRecoveryServicesBackupRPMountScript</span></span>
    - <span data-ttu-id="bc0e4-739">Disable-AzureRmRecoveryServicesBackupRPMountScript</span><span class="sxs-lookup"><span data-stu-id="bc0e4-739">Disable-AzureRmRecoveryServicesBackupRPMountScript</span></span>
  * <span data-ttu-id="bc0e4-740">將 RecoveryServices.Backup SDK 更新至最新版本</span><span class="sxs-lookup"><span data-stu-id="bc0e4-740">Updated RecoveryServices.Backup SDK version to the latest</span></span>
  * <span data-ttu-id="bc0e4-741">更新 Azure VM 工作負載的測試，如此一來測試回合所需的所有設定便由測試本身完成。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-741">Updated tests for the Azure VM workload so that, all setups needed for test runs are done by the tests themselves.</span></span>
  * <span data-ttu-id="bc0e4-742">修正 https://github.com/Azure/azure-powershell/issues/3164</span><span class="sxs-lookup"><span data-stu-id="bc0e4-742">Fixes https://github.com/Azure/azure-powershell/issues/3164</span></span>
* <span data-ttu-id="bc0e4-743">RecoveryServices.SiteRecovery</span><span class="sxs-lookup"><span data-stu-id="bc0e4-743">RecoveryServices.SiteRecovery</span></span>
  * <span data-ttu-id="bc0e4-744">ASR VMware 到 Azure Site Recovery 的變更 (Cmdlet 目前支援企業到企業、企業到 Azure、HyperV 到 Azure 的作業)</span><span class="sxs-lookup"><span data-stu-id="bc0e4-744">Changes for ASR VMware to Azure Site Recovery (cmdlets are currently supporting operations for Enterprise to Enterprise, Enterprise to Azure, HyperV to Azure)</span></span>
    - <span data-ttu-id="bc0e4-745">New-AzureRmRecoveryServicesAsrPolicy</span><span class="sxs-lookup"><span data-stu-id="bc0e4-745">New-AzureRmRecoveryServicesAsrPolicy</span></span>
    - <span data-ttu-id="bc0e4-746">New-AzureRmRecoveryServicesAsrProtectedItem</span><span class="sxs-lookup"><span data-stu-id="bc0e4-746">New-AzureRmRecoveryServicesAsrProtectedItem</span></span>
    - <span data-ttu-id="bc0e4-747">Update-AzureRmRecoveryServicesAsrPolicy</span><span class="sxs-lookup"><span data-stu-id="bc0e4-747">Update-AzureRmRecoveryServicesAsrPolicy</span></span>
    - <span data-ttu-id="bc0e4-748">Update-AzureRmRecoveryServicesAsrProtectionDirection</span><span class="sxs-lookup"><span data-stu-id="bc0e4-748">Update-AzureRmRecoveryServicesAsrProtectionDirection</span></span>
  * <span data-ttu-id="bc0e4-749">新增以 AAD 為基礎的保存庫支援</span><span class="sxs-lookup"><span data-stu-id="bc0e4-749">Added support to AAD-based vault</span></span>
  * <span data-ttu-id="bc0e4-750">新增 Cmdlet 以管理 VCenter 資源</span><span class="sxs-lookup"><span data-stu-id="bc0e4-750">Added cmdlets to manage VCenter resources</span></span>
    - <span data-ttu-id="bc0e4-751">Get-AzureRmRecoveryServicesAsrVCenter</span><span class="sxs-lookup"><span data-stu-id="bc0e4-751">Get-AzureRmRecoveryServicesAsrVCenter</span></span>
    - <span data-ttu-id="bc0e4-752">New-AzureRmRecoveryServicesAsrVCenter</span><span class="sxs-lookup"><span data-stu-id="bc0e4-752">New-AzureRmRecoveryServicesAsrVCenter</span></span>
    - <span data-ttu-id="bc0e4-753">Remove-AzureRmRecoveryServicesAsrVCenter</span><span class="sxs-lookup"><span data-stu-id="bc0e4-753">Remove-AzureRmRecoveryServicesAsrVCenter</span></span>
    - <span data-ttu-id="bc0e4-754">Update-AzureRmRecoveryServicesAsrVCenter</span><span class="sxs-lookup"><span data-stu-id="bc0e4-754">Update-AzureRmRecoveryServicesAsrVCenter</span></span>
  * <span data-ttu-id="bc0e4-755">新增其他 Cmdlet</span><span class="sxs-lookup"><span data-stu-id="bc0e4-755">Added other cmdlets</span></span>
    - <span data-ttu-id="bc0e4-756">Get-AzureRmRecoveryServicesAsrAlertSetting</span><span class="sxs-lookup"><span data-stu-id="bc0e4-756">Get-AzureRmRecoveryServicesAsrAlertSetting</span></span>
    - <span data-ttu-id="bc0e4-757">Get-AzureRmRecoveryServicesAsrEvent</span><span class="sxs-lookup"><span data-stu-id="bc0e4-757">Get-AzureRmRecoveryServicesAsrEvent</span></span>
    - <span data-ttu-id="bc0e4-758">New-AzureRmRecoveryServicesAsrProtectableItem</span><span class="sxs-lookup"><span data-stu-id="bc0e4-758">New-AzureRmRecoveryServicesAsrProtectableItem</span></span>
    - <span data-ttu-id="bc0e4-759">Set-AzureRmRecoveryServicesAsrAlertSetting</span><span class="sxs-lookup"><span data-stu-id="bc0e4-759">Set-AzureRmRecoveryServicesAsrAlertSetting</span></span>
    - <span data-ttu-id="bc0e4-760">Start-AzureRmRecoveryServicesAsrResynchronizeReplicationJob</span><span class="sxs-lookup"><span data-stu-id="bc0e4-760">Start-AzureRmRecoveryServicesAsrResynchronizeReplicationJob</span></span>
    - <span data-ttu-id="bc0e4-761">Start-AzureRmRecoveryServicesAsrSwitchProcessServerJob</span><span class="sxs-lookup"><span data-stu-id="bc0e4-761">Start-AzureRmRecoveryServicesAsrSwitchProcessServerJob</span></span>
    - <span data-ttu-id="bc0e4-762">Start-AzureRmRecoveryServicesAsrTestFailoverCleanupJob</span><span class="sxs-lookup"><span data-stu-id="bc0e4-762">Start-AzureRmRecoveryServicesAsrTestFailoverCleanupJob</span></span>
    - <span data-ttu-id="bc0e4-763">Update-AzureRmRecoveryServicesAsrMobilityService</span><span class="sxs-lookup"><span data-stu-id="bc0e4-763">Update-AzureRmRecoveryServicesAsrMobilityService</span></span>
* <span data-ttu-id="bc0e4-764">ServiceBus</span><span class="sxs-lookup"><span data-stu-id="bc0e4-764">ServiceBus</span></span>
  - <span data-ttu-id="bc0e4-765">有關 ServiceBus 在這一版所做的重大變更，請參閱移轉指南</span><span class="sxs-lookup"><span data-stu-id="bc0e4-765">Please see the migration guide for breaking changes made to ServiceBus this release</span></span>
* <span data-ttu-id="bc0e4-766">Sql</span><span class="sxs-lookup"><span data-stu-id="bc0e4-766">Sql</span></span>
  * <span data-ttu-id="bc0e4-767">新增對列出和取消資料庫上非同步 updateslo 作業的支援</span><span class="sxs-lookup"><span data-stu-id="bc0e4-767">Adding support for list and cancel the asynchronous updateslo operation on the database</span></span>
    - <span data-ttu-id="bc0e4-768">更新現有的 Cmdlet Get-AzureRmSqlDatabaseActivity 以傳回 DB updateslo 作業狀態。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-768">update existing cmdlet Get-AzureRmSqlDatabaseActivity to return DB updateslo operation status.</span></span>
    - <span data-ttu-id="bc0e4-769">新增新的 Cmdlet Stop-AzureRmSqlDatabaseActivity 以取消資料庫上的非同步 updateslo 作業。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-769">add new cmdlet Stop-AzureRmSqlDatabaseActivity for cancel the asynchronous updateslo operation on the database.</span></span>
  * <span data-ttu-id="bc0e4-770">新增對資料庫和彈性集區的區域備援支援</span><span class="sxs-lookup"><span data-stu-id="bc0e4-770">Adding support for Zone Redundancy for databases and elastic pools</span></span>
    - <span data-ttu-id="bc0e4-771">將 ZoneRedundant 切換參數新增至 New-AzureRmSqlDatabase</span><span class="sxs-lookup"><span data-stu-id="bc0e4-771">Adding ZoneRedundant switch parameter to New-AzureRmSqlDatabase</span></span>
    - <span data-ttu-id="bc0e4-772">將 ZoneRedundant 切換參數新增至 Set-AzureRmSqlDatabase</span><span class="sxs-lookup"><span data-stu-id="bc0e4-772">Adding ZoneRedundant switch parameter to Set-AzureRmSqlDatabase</span></span>
    - <span data-ttu-id="bc0e4-773">將 ZoneRedundant 切換參數新增至 New-AzureRmSqlElasticPool</span><span class="sxs-lookup"><span data-stu-id="bc0e4-773">Adding ZoneRedundant switch parameter to New-AzureRmSqlElasticPool</span></span>
    - <span data-ttu-id="bc0e4-774">將 ZoneRedundant 切換參數新增至 Set-AzureRmSqlElasticPool</span><span class="sxs-lookup"><span data-stu-id="bc0e4-774">Adding ZoneRedundant switch parameter to Set-AzureRmSqlElasticPool</span></span>
  * <span data-ttu-id="bc0e4-775">新增對伺服器 DNS 別名的支援</span><span class="sxs-lookup"><span data-stu-id="bc0e4-775">Adding support for Server DNS Aliases</span></span>
    - <span data-ttu-id="bc0e4-776">新增 Get-AzureRmSqlServerDnsAlias Cmdlet，其可按照伺服器和別名名稱取得伺服器 dns 別名，或 Azure Sql Server 的伺服器 dns 別名清單。</span><span class="sxs-lookup"><span data-stu-id="bc0e4-776">Adding Get-AzureRmSqlServerDnsAlias cmdlet which gets server dns aliases by server and alias name or a list of server dns aliases for an azure Sql Server.</span></span>
    - <span data-ttu-id="bc0e4-777">新增 New-AzureRmSqlServerDnsAlias Cmdlet，其可建立指定的 Azure Sql 伺服器的新伺服器 dns 別名</span><span class="sxs-lookup"><span data-stu-id="bc0e4-777">Adding New-AzureRmSqlServerDnsAlias cmdlet which creates new server dns alias for a given Azure Sql server</span></span>
    - <span data-ttu-id="bc0e4-778">新增 Set-AzurermSqlServerDnsAlias Cmdlet，其可讓伺服器 dns 別名指向的 Azure Sql Server 進行更新</span><span class="sxs-lookup"><span data-stu-id="bc0e4-778">Adding Set-AzurermSqlServerDnsAlias cmlet which allows updating a Azure Sql Server to which server dns alias is pointing</span></span>
    - <span data-ttu-id="bc0e4-779">新增 Remove-AzureRmSqlServerDnsAlias Cmdlet，其可移除 Azure Sql 伺服器的伺服器 dns 別名</span><span class="sxs-lookup"><span data-stu-id="bc0e4-779">Adding Remove-AzureRmSqlServerDnsAlias cmdlet which removes a server dns alias for a Azure Sql Server</span></span>
* <span data-ttu-id="bc0e4-780">Azure.Storage</span><span class="sxs-lookup"><span data-stu-id="bc0e4-780">Azure.Storage</span></span>
  * <span data-ttu-id="bc0e4-781">升級至 Azure 儲存體用戶端程式庫 8.5.0 及 Azure 儲存體資料移動程式庫 0.6.3</span><span class="sxs-lookup"><span data-stu-id="bc0e4-781">Upgrade to Azure Storage Client Library 8.5.0 and Azure Storage DataMovement Library 0.6.3</span></span>
  * <span data-ttu-id="bc0e4-782">新增檔案共用快照集支援功能</span><span class="sxs-lookup"><span data-stu-id="bc0e4-782">Add File Share Snapshot Support Feature</span></span>
    - <span data-ttu-id="bc0e4-783">將 'SnapshotTime' 參數新增至 Get-AzureStorageShare</span><span class="sxs-lookup"><span data-stu-id="bc0e4-783">Add 'SnapshotTime' parameter to Get-AzureStorageShare</span></span>
    - <span data-ttu-id="bc0e4-784">將 'IncludeAllSnapshot' 參數新增至 Remove-AzureStorageShare</span><span class="sxs-lookup"><span data-stu-id="bc0e4-784">Add 'IncludeAllSnapshot' parameter to Remove-AzureStorageShare</span></span>
