---
title: "在 macOS 與 Linux 上安裝和設定 Azure PowerShell | Microsoft Docs"
description: "如何在 macOS 與 Linux 上安裝 Azure PowerShell，以及針對初次使用來進行設定。"
services: azure
author: sdwheeler
ms.author: sewhee
manager: carmonm
ms.product: azure
ms.service: azure-powershell
ms.devlang: powershell
ms.topic: conceptual
ms.date: 09/06/2017
ms.openlocfilehash: 94b39c18acaca7a4b17b5207feed025442665acc
ms.sourcegitcommit: 202ec2df66c40a60f47ea06b30a6701ad444d229
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/08/2017
---
# <a name="install-and-configure-azure-powershell-on-macos-and-linux"></a><span data-ttu-id="f3d74-103">在 macOS 與 Linux 上安裝和設定 Azure PowerShell</span><span class="sxs-lookup"><span data-stu-id="f3d74-103">Install and configure Azure PowerShell on macOS and Linux</span></span>

<span data-ttu-id="f3d74-104">現在可以將 PowerShell 6 搶鮮版 (Beta) 與 Azure PowerShell 安裝在非 Windows 平台上。</span><span class="sxs-lookup"><span data-stu-id="f3d74-104">It is now possible to install PowerShell 6 (beta) and Azure PowerShell on non-Windows platforms.</span></span>
<span data-ttu-id="f3d74-105">將 Azure PowerShell 安裝在 macOS 與 Linux 的程序與安裝在 Windows 上沒有不同，但您必須先安裝 PowerShell 6 搶鮮版 (Beta)。</span><span class="sxs-lookup"><span data-stu-id="f3d74-105">The process of installing Azure PowerShell on macOS and Linux is not that different from Windows, however, you must first install PowerShell 6 (beta).</span></span>

> [!NOTE]

