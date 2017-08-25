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
# <a name="azure-stack-powershell"></a>Azure Stack PowerShell 

Azure Stack 需要下列兩個 PowerShell 模組：  

1. Azure Stack 相容的 **AzureRM** 模組，可藉由安裝 **2017-03-09-profile** API 版本設定檔來取得。 使用此設定檔安裝的 Cmdlet 可以供 Azure Stack 雲端系統管理員和租用戶使用。 若要了解此設定檔中可用的 PowerShell Cmdlet，請參閱 PowerShell 參考內容中的 [1.2.9 版 AzureRM](https://docs.microsoft.com/en-us/powershell/azure/overview?view=azurermps-1.2.9) 模組。  

2. **1.2.9** 版的 **AzureStack** 模組。 使用此模組安裝的 Cmdlet 只可以供 Azure Stack 雲端系統管理員使用。 系統管理員可以使用此模組所提供的 PowerShell Cmdlet 來執行各項作業，例如管理供應項目、方案、服務、配額等。 若要了解此模組中可用的 PowerShell Cmdlet，請參閱 [AzureStackAdmin](https://docs.microsoft.com/en-us/powershell/module/azurerm.azurestackadmin/?view=azurestackps-1.2.9#azurerm.azurestackadmin) 和 [AzureStackStorage](https://docs.microsoft.com/en-us/powershell/module/azurerm.azurestackstorage/?view=azurestackps-1.2.9#azurerm.azurestackstorage) 參考內容。

## <a name="next-steps"></a>後續步驟

* [安裝 Azure Stack 適用的 PowerShell](https://docs.microsoft.com/en-us/azure/azure-stack/azure-stack-powershell-install?view=azurestackps-1.2.9&toc=%2fpowershell%2fmodule%2ftoc.json%3fview%3dazurestackps-1.2.9&view=azurestackps-1.2.9)
* [設定 PowerShell 以便搭配 Azure Stack 使用](https://docs.microsoft.com/en-us/azure/azure-stack/azure-stack-powershell-configure?view=azurestackps-1.2.9&toc=%2fpowershell%2fmodule%2ftoc.json%3fview%3dazurestackps-1.2.9&view=azurestackps-1.2.9)


