---
title: 管理加载项
description: 管理外接程序。
ms.reviewer: ''
ms.author: serdars
author: serdarsoysal
f1.keywords:
- NOCSH
TOCTitle: Manage add-ins
ms:assetid: b84f868e-b36e-4ab4-b284-7db212d401c3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ205193(v=OCS.15)
ms:contentKeyID: 48185204
ms.date: 07/23/2014
manager: serdars
mtps_version: v=OCS.15
ms.openlocfilehash: f2f381e73d8da33e1347ccc81e7b0d98270827d2
ms.sourcegitcommit: 36fee89bb887bea4f18b19f17a8c69daf5bc423d
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 11/26/2020
ms.locfileid: "49446967"
---
# <a name="manage-add-ins"></a><span data-ttu-id="dbe27-103">管理加载项</span><span class="sxs-lookup"><span data-stu-id="dbe27-103">Manage add-ins</span></span>

<div data-xmlns="http://www.w3.org/1999/xhtml">

<div class="topic" data-xmlns="http://www.w3.org/1999/xhtml" data-msxsl="urn:schemas-microsoft-com:xslt" data-cs="https://msdn.microsoft.com/">

<div data-asp="https://msdn2.microsoft.com/asp">



</div>

<div id="mainSection">

<div id="mainBody"><span data-ttu-id="dbe27-104">

<span> </span></span><span class="sxs-lookup"><span data-stu-id="dbe27-104">

<span> </span></span></span>

<span data-ttu-id="dbe27-105">_**主题上次修改时间：** 2012-10-06_</span><span class="sxs-lookup"><span data-stu-id="dbe27-105">_**Topic Last Modified:** 2012-10-06_</span></span>

<span data-ttu-id="dbe27-106">创建新的持久聊天服务器外接程序</span><span class="sxs-lookup"><span data-stu-id="dbe27-106">To create a new Persistent Chat Server Add-in</span></span>

    New-CsPersistentChatAddin -Name Contoso -PersistentChatPoolFqdn client.contoso.com -Url http://contoso.com 

<div>

## <a name="create-get-set-or-remove-an-add-in"></a><span data-ttu-id="dbe27-107">创建、获取、设置或删除加载项</span><span class="sxs-lookup"><span data-stu-id="dbe27-107">Create, Get, Set, or Remove an Add-in</span></span>

<span data-ttu-id="dbe27-108">创建新的外接程序</span><span class="sxs-lookup"><span data-stu-id="dbe27-108">To create a new Add-in</span></span>

    New-CsPersistentChatAddin -PersistentChatPoolFqdn <String> -Name <String> -Url<String>

<div>


> [!IMPORTANT]  
> <span data-ttu-id="dbe27-109">&lt; &gt; 仅当存在多个持久聊天服务器池时，才需要 PersistentChatPoolFqdn 字符串。</span><span class="sxs-lookup"><span data-stu-id="dbe27-109">PersistentChatPoolFqdn &lt;String&gt; is required only if there is more than one Persistent Chat Server pool.</span></span>



</div>

<span data-ttu-id="dbe27-110">获取加载项</span><span class="sxs-lookup"><span data-stu-id="dbe27-110">To get an Add-in</span></span>

    Get-CsPersistentChatAddin -Identity <String>]

<span data-ttu-id="dbe27-111">或者</span><span class="sxs-lookup"><span data-stu-id="dbe27-111">or</span></span>

    Get-CsPersistentChatAddin -PersistentChatPoolFqdn <String>

<span data-ttu-id="dbe27-112">设置加载项</span><span class="sxs-lookup"><span data-stu-id="dbe27-112">To set an Add-in</span></span>

    Set-CsPersistentChatAddIn -Instance <AddinObject> [-Force <Switch Parameter>] [-Confirm <Switch Parameter>]

<span data-ttu-id="dbe27-113">或者</span><span class="sxs-lookup"><span data-stu-id="dbe27-113">or</span></span>

    Set-CsPersistentChatAddIn -Identity <String> [-Name <String>] [-Url<String>] [-Force <Switch Parameter>] [-Confirm <Switch Parameter>]

<span data-ttu-id="dbe27-114">删除加载项</span><span class="sxs-lookup"><span data-stu-id="dbe27-114">To remove an Add-in</span></span>

    Remove-CsPersistentChatAddIn -Instance <AddinObject> [-Force <Switch Parameter>] [-Confirm <Switch Parameter>]

<span data-ttu-id="dbe27-115">或者</span><span class="sxs-lookup"><span data-stu-id="dbe27-115">or</span></span>

    Remove-CsPersistentChatAddIn -Identity <String> [-Force <Switch Parameter>] [-Confirm <Switch Parameter>]

<span data-ttu-id="dbe27-116"></div>

</div>

<span> </span>

</div>

</div>

</span><span class="sxs-lookup"><span data-stu-id="dbe27-116"></div>

</div>

<span> </span>

</div>

</div>

</span></span></div>

