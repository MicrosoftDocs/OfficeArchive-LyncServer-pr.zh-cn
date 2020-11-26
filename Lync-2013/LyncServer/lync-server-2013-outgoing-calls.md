---
title: Lync Server 2013：传出呼叫
description: Lync Server 2013：传出呼叫。
ms.reviewer: ''
ms.author: v-lanac
author: lanachin
f1.keywords:
- NOCSH
TOCTitle: Outgoing calls
ms:assetid: 885ffe6f-cd51-4f21-8d4f-a1ff8d818858
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ994049(v=OCS.15)
ms:contentKeyID: 51803960
ms.date: 07/23/2014
manager: serdars
mtps_version: v=OCS.15
ms.openlocfilehash: e14f19dec35a6da47a2ddd62657d5d087a854f16
ms.sourcegitcommit: 36fee89bb887bea4f18b19f17a8c69daf5bc423d
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 11/26/2020
ms.locfileid: "49424833"
---
# <a name="outgoing-calls-in-lync-server-2013"></a><span data-ttu-id="fd50d-103">Lync Server 2013 中的传出呼叫</span><span class="sxs-lookup"><span data-stu-id="fd50d-103">Outgoing calls in Lync Server 2013</span></span>

<div data-xmlns="http://www.w3.org/1999/xhtml">

<div class="topic" data-xmlns="http://www.w3.org/1999/xhtml" data-msxsl="urn:schemas-microsoft-com:xslt" data-cs="https://msdn.microsoft.com/">

<div data-asp="https://msdn2.microsoft.com/asp">



</div>

<div id="mainSection">

<div id="mainBody"><span data-ttu-id="fd50d-104">

<span> </span></span><span class="sxs-lookup"><span data-stu-id="fd50d-104">

<span> </span></span></span>

<span data-ttu-id="fd50d-105">_**主题上次修改时间：** 2013-03-09_</span><span class="sxs-lookup"><span data-stu-id="fd50d-105">_**Topic Last Modified:** 2013-03-09_</span></span>

<span data-ttu-id="fd50d-106">为 Location-Based 路由启用的用户的出站呼叫的路由受用户终结点的网络位置的影响。</span><span class="sxs-lookup"><span data-stu-id="fd50d-106">The routing of outbound calls of users enabled for Location-Based Routing is affected by the network location of the user’s endpoint.</span></span> <span data-ttu-id="fd50d-107">下表说明了 Location-Based 路由如何影响出站呼叫的路由，具体取决于呼叫者终结点的位置。</span><span class="sxs-lookup"><span data-stu-id="fd50d-107">The following table illustrates how Location-Based Routing affects the routing of outbound calls depending on the location of the caller’s endpoint.</span></span>

### <a name="caller-placing-an-outbound-call-to-the-pstn"></a><span data-ttu-id="fd50d-108">向 PSTN 发出出站呼叫的呼叫者</span><span class="sxs-lookup"><span data-stu-id="fd50d-108">Caller placing an outbound call to the PSTN</span></span>

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th></th>
<th><span data-ttu-id="fd50d-109">位于启用了基于位置的路由的网络站点中的用户终结点</span><span class="sxs-lookup"><span data-stu-id="fd50d-109">User endpoint located in a network site enabled for Location-Based Routing</span></span></th>
<th><span data-ttu-id="fd50d-110">位于未知网络站点或者未启用基于位置的路由的网络站点中的用户终结点</span><span class="sxs-lookup"><span data-stu-id="fd50d-110">User endpoint located in unknown network site or not enabled for Location-Based Routing</span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><span data-ttu-id="fd50d-111">出站呼叫授权</span><span class="sxs-lookup"><span data-stu-id="fd50d-111">Authorization of outbound calls</span></span></p></td>
<td><p><span data-ttu-id="fd50d-112">基于用户的语音策略授权呼叫</span><span class="sxs-lookup"><span data-stu-id="fd50d-112">Call is authorized based on user’s voice policy</span></span></p></td>
<td><p><span data-ttu-id="fd50d-113">基于用户的语音策略授权呼叫</span><span class="sxs-lookup"><span data-stu-id="fd50d-113">Call is authorized based on user’s voice policy</span></span></p></td>
</tr>
<tr class="even">
<td><p><span data-ttu-id="fd50d-114">出站呼叫路由</span><span class="sxs-lookup"><span data-stu-id="fd50d-114">Routing of outbound call</span></span></p></td>
<td><p><span data-ttu-id="fd50d-115">根据网络站点的语音路由策略路由呼叫</span><span class="sxs-lookup"><span data-stu-id="fd50d-115">Call is routed according to the network site’s voice routing policy</span></span></p></td>
<td><p><span data-ttu-id="fd50d-116">根据用户的语音策略仅通过未启用基于位置的路由的中继路由呼叫（如果可用）</span><span class="sxs-lookup"><span data-stu-id="fd50d-116">Call is routed according to user’s voice policy and only through trunks not enabled for Location-Based Routing (if available)</span></span></p></td>
</tr>
</tbody>
</table>


<div>

## <a name="see-also"></a><span data-ttu-id="fd50d-117">另请参阅</span><span class="sxs-lookup"><span data-stu-id="fd50d-117">See Also</span></span>


[<span data-ttu-id="fd50d-118">Lync Server 2013 中基于位置的路由的方案</span><span class="sxs-lookup"><span data-stu-id="fd50d-118">Scenarios for Location-Based Routing in Lync Server 2013</span></span>](lync-server-2013-scenarios-for-location-based-routing.md)  
  

<span data-ttu-id="fd50d-119"></div>

</div>

<span> </span>

</div>

</div>

</span><span class="sxs-lookup"><span data-stu-id="fd50d-119"></div>

</div>

<span> </span>

</div>

</div>

</span></span></div>

