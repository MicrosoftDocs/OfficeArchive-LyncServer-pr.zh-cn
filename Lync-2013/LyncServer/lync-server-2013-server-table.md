---
title: Lync Server 2013：Server 表
description: Lync Server 2013：服务器表。
ms.reviewer: ''
ms.author: v-lanac
author: lanachin
f1.keywords:
- NOCSH
TOCTitle: Server table
ms:assetid: 9af89d08-d35a-48e8-b56d-6df292f973cc
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg398801(v=OCS.15)
ms:contentKeyID: 48184890
ms.date: 07/23/2014
manager: serdars
mtps_version: v=OCS.15
ms.openlocfilehash: 00990a91aec64063480d96a16380171990913ad4
ms.sourcegitcommit: 36fee89bb887bea4f18b19f17a8c69daf5bc423d
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 11/26/2020
ms.locfileid: "49441849"
---
# <a name="server-table-in-lync-server-2013"></a><span data-ttu-id="cf55f-103">Lync Server 2013 中的 Server  表</span><span class="sxs-lookup"><span data-stu-id="cf55f-103">Server table in Lync Server 2013</span></span>

<div data-xmlns="http://www.w3.org/1999/xhtml">

<div class="topic" data-xmlns="http://www.w3.org/1999/xhtml" data-msxsl="urn:schemas-microsoft-com:xslt" data-cs="https://msdn.microsoft.com/">

<div data-asp="https://msdn2.microsoft.com/asp">



</div>

<div id="mainSection">

<div id="mainBody"><span data-ttu-id="cf55f-104">

<span> </span></span><span class="sxs-lookup"><span data-stu-id="cf55f-104">

<span> </span></span></span>

<span data-ttu-id="cf55f-105">_**主题上次修改时间：** 2012-10-02_</span><span class="sxs-lookup"><span data-stu-id="cf55f-105">_**Topic Last Modified:** 2012-10-02_</span></span>

<span data-ttu-id="cf55f-106">服务器表是支持表。</span><span class="sxs-lookup"><span data-stu-id="cf55f-106">The Server table is a supporting table.</span></span> <span data-ttu-id="cf55f-107">每条记录代表一台服务器。</span><span class="sxs-lookup"><span data-stu-id="cf55f-107">Each record represents one server.</span></span>


<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="cf55f-108"><strong>列</strong></span><span class="sxs-lookup"><span data-stu-id="cf55f-108"><strong>Column</strong></span></span></th>
<th><span data-ttu-id="cf55f-109"><strong>数据类型</strong></span><span class="sxs-lookup"><span data-stu-id="cf55f-109"><strong>Data Type</strong></span></span></th>
<th><span data-ttu-id="cf55f-110"><strong>键/索引</strong></span><span class="sxs-lookup"><span data-stu-id="cf55f-110"><strong>Key/Index</strong></span></span></th>
<th><span data-ttu-id="cf55f-111"><strong>Details</strong></span><span class="sxs-lookup"><span data-stu-id="cf55f-111"><strong>Details</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><span data-ttu-id="cf55f-112"><strong>ServerKey</strong></span><span class="sxs-lookup"><span data-stu-id="cf55f-112"><strong>ServerKey</strong></span></span></p></td>
<td><p><span data-ttu-id="cf55f-113">int</span><span class="sxs-lookup"><span data-stu-id="cf55f-113">int</span></span></p></td>
<td><p><span data-ttu-id="cf55f-114">Primary</span><span class="sxs-lookup"><span data-stu-id="cf55f-114">Primary</span></span></p></td>
<td><p><span data-ttu-id="cf55f-115">标识服务器的唯一号码。</span><span class="sxs-lookup"><span data-stu-id="cf55f-115">Unique number identifying the server.</span></span></p></td>
</tr>
<tr class="even">
<td><p><span data-ttu-id="cf55f-116"><strong>FQDNOrIP</strong></span><span class="sxs-lookup"><span data-stu-id="cf55f-116"><strong>FQDNOrIP</strong></span></span></p></td>
<td><p><span data-ttu-id="cf55f-117">nvarchar(256)</span><span class="sxs-lookup"><span data-stu-id="cf55f-117">nvarchar(256)</span></span></p></td>
<td><p><span data-ttu-id="cf55f-118">食指</span><span class="sxs-lookup"><span data-stu-id="cf55f-118">index</span></span></p></td>
<td><p><span data-ttu-id="cf55f-119">MAC 地址字符串。</span><span class="sxs-lookup"><span data-stu-id="cf55f-119">MAC address string.</span></span></p></td>
</tr>
<tr class="odd">
<td><p><span data-ttu-id="cf55f-120"><strong>ServerType</strong></span><span class="sxs-lookup"><span data-stu-id="cf55f-120"><strong>ServerType</strong></span></span></p></td>
<td><p><span data-ttu-id="cf55f-121">int</span><span class="sxs-lookup"><span data-stu-id="cf55f-121">int</span></span></p></td>
<td><p><span data-ttu-id="cf55f-122">外表</span><span class="sxs-lookup"><span data-stu-id="cf55f-122">Foreign</span></span></p></td>
<td><p><span data-ttu-id="cf55f-123">1：中介服务器</span><span class="sxs-lookup"><span data-stu-id="cf55f-123">1: Mediation Server</span></span></p>
<p><span data-ttu-id="cf55f-124">2： a/V 会议 Server16394： A/V 边缘 service32769： Gateway</span><span class="sxs-lookup"><span data-stu-id="cf55f-124">2: A/V Conferencing Server16394: A/V Edge service32769: Gateway</span></span></p></td>
</tr>
<tr class="even">
<td><p><span data-ttu-id="cf55f-125"><strong>PoolName</strong></span><span class="sxs-lookup"><span data-stu-id="cf55f-125"><strong>PoolName</strong></span></span></p></td>
<td><p><span data-ttu-id="cf55f-126">nvarchar (512) </span><span class="sxs-lookup"><span data-stu-id="cf55f-126">nvarchar(512)</span></span></p></td>
<td></td>
<td><p><span data-ttu-id="cf55f-127">服务器所属的池。</span><span class="sxs-lookup"><span data-stu-id="cf55f-127">Pool the server belongs to.</span></span> <span data-ttu-id="cf55f-128">仅适用于 A/V 会议服务器。</span><span class="sxs-lookup"><span data-stu-id="cf55f-128">Only applicable for the A/V Conferencing Server.</span></span></p></td>
</tr>
<tr class="odd">
<td><p><span data-ttu-id="cf55f-129"><strong>NextUpdateTS</strong></span><span class="sxs-lookup"><span data-stu-id="cf55f-129"><strong>NextUpdateTS</strong></span></span></p></td>
<td><p><span data-ttu-id="cf55f-130">datetime</span><span class="sxs-lookup"><span data-stu-id="cf55f-130">datetime</span></span></p></td>
<td></td>
<td><p><span data-ttu-id="cf55f-131">仅供内部使用。</span><span class="sxs-lookup"><span data-stu-id="cf55f-131">For internal use only.</span></span></p></td>
</tr>
</tbody>
</table><span data-ttu-id="cf55f-132">


</div>

<span> </span>

</div>

</div>

</span><span class="sxs-lookup"><span data-stu-id="cf55f-132">


</div>

<span> </span>

</div>

</div>

</span></span></div>