> <span data-ttu-id="f3d74-106">PowerShell 6 搶鮮版 (Beta) 與 Azure PowerShell for .NET Core 目前仍處於 Beta 階段。</span><span class="sxs-lookup"><span data-stu-id="f3d74-106">At this time, both PowerShell 6 (beta) and Azure PowerShell for .NET Core are still in beta.</span></span>
> <span data-ttu-id="f3d74-107">這些產品只提供有限支援。</span><span class="sxs-lookup"><span data-stu-id="f3d74-107">Support for these products is limited.</span></span> <span data-ttu-id="f3d74-108">若有問題或發現錯誤，請在 GitHub 中提出。</span><span class="sxs-lookup"><span data-stu-id="f3d74-108">If you have problems or discover bugs, please file Issues in GitHub.</span></span>
>
> * [<span data-ttu-id="f3d74-109">關於 PowerShell 6 搶鮮版 (Beta) 的問題</span><span class="sxs-lookup"><span data-stu-id="f3d74-109">Issues for PowerShell 6 (beta)</span></span>](https://github.com/PowerShell/PowerShell/issues)
> * [<span data-ttu-id="f3d74-110">關於Azure PowerShell 的問題</span><span class="sxs-lookup"><span data-stu-id="f3d74-110">Issues for Azure PowerShell</span></span>](https://github.com/azure/azure-docs-powershell/issues)

## <a name="step-1-install-powershell-6-beta"></a><span data-ttu-id="f3d74-111">步驟 1：安裝 PowerShell 6 搶鮮版 (Beta)</span><span class="sxs-lookup"><span data-stu-id="f3d74-111">Step 1: Install PowerShell 6 (beta)</span></span>

<span data-ttu-id="f3d74-112">PowerShell 6 搶鮮版 (Beta) 安裝程序因目標作業系統而異。</span><span class="sxs-lookup"><span data-stu-id="f3d74-112">The process of installing PowerShell 6 (beta) on varies depending on the target operating system.</span></span>
<span data-ttu-id="f3d74-113">雖然 PowerShell 6 搶鮮版 (Beta) 可以安裝在 Windows 上，但本文只說明在 macOS 與 Linux 上安裝的步驟。</span><span class="sxs-lookup"><span data-stu-id="f3d74-113">While it is possible to install PowerShell 6 (beta) on Windows, this article focuses on macOS and Linux.</span></span> <span data-ttu-id="f3d74-114">如果您想要在 Windows 中使用 Azure PowerShell，請參閱 Windows 適用的[安裝](./install-azurerm-ps.md)文章。</span><span class="sxs-lookup"><span data-stu-id="f3d74-114">If you want to use Azure PowerShell on Windows, see the [install](./install-azurerm-ps.md) article for Windows.</span></span>

<span data-ttu-id="f3d74-115">若要在 Linux 或 macOS 上安裝 **PowerShell 6** 搶鮮版 (Beta)，您必須：</span><span class="sxs-lookup"><span data-stu-id="f3d74-115">To install **PowerShell 6** (beta) on Linux or macOS, you need to:</span></span>

1. <span data-ttu-id="f3d74-116">從 [GitHub](https://github.com/powershell/powershell#get-powershell) 取得特定 OS 與作業系統版本適用的 PowerShell</span><span class="sxs-lookup"><span data-stu-id="f3d74-116">Get PowerShell for the specific OS and version, from [GitHub](https://github.com/powershell/powershell#get-powershell)</span></span>
2. <span data-ttu-id="f3d74-117">依照安裝指示進行</span><span class="sxs-lookup"><span data-stu-id="f3d74-117">Follow the installation instructions</span></span>
   - [<span data-ttu-id="f3d74-118">Linux</span><span class="sxs-lookup"><span data-stu-id="f3d74-118">Linux</span></span>](https://github.com/PowerShell/PowerShell/blob/master/docs/installation/linux.md)
   - [<span data-ttu-id="f3d74-119">macOS</span><span class="sxs-lookup"><span data-stu-id="f3d74-119">macOS</span></span>](https://github.com/PowerShell/PowerShell/blob/master/docs/installation/linux.md#macos-1012)

## <a name="step-2-install-azure-powershell-for-net-core"></a><span data-ttu-id="f3d74-120">步驟 2：安裝 Azure PowerShell for .NET Core</span><span class="sxs-lookup"><span data-stu-id="f3d74-120">Step 2: Install Azure PowerShell for .NET Core</span></span>

<span data-ttu-id="f3d74-121">PowerShell 6 搶鮮版 (Beta) 隨附於已安裝的 PowerShellGet 模組。</span><span class="sxs-lookup"><span data-stu-id="f3d74-121">PowerShell 6 (beta) comes with the PowerShellGet module already installed.</span></span> <span data-ttu-id="f3d74-122">這可讓您輕鬆地安裝任何已發佈到 PowerShell 資源庫的模組。</span><span class="sxs-lookup"><span data-stu-id="f3d74-122">This makes it easy to install any module that is published to the PowerShell Gallery.</span></span> <span data-ttu-id="f3d74-123">若要安裝 Azure PowerShell，請開啟新的 PowerShell 工作階段，並執行下列命令：</span><span class="sxs-lookup"><span data-stu-id="f3d74-123">To install Azure PowerShell, open a new PowerShell session and run the following command:</span></span>

```powershell
Install-Module AzureRM.NetCore
```

## <a name="step-3-load-the-azurermnetcore-module"></a><span data-ttu-id="f3d74-124">步驟 3：載入 AzureRM.Netcore 模組</span><span class="sxs-lookup"><span data-stu-id="f3d74-124">Step 3: Load the AzureRM.Netcore module</span></span>

<span data-ttu-id="f3d74-125">安裝模組後，您需要將模組載入您的 PowerShell 工作階段。</span><span class="sxs-lookup"><span data-stu-id="f3d74-125">Once the module is installed, you need to load the module into your PowerShell session.</span></span> <span data-ttu-id="f3d74-126">使用 `Import-Module`Cmdlet 載入模組，如下所示︰</span><span class="sxs-lookup"><span data-stu-id="f3d74-126">Modules are loaded using the `Import-Module` cmdlet, as follows:</span></span>

```powershell
Import-Module AzureRM.Netcore
```

<span data-ttu-id="f3d74-127">匯入完成後，您可以嘗試使用下列命令登入 Azure，來測試新安裝的模組：</span><span class="sxs-lookup"><span data-stu-id="f3d74-127">After the import completes, you can test your newly installed and module by attempting to sign into Azure using the following command:</span></span>

```powershell
Login-AzureRMAccount
```

<span data-ttu-id="f3d74-128">上述命令應會提示您移至 `https://aka.ms/devicelogin`，並輸入您收到的驗證碼。</span><span class="sxs-lookup"><span data-stu-id="f3d74-128">The above command should prompt you to go to `https://aka.ms/devicelogin` and enter the provided code.</span></span>

## <a name="available-cmdlets"></a><span data-ttu-id="f3d74-129">可用的 Cmdlet</span><span class="sxs-lookup"><span data-stu-id="f3d74-129">Available cmdlets</span></span>

<span data-ttu-id="f3d74-130">Azure PowerShell modules for .NET Standard 模組仍在開發中。</span><span class="sxs-lookup"><span data-stu-id="f3d74-130">The Azure PowerShell modules for .NET Standard are still in development.</span></span> <span data-ttu-id="f3d74-131">這些模組未提供適用於 Windows 版模組的所有 Cmdlet。</span><span class="sxs-lookup"><span data-stu-id="f3d74-131">These modules do not provide the full set of cmdlets that are available for the Windows version of the modules.</span></span> <span data-ttu-id="f3d74-132">AzureRM.Netcore 模組實作了下列功能：</span><span class="sxs-lookup"><span data-stu-id="f3d74-132">The following functions are implemented in AzureRM.Netcore modules:</span></span>

* <span data-ttu-id="f3d74-133">帳戶管理</span><span class="sxs-lookup"><span data-stu-id="f3d74-133">Account management</span></span>
  - <span data-ttu-id="f3d74-134">透過 Microsoft Azure Active Directory，以 Microsoft 帳戶、組織帳戶或服務主體登入</span><span class="sxs-lookup"><span data-stu-id="f3d74-134">Login with Microsoft account, Organizational account, or Service Principal through Microsoft Azure Active Directory</span></span>
  - <span data-ttu-id="f3d74-135">透過 Save-AzureRmContext 將認證儲存到磁碟上，及使用 Import-AzureRmContext 載入儲存的認證</span><span class="sxs-lookup"><span data-stu-id="f3d74-135">Save Credentials to disk with Save-AzureRmContext and load saved credentials using Import-AzureRmContext</span></span>
* <span data-ttu-id="f3d74-136">Environment</span><span class="sxs-lookup"><span data-stu-id="f3d74-136">Environment</span></span>
  - <span data-ttu-id="f3d74-137">取得其他現成可用的 Microsoft Azure 環境</span><span class="sxs-lookup"><span data-stu-id="f3d74-137">Get the different out-of-box Microsoft Azure environments</span></span>
  - <span data-ttu-id="f3d74-138">新增/設定/移除自訂環境 (例如 Azure Stack 或 Windows Azure 套件環境)</span><span class="sxs-lookup"><span data-stu-id="f3d74-138">Add/Set/Remove customized environments (like your Azure Stack or Windows Azure Pack environments)</span></span>
* <span data-ttu-id="f3d74-139">使用資源管理員與服務管理介面之 Azure 服務適用的管理平面 Cmdlet。</span><span class="sxs-lookup"><span data-stu-id="f3d74-139">Management plane cmdlets for Azure services using Resource Manager and Service Management interfaces.</span></span>
  - <span data-ttu-id="f3d74-140">虛擬機器</span><span class="sxs-lookup"><span data-stu-id="f3d74-140">Virtual Machine</span></span>
  - <span data-ttu-id="f3d74-141">App Service (網站)</span><span class="sxs-lookup"><span data-stu-id="f3d74-141">App Service (Websites)</span></span>
  - <span data-ttu-id="f3d74-142">SQL Database</span><span class="sxs-lookup"><span data-stu-id="f3d74-142">SQL Database</span></span>
  - <span data-ttu-id="f3d74-143">儲存體</span><span class="sxs-lookup"><span data-stu-id="f3d74-143">Storage</span></span>
  - <span data-ttu-id="f3d74-144">網路</span><span class="sxs-lookup"><span data-stu-id="f3d74-144">Network</span></span>

## <a name="next-steps"></a><span data-ttu-id="f3d74-145">後續步驟</span><span class="sxs-lookup"><span data-stu-id="f3d74-145">Next Steps</span></span>

<span data-ttu-id="f3d74-146">如需有關使用 Azure PowerShell 的詳細資訊，請參閱[開始使用 Azure PowerShell](get-started-azureps.md)文章。</span><span class="sxs-lookup"><span data-stu-id="f3d74-146">For more information about using Azure PowerShell, see the [Get started with Azure PowerShell](get-started-azureps.md) article.</span></span>
