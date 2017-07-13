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
ms.openlocfilehash: 143d92384fd270711378f6741ba59e88c12833d1
ms.sourcegitcommit: 226527be7cb647acfe2ea9ab151185053ab3c6db
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 06/29/2017
---
# <span data-ttu-id="44119-103">版本資訊</span><span class="sxs-lookup"><span data-stu-id="44119-103">Release notes</span></span>
<a id="release-notes" class="xliff"></a>

<span data-ttu-id="44119-104">這是此版本中對 Azure PowerShell 所做的變更清單。</span><span class="sxs-lookup"><span data-stu-id="44119-104">This is a list of changes made to Azure PowerShell in this release.</span></span>

## <span data-ttu-id="44119-105">2.2.0 版</span><span class="sxs-lookup"><span data-stu-id="44119-105">Version 2.2.0</span></span>
<a id="version-220" class="xliff"></a>
* <span data-ttu-id="44119-106">計算</span><span class="sxs-lookup"><span data-stu-id="44119-106">Compute</span></span>
  - <span data-ttu-id="44119-107">新增從 AzureDiskEncryptionForLinux 擴充查詢加密狀態的支援</span><span class="sxs-lookup"><span data-stu-id="44119-107">Add support for querying encryption status from the AzureDiskEncryptionForLinux extension</span></span>
* <span data-ttu-id="44119-108">DataFactory</span><span class="sxs-lookup"><span data-stu-id="44119-108">DataFactory</span></span>
  - <span data-ttu-id="44119-109">已新增 Cmdlet 以供列出活動時段</span><span class="sxs-lookup"><span data-stu-id="44119-109">Added new cmdlet for listing activity windows</span></span>
    + <span data-ttu-id="44119-110">Get-AzureRmDataFactoryActivityWindow</span><span class="sxs-lookup"><span data-stu-id="44119-110">Get-AzureRmDataFactoryActivityWindow</span></span>
* <span data-ttu-id="44119-111">DataLake</span><span class="sxs-lookup"><span data-stu-id="44119-111">DataLake</span></span>
  - <span data-ttu-id="44119-112">已將參數 `Host` 變更為 `DatabaseHost` 並將別名新增至 `Host`</span><span class="sxs-lookup"><span data-stu-id="44119-112">Changed parameter `Host` to `DatabaseHost` and added alias to `Host`</span></span>
    + <span data-ttu-id="44119-113">New-AzureRmDataLakeAnalyticsCatalogSecret</span><span class="sxs-lookup"><span data-stu-id="44119-113">New-AzureRmDataLakeAnalyticsCatalogSecret</span></span>
    + <span data-ttu-id="44119-114">Set-AzureRmDataLakeAnalyticsCatalogSecret</span><span class="sxs-lookup"><span data-stu-id="44119-114">Set-AzureRmDataLakeAnalyticsCatalogSecret</span></span>
  - <span data-ttu-id="44119-115">新增 ACL 和預設 ACL 移除的支援</span><span class="sxs-lookup"><span data-stu-id="44119-115">Add support for ACL and Default ACL removal</span></span>
  - <span data-ttu-id="44119-116">新增取得及設定檔案和資料夾之未命名權限的支援</span><span class="sxs-lookup"><span data-stu-id="44119-116">Add support for getting and setting unnamed permissions on files and folders</span></span>
