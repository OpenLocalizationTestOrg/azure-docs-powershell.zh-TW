---
title: "Azure PowerShell 概觀 | Microsoft Docs"
description: "Azure PowerShell 的概觀以及有關安裝和設定的連結。"
author: sdwheeler
ms.author: sewhee
manager: carmonm
ms.product: azure
ms.service: azure-powershell
ms.devlang: powershell
ms.topic: conceptual
ms.manager: carmonm
ms.date: 07/26/2017
ms.openlocfilehash: 3772b68949dc9dba110e6015c8d2a8b944b26528
ms.sourcegitcommit: 20bcef86db4e4869125bb63085fcffd009c19280
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/27/2017
---
# <a name="overview-of-azure-powershell"></a><span data-ttu-id="c39a5-103">Azure PowerShell 的概觀</span><span class="sxs-lookup"><span data-stu-id="c39a5-103">Overview of Azure PowerShell</span></span>

<span data-ttu-id="c39a5-104">Azure PowerShell 提供了一組 Cmdlet，它們會使用 [Azure Resource Manager](/azure/azure-resource-manager/resource-group-overview) 模型來管理 Azure 資源。</span><span class="sxs-lookup"><span data-stu-id="c39a5-104">Azure PowerShell provides a set of cmdlets that use the [Azure Resource Manager](/azure/azure-resource-manager/resource-group-overview) model for managing your Azure resources.</span></span>

<span data-ttu-id="c39a5-105">檢閱[安裝文章](install-azurerm-ps.md)將 Azure PowerShell 啟動並在您的系統上執行。</span><span class="sxs-lookup"><span data-stu-id="c39a5-105">Review the [Install](install-azurerm-ps.md) article to get Azure PowerShell up and running on your system.</span></span> <span data-ttu-id="c39a5-106">接著請閱讀[開始](get-started-azureps.md)文件以開始使用它。</span><span class="sxs-lookup"><span data-stu-id="c39a5-106">Then read the [Get Started](get-started-azureps.md) article to begin using it.</span></span> <span data-ttu-id="c39a5-107">如需最新版本的相關資訊，請參閱[版本資訊](release-notes-azureps.md)。</span><span class="sxs-lookup"><span data-stu-id="c39a5-107">For information about the latest release, see the [release notes](release-notes-azureps.md).</span></span>

<span data-ttu-id="c39a5-108">下列範例可協助您了解如何使用 Azure PowerShell 來執行常見案例：</span><span class="sxs-lookup"><span data-stu-id="c39a5-108">The following samples can help you learn how to perform common scenarios with Azure PowerShell:</span></span>

* [<span data-ttu-id="c39a5-109">Linux 虛擬機器</span><span class="sxs-lookup"><span data-stu-id="c39a5-109">Linux Virtual Machines</span></span>](/azure/virtual-machines/virtual-machines-linux-powershell-samples?toc=/powershell/azure/toc.json)
* [<span data-ttu-id="c39a5-110">Windows 虛擬機器</span><span class="sxs-lookup"><span data-stu-id="c39a5-110">Windows Virtual Machines</span></span>](/azure/virtual-machines/virtual-machines-windows-powershell-samples?toc=/powershell/azure/toc.json)
* [<span data-ttu-id="c39a5-111">Web Apps</span><span class="sxs-lookup"><span data-stu-id="c39a5-111">Web Apps</span></span>](/azure/app-service-web/app-service-powershell-samples?toc=/powershell/azure/toc.json)
* [<span data-ttu-id="c39a5-112">SQL Databases</span><span class="sxs-lookup"><span data-stu-id="c39a5-112">SQL Databases</span></span>](/azure/sql-database/sql-database-powershell-samples?toc=/powershell/azure/toc.json)


> [!NOTE]<span data-ttu-id="c39a5-113"> > 如果您的部署使用無法轉換的傳統部署模型，您可以安裝 Azure PowerShell 的服務管理版本。</span><span class="sxs-lookup"><span data-stu-id="c39a5-113"> > If you have deployments that use the classic deployment model that cannot be converted, you can install the Service Management version of Azure PowerShell.</span></span> <span data-ttu-id="c39a5-114">如需詳細資訊，請參閱[安裝 Azure PowerShell 服務管理模組](/powershell/azure/servicemanagement/install-azure-ps)。</span><span class="sxs-lookup"><span data-stu-id="c39a5-114">For more information, see [Install the Azure PowerShell Service Management module](/powershell/azure/servicemanagement/install-azure-ps).</span></span>


### <a name="need-help-with-powershell"></a><span data-ttu-id="c39a5-115">需要有關 PowerShell 的協助嗎？</span><span class="sxs-lookup"><span data-stu-id="c39a5-115">Need help with PowerShell?</span></span>

<span data-ttu-id="c39a5-116">如果您不熟悉 PowerShell，則 PowerShell 的簡介會很有幫助。</span><span class="sxs-lookup"><span data-stu-id="c39a5-116">If you are unfamiliar with PowerShell, you may find an introduction to PowerShell helpful.</span></span> <span data-ttu-id="c39a5-117">若要開始使用 PowerShell，請參閱[使用 PowerShell 編寫指令碼](https://technet.microsoft.com/library/bb978526.aspx)。</span><span class="sxs-lookup"><span data-stu-id="c39a5-117">To get started with PowerShell, see [Scripting with PowerShell](https://technet.microsoft.com/library/bb978526.aspx).</span></span>

<span data-ttu-id="c39a5-118">您也可以觀賞這段影片︰[PowerShell 基本概念：(第 1 部分) 開始使用 PowerShell](https://channel9.msdn.com/Blogs/Taste-of-Premier/PowerShellBasicsPart1)。</span><span class="sxs-lookup"><span data-stu-id="c39a5-118">You can also watch this video: [PowerShell Basics: (Part 1) Getting Started with PowerShell](https://channel9.msdn.com/Blogs/Taste-of-Premier/PowerShellBasicsPart1).</span></span>

## <a name="other-azure-powershell-modules"></a><span data-ttu-id="c39a5-119">其他 Azure Powershell 模組</span><span class="sxs-lookup"><span data-stu-id="c39a5-119">Other Azure PowerShell modules</span></span>

* [<span data-ttu-id="c39a5-120">Azure Active Directory</span><span class="sxs-lookup"><span data-stu-id="c39a5-120">Azure Active Directory</span></span>](/powershell/azure/active-directory/)
* [<span data-ttu-id="c39a5-121">Azure 資訊保護</span><span class="sxs-lookup"><span data-stu-id="c39a5-121">Azure Information Protection</span></span>](/powershell/azure/aip/)
* [<span data-ttu-id="c39a5-122">Azure Service Fabric</span><span class="sxs-lookup"><span data-stu-id="c39a5-122">Azure Service Fabric</span></span>](/powershell/azure/service-fabric/)
* [<span data-ttu-id="c39a5-123">Azure ElasticDB</span><span class="sxs-lookup"><span data-stu-id="c39a5-123">Azure ElasticDB</span></span>](/powershell/azure/elasticdbjobs/)
