---
title: 使用 Windows PowerShell Cmdlet 配置持久聊天服务器
description: 使用 Windows PowerShell cmdlet 配置持久聊天服务器。
ms.reviewer: ''
ms.author: serdars
author: serdarsoysal
f1.keywords:
- NOCSH
TOCTitle: Configuring Persistent Chat Server by using Windows PowerShell cmdlets
ms:assetid: 4c1d1ad7-b6bd-476f-9c5b-f0c1756d5aa8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ204877(v=OCS.15)
ms:contentKeyID: 48184089
ms.date: 07/23/2014
manager: serdars
mtps_version: v=OCS.15
ms.openlocfilehash: 39d97657684227ef3c36f6ac39389220a6805f82
ms.sourcegitcommit: 36fee89bb887bea4f18b19f17a8c69daf5bc423d
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 11/24/2020
ms.locfileid: "49392050"
---
# <a name="configuring-persistent-chat-server-by-using-windows-powershell-cmdlets"></a><span data-ttu-id="a87b3-103">使用 Windows PowerShell Cmdlet 配置持久聊天服务器</span><span class="sxs-lookup"><span data-stu-id="a87b3-103">Configuring Persistent Chat Server by using Windows PowerShell cmdlets</span></span>

<div data-xmlns="http://www.w3.org/1999/xhtml">

<div class="topic" data-xmlns="http://www.w3.org/1999/xhtml" data-msxsl="urn:schemas-microsoft-com:xslt" data-cs="https://msdn.microsoft.com/">

<div data-asp="https://msdn2.microsoft.com/asp">



</div>

<div id="mainSection">

<div id="mainBody"><span data-ttu-id="a87b3-104">

<span> </span></span><span class="sxs-lookup"><span data-stu-id="a87b3-104">

<span> </span></span></span>

<span data-ttu-id="a87b3-105">_**主题上次修改时间：** 2012-10-06_</span><span class="sxs-lookup"><span data-stu-id="a87b3-105">_**Topic Last Modified:** 2012-10-06_</span></span>

<span data-ttu-id="a87b3-106">使用以下 Windows PowerShell cmdlet 配置 Lync Server 2013、永久聊天服务器中的管理。</span><span class="sxs-lookup"><span data-stu-id="a87b3-106">Use the following Windows PowerShell cmdlets to configure management within Lync Server 2013, Persistent Chat Server.</span></span>

<div>

## <a name="in-this-section"></a><span data-ttu-id="a87b3-107">本节内容</span><span class="sxs-lookup"><span data-stu-id="a87b3-107">In This Section</span></span>

  - [<span data-ttu-id="a87b3-108">Manage categories</span><span class="sxs-lookup"><span data-stu-id="a87b3-108">Manage categories</span></span>](manage-categories.md)

  - [<span data-ttu-id="a87b3-109">管理聊天室</span><span class="sxs-lookup"><span data-stu-id="a87b3-109">Manage rooms</span></span>](manage-rooms.md)

  - [<span data-ttu-id="a87b3-110">管理加载项</span><span class="sxs-lookup"><span data-stu-id="a87b3-110">Manage add-ins</span></span>](manage-add-ins.md)

  - [<span data-ttu-id="a87b3-111">删除消息</span><span class="sxs-lookup"><span data-stu-id="a87b3-111">Remove a message</span></span>](remove-a-message.md)

  - [<span data-ttu-id="a87b3-112">使用综合事务测试持久聊天服务器</span><span class="sxs-lookup"><span data-stu-id="a87b3-112">Test Persistent Chat Server with a synthetic transaction</span></span>](test-persistent-chat-server-with-a-synthetic-transaction.md)

  - [<span data-ttu-id="a87b3-113">为持久聊天服务器运行向后兼容</span><span class="sxs-lookup"><span data-stu-id="a87b3-113">Run backward compatibility for Persistent Chat Server</span></span>](run-backward-compatibility-for-persistent-chat-server.md)

  - [<span data-ttu-id="a87b3-114">在 Lync Server 2013 中运行、授予、获取、删除或设置持久聊天策略</span><span class="sxs-lookup"><span data-stu-id="a87b3-114">Run, grant, get, remove, or set Persistent Chat Policy in Lync Server 2013</span></span>](lync-server-2013-run-grant-get-remove-or-set-persistent-chat-policy.md)

  - [<span data-ttu-id="a87b3-115">在 Lync Server 2013 中配置持久聊天服务器</span><span class="sxs-lookup"><span data-stu-id="a87b3-115">Configure Persistent Chat Server in Lync Server 2013</span></span>](lync-server-2013-configure-persistent-chat-server.md)

  - [<span data-ttu-id="a87b3-116">在 Lync Server 2013 中获取持久聊天服务器池可用性</span><span class="sxs-lookup"><span data-stu-id="a87b3-116">Get Persistent Chat Server pool availability in Lync Server 2013</span></span>](lync-server-2013-get-persistent-chat-server-pool-availability.md)

  - [<span data-ttu-id="a87b3-117">Lync Server 2013 中的持久聊天合规性</span><span class="sxs-lookup"><span data-stu-id="a87b3-117">Persistent Chat compliance in Lync Server 2013</span></span>](lync-server-2013-persistent-chat-compliance.md)

<span data-ttu-id="a87b3-118"></div>

</div>

<span> </span>

</div>

</div>

</span><span class="sxs-lookup"><span data-stu-id="a87b3-118"></div>

</div>

<span> </span>

</div>

</div>

</span></span></div>