* <span data-ttu-id="44119-117">KeyVault</span><span class="sxs-lookup"><span data-stu-id="44119-117">KeyVault</span></span>
  - <span data-ttu-id="44119-118">新增憑證的支援</span><span class="sxs-lookup"><span data-stu-id="44119-118">Add support for certificates</span></span>
    + <span data-ttu-id="44119-119">Add-AzureKeyVaultCertificate</span><span class="sxs-lookup"><span data-stu-id="44119-119">Add-AzureKeyVaultCertificate</span></span>
    + <span data-ttu-id="44119-120">Add-AzureKeyVaultCertificateContact</span><span class="sxs-lookup"><span data-stu-id="44119-120">Add-AzureKeyVaultCertificateContact</span></span>
    + <span data-ttu-id="44119-121">Get-AzureKeyVaultCertificate</span><span class="sxs-lookup"><span data-stu-id="44119-121">Get-AzureKeyVaultCertificate</span></span>
    + <span data-ttu-id="44119-122">Get-AzureKeyVaultCertificateContact</span><span class="sxs-lookup"><span data-stu-id="44119-122">Get-AzureKeyVaultCertificateContact</span></span>
    + <span data-ttu-id="44119-123">Get-AzureKeyVaultCertificateIssuer</span><span class="sxs-lookup"><span data-stu-id="44119-123">Get-AzureKeyVaultCertificateIssuer</span></span>
    + <span data-ttu-id="44119-124">Get-AzureKeyVaultCertificateOperation</span><span class="sxs-lookup"><span data-stu-id="44119-124">Get-AzureKeyVaultCertificateOperation</span></span>
    + <span data-ttu-id="44119-125">Get-AzureKeyVaultCertificatePolicy</span><span class="sxs-lookup"><span data-stu-id="44119-125">Get-AzureKeyVaultCertificatePolicy</span></span>
    + <span data-ttu-id="44119-126">Import-AzureKeyVaultCertificate</span><span class="sxs-lookup"><span data-stu-id="44119-126">Import-AzureKeyVaultCertificate</span></span>
    + <span data-ttu-id="44119-127">New-AzureKeyVaultCertificateAdministratorDetails</span><span class="sxs-lookup"><span data-stu-id="44119-127">New-AzureKeyVaultCertificateAdministratorDetails</span></span>
    + <span data-ttu-id="44119-128">New-AzureKeyVaultCertificateOrganizationDetails</span><span class="sxs-lookup"><span data-stu-id="44119-128">New-AzureKeyVaultCertificateOrganizationDetails</span></span>
    + <span data-ttu-id="44119-129">New-AzureKeyVaultCertificatePolicy</span><span class="sxs-lookup"><span data-stu-id="44119-129">New-AzureKeyVaultCertificatePolicy</span></span>
    + <span data-ttu-id="44119-130">Remove-AzureKeyVaultCertificate</span><span class="sxs-lookup"><span data-stu-id="44119-130">Remove-AzureKeyVaultCertificate</span></span>
    + <span data-ttu-id="44119-131">Remove-AzureKeyVaultCertificateContact</span><span class="sxs-lookup"><span data-stu-id="44119-131">Remove-AzureKeyVaultCertificateContact</span></span>
    + <span data-ttu-id="44119-132">Remove-AzureKeyVaultCertificateIssuer</span><span class="sxs-lookup"><span data-stu-id="44119-132">Remove-AzureKeyVaultCertificateIssuer</span></span>
    + <span data-ttu-id="44119-133">Remove-AzureKeyVaultCertificateOperation</span><span class="sxs-lookup"><span data-stu-id="44119-133">Remove-AzureKeyVaultCertificateOperation</span></span>
    + <span data-ttu-id="44119-134">Set-AzureKeyVaultCertificateAttribute</span><span class="sxs-lookup"><span data-stu-id="44119-134">Set-AzureKeyVaultCertificateAttribute</span></span>
    + <span data-ttu-id="44119-135">Set-AzureKeyVaultCertificateIssuer</span><span class="sxs-lookup"><span data-stu-id="44119-135">Set-AzureKeyVaultCertificateIssuer</span></span>
    + <span data-ttu-id="44119-136">Set-AzureKeyVaultCertificatePolicy</span><span class="sxs-lookup"><span data-stu-id="44119-136">Set-AzureKeyVaultCertificatePolicy</span></span>
    + <span data-ttu-id="44119-137">Stop-AzureKeyVaultCertificateOperation</span><span class="sxs-lookup"><span data-stu-id="44119-137">Stop-AzureKeyVaultCertificateOperation</span></span>
