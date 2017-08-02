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
ms.openlocfilehash: cc2fe75f498f9043e5a4b632c144877af0143173
ms.sourcegitcommit: 20bcef86db4e4869125bb63085fcffd009c19280
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/27/2017
---
# <a name="release-notes"></a><span data-ttu-id="67d2b-103">版本資訊</span><span class="sxs-lookup"><span data-stu-id="67d2b-103">Release notes</span></span>

<span data-ttu-id="67d2b-104">這是此版本中對 Azure PowerShell 所做的變更清單。</span><span class="sxs-lookup"><span data-stu-id="67d2b-104">This is a list of changes made to Azure PowerShell in this release.</span></span>

## <a name="20170717---version-421"></a><span data-ttu-id="67d2b-105">2017.07.17 - 版本 4.2.1</span><span class="sxs-lookup"><span data-stu-id="67d2b-105">2017.07.17 - Version 4.2.1</span></span>
* <span data-ttu-id="67d2b-106">計算</span><span class="sxs-lookup"><span data-stu-id="67d2b-106">Compute</span></span>
    - <span data-ttu-id="67d2b-107">透過 VM 磁碟和 VM 磁碟快照集修正問題，建立並更新 Cmdlet，(連結) (英文) [https://github.com/azure/azure-powershell/issues/4309]</span><span class="sxs-lookup"><span data-stu-id="67d2b-107">Fix issue with VM DIsk and VM Disk snapshot create and update cmdlets, (link)[https://github.com/azure/azure-powershell/issues/4309]</span></span>
      - <span data-ttu-id="67d2b-108">New-AzureRmDisk</span><span class="sxs-lookup"><span data-stu-id="67d2b-108">New-AzureRmDisk</span></span>
      - <span data-ttu-id="67d2b-109">New-AzureRmSnapshot</span><span class="sxs-lookup"><span data-stu-id="67d2b-109">New-AzureRmSnapshot</span></span>
      - <span data-ttu-id="67d2b-110">Update-AzureRmDisk</span><span class="sxs-lookup"><span data-stu-id="67d2b-110">Update-AzureRmDisk</span></span>
      - <span data-ttu-id="67d2b-111">Update-AzureRmSnapshot</span><span class="sxs-lookup"><span data-stu-id="67d2b-111">Update-AzureRmSnapshot</span></span>
* <span data-ttu-id="67d2b-112">設定檔</span><span class="sxs-lookup"><span data-stu-id="67d2b-112">Profile</span></span>
    - <span data-ttu-id="67d2b-113">在 RDFE 使用非互動使用者驗證修正問題 (連結) (英文) [https://github.com/Azure/azure-powershell/issues/4299]</span><span class="sxs-lookup"><span data-stu-id="67d2b-113">Fix issue with non-interactive user authentication in RDFE (link)[https://github.com/Azure/azure-powershell/issues/4299]</span></span>
* <span data-ttu-id="67d2b-114">ServiceManagement</span><span class="sxs-lookup"><span data-stu-id="67d2b-114">ServiceManagement</span></span>
    - <span data-ttu-id="67d2b-115">使用非互動使用者驗證修正問題 (連結) (英文) [https://github.com/Azure/azure-powershell/issues/4299]</span><span class="sxs-lookup"><span data-stu-id="67d2b-115">Fix issue with non-interactive user authentication (link)[https://github.com/Azure/azure-powershell/issues/4299]</span></span>

## <a name="2017711---version-420"></a><span data-ttu-id="67d2b-116">2017.7.11 - 版本 4.2.0</span><span class="sxs-lookup"><span data-stu-id="67d2b-116">2017.7.11 - Version 4.2.0</span></span>
* <span data-ttu-id="67d2b-117">AnalysisServices</span><span class="sxs-lookup"><span data-stu-id="67d2b-117">AnalysisServices</span></span>
    * <span data-ttu-id="67d2b-118">新增資料平面 API</span><span class="sxs-lookup"><span data-stu-id="67d2b-118">Add new dataplane API</span></span>
        - <span data-ttu-id="67d2b-119">引進用以擷取 AS 伺服器記錄檔 Export-AzureAnalysisServicesInstanceLog 的 API</span><span class="sxs-lookup"><span data-stu-id="67d2b-119">Introduced API to fetch AS server log, Export-AzureAnalysisServicesInstanceLog</span></span>
* <span data-ttu-id="67d2b-120">自動化</span><span class="sxs-lookup"><span data-stu-id="67d2b-120">Automation</span></span>
    * <span data-ttu-id="67d2b-121">針對 New-AzureRmAutomationSchedule，正確設定每週和每月排程的 TimeZone 值</span><span class="sxs-lookup"><span data-stu-id="67d2b-121">Properly setting TimeZone value for Weekly and Monthly schedules for New-AzureRmAutomationSchedule</span></span>
        - <span data-ttu-id="67d2b-122">詳細資訊可以在本問題找到 (英文)：https://github.com/Azure/azure-powershell/issues/3043</span><span class="sxs-lookup"><span data-stu-id="67d2b-122">More information can be found in this issue: https://github.com/Azure/azure-powershell/issues/3043</span></span>
* <span data-ttu-id="67d2b-123">AzureBatch</span><span class="sxs-lookup"><span data-stu-id="67d2b-123">AzureBatch</span></span>
    - <span data-ttu-id="67d2b-124">新增 Get-AzureBatchJobPreparationAndReleaseTaskStatus cmdlet。</span><span class="sxs-lookup"><span data-stu-id="67d2b-124">Added new Get-AzureBatchJobPreparationAndReleaseTaskStatus cmdlet.</span></span>
    - <span data-ttu-id="67d2b-125">將位元組範圍的開始與結束加入 Get-AzureBatchNodeFileContent 參數。</span><span class="sxs-lookup"><span data-stu-id="67d2b-125">Added byte range start and end to Get-AzureBatchNodeFileContent parameters.</span></span>
* <span data-ttu-id="67d2b-126">CognitiveServices</span><span class="sxs-lookup"><span data-stu-id="67d2b-126">CognitiveServices</span></span>
    * <span data-ttu-id="67d2b-127">整合辨識服務管理 SDK 1.0.0 版。</span><span class="sxs-lookup"><span data-stu-id="67d2b-127">Integrate with Cognitive Services Management SDK version 1.0.0.</span></span>
    * <span data-ttu-id="67d2b-128">修正帳戶名稱長度檢查錯誤。</span><span class="sxs-lookup"><span data-stu-id="67d2b-128">Fix an account name length checking bug.</span></span>
* <span data-ttu-id="67d2b-129">計算</span><span class="sxs-lookup"><span data-stu-id="67d2b-129">Compute</span></span>
    * <span data-ttu-id="67d2b-130">儲存體帳戶類型支援映像磁碟：</span><span class="sxs-lookup"><span data-stu-id="67d2b-130">Storage account type support for Image disk:</span></span>
        - <span data-ttu-id="67d2b-131">「StorageAccountType」參數已加入 Set-AzureRmImageOsDisk 和 Add-AzureRmImageDataDisk</span><span class="sxs-lookup"><span data-stu-id="67d2b-131">'StorageAccountType' parameter is added to Set-AzureRmImageOsDisk and Add-AzureRmImageDataDisk</span></span>
    * <span data-ttu-id="67d2b-132">採用 Vmss IP 組態的 PrivateIP 和 PublicIP 功能：</span><span class="sxs-lookup"><span data-stu-id="67d2b-132">PrivateIP and PublicIP feature in Vmss Ip Configuration:</span></span>
        - <span data-ttu-id="67d2b-133">「PrivateIPAddressVersion」、「PublicIPAddressConfigurationName」、「PublicIPAddressConfigurationIdleTimeoutInMinutes」、「DnsSetting」名稱已加入 New-AzureRmVmssIpConfig</span><span class="sxs-lookup"><span data-stu-id="67d2b-133">'PrivateIPAddressVersion', 'PublicIPAddressConfigurationName', 'PublicIPAddressConfigurationIdleTimeoutInMinutes', 'DnsSetting' names are added to New-AzureRmVmssIpConfig</span></span>
        - <span data-ttu-id="67d2b-134">指定 IPv4 或 IPv6 的「PrivateIPAddressVersion」參數已加入 New-AzureRmVmssIpConfig</span><span class="sxs-lookup"><span data-stu-id="67d2b-134">'PrivateIPAddressVersion' parameter for specifying IPv4 or IPv6 is added to New-AzureRmVmssIpConfig</span></span>
    * <span data-ttu-id="67d2b-135">效能維護功能：</span><span class="sxs-lookup"><span data-stu-id="67d2b-135">Performance Maintenance feature:</span></span>
        - <span data-ttu-id="67d2b-136">「PerformMaintenance」切換參數已加入 Restart-AzureRmVM。</span><span class="sxs-lookup"><span data-stu-id="67d2b-136">'PerformMaintenance' switch parameter is added to Restart-AzureRmVM.</span></span>
        - <span data-ttu-id="67d2b-137">Get-AzureRmVM -Status 會顯示特定 VM 的效能維護資訊</span><span class="sxs-lookup"><span data-stu-id="67d2b-137">Get-AzureRmVM -Status shows the information of performance maintenance of the given VM</span></span>
    * <span data-ttu-id="67d2b-138">虛擬機器身分識別功能：</span><span class="sxs-lookup"><span data-stu-id="67d2b-138">Virtual Machine Identity feature:</span></span>
        - <span data-ttu-id="67d2b-139">「IdentityType」參數已加入 New-AzureRmVMConfig 和 UpdateAzureRmVM</span><span class="sxs-lookup"><span data-stu-id="67d2b-139">'IdentityType' parameter is added to New-AzureRmVMConfig and UpdateAzureRmVM</span></span>
        - <span data-ttu-id="67d2b-140">Get-AzureRmVM 顯示特定 VM 的身分識別資訊</span><span class="sxs-lookup"><span data-stu-id="67d2b-140">Get-AzureRmVM shows the information of the identity of the given VM</span></span>
    * <span data-ttu-id="67d2b-141">Vmss 身分識別功能：</span><span class="sxs-lookup"><span data-stu-id="67d2b-141">Vmss Identity feature:</span></span>
        - <span data-ttu-id="67d2b-142">「IdentityType」參數已加入 New-AzureRmVmssConfig</span><span class="sxs-lookup"><span data-stu-id="67d2b-142">'IdentityType' parameter is added to to New-AzureRmVmssConfig</span></span>
        - <span data-ttu-id="67d2b-143">Get-AzureRmVmss 顯示特定 Vmss 的身分識別資訊</span><span class="sxs-lookup"><span data-stu-id="67d2b-143">Get-AzureRmVmss shows the information of the identity of the given Vmss</span></span>
    * <span data-ttu-id="67d2b-144">Vmss 開機診斷功能：</span><span class="sxs-lookup"><span data-stu-id="67d2b-144">Vmss Boot Diagnostics feature:</span></span>
        - <span data-ttu-id="67d2b-145">設定 Vmss 物件開機診斷的新 Cmdlet：Set-AzureRmVmssBootDiagnostics</span><span class="sxs-lookup"><span data-stu-id="67d2b-145">New cmdlet for setting boot diagnostics of Vmss object: Set-AzureRmVmssBootDiagnostics</span></span>
        - <span data-ttu-id="67d2b-146">「BootDiagnostic」參數已加入 New-AzureRmVmssConfig</span><span class="sxs-lookup"><span data-stu-id="67d2b-146">'BootDiagnostic' parameter is added to New-AzureRmVmssConfig</span></span>
    * <span data-ttu-id="67d2b-147">Vmss LicenseType 功能：</span><span class="sxs-lookup"><span data-stu-id="67d2b-147">Vmss LicenseType feature:</span></span>
        - <span data-ttu-id="67d2b-148">「LicenseType」參數已加入 New-AzureRmVmssConfig</span><span class="sxs-lookup"><span data-stu-id="67d2b-148">'LicenseType' parameter is added to New-AzureRmVmssConfig</span></span>
    * <span data-ttu-id="67d2b-149">RecoveryPolicyMode 支援：</span><span class="sxs-lookup"><span data-stu-id="67d2b-149">RecoveryPolicyMode support:</span></span>
        - <span data-ttu-id="67d2b-150">「RecoveryPolicyMode」參數已加入 New-AzureRmVmssConfig</span><span class="sxs-lookup"><span data-stu-id="67d2b-150">'RecoveryPolicyMode' paramter is added to New-AzureRmVmssConfig</span></span>
    * <span data-ttu-id="67d2b-151">計算資源 Sku 功能：</span><span class="sxs-lookup"><span data-stu-id="67d2b-151">Compute Resource Sku feature:</span></span>
        - <span data-ttu-id="67d2b-152">新 Cmdlet「Get-AzureRmComputeResourceSku」列出所有計算資源 sku</span><span class="sxs-lookup"><span data-stu-id="67d2b-152">New cmdlet 'Get-AzureRmComputeResourceSku' list all compute resource skus</span></span>
* <span data-ttu-id="67d2b-153">DataFactories</span><span class="sxs-lookup"><span data-stu-id="67d2b-153">DataFactories</span></span>
    * <span data-ttu-id="67d2b-154">取代 New-AzureRmDataFactoryGatewayKey</span><span class="sxs-lookup"><span data-stu-id="67d2b-154">Deprecate New-AzureRmDataFactoryGatewayKey</span></span>
    * <span data-ttu-id="67d2b-155">加入 New-AzureRmDataFactoryGatewayAuthKey 和 Get-AzureRmDataFactoryGatewayAuthKey，推出閘道驗證金鑰功能</span><span class="sxs-lookup"><span data-stu-id="67d2b-155">Introduce gateway auth key feature by adding New-AzureRmDataFactoryGatewayAuthKey and Get-AzureRmDataFactoryGatewayAuthKey</span></span>
* <span data-ttu-id="67d2b-156">DataLakeAnalytics</span><span class="sxs-lookup"><span data-stu-id="67d2b-156">DataLakeAnalytics</span></span>
    * <span data-ttu-id="67d2b-157">透過下列命令，加入計算原則 CRUD 支援：</span><span class="sxs-lookup"><span data-stu-id="67d2b-157">Add support for Compute Policy CRUD through the following commands:</span></span>
        - <span data-ttu-id="67d2b-158">New-AzureRMDataLakeAnalyticsComputePolicy</span><span class="sxs-lookup"><span data-stu-id="67d2b-158">New-AzureRMDataLakeAnalyticsComputePolicy</span></span>
        - <span data-ttu-id="67d2b-159">Get-AzureRMDataLakeAnalyticsComputePolicy</span><span class="sxs-lookup"><span data-stu-id="67d2b-159">Get-AzureRMDataLakeAnalyticsComputePolicy</span></span>
        - <span data-ttu-id="67d2b-160">Remove-AzureRMDataLakeAnalyticsComputePolicy</span><span class="sxs-lookup"><span data-stu-id="67d2b-160">Remove-AzureRMDataLakeAnalyticsComputePolicy</span></span>
        - <span data-ttu-id="67d2b-161">Update-AzureRMDataLakeAnalyticsComputePolicy</span><span class="sxs-lookup"><span data-stu-id="67d2b-161">Update-AzureRMDataLakeAnalyticsComputePolicy</span></span>
    * <span data-ttu-id="67d2b-162">新增支援作業關係中繼資料，協助處理週期性作業和作業流程。</span><span class="sxs-lookup"><span data-stu-id="67d2b-162">Add support for job relationship metadata for help with recurring jobs and job pipelines.</span></span> <span data-ttu-id="67d2b-163">已更新或新增下列命令：</span><span class="sxs-lookup"><span data-stu-id="67d2b-163">The following commands were updated or added:</span></span>
        - <span data-ttu-id="67d2b-164">Submit-AzureRMDataLakeAnalyticsJob</span><span class="sxs-lookup"><span data-stu-id="67d2b-164">Submit-AzureRMDataLakeAnalyticsJob</span></span>
        - <span data-ttu-id="67d2b-165">Get-AzureRMDataLakeAnalyticsJob</span><span class="sxs-lookup"><span data-stu-id="67d2b-165">Get-AzureRMDataLakeAnalyticsJob</span></span>
        - <span data-ttu-id="67d2b-166">Get-AzureRMDataLakeAnalyticsJobRecurrence</span><span class="sxs-lookup"><span data-stu-id="67d2b-166">Get-AzureRMDataLakeAnalyticsJobRecurrence</span></span>
        - <span data-ttu-id="67d2b-167">Get-AzureRMDataLakeAnalyticsJobPipeline</span><span class="sxs-lookup"><span data-stu-id="67d2b-167">Get-AzureRMDataLakeAnalyticsJobPipeline</span></span>
    * <span data-ttu-id="67d2b-168">針對作業和目錄 API 更新 Token 對象，以使用正確的 Data Lake 特定對象，而非 Azure 資源對象。</span><span class="sxs-lookup"><span data-stu-id="67d2b-168">Updated the token audience for job and catalog APIs to use the correct Data Lake specific audience instead of the Azure Resource audience.</span></span>
* <span data-ttu-id="67d2b-169">DataLakeStore</span><span class="sxs-lookup"><span data-stu-id="67d2b-169">DataLakeStore</span></span>
    * <span data-ttu-id="67d2b-170">新增支援在 Set-AzureRMDataLakeStoreAccount Cmdlet 由使用者管理 KeyVault 金鑰輪替</span><span class="sxs-lookup"><span data-stu-id="67d2b-170">Added support for user managed KeyVault key rotations in the Set-AzureRMDataLakeStoreAccount cmdlet</span></span>
    * <span data-ttu-id="67d2b-171">新增生活品質更新，在新增使用者管理的 KeyVault 或金鑰輪替時，自動觸發 `enableKeyVault` 呼叫。</span><span class="sxs-lookup"><span data-stu-id="67d2b-171">Added a quality of life update to automatically trigger an `enableKeyVault` call when a user managed KeyVault is added or a key is rotated.</span></span>
    * <span data-ttu-id="67d2b-172">針對作業和目錄 API 更新 Token 對象，以使用正確的 Data Lake 特定對象，而非 Azure 資源對象。</span><span class="sxs-lookup"><span data-stu-id="67d2b-172">Updated the token audience for job and catalog APIs to use the correct Data Lake specific audience instead of the Azure Resource audience.</span></span>
    * <span data-ttu-id="67d2b-173">已修正錯誤，該錯誤會使用下列 Cmdlet 限制建立/附加檔案的大小：</span><span class="sxs-lookup"><span data-stu-id="67d2b-173">Fixed a bug limiting the size of files created/appended using the following cmdlets:</span></span>
        - <span data-ttu-id="67d2b-174">New-AzureRmDataLakeStoreItem</span><span class="sxs-lookup"><span data-stu-id="67d2b-174">New-AzureRmDataLakeStoreItem</span></span>
        - <span data-ttu-id="67d2b-175">Add-AzureRmDataLakeStoreItemContent</span><span class="sxs-lookup"><span data-stu-id="67d2b-175">Add-AzureRmDataLakeStoreItemContent</span></span>
* <span data-ttu-id="67d2b-176">Dns</span><span class="sxs-lookup"><span data-stu-id="67d2b-176">Dns</span></span>
    * <span data-ttu-id="67d2b-177">針對 Get-AzureRmDnsZone 修正管線情節中的錯誤</span><span class="sxs-lookup"><span data-stu-id="67d2b-177">Fix bug in the piping scenario for Get-AzureRmDnsZone</span></span>
        - <span data-ttu-id="67d2b-178">詳細資訊可以在這裡找到 (英文)：https://github.com/Azure/azure-powershell/issues/4203</span><span class="sxs-lookup"><span data-stu-id="67d2b-178">More information can be found here: https://github.com/Azure/azure-powershell/issues/4203</span></span>
* <span data-ttu-id="67d2b-179">HDInsight</span><span class="sxs-lookup"><span data-stu-id="67d2b-179">HDInsight</span></span>
    * <span data-ttu-id="67d2b-180">新增支援以啟用/停用 Operations Management Suite (OMS)</span><span class="sxs-lookup"><span data-stu-id="67d2b-180">Added support to enable / disable Operations Management Suite(OMS)</span></span>
    * <span data-ttu-id="67d2b-181">新的 Cmdlet</span><span class="sxs-lookup"><span data-stu-id="67d2b-181">New cmdlets</span></span>
        - <span data-ttu-id="67d2b-182">Enable-AzureRmHDInsightOperationsManagementSuite</span><span class="sxs-lookup"><span data-stu-id="67d2b-182">Enable-AzureRmHDInsightOperationsManagementSuite</span></span>
        - <span data-ttu-id="67d2b-183">Disable-AzureRmHDInsightOperationsManagementSuite</span><span class="sxs-lookup"><span data-stu-id="67d2b-183">Disable-AzureRmHDInsightOperationsManagementSuite</span></span>
        - <span data-ttu-id="67d2b-184">Get-AzureRmHDInsightOperationsManagementSuite</span><span class="sxs-lookup"><span data-stu-id="67d2b-184">Get-AzureRmHDInsightOperationsManagementSuite</span></span>
    * <span data-ttu-id="67d2b-185">加入新的參數，將 Spark 自訂設定設為 Add-AzureRmHDInsightConfigValues</span><span class="sxs-lookup"><span data-stu-id="67d2b-185">Add new parameters to set Spark custom configurations to Add-AzureRmHDInsightConfigValues</span></span>
        - <span data-ttu-id="67d2b-186">Spark 1.6 適用的參數 SparkDefaults 和 SparkThriftConf</span><span class="sxs-lookup"><span data-stu-id="67d2b-186">Parameters SparkDefaults and SparkThriftConf for Spark 1.6</span></span>
        - <span data-ttu-id="67d2b-187">Spark 2.0 適用的參數 Spark2Defaults 和 Spark2ThriftConf</span><span class="sxs-lookup"><span data-stu-id="67d2b-187">Parameters Spark2Defaults and Spark2ThriftConf for Spark 2.0</span></span>
* <span data-ttu-id="67d2b-188">深入解析</span><span class="sxs-lookup"><span data-stu-id="67d2b-188">Insights</span></span>
    * <span data-ttu-id="67d2b-189">問題 #4215 (變更要求) 移除 Get-AzureRmLog Cmdlet 的 15 天期間限制。</span><span class="sxs-lookup"><span data-stu-id="67d2b-189">Issue #4215 (change request) remove the 15 days limit in the time window for the Get-AzureRmLog cmdlet.</span></span> <span data-ttu-id="67d2b-190">此外亦小幅變更了單元測試名稱。</span><span class="sxs-lookup"><span data-stu-id="67d2b-190">Also minor changes to the unit test names.</span></span>
    * <span data-ttu-id="67d2b-191">已針對 Get-AzureRmLog 修正問題 #3957</span><span class="sxs-lookup"><span data-stu-id="67d2b-191">Issue #3957 fixed for Get-AzureRmLog</span></span>
        - <span data-ttu-id="67d2b-192">問題 #1：後端傳回的記錄，每頁 200 筆，透過接續 Token 連結下一頁。</span><span class="sxs-lookup"><span data-stu-id="67d2b-192">Issue #1: The backend returns the records in pages of 200 records each, linked by the continuation token to the next page.</span></span> <span data-ttu-id="67d2b-193">客戶會看到 Cmdlet 只傳回 200 筆記錄，但確知應還有更多記錄。</span><span class="sxs-lookup"><span data-stu-id="67d2b-193">The customers were seeing the cmdlet returning only 200 records when they knew there were more.</span></span> <span data-ttu-id="67d2b-194">除非 MaxEvents 小於 200，否則不論客戶設定的值為何，都會發生這種情形。</span><span class="sxs-lookup"><span data-stu-id="67d2b-194">This was happening regardless of the value they set for MaxEvents, unless that value was less than 200.</span></span>
        - <span data-ttu-id="67d2b-195">問題 #2：文件包含不正確的 Cmdlet 相關資料，例如：預設期間是 1 小時。</span><span class="sxs-lookup"><span data-stu-id="67d2b-195">Issue #2: The documentation contained incorrect data about this cmdlet, e.g.: the default timewindow was 1 hour.</span></span>
        - <span data-ttu-id="67d2b-196">修正 #1：Cmdlet 現在會遵循後端傳回的接續 Token，直到達到 MaxEvents 或集合的結束為止。</span><span class="sxs-lookup"><span data-stu-id="67d2b-196">Fix #1: The cmdlet now follows the continuation token returned by the backend until it reaches MaxEvents or the end of the set.</span></span><br><span data-ttu-id="67d2b-197">MaxEvents 的預設值為 1000，最大值為 100000。</span><span class="sxs-lookup"><span data-stu-id="67d2b-197">The default value for MaxEvents is 1000 and its maximum is 100000.</span></span> <span data-ttu-id="67d2b-198">凡 MaxEvents 值小於 1 都會忽略，並改為使用預設值。</span><span class="sxs-lookup"><span data-stu-id="67d2b-198">Any value for MaxEvents that is less than 1 is ignored and the default is used instead.</span></span> <span data-ttu-id="67d2b-199">這些值和行為並未變更，現在都已正確地記錄。</span><span class="sxs-lookup"><span data-stu-id="67d2b-199">These values and behavior did not change, now they are correctly documented.</span></span><br><span data-ttu-id="67d2b-200">由於 Cmdlet 名稱未說明相關事件，而只提供了記錄檔，因此已新增 MaxEvents 別名 -MaxRecords-。</span><span class="sxs-lookup"><span data-stu-id="67d2b-200">An alias for MaxEvents has been added -MaxRecords- since the name of the cmdlet does not speak about events anymore, but only about Logs.</span></span>
        - <span data-ttu-id="67d2b-201">修正 #2：文件包含正確及更詳細的資訊：新的別名、正確的期間、正確的預設值、最小值和最大值。</span><span class="sxs-lookup"><span data-stu-id="67d2b-201">Fix #2: The documentation contains correct and more detailed information: new alias, correct time window, correct default, minimum, and maximum values.</span></span>
* <span data-ttu-id="67d2b-202">KeyVault</span><span class="sxs-lookup"><span data-stu-id="67d2b-202">KeyVault</span></span>
    * <span data-ttu-id="67d2b-203">將 -UserPrincipalName 指定到 Set-AzureRMKeyVaultAccessPolicy 和 Remove-AzureRMKeyVaultAccessPolicy Cmdlet 時，請從目錄查詢中移除電子郵件地址。</span><span class="sxs-lookup"><span data-stu-id="67d2b-203">Remove email address from the directory query when -UserPrincipalName is specified to the Set-AzureRMKeyVaultAccessPolicy and Remove-AzureRMKeyVaultAccessPolicy cmdlets.</span></span>
      - <span data-ttu-id="67d2b-204">兩個 Cmdlet 現在會有適當的 -EmailAddress 參數，在需要查詢電子郵件地址時可供使用，而不使用 -UserPrincipalName 參數。</span><span class="sxs-lookup"><span data-stu-id="67d2b-204">Both Cmdlets now have an -EmailAddress parameter that can be used instead of the -UserPrincipalName parameter when querying for email address is appropriate.</span></span>  <span data-ttu-id="67d2b-205">如果目錄中有多個相符的電子郵件地址，則此 Cmdlet 的電子郵件地址將會失效。</span><span class="sxs-lookup"><span data-stu-id="67d2b-205">If there are more than one matching email addresses in the directory then the Cmdlet will fail.</span></span>
* <span data-ttu-id="67d2b-206">網路</span><span class="sxs-lookup"><span data-stu-id="67d2b-206">Network</span></span>
    * <span data-ttu-id="67d2b-207">New-AzureRmIpsecPolicy：SALifeTimeSeconds 和 SADataSizeKilobytes 不再是必要參數</span><span class="sxs-lookup"><span data-stu-id="67d2b-207">New-AzureRmIpsecPolicy: SALifeTimeSeconds and SADataSizeKilobytes are no longer mandatory parameters</span></span>
        - <span data-ttu-id="67d2b-208">SALifeTimeSeconds 預設值為 27000 秒</span><span class="sxs-lookup"><span data-stu-id="67d2b-208">SALifeTimeSeconds defaults to 27000 seconds</span></span>
        - <span data-ttu-id="67d2b-209">SADataSizeKilobytes 預設值為 102400000 KB</span><span class="sxs-lookup"><span data-stu-id="67d2b-209">SADataSizeKilobytes defaults to 102400000 KB</span></span>
    * <span data-ttu-id="67d2b-210">使用 ssl 原則，並在應用程式閘道列出所有 ssl 選項 api，以新增支援自訂加密套件設定</span><span class="sxs-lookup"><span data-stu-id="67d2b-210">Added support for custom cipher suite configuration using ssl policy and listing all ssl options api in Application Gateway</span></span>
        - <span data-ttu-id="67d2b-211">新增選擇性參數 -PolicyType、-PolicyName、-MinProtocolVersion、-Ciphersuite</span><span class="sxs-lookup"><span data-stu-id="67d2b-211">Added optional parameter -PolicyType, -PolicyName, -MinProtocolVersion, -Ciphersuite</span></span>
            - <span data-ttu-id="67d2b-212">Add-AzureRmApplicationGatewaySslPolicy</span><span class="sxs-lookup"><span data-stu-id="67d2b-212">Add-AzureRmApplicationGatewaySslPolicy</span></span>
            - <span data-ttu-id="67d2b-213">New-AzureRmApplicationGatewaySslPolicy</span><span class="sxs-lookup"><span data-stu-id="67d2b-213">New-AzureRmApplicationGatewaySslPolicy</span></span>
            - <span data-ttu-id="67d2b-214">Set-AzureRmApplicationGatewaySslPolicy</span><span class="sxs-lookup"><span data-stu-id="67d2b-214">Set-AzureRmApplicationGatewaySslPolicy</span></span>
        - <span data-ttu-id="67d2b-215">新增 Get-AzureRmApplicationGatewayAvailableSslOptions (別名：List-AzureRmApplicationGatewayAvailableSslOptions)</span><span class="sxs-lookup"><span data-stu-id="67d2b-215">Added Get-AzureRmApplicationGatewayAvailableSslOptions (Alias: List-AzureRmApplicationGatewayAvailableSslOptions)</span></span>
        - <span data-ttu-id="67d2b-216">新增 Get AzureRmApplicationGatewaySslPredefinedPolicy (別名：List-AzureRmApplicationGatewaySslPredefinedPolicy)</span><span class="sxs-lookup"><span data-stu-id="67d2b-216">Added Get-AzureRmApplicationGatewaySslPredefinedPolicy (Alias: List-AzureRmApplicationGatewaySslPredefinedPolicy)</span></span>
    * <span data-ttu-id="67d2b-217">應用程式閘道中新增重新導向支援</span><span class="sxs-lookup"><span data-stu-id="67d2b-217">Added redirect support in Application Gateway</span></span>
        - <span data-ttu-id="67d2b-218">新增 Add-AzureRmApplicationGatewayRedirectConfiguration</span><span class="sxs-lookup"><span data-stu-id="67d2b-218">Added Add-AzureRmApplicationGatewayRedirectConfiguration</span></span>
        - <span data-ttu-id="67d2b-219">新增 Get-AzureRmApplicationGatewayRedirectConfiguration</span><span class="sxs-lookup"><span data-stu-id="67d2b-219">Added Get-AzureRmApplicationGatewayRedirectConfiguration</span></span>
        - <span data-ttu-id="67d2b-220">新增 New-AzureRmApplicationGatewayRedirectConfiguration</span><span class="sxs-lookup"><span data-stu-id="67d2b-220">Added New-AzureRmApplicationGatewayRedirectConfiguration</span></span>
        - <span data-ttu-id="67d2b-221">新增 Remove-AzureRmApplicationGatewayRedirectConfiguration</span><span class="sxs-lookup"><span data-stu-id="67d2b-221">Added Remove-AzureRmApplicationGatewayRedirectConfiguration</span></span>
        - <span data-ttu-id="67d2b-222">新增 Set-AzureRmApplicationGatewayRedirectConfiguration</span><span class="sxs-lookup"><span data-stu-id="67d2b-222">Added Set-AzureRmApplicationGatewayRedirectConfiguration</span></span>
        - <span data-ttu-id="67d2b-223">新增選擇性參數 -RedirectConfiguration</span><span class="sxs-lookup"><span data-stu-id="67d2b-223">Added optional parameter -RedirectConfiguration</span></span>
            - <span data-ttu-id="67d2b-224">Add-AzureRmApplicationGatewayRequestRoutingRule</span><span class="sxs-lookup"><span data-stu-id="67d2b-224">Add-AzureRmApplicationGatewayRequestRoutingRule</span></span>
            - <span data-ttu-id="67d2b-225">New-AzureRmApplicationGatewayRequestRoutingRule</span><span class="sxs-lookup"><span data-stu-id="67d2b-225">New-AzureRmApplicationGatewayRequestRoutingRule</span></span>
            - <span data-ttu-id="67d2b-226">Set-AzureRmApplicationGatewayRequestRoutingRule</span><span class="sxs-lookup"><span data-stu-id="67d2b-226">Set-AzureRmApplicationGatewayRequestRoutingRule</span></span>
        - <span data-ttu-id="67d2b-227">新增選擇性參數-DefaultRedirectConfiguration</span><span class="sxs-lookup"><span data-stu-id="67d2b-227">Added optional parameter -DefaultRedirectConfiguration</span></span>
            - <span data-ttu-id="67d2b-228">Add-AzureRmApplicationGatewayUrlPathMapConfig</span><span class="sxs-lookup"><span data-stu-id="67d2b-228">Add-AzureRmApplicationGatewayUrlPathMapConfig</span></span>
            - <span data-ttu-id="67d2b-229">New-AzureRmApplicationGatewayUrlPathMapConfig</span><span class="sxs-lookup"><span data-stu-id="67d2b-229">New-AzureRmApplicationGatewayUrlPathMapConfig</span></span>
            - <span data-ttu-id="67d2b-230">Set-AzureRmApplicationGatewayUrlPathMapConfig</span><span class="sxs-lookup"><span data-stu-id="67d2b-230">Set-AzureRmApplicationGatewayUrlPathMapConfig</span></span>
        - <span data-ttu-id="67d2b-231">新增選擇性參數 -RedirectConfiguration</span><span class="sxs-lookup"><span data-stu-id="67d2b-231">Added optional parameter -RedirectConfiguration</span></span>
            - <span data-ttu-id="67d2b-232">Add-AzureRmApplicationGatewayPathRuleConfig</span><span class="sxs-lookup"><span data-stu-id="67d2b-232">Add-AzureRmApplicationGatewayPathRuleConfig</span></span>
            - <span data-ttu-id="67d2b-233">New-AzureRmApplicationGatewayPathRuleConfig</span><span class="sxs-lookup"><span data-stu-id="67d2b-233">New-AzureRmApplicationGatewayPathRuleConfig</span></span>
            - <span data-ttu-id="67d2b-234">Set-AzureRmApplicationGatewayPathRuleConfig</span><span class="sxs-lookup"><span data-stu-id="67d2b-234">Set-AzureRmApplicationGatewayPathRuleConfig</span></span>
        - <span data-ttu-id="67d2b-235">新增選擇性參數 -RedirectConfigurations</span><span class="sxs-lookup"><span data-stu-id="67d2b-235">Added optional parameter -RedirectConfigurations</span></span>
            - <span data-ttu-id="67d2b-236">New-AzureRmApplicationGateway</span><span class="sxs-lookup"><span data-stu-id="67d2b-236">New-AzureRmApplicationGateway</span></span>
            - <span data-ttu-id="67d2b-237">Set-AzureRmApplicationGateway</span><span class="sxs-lookup"><span data-stu-id="67d2b-237">Set-AzureRmApplicationGateway</span></span>
    * <span data-ttu-id="67d2b-238">在應用程式閘道中新增支援 azure 網站</span><span class="sxs-lookup"><span data-stu-id="67d2b-238">Added support for azure websites in Application Gateway</span></span>
        - <span data-ttu-id="67d2b-239">新增 New-AzureRmApplicationGatewayProbeHealthResponseMatch</span><span class="sxs-lookup"><span data-stu-id="67d2b-239">Added New-AzureRmApplicationGatewayProbeHealthResponseMatch</span></span>
        - <span data-ttu-id="67d2b-240">新增選擇性參數 -PickHostNameFromBackendHttpSettings、-MinServers、-Match</span><span class="sxs-lookup"><span data-stu-id="67d2b-240">Added optional parameters -PickHostNameFromBackendHttpSettings, -MinServers, -Match</span></span>
            - <span data-ttu-id="67d2b-241">Add-AzureRmApplicationGatewayProbeConfig</span><span class="sxs-lookup"><span data-stu-id="67d2b-241">Add-AzureRmApplicationGatewayProbeConfig</span></span>
            - <span data-ttu-id="67d2b-242">New-AzureRmApplicationGatewayProbeConfig</span><span class="sxs-lookup"><span data-stu-id="67d2b-242">New-AzureRmApplicationGatewayProbeConfig</span></span>
            - <span data-ttu-id="67d2b-243">Set-AzureRmApplicationGatewayProbeConfig</span><span class="sxs-lookup"><span data-stu-id="67d2b-243">Set-AzureRmApplicationGatewayProbeConfig</span></span>
        - <span data-ttu-id="67d2b-244">新增選擇性參數 -PickHostNameFromBackendAddress、-AffinityCookieName、-ProbeEnabled、-Path</span><span class="sxs-lookup"><span data-stu-id="67d2b-244">Added optional parameters -PickHostNameFromBackendAddress, -AffinityCookieName, -ProbeEnabled, -Path</span></span>
            - <span data-ttu-id="67d2b-245">Add-AzureRmApplicationGatewayBackendHttpSettings</span><span class="sxs-lookup"><span data-stu-id="67d2b-245">Add-AzureRmApplicationGatewayBackendHttpSettings</span></span>
            - <span data-ttu-id="67d2b-246">New-AzureRmApplicationGatewayBackendHttpSettings</span><span class="sxs-lookup"><span data-stu-id="67d2b-246">New-AzureRmApplicationGatewayBackendHttpSettings</span></span>
            - <span data-ttu-id="67d2b-247">Set-AzureRmApplicationGatewayBackendHttpSettings</span><span class="sxs-lookup"><span data-stu-id="67d2b-247">Set-AzureRmApplicationGatewayBackendHttpSettings</span></span>
    * <span data-ttu-id="67d2b-248">更新 Get-AzureRmPublicIPaddress，以擷取透過 VM 擴展集建立的 publicipaddress 資源</span><span class="sxs-lookup"><span data-stu-id="67d2b-248">Update Get-AzureRmPublicIPaddress to retrieve publicipaddress resources created via VM Scale Set</span></span>
    * <span data-ttu-id="67d2b-249">新增 Cmdlet 取得虛擬網路的目前使用情形</span><span class="sxs-lookup"><span data-stu-id="67d2b-249">Added cmdlet to get virtual network current usage</span></span>
        - <span data-ttu-id="67d2b-250">Get-AzureRmVirtualNetworkUsageList</span><span class="sxs-lookup"><span data-stu-id="67d2b-250">Get-AzureRmVirtualNetworkUsageList</span></span>
* <span data-ttu-id="67d2b-251">設定檔</span><span class="sxs-lookup"><span data-stu-id="67d2b-251">Profile</span></span>
    * <span data-ttu-id="67d2b-252">修正使用 Import-AzureRmContext 或 Save-AzureRmContext 時的錯誤</span><span class="sxs-lookup"><span data-stu-id="67d2b-252">Fixed error when using Import-AzureRmContext or Save-AzureRmContext</span></span>
        - <span data-ttu-id="67d2b-253">詳細資訊可以在本問題找到 (英文)：https://github.com/Azure/azure-powershell/issues/3954</span><span class="sxs-lookup"><span data-stu-id="67d2b-253">More information can be found in this issue: https://github.com/Azure/azure-powershell/issues/3954</span></span>
* <span data-ttu-id="67d2b-254">RecoveryServices.SiteRecovery</span><span class="sxs-lookup"><span data-stu-id="67d2b-254">RecoveryServices.SiteRecovery</span></span>
    * <span data-ttu-id="67d2b-255">推出新的 Azure Site Recovery 作業模組。</span><span class="sxs-lookup"><span data-stu-id="67d2b-255">Introducing a new module for Azure Site Recovery operations.</span></span>
        - <span data-ttu-id="67d2b-256">所有 Cmdlet 的開頭均為 AzureRmRecoveryServicesAsr*</span><span class="sxs-lookup"><span data-stu-id="67d2b-256">All cmdlets begin with AzureRmRecoveryServicesAsr*</span></span>
* <span data-ttu-id="67d2b-257">Sql</span><span class="sxs-lookup"><span data-stu-id="67d2b-257">Sql</span></span>
    * <span data-ttu-id="67d2b-258">將資料同步 PowerShell Cmdlet 加入 AzureRM.Sql</span><span class="sxs-lookup"><span data-stu-id="67d2b-258">Add Data Sync PowerShell Cmdlets to AzureRM.Sql</span></span>
    * <span data-ttu-id="67d2b-259">更新 AzureRmSqlServer Cmdlet 以使用新的 REST API 版本，避免建立伺服器時發生逾時。</span><span class="sxs-lookup"><span data-stu-id="67d2b-259">Updated AzureRmSqlServer cmdlets to use new REST API version that avoids timeouts when creating server.</span></span>
    * <span data-ttu-id="67d2b-260">已取代的伺服器升級 Cmdlet，因為舊的伺服器版本 (2.0) 已經不存在。</span><span class="sxs-lookup"><span data-stu-id="67d2b-260">Deprecated server upgrade cmdlets because the old server version (2.0) no longer exists.</span></span>
    * <span data-ttu-id="67d2b-261">將新的選擇性切換參數「AssignIdentity」加入 New-AzureRmSqlServer 和 Set-AzureRmSqlServer Cmdlet，以支援佈建 SQL 伺服器資源的資源身分識別</span><span class="sxs-lookup"><span data-stu-id="67d2b-261">Add new optional switch paramter "AssignIdentity" to New-AzureRmSqlServer and Set-AzureRmSqlServer cmdlets to support provisioning of a resource identity for the SQL server resource</span></span>
    * <span data-ttu-id="67d2b-262">參數 ResourceGroupName 現在是 Get-AzureRmSqlServer 的選擇性項目</span><span class="sxs-lookup"><span data-stu-id="67d2b-262">The parameter ResourceGroupName is now optional for Get-AzureRmSqlServer</span></span>
        - <span data-ttu-id="67d2b-263">詳細資訊可在下列問題中找到 (英文)：https://github.com/Azure/azure-powershell/issues/635</span><span class="sxs-lookup"><span data-stu-id="67d2b-263">More information can be found in the following issue: https://github.com/Azure/azure-powershell/issues/635</span></span>
* <span data-ttu-id="67d2b-264">ExpressRoute 的 ServiceManagement：</span><span class="sxs-lookup"><span data-stu-id="67d2b-264">ServiceManagement   For ExpressRoute:</span></span>
    * <span data-ttu-id="67d2b-265">更新 New-AzureBgpPeering Cmdlet，新增下列選項：</span><span class="sxs-lookup"><span data-stu-id="67d2b-265">Updated New-AzureBgpPeering cmdlet to add following new options :</span></span>
        - <span data-ttu-id="67d2b-266">PeerAddressType：可指定「IPv4」或「IPv6」的值，以建立對應位址系列類型的 BGP 對等互連</span><span class="sxs-lookup"><span data-stu-id="67d2b-266">PeerAddressType : Values of "IPv4" or "IPv6" can be specified to create a BGP Peering of the corresponding address family type</span></span>
    * <span data-ttu-id="67d2b-267">更新 Set-AzureBgpPeering Cmdlet，新增下列選項：</span><span class="sxs-lookup"><span data-stu-id="67d2b-267">Updated Set-AzureBgpPeering cmdlet to add following new options :</span></span>
        - <span data-ttu-id="67d2b-268">PeerAddressType：可指定「IPv4」或「IPv6」的值，以更新對應位址系列類型的 BGP 對等互連</span><span class="sxs-lookup"><span data-stu-id="67d2b-268">PeerAddressType : Values of "IPv4" or "IPv6" can be specified to update BGP Peering of the corresponding address family type</span></span>
    * <span data-ttu-id="67d2b-269">更新 Remove-AzureBgpPeering Cmdlet，新增下列選項：</span><span class="sxs-lookup"><span data-stu-id="67d2b-269">Updated Remove-AzureBgpPeering cmdlet to add following new options :</span></span>
        - <span data-ttu-id="67d2b-270">PeerAddressType：可指定「IPv4」、「IPv6」或所有的值，以移除對應位址系列類型或所有的 BGP 對等互連</span><span class="sxs-lookup"><span data-stu-id="67d2b-270">PeerAddressType : Values of "IPv4", "IPv6" or All can be specified to remove BGP Peering of the corresponding address family type or all of them</span></span>

## <a name="20170607---version-410"></a><span data-ttu-id="67d2b-271">2017.06.07 - 版本 4.1.0</span><span class="sxs-lookup"><span data-stu-id="67d2b-271">2017.06.07 - Version 4.1.0</span></span>
* <span data-ttu-id="67d2b-272">AnalysisServices</span><span class="sxs-lookup"><span data-stu-id="67d2b-272">AnalysisServices</span></span>
    * <span data-ttu-id="67d2b-273">新增的 SKU：B1、B2、S0</span><span class="sxs-lookup"><span data-stu-id="67d2b-273">New SKUs added: B1, B2, S0</span></span>
    * <span data-ttu-id="67d2b-274">新增相應增加/減少支援</span><span class="sxs-lookup"><span data-stu-id="67d2b-274">Scale up/down support added</span></span>
* <span data-ttu-id="67d2b-275">CognitiveServices</span><span class="sxs-lookup"><span data-stu-id="67d2b-275">CognitiveServices</span></span>
    * <span data-ttu-id="67d2b-276">更新在建立辨識服務資源時的授權合約詳細顯示內容</span><span class="sxs-lookup"><span data-stu-id="67d2b-276">Update detailed display of license agreements when creating Cognitive Services resources</span></span>
* <span data-ttu-id="67d2b-277">計算</span><span class="sxs-lookup"><span data-stu-id="67d2b-277">Compute</span></span>
    * <span data-ttu-id="67d2b-278">針對具有多個受控磁碟的虛擬機器，修正 Test-AzureRmVMAEMExtension</span><span class="sxs-lookup"><span data-stu-id="67d2b-278">Fix Test-AzureRmVMAEMExtension for virtual machines with multiple managed disks</span></span>
    * <span data-ttu-id="67d2b-279">更新 Set-AzureRmVMAEMExtension：新增進階受控磁碟的快取資訊</span><span class="sxs-lookup"><span data-stu-id="67d2b-279">Updated Set-AzureRmVMAEMExtension: Add caching information for Premium managed disks</span></span>
    * <span data-ttu-id="67d2b-280">Add-AzureRmVhd：vhd 的大小限制會增加至 4TB。</span><span class="sxs-lookup"><span data-stu-id="67d2b-280">Add-AzureRmVhd: The size limit on vhd is increased to 4TB.</span></span>
    * <span data-ttu-id="67d2b-281">Stop-AzureRmVM：釐清 STayProvisioned 參數的文件</span><span class="sxs-lookup"><span data-stu-id="67d2b-281">Stop-AzureRmVM: Clarify documentation for STayProvisioned parameter</span></span>
    * <span data-ttu-id="67d2b-282">New-AzureRmDiskUpdateConfig</span><span class="sxs-lookup"><span data-stu-id="67d2b-282">New-AzureRmDiskUpdateConfig</span></span>
      * <span data-ttu-id="67d2b-283">已取代的參數 CreateOption、StorageAccountId、ImageReference、SourceUri、SourceResourceId</span><span class="sxs-lookup"><span data-stu-id="67d2b-283">Deprecated parameters CreateOption, StorageAccountId, ImageReference, SourceUri, SourceResourceId</span></span>
    * <span data-ttu-id="67d2b-284">Set-AzureRmDiskUpdateImageReference：已取代的 Cmdlet</span><span class="sxs-lookup"><span data-stu-id="67d2b-284">Set-AzureRmDiskUpdateImageReference: Deprecated cmdlet</span></span>
    * <span data-ttu-id="67d2b-285">New-AzureRmSnapshotUpdateConfig</span><span class="sxs-lookup"><span data-stu-id="67d2b-285">New-AzureRmSnapshotUpdateConfig</span></span>
      * <span data-ttu-id="67d2b-286">已取代的參數 CreateOption、StorageAccountId、ImageReference、SourceUri、SourceResourceId</span><span class="sxs-lookup"><span data-stu-id="67d2b-286">Deprecated parameters CreateOption, StorageAccountId, ImageReference, SourceUri, SourceResourceId</span></span>
    * <span data-ttu-id="67d2b-287">Set-AzureRmSnapshotUpdateImageReference：已取代的 Cmdlet</span><span class="sxs-lookup"><span data-stu-id="67d2b-287">Set-AzureRmSnapshotUpdateImageReference: Deprecated Cmdlet</span></span>
* <span data-ttu-id="67d2b-288">DataLakeStore</span><span class="sxs-lookup"><span data-stu-id="67d2b-288">DataLakeStore</span></span>
    * <span data-ttu-id="67d2b-289">Enable-AzureRmDataLakeStoreKeyVault (Enable-AdlStoreKeyVault)</span><span class="sxs-lookup"><span data-stu-id="67d2b-289">Enable-AzureRmDataLakeStoreKeyVault (Enable-AdlStoreKeyVault)</span></span>
      * <span data-ttu-id="67d2b-290">啟用 DataLake 存放區的 KeyVault 受控加密</span><span class="sxs-lookup"><span data-stu-id="67d2b-290">Enable KeyVault managed encryption for a DataLake Store</span></span>
* <span data-ttu-id="67d2b-291">DevTestLabs</span><span class="sxs-lookup"><span data-stu-id="67d2b-291">DevTestLabs</span></span>
    * <span data-ttu-id="67d2b-292">更新 Cmdlet 以處理目前和更新的 DevTest Labs API 版本。</span><span class="sxs-lookup"><span data-stu-id="67d2b-292">Update cmdlets to work with current and updated DevTest Labs API version.</span></span>
* <span data-ttu-id="67d2b-293">IotHub</span><span class="sxs-lookup"><span data-stu-id="67d2b-293">IotHub</span></span>
    * <span data-ttu-id="67d2b-294">新增 IoTHub Cmdlet 的路由支援</span><span class="sxs-lookup"><span data-stu-id="67d2b-294">Add Routing support for IoTHub cmdlets</span></span>
* <span data-ttu-id="67d2b-295">KeyVault</span><span class="sxs-lookup"><span data-stu-id="67d2b-295">KeyVault</span></span>
  * <span data-ttu-id="67d2b-296">新的 Cmdlet，可支援 KeyVault 受控儲存體帳戶金鑰</span><span class="sxs-lookup"><span data-stu-id="67d2b-296">New Cmdlets to support KeyVault Managed Storage Account Keys</span></span>
    * <span data-ttu-id="67d2b-297">Get-AzureKeyVaultManagedStorageAccount</span><span class="sxs-lookup"><span data-stu-id="67d2b-297">Get-AzureKeyVaultManagedStorageAccount</span></span>
    * <span data-ttu-id="67d2b-298">Add-AzureKeyVaultManagedStorageAccount</span><span class="sxs-lookup"><span data-stu-id="67d2b-298">Add-AzureKeyVaultManagedStorageAccount</span></span>
    * <span data-ttu-id="67d2b-299">Remove-AzureKeyVaultManagedStorageAccount</span><span class="sxs-lookup"><span data-stu-id="67d2b-299">Remove-AzureKeyVaultManagedStorageAccount</span></span>
    * <span data-ttu-id="67d2b-300">Update-AzureKeyVaultManagedStorageAccount</span><span class="sxs-lookup"><span data-stu-id="67d2b-300">Update-AzureKeyVaultManagedStorageAccount</span></span>
    * <span data-ttu-id="67d2b-301">Update-AzureKeyVaultManagedStorageAccountKey</span><span class="sxs-lookup"><span data-stu-id="67d2b-301">Update-AzureKeyVaultManagedStorageAccountKey</span></span>
    * <span data-ttu-id="67d2b-302">Get-AzureKeyVaultManagedStorageSasDefinition</span><span class="sxs-lookup"><span data-stu-id="67d2b-302">Get-AzureKeyVaultManagedStorageSasDefinition</span></span>
    * <span data-ttu-id="67d2b-303">Set-AzureKeyVaultManagedStorageSasDefinition</span><span class="sxs-lookup"><span data-stu-id="67d2b-303">Set-AzureKeyVaultManagedStorageSasDefinition</span></span>
    * <span data-ttu-id="67d2b-304">Remove-AzureKeyVaultManagedStorageSasDefinition</span><span class="sxs-lookup"><span data-stu-id="67d2b-304">Remove-AzureKeyVaultManagedStorageSasDefinition</span></span>
* <span data-ttu-id="67d2b-305">網路</span><span class="sxs-lookup"><span data-stu-id="67d2b-305">Network</span></span>
    * <span data-ttu-id="67d2b-306">Get-AzureRmNetworkUsage：新的 Cmdlet，可顯示網路使用量和容量詳細資料</span><span class="sxs-lookup"><span data-stu-id="67d2b-306">Get-AzureRmNetworkUsage: New cmdlet to show network usage and capacity details</span></span>
    * <span data-ttu-id="67d2b-307">新增 VirtualNetworkGateways 的 GatewaySku 選項</span><span class="sxs-lookup"><span data-stu-id="67d2b-307">Added new GatewaySku options for VirtualNetworkGateways</span></span>
        * <span data-ttu-id="67d2b-308">VpnGw1、VpnGw2、VpnGw3 是針對 Vpn 閘道新增的 Sku</span><span class="sxs-lookup"><span data-stu-id="67d2b-308">VpnGw1, VpnGw2, VpnGw3 are the new Skus added for Vpn gateways</span></span>
    * <span data-ttu-id="67d2b-309">Set-AzureRmNetworkWatcherConfigFlowLog</span><span class="sxs-lookup"><span data-stu-id="67d2b-309">Set-AzureRmNetworkWatcherConfigFlowLog</span></span>
      * <span data-ttu-id="67d2b-310">固定說明範例</span><span class="sxs-lookup"><span data-stu-id="67d2b-310">Fixed  help examples</span></span>
* <span data-ttu-id="67d2b-311">NotificationHubs</span><span class="sxs-lookup"><span data-stu-id="67d2b-311">NotificationHubs</span></span>
    * <span data-ttu-id="67d2b-312">針對新 API 的 NotificationHubs Cmdlet 進行透明更新</span><span class="sxs-lookup"><span data-stu-id="67d2b-312">Transparent Update to NotificationHubs cmdlets for new API</span></span>
* <span data-ttu-id="67d2b-313">設定檔</span><span class="sxs-lookup"><span data-stu-id="67d2b-313">Profile</span></span>
    * <span data-ttu-id="67d2b-314">Resolve-AzureRmError</span><span class="sxs-lookup"><span data-stu-id="67d2b-314">Resolve-AzureRmError</span></span>
      * <span data-ttu-id="67d2b-315">新的 Cmdlet，可顯示詳細錯誤和 Cmdlet 產生的例外狀況，包括伺服器要求/回應資料</span><span class="sxs-lookup"><span data-stu-id="67d2b-315">New cmdlet to show details of errors and exceptions thrown by cmdlets, including server request/response data</span></span>
    * <span data-ttu-id="67d2b-316">Send-Feedback</span><span class="sxs-lookup"><span data-stu-id="67d2b-316">Send-Feedback</span></span>
      * <span data-ttu-id="67d2b-317">啟用傳送意見反應而無須登入</span><span class="sxs-lookup"><span data-stu-id="67d2b-317">Enabled sending feedback without logging in</span></span>
    * <span data-ttu-id="67d2b-318">Get-AzureRmSubscription</span><span class="sxs-lookup"><span data-stu-id="67d2b-318">Get-AzureRmSubscription</span></span>
      * <span data-ttu-id="67d2b-319">修正擷取 CSP 訂用帳戶時的錯誤</span><span class="sxs-lookup"><span data-stu-id="67d2b-319">Fix bug in retreiving CSP subscriptions</span></span>
* <span data-ttu-id="67d2b-320">資源</span><span class="sxs-lookup"><span data-stu-id="67d2b-320">Resources</span></span>
    * <span data-ttu-id="67d2b-321">已修正問題，其中若 roleassignments 的數字大於 1000，Get-AzureRMRoleAssignment 會導致錯誤的要求</span><span class="sxs-lookup"><span data-stu-id="67d2b-321">Fixed issue where Get-AzureRMRoleAssignment would result in a Bad Request if the number of roleassignments where greater than 1000</span></span>
        * <span data-ttu-id="67d2b-322">現在即使要傳回的 roleassignments 大於 1000，使用者仍可使用 Get-AzureRMRoleAssignment</span><span class="sxs-lookup"><span data-stu-id="67d2b-322">Users can now use Get-AzureRMRoleAssignment even if the roleassignments to be returned is greater than 1000</span></span>
* <span data-ttu-id="67d2b-323">Sql</span><span class="sxs-lookup"><span data-stu-id="67d2b-323">Sql</span></span>
    * <span data-ttu-id="67d2b-324">Restore-AzureRmSqlDatabase：更新文件範例</span><span class="sxs-lookup"><span data-stu-id="67d2b-324">Restore-AzureRmSqlDatabase: Update documentation example</span></span>
* <span data-ttu-id="67d2b-325">儲存體</span><span class="sxs-lookup"><span data-stu-id="67d2b-325">Storage</span></span>
    * <span data-ttu-id="67d2b-326">在資源模式的儲存體帳戶 Cmdlet，新增 AssignIdentity 設定支援</span><span class="sxs-lookup"><span data-stu-id="67d2b-326">Add AssignIdentity setting support to resource mode storage account cmdlets</span></span>
        * <span data-ttu-id="67d2b-327">New-AzureRmStorageAccount</span><span class="sxs-lookup"><span data-stu-id="67d2b-327">New-AzureRmStorageAccount</span></span>
        * <span data-ttu-id="67d2b-328">Set-AzureRmStorageAccount</span><span class="sxs-lookup"><span data-stu-id="67d2b-328">Set-AzureRmStorageAccount</span></span>
    * <span data-ttu-id="67d2b-329">在資源模式的儲存體帳戶 Cmdlet，新增客戶金鑰支援</span><span class="sxs-lookup"><span data-stu-id="67d2b-329">Add Customer Key Support to resource mode storage account cmdlets</span></span>
        * <span data-ttu-id="67d2b-330">Set-AzureRmStorageAccount</span><span class="sxs-lookup"><span data-stu-id="67d2b-330">Set-AzureRmStorageAccount</span></span>
        * <span data-ttu-id="67d2b-331">New-AzureRmStorageAccountEncryptionKeySource</span><span class="sxs-lookup"><span data-stu-id="67d2b-331">New-AzureRmStorageAccountEncryptionKeySource</span></span>
* <span data-ttu-id="67d2b-332">TrafficManager</span><span class="sxs-lookup"><span data-stu-id="67d2b-332">TrafficManager</span></span>

    * <span data-ttu-id="67d2b-333">新監視器設定「MonitorIntervalInSeconds」、「MonitorTimeoutInSeconds」、「MonitorToleratedNumberOfFailures」</span><span class="sxs-lookup"><span data-stu-id="67d2b-333">New Monitor settings 'MonitorIntervalInSeconds', 'MonitorTimeoutInSeconds', 'MonitorToleratedNumberOfFailures'</span></span>
    * <span data-ttu-id="67d2b-334">新監視器通訊協定「TCP」</span><span class="sxs-lookup"><span data-stu-id="67d2b-334">New Monitor protocol 'TCP'</span></span>
* <span data-ttu-id="67d2b-335">ServiceManagement</span><span class="sxs-lookup"><span data-stu-id="67d2b-335">ServiceManagement</span></span>
    * <span data-ttu-id="67d2b-336">Add-AzureVhd：vhd 的大小限制會增加至 4TB。</span><span class="sxs-lookup"><span data-stu-id="67d2b-336">Add-AzureVhd: The size limit on vhd is increased to 4TB.</span></span>
    * <span data-ttu-id="67d2b-337">New-AzureBGPPeering：支援 LegacyMode</span><span class="sxs-lookup"><span data-stu-id="67d2b-337">New-AzureBGPPeering: Support LegacyMode</span></span>
* <span data-ttu-id="67d2b-338">Azure.Storage</span><span class="sxs-lookup"><span data-stu-id="67d2b-338">Azure.Storage</span></span>
    * <span data-ttu-id="67d2b-339">針對可接受萬用字元的參數更新說明，並更新 StorageContext 類型</span><span class="sxs-lookup"><span data-stu-id="67d2b-339">Update help for parameters that accept wildcard characters and update StorageContext type</span></span>

## <a name="20170523---version-402"></a><span data-ttu-id="67d2b-340">2017.05.23 - 版本 4.0.2</span><span class="sxs-lookup"><span data-stu-id="67d2b-340">2017.05.23 - Version 4.0.2</span></span>
* <span data-ttu-id="67d2b-341">設定檔</span><span class="sxs-lookup"><span data-stu-id="67d2b-341">Profile</span></span>
    * <span data-ttu-id="67d2b-342">Add-AzureRmAccount</span><span class="sxs-lookup"><span data-stu-id="67d2b-342">Add-AzureRmAccount</span></span>
      * <span data-ttu-id="67d2b-343">新增 `-EnvironmentName` 參數別名，以便回溯相容於 AzureRM.profile 的 2.x 版本</span><span class="sxs-lookup"><span data-stu-id="67d2b-343">Added `-EnvironmentName` parameter alis for backward compatibility with 2.x versions of AzureRM.profile</span></span>

## <a name="20170512---version-401"></a><span data-ttu-id="67d2b-344">2017.05.12 - 版本 4.0.1</span><span class="sxs-lookup"><span data-stu-id="67d2b-344">2017.05.12 - Version 4.0.1</span></span>
 * <span data-ttu-id="67d2b-345">修正離線情況下 New-AzureStorageContext 的問題 (英文)：https://github.com/Azure/azure-powershell/issues/3939</span><span class="sxs-lookup"><span data-stu-id="67d2b-345">Fix issue with New-AzureStorageContext in offline scenarios: https://github.com/Azure/azure-powershell/issues/3939</span></span>

## <a name="20170510---version-400"></a><span data-ttu-id="67d2b-346">2017.05.10 - 版本 4.0.0</span><span class="sxs-lookup"><span data-stu-id="67d2b-346">2017.05.10 - Version 4.0.0</span></span>


* <span data-ttu-id="67d2b-347">此版本包含重大變更。</span><span class="sxs-lookup"><span data-stu-id="67d2b-347">This release contains breaking changes.</span></span> <span data-ttu-id="67d2b-348">如需變更詳細資料和對現有指令碼的影響，請參閱[移轉指南 (英文)](https://aka.ms/azps-migration-guide)。</span><span class="sxs-lookup"><span data-stu-id="67d2b-348">Please see [the migration guide](https://aka.ms/azps-migration-guide) for change details and the impact on existing scripts.</span></span>
* <span data-ttu-id="67d2b-349">ApiManagement</span><span class="sxs-lookup"><span data-stu-id="67d2b-349">ApiManagement</span></span>
  - <span data-ttu-id="67d2b-350">新增在 New-AzureRmApiManagementGroup 中設定外部群組的支援。</span><span class="sxs-lookup"><span data-stu-id="67d2b-350">Added support for configuring external groups in New-AzureRmApiManagementGroup.</span></span>
* <span data-ttu-id="67d2b-351">計費</span><span class="sxs-lookup"><span data-stu-id="67d2b-351">Billing</span></span>
  - <span data-ttu-id="67d2b-352">新的 Get-AzureRmBillingPeriod Cmdlet</span><span class="sxs-lookup"><span data-stu-id="67d2b-352">New Cmdlet Get-AzureRmBillingPeriod</span></span>
    + <span data-ttu-id="67d2b-353">用來擷取 Azure 訂用帳戶計費週期的 Cmdlet。</span><span class="sxs-lookup"><span data-stu-id="67d2b-353">cmdlet to retrieve azure billing periods of the subscription.</span></span>
  - <span data-ttu-id="67d2b-354">更新 Get-AzureRmBillingInvoice Cmdlet</span><span class="sxs-lookup"><span data-stu-id="67d2b-354">Update Cmdlet Get-AzureRmBillingInvoice</span></span>
  - <span data-ttu-id="67d2b-355">新的 BillingPeriodNames 屬性</span><span class="sxs-lookup"><span data-stu-id="67d2b-355">new property BillingPeriodNames</span></span>
  - <span data-ttu-id="67d2b-356">在清單檢視中輸出</span><span class="sxs-lookup"><span data-stu-id="67d2b-356">output in list view</span></span>
* <span data-ttu-id="67d2b-357">計算</span><span class="sxs-lookup"><span data-stu-id="67d2b-357">Compute</span></span>
  - <span data-ttu-id="67d2b-358">已更新 Set-AzureRmVMAEMExtension 和 Test-AzureRmVMAEMExtension Cmdlet，以支援進階受控磁碟</span><span class="sxs-lookup"><span data-stu-id="67d2b-358">Updated Set-AzureRmVMAEMExtension and Test-AzureRmVMAEMExtension cmdlets to support Premium managed disks</span></span>
  - <span data-ttu-id="67d2b-359">適用於 IaaS VM 和失敗時還原的備份加密設定</span><span class="sxs-lookup"><span data-stu-id="67d2b-359">Backup encryption settings for IaaS VMs and restore on failure</span></span>
  - <span data-ttu-id="67d2b-360">ChefServiceInterval 選項現已重新命名為 ChefDaemonInterval。</span><span class="sxs-lookup"><span data-stu-id="67d2b-360">ChefServiceInterval option is renamed to ChefDaemonInterval now.</span></span> <span data-ttu-id="67d2b-361">但舊選項將繼續運作。</span><span class="sxs-lookup"><span data-stu-id="67d2b-361">Old one will continue to work however.</span></span>
  - <span data-ttu-id="67d2b-362">移除 PS VM 物件中重複的 DataDiskNames 和 NetworkInterfaceIDs 屬性。</span><span class="sxs-lookup"><span data-stu-id="67d2b-362">Remove duplicated DataDiskNames and NetworkInterfaceIDs properties from PS VM object.</span></span>
  - <span data-ttu-id="67d2b-363">使個別位於 Remove-AzureRmVMDataDisk 和 Remove-AzureRmVMNetworkInterface 中的 DataDiskNames 和 NetworkInterfaceIDs 參數成為選擇性。</span><span class="sxs-lookup"><span data-stu-id="67d2b-363">Make DataDiskNames and NetworkInterfaceIDs parameters optional in Remove-AzureRmVMDataDisk and Remove-AzureRmVMNetworkInterface, respectively.</span></span>
  - <span data-ttu-id="67d2b-364">修正 Get Cmdlet 傳回清單物件時的管線問題。</span><span class="sxs-lookup"><span data-stu-id="67d2b-364">Fix the piping issue of Get cmdlets when the Get cmdlets return a list object.</span></span>
  - <span data-ttu-id="67d2b-365">已重新命名和 RDFE Cmdlet 衝突的 Cmdlet。</span><span class="sxs-lookup"><span data-stu-id="67d2b-365">Cmdlets that conflicted with RDFE cmdlets have been renamed.</span></span> <span data-ttu-id="67d2b-366">如需詳細資料，請參閱此問題：https://github.com/Azure/azure-powershell/issues/2917</span><span class="sxs-lookup"><span data-stu-id="67d2b-366">See issue https://github.com/Azure/azure-powershell/issues/2917 for more details</span></span>
    + <span data-ttu-id="67d2b-367">`New-AzureVMSqlServerAutoBackupConfig` 已重新命名為 `New-AzureRmVMSqlServerAutoBackupConfig`</span><span class="sxs-lookup"><span data-stu-id="67d2b-367">`New-AzureVMSqlServerAutoBackupConfig` has been renamed to `New-AzureRmVMSqlServerAutoBackupConfig`</span></span>
    + <span data-ttu-id="67d2b-368">`New-AzureVMSqlServerAutoPatchingConfig` 已重新命名為 `New-AzureRmVMSqlServerAutoPatchingConfig`</span><span class="sxs-lookup"><span data-stu-id="67d2b-368">`New-AzureVMSqlServerAutoPatchingConfig` has been renamed to `New-AzureRmVMSqlServerAutoPatchingConfig`</span></span>
    + <span data-ttu-id="67d2b-369">`New-AzureVMSqlServerKeyVaultCredentialConfig` 已重新命名為 `New-AzureRmVMSqlServerKeyVaultCredentialConfig`</span><span class="sxs-lookup"><span data-stu-id="67d2b-369">`New-AzureVMSqlServerKeyVaultCredentialConfig` has been renamed to `New-AzureRmVMSqlServerKeyVaultCredentialConfig`</span></span>
* <span data-ttu-id="67d2b-370">耗用量</span><span class="sxs-lookup"><span data-stu-id="67d2b-370">Consumption</span></span>
  - <span data-ttu-id="67d2b-371">新的 Get-AzureRmConsumptionUsageDetail Cmdlet</span><span class="sxs-lookup"><span data-stu-id="67d2b-371">New Cmdlet Get-AzureRmConsumptionUsageDetail</span></span>
    + <span data-ttu-id="67d2b-372">用於擷取訂用帳戶使用量詳細資料的 Cmdlet。</span><span class="sxs-lookup"><span data-stu-id="67d2b-372">cmdlet to retrieve usage details of the subscription.</span></span>
* <span data-ttu-id="67d2b-373">ContainerRegistry</span><span class="sxs-lookup"><span data-stu-id="67d2b-373">ContainerRegistry</span></span>
  - <span data-ttu-id="67d2b-374">新增 Azure Container Registry 的 PowerShell Cmdlet</span><span class="sxs-lookup"><span data-stu-id="67d2b-374">Add PowerShell cmdlets for Azure Container Registry</span></span>
    + <span data-ttu-id="67d2b-375">New-AzureRmContainerRegistry</span><span class="sxs-lookup"><span data-stu-id="67d2b-375">New-AzureRmContainerRegistry</span></span>
    + <span data-ttu-id="67d2b-376">Get-AzureRmContainerRegistry</span><span class="sxs-lookup"><span data-stu-id="67d2b-376">Get-AzureRmContainerRegistry</span></span>
    + <span data-ttu-id="67d2b-377">Update-AzureRmContainerRegistry</span><span class="sxs-lookup"><span data-stu-id="67d2b-377">Update-AzureRmContainerRegistry</span></span>
    + <span data-ttu-id="67d2b-378">Remove-AzureRmContainerRegistry</span><span class="sxs-lookup"><span data-stu-id="67d2b-378">Remove-AzureRmContainerRegistry</span></span>
    + <span data-ttu-id="67d2b-379">Get-AzureRmContainerRegistryCredential</span><span class="sxs-lookup"><span data-stu-id="67d2b-379">Get-AzureRmContainerRegistryCredential</span></span>
    + <span data-ttu-id="67d2b-380">Update-AzureRmContainerRegistryCredential</span><span class="sxs-lookup"><span data-stu-id="67d2b-380">Update-AzureRmContainerRegistryCredential</span></span>
    + <span data-ttu-id="67d2b-381">Test-AzureRmContainerRegistryNameAvailability</span><span class="sxs-lookup"><span data-stu-id="67d2b-381">Test-AzureRmContainerRegistryNameAvailability</span></span>
* <span data-ttu-id="67d2b-382">DataLakeAnalytics</span><span class="sxs-lookup"><span data-stu-id="67d2b-382">DataLakeAnalytics</span></span>
  - <span data-ttu-id="67d2b-383">新增取得和列出目錄套件的支援</span><span class="sxs-lookup"><span data-stu-id="67d2b-383">Add support for catalog package get and list</span></span>
  - <span data-ttu-id="67d2b-384">新增從更深層的上階列出下列目錄項目的支援：</span><span class="sxs-lookup"><span data-stu-id="67d2b-384">Add support for listing the following catalog items from deeper ancestors:</span></span>
    + <span data-ttu-id="67d2b-385">資料表</span><span class="sxs-lookup"><span data-stu-id="67d2b-385">Table</span></span>
    + <span data-ttu-id="67d2b-386">TVF</span><span class="sxs-lookup"><span data-stu-id="67d2b-386">TVF</span></span>
    + <span data-ttu-id="67d2b-387">檢視</span><span class="sxs-lookup"><span data-stu-id="67d2b-387">View</span></span>
    + <span data-ttu-id="67d2b-388">統計資料</span><span class="sxs-lookup"><span data-stu-id="67d2b-388">Statistics</span></span>
* <span data-ttu-id="67d2b-389">DataLakeStore</span><span class="sxs-lookup"><span data-stu-id="67d2b-389">DataLakeStore</span></span>
  - <span data-ttu-id="67d2b-390">對於 `Import-AzureRMDataLakeStoreItem` 和 `Export-AzureRMDataLakeStoreItem`，預設已停用追蹤記錄以改善效能。</span><span class="sxs-lookup"><span data-stu-id="67d2b-390">For `Import-AzureRMDataLakeStoreItem` and `Export-AzureRMDataLakeStoreItem` trace logging has been disabled by default to improve performance.</span></span> <span data-ttu-id="67d2b-391">如果需要追蹤記錄，請使用 `-DiagnosticLogLevel` 和 `-DiagnosticLogPath` 參數</span><span class="sxs-lookup"><span data-stu-id="67d2b-391">If trace logging is desired please use the `-DiagnosticLogLevel` and `-DiagnosticLogPath` parameters</span></span>
  - <span data-ttu-id="67d2b-392">已修正將大量的小型檔案上傳到 ADLS 時偶爾會導致 PowerShell 當機的問題。</span><span class="sxs-lookup"><span data-stu-id="67d2b-392">Fixed a bug that would sometimes cause PowerShell to crash when uploading lots of small file to ADLS.</span></span>
* <span data-ttu-id="67d2b-393">EventHub</span><span class="sxs-lookup"><span data-stu-id="67d2b-393">EventHub</span></span>
  - <span data-ttu-id="67d2b-394">錯誤修正：</span><span class="sxs-lookup"><span data-stu-id="67d2b-394">Bug fix :</span></span>
    + <span data-ttu-id="67d2b-395">修正 Set-AzureRmEventHubNamespace Cmdlet 錯誤 - 'Tier' 不能為 Null，而必須是 'SkuName'</span><span class="sxs-lookup"><span data-stu-id="67d2b-395">Fix for Set-AzureRmEventHubNamespace cmdlet error  - 'Tier' cannot be null, where it should be 'SkuName'</span></span>
    + <span data-ttu-id="67d2b-396">Set-AzureRmEventHub - 修正更新 EventHub 時的「物件參考未設定成物件的執行個體」錯誤</span><span class="sxs-lookup"><span data-stu-id="67d2b-396">Set-AzureRmEventHub - Fix 'Object reference not set to an instance of an object' error while updating EventHub</span></span>
* <span data-ttu-id="67d2b-397">深入解析</span><span class="sxs-lookup"><span data-stu-id="67d2b-397">Insights</span></span>
  - <span data-ttu-id="67d2b-398">Add-AzureRm*AlertRule</span><span class="sxs-lookup"><span data-stu-id="67d2b-398">Add-AzureRm*AlertRule</span></span>
    + <span data-ttu-id="67d2b-399">傳回單一物件︰newResource、statusCode、requestId</span><span class="sxs-lookup"><span data-stu-id="67d2b-399">Returns a single object: newResource, statusCode, requestId</span></span>
  - <span data-ttu-id="67d2b-400">Get-AzureRmAlertRule</span><span class="sxs-lookup"><span data-stu-id="67d2b-400">Get-AzureRmAlertRule</span></span>
    + <span data-ttu-id="67d2b-401">現在會對輸出進行列舉，而不是將它視為單一物件。</span><span class="sxs-lookup"><span data-stu-id="67d2b-401">The output is now enumerated instead of considered a single object.</span></span> <span data-ttu-id="67d2b-402">它的類型並未變更，仍然是清單。</span><span class="sxs-lookup"><span data-stu-id="67d2b-402">Its type did not change, it is still a list.</span></span>
  - <span data-ttu-id="67d2b-403">Remove-AzureRmAlertRule</span><span class="sxs-lookup"><span data-stu-id="67d2b-403">Remove-AzureRmAlertRule</span></span>
    + <span data-ttu-id="67d2b-404">statusCode 會遵循要求所傳回的狀態碼，先前一律是「良好」。</span><span class="sxs-lookup"><span data-stu-id="67d2b-404">The statusCode follows the status code returned by the request, before it was Ok always.</span></span>
  - <span data-ttu-id="67d2b-405">Add-AzureRmAutoscaleSetting</span><span class="sxs-lookup"><span data-stu-id="67d2b-405">Add-AzureRmAutoscaleSetting</span></span>
    + <span data-ttu-id="67d2b-406">現在會傳回包含 statusCode、requestId，以及最近所建立/更新資源的單一物件 (而非先前的清單)。</span><span class="sxs-lookup"><span data-stu-id="67d2b-406">Returns now a single object (not a list as before) containing statusCode, requestId, and the newly created/updated resource.</span></span>
    + <span data-ttu-id="67d2b-407">狀態碼會遵循要求所傳回的狀態，先前一律是「良好」。</span><span class="sxs-lookup"><span data-stu-id="67d2b-407">The status code follows the status returned by the request, before it was always Ok.</span></span>
  - <span data-ttu-id="67d2b-408">New-AzureRmAutoscaleRule</span><span class="sxs-lookup"><span data-stu-id="67d2b-408">New-AzureRmAutoscaleRule</span></span>
    + <span data-ttu-id="67d2b-409">已擴充 ScaleActionType 參數，現在它會接收下列值：ChangeCount、PercentChangeCount、ExactCount。</span><span class="sxs-lookup"><span data-stu-id="67d2b-409">The parameter ScaleActionType has been extended, it receives the following values now: ChangeCount, PercentChangeCount, ExactCount.</span></span>
  - <span data-ttu-id="67d2b-410">Remove-AzureRmAutoscaleSetting</span><span class="sxs-lookup"><span data-stu-id="67d2b-410">Remove-AzureRmAutoscaleSetting</span></span>
    + <span data-ttu-id="67d2b-411">輸出中的 statusCode 會遵循要求所傳回的 statusCode。</span><span class="sxs-lookup"><span data-stu-id="67d2b-411">The statusCode in the output follows the statusCode returned by the request.</span></span> <span data-ttu-id="67d2b-412">先前一律是「良好」。</span><span class="sxs-lookup"><span data-stu-id="67d2b-412">Before it was always Ok.</span></span>
  - <span data-ttu-id="67d2b-413">Get-AzureRMLogProfile</span><span class="sxs-lookup"><span data-stu-id="67d2b-413">Get-AzureRMLogProfile</span></span>
    + <span data-ttu-id="67d2b-414">現在會對輸出進行列舉。</span><span class="sxs-lookup"><span data-stu-id="67d2b-414">The output is now enumerated.</span></span> <span data-ttu-id="67d2b-415">先前是將它視為單一物件。</span><span class="sxs-lookup"><span data-stu-id="67d2b-415">Before it was considered a single object.</span></span> <span data-ttu-id="67d2b-416">輸出的類型仍為先前的清單。</span><span class="sxs-lookup"><span data-stu-id="67d2b-416">The type of the output remains a list as before.</span></span>
  - <span data-ttu-id="67d2b-417">Remove-AzureRmLogProfile</span><span class="sxs-lookup"><span data-stu-id="67d2b-417">Remove-AzureRmLogProfile</span></span>
    + <span data-ttu-id="67d2b-418">已實作 PassThru 參數。</span><span class="sxs-lookup"><span data-stu-id="67d2b-418">The PassThru parameter has been implemented.</span></span>
  - <span data-ttu-id="67d2b-419">計量 API</span><span class="sxs-lookup"><span data-stu-id="67d2b-419">Metrics API</span></span>
    + <span data-ttu-id="67d2b-420">SDK 現在會從 MDM 擷取計量。</span><span class="sxs-lookup"><span data-stu-id="67d2b-420">The SDK now retrieves metrics from MDM.</span></span>
  - <span data-ttu-id="67d2b-421">Get-AzureRmMetricDefinition</span><span class="sxs-lookup"><span data-stu-id="67d2b-421">Get-AzureRmMetricDefinition</span></span>
    + <span data-ttu-id="67d2b-422">輸出仍是清單，但清單的結構已變更。</span><span class="sxs-lookup"><span data-stu-id="67d2b-422">The output is still a list, but the structure of the list changed.</span></span>
  - <span data-ttu-id="67d2b-423">Get-AzureRmMetric</span><span class="sxs-lookup"><span data-stu-id="67d2b-423">Get-AzureRmMetric</span></span>
    + <span data-ttu-id="67d2b-424">呼叫已變更。</span><span class="sxs-lookup"><span data-stu-id="67d2b-424">The call has changed.</span></span> <span data-ttu-id="67d2b-425">新的語法如下：Get-AzureRmMetric ResourceId [MetricNames [TimeGrain] [AggregationType] [StartTime] [EndTime]] [DetailedOutput]</span><span class="sxs-lookup"><span data-stu-id="67d2b-425">This is the new syntax: Get-AzureRmMetric ResourceId [MetricNames [TimeGrain] [AggregationType] [StartTime] [EndTime]] [DetailedOutput]</span></span>
    + <span data-ttu-id="67d2b-426">輸出是清單，但其元素的結構已變更。</span><span class="sxs-lookup"><span data-stu-id="67d2b-426">The output is a list, and the structure of its elements has changed.</span></span>
* <span data-ttu-id="67d2b-427">KeyVault</span><span class="sxs-lookup"><span data-stu-id="67d2b-427">KeyVault</span></span>
  - <span data-ttu-id="67d2b-428">新增備份/還原 KeyVault 密碼的支援</span><span class="sxs-lookup"><span data-stu-id="67d2b-428">Adding backup/restore support for KeyVault secrets</span></span>
    + <span data-ttu-id="67d2b-429">可以對密碼進行備份和還原，以符合目前對於金鑰所支援的功能</span><span class="sxs-lookup"><span data-stu-id="67d2b-429">Secrets can be backed up and restored, matching the functionality currently supported for Keys</span></span>

  - <span data-ttu-id="67d2b-430">金鑰和密碼的備份 Cmdlet 現在接受以對應的物件做為輸入參數</span><span class="sxs-lookup"><span data-stu-id="67d2b-430">Backup cmdlets for Keys and Secrets now accept a corresponding object as an input parameter</span></span>
    + <span data-ttu-id="67d2b-431">呼叫端可鏈結擷取和備份作業︰Get-AzureKeyVaultKey -VaultName myVault -Name myKey | Backup-AzureKeyVaultKey</span><span class="sxs-lookup"><span data-stu-id="67d2b-431">The caller may chain retrieval and backup operations: Get-AzureKeyVaultKey -VaultName myVault -Name myKey | Backup-AzureKeyVaultKey</span></span>

  - <span data-ttu-id="67d2b-432">備份 Cmdlet 現在支援用於覆寫現有檔案的 -Force 參數</span><span class="sxs-lookup"><span data-stu-id="67d2b-432">Backup cmdlets now support a -Force switch to overwrite an existing file</span></span>
    + <span data-ttu-id="67d2b-433">請注意，嘗試覆寫現有檔案將不再會擲回，而是改為提示使用者選擇繼續的方式。</span><span class="sxs-lookup"><span data-stu-id="67d2b-433">Note that attempting to overwrite an existing file will no longer throw, and will instead prompt the user for a choice on how to proceed.</span></span>
* <span data-ttu-id="67d2b-434">LogicApp</span><span class="sxs-lookup"><span data-stu-id="67d2b-434">LogicApp</span></span>
  - <span data-ttu-id="67d2b-435">交換控制編號災害復原 Cmdlet 的新參數︰</span><span class="sxs-lookup"><span data-stu-id="67d2b-435">New parameters for Interchange Control Number disaster recovery cmdlets:</span></span>
    + <span data-ttu-id="67d2b-436">用於指定相關控制編號的選擇性 -AgreementType 參數 ("X12" 或 "Edifact")</span><span class="sxs-lookup"><span data-stu-id="67d2b-436">Optional -AgreementType parameter ("X12", or "Edifact") to specify the relevant control numbers</span></span>
* <span data-ttu-id="67d2b-437">MachineLearning</span><span class="sxs-lookup"><span data-stu-id="67d2b-437">MachineLearning</span></span>
  - <span data-ttu-id="67d2b-438">使用新版的 Azure Machine Learning .Net SDK，並新增 Cmdlet</span><span class="sxs-lookup"><span data-stu-id="67d2b-438">Consume new version of Azure Machine Learning .Net SDK and add a new cmdlet</span></span>
    + <span data-ttu-id="67d2b-439">Add-AzureRmMlWebServiceRegionalProperty</span><span class="sxs-lookup"><span data-stu-id="67d2b-439">Add-AzureRmMlWebServiceRegionalProperty</span></span>
  - <span data-ttu-id="67d2b-440">說明文字中的次要措辭修正。</span><span class="sxs-lookup"><span data-stu-id="67d2b-440">Minor wording fixes in help text.</span></span>
* <span data-ttu-id="67d2b-441">網路</span><span class="sxs-lookup"><span data-stu-id="67d2b-441">Network</span></span>
  - <span data-ttu-id="67d2b-442">已新增 Test-AzureRmNetworkWatcherConnectivity Cmdlet</span><span class="sxs-lookup"><span data-stu-id="67d2b-442">Added Test-AzureRmNetworkWatcherConnectivity cmdlet</span></span>
    + <span data-ttu-id="67d2b-443">傳回指定來源 VM 和目的地的連線資訊</span><span class="sxs-lookup"><span data-stu-id="67d2b-443">Returns connectivity information for a specified source VM and a destination</span></span>
    + <span data-ttu-id="67d2b-444">如果無法建立來源與目的地之間的連線，此 Cmdlet 會傳回問題的詳細資料</span><span class="sxs-lookup"><span data-stu-id="67d2b-444">If connectivity between the source and destination cannot be established, the cmdlet returns details about the issue</span></span>
* <span data-ttu-id="67d2b-445">設定檔</span><span class="sxs-lookup"><span data-stu-id="67d2b-445">Profile</span></span>
  - <span data-ttu-id="67d2b-446">已新增 'Send-Feedback' Cmdlet︰可讓使用者起始一組提示，以傳送意見反應給 Azure PowerShell 小組。</span><span class="sxs-lookup"><span data-stu-id="67d2b-446">Added \`Send-Feedback' cmdlet: allows a user to initiate a set of prompts which sends feedback to the Azure PowerShell team.</span></span>
  - <span data-ttu-id="67d2b-447">已移除下列別名，因為它們與 Azure 模組中現有的 Cmdlet 名稱衝突︰</span><span class="sxs-lookup"><span data-stu-id="67d2b-447">The following aliases have been removed as they conflicted with existing cmdlet names in the Azure module:</span></span>
    + <span data-ttu-id="67d2b-448">`Enable-AzureDataCollection` (受 `Enable-AzureRmDataCollection` 支援)</span><span class="sxs-lookup"><span data-stu-id="67d2b-448">`Enable-AzureDataCollection` (supported by `Enable-AzureRmDataCollection`)</span></span>
    + <span data-ttu-id="67d2b-449">`Disable-AzureDataCollection` (受 `Disable-AzureRmDataCollection` 支援)</span><span class="sxs-lookup"><span data-stu-id="67d2b-449">`Disable-AzureDataCollection` (supported by `Disable-AzureRmDataCollection`)</span></span>
* <span data-ttu-id="67d2b-450">轉送</span><span class="sxs-lookup"><span data-stu-id="67d2b-450">Relay</span></span>
  - <span data-ttu-id="67d2b-451">新增 Azure 轉送適用的 Cmdlet，方便使用者建立和管理所有 Azure 轉送資源。</span><span class="sxs-lookup"><span data-stu-id="67d2b-451">Adds cmdlets for the Azure Relay which allows users to create and manage all Azure Relay resources.</span></span>
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
* <span data-ttu-id="67d2b-452">資源</span><span class="sxs-lookup"><span data-stu-id="67d2b-452">Resources</span></span>
  - <span data-ttu-id="67d2b-453">支援適用於 AzureRmResourceGroupDeployment 的跨資源群組部署</span><span class="sxs-lookup"><span data-stu-id="67d2b-453">Support cross-resource-group deployments for New-AzureRmResourceGroupDeployment</span></span>
    + <span data-ttu-id="67d2b-454">使用者現在可以使用巢狀部署以部署至不同的資源群組。</span><span class="sxs-lookup"><span data-stu-id="67d2b-454">Users can now use nested deployments to deploy to different resource groups.</span></span>
* <span data-ttu-id="67d2b-455">ServiceBus</span><span class="sxs-lookup"><span data-stu-id="67d2b-455">ServiceBus</span></span>

  - <span data-ttu-id="67d2b-456">錯誤修正：ServiceBus 佇列物件屬性值已設為 Null，該物件是做為 Set-AzureRmServiceBusQueue Cmdlet 中的輸入參數使用以更新佇列。</span><span class="sxs-lookup"><span data-stu-id="67d2b-456">Bug Fix: ServiceBus Queue object property values were set to null, the object is used as input parameter in Set-AzureRmServiceBusQueue cmdlet to update Queue.</span></span>
   - <span data-ttu-id="67d2b-457">受影響的屬性包括 LockDuration、EntityAvailabilityStatus、DuplicateDetectionHistoryTimeWindow、MaxDeliveryCount 和 MessageCount</span><span class="sxs-lookup"><span data-stu-id="67d2b-457">Properties affected are LockDuration, EntityAvailabilityStatus, DuplicateDetectionHistoryTimeWindow, MaxDeliveryCount and MessageCount</span></span>
* <span data-ttu-id="67d2b-458">ServiceFabric</span><span class="sxs-lookup"><span data-stu-id="67d2b-458">ServiceFabric</span></span>

  - <span data-ttu-id="67d2b-459">已新增適用於 Service Fabric 的 Cmdlet</span><span class="sxs-lookup"><span data-stu-id="67d2b-459">Added cmdlets for service fabric</span></span>
    + <span data-ttu-id="67d2b-460">Add-AzureRmServiceFabricApplicationCertificate       新增將做為應用程式憑證使用的憑證</span><span class="sxs-lookup"><span data-stu-id="67d2b-460">Add-AzureRmServiceFabricApplicationCertificate       Add a certificate which will be used as application certificate</span></span>
    + <span data-ttu-id="67d2b-461">Add-AzureRmServiceFabricClientCertificate       在叢集設定新增用於用戶端驗證的一般名稱或指紋</span><span class="sxs-lookup"><span data-stu-id="67d2b-461">Add-AzureRmServiceFabricClientCertificate       Add a common name or thumbprint to the cluster settings for client authentication</span></span>
    + <span data-ttu-id="67d2b-462">Add-AzureRmServiceFabricClusterCertificate       在叢集新增次要叢集憑證以更換現有的憑證</span><span class="sxs-lookup"><span data-stu-id="67d2b-462">Add-AzureRmServiceFabricClusterCertificate       Add a secondary cluster certificate to the cluster for rolling over the existing certificate</span></span>
    + <span data-ttu-id="67d2b-463">Add-AzureRmServiceFabricNodes       在叢集新增特定節點類型的節點/VM</span><span class="sxs-lookup"><span data-stu-id="67d2b-463">Add-AzureRmServiceFabricNodes       Add nodes/VMs of a specific node type to a cluster</span></span>
    + <span data-ttu-id="67d2b-464">Add-AzureRmServiceFabricNodeType       在現有叢集新增節點類型/VM</span><span class="sxs-lookup"><span data-stu-id="67d2b-464">Add-AzureRmServiceFabricNodeType       Add a node type/VMs to an existing cluster</span></span>
    + <span data-ttu-id="67d2b-465">Get-AzureRmServiceFabricCluster       取得叢集資源的詳細資料</span><span class="sxs-lookup"><span data-stu-id="67d2b-465">Get-AzureRmServiceFabricCluster       Get the details of the cluster resource</span></span>
    + <span data-ttu-id="67d2b-466">New-AzureRmServiceFabricCluster 建立新的 ServiceFabric 叢集。</span><span class="sxs-lookup"><span data-stu-id="67d2b-466">New-AzureRmServiceFabricCluster Create a new ServiceFabric cluster.</span></span> <span data-ttu-id="67d2b-467">此命令有許多的多載，可涵蓋各種案例</span><span class="sxs-lookup"><span data-stu-id="67d2b-467">This command has many overloads to cover various scenarios</span></span>
    + <span data-ttu-id="67d2b-468">Remove-AzureRmServiceFabricClientCertificate       移除某個用戶端憑證以防止將它用於存取叢集</span><span class="sxs-lookup"><span data-stu-id="67d2b-468">Remove-AzureRmServiceFabricClientCertificate       Remove a client certificate from being used to access a cluster</span></span>
    + <span data-ttu-id="67d2b-469">Remove-AzureRmServiceFabricClusterCertificate       移除某個用戶端憑證以防止將它用於叢集安全性</span><span class="sxs-lookup"><span data-stu-id="67d2b-469">Remove-AzureRmServiceFabricClusterCertificate       Remove a cluster certificate from being used for cluster security</span></span>
    + <span data-ttu-id="67d2b-470">Remove-AzureRmServiceFabricNodes       自叢集中移除特定節點類型的節點</span><span class="sxs-lookup"><span data-stu-id="67d2b-470">Remove-AzureRmServiceFabricNodes       Remove nodes from a specific node type from a cluster</span></span>
    + <span data-ttu-id="67d2b-471">Remove-AzureRmServiceFabricNodeType       自叢集中移除某個節點類型</span><span class="sxs-lookup"><span data-stu-id="67d2b-471">Remove-AzureRmServiceFabricNodeType       Remove a node type from a cluster</span></span>
    + <span data-ttu-id="67d2b-472">Remove-AzureRmServiceFabricSettings       自叢集中移除一或多個 ServiceFabric 設定</span><span class="sxs-lookup"><span data-stu-id="67d2b-472">Remove-AzureRmServiceFabricSettings       Remove one or more ServiceFabric settings from a cluster</span></span>
    + <span data-ttu-id="67d2b-473">Set-AzureRmServiceFabricSettings       新增或更新叢集的一或多個 ServiceFabric 設定</span><span class="sxs-lookup"><span data-stu-id="67d2b-473">Set-AzureRmServiceFabricSettings       Add or update one or more ServiceFabric settings of a cluster</span></span>
    + <span data-ttu-id="67d2b-474">Set-AzureRmServiceFabricUpgradeType       變更叢集的 ServiceFabric 升級類型</span><span class="sxs-lookup"><span data-stu-id="67d2b-474">Set-AzureRmServiceFabricUpgradeType       Change the ServiceFabric upgrade type of a cluster</span></span>
    + <span data-ttu-id="67d2b-475">Update-AzureRmServiceFabricDurability       變更叢集的持久性層</span><span class="sxs-lookup"><span data-stu-id="67d2b-475">Update-AzureRmServiceFabricDurability       Change the durability tier of a cluster</span></span>
    + <span data-ttu-id="67d2b-476">Update-AzureRmServiceFabricReliability       變更叢集的可靠性層</span><span class="sxs-lookup"><span data-stu-id="67d2b-476">Update-AzureRmServiceFabricReliability       Change the reliability tier of a cluster</span></span>
* <span data-ttu-id="67d2b-477">Sql</span><span class="sxs-lookup"><span data-stu-id="67d2b-477">Sql</span></span>
  - <span data-ttu-id="67d2b-478">已將 -SampleName 參數新增至 New-AzureRmSqlDatabase</span><span class="sxs-lookup"><span data-stu-id="67d2b-478">Added -SampleName parameter to New-AzureRmSqlDatabase</span></span>
  - <span data-ttu-id="67d2b-479">更新容錯移轉群組 Cmdlet</span><span class="sxs-lookup"><span data-stu-id="67d2b-479">Updates to Failover Group cmdlets</span></span>
  - <span data-ttu-id="67d2b-480">移除 'Tag' 參數</span><span class="sxs-lookup"><span data-stu-id="67d2b-480">Remove 'Tag' parameters</span></span>
  - <span data-ttu-id="67d2b-481">從 Remove-AzureRmSqlDatabaseFailoverGroup Cmdlet 中移除 'PartnerResourceGroupName' 和 'PartnerServerName' 參數</span><span class="sxs-lookup"><span data-stu-id="67d2b-481">Remove 'PartnerResourceGroupName' and 'PartnerServerName' parameters from Remove-AzureRmSqlDatabaseFailoverGroup cmdlet</span></span>
  - <span data-ttu-id="67d2b-482">將 'GracePeriodWithDataLossHours' 參數新增至 New- 和 Set- Cmdlet，此參數最終會取代 'GracePeriodWithDataLossHour'</span><span class="sxs-lookup"><span data-stu-id="67d2b-482">Add 'GracePeriodWithDataLossHours' parameter to New- and Set- cmdlets, which shall eventually replace 'GracePeriodWithDataLossHour'</span></span>
  - <span data-ttu-id="67d2b-483">文件已增補並更新</span><span class="sxs-lookup"><span data-stu-id="67d2b-483">Documentation has been fleshed out and updated</span></span>
  - <span data-ttu-id="67d2b-484">變更傳回物件的格式，並修正欄位有時不會填入的錯誤</span><span class="sxs-lookup"><span data-stu-id="67d2b-484">Change formatting of returned objects and fix some bugs where fields were not always populated</span></span>
  - <span data-ttu-id="67d2b-485">將 'DatabaseNames' 和 'PartnerLocation' 屬性新增至容錯移轉群組物件</span><span class="sxs-lookup"><span data-stu-id="67d2b-485">Add 'DatabaseNames' and 'PartnerLocation' properties to Failover Group object</span></span>
  - <span data-ttu-id="67d2b-486">修正造成 Switch- Cmdlet 立即傳回 (而非等待作業完成後再傳回) 的錯誤</span><span class="sxs-lookup"><span data-stu-id="67d2b-486">Fix bug causing Switch- cmdlet to return immediately rather than waiting for operation to complete</span></span>
  - <span data-ttu-id="67d2b-487">修正使用高寬限期值時的整數溢位錯誤</span><span class="sxs-lookup"><span data-stu-id="67d2b-487">Fix integer overflow bug when high grace period values are used</span></span>
  - <span data-ttu-id="67d2b-488">在提供的值比 1 小時的下限還要低的情況下，將寬限期調整為 1 小時</span><span class="sxs-lookup"><span data-stu-id="67d2b-488">Adjust grace period to a minimum of 1 hour if a lower one is provided</span></span>
  - <span data-ttu-id="67d2b-489">從 Set-AzureRmSqlDatabaseThreatDetectionPolicy Cmdlet 和 Set-AzureRmSqlServerThreatDetectionPolicy Cmdlet 之 "ExcludedDetectionType" 參數的可接受值中移除 "Usage_Anomaly"。</span><span class="sxs-lookup"><span data-stu-id="67d2b-489">Remove "Usage_Anomaly" from the accepted values for "ExcludedDetectionType" parameter of Set-AzureRmSqlDatabaseThreatDetectionPolicy cmdlet and Set-AzureRmSqlServerThreatDetectionPolicy cmdlet.</span></span>
* <span data-ttu-id="67d2b-490">儲存體</span><span class="sxs-lookup"><span data-stu-id="67d2b-490">Storage</span></span>
  - <span data-ttu-id="67d2b-491">將 SRP SDK 升級至 6.3.0</span><span class="sxs-lookup"><span data-stu-id="67d2b-491">Upgrade SRP SDK to 6.3.0</span></span>
  - <span data-ttu-id="67d2b-492">New/Set-AzureRmStorageAccount：新增參數以支援 EnableHttpsTrafficOnly</span><span class="sxs-lookup"><span data-stu-id="67d2b-492">New/Set-AzureRmStorageAccount:Add a new parameter to support EnableHttpsTrafficOnly</span></span>
  - <span data-ttu-id="67d2b-493">New/Set/Get-AzureRmStorageAccount：傳回的儲存體帳戶包含新的 EnableHttpsTrafficOnly 屬性</span><span class="sxs-lookup"><span data-stu-id="67d2b-493">New/Set/Get-AzureRmStorageAccount: Returned Storage Account contains a new attribute EnableHttpsTrafficOnly</span></span>
* <span data-ttu-id="67d2b-494">Azure.Storage</span><span class="sxs-lookup"><span data-stu-id="67d2b-494">Azure.Storage</span></span>
  - <span data-ttu-id="67d2b-495">升級至 Azure 儲存體用戶端程式庫 8.1.1 及 Azure 儲存體資料移動程式庫 0.5.1</span><span class="sxs-lookup"><span data-stu-id="67d2b-495">Upgrade to Azure Storage Client Library 8.1.1 and Azure Storage DataMovement Library 0.5.1</span></span>
  - <span data-ttu-id="67d2b-496">新增 Cmdlet 以支援 Blob 增量複製功能</span><span class="sxs-lookup"><span data-stu-id="67d2b-496">Add a new cmdlet to support blob Incremental Copy feature</span></span>
