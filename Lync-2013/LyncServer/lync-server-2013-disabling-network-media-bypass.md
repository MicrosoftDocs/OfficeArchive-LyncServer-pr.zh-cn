---
title: Lync Server 2013：禁用网络媒体旁路
description: Lync Server 2013：禁用网络媒体旁路。
ms.reviewer: ''
ms.author: v-lanac
author: lanachin
f1.keywords:
- NOCSH
TOCTitle: Disabling network media bypass
ms:assetid: 936d2678-d712-4589-b172-b5793013652f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ688141(v=OCS.15)
ms:contentKeyID: 49733741
ms.date: 07/23/2014
manager: serdars
mtps_version: v=OCS.15
ms.openlocfilehash: 1472711417218aa87936a3ccabe1bb465dd07c20
ms.sourcegitcommit: 36fee89bb887bea4f18b19f17a8c69daf5bc423d
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 11/26/2020
ms.locfileid: "49429096"
---
# <a name="disabling-network-media-bypass-in-lync-server-2013"></a><span data-ttu-id="58d3a-103">在 Lync Server 2013 中禁用网络媒体旁路</span><span class="sxs-lookup"><span data-stu-id="58d3a-103">Disabling network media bypass in Lync Server 2013</span></span>

<div data-xmlns="http://www.w3.org/1999/xhtml">

<div class="topic" data-xmlns="http://www.w3.org/1999/xhtml" data-msxsl="urn:schemas-microsoft-com:xslt" data-cs="https://msdn.microsoft.com/">

<div data-asp="https://msdn2.microsoft.com/asp">



</div>

<div id="mainSection">

<div id="mainBody"><span data-ttu-id="58d3a-104">

<span> </span></span><span class="sxs-lookup"><span data-stu-id="58d3a-104">

<span> </span></span></span>

<span data-ttu-id="58d3a-105">_**主题上次修改时间：** 2012-10-15_</span><span class="sxs-lookup"><span data-stu-id="58d3a-105">_**Topic Last Modified:** 2012-10-15_</span></span>

<span data-ttu-id="58d3a-106">媒体绕过设置在 Microsoft Lync Server 2013 部署中全局应用。</span><span class="sxs-lookup"><span data-stu-id="58d3a-106">Media bypass settings apply globally across a Microsoft Lync Server 2013 deployment.</span></span> <span data-ttu-id="58d3a-107">媒体绕过允许呼叫绕过中介服务器。</span><span class="sxs-lookup"><span data-stu-id="58d3a-107">Media bypass allows calls to bypass the Mediation Server.</span></span> <span data-ttu-id="58d3a-108">有关何时使用 "媒体绕过" 的详细信息，请参阅 "规划" 部分中的 " [在 Lync Server 2013 中规划媒体旁路](lync-server-2013-planning-for-media-bypass.md) "。可以从 Lync Server 控制面板禁用 "媒体绕过"。</span><span class="sxs-lookup"><span data-stu-id="58d3a-108">For details about when to use Media bypass, see [Planning for media bypass in Lync Server 2013](lync-server-2013-planning-for-media-bypass.md) in the Planning section.You can disable media bypass from the Lync Server Control Panel.</span></span> <span data-ttu-id="58d3a-109">有关启用和配置中间词跳过的详细信息，请参阅 [在 Lync Server 2013 中启用网络媒体旁路](lync-server-2013-enabling-network-media-bypass.md)</span><span class="sxs-lookup"><span data-stu-id="58d3a-109">For details on enabling and configuring medial bypass, see [Enabling network media bypass in Lync Server 2013](lync-server-2013-enabling-network-media-bypass.md)</span></span>

<div>

## <a name="to-disable-media-bypass"></a><span data-ttu-id="58d3a-110">禁用媒体绕过</span><span class="sxs-lookup"><span data-stu-id="58d3a-110">To disable media bypass</span></span>

1.  <span data-ttu-id="58d3a-111">使用 RTCUniversalServerAdmins 组成员（或具有同等用户权限）的用户帐户，或分配给 CsAdministrator 角色的用户帐户，登录到内部部署中的任何计算机。</span><span class="sxs-lookup"><span data-stu-id="58d3a-111">From a user account that is a member of the RTCUniversalServerAdmins group (or has equivalent user rights), or is assigned to the CsAdministrator role, log on to any computer in your internal deployment.</span></span>

2.  <span data-ttu-id="58d3a-112">打开一个浏览器窗口，然后输入 "管理员" URL 以打开 Lync Server "控制面板"。</span><span class="sxs-lookup"><span data-stu-id="58d3a-112">Open a browser window, and then enter the Admin URL to open the Lync Server Control Panel.</span></span> <span data-ttu-id="58d3a-113">有关可用于启动 Lync Server "控制面板" 的不同方法的详细信息，请参阅 [打开 Lync server 2013 管理工具](lync-server-2013-open-lync-server-administrative-tools.md)。</span><span class="sxs-lookup"><span data-stu-id="58d3a-113">For details about the different methods you can use to start Lync Server Control Panel, see [Open Lync Server 2013 administrative tools](lync-server-2013-open-lync-server-administrative-tools.md).</span></span>

3.  <span data-ttu-id="58d3a-114">在左侧导航栏中，单击 " **网络配置** "，然后单击 " **全局**"。</span><span class="sxs-lookup"><span data-stu-id="58d3a-114">In the left navigation bar, click **Network Configuration** and then click **Global**.</span></span>

4.  <span data-ttu-id="58d3a-115">在 " **全局** " 页面上，单击 " **全局** 配置"。</span><span class="sxs-lookup"><span data-stu-id="58d3a-115">On the **Global** page, click the **Global** configuration.</span></span> <span data-ttu-id="58d3a-116">始终只有一种配置，它始终名为 Global。</span><span class="sxs-lookup"><span data-stu-id="58d3a-116">There is always only one configuration, and it is always named Global.</span></span>

5.  <span data-ttu-id="58d3a-117">在 " **编辑** " 菜单上，单击 " **查看详细信息**"。</span><span class="sxs-lookup"><span data-stu-id="58d3a-117">On the **Edit** menu, click **View details**.</span></span>

6.  <span data-ttu-id="58d3a-118">在 " **编辑全局设置** " 页面上，清除 " **启用绕过媒体** " 复选框。</span><span class="sxs-lookup"><span data-stu-id="58d3a-118">On the **Edit Global Setting** page, clear the **Enable media bypass** check box.</span></span>

7.  <span data-ttu-id="58d3a-119">单击 " **提交** " 保存所做的更改。</span><span class="sxs-lookup"><span data-stu-id="58d3a-119">Click **Commit** to save your changes.</span></span>

</div>

<div>

## <a name="see-also"></a><span data-ttu-id="58d3a-120">另请参阅</span><span class="sxs-lookup"><span data-stu-id="58d3a-120">See Also</span></span>


[<span data-ttu-id="58d3a-121">在 Lync Server 2013 中启用网络媒体旁路</span><span class="sxs-lookup"><span data-stu-id="58d3a-121">Enabling network media bypass in Lync Server 2013</span></span>](lync-server-2013-enabling-network-media-bypass.md)  
  

<span data-ttu-id="58d3a-122"></div>

</div>

<span> </span>

</div>

</div>

</span><span class="sxs-lookup"><span data-stu-id="58d3a-122"></div>

</div>

<span> </span>

</div>

</div>

</span></span></div>

