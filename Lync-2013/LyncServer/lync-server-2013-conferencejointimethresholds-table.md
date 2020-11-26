---
title: Lync Server 2013： ConferenceJoinTimeThresholds 表
description: Lync Server 2013： ConferenceJoinTimeThresholds 表。
ms.reviewer: ''
ms.author: v-lanac
author: lanachin
f1.keywords:
- NOCSH
TOCTitle: ConferenceJoinTimeThresholds table
ms:assetid: 3944d724-bdd8-4d1c-a2af-933ee8141529
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ204809(v=OCS.15)
ms:contentKeyID: 48183855
ms.date: 07/23/2014
manager: serdars
mtps_version: v=OCS.15
ms.openlocfilehash: 5e38c8b99f444e16309882b6a8885d166fdceb9b
ms.sourcegitcommit: 36fee89bb887bea4f18b19f17a8c69daf5bc423d
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 11/26/2020
ms.locfileid: "49434457"
---
# <a name="conferencejointimethresholds-table-in-lync-server-2013"></a><span data-ttu-id="f1556-103">Lync Server 2013 中的 ConferenceJoinTimeThresholds 表</span><span class="sxs-lookup"><span data-stu-id="f1556-103">ConferenceJoinTimeThresholds table in Lync Server 2013</span></span>

<div data-xmlns="http://www.w3.org/1999/xhtml">

<div class="topic" data-xmlns="http://www.w3.org/1999/xhtml" data-msxsl="urn:schemas-microsoft-com:xslt" data-cs="https://msdn.microsoft.com/">

<div data-asp="https://msdn2.microsoft.com/asp">



</div>

<div id="mainSection">

<div id="mainBody"><span data-ttu-id="f1556-104">

<span> </span></span><span class="sxs-lookup"><span data-stu-id="f1556-104">

<span> </span></span></span>

<span data-ttu-id="f1556-105">_**主题上次修改时间：** 2012-09-28_</span><span class="sxs-lookup"><span data-stu-id="f1556-105">_**Topic Last Modified:** 2012-09-28_</span></span>

<span data-ttu-id="f1556-106">ConferenceJoinTimeThresholds 表包含 "会议加入时间摘要" 报表使用的分类边界。</span><span class="sxs-lookup"><span data-stu-id="f1556-106">The ConferenceJoinTimeThresholds table contains the classification boundaries used by the Conference Join Time Summary Report.</span></span> <span data-ttu-id="f1556-107">"会议加入时间摘要" 报表汇总了用户成功加入会议所需的时间量;这些时间值以平均值和以下类别之一报告：</span><span class="sxs-lookup"><span data-stu-id="f1556-107">The Conference Join Time Summary Report summarizes the amount time required for users to successfully join a conference; these time values are reported both as an average and in one of the following categories:</span></span>

  - <span data-ttu-id="f1556-108">不到2秒。</span><span class="sxs-lookup"><span data-stu-id="f1556-108">Less than 2 seconds.</span></span>

  - <span data-ttu-id="f1556-109">介于2秒和5秒之间。</span><span class="sxs-lookup"><span data-stu-id="f1556-109">Between 2 second and 5 seconds.</span></span>

  - <span data-ttu-id="f1556-110">介于5秒和10秒之间。</span><span class="sxs-lookup"><span data-stu-id="f1556-110">Between 5 seconds and 10 seconds.</span></span>

  - <span data-ttu-id="f1556-111">10秒以上。</span><span class="sxs-lookup"><span data-stu-id="f1556-111">More than 10 seconds.</span></span>

<span data-ttu-id="f1556-112">ConferenceJoinTimeThresholds 表包含分类值2秒、5秒和10秒钟。</span><span class="sxs-lookup"><span data-stu-id="f1556-112">The ConferenceJoinTimeThresholds table contains the classification values 2 seconds, 5 seconds, and 10 seconds.</span></span>

<span data-ttu-id="f1556-113">此表是在 Microsoft Lync Server 2013 中引入的。</span><span class="sxs-lookup"><span data-stu-id="f1556-113">This table was introduced in Microsoft Lync Server 2013.</span></span>


<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="f1556-114">列</span><span class="sxs-lookup"><span data-stu-id="f1556-114">Column</span></span></th>
<th><span data-ttu-id="f1556-115">数据类型</span><span class="sxs-lookup"><span data-stu-id="f1556-115">Data Type</span></span></th>
<th><span data-ttu-id="f1556-116">键/索引</span><span class="sxs-lookup"><span data-stu-id="f1556-116">Key/Index</span></span></th>
<th><span data-ttu-id="f1556-117">详细信息</span><span class="sxs-lookup"><span data-stu-id="f1556-117">Details</span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><span data-ttu-id="f1556-118"><strong>ThresholdId</strong></span><span class="sxs-lookup"><span data-stu-id="f1556-118"><strong>ThresholdId</strong></span></span></p></td>
<td><p><span data-ttu-id="f1556-119">int</span><span class="sxs-lookup"><span data-stu-id="f1556-119">int</span></span></p></td>
<td><p><span data-ttu-id="f1556-120">Primary</span><span class="sxs-lookup"><span data-stu-id="f1556-120">Primary</span></span></p></td>
<td><p><span data-ttu-id="f1556-121">分类的唯一标识符。</span><span class="sxs-lookup"><span data-stu-id="f1556-121">Unique identifier for the classification.</span></span></p></td>
</tr>
<tr class="even">
<td><p><span data-ttu-id="f1556-122"><strong>ThresholdValue</strong></span><span class="sxs-lookup"><span data-stu-id="f1556-122"><strong>ThresholdValue</strong></span></span></p></td>
<td><p><span data-ttu-id="f1556-123">int</span><span class="sxs-lookup"><span data-stu-id="f1556-123">int</span></span></p></td>
<td></td>
<td><p><span data-ttu-id="f1556-124">分类的上限。</span><span class="sxs-lookup"><span data-stu-id="f1556-124">Upper limit for the classification.</span></span> <span data-ttu-id="f1556-125">允许的值包括：</span><span class="sxs-lookup"><span data-stu-id="f1556-125">Allowed values are:</span></span></p>
<ol>
<li><p><span data-ttu-id="f1556-126">2</span><span class="sxs-lookup"><span data-stu-id="f1556-126">2</span></span></p></li>
<li><p><span data-ttu-id="f1556-127">5</span><span class="sxs-lookup"><span data-stu-id="f1556-127">5</span></span></p></li>
<li><p><span data-ttu-id="f1556-128">10</span><span class="sxs-lookup"><span data-stu-id="f1556-128">10</span></span></p></li>
</ol></td>
</tr>
</tbody>
</table><span data-ttu-id="f1556-129">


</div>

<span> </span>

</div>

</div>

</span><span class="sxs-lookup"><span data-stu-id="f1556-129">


</div>

<span> </span>

</div>

</div>

</span></span></div>