* <span data-ttu-id="44119-138">網路</span><span class="sxs-lookup"><span data-stu-id="44119-138">Network</span></span>

  - <span data-ttu-id="44119-139">新增網路介面的切換參數來啟用/停用加速網路 +New-AzureRmNetworkInterface -EnableAcceleratedNetworking</span><span class="sxs-lookup"><span data-stu-id="44119-139">New switch parameter added for network interface to enable/disable accelerated networking +New-AzureRmNetworkInterface -EnableAcceleratedNetworking</span></span>
  - <span data-ttu-id="44119-140">啟用主動-主動閘道功能 PowerShell Cmdlet</span><span class="sxs-lookup"><span data-stu-id="44119-140">Enable Active-Active gateway feature PowerShell cmdlets</span></span>
    + <span data-ttu-id="44119-141">Add-AzureRmVirtualNetworkGatewayIpConfig</span><span class="sxs-lookup"><span data-stu-id="44119-141">Add-AzureRmVirtualNetworkGatewayIpConfig</span></span>
    + <span data-ttu-id="44119-142">Remove-AzureRmVirtualNetworkGatewayIpConfig</span><span class="sxs-lookup"><span data-stu-id="44119-142">Remove-AzureRmVirtualNetworkGatewayIpConfig</span></span>
  - <span data-ttu-id="44119-143">已新增 Cmdlet</span><span class="sxs-lookup"><span data-stu-id="44119-143">Added new cmdlet</span></span>
    + <span data-ttu-id="44119-144">Test-AzureRmPrivateIpAddressAvailability</span><span class="sxs-lookup"><span data-stu-id="44119-144">Test-AzureRmPrivateIpAddressAvailability</span></span>
* <span data-ttu-id="44119-145">資源</span><span class="sxs-lookup"><span data-stu-id="44119-145">Resources</span></span>
  - <span data-ttu-id="44119-146">支援提供者和資源 Cmdlet 的區域</span><span class="sxs-lookup"><span data-stu-id="44119-146">Support zones in provider and resource cmdlets</span></span>
    + <span data-ttu-id="44119-147">Get-AzureRmProvider</span><span class="sxs-lookup"><span data-stu-id="44119-147">Get-AzureRmProvider</span></span>
    + <span data-ttu-id="44119-148">New-AzureRmResource</span><span class="sxs-lookup"><span data-stu-id="44119-148">New-AzureRmResource</span></span>
    + <span data-ttu-id="44119-149">Set-AzureRmResource</span><span class="sxs-lookup"><span data-stu-id="44119-149">Set-AzureRmResource</span></span>
