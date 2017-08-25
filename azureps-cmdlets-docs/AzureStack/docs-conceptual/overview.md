---
title: "Azure Stack PowerShell 概觀 | Microsoft Docs"
description: "Azure Stack PowerShell 安裝和設定概觀。"
author: SnehaGunda
manager: Byronr
ms.product: azure-stack
ms.service: powershell
ms.devlang: powershell
ms.topic: reference
ms.author: sngun
ms.manager: byronr
ms.openlocfilehash: 2a03697e0f3e80d63c48f2dc5615f6c99b9ef716
ms.sourcegitcommit: 226527be7cb647acfe2ea9ab151185053ab3c6db
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 06/29/2017
---
# <a name="azure-stack-powershell"></a><span data-ttu-id="70843-103">Azure Stack PowerShell</span><span class="sxs-lookup"><span data-stu-id="70843-103">Azure Stack PowerShell</span></span> 

<span data-ttu-id="70843-104">Azure Stack 需要下列兩個 PowerShell 模組：</span><span class="sxs-lookup"><span data-stu-id="70843-104">Azure Stack requires the following two PowerShell modules:</span></span>  

1. <span data-ttu-id="70843-105">Azure Stack 相容的 **AzureRM** 模組，可藉由安裝 **2017-03-09-profile** API 版本設定檔來取得。</span><span class="sxs-lookup"><span data-stu-id="70843-105">The Azure Stack compatible **AzureRM** module which is available by installing the **2017-03-09-profile** API Version Profile.</span></span> <span data-ttu-id="70843-106">使用此設定檔安裝的 Cmdlet 可以供 Azure Stack 雲端系統管理員和租用戶使用。</span><span class="sxs-lookup"><span data-stu-id="70843-106">The cmdlets installed by using this profile can be used by the Azure Stack cloud administrators and the tenants.</span></span> <span data-ttu-id="70843-107">若要了解此設定檔中可用的 PowerShell Cmdlet，請參閱 PowerShell 參考內容中的 [1.2.9 版 AzureRM](https://docs.microsoft.com/en-us/powershell/azure/overview?view=azurermps-1.2.9) 模組。</span><span class="sxs-lookup"><span data-stu-id="70843-107">To learn about the PowerShell cmdlets that are available in this profile, see the PowerShell reference content for the [1.2.9 version of AzureRM](https://docs.microsoft.com/en-us/powershell/azure/overview?view=azurermps-1.2.9) module.</span></span>  

2. <span data-ttu-id="70843-108">**1.2.9** 版的 **AzureStack** 模組。</span><span class="sxs-lookup"><span data-stu-id="70843-108">The **1.2.9** version of the **AzureStack** module.</span></span> <span data-ttu-id="70843-109">使用此模組安裝的 Cmdlet 只可以供 Azure Stack 雲端系統管理員使用。</span><span class="sxs-lookup"><span data-stu-id="70843-109">The cmdlets installed by using this module can be used by Azure Stack cloud administrators only.</span></span> <span data-ttu-id="70843-110">系統管理員可以使用此模組所提供的 PowerShell Cmdlet 來執行各項作業，例如管理供應項目、方案、服務、配額等。</span><span class="sxs-lookup"><span data-stu-id="70843-110">Administrator can perform operations such as manage offers, plans, services, quotas, etc. by using the PowerShell cmdlets provided by this module.</span></span> <span data-ttu-id="70843-111">若要了解此模組中可用的 PowerShell Cmdlet，請參閱 [AzureStackAdmin](https://docs.microsoft.com/en-us/powershell/module/azurerm.azurestackadmin/?view=azurestackps-1.2.9#azurerm.azurestackadmin) 和 [AzureStackStorage](https://docs.microsoft.com/en-us/powershell/module/azurerm.azurestackstorage/?view=azurestackps-1.2.9#azurerm.azurestackstorage) 參考內容。</span><span class="sxs-lookup"><span data-stu-id="70843-111">To learn about the PowerShell cmdlets available in this module, see the [AzureStackAdmin](https://docs.microsoft.com/en-us/powershell/module/azurerm.azurestackadmin/?view=azurestackps-1.2.9#azurerm.azurestackadmin) and [AzureStackStorage](https://docs.microsoft.com/en-us/powershell/module/azurerm.azurestackstorage/?view=azurestackps-1.2.9#azurerm.azurestackstorage) Reference content.</span></span>

## <a name="next-steps"></a><span data-ttu-id="70843-112">後續步驟</span><span class="sxs-lookup"><span data-stu-id="70843-112">Next Steps</span></span>

* [<span data-ttu-id="70843-113">安裝 Azure Stack 適用的 PowerShell</span><span class="sxs-lookup"><span data-stu-id="70843-113">Install PowerShell for Azure Stack</span></span>](https://docs.microsoft.com/en-us/azure/azure-stack/azure-stack-powershell-install?view=azurestackps-1.2.9&toc=%2fpowershell%2fmodule%2ftoc.json%3fview%3dazurestackps-1.2.9&view=azurestackps-1.2.9)
* [<span data-ttu-id="70843-114">設定 PowerShell 以便搭配 Azure Stack 使用</span><span class="sxs-lookup"><span data-stu-id="70843-114">Configure PowerShell for use with Azure Stack</span></span>](https://docs.microsoft.com/en-us/azure/azure-stack/azure-stack-powershell-configure?view=azurestackps-1.2.9&toc=%2fpowershell%2fmodule%2ftoc.json%3fview%3dazurestackps-1.2.9&view=azurestackps-1.2.9)