* <span data-ttu-id="44119-150">Sql</span><span class="sxs-lookup"><span data-stu-id="44119-150">Sql</span></span>
  - <span data-ttu-id="44119-151">已在伺服器層級新增用於 Azure SQL 威脅偵測原則管理的 Cmdlet</span><span class="sxs-lookup"><span data-stu-id="44119-151">Added new cmdlets for Azure SQL threat detection policy management at server level</span></span>
    + <span data-ttu-id="44119-152">Get-AzureRmSqlServerThreatDetectionPolicy</span><span class="sxs-lookup"><span data-stu-id="44119-152">Get-AzureRmSqlServerThreatDetectionPolicy</span></span>
    + <span data-ttu-id="44119-153">Remove-AzureRmSqlServerThreatDetectionPolicy</span><span class="sxs-lookup"><span data-stu-id="44119-153">Remove-AzureRmSqlServerThreatDetectionPolicy</span></span>
    + <span data-ttu-id="44119-154">Set-AzureRmSqlServerThreatDetectionPolicy</span><span class="sxs-lookup"><span data-stu-id="44119-154">Set-AzureRmSqlServerThreatDetectionPolicy</span></span>
  - <span data-ttu-id="44119-155">已新增 Cmdlet 來支援為 Sql Azure DataWarehouse 啟用/停用 GeoBackupPolicy</span><span class="sxs-lookup"><span data-stu-id="44119-155">Added new cmdlets to support enabling/disabling GeoBackupPolicy for Sql Azure DataWarehouses</span></span>
    + <span data-ttu-id="44119-156">Get-AzureRmSqlDatabaseGeoBackupPolicy</span><span class="sxs-lookup"><span data-stu-id="44119-156">Get-AzureRmSqlDatabaseGeoBackupPolicy</span></span>
    + <span data-ttu-id="44119-157">Set-AzureRmSqlDatabaseGeoBackupPolicy</span><span class="sxs-lookup"><span data-stu-id="44119-157">Set-AzureRmSqlDatabaseGeoBackupPolicy</span></span>
  - <span data-ttu-id="44119-158">已新增 Azure Sql Advisor 和建議動作 API 的 Cmdlet</span><span class="sxs-lookup"><span data-stu-id="44119-158">Added new cmdlets for Azure Sql Advisors and Recommended Actions APIs</span></span>
    + <span data-ttu-id="44119-159">Get-AzureRmSqlDatabaseAdvisor</span><span class="sxs-lookup"><span data-stu-id="44119-159">Get-AzureRmSqlDatabaseAdvisor</span></span>
    + <span data-ttu-id="44119-160">Get-AzureRmSqlElasticPoolAdvisor</span><span class="sxs-lookup"><span data-stu-id="44119-160">Get-AzureRmSqlElasticPoolAdvisor</span></span>
    + <span data-ttu-id="44119-161">Get-AzureRmSqlServerAdvisor</span><span class="sxs-lookup"><span data-stu-id="44119-161">Get-AzureRmSqlServerAdvisor</span></span>
    + <span data-ttu-id="44119-162">Get-AzureRmSqlDatabaseRecommendedActions</span><span class="sxs-lookup"><span data-stu-id="44119-162">Get-AzureRmSqlDatabaseRecommendedActions</span></span>
    + <span data-ttu-id="44119-163">Get-AzureRmSqlElasticPoolRecommendedActions</span><span class="sxs-lookup"><span data-stu-id="44119-163">Get-AzureRmSqlElasticPoolRecommendedActions</span></span>
    + <span data-ttu-id="44119-164">Get-AzureRmSqlServerRecommendedActions</span><span class="sxs-lookup"><span data-stu-id="44119-164">Get-AzureRmSqlServerRecommendedActions</span></span>
    + <span data-ttu-id="44119-165">Set-AzureRmSqlDatabaseAdvisorAutoExecuteStatus</span><span class="sxs-lookup"><span data-stu-id="44119-165">Set-AzureRmSqlDatabaseAdvisorAutoExecuteStatus</span></span>
    + <span data-ttu-id="44119-166">Set-AzureRmSqlElasticPoolAdvisorAutoExecuteStatus</span><span class="sxs-lookup"><span data-stu-id="44119-166">Set-AzureRmSqlElasticPoolAdvisorAutoExecuteStatus</span></span>
    + <span data-ttu-id="44119-167">Set-AzureRmSqlServerAdvisorAutoExecuteStatus</span><span class="sxs-lookup"><span data-stu-id="44119-167">Set-AzureRmSqlServerAdvisorAutoExecuteStatus</span></span>
    + <span data-ttu-id="44119-168">Set-AzureRmSqlDatabaseRecommendedActionState</span><span class="sxs-lookup"><span data-stu-id="44119-168">Set-AzureRmSqlDatabaseRecommendedActionState</span></span>
    + <span data-ttu-id="44119-169">Set-AzureRmSqlElasticPoolRecommendedActionState</span><span class="sxs-lookup"><span data-stu-id="44119-169">Set-AzureRmSqlElasticPoolRecommendedActionState</span></span>
    + <span data-ttu-id="44119-170">Set-AzureRmSqlServerRecommendedActionState</span><span class="sxs-lookup"><span data-stu-id="44119-170">Set-AzureRmSqlServerRecommendedActionState</span></span>
